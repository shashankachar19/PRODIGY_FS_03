# Local Store E-commerce Platform (Internship Project - Prodigy)

This project is a fully functional, full-stack e-commerce application developed as the core deliverable for the **Prodigy Infotech** internship. It features dynamic product listings, a persistent shopping cart, and a UI design heavily inspired by the clean, professional layout of **Amazon**.

The application operates using a dual-server architecture: a **React Frontend** for the user interface and a **Node.js/Express Backend** for data supply.

##  Key Features & Technical Achievements

| Feature | Description | Technical Implementation |
| :--- | :--- | :--- |
| **Architecture** | Application runs on two independent servers simultaneously. | **React Frontend** (CRA) on **Port 3000** and **Node/Express Backend** (API) on **Port 5000**; configured with **CORS**. |
| **State Management** | Manages product quantities, cart updates, and totals across components. | Global cart state passed via props; implemented logic for adding, removing, and quantity updates. |
| **UI Design** | Professional, clean layout for easy browsing and checkout. | **Amazon-inspired** header, product card structure, and responsive cart summary styling. |
| **Localization** | Prices and currency symbols are displayed for a specific region. | All product pricing is formatted using the **Indian Rupee (₹)** symbol. |
| **API Integration** | Retrieves product details and prices from an external source. | Asynchronous `fetch` calls from the React components to the Express API endpoint (`/api/products`). |
| **Environment Debugging**| Successfully resolved critical dependency and scripting errors. | Fixed 'Missing script' and 'react-scripts not recognized' errors on initial setup (Windows/Linux). |

##  How to Run the Project Locally

This project requires **Node.js** and **npm** to be installed on your system.

1.  **Clone the Repository:**
    ```bash
    git clone [Your Repository HTTPS Link Here]
    cd [your-repo-name]
    ```
2.  **Move into the main project directory:**
    ```
    cd local-store-ecommerce
    Install Backend Dependencies:
    cd backend
    npm install
    ```
3.  **Install Frontend Dependencies:**
    ```
    cd frontend
    npm install
    ```
## Technology Stack

* **Frontend:** React,HTML5,CSS3,react-router-dom
* **Backend:** Node.js,Express.js
* **Data:** Mock JSON Data served via Express
* **Environment:** Ubuntu/Linux

---
*Developed by **Shashank S***
