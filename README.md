🚗 AutoMart (React E-Commerce Catalog)

AutoMart is a dynamic, front-end web application built with React that serves as an interactive car catalog. It demonstrates a complete implementation of CRUD (Create, Read, Update, Delete) operations and global state management using React's Context API.

(📝 Note to recruiter: This project showcases my ability to manage complex UI states, integrate RESTful APIs, and build modular React components.)

✨ Features

Display Products: View a beautifully styled grid of car listings with images, descriptions, and prices.

Add New Cars: A dedicated form to dynamically add new vehicles to the catalog.

Edit Existing Cars: Inline or modal editing capabilities to update car details (Price, Name, Description, Image URL).

Delete Cars: Remove vehicles from the catalog with immediate UI updates.

Interactive Shopping Cart:

Add items to the cart.

Increment/Decrement quantities.

Real-time calculation of total prices based on quantity.

🛠️ Tech Stack

Frontend: React 19 (Hooks)

State Management: Context API (ProductContext)

Styling: Pure CSS / Responsive Design

Icons: Lucide React

HTTP Client: Axios

Mock Backend: JSON Server

📂 Project Architecture highlight

The project is structured for scalability and separation of concerns:

src/context/: Contains the ProductContext.jsx which centralizes the business logic, API calls, and state management, keeping components clean.

src/Component/: Reusable UI components (ProductCard, AddProduct, EditProduct).

src/data/: Mock data initialization.

🚀 Getting Started

To run this project locally, follow these steps:

Prerequisites

Node.js (v14 or higher)

npm or yarn

Installation

Clone the repository

git clone https://github.com/yourusername/automart.git
cd automart


Install dependencies

npm install


Start the Mock Backend (JSON Server)
This will run the mock API locally on port 8000.

npm run server


Start the React Application
Open a new terminal window and run:

npm start


The app will open in your browser at http://localhost:3000.

💡 Future Improvements

Implement a persistent real database (e.g., MongoDB, PostgreSQL) via a Node.js/Express backend.

Add user authentication and authorization.

Implement pagination and a search/filter feature for cars.

Coded with ❤️ by [Your Name]