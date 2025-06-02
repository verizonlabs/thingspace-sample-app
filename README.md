# Verizon ThingSpace API Sample Application

Welcome to the **Verizon ThingSpace API Sample Application**! This interactive application demonstrates how to use the Verizon ThingSpace API with its official Python SDK. Feel free to modify and extend this open-source application to suit your needs.

---

## Table of Contents

1. [About This Application](#about-this-application)
2. [Key Features](#key-features)
3. [Getting Started](#getting-started)
   - [Prerequisites](#prerequisites)
   - [Running the Application](#running-the-application)
4. [Troubleshooting](#troubleshooting)
5. [Additional Notes](#additional-notes)
6. [Create Your Own Application!](#create-your-own-application)

---

## About This Application

This sample application helps developers explore and interact with Verizon ThingSpace APIs for managing IoT devices. It provides a step-by-step workflow for both **Sandbox** and **Production** environments.

Built with **Flask** and the **Verizon ThingSpace SDK**, this application is easy to set up and run locally, offering a user-friendly interface to test and explore API features.

---

### Key Features

- **Environment Selection**  
  - **Sandbox**: For testing with predefined credentials.  
  - **Production**: For live operations (requires your own credentials).

- **Access Token Generation**  
  Securely generate tokens to communicate with the API.

- **API Endpoints Exploration**  
  Interact with three key API endpoints:
  1. **Start Session**: Manage IoT connectivity sessions.
  2. **Manage Devices**: Query or update device configurations.
  3. **End Session**: Terminate sessions securely.

- **Interactive Interface**  
  A web-based interface to call API endpoints and view responses.

- **Customizable Foundation**  
  Use this Flask-based application as a starting point for your own projects.

---

## Getting Started

### Prerequisites

1. **Python 3.7 or Higher**  
   Verify Python is installed:

   ```bash
   python3 --version
   ```

   If not installed, visit the [official Python website](https://www.python.org/) for installation instructions.

2. **Virtual Environment**  
   Create and activate a virtual environment:

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # macOS/Linux
   venv\Scripts\activate     # Windows
   ```

3. **Install Dependencies**  
   Install required packages from `requirements.txt`:

   ```bash
   pip install -r requirements.txt
   ```

---

### Running the Application

1. **Start the Server**  
   Run the Flask server:

   ```bash
   python main.py
   ```

   or

   ```bash
   python3 main.py
   ```

2. **Access the Application**  
   Open your browser and navigate to:
   [http://127.0.0.1:5000/](http://127.0.0.1:5000/)

3. **Explore the API**  
   Use the interactive interface to test API endpoints in real-time.

---

### Troubleshooting

- **ModuleNotFoundError: No module named 'verizon'**  
  Ensure the `sdksio-verizon-apis-sdk` package is installed:

  ```bash
  pip install --force-reinstall sdksio-verizon-apis-sdk
  ```
  
  Make sure you're running the application within the virtual environment.

- **Deactivate the Virtual Environment**  
  When finished, deactivate the virtual environment:

  ```bash
  deactivate
  ```

---

## Additional Notes

- **Credentials**:  
  - **Sandbox**: Predefined credentials are provided.  
  - **Production**: Use your own credentials. Sign up at [Verizon ThingSpace](https://thingspace.verizon.com/profile/sign-up.html) to obtain production credentials.

- **Documentation**:  
  Refer to the [Verizon ThingSpace API Documentation](https://thingspace.verizon.com/documentation/api-documentation.html#/http/quick-start/getting-started-with-the-verizon-api).

- **Security**:  
  Handle API credentials securely. Avoid hardcoding sensitive information.

- **Best Practices**:  
  Follow API usage best practices, including rate limiting and error handling.

- **Disclaimer**:  
  This application is for demonstration purposes only. Always follow best practices when handling sensitive information.

---

## Create Your Own Application

This sample application is open-source and designed to be a foundation for your own projects. Modify and extend it to suit your needs. Thank you for exploring the Verizon ThingSpace API. Happy coding!
