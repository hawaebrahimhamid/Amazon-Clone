# Amazon Clone — Full-Stack E-Commerce Application

A full-stack e-commerce application inspired by Amazon, built with React, Firebase, Express, and Stripe. The project demonstrates authentication, state management, API integration, protected routes, and payment processing.

**Live Demo:** https://amazon-clone-ne.netlify.app

## Features

* User registration and sign-in with Firebase Authentication
* Product and category browsing using the Fake Store API
* Shopping cart and global state management with React Context and `useReducer`
* Protected orders and checkout flows
* Stripe payment integration with PaymentIntents
* Firebase Cloud Functions and Express backend
* Responsive, component-based React interface
* Firestore integration for application data

## Tech Stack

**Frontend**

* React
* React Router
* React Context API
* Material UI
* Axios

**Backend & Services**

* Firebase Authentication
* Cloud Firestore
* Firebase Cloud Functions
* Express.js
* Stripe

**APIs**

* Fake Store API
* Stripe API

## Architecture

```text
React Frontend
     │
     ├── Firebase Authentication
     ├── Firestore
     ├── Fake Store API
     │
     └── Firebase Cloud Functions
              │
              └── Express + Stripe PaymentIntents
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/hawaebrahimhamid/Amazon-Clone.git
cd Amazon-Clone/Amazon_icon_svg
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start the development server

```bash
npm start
```

The application will run at:

```text
http://localhost:3000
```

### 4. Create a production build

```bash
npm run build
```

## Project Highlights

* Implemented Firebase-based authentication and authentication state management.
* Built reusable React components and application-wide state management with Context API and `useReducer`.
* Integrated protected routes for authenticated user flows.
* Implemented Stripe checkout using a Firebase Cloud Functions backend and Stripe PaymentIntents.
* Integrated external product data through the Fake Store API.
* Structured the application into reusable pages, components, API services, and utility modules.

## Repository

GitHub: https://github.com/hawaebrahimhamid/Amazon-Clone
