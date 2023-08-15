# Firebase_Crud
# Firebase CRUD Operations Example

This is a simple web application that demonstrates CRUD (Create, Read, Update, Delete) operations using Firebase Firestore. It allows you to manage a collection of cars by adding, displaying, updating, and deleting car records.

## Getting Started

To run this application, follow these steps:

1. Clone the repository:
https://github.com/PazMiz/Firebase_Crud.git

2. 
Replace Firebase Configuration:
Before you can run the application,Replace the Firebase configuration in the index.html file with your own configuration:

Example -
const firebaseConfig = {
  apiKey: "your-api-key",
  authDomain: "your-auth-domain",
  projectId: "your-project-id",
  storageBucket: "your-storage-bucket",
  messagingSenderId: "your-messaging-sender-id",
  appId: "your-app-id",
  measurementId: "your-measurement-id"
};


3. Open the index.html file in a web browser or serve it using a local development server.


Read Data: Open the application in a web browser to view the list of cars retrieved from the Firestore database.

Add Data: Use the "Add Car" form to add new car records. The data will be added to the Firestore database.

This project is licensed under the PazMiz License 
