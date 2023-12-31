# PDF Editor App

A simple web application for editing and managing PDF files. This project is built with Node.js, Express, React, and MongoDB using GridFS for storing PDFs.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Installation](#installation)
3. [Usage](#usage)
4. [API Endpoints](#api-endpoints)
5. [Contributing](#contributing)


## Project Overview

The PDF Editor App allows users to perform the following actions:

- **Upload PDFs**: Users can upload PDF files to the application, which are stored in MongoDB using GridFS.

- **View PDFs**: Users can view a list of their uploaded PDFs and select a PDF to view in a modal.

- **Edit PDFs**: Users can edit PDFs by selecting specific pages and creating a new PDF containing those pages.

- **Download PDFs**: Users can download edited PDFs with selected pages.

- **Delete PDFs**: Users can delete PDFs from their account.

This project uses the Express framework for the backend server, React for the frontend, and MongoDB with GridFS for storing and retrieving PDF files.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```shell
   git clone https://github.com/yourusername/pdf-editor-app.git
    ```


2. Change into the project directory:

    ```shell
    cd pdf-editor-app 
    ```

3. Install the dependencies for both the server and client:
    ```shell
    cd server
    npm install
    cd ../client
    npm install

    ```

4. Start the server and client:
    Start the server:
    ```shell
    cd ../server
    npm start

    cd ../client
    npm start

    ```

5.Open a web browser and navigate to http://localhost:3000 to access the application.


## Usage

1. Register and log in to your account.

2. Upload PDF files to your account.

3. View your uploaded PDFs, edit or download them, and delete them as needed.

4. Enjoy editing and managing your PDFs!


## API Endpoints

### User Authentication

- **POST /api/v1/users/register:** Register a new user.
- **POST /api/v1/users/login:** Authenticate and generate a token for a user.

### PDF Manangement

- **POST /api/v1/pdf/upload:** Upload a PDF file to the server.
- **GET /api/v1/pdf/get-all:** Retrieve all PDFs uploaded by the user.
- **GET /api/v1/pdf/:id:** Retrieve a single PDF by ID.
- **POST /api/v1/pdf/download:** Download a PDF with selected pages.
- **DELETE /api/v1/pdf/:id:** Delete a PDF.


## Contributing
Contributions to this project are welcome. If you find any issues or would like to contribute new features or improvements, please open a pull request.# pdf-management-editor
