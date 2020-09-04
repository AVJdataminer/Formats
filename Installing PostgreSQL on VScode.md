

# Connect VS Code to PostgreSQL 
Visual Studio Code (VS Code) is a very powerful IDE used by Windows and Mac users alike. These instructions are specific for a Mac, so slight variations may exist for Windows users.

Prerequisites: Microsoft VS Code installed and running on your machine.

Steps:
1. Install the PostgreSQL extension in VS Code.
2. Connect to the Server
3. Write a query 

## 1. Installing PostgreSQL
Open VScode click on the Extensions in the left panel and search for PostgreSQL. Select the extension authored by Chris Kolkman, click the green install button.

![](https://raw.githubusercontent.com/AVJdataminer/Formats/master/images/image1a.png)


![enter image description here](https://raw.githubusercontent.com/AVJdataminer/Formats/master/images/image2.png)

Once you have sucessfully installed the green button will change to 'uninstall' or 'disable'. Now you're ready to connect to the thinkful server.

## 2. Connect to the Thinkful Server

1) Open the Command Palette (Ctrl + Shift + P) in VS Code.

2) Type 'PostgreSQL' in front of the carrot, and select 'PostgreSQL: Add Connection' when it shows up in the list. Then the command palette will start prompting you for the connection information. Follow the settings listed below to establish your server connection.

![enter image description here](https://raw.githubusercontent.com/AVJdataminer/Formats/master/images/image3.png)

In the command palette, follow the prompts filing in the connection details for the Postgres server connection, including:  instance's hostname, database, username, and password:  
	-   **Host name/address:**  142.93.121.174
	-   **Port:**  5432
	-   **Username:**  dabc_student
	-   **Password:**  7*.8G9QH21

Once you're connected you will see the connection details on the left sidebar in VS code. If you done't see the connection in your left table of Click on the Elephant Postgres database icon and you will see thr hostname and address with an expandable arrow. You can exapnad each of the databases as you would in any server connection tool to investigate the tables and their attributes as well.

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
eyJoaXN0b3J5IjpbLTEwMTc3MjMzMTksLTI0NzQ4MDk5NSwxOD
MyMTczNzU4LC05OTQwNzUzNDUsMTkyMjg3MDU2NywxNzMwMjIx
MDI5LDE2MjY5MjYzMDMsMTE2MTQ4NzA5LDYwODQwNzc5LC0xOT
AwOTI5NzQxLDExNzA3Nzk0OTAsLTE0MTE0NTU1NTgsMjgxNDU3
ODMwXX0=
-->