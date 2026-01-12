# Garden Go: Auto Courier Connect

**Garden Go** is an integrated e-commerce platform designed to bridge the gap between plant nurseries and customers through a dependable, automated courier service. Developed during the **Infosys Springboard Internship**, this project streamlines the process of ordering, calculating logistics, and tracking deliveries for seeds and plants.

> "Plants are the earth's endless effort to speak to the listening heaven." — *Rabindranath Tagore*

---

## Key Modules

### 1. User Authentication & Role Management
Ensures secure access and tailored permissions for all users:
* **Multi-Role Access:** Specific interfaces for Customers, Couriers, and Administrators.
* **Security:** Features secure login, user registration, and password recovery systems.

### 2. Product Management
A comprehensive system to manage the digital nursery:
* **Dynamic Catalog:** Showcases seeds and plants with detailed descriptions, images, weights, and prices.
* **Inventory Control:** Administrators can add, edit, or delete products and organize them into categories like flowers, vegetables, and herbs.
* **User Experience:** Includes robust search and filtering options for easy navigation.

### 3. Shipping Cost Calculation
Automates the logistics of plant delivery:
* **Weight-Based Logic:** Automatically calculates total cart weight for precise shipping estimates.
* **Location Validation:** Validates delivery pin codes to ensure serviceability.
* **Real-Time Estimation:** Provides costs to customers before they complete their purchase.

### 4. Courier Dashboard & Tracking
Real-time delivery management for courier personnel:
* **Status Updates:** Couriers can update orders to "Picked Up," "In Transit," "Delivered," or "Failed Delivery".
* **Issue Reporting:** Couriers can report delivery problems (e.g., wrong address) to alert administrators.
* **Live Monitoring:** Customers and admins receive immediate status changes via automated notifications.

### 5. Performance Analytics
Data-driven insights for business optimization:
* **Sales Trends:** Visualization of growth patterns over time (daily, weekly, monthly).
* **Shipping Efficiency:** Distribution histograms of delivery times and pie charts for on-time delivery rates.
* **Market Intelligence:** Heatmaps for product popularity and charts for customer demographics.

---

## 🛠️ Technology Stack

* **Language:** Python
* **Framework:** Flask
* **Frontend:** HTML, CSS, JavaScript 
* **Database:** SQLAlchemy
* **Data Analysis:** Pandas
* **Visualization:** Matplotlib, Seaborn, or Plotly
* **Testing:** Unittest or Pytest

---

## 📂 Project Structure & Artifacts

During the development phase, the following artifacts were completed:
* **Design:** UI Mockups, Use Case Diagrams, and Class Diagrams.
* **Documentation:** Project Launch Document (Scope & Objectives).
* **QA:** Comprehensive Test Cases and Database Design.

---

## ⚙️ Installation

To run the Garden Go platform locally:

```bash
# Clone the repository
git clone [https://github.com/ImaduddinQazi/Infosys-Python-Batch-3-Garden-Go](https://github.com/ImaduddinQazi/Infosys-Python-Batch-3-Garden-Go)

# Install required dependencies
pip install flask sqlalchemy pandas matplotlib plotly

# Initialize the database and run the app
python app.py
