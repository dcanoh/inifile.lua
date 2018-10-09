inifile.lua
===========

Inifile parser.

===============  ==========  ============== ====================================================================================
  platform          arch        version       build status
===============  ==========  ============== ====================================================================================
  ``Windows``      ``x86``      ``0.1``       .. image:: https://ci.appveyor.com/api/projects/status/tgol246fvwsdoq0o/branch/package.lide?svg=true
                                                       :target: https://ci.appveyor.com/project/dcanoh/lide-sql/branch/package.lide
===============  ==========  ============== ====================================================================================


instalación
^^^^^^^^^^^

Para instalar ésta libreria recomiendo utilizar la linea de comandos de lide, usando ``lide install``.

*Así todas las dependencias se instalarán automaticamente:*

``$ lide install inifile``



lua API
^^^^^^^

Basic usage functions.

inifile.parse ( string stringToParse )
	Create new Database object and connect using given sql driver.

inifile.parse_file ( string fileToParse )
	Executes the given SQL statement.
