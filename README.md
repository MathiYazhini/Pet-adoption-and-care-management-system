# Pet-adoption-and-care-management-system

📌 Problem Description

Animal shelters often struggle to manage pet records, adoption processes, and care schedules using manual methods. This leads to errors, loss of information, and inefficiency. The Pet Adoption and Care Management System aims to solve this by digitizing the workflow, allowing staff to add pets, register adopters, track adoptions, and maintain care routines. It ensures that pet data is secure, adoption processes are streamlined, and the shelter functions efficiently.

🔹 OOP Concepts Applied

Encapsulation – Private fields with getters/setters for Pet, Adopter, Staff, and CareSchedule.

Abstraction – Interfaces like AdoptionOperations to define methods (adoptPet(), returnPet()).

Inheritance – Base class Pet extended by Dog, Cat, Bird; base class User extended by Adopter and Staff.

Polymorphism – Overridden displayInfo() shows different details for each pet type or user role.

🎯 Key Roles in the System

Pet Management 🐕 – Add, update, and track available/adopted pets.

Adopter Management 👨‍👩‍👧 – Register adopters and maintain their adoption history.

Adoption Handling 📄 – Process adoptions, cancellations, and returns.

Care Scheduling ⏰ – Manage feeding, vaccination, and medical check-ups for pets.

⚙️ Technology Stack
Frontend (Console-Based UI)

Java Core – For console-based user interaction

Scanner Class – For input handling

Collections (ArrayList) – For temporary in-memory storage

Backend (Business Logic & Database):
JDBC (Java Database Connectivity) – To connect Java with SQL database
MySQL – To store pets, adopters, adoptions, and care schedules



##USE CASE DIAGRAM


                        +------------------+
                        |  Adopter (User)  |
                        +------------------+
                               |
      ---------------------------------------------------------
      |                                                       |
 [Register as Adopter]                                [View Available Pets]
      |                                                       |
 [Adopt Pet]                                           [Return Adopted Pet]


                        +------------------+
                        |   Admin / Staff  |
                        +------------------+
                               |
 -------------------------------------------------------------------------------
 |                |                     |                        |              |
[Add / Update /   |        [Manage      |       [Manage Pet      | [Approve /   |
 Delete Pet Info] |        Care         |       Records]         | Cancel       |
                  |        Schedules]   |                        | Adoption]    |
 -------------------------------------------------------------------------------

