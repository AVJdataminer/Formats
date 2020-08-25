

# Connect VS Code to PostgreSQL 
Visual Studio Code is very pwoerful IDE used by Windows and Mac lovers alike. These instructions were created for Mac users. 
Steps:
1. Install the PostgreSQL extension in VS Code.
2. Connect to the Server
3. Write a query 

## 1. Installing PostgreSQL
Open VScode open the Extensions in the left panel and search for PostgreSQL. Select the one authored by Microsoft, click the green install button.

![relative image link](images/image1a.png)

Install link: https://marketplace.visualstudio.com/items?itemName=ms-ossdata.vscode-postgresql 

## 2. Connect to the Thinkful Server

1) Open the Command Palette (Ctrl + Shift + P) in VS Code.

2) Search and select 'PostgreSQL: New Query'
![search_image](images/search_image.png)
3) In the command palette, select 'Create Connection Profile'.  
Use these connection details following the prompts to enter your Postgres instance's hostname, database, username, and password:
	-   **Host name/address:**  142.93.121.174
	-   **Port:**  5432
	-   **Username:**  dabc_student
	-   **Password:**  7*.8G9QH21

Once you're connected you will see the connection details at the bottom of your VS Code Window.
![connect image](images/connect_image.png)

4) Type this query into the new SQL script in VS Code to confirm `SELECT * FROM pg_stat_activity;`

5) Highlight the query and Right-click, select 'Execute Query' and the results will show in a new window.
![execute qry](images/exe_q1_image.png)
You can save the query results to JSON, csv or Excel.



<!--stackedit_data:
eyJoaXN0b3J5IjpbMTg2ODc4MTY4NCwxNjI2OTI2MzAzLDExNj
E0ODcwOSw2MDg0MDc3OSwtMTkwMDkyOTc0MSwxMTcwNzc5NDkw
LC0xNDExNDU1NTU4LDI4MTQ1NzgzMF19
-->