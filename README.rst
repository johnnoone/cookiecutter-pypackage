======================
cookiecutter-pypackage
======================

Cookiecutter template for a Python package. See https://github.com/johnnoone/cookiecutter.

* Free software: BSD license
* Vanilla testing setup with `nose` and `python setup.py test`
* Travis-CI_: Ready for Travis Continuous Integration testing
* Tox_ testing: Setup to easily test for Python 2.6, 2.7, 3.3
* Sphinx_ docs: Documentation ready for generation with, for example, ReadTheDocs_
* distutils2 ready with pbr_

Usage
-----

Generate a Python package project::

    cookiecutter https://github.com/johnnoone/cookiecutter-pypackage.git

Then:

* Create a repo and put it there.
* Add the repo to your Travis CI account.
* Add the repo to your ReadTheDocs account + turn on the ReadTheDocs service hook.
* Release your package the standard Python way. Here's a release checklist: https://gist.github.com/audreyr/5990987


Similar Cookiecutter Templates
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

* `audreyr/cookiecutter-pypackage`_: Initial cookie.

* `Nekroze/cookiecutter-pypackage`_: A fork of this with a PyTest test runner,
  strict flake8 checking with Travis/Tox, and some docs and `setup.py` differences.

* `tony/cookiecutter-pypackage`_: Fork with py2.7+3.3 optimizations. Flask/Werkzeug-style
  test runner, ``_compat`` module and module/doc conventions. See ``README.rst`` or
  the `github comparison view`_ for exhaustive list of additions and modifications.

.. _Travis-CI: http://travis-ci.org/
.. _Tox: http://testrun.org/tox/
.. _Sphinx: http://sphinx-doc.org/
.. _ReadTheDocs: https://readthedocs.org/
.. _`Nekroze/cookiecutter-pypackage`: https://github.com/Nekroze/cookiecutter-pypackage
.. _`tony/cookiecutter-pypackage`: https://github.com/tony/cookiecutter-pypackage
.. _github comparison view: https://github.com/tony/cookiecutter-pypackage/compare/audreyr:master...master
.. _`network`: https://github.com/audreyr/cookiecutter-pypackage/network
.. _`family tree`: https://github.com/audreyr/cookiecutter-pypackage/network/members
.. _`audreyr/cookiecutter-pypackage`: https://github.com/audreyr/cookiecutter-pypackage.git
.. _pbr: https://pypi.python.org/pypi/pbr
