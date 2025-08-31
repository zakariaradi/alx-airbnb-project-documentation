# Airbnb Clone Use Case Diagram

## Objective
The Use Case Diagram visualizes the interactions between the actors and the system for key functionalities in the Airbnb Clone project. It highlights how users, hosts, admins, and external systems interact with the platform.

## Actors
- **Guest/User**: Browses properties, registers, books, makes payments, writes reviews, and cancels bookings.
- **Host**: Lists and manages properties, views bookings, and accepts or rejects booking requests.
- **Admin**: Manages users, properties, and bookings.
- **Payment Gateway**: External system responsible for processing payments.

## Use Cases
### Guest/User
- Register / Login
- Search Properties
- View Property Details
- Book Property (includes Make Payment)
- Cancel Booking (extends Book Property)
- Write Review (extends Book Property)

### Host
- Register / Login
- List Property
- Update Property Details
- View Bookings
- Accept / Reject Booking

### Admin
- Manage Users, Properties, and Bookings

### Payment Gateway
- Process Payment

## Relationships
- **Association**: Direct interaction between actor and use case.
- **Include (`<<include>>`)**: Mandatory use of one use case by another (e.g., Book Property includes Make Payment).
- **Extend (`<<extend>>`)**: Optional behavior (e.g., Cancel Booking extends Book Property).

## Diagram
<img width="1536" height="1024" alt="ChatGPT Image Aug 31, 2025, 06_06_02 PM" src="https://github.com/user-attachments/assets/190783e3-8f8c-4b87-bd55-0f96a88e205a" />
