# School Management Platform

The **School Management Platform** is a comprehensive system designed to meet the administrative needs of educational institutions like schools and colleges. Built with **Laravel 8** on the backend and **Vue.js** on the frontend, this platform provides a seamless and efficient way to manage various school operations such as student data, class management, fees, library resources, and more. It is designed to cater to multiple user roles, each with specific permissions and responsibilities.

## Technologies Used

- **Laravel 8**: Backend framework for robust application structure.
- **Vue.js**: Modern JavaScript framework for building the frontend.
- **Bootstrap**: Responsive design framework.
- **Axios**: For making HTTP requests.
- **Laravel Mix**: Asset compilation and management.
- **jQuery**: DOM manipulation and event handling.
- **Popper.js**: For tooltip and popover positioning.
- **Lodash**: Utility functions for arrays, objects, and more.
- **Cross-Env**: Platform-agnostic environment settings.

## Installation and Setup

To install and run this project locally, follow these steps:

### Backend Setup (Laravel 8)

1. **Clone the repository** and navigate to the project directory:
   ```bash
   git clone <repository-url>
   cd school-management-platform
   ```
2. Install the necessary PHP dependencies:
  - composer install

3. Configure environment variables:
  - Copy the .env.example file to .env
    cp .env.example .env
  - Set up your database credentials and other environment settings in the .env file.

4. Run database migrations to set up the database structure:
   php artisan migrate

5. Seed the database with default user roles and data:
  - php artisan db:seed
6. Start the backend server:
  - php artisan serve

### Frontend Setup (Vue.js)

1. Install frontend dependencies::
  npm install

2. Compile the frontend assets for development:
  npm run dev

3. To watch for changes and automatically compile assets:
   npm run watch

4. For production builds:
   npm run prod

### Access the Application
   Once the backend and frontend servers are running, open your browser and navigate to:
   http://localhost:8000

### Project Overview

The **School Management Platform** allows for the efficient management of all aspects of a school or college. It includes features and functionalities for various user roles:

### Super Admin & Admin

- Manage user accounts for all roles (Super Admin, Admin, Teachers, Students, Parents, Librarians, and Accountants).
- Manage classes, sections, subjects, and exams.
- Oversee payments, fees, and the noticeboard.
- Configure system settings and delete any record.

### Teacher

- Manage class sections, subjects, and exam records.
- Upload study materials and manage student marks.
- View and manage timetables.

### Student

- View class subjects, marks, and timetables.
- Access study materials uploaded by teachers.
- View payment history and school events.

### Parent

- View child's marksheet, timetable, and payment records.
- Monitor child’s academic progress and school activities.
- Manage own profile information.

### Accountant

- Handle payments and fee management.
- Print payment receipts.

### Librarian

- Manage library resources such as books and their status.

## Additional Features

- **Responsive Design**: Built with Bootstrap for full compatibility with all devices.
- **Security**: Implemented role-based access control and secured data management.
- **Customizable**: Extend or modify features easily to suit your institution's needs.

### SCREENSHOTS 

**Dashboard**
<img src="https://i.ibb.co/D4T0z6T/dashboard.png" alt="dashboard" border="0">

**Login**
<img src="https://i.ibb.co/Rh1Bfwk/login.png" alt="login" border="0">

**Student Marksheet**
<img src="https://i.ibb.co/GCgv5ZR/marksheet.png" alt="marksheet" border="0">

**System Settings**
<img src="https://i.ibb.co/Kmrhw69/system-settings.png" alt="system-settings" border="0">

**Print Marksheet**
<div style="clear: both"> </div>
<img src="https://i.ibb.co/5c1GHCj/capture-20210530-115521-crop.png" alt="print-marksheet">

**Print Tabulation Sheet & Marksheet**
<img src="https://i.ibb.co/QmscPfn/capture-20210530-115802.png" alt="tabulation-sheet" border="0">

<hr />  

## License
This project is licensed under the **MIT License**.
**Developed by Marcus Wilkes**
