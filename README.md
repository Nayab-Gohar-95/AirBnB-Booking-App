# Airbnb Clone

## Overview
This project is a **full-stack Airbnb clone** built with:
- **Front-end:** React (Vite) + Tailwind CSS
- **Back-end:** Node.js + Express
- **Database:**  MongoDB

## Features
- User authentication & registration
- Property listing & search functionality
- Booking & reservation system
- Responsive UI with modern design

## Installation & Setup
### 1. Clone the repository
```sh
git clone https://github.com/your-username/Airbnb-Clone.git
cd Airbnb-Clone
```

### 2. Install dependencies
#### Back-end
```sh
cd Back-end
npm install
```
#### Front-end
```sh
cd Front-end
npm install
```

### 3. Set up environment variables
- Create a `.env` file in both `Front-end/` and `Back-end/` directories.
- Add necessary environment variables (e.g., database URL, API keys, JWT secrets).

### 4. Run the project
#### Back-end
```sh
npm start
```
#### Front-end
```sh
npm run dev
```

## Folder Structure
```
Airbnb-Clone/
│── Back-end/  # Node.js server
│   ├── index.js  # Main server file
│   ├── package.json  # Dependencies
│   ├── routes/  # API routes
│   ├── models/  # Database models
│
│── Front-end/  # React app
│   ├── src/
│   ├── public/
│   ├── index.html
│   ├── vite.config.js
```

## Future Improvements
- Implement payment integration
- Add advanced search filters
- Deploy to production


