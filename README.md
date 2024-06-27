# Business Management Website🤘

This project is a website for managing a private business, such as a psychologist or cosmetician. The site is designed for use by both the business owner and regular users. Regular users can contact the business owner and view information about the business, while the owner can manage the business through the site.

## Admin Interface

The admin interface is accessible via a separate route (`/admin`) and requires a username and password for login. The admin interface includes the following pages:

- **Business Details:** Information about the business, such as address and contact details.
- **Services:** A list of services provided by the business, including descriptions, prices, and durations.
- **Appointments:** The owner can add, cancel, and modify appointments.
- **Clients:** A list of clients.

## User Interface

The user interface includes the following features:

- **Home Page:** Displays information and advertisements about the site.
- **Book an Appointment:** Users can book appointments by selecting the following options:
  - Service type
  - Date and time
  - Note to the business owner
  - Client name
  - Phone number

When a user books an appointment, it is added to the list of appointments in the admin interface. The owner can view the appointments sorted by date or client name. Users cannot cancel appointments directly; they must send a message to the business owner, who can then cancel the appointment.

## Additional Features

- Users can send messages to the business owner independently of appointments.
- The admin has a messaging interface to manage these communications.
- Regular users cannot access the admin pages.

## Design Notes

- The site should have a basic and reasonable appearance.
- The project includes the integration of new learning experiences, such as additional functions from the React website, the use of a design library, or any auxiliary library.

## Technologies Used

- **Frontend:** React
- **Backend:** Node.js
- **Database:** MongoDB
- **Authentication:** JWT

## Installation and Setup

1. Clone the repository: `git clone <repository-url>`
2. Install dependencies: `npm install`
3. Set up environment variables:
   - `MONGO_URI`: MongoDB connection string
   - `JWT_SECRET`: Secret key for JWT
4. Start the development server: `npm start`

## Usage

- Visit the home page to view business information and book appointments.
- Admins can log in at `/admin` to manage business details, services, appointments, and clients.

## Contributions

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.
