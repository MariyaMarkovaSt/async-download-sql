# async-download-sql

**Library usage**: 
- pandas
- os
- sys
- concurrent.futures -> for async reading sql scripts in code
- sqlalchemy -> connection to personal engine to database
- time -> to show how much code will work
  
**Overview**
This project is designed to provide a robust and efficient way to asynchronously read multiple SQL scripts using Python's concurrent.futures.ThreadPoolExecutor and as_completed methods. The primary goal is to enhance data processing speed by leveraging concurrent execution, making it ideal for handling large datasets or numerous SQL queries.

**Key Features**

Asynchronous SQL Script Reading: 

Utilize ThreadPoolExecutor and as_completed to execute SQL scripts concurrently, significantly reducing the time needed to process multiple scripts.

__Dynamic Path Management:__ 

Implement sys and os modules to create dynamic paths, ensuring compatibility across different disk locations. 
This flexibility allows users to run the project from any directory without worrying about path configurations.

Automated Excel Export: 

After processing, all SQL query outputs are consolidated and automatically exported into an Excel file, streamlining data analysis and reporting.

Why Use This Project?

Whether you're a data engineer, analyst, or developer, this project simplifies the complexities involved in managing multiple SQL scripts and paths. 
It ensures efficient resource utilization, reduces execution time, and provides an easy-to-use output format for further data manipulation or presentation.
