inifile.lua
===========

Inifile parser.

===============  ==========  ============== ====================================================================================
  platform          arch        version       build status
===============  ==========  ============== ====================================================================================
  ``Windows``      ``x86``      ``0.1``       .. image:: https://ci.appveyor.com/api/projects/status/tgol246fvwsdoq0o/branch/package.lide?svg=true
                                                       :target: https://ci.appveyor.com/project/dcanoh/lide-sql/branch/package.lide
===============  ==========  ============== ====================================================================================



installation
^^^^^^^^^^^^

To install this library I recommend using the command line of lide, using `` lide install``.

*Thus all the dependencies will be installed automatically:*

``$ lide install inifile``



lua API
^^^^^^^

Basic usage functions.

inifile.parse ( string stringToParse )
	Load string and return table.

inifile.parse_file ( string fileToParse )
	Load file and return table.
