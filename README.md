# 3D Visualization Order Management System — Backend

## Overview

This repository contains the backend component of a web-based 3D visualization order management system.

The backend supports communication between the frontend application and the server-side functionality required for managing visualization orders.

## Key Responsibilities

- **Order Management:** Supporting the management of visualization orders.
- **Order Status Updates:** Handling server-side operations related to order progress.
- **Email Notifications:** Supporting notifications when new orders are submitted.
- **Project Management:** Supporting the presentation of completed visualization projects.
- **Customer Interactions:** Supporting relevant customer-facing functionality.

## Technologies

- C#
- .NET

## Architecture

The project follows a layered structure, with separate areas for API operations, business logic, data access, and presentation-related functionality.

This separation helps organize responsibilities and makes the application easier to maintain.

## Frontend Integration

The frontend application is maintained in a separate repository:

[SimulationProjectAngular — Frontend Repository](https://github.com/RikiGiberstien/SimulationProjectAngular)

The frontend provides the user interface, while this repository contains the server-side implementation.

## Getting Started

### Prerequisites

- The .NET SDK version required by the solution
- Visual Studio or another compatible development environment

### Setup

1. Clone the repository.
2. Open the solution file in Visual Studio.
3. Restore the required dependencies.
4. Configure the required local settings and database connection.
5. Run the backend using the development instructions appropriate for the solution.

**Note:** Do not commit passwords, API keys, connection strings containing credentials, or confidential business information.

## Project Goal

The goal of this project is to support an organized workflow for visualization orders, from order submission and status tracking to the management and presentation of completed projects.
