# Ticket-Booking-Application-Using-Go

This Go application is a simple booking system for a conference. Users can enter their personal information, such as first name, last name, email, and the number of tickets they want to book. The application checks the validity of the input, including the name length, email format, and the number of tickets available.

## Requirements
- Go programming language
- Microsoft Visual Studio Code

## Usage
1. Run the application in your terminal:


2. The application will prompt you to enter your first name, last name, email, and the number of tickets you want to book for the "Go Conference."

3. After entering the details, the application checks if the provided information is valid. If the data is valid, it books the tickets and adds the user's information to the list of bookings. It also displays the first names of all bookings made so far.

4. If the provided data is invalid, the application displays corresponding error messages.

5. If all tickets are booked (i.e., remaining tickets become zero), the application informs the user that the conference is fully booked and will end.

6. While booking tickets, the application also sends a ticket to the user's email after a simulated delay of 60 seconds (to mimic an asynchronous operation).

## Files
- `main.go`: The main file containing the Go application code.
- `helper.go`: A helper file containing the `validateUserInput()` function used for input validation.

## Structs
- `UserData`: A struct representing user data with fields for first name, last name, email, and the number of tickets booked.

## Functions
- `greetUsers()`: A function that displays a welcome message and the number of remaining tickets.
- `getUserInput()`: A function that reads and returns user input for first name, last name, email, and the number of tickets.
- `validateUserInput()`: A function that checks the validity of the user's input for first name, last name, email, and ticket number.
- `bookTickets()`: A function that books the tickets for the user and updates the list of bookings and remaining tickets.
- `sendTicket()`: A function that simulates sending a ticket to the user's email after a delay of 60 seconds.
- `getFirstNames()`: A function that retrieves the first names of all the bookings made so far.



