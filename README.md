# Hotel Reservation System

The **Hotel Reservation System** is a web-based application designed to streamline hotel booking and management processes. This project includes a well-designed MySQL database schema and user-friendly features to enhance the experience for both customers and administrators.

---

## Features

### Customer Features
- Search and browse available rooms by dates and preferences.
- Real-time booking and cancellation options.
- Secure payment processing.
- Notifications for booking confirmations and updates.

### Admin Features
- Manage room inventory, pricing, and availability.
- Track customer reservations.
- Generate reports on occupancy, revenue, and customer activity.
- Handle promotions and discounts.

---

## Database Highlights

The MySQL database schema ensures:
- **Normalized Design:** Reduces data redundancy for efficient storage.
- **Scalability:** Supports growing hotel data and customer demands.
- **Integrity:** Utilizes foreign key constraints to maintain relational accuracy.

### Key Tables
- `booking_status`: Tracks the status of reservations.
- Additional tables for user details, room details, and payments.
- And a main table Hotel reservations 

---

### Database
- MySQL


## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/your-repository-name.git
   cd your-repository-name
   ```

2. **Set Up the Database**
   - Import the provided `Database Final Schema.sql` file into your MySQL server.
   ```bash
   mysql -u your-username -p your-database-name < Database\ Final\ Schema.sql
   ```

3. **Configure the Backend**
   - Update the database connection string in your backend configuration file.
   - Install required dependencies:
     ```bash
     pip install -r requirements.txt
     ```


**Access the Application**
   - Open your browser and navigate to `http://localhost:5000`.

---

## Usage

- **Customer Access:** Browse rooms, make reservations, and manage bookings.
- **Admin Access:** Log in to the admin panel to manage inventory and view reports.



## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---


