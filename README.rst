.. -*- coding: utf-8 -*-

==================================================
 GenSASchema - Static SQLAlchemy Schema Generator
==================================================

TABLE OF CONTENTS
-----------------

1. Introduction
2. Development Status
3. Copyright and License
4. System Requirements
5. Installation
6. Documentation
7. Bugs
8. Author Information


INTRODUCTION
------------

GenSASchema is a static SQLAlchemy schema generator.


DEVELOPMENT STATUS
------------------

Alpha.


COPYRIGHT AND LICENSE
---------------------

Copyright 2010 - 2016
André Malo or his licensors, as applicable.

The whole package is distributed under the Apache License Version 2.0.
You'll find a copy in the root directory of the distribution or online
at: <http://www.apache.org/licenses/LICENSE-2.0>.


SYSTEM REQUIREMENTS
-------------------

You need at least python 2.7 or Python 3 starting with version 3.3.


INSTALLATION
------------

Using pip
~~~~~~~~~

$ pip install gensaschema


Using distutils
~~~~~~~~~~~~~~~

Download the package, unpack it, change into the directory

$ python setup.py install

The command above will install a new "gensaschema" package into python's
library path.

Additionally it will install the documentation. On unices it will be
installed by default into <prefix>/share/doc/gensaschema.

For customization options please study the output of

$ python setup.py --help


DOCUMENTATION
-------------

You'll find a user documentation in the docs/userdoc/ directory of the
distribution package. It is installed by default under
<prefix>/share/doc/gensaschema (e.g. /usr/share/doc/gensaschema). Further,
there's the code documentation, generated by epydoc
(<http://epydoc.sourceforge.net/>), which can be found in the docs/apidoc/
subdirectory.

The latest documentation is also available online at
<http://opensource.perlig.de/gensaschema/>.


BUGS
----

No bugs, of course. ;-)
But if you've found one or have an idea how to improve GenSASchema, feel free to
send a pull request on `github <https://github.com/ndparker/gensaschema>`_ or
send a mail to <gensaschema-bugs@perlig.de>.


AUTHOR INFORMATION
------------------

André "nd" Malo <nd@perlig.de>
GPG: 0x8103A37E


  If God intended people to be naked, they would be born that way.
                                                   -- Oscar Wilde
