# Simple Backconnect Android App

A basic Android application demonstrating client-server communication. This app captures two numbers from the user, sends them to a Python backend API for addition, and displays the result returned by the server.

<img width="401" height="808" alt="image" src="https://github.com/user-attachments/assets/9df3ca99-1438-48cf-a9ff-83471e3877be" />


## 📋 Overview

This project serves as a simple example of how to connect an Android client to a remote backend service. It's designed to illustrate fundamental concepts of Android development and networking.

## ✨ Features

*   **Client-Server Model:** Clear separation between the Android front-end and a Python back-end.
*   **REST API Communication:** Uses `HttpURLConnection` to send a `POST` request to a RESTful API endpoint.
*   **JSON Data Handling:** Creates a JSON object to send data and parses a JSON response to retrieve the result.


## ⚙️ How It Works

1.  The user enters two numbers into the input fields on the Android app.
2.  When the "Add" button is pressed, the app creates a JSON object containing the two numbers.
3.  An HTTP `POST` request is sent to the backend API endpoint with the JSON data.
4.  The Python backend server receives the request, parses the numbers, calculates their sum, and returns the result in a JSON response.
5.  The Android app receives the response, parses the sum, and updates the `TextView` to display the result to the user.

