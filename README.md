# TRAIN-OR-BUS-ROUTE-MANAGEMENT-SYSTEM.CPP
A Train or Bus Route Management System is software that organizes routes, schedules, vehicles, and drivers. It enables real-time tracking, efficient planning, and ticketing. Passengers get timely updates, while operators improve service reliability, reduce delays, and manage resources effectively.
A console-based Bus Management System developed in C++. The system helps manage bus operations like adding new buses, viewing available buses, booking seats, and cancelling tickets. It uses file handling to store data permanently so records are not lost after closing the program.
This project is designed to demonstrate **Object-Oriented Programming, File Handling, and Menu-Driven Programming** concepts in C++.
**Key Features**:
1. **Add New Bus** – Admin can add bus details including bus number, driver name, source, destination, departure time, and total seats.
2. **View All Buses** – Displays the complete list of buses with route details and number of seats available.
3. **Book Ticket** – Passengers can book a seat in a selected bus if seats are available. System updates the seat count automatically.
4. **Cancel Ticket** – Allows cancellation of booked tickets and updates seat availability in the record.
5. **Data Persistence** – All bus information is stored in a text file, so data remains saved even after the program is closed.
**How the System Works**:
1. The program displays a main menu with options to add, view, book, or cancel.
2. When a new bus is added, details are saved to `bus.txt`.
3. For booking or cancellation, the program reads all data, updates the specific bus record, and writes back to the file.
4. All operations are done through a simple text-based interface for easy use.
**Scope for Future Enhancement**:
1. Add passenger details with PNR number generation
2. Implement admin login and user login separately
3. Add search functionality by source and destination
4. Create a graphical interface using C++ graphics
5. Add date-wise booking and advanced fare calculation
