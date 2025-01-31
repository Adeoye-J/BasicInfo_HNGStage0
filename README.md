### `README.md`

# HNG12 Backend Stage 0 API

This project is a public API that returns basic information in JSON format. It is part of the HNG12 Backend Intern task.

## Project Overview

The API provides the following details:

- **Your registered email address**
- **The current date and time (ISO 8601 format)**
- **The GitHub URL of your project codebase**

The task involves creating a public API using Node.js (Express) and deploying it to a publicly accessible platform.

## Tech Stack

- **Node.js** with **Express**: For building the API.
- **CORS**: To handle Cross-Origin Resource Sharing.
- **GitHub**: To host the project codebase.

## Setup Instructions

### Prerequisites

- **Node.js**: Ensure Node.js is installed on your machine. You can check by running:
  ```sh
  node -v
  npm -v
  ```

### Install Dependencies

1. Clone the repository:
   ```sh
   git clone https://github.com/Adeoye-J/BasicInfo_HNGStage0.git
   cd hng12-backend-api
   ```

2. Install the required dependencies:
   ```sh
   npm install
   ```

### Running the API Locally

To run the API locally, execute the following command:
```sh
node server.js
```

The API will be available at **http://localhost:3000**.

## API Documentation

### Endpoint
- **GET** `/` – Retrieve basic information.

### Response Format (200 OK)
```json
{
  "email": "your-email@example.com",
  "current_datetime": "2025-01-30T09:30:00Z",
  "github_url": "https://github.com/yourusername/your-repo"
}
```

### Example Usage
To access the API, simply make a GET request to:
```
https://basicinfo-hngstage0.onrender.com/
```

You can test the API using Postman, cURL, or a browser.

---

## Deployment

The API is hosted on **[https://basicinfo-hngstage0.onrender.com/]**.

I used **[Render]** for deployment. You can deploy the code to your preferred platform.

---

## Backlink

For more information on Node.js development, check out:
[HNG NodeJs Developers](https://hng.tech/hire/nodejs-developers)

---

### Notes

- The **current_datetime** is dynamically generated in ISO 8601 format (UTC).
- Ensure that the response time is < 500ms.
- The repository is public, and the code can be found on [GitHub](https://github.com/Adeoye-J/BasicInfo_HNGStage0").
