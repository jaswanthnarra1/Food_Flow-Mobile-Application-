# Food_Flow-Mobile-Application-
🍱 FoodFlow

A mobile application designed to reduce food waste and hunger by connecting restaurants with surplus food to NGOs that distribute it to those in need.

🌍 Problem Statement

Every single day, tons of perfectly good food are cooked in restaurants, hotels, and events. When the day ends, extra food is often discarded — while millions of people go to bed hungry.

This creates two major problems:

Food Waste – Edible food is wasted despite the resources invested to produce it.

Hunger & Malnutrition – People who need food the most remain deprived.

FoodFlow aims to solve this by providing a platform to bridge the gap between food donors and NGOs — making the process transparent, efficient, and sustainable.

💡 About the Project

FoodFlow enables:

Restaurants to donate surplus food quickly.

NGOs to locate nearby donations and collect them in real time.

Real-time tracking using Google Maps API for pickup and delivery logistics.

Smooth authentication and user management through context-based auth system.

⚙️ Features

🍔 Food Donation System – Restaurants can upload donation details with quantity and type.

🏢 NGO Dashboard – NGOs can view, claim, and manage available donations.

🔐 Authentication System – Secure login and registration using JWT & Context API.

🗺️ Real-Time Maps – Google Maps integration for navigation and tracking.

💬 Push Notifications – Instant updates when donations are created or accepted.

🎨 Modern UI/UX – Clean, responsive mobile-first design using React Native and Expo.

🛠️ Tech Stack
Layer	Technology
Frontend	React Native (Expo)
State Management	Context API
Backend Integration	Node.js / Express APIs
Authentication	JWT, Custom Auth Context
Database	MongoDB
Maps & Location	Google Maps API
Package Management	npm
Environment Config	.env file support
📁 Project Structure
FoodFlow/
├── App.js
├── AppSimple.js
├── context/
│   ├── AuthContext.js
│   └── EnhancedAuthContext.js
├── assets/
├── components/
├── screens/
├── package.json
├── babel.config.js
├── metro.config.js
└── README.md

🚀 Getting Started
Prerequisites

Node.js installed

Expo CLI installed (npm install -g expo-cli)

Google Maps API key

MongoDB (local or cloud via Atlas)

Installation Steps

Clone the Repository

git clone https://github.com/your-username/FoodFlow.git
cd FoodFlow


Install Dependencies

npm install


Configure Environment Variables
Create a .env file in the root directory and add:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
GOOGLE_MAPS_API_KEY=your_maps_api_key


Run the App

npx expo start


Launch on Device

Scan the QR code with the Expo Go app on your phone

Or run on emulator using a (Android) / i (iOS)

🧠 Authentication System Overview

The authentication system uses a Context API with JWT tokens for secure user login and session persistence.
See README_AUTH_SYSTEM.md
 for detailed documentation on authentication flow and token management.

📈 Future Scope

Integration with food delivery volunteers

AI-based food quality prediction

NGO performance analytics dashboard

Multi-language support

Cloud storage for food images

🤝 Contributing

Contributions are welcome!
If you’d like to improve or extend FoodFlow:

Fork the repository

Create your branch: git checkout -b feature/YourFeature

Commit your changes: git commit -m 'Add new feature'

Push to your branch: git push origin feature/YourFeature

Create a Pull Request

👨‍💻 Author

Jaswanth Narra
Web/ Developer

📜 License

This project is Not available For Any Modification With out reaching me.
Jaswanthnarra345@gmail.com
