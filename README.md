# VDM-Escape-Game

# Database Generation Script
This script generates mock data for a database used in an escape game application. It populates tables for establishments, scenarios, rooms, plannings, employees, clients, reviews, reservations, payments, pricing, communication logs.

## Data Generation

The script will generate the following data:

- 25 establishments
- 10 scenarios
- 1250 rooms (5 per establishment each having 10 possible scenarios)
- 1250 employees (10 per rooms per establishment = 50 per establishment)
- 5000 reviews
- 5000 logs
- 5000 reservations
- 5000 payments
- random pricings per participants

Each entity is generated with randomized data. Reservations are linked to clients, plannings, payments, pricing, reviews.


## Database Schema

The script will create the tables if they don't exist:

- Establishments
- Scenarios
- Rooms
- Plannings
- Clients
- Employees
- Payments
- Pricing
- CommunicationLogs
- Reservations
- Reviews

## Statistics Queries

Upon completion, the script will run a series of SQL queries to gather statistics about the generated data, such as the total number of reservations per room and average ratings.

