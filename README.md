🔥Demo: https://crm-system-ui.vercel.app/
 # CRM System

[![License: Fair-code](https://img.shields.io/badge/License-Fair--code-blue.svg)](https://github.com/Hoaivuxuan/crm-system)
[![Node](https://img.shields.io/badge/Node-v20.9.0-green.svg)](https://nodejs.org/)
[![NPM](https://img.shields.io/badge/NPM-v10.2.4-red.svg)](https://www.npmjs.com/)

## Introduction

System ERP-CRM is a comprehensive business management solution that helps optimize processes, improve operational efficiency, and drive revenue growth. The system is designed with a modern user interface and integrates complete customer management, sales, human resources, and financial management functionalities.

## Key Features

- **Customer Relationship Management (CRM)**
  - Track customer information and interaction history
  - Manage business opportunities and leads
  - Analyze customer behavior

- **Sales Management**
  - Automated order processing
  - Quote and contract management
  - Real-time sales reporting

- **Human Resources Management**
  - Employee tracking and performance monitoring
  - Salary and benefits management
  - Work performance evaluation

- **Financial Management**
  - Income and expense tracking
  - Invoice and payment management
  - Financial reporting

## Technologies Used

### Frontend
- React 18
- Vite
- Ant Design
- Redux Toolkit
- React Router
- Axios

### Backend
- Node.js
- Express
- MongoDB
- JWT Authentication
- AWS S3

## Installation and Setup

### System Requirements
- Node.js v20.9.0
- NPM v10.2.4
- MongoDB

### Step 1: Clone the repository
```bash
git clone https://github.com/Hoaivuxuan/crm-system
cd crm-system
```

### Step 2: Install dependencies

#### Backend
```bash
cd backend
npm install
```

#### Frontend
```bash
cd frontend
npm install
```

### Step 3: Configure environment
Create a `.env` file in the backend directory based on the provided `.env.example` file

### Step 4: Initialize the database
```bash
cd backend
npm run setup
```

### Step 5: Run the application

#### Development mode
```bash
# Terminal 1 - Backend
cd backend
npm run dev

# Terminal 2 - Frontend
cd frontend
npm run dev
```

#### Production mode
```bash
# Backend
cd backend
npm run production

# Frontend
cd frontend
npm run build
```

## Deployment

The system is configured for deployment on Vercel using the `vercel.json` configuration file in the root directory.

## Author

- **Hoaivuxuan** - [GitHub](https://github.com/Hoaivuxuan)

## License

This project is licensed under the Fair-code License - see the LICENSE file for details.

## Contact

Email: vuxuanhoai28@gmail.com

## Contribution

We welcome contributions from the community. Please read the contribution guidelines in the CONTRIBUTING.md file before submitting a Pull Request.
