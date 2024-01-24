# Doctor's Planet - Hospital Management System

Doctor's Planet is a comprehensive hospital management system built to streamline the operations of a hospital efficiently. It offers a range of functionalities for patients, doctors, staff, and administrators to manage appointments, treatment schedules, payments, and more.

## Features

- **Appointment Booking**: Patients can conveniently book appointments online for consultancy or specific services.

- **Role-based Access**: The system has four roles - Admin, Doctor, Staff, and Patient - each with specific privileges and responsibilities.

- **Doctor Functionality**:
  - View and manage patient appointments.
  - Treat patients according to their schedule.
  - Receive salary payments through the website.

- **Admin Dashboard**:
  - Comprehensive control over the entire system.
  - Manage doctors, staff, and patients.
  - Send notifications to specific individuals or teams.
  - Blood donation membership system for voluntary work.

- **Blood Donation Membership System**: Facilitates voluntary blood donation; members can be contacted in times of need.

- **Payment System**: Seamless payment processing using Stripe Connect.

- **Fully Responsive UI**: User-friendly layout designed to work seamlessly on all devices.

## Tech Stack

### Front-End
- React
- Context API
- Material UI
- React Data Table
- Socket IO
- CSS Frameworks: Tailwind CSS, Mamba UI, Hyper UI, Kitwnd UI

### Back-End
- Node.js
- Express
- Socket IO

### Database
- MongoDB
- Mongoose

### Extra Tools
- Hero Icon
- Swiper JS
- Hooks Form
- React Query
- Axios

### Payment Processor
- Stripe Connect

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/doctors-planet.git
   cd doctors-planet
   ```

2. Install dependencies for the front-end and back-end:
   ```bash
   cd frontend
   npm install

   cd ../backend
   npm install
   ```

3. Set up environment variables:
   - Create a `.env` file in the `backend` directory.
   - Add the necessary environment variables, such as MongoDB connection string, Stripe API keys, etc.

4. Start the development server:
   ```bash
   # In the frontend directory
   npm start

   # In the backend directory
   npm start
   ```

5. Open your browser and navigate to `http://localhost:3000` to access Doctor's Planet.

## User Credentials

- **Patient:**
  - Email: patient@gmail.com
  - Password: 1234Aa@

- **Doctor:**
  - Email: doctor@gmail.com
  - Password: 1234Aa@

## Contribution

Feel free to contribute to Doctor's Planet by submitting issues or pull requests.

---

**Note**: Make sure to replace placeholder values (e.g., MongoDB connection string, Stripe API keys) with your actual configurations.
