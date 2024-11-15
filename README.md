# Grocery Store Management System

The **Grocery Store Management System** is a comprehensive application designed to streamline and automate the operations of a grocery store. It allows for inventory management, sales tracking, and customer management, providing an intuitive interface for the store management team. Built using a combination of **Python**, **HTML**, **CSS**, **SQL**, **JavaScript**, and **Electron**, this system facilitates real-time data management and efficient customer service, with a cross-platform desktop application interface.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Inventory Management**: Manage product stock, update quantities, and track product details.
- **Sales Tracking**: Keep track of customer purchases, generate bills, and monitor sales performance.
- **Customer Management**: Store customer information and maintain purchase history.
- **Real-Time Updates**: The system updates inventory and sales data in real-time using JavaScript for dynamic interactions.
- **Database Integration**: SQL database for storing and retrieving customer, sales, and product data efficiently.
- **Cross-Platform Desktop Application**: Using **Electron**, this system can be run as a desktop application on Windows, macOS, and Linux.
- **User-Friendly Interface**: Developed using HTML and CSS for a simple and easy-to-navigate interface.

## Technologies Used

- **Python**: Backend logic, sales processing, and server-side functionality.
- **HTML & CSS**: Frontend structure and design for an interactive, clean interface.
- **JavaScript**: Real-time updates for the UI, enabling dynamic content interactions.
- **SQL**: Database management for product, customer, and sales data storage.
- **Electron**: Framework for building a cross-platform desktop application, wrapping the web-based frontend and Python backend into a standalone executable.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/puneethrajg/grocery-store-management-system.git
   ```
2. **Navigate to the Project Directory**:
   ```bash
   cd grocery-store-management-system
   ```
3. **Install Backend Dependencies**:
   - Python:
     ```bash
     pip install -r requirements.txt
     ```
4. **Install Frontend Dependencies**:
   - Install Node.js (if not already installed): https://nodejs.org/
   - Install Electron and JavaScript libraries:
     ```bash
     npm install
     ```
5. **Setup Database**:
   - Create and configure your database using the provided SQL scripts.

## Usage

1. **Start the Backend Server**:
   ```bash
   python server.py
   ```
2. **Launch the Frontend**:
   - To start the web interface, open `index.html` in your preferred browser.
   - Or, run the **Electron** app by executing the following command in the project directory:
     ```bash
     npm start
     ```
   - This will open the application as a desktop app on your system.

3. **Use the System**:
   - Add, update, and remove products from the inventory.
   - Track customer purchases and generate receipts.
   - Monitor sales and inventory in real time.

## Contributing

Contributions are welcome! Please follow the steps below:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or issues, please reach out to (punithraj400@gmail.com [Puneeth Raj G]).

---

Thank you for using the **Grocery Store Management System**! We hope this project helps you efficiently manage your grocery store operations.

