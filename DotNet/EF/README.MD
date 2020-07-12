# EF - Useful Links

- DB Context
- Methodologies
- EF architecture
	- https://www.entityframeworktutorial.net/basics/how-entity-framework-works.aspx

- How EF works?
- Migration

- EFCore
	- https://www.entityframeworktutorial.net/efcore/entity-framework-core.aspx

- Data Annotations - Fluent API
	- Many to Many: https://www.entityframeworktutorial.net/code-first/configure-many-to-many-relationship-in-code-first.aspx

- SQL Commands
    - https://explainjava.com/dml-ddl-dcl-tcl-sql-commands/
	- DML
	- DDL
	- TCL

- SP
	- https://www.sqlservertutorial.net/sql-server-stored-procedures/stored-procedure-output-parameters/

- Functions
	- https://www.dotnettricks.com/learn/sqlserver/different-types-of-sql-server-functions
	- 
- SP vs Fns
	- https://www.dotnettricks.com/learn/sqlserver/difference-between-stored-procedure-and-function-in-sql-server#:~:text=The%20function%20must%20return%20a,be%20called%20from%20a%20Function.

- Unique key vs Primary Key
	- https://www.geeksforgeeks.org/difference-between-primary-key-and-unique-key/#:~:text=Primary%20key%20will%20not%20accept,generates%20the%20non%2Dclustered%20index.

- Clustered Index vs Non-clustered Index
	- https://stackoverflow.com/questions/91688/what-are-the-differences-between-a-clustered-and-a-non-clustered-index

- Other questions
	- Cursor
		- https://www.sqlservertutorial.net/sql-server-stored-procedures/sql-server-cursor/
	- Temp Tables
		- https://codingsight.com/introduction-to-temporary-tables-in-sql-server/ - # and ##
	- Custom data type
		- https://www.c-sharpcorner.com/article/create-user-defined-data-types/

- Connection strings
	- https://www.c-sharpcorner.com/code/3379/connection-strings-in-web-config-file-using-asp-net.aspx

- Deadlock:
	- https://www.google.com/search?rlz=1C1GCEU_enUS891US891&ei=MHvyXof6JsioytMP6420-AU&q=deadlocks+in+sql+server+example&oq=deadlocks+in+sql+server+example&gs_lcp=CgZwc3ktYWIQAzIGCAAQFhAeMgYIABAWEB4yBggAEBYQHjoHCAAQRxCwAzoCCABQnccEWODTBGDB1ARoAXAAeACAAasBiAHfBZIBAzUuMpgBAKABAaoBB2d3cy13aXo&sclient=psy-ab&ved=0ahUKEwiH0uvB95jqAhVIlHIEHesGDV8Q4dUDCAw&uact=5#kpvalbx=_fnvyXuaSBIHM1QHzqa3gCA38

- ADO.NET way of calling
	- https://stackoverflow.com/questions/2974154/what-is-the-difference-between-executescalar-executereader-and-executenonquery
	- ExecuteScalar - Returns single value
	- ExecuteNonQuery - I/U/D - #of rows effected
	- ExecuteReader - Select multiple
    - Reading:
        - Get SqlConnection by conn string
        - Open
        - SqlCommand(SP)
        - Set CommandType as SP
        - Add params to SqlCommand - name, value, SqlDbType
        - ExecuteReader - single
        - ExecuteDataSet - Tables[] - Rows
        - objSqlCon.Close();objSqlCon.Dispose();

    - Saving (CUD):
        - Get SqlConnection by conn string
        - Open
        - Begin Transaction
        - SqlCommand(SP)
        - Set CommandType as SP
        - Add params to SqlCommand - name, value, type
        - Datatable to pass multiple rows (SqlDbType.Structured, TypeName) or single row
            - Datatable ==> DataColumns ==> DataTable Rows
        - Pass as param to SP
        - ExecuteNonQuery(sqlCommand, sqlTrans)
        - objSqlCon.Close();objSqlCon.Dispose();

- SQL:
	- MERGE Table1 AS PC USING Table2 AS tvp_PC ON <condition>
		WHEN  MATCHED THEN ..
		WHEN NOT MATCHED THEN ..

    - BEGIN.. END
    - BEGIN TRY... END TRY.. BEGIN CATCH .. END CATCH..

- Table Partitioning: 
	- https://www.sqlshack.com/database-table-partitioning-sql-server/

