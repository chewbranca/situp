What is situp.py
========================================

situp.py originally started out as an attempt to write a simplified CouchApp
"client" that followed and reused the python distutils package, the idea being
that distutils would take care of lots of the heavy lifting (and provide a few
features "out of the box"). After a bit of tinkering it became fairly apparent
that a lot of code would be necessary to override distutils behaviour. So now
situp.py is just another CouchApp client.

Documentation
----------------------------------------

You can generate the situp.py documentation, using sphinx, by issuing the
following command:

    make -f docs/Makefile html