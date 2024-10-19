# Employee-Management-System

## Overview

The Employee Management System is a web application designed to efficiently manage employee data. This system allows administrators and employees to log in through role-based access and perform various operations based on their privileges. The system is developed using React for the frontend and Spring Boot for the backend, providing a comprehensive platform for managing employee records, including personal, professional, project, and financial details.

## Key Features

Role-Based Login

Admins and Employees must log in using their company email ID and password.
Upon verification, users are directed to either the Admin or Employee dashboard based on their role.
Admin Dashboard

Admins can view, add, update, and delete employee records.
Employee records include basic details like employment code, name, email, manager name, current project, and more.
Admins can manage all aspects of employee data, including personal, professional, project, and financial details.
Employee Dashboard

Employees can view their personal and professional details.
Employees can also download their monthly payslips.
Employee Records Management

Personal Details: Full name, date of birth, address, contact information, etc.
Professional Details: Employment code, office address, reporting manager, HR name, etc.
Project Details: Project code, project name, client details, and reporting manager.
Finance Details: PAN, Aadhar, bank details, and salary slips.

## Technology Stack

Frontend: React.js
Backend: Spring Boot
Database: MySQL

## Project Structure

Admin Features:

View all employee details
Add new employees
Update employee information
Delete employee records
View and generate employee payslips

Employee Features:

View personal and professional details
Download monthly payslips
