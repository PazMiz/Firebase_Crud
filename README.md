Firebase CRUD Operations Example
Create firestore
This is a simple web application that demonstrates CRUD (Create, Read, Update, Delete) operations using Firebase Firestore. It allows you to manage a collection of cars by adding, displaying, updating, and deleting car records.

Getting Started
To run this application, follow these steps:

Clone the repository:

shell
Copy code
git clone https://github.com/PazMiz/Firebase_Crud.git
Replace Firebase Configuration:

Before you can run the application, replace the Firebase configuration in the index.html file with your own configuration:

javascript
Copy code
const firebaseConfig = {
  apiKey: "your-api-key",
  authDomain: "your-auth-domain",
  projectId: "your-project-id",
  storageBucket: "your-storage-bucket",
  messagingSenderId: "your-messaging-sender-id",
  appId: "your-app-id",
  measurementId: "your-measurement-id"
};
Open the index.html file in a web browser or serve it using a local development server.

Features
Read Data
Open the application in a web browser to view the list of cars retrieved from the Firestore database.

Add Data
Use the "Add Car" form to add new car records. The data will be added to the Firestore database.

Update Data
Each car entry has an "Update" button. Clicking on this button allows you to edit the details of the car, such as its model, year, and color. Once updated, the changes will be reflected in the Firestore database.

Delete Data
Each car entry also has a "Delete" button. Clicking on this button will remove the corresponding car record from both the UI and the Firestore database.

License
This project is licensed under the PazMiz License. Feel free to use, modify, and distribute this code according to the terms of the license.

