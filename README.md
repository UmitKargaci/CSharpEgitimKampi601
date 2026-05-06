C# MongoDB Customer Management System
This project is a Customer Management System application developed using C# Windows Forms and integrated with MongoDB as the database. The application aims to perform basic CRUD (Create, Read, Update, Delete) operations on customer data.

🚀 About the Project
The application is a desktop solution where data is stored in MongoDB, a modern, flexible NoSQL database. A layered architecture approach has been adopted to enhance code maintainability and readability.

Core Features
List (Listele): View all customer records stored in MongoDB directly on the user interface.

Add (Ekle): Create and store new customer profiles.

Delete (Sil): Remove existing customers from the database using their unique ID.

Update (Güncelle): Edit and save modifications to existing customer details.

Get by ID (Id'ye Göre Getir): Fetch and view a specific customer's details instantly using their ID.

🛠 Tech Stack
Language: C# (.NET Framework)

UI Framework: Windows Forms

Database: MongoDB (NoSQL)

Driver: MongoDB.Driver (NuGet package)

📂 Project Structure
Entities/: Contains the model definitions mapping to the database collections.

Customer.cs: Defines the customer properties matching the MongoDB document structure (CustomerId, CustomerName, CustomerSurname, CustomerCity, CustomerBalance, CustomerShopping).

Services/:

MongoDbConnection.cs: Manages the database connection settings and client initialization.

CustomerOperations.cs: Contains the business logic and methods required for executing CRUD operations against MongoDB.

Form1.cs: Handles the user interface, event handling, and data binding to the data grid.

⚙️ Setup and Installation
Prepare MongoDB: Ensure that a local MongoDB instance or a MongoDB Atlas cloud cluster is running.

Configure Connection String: Open MongoDbConnection.cs and update the connection string settings with your server configuration.

Restore NuGet Packages: Make sure the MongoDB.Driver package is successfully restored via the Visual Studio NuGet Package Manager.

Build and Run: Open the solution in Visual Studio, build the solution, and start the application.

This project was developed as part of the C# BootCamp (C# Eğitim Kampı).

<img width="1147" height="446" alt="image" src="https://github.com/user-attachments/assets/144b8571-9fcb-4d20-abf6-862e96e0ef9f" />
