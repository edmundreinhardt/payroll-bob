# demo payroll program
This sample program illustrates the use of https://github.com/IBM/ibmi-bob


Maintains all of the SQL tables for running the payroll.

Will generate the programs and DSPFs to the library referenced by the &pgmlib environment variable.
The source for this top layer of the program is found in the root directory of the project.

Will generate the datbase tables and views to the library referenced by the &dtalib environment variable.
The source and make rules for the database layer is found in the 'data' subdirectory.

Include files are automatically discovered in the 'includes' directory .
