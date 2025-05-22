# Java Bank Application – OOP Project

This is a console-based banking system project developed in Java. It demonstrates core Object-Oriented Programming (OOP) concepts like inheritance, interfaces, polymorphism, and abstraction.

---

## Table of Contents
- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [OOP Concepts Demonstrated](#oop-concepts-demonstrated)
- [Features](#features)
- [Class Design](#class-design)

---

## Overview

The **Bank Application** allows users to simulate common banking operations through a command-line interface. It supports:

- [Opening new bank accounts](#features)
- [Depositing and withdrawing funds](#features)
- [Viewing account details](#features)
- [Implementing different bank behaviors](#oop-concepts-demonstrated)

This project is ideal for understanding and applying core [OOP concepts](#oop-concepts-demonstrated) in Java using a hands-on, practical example.

---

## Technologies Used

- Java SE (Standard Edition)
- OOP principles (abstract classes, interfaces, inheritance, polymorphism)
- No external libraries or frameworks required

---

## OOP Concepts Demonstrated

This project demonstrates the following core object-oriented programming principles:

- **Abstraction**: 
  - `Bank` and `Account` are abstract classes representing core entities.
- **Inheritance**: 
  - `NationalizedBank` and `CooperativeBank` extend the `Bank` class.
- **Interfaces**: 
  - `AccountOperations` defines standard operations like deposit and withdraw.
- **Polymorphism**: 
  - Overridden methods in subclasses provide bank-specific behaviors.
- **Static and Final**: 
  - Used for constants and utility behavior where applicable.

---

## Features

- Open new accounts under different banks
- Deposit money into accounts
- Withdraw money from accounts
- View details of existing accounts
- Bank-specific functionality based on the type (Nationalized vs Cooperative)

---

## Class Design

- **Bank** – An abstract class defining common properties and methods across banks  
- **Account** – A base class that holds customer account information  
- **NationalizedBank / CooperativeBank** – Subclasses of `Bank` with customized behavior  
- **AccountOperations** – An interface that defines the structure of deposit, withdraw, and view operations  
- **Main** – Contains the main program logic and user interaction via the console  

---

Feel free to fork, clone, and run the project to explore and learn OOP principles in action!
