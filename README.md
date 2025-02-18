# Appointment Booking API

This project is an **Appointment Booking API** built using **Node.js**, **Express**, and **MongoDB** that allows users to book appointments

## Tech Stack
The project consists of the following parts:
### Frontend
- **React.js** - JavaScript library for building user interfaces
- **HTML, CSS, JavaScript** - Standard technologies for frontend development
- **react-hot-toast** - used for notifications
### Backend
- **Node.js** - JavaScript runtime used for backend development
- **Express.js** - Web framework for Node.js to handle routing
- **Jest**: For running tests to ensure the application is working correctly.
- **Supertest**: For testing the API endpoints.
### Database
- **MongoDB** - NoSQL database used to store data
- **Mongoose** - ODM (Object Data Modeling) library for MongoDB

### Other Libraries/Tools

- **Axios** - Promise-based HTTP client for making API requests
- **dotenv** - Loads environment variables from a .env file into process.env


## Setup and Installation

### Prerequisites
- **Node.js** and **npm** (Node Package Manager)
- **MongoDB** (locally or use a cloud-based MongoDB like MongoDB Atlas)
### 1. Clone the repository

```bash
git clone https://github.com/Anujith-vk/Raify_machine_test.git
cd Raify_machine_test
```
## install Dependencies

```bash
npm install
```

## Create a .env file
create a .enve file and inside it define your port and database link
```bash
PORT='your port number'
DB='Your database link'
```
## Test
for api testing sample data is used

    name: "ibrahim",
    phone_number: "8987787686",
    date: '2025-01-1',
    time: '02:00 PM'
    
to test run
```bash
npm test
```
## Run the project
run the project by using command
```bash
npm start
```
