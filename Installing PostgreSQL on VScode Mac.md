

# Connect VS Code to PostgreSQL on a Mac

| ![enter image description here](https://raw.githubusercontent.com/AVJdataminer/Formats/master/images/1200px-Visual_Studio_Code_1.35_icon_125px_thumb.jpg) |  ![enter image description here](https://raw.githubusercontent.com/AVJdataminer/Formats/master/images/postgresql_icon_125px_thumb.jpg)|
|--|--|

Visual Studio Code (VS Code) is a very powerful IDE used by Windows and Mac users alike. These instructions are specific for a Mac, so slight variations may exist for Windows users.

Prerequisites: [Microsoft VS Code](https://code.visualstudio.com/?wt.mc_id=vscom_downloads) installed and running on your machine.

Steps:
1. Install the [PostgreSQL Extension](https://marketplace.visualstudio.com/items?itemName=ckolkman.vscode-postgres) in VS Code
2. Connect to the Server
3. Write a query 

## 1. Installing PostgreSQL
Open VScode click on the Extensions in the left panel and search for PostgreSQL. Select the extension authored by Chris Kolkman, click the green install button.

![enter image description here](https://raw.githubusercontent.com/AVJdataminer/Formats/master/images/image2.png)

Once you have sucessfully installed the green button will change to 'uninstall' or 'disable'. Now you're ready to connect to the thinkful server.

## 2. Connect to the Thinkful Server

1) Open the Command Palette (Ctrl + Shift + P) in VS Code.

2) Type 'PostgreSQL' in front of the carrot, and select 'PostgreSQL: Add Connection' when it shows up in the list. Then the command palette will start prompting you for the connection information. Follow the settings listed below to establish your server connection.

![enter image description here](https://raw.githubusercontent.com/AVJdataminer/Formats/master/images/image3.png)

3) Add the hostname of the database: **Host name/address:**  142.93.121.174  and press enter  
![add_database](https://raw.githubusercontent.com/AVJdataminer/Formats/master/images/add_database.png)

4) Add the user to authenticate: **Username:**  dabc_student and press enter
![user](https://raw.githubusercontent.com/AVJdataminer/Formats/master/images/user.png)
5) Type the **Password:**  7*.8G9QH21 and press enter 
![pw](https://raw.githubusercontent.com/AVJdataminer/Formats/master/images/pw.png)  
6) Enter the **port number:**  5432  
![pn](https://raw.githubusercontent.com/AVJdataminer/Formats/master/images/pn.png)
7) Select Secure Connection and Select Show All Databases
![secure](https://raw.githubusercontent.com/AVJdataminer/Formats/master/images/secure.png)
![show](https://raw.githubusercontent.com/AVJdataminer/Formats/master/images/show.png)
8) Press enter to confirm the display name of the database

You may be asked to for your Mac password to allow access to your Keychain. Enter your password and select Always Allow.  
![keychain](https://raw.githubusercontent.com/AVJdataminer/Formats/master/images/keychain.png)

Once you're connected you will see the connection details on the left sidebar in VS code. If you don't see the connection in your left table of contents, click on the Elephant Postgres database icon to show the hostname and address with an expandable arrow. You can expand each of the databases as you would in any server connection tool to investigate the tables and their attributes as well. For example if you click on the 'people' table inside the 'baseball' database you can see the name of each field and the data type of each field as well.  

![explore tables image](https://raw.githubusercontent.com/AVJdataminer/Formats/master/images/image7.png) 

## 3. Write a query
Click on the 'baseball' database to show the public tables, click on public to list those tables. Now, if you right click on the 'salaries' table you choose 'Select Top 1000' from the menu and a new query is generated. Highlight the query and Right-click, select 'Execute Query' and the results will show in a new window in VS Code.

![execute query image](https://raw.githubusercontent.com/AVJdataminer/Formats/master/images/image6.png)

You can also select 'New Query' and write your own, remember to execute you need to highlight the text, right-click and select run query. You can save queries as SQL files and the query results as JSON, csv or Excel.

---

You can easily add additional connections by clicking on the plus sign to the right of 'POSTGRESQL EXPLORER:' For more instructions and demos you can visit the [extension website](https://marketplace.visualstudio.com/items?itemName=ckolkman.vscode-postgres).  Microsoft does have their own authored extension, but it has more limited capabilities for connecting to and exploring Postgres servers.
