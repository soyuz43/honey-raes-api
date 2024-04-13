# Database for Honey-Rae Repairs

## Overview
This repository houses the database files for the Honey-Rae Repairs application. It includes JSON data representing users, customers, employees, service tickets, and related entities that support the operational logic of the Honey-Rae Repairs system.

## Purpose
The purpose of this repository is to maintain the data models and sample data in a separate location from the main application codebase. This allows for easier updates, management, and version control of the data structure used across the development and production environments.

## Structure
- **users**: Contains user profiles including staff and customer distinctions.
- **customers**: Details on customer addresses and contact information.
- **employees**: Information on employee specialties and rates.
- **serviceTickets**: Records of service requests and statuses.
- **employeeTickets**: Assignments of employees to specific service tickets.

## Integration with Main Application
This database directly supports the [Honey-Rae Repairs main application](https://github.com/soyuz43/honey-rae-repairs), which utilizes this data for all operational functionalities from managing service tickets to handling user information.

## Using This Repository
To use this repository in conjunction with the main application:
1. Clone this repository.
2. Import the `database.json` file into your local development environment or a suitable database management system that supports JSON.
3. Configure the main application to point to where this database is hosted or loaded locally.

## Contributions
As this is a critical part of the Honey-Rae Repairs infrastructure, changes to this repository should be carefully considered. For suggestions or modifications, please raise an issue or submit a pull request to the [main application repository](https://github.com/soyuz43/honey-rae-repairs).