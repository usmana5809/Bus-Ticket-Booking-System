# Bus-Ticket-Booking-System
This project is a comprehensive bus ticket booking and management system developed in C++. It allows users to book bus tickets, manage passenger details, and includes administrative functions for bus and ticket management.
Bus Reservation System
# Project Overview
The Bus Reservation System is a console-based application written in C++ that allows users to book bus tickets, manage bus details, and view booking information. It provides functionalities for both administrators and passengers.

# Features
Administrator Functions:
Add new buses with details like bus number, driver name, arrival/departure times, source, and destination.
Manage seat allotment and availability.
Display buses and their availability.
Passenger Functions:
Book tickets for available buses.
Display booked tickets.
Calculate fares including optional insurance costs.

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/your_username/bus-reservation.git
    ```
2. Navigate to the project directory:
    ```sh
    cd bus-reservation
    ```
3. Compile the code using a C++ compiler:
Compile the C++ files using your preferred compiler (e.g., g++)
    ```sh
    g++ main.cpp -o main
    ```
4. Run the executable:
    ```sh
    ./main
    ```
# Usage
# 1.Administrator Mode:
 - Log in with appropriate credentials.
 - Use the menu to manage buses (add, view, etc.).
# 2.Passenger Mode:
- Book a ticket by selecting available buses.
- View booked tickets and fare details.

# Example Outputs
Adding a Bus
Enter bus no: 1234
Enter Driver's name: John Doe
Arrival time: 09:00 AM
Departure: 05:00 PM
From: CityA
To: CityB
Seats initialized.




# Booking a Ticket
Select the Bus No: 1234

----------------------------------------------------------------
Bus No || Source || Destination || Bus Name || Distance(KM) || Arr. time(Hrs) || Dept. time(Hrs) || Duration
----------------------------------------------------------------
1234   CityA   CityB       ABC Bus         100         09:00 AM         05:00 PM         8 hrs


# Displaying Booked Ticket
Booked Bus is ....

----------------------------------------------------------------
Bus No || Source || Destination || Bus Name || Distance(KM) || Arr. time(Hrs) || Dept. time(Hrs) || Duration
----------------------------------------------------------------
1234   CityA   CityB       ABC Bus         100         09:00 AM         05:00 PM         8 hrs




# Fare Calculation
Child fare: 500
Adult fare: 1000
Temporary fare: 1500

Want to take insurance (y/n)?
Rs 1/Km for child
Rs 2/Km for adult: y

Total fare: 1600



# Viewing Available Buses
Bus no: 1234
Driver: John Doe        Arrival time: 09:00 AM    Departure time: 05:00 PM
From: CityA             To: CityB



## Expected Output
- Users will interact with the system via a command-line interface.
- Menus will guide the user to perform various operations.
- Success and error messages will be displayed accordingly.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## Contact
For any questions or suggestions, please contact [usmanazulfiqar2001@gmail.com](mailto:usmanazulfiqar2001@gmail.com).


