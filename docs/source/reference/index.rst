#########
Reference
#########

.. currentmodule:: dbdicom

.. warning::

   This reference guide presents the dbdicom version 0.3 API. This 
   replaces the v0.2 API which is no longer supported and will be 
   phased out.


This reference manual details functions, modules, and objects 
included in dbdicom, describing what they are and what they do.
All operations are available via a *functional* and an *object-oriented* 
API. 

The *functional API* is slightly more compact and easier to use 
but also a little slower as the index file of the database is read and 
written at each operation. 

For interactive use or when many operations are performed in rapid 
succession, such as in a loop, the *object-oriented API* may be 
preferable.


**************
Functional API
**************

Summarize the database
----------------------

.. autosummary::
   :toctree: ../api/
   :template: autosummary.rst

   print
   summary


Retrieve information entities
-----------------------------


.. autosummary::
   :toctree: ../api/
   :template: autosummary.rst

   patients
   studies
   series


Edit information entities
-------------------------

.. autosummary::
   :toctree: ../api/
   :template: autosummary.rst

   copy
   delete
   move

Reading DICOM
-------------

.. autosummary::
   :toctree: ../api/
   :template: autosummary.rst

   volume
   values
   pixel_data
   unique
   files

Writing DICOM
-------------

.. autosummary::
   :toctree: ../api/
   :template: autosummary.rst

   split_series
   write_volume
   edit


Import/export to other formats
------------------------------

.. autosummary::
   :toctree: ../api/
   :template: autosummary.rst

   to_nifti
   from_nifti


*******************
Object oriented API
*******************


.. autosummary::
   :toctree: ../api/
   :template: custom-class-template.rst
   :recursive:

   DataBaseDicom
  
   
