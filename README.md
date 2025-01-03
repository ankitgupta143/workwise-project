# Seat Reservation System

This project implements a train seat reservation system with the following features:

## Features
- **Coach Configuration**: One coach with 80 seats.
  - **Row Layout**: 7 seats in each row, except the last row with only 3 seats.
- **Seat Booking**:
  - A user can reserve up to 7 seats at a time.
  - Priority is given to book seats in the same row.
  - If seats are unavailable in one row, nearby seats are booked instead.
  - Users can continue booking tickets until the coach is fully reserved.
- **User Authentication**:
  - User login and signup functionality.
- **Seat Availability**:
  - Reserved seats cannot be booked by another user unless canceled or reset.

## Tech Stack
- **Frontend**: Next.js
- **Backend**: Node.js, Express.js
- **Database**: PostgreSQL

Feel free to use any npm package and platform for backend, frontend, and database deployment.

## Demo
For a detailed demonstration of the Project, watch the [demo video](#).

## Getting Started
### Prerequisites
Ensure you have the following installed:
- Node.js
- PostgreSQL

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/ankitgupta143/workwise-project.git
   cd workwise-project
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up the PostgreSQL database and configure the connection details in the backend.

### Running the Application
1. Start the backend server:
   ```bash
   npm run server
   ```
2. Start the frontend:
   ```bash
   npm run dev
   ```

### Usage
1. Sign up or log in to the application.
2. Reserve seats by specifying the number of seats (up to 7 per booking).
3. Manage your bookings, including canceling reservations.

## License
This project is licensed under the MIT License.
