# flightReservations_.maui_blazor

Flight Reservation App
Overview

The Flight Reservation App is a Blazor-based web application that allows users to search for flights and manage reservations. It provides functionalities for both flight searching and reservation management, making it easy for users to find and reserve flights based on their preferences.
Features
<br/>
 ![Home page](https://res.cloudinary.com/duk3olmgh/image/upload/v1722977417/flight_reservation_app1_pduagr.png)
 <br/> 
 ![Flight lookup page](https://res.cloudinary.com/duk3olmgh/image/upload/v1722977430/flight_reservation_app2_ckf7ls.png)
 <br/>
 ![Reservations page](https://res.cloudinary.com/duk3olmgh/image/upload/v1722977446/flight_reservation_app6_ngcxae.png)
 <br/>






Flight Finder

    Search Flights: Users can search for flights by entering origin, destination, and day of travel.
    View Flight Details: Display a list of flights matching the search criteria, including flight code, airline, origin, destination, day, available seats, and price.
    Select Flights: Users can select a flight from the search results to view more details.

Reservations

    Search Reservations: Users can search for reservations using reservation code, airline, and passenger name.
    View Reservations: Display a list of reservations matching the search criteria.
    Select Reservations: Users can select a reservation to view or modify details.

Reservation Management

    Create Reservations: Users can create new reservations by selecting a flight and entering passenger details (name and citizenship).
    Modify Reservations: Users can update existing reservations, including changing the passenger's name, citizenship, and reservation status.
    Save Changes: Reservations can be saved and updated, with changes reflected in the reservation list.

Technologies Used

    Blazor: For building the interactive user interface.
    C#: Backend logic and data handling.
    .NET MAUI: Integration with hybrid app functionalities.
    CSV File Handling: Import and export flight data from CSV files.

Getting Started

To get started with the Flight Reservation App, clone the repository and follow the instructions below to set up your development environment.
Prerequisites

    .NET SDK 6.0 or higher
    Blazor WebAssembly
    Visual Studio or any preferred C# IDE

Installation

    Clone the Repository:

    bash

git clone <repository-url>

Navigate to the Project Directory:

bash

cd flight-reservation-app

Run the Application:

bash

dotnet run

Access the App:
Open your browser and navigate to http://localhost:5000 to start using the app.
