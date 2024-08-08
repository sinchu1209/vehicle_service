# Vehicle Service Management System

## Setup Instructions

1. **Install Local Web Server:**
   - Install XAMPP or WAMP on your local machine.

2. **Prepare the Project:**
   - Download and extract the provided source code zip file.
   - Copy the extracted folder to the `htdocs` directory (XAMPP) or `www` directory (WAMP).

3. **Start Services:**
   - Open XAMPP/WAMP Control Panel and start the **Apache** and **MySQL** services.

4. **Setup Database:**
   - Go to [phpMyAdmin](http://localhost/phpmyadmin) in your browser.
   - Create a new database named `vehicle_service_db`.
   - Import the `vehicle_service_db.sql` file located in the `database` folder of the extracted source code.

5. **Access the Application:**
   - Visit [http://localhost/vehicle_service](http://localhost/vehicle_service) for the application.
   - For the admin interface, go to [http://localhost/vehicle_service/admin](http://localhost/vehicle_service/admin).

### Default Admin Credentials

- **Username**: `admin`
- **Password**: `admin123`
