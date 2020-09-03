

# Connect VS Code to PostgreSQL 
Visual Studio Code (VS Code) is a very pwoerful IDE used by Windows and Mac users alike. These instructions were created on a Mac, so slight variations may exist for Windows users.

Steps:
1. Install the PostgreSQL extension in VS Code.
2. Connect to the Server
3. Write a query 

## 1. Installing PostgreSQL
Open VScode open the Extensions in the left panel and search for PostgreSQL. Select the one authored by Chris Kolkman, click the green install button.

![](https://raw.githubusercontent.com/AVJdataminer/Formats/master/images/image1.png)



![enter image description here](https://raw.githubusercontent.com/AVJdataminer/Formats/master/images/image2.png)


## 2. Connect to the Thinkful Server

1) Open the Command Palette (Ctrl + Shift + P) in VS Code.

2) Search and select 'PostgreSQL: Add Connection'

![enter image description here](https://raw.githubusercontent.com/AVJdataminer/Formats/master/images/image3.png)

In the command palette, follow the prompts filing in the connection details for the Postgres server connection, including:  instance's hostname, database, username, and password:  
	-   **Host name/address:**  142.93.121.174
	-   **Port:**  5432
	-   **Username:**  dabc_student
	-   **Password:**  7*.8G9QH21

Once you're connected you will see the connection deatils on the left sidebar in VS code. Click on the Elephant Postgres database icon and you will see thr hostname and address with an expandable arrow. You can exapnad each of the databases as you would in any server connection tool to investigate the tables and their attributes as 

![enter image description here](https://raw.githubusercontent.com/AVJdataminer/Formats/master/images/image4.png)

## 3. Write a query
Type this query into the new SQL script in VS Code to confirm you're connected 
   
`SELECT * FROM pg_stat_activity;` 

Highlight the query and Right-click, select 'Execute Query' and the results will show in a new window in VS Code.
![execute qry](https://raw.githubusercontent.com/AVJdataminer/Formats/master/images/exe_q1_image.png)

You can save queries as SQL files and the query results as JSON, csv or Excel.

---

In case you need it here is the [Install link]( https://marketplace.visualstudio.com/items?itemName=ms-ossdata.vscode-postgresql).



<!--stackedit_data:
eyJoaXN0b3J5IjpbMTcxOTM5MTI0OCwtOTk0MDc1MzQ1LDE5Mj
I4NzA1NjcsMTczMDIyMTAyOSwxNjI2OTI2MzAzLDExNjE0ODcw
OSw2MDg0MDc3OSwtMTkwMDkyOTc0MSwxMTcwNzc5NDkwLC0xND
ExNDU1NTU4LDI4MTQ1NzgzMF19
-->