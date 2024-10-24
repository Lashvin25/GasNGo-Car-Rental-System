# GasNGo Car Rental System

## Overview
GasNGo is a car rental system designed to provide easy and convenient rental services to Malaysian customers. The system supports three user roles: Superuser, Admin, and Customer. Each role has distinct functionalities, such as managing cars, customers, and bookings for Admins, and booking and managing profiles for Customers. The system is built using Java and follows object-oriented principles with modular architecture.

## Features
- **Superuser**:
  - Manage Admins: Add, edit, or remove Admin profiles.
  
- **Admin**:
  - Manage Cars: Add, update, delete car records.
  - Manage Customers: View, edit, or remove customer details.
  - Manage Bookings: Approve or decline car bookings.
  - Generate Receipts: Create receipts for completed payments.
  - Update Profile: Admin can update their account details and passwords.

- **Customer**:
  - Book Cars: Select available cars, view pricing, and confirm bookings.
  - Manage Profile: Update personal information and change passwords.
  - View Booking History: Review booking details, return cars, and generate payment receipts.

## System Assumptions
- Available to Malaysians only.
- Payments accepted in MYR (Malaysian Ringgit) only.
- Each car can be rented for a minimum of 24 hours.
- Admins manually set car availability.
- Late returns are penalized, and customers must pay fines accordingly.

## Architecture
The system is built following Object-Oriented Programming principles with features such as:
- **Classes and Objects**: Modular design with classes representing users, cars, and bookings.
- **Encapsulation**: Data and methods are bundled together for secure management of car and customer details.
- **Inheritance**: Admins inherit common functionalities from the user base class.
- **Polymorphism**: Methods for handling different types of users (Superuser, Admin, Customer).
- **Abstraction**: Key functionalities are exposed while unnecessary details are hidden.

## Tools Used
- **Java**: Core programming language.
- **Apache NetBeans**: Integrated Development Environment (IDE) for development.
- **Text Files**: Used for data storage of user, car, and booking details.

## UML Diagrams & Use Case Diagrams
The project includes UML diagrams that illustrate the class structure, and use case diagrams that show how different users interact with the system.

## How to Run
1. Open the project in **Apache NetBeans**.
2. Ensure the required text files are present for data storage (e.g., car details, user profiles).
3. Run the project and log in as one of the three roles (Superuser, Admin, Customer).
4. Follow the respective use case to manage cars, customers, or bookings.
