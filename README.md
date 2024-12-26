# Smart Meter Web Application

This project is a web application for managing and analyzing energy consumption data using IoT devices and machine learning techniques. It provides features like energy usage forecasting, anomaly detection, optimization suggestions, device management, and notification handling.

---

## **Folder Structure**

The application is organized into a modular structure based on the MVC (Model-View-Controller) architecture, ensuring maintainability and scalability.

### **Root Files**
- **`register.php`**: Handles user registration functionality.
- **`login.php`**: Manages user login process.
- **`logout.php`**: Handles user logout functionality.
- **`auth.php`**: Centralized authentication logic.
- **`index.php`**: Main entry point for the application.
- **`forgot_password.php` / `reset_password.php`**: Manage password recovery and reset processes.
- **`test_db.php`**: Script to test database connections and configurations.
- **`debug.php`**: Used for debugging purposes.
- **`password_hash.php`**: Encrypts or validates user passwords securely.
- **`composer.json`**: Defines PHP dependencies managed by Composer.
- **`.htaccess`**: Configures Apache for URL routing, security settings, and access control.

---

### **Directories**

#### **1. views/**
Contains all front-end templates categorized into modules.

- **`user/`**:
  - **`profile.php`**: Displays the user's profile information.
  - **`dashboard.php`**: User-specific dashboard showing analytics.
  - **`energy_usage.php`**: Visualizes energy usage data.

- **`optimization/`**:
  - **`control.php`**: Interface for controlling optimization settings.
  - **`suggestions.php`**: Displays energy-saving recommendations.

- **`notifications/`**:
  - **`list.php`**: Lists all notifications.
  - **`detail.php`**: Shows details for a specific notification.

- **`layouts/`**:
  - **`footer.php`**: Common footer used across pages.
  - **`sidebar.php`**: Navigation menu/sidebar component.
  - **`header.php`**: Page header for branding and navigation.

- **`forecast/`**:
  - **`result.php`**: Displays the result of energy forecasting.
  - **`form.php`**: Input form for forecast queries.

- **`device/`**:
  - **`list.php`**: Lists all connected devices.
  - **`detail.php`**: Displays detailed information about a specific device.

- **`admin/`**:
  - **`dashboard.php`**: Admin dashboard with management tools.
  - **`users.php`**: Admin view for managing users.
  - **`devices.php`**: Admin view for managing devices.

---

#### **2. scripts/**
Backend scripts for processing and data handling.
- **`anomaly_detection.php`**: Implements anomaly detection for energy usage.
- **`ml_model.php`**: Handles Machine Learning model predictions.
- **`device_recognition.php`**: Identifies connected IoT devices.

---

#### **3. public/**
Contains files accessible to users, such as front-end scripts and assets.
- **`index.php`**: Entry point for public-facing users.
- **`js/`**: JavaScript files for client-side interactions.
  - **`app.js`**: Core application script.
  - **`admin.js`**: JavaScript logic for the admin panel.
  - **`user.js`**: JavaScript logic for user-specific interactions.
- **`css/`**: Stylesheets for various roles and pages.
  - **`admin.css`**: Styling for admin panel pages.
  - **`style.css`**: Global styling.
  - **`user.css`**: Styling for user-specific pages.
- **`assets/`**: Static resources such as images and icons.

---

#### **4. models/**
Represents data models for the application.
- **`Notification.php`**: Model for managing notifications.
- **`Forecast.php`**: Model for forecasting data.
- **`EnergyUsage.php`**: Model for energy usage analytics.
- **`Device.php`**: Model for IoT devices.
- **`User.php`**: Model for user management.
- **`Admin.php`**: Model for admin operations.

---

#### **5. js/** and **css/**
Standalone front-end scripts and styles.
- **`scripts.js`**: General JavaScript utilities.
- **`index.css, login.css, styles.css`**: Global and module-specific stylesheets.

---

#### **6. controllers/**
Controllers handle business logic for various modules.
- **`ForecastController.php`**: Manages forecasting logic and interactions.
- **`EnergyController.php`**: Handles energy usage data.
- **`UserController.php`**: Manages user-related actions.
- **`DeviceController.php`**: Handles device operations.
- **`NotificationController.php`**: Manages notifications.
- **`OptimizationController.php`**: Handles energy optimization features.
- **`AdminController.php`**: Admin-related logic.

---

#### **7. config/**
Configuration files for system settings.
- **`database.php`**: Database connection and settings.
- **`settings.php`**: General application configurations.

---

#### **8. assets/**
Static resources such as:
- **Images**: Graphical content.
- **Icons**: Small, reusable visuals for UI.

---

## **Technologies Used**
- **Backend**: PHP
- **Frontend**: HTML, CSS, JavaScript
- **Database**: MySQL
- **Machine Learning**: Python scripts integrated via backend.
- **Version Control**: Git

---

## **Setup Instructions**

1. Clone the repository:
   ```bash
   git clone https://github.com/username/smart-meter.git
