=================
 Release History
=================

2.1.1
=====

- Correct an `issue with the way database connections are managed
  <https://github.com/sphinx-contrib/sqltable/issues/18>`__ so that
  all content is read before the connection is closed. (contributed by
  `dopas21 <https://github.com/dopas21>`__)

2.1.0
=====

- Update SQLAlchemy integration to support (and require) 2.0 or
  higher. (contributed by `Gabriel Gaona
  <https://github.com/GabrielGaona>`__)

2.0.0
=====

- Drop python 2 support.
- Fix documentation build on readthedocs.org.

1.1.0
=====

- Use pbr for packaging.

1.0
===

- First public release.
