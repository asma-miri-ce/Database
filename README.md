This project has been completed in two mandatory phases. Details of the work carried out in each phase can be found in the Revision History table.


The database consists of 35 tables in total.

CRUD operations have been implemented for all 35 tables. However, due to time constraints and the complexity of implementing all 35 tables, only 15 tables are accessible through the menu.

Three reports have also been implemented in the Reports section, covering only the 15 accessible tables.

The main operations menu provides various options. For example, in tables containing a status column, users can select from predefined status options. Similarly, columns that reference other tables and support configurable selection options have been implemented using dropdown selections.

Execution Instructions

The database schema can be executed without any special restrictions. The database name is FINAL.

To run the CRUD menu, navigate to the corresponding folder and execute the main.py file.

Important: Make sure to configure the server_name and the related settings in the database_config file as follows:

SERVER = "localhost"
DATABASE = "FINAL"
DRIVER = "{SQL Server}"

The same database_config settings must also be configured when running the reports.# Database
