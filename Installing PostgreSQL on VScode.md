


Vscode is very pwoerful IDE used by Windows and Mac lovers alike. These instructions were created for Mac users. 
Steps:
1. Install the PostgreSQL add on in VSCode.
2. Connect to the server
3. Write a query and get some data

## 1. Installing PostgreSQL
Open VScode open the Extensions in the left panel and search for PostgreSQL. Select the one authored by Microsoft, click the green install button.

![relative image link](images/image1a.png)

Install link: https://marketplace.visualstudio.com/items?itemName=ms-ossdata.vscode-postgresql 

## 2. Connect to the Thinkful Server

1) Open the Command Palette (Ctrl + Shift + P) in VScode.

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

You can save the query results to JSON, csv or Excel.



<!--stackedit_data:
eyJoaXN0b3J5IjpbMTYyNjkyNjMwMywxMTYxNDg3MDksNjA4ND
A3NzksLTE5MDA5Mjk3NDEsMTE3MDc3OTQ5MCwtMTQxMTQ1NTU1
OCwyODE0NTc4MzBdfQ==
-->