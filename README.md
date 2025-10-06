# Oracle-Database-Lab-PDB-and-OEM-Configuration
Oracle PDB and OEM Configuration
Oracle PDB and OEM Configuration Student Information

Name: Immaculate Mutarutwa 

Student ID: 27806

Course: PL/SQL

Assignment Title: Oracle PDB and OEM Configuration

Date: 06/10/2025

Overview of Tasks
This report summarizes the Oracle practical exercises focused on creating, managing, and monitoring pluggable databases using Oracle Database 21c Express Edition. The tasks were divided into three main activities:

Task 1: Create a new Pluggable Database (PDB)

Task 2: Create and delete a PDB

Task 3: Configure and access Oracle Enterprise Manager (OEM)

Task 1: Creating a New Pluggable Database (PDB)
A new pluggable database was created using the following name:

plsql_class2025db

The username was generated based on the naming convention:

Amos_plsqlauca_26973

A simple password was used for authentication. This database was successfully created and opened for use in classwork.

Screenshot:

<img width="588" height="215" alt="immaculate task1" src="https://github.com/user-attachments/assets/2d3292bb-fd19-4870-9be0-6233fa5548c7" />

PDB creation confirmation (attached).

Task 2: Creating and Deleting a PDB
For this task, another pluggable database was created following the format:

FirstTwoLettersOfName_to_delete_pdb_StudentID

Hence, the database name was:

am_to_delete_pdb_26973

After creating the PDB, it was successfully deleted to demonstrate proper lifecycle management.

Screenshot:

<img width="576" height="312" alt="Immaculate task 2 creation" src="https://github.com/user-attachments/assets/4015dc41-bf87-405b-ac34-2f9694e12e53" />


Creation confirmation (attached).

Screenshot:

<img width="689" height="321" alt="Immaculate task 2 deletion" src="https://github.com/user-attachments/assets/6bcdaf4c-70af-4f6b-987d-d0cbb0cd91b6" />

Deletion confirmation (attached).

Task 3: Oracle Enterprise Manager (OEM) Configuration
Oracle Enterprise Manager was accessed via:

https://localhost:5500/em

and logged in with administrative credentials.

The OEM dashboard displayed:

Database: XE (21.3.0.0.0 Express Edition)

Type: Single Instance (CDB with 1 PDB)

Metrics: CPU usage, memory allocation, and data storage

Schema visible: AMOS_PLSQ...

This confirms a successful configuration of OEM and database monitoring setup.

Screenshot:

<img width="1909" height="940" alt="Immaculate dashboard" src="https://github.com/user-attachments/assets/c807195d-01f4-4b16-be37-7948909c3e77" />

OEM Dashboard (attached).

Issues Encountered and Solutions Issue Cause Solution OEM not loading Listener not started Ran lsnrctl start PDB not opening automatically Database started in MOUNT mode Executed ALTER PLUGGABLE DATABASE ALL OPEN; Login failed Wrong username/password Re-entered correct credentials
Conclusion
All three tasks were successfully completed. The configuration demonstrates knowledge of Oracle container databases, pluggable database creation and deletion, and performance monitoring via OEM. This hands-on exercise reinforced practical Oracle administration concepts.




