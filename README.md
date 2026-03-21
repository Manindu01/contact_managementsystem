# GreenLife Organic Store Management System 🌱

A desktop-based retail management application built with **C#** and **Windows Forms (.NET Framework)**. This system is designed to streamline the daily operations of an organic grocery store, providing dedicated interfaces for both Store Administrators and Customers. 

Data persistence is handled via **local file storage (.txt and .csv)**, making it a lightweight, easy-to-deploy solution without the need for complex database setups.

## 🚀 Key Features

### 👨‍💼 Admin Features
* **Dashboard Overview:** Real-time statistics on total products, active orders, and sales.
* **Product Management:** Add, update, delete, and search for products. Includes automated low-stock warnings.
* **Order Management:** View all customer orders, update order statuses (Pending, Shipped, Delivered), and export order history to **CSV**.
* **Customer Management:** View registered customers and update their details.
* **Promotions:** Apply percentage-based discounts to products.
* **System Reports:** Generate summarized text reports for stock and sales tracking.

### 🛒 Customer Features
* **User Authentication:** Secure registration and login system.
* **Product Browsing & Ordering:** View available inventory and place orders.
* **Real-time Stock Updates:** Placing an order automatically deducts the item from the store's stock.
* **Order Tracking:** Customers can view the real-time status of their placed orders.
* **Profile Management:** Update personal contact details easily.
* **Product Ratings:** Ability to rate purchased products.

## 💻 Tech Stack
* **Language:** C#
* **Framework:** .NET Framework (Windows Forms)
* **IDE:** Microsoft Visual Studio
* **Data Storage:** Local Flat Files (`.txt`, `.csv`)
* **Architecture:** Object-Oriented Programming (OOP) with Layered UI/Logic separation.

## 📂 Data Storage Mechanism
The system uses simple text files stored in the `bin/Debug` folder to persist data across sessions:
* `users.txt` - Stores registered customer credentials and details.
* `products.txt` - Stores product inventory, pricing, and stock levels.
* `orders.txt` - Stores placed orders and their current statuses.
* `orders.csv` - Exported data file for admin reporting.

## 🛠️ Getting Started (How to Run)

### Prerequisites
* Microsoft Visual Studio (2015 or newer recommended).
* .NET Framework installed on your Windows machine.

### Installation
 **Clone the repository:**
   ```bash
   git clone https://github.com/YourUsername/GreenLifeStore.git


1. **Clone the repository:**
   ```bash
   git clone https://github.com/YourUsername/GreenLifeStore.git
