
# SingASong - ASP.NET Core MVC Application
This is an ASP.NET Core MVC application for a online music store, allowing users to browse through and purchase songs. The application is designed to have a modular architecture with multiple API services to handle various processes including Payment, Search Catalogue, Shopping Cart, Admin Processes. The application utilizes Entity Framework for data access and has connections to a MSSQL database server. 


## Technologies Used

ASP.NET 8 Core MVC: The framework used to build the web application.

Entity Framework: Used for data access and interacting with the database.

ASP.NET API Services: Modular APIs for specific functionalities (Shopping Cart, Payment, Admin, User, Catalogue).

MSSQL: The application is connected to a database server to store and retrieve data.
## Run Locally

Clone the project

```bash
  git clone https://github.com/WartanRM/MusicStores
```

Configure Database Connection:
```bash

Open the appsettings.json file.
Update the connection string in the ConnectionStrings section to point to your database.
json
Copy code
"ConnectionStrings": {
  "DefaultConnection": "your_database_connection_string"
}
```
Run Migrations:
```bash
Install SqlClient for Microsoft Entity Framework from NuGet Package Manager

https://www.nuget.org/packages/Microsoft.Data.SqlClient/5.1.5?_src=template
```

Build and run Application


## API Reference

Shopping Cart API: Manages the user's shopping cart and handles related operations.

Payment API: Handles payment processing for song purchases.

Admin API: Provides administrative functionalities for managing the music store.

User API: Manages user-related operations and authentication.

Catalogue API: Handles the catalog of available songs.


## Demo



Users must Register or Login to access the full functionality of the application.

Browse Catalogue:

Explore the available songs in the catalogue.

User Profile:

Users can access their profile and personal info and the purchased songs.

Add to Cart:

Add desired songs to the shopping cart.

Checkout:

Proceed to checkout to complete the purchase using the Payment API.

Contributing

Feel free to contribute to the project. Fork the repository and create a pull request with your changes.

## Snapshots
![alt text](<Screenshot (63).png>)
![alt text](<Screenshot (64).png>)
![alt text](<Screenshot (65).png>)
![alt text](<Screenshot (66).png>)


## License

This project is licensed under the SingASong.com License - see the LICENSE.md file for details.


## TEAM MEMBERS

Gokul Wartan R M

Sabbisetti Sri Sai Keerthi

Bade Nithin Sai Kumar Reddy
