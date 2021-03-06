===================
 XRootDPyFS v0.1.5
===================

XRootDPyFS v0.1.5 was released on 2017-07-18.

About
-----

XRootDPyFS is a PyFilesystem interface to XRootD.

XRootD protocol aims at giving high performance, scalable fault tolerant access
to data repositories of many kinds. The XRootDPyFS adds a high-level interface
on top of the existing Python interface (pyxrootd) and makes it easy to e.g.
copy a directory in parallel or recursively remove a directory.


What's new
----------

- Fixes an issue where the xrootd response was not checked when closing
  a file. This could ultimately result in masking very important errors
  that could lead to silent data loss (such as not reporting that the
  server had a problem replicating the file and thus deleted the file).


Documentation
-------------

   https://xrootdpyfs.readthedocs.io/

Homepage
--------

   https://github.com/inveniosoftware/xrootdpyfs

Happy hacking and thanks for flying XRootDPyFS.

| Invenio Development Team
|   Email: info@inveniosoftware.org
|   Twitter: http://twitter.com/inveniosoftware
|   GitHub: http://github.com/inveniosoftware
|   URL: http://inveniosoftware.org
