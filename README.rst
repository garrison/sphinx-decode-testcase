sphinx-decode-testcase
======================

This is a repository made to demonstrate a bug in `Sphinx <https://github.com/sphinx-doc/sphinx>`_.

When `make linkcheck` is run under python 3, everything works.  However, if it is run under python 2, `this link <http://valgrind.org/docs/manual/manual-core.html#manual-core.suppress>`_ will fail with the message ``'utf8' codec can't decode byte 0xa0 in position 2625: invalid start byte``.
