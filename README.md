# Gari Dealership System 

This repository contains the first phase of the **Car Dealership System**, a Java project developed for the CSC 113 course during the second semester of 1445. The project aims to provide a comprehensive understanding of Java programming concepts, including inheritance, polymorphism, abstract classes, and array manipulation.

## Project Overview

The Car Dealership System is designed to simulate the management of a car dealership. It allows users to add, remove, sell, and edit vehicles within the dealership's inventory. The system also maintains a sales history to track all vehicle transactions.

## Project Structure

The project is structured into multiple Java classes:

1. **Vehicle**: An abstract class representing a generic vehicle with common attributes such as make, model, color, year, and price.
2. **Car**: A subclass of Vehicle, representing a car with additional attributes such as type.
3. **Motorcycle**: Another subclass of Vehicle, representing a motorcycle with specific attributes such as handlebar type.
4. **Dealership**: The main class handling dealership operations including managing inventory, sales, and displaying information.
5. **Sale**: A class representing a sale transaction, including details of the vehicle sold, buyer's name, contact, and sale date.
6. **Main**: The entry point of the program containing the main menu and user interaction functionalities.

## Functionality

The system provides the following functionalities:

- Displaying all vehicles in the inventory.
- Adding new vehicles (cars or motorcycles) to the inventory.
- Selling vehicles to customers and maintaining a sales history.
- Removing vehicles from the inventory.
- Editing vehicle information (make, model, color, year, price, type, handlebar type).
- Searching for cars by type.
- Finding cars within a specified budget.

## Usage
