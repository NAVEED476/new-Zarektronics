
# MERN Stack Signup
![Screenshot 2024-03-06 121751](https://github.com/NAVEED476/new-Zarektronics/assets/95119749/c686be9d-5818-477f-af1a-d0057fa1ef18)
![Screenshot 2024-03-06 121712](https://github.com/NAVEED476/new-Zarektronics/assets/95119749/61ea56ae-c833-464f-bf53-6fc7c63fa9bd)
This project is a simple signup application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It allows users to sign up by providing their details and stores the data in MongoDB. The frontend is built with React and styled-components, and local storage is used to store data when offline. If a user already exists, the application will throw an error.

## Features
![Screenshot 2024-03-06 121725](https://github.com/NAVEED476/new-Zarektronics/assets/95119749/e86afc4c-c869-404c-8919-b256b07ee3f3)
- User signup with basic details (first name, last name, email, username, password)
- Data storage in MongoDB
- Frontend built with React and styled-components
- Offline data storage using IndexDB
- Validating an email
- Error handling for duplicate users

## Deployment

The application is deployed on Vercel. You can access it [here](https://zarektroniks-ui.vercel.app/).

## Technologies Used

- MongoDB
- Express.js
- React.js
- Node.js
- styled-components
- local storage

## Setup Instructions

1. Clone the repositories:

```bash
for frontend
git clone https://github.com/NAVEED476/new-Zarektronics.git

for backend 
git clone https://github.com/NAVEED476/api-zarektroinks.git
```

2. Navigate to the project directory:

```bash
cd mern-signup
```

3. Install dependencies for both the backend and frontend:

```bash
cd server && npm install
cd ../user && npm install
```

4. Start the backend server:

```bash
cd ../server && npm start
```

5. Start the frontend server:

```bash
cd ../user && npm start
```

6. Open your browser and navigate to [http://localhost:3000](http://localhost:3000) to view the application.

## Project Structure

```
mern-signup/
│
├── server/                  # Backend server files
│   ├── controllers/          # Controller functions
│   ├── models/               # Mongoose models
│   ├── routes/               # API routes
│   └── index.js                # Express app configuration
│
└── user/                 # Frontend React application
    ├── public/
    └── src/
        ├── components/       # React components
       
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
