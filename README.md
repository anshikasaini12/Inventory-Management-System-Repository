Inventory Management System
This is an Inventory Management System built in the form of a GUI desktop application developed in Java using MySQL as its database. The GUI was designed using Swing and the database connectivity was managed using JDBC API.

This application can be used by any small to mid-sized stores to easily maintain and manage an inventory of all their-

Products
Customers
Suppliers
Users
Transactions
Features of the Application
Users can manage inventory and stock of all the products available in their store.

Users can manage all sales and purchase transactions made by the store.

Supports two user types:

Administrator
Employee
[Admins have the ability to manage all other personnel.]

Any transaction made automatically handles the stock availability in the inventory.

Each section includes a search feature to make it easier for users to view the data they want to see.

Users only need to enter the product code while making a sale and all the relevant details will be retrieved from the database automatically.

Maintains a time log of all the users using the application.

How to download and run the software
Minimum Requirements: JDK or JRE version 16.
Download and unzip the ZIP folder: InventoryManagement.zip

Download the SQL dump file: inventory DB

Import the SQL dump file using MySQL Workbench to locally create the sample schema and tables associated with this software.

After the inventory schema has been locally created, you can go ahead and run the JAR file (InventoryManagement.jar) included in the zip folder.

Default credentials for the connection to MySQL database is:

For Administrator
Username: root
Password: root
For Employee
Username: root
Password: root

Application Preview
Login Page
The login page takes in the credentials entered by the user and verifies with the database.
![image](https://github.com/anshikasaini12/Inventory-Management-System-Repository/assets/168024540/05ea36cb-79a8-4e94-99bf-bae0d295f49b)

Dashboard/Welcome Page
The landing page of the application after a successful login.
![image](https://github.com/anshikasaini12/Inventory-Management-System-Repository/assets/168024540/7a781a68-4046-4b18-be8f-0f45154ef2e6)

Products
The products section allows the user to add, edit and delete products from the store's inventory.
![image](https://github.com/anshikasaini12/Inventory-Management-System-Repository/assets/168024540/bdeb362e-2d35-4b5d-8d4e-7f9e1d1240d7)

Current Stock
This section allows the user to check the availability of every item.
![image](https://github.com/anshikasaini12/Inventory-Management-System-Repository/assets/168024540/a611c0a7-806e-4893-81d1-c72590b89b15)

Suppliers
Here, the user can manage and manipulate the record of all the suppliers associated with the store.
![image](https://github.com/anshikasaini12/Inventory-Management-System-Repository/assets/168024540/6e825a2f-6658-4246-a2f0-0c6b65ec48db)

Customers
Allows user to add new customers or update/delete existing customers in the database.
![image](https://github.com/anshikasaini12/Inventory-Management-System-Repository/assets/168024540/6bcff1d3-098f-4b2d-9dbb-51abd2c2476c)

Sales
This section is where users can sell a product and manage all the sales transactions. The user only needs to enter the customer and product code and the software will handle the rest, showing all the necessary details like available stock and selling price of the product.
![image](https://github.com/anshikasaini12/Inventory-Management-System-Repository/assets/168024540/e6b46e8b-f741-4efe-8722-bfda94a05975)

Purchase
This section is where users can view purchase logs and enter new purchase transactions. Similar to the sales section, this section only requires the user to enter the product code and the details that are already available in the database will immediately be displayed in the respective spaces.
![image](https://github.com/anshikasaini12/Inventory-Management-System-Repository/assets/168024540/f77d5539-1032-4176-b6fe-91ec76e5e83d)

Users
This section is only available to ADMINISTRATORS. It allows them to view, add and delete any users.
![image](https://github.com/anshikasaini12/Inventory-Management-System-Repository/assets/168024540/e716a584-3cfb-4fa8-843a-8a78315d9ae0)

User Logs
Stores and shows the administrator a log of all the users that have previously logged in, including their login time and logout time.
![image](https://github.com/anshikasaini12/Inventory-Management-System-Repository/assets/168024540/41cc798f-0118-4630-8f71-d06b7befca57)










