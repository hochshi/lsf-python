LSF
===

A simple abstraction built on top of existing LSF SWIG bindings.


Usage
-----

Basic job submission:

::

    import lsf

    job = lsf.submit('ls -lh', options={'queue': 'testing'})


Installation
------------

Install https://github.com/IBMSpectrumComputing/lsf-python-api 

Then, simply install with pip:

::

    pip install lsf


Testing
-------

::

    pip install tox
    tox
