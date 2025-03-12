# Rento Property Management

**Rento Property Management** is a property management application that provides separate interfaces for both landlords and tenants. Through this platform, landlords can manage their properties and tenants can get information about available properties, apply and make payments.

## Features

### Landlord
- **Property Management:** Add, edit, and delete properties.
- **Tenant Tracking:** Maintain a list of tenants and record their payments.
- **Request Management:** Manage and resolve tenant requests and issues.

### Tenant
- **Property Search:** Browse and book available properties.
- **Payment Status:** View the status of rent payments.
- **Direct Communication:** Easily contact the landlord.

## Technical Details

- **Frontend:** Developed using React Native for mobile applications.
- **Backend:** Built with Node.js and Express.js.
- **Deployment:** Hosted on Amazon Web Services (AWS).
- **Database:** Utilizes MongoDB or DynamoDB.

## Installation and Setup Instructions

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/rento-app-india/rento-property-management.git
    ```
    ```bash
    rento-property-management/

            ├── backend/
            ├── frontend/
            │       ├── landlord/
            │       └── tenant/
            └── README.md
    ```


2. **Backend Setup:**
    ```bash
    cd backend
    ```
    **- \rento-property-management\backend>**

    ```bash
    npm install
    ```
    ### Configure the required environment variables in a .env file
    ```bash
    npm start
    ```
3. **Frontend (Landlord) Setup:**
    ```bash
    cd ../frontend/landlord
    ```
    **- \rento-property-management\frontend\landlord>**

    ```bash
    npm install
    npm start
    ```

4. **Frontend (Tenant) Setup:**
    ```bash
     cd ../tenant
    ```
    **- \rento-property-management\frontend\tenant>**

    ```bash
    npm install
    npm start
    ```
