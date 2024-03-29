Recipe-dictionary

Innovative use of React Native is revolutionizing home cooking.

Purpose of Our App

Streamline Cooking: Our app aims to simplify the cooking process by providing step-by-step recipes, ingredient lists, and cooking tips. Explore a variety of cuisines effortlessly.

Efficient Meal Planning: Streamline your meal preparation with a recipe app that offers a diverse range of quick and delicious recipes. Plan your meals efficiently for a stress-free cooking experience.

Quantify Groceries Usage: Keep track of grocery usage to minimize food spoilage and save money while promoting sustainability. Our app helps you manage and optimize your grocery shopping.

Getting Started

To run the Recipe-dictionary app locally, follow these steps:

Prerequisites

Node.js installed
Expo CLI installed
Installing Dependencies

# Clone the repository
git clone https://github.com/your-username/Recipe-dictionary.git

# Navigate to the project directory
cd Recipe-dictionary

# Install dependencies
npm install
Adding Firebase and Firestore

Create a Firebase project.
Obtain your Firebase configuration object.
Replace the placeholder in firebaseConfig.js with your Firebase configuration.
// ./firebaseConfig.js

const firebaseConfig = {
  apiKey: "your-api-key",
  authDomain: "your-auth-domain",
  projectId: "your-project-id",
  storageBucket: "your-storage-bucket",
  messagingSenderId: "your-messaging-sender-id",
  appId: "your-app-id",
};

export default firebaseConfig;
Running the App

# Start the app
npm start
Follow the Expo CLI instructions to run the app on an emulator or physical device.
