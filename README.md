# ID Card Generator

The **ID Card Generator** is a full-stack web application designed to streamline the creation of professional ID cards. Users can input personal details, upload photos, and generate customized ID cards.

## Features

- User-friendly interface for inputting personal information
- Photo upload functionality for personalized ID cards
- Options to download or print the generated ID cards

## Prerequisites

Ensure you have the following installed on your system:

- [Node.js](https://nodejs.org/) (v14 or higher)
- [npm](https://www.npmjs.com/) (comes with Node.js)

## Project Structure

The repository is organized into two main directories:

- `backend/` - Contains the Express.js server handling API requests and QR code generation.
- `frontend/` - Contains the React.js application for the user interface.

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/prerna-phadnis/id-card-generator.git
cd id-card-generator
```

### 2. Backend Setup

Navigate to the `backend` directory, install dependencies, and start the server.

```bash
cd backend
npm install
npm run dev
```

The backend server will start on `http://localhost:5000` by default.

### 3. Frontend Setup

Open a new terminal window, navigate to the `frontend` directory, install dependencies, and start the development server.

```bash
cd frontend
npm install
npm start
```

The frontend application will be accessible at `http://localhost:3000`.

## Usage

1. Open your browser and navigate to `http://localhost:3000`.
2. Fill in the required personal details in the form.
3. Upload a clear photo for the ID card.
4. Click on the "Generate ID Card" button.
5. Preview the generated ID card.
6. Use the available options to download or print the ID card.

## API Endpoints

The backend server exposes the following API endpoints:

- `POST /api/generate`: Accepts user details and returns a generated ID card with an embedded QR code.
- `GET /api/preview/:id`: Retrieves a preview of the generated ID card based on the provided ID.

## Technologies Used

### Frontend

- React.js
- HTML5 & CSS3, Bootstrap
- JavaScript

### Backend

- Node.js
- Express.js

## License

This project is licensed under the [MIT License](LICENSE).
