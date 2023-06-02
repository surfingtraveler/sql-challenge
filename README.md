# sql-challenge

This is an analysis to conduct a research project as assigned about people Pewlett Hackard employed during the 1980's and 1990's.  To conduct the analysis the steps taken are as follows:

Step 1 - Data Modeling:  An entity Relationship Diagram was created using quickdatabasediagrams.com.  Screenshot included and saved as ERD_Diagram.

Step 2 - Data Engineering:  Tables have been created in Postgres to hold 6 csv files creating a table schema.  The csv files have also been imported into the database Tables.  The file was saved as table_schema.sql.

Step 3 - Data Analysis: Queries ran to answer the following questions below.  The query file was saved as query.sql.  A screenshot was also included of each individual question with screenshot of the query results.  These are saved as .png files in a folder called query_results.

  List the employee number, last name, first name, sex, and salary of each employee.

  List the first name, last name, and hire date for the employees who were hired in 1986.

  List the manager of each department along with their department number, department name,     employee number, last name, and first name.

  List the department number for each employee along with that employee’s employee number,     last name, first name, and department name.

  List first name, last name, and sex of each employee whose first name is Hercules and whose   last name begins with the letter B.

  List each employee in the Sales department, including their employee number, last name, and   first name.

  List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.

List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name)
