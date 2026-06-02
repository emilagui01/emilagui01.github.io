# Travlr Full Stack Application

## Overview

Travlr is a full-stack travel booking web application developed using the MEAN stack (MongoDB, Express, Angular, and Node.js). The application includes an Angular-based administrative interface, a Node.js/Express backend API, MongoDB database integration, and JWT-based authentication for secure access to protected routes.

This artifact was originally developed in **CS-465 Full Stack Development I** and is being used as an enhancement artifact for the **CS-499 Computer Science Capstone**.

## Features

* Angular single-page application (SPA)
* RESTful API architecture
* MongoDB database integration with Mongoose
* JWT authentication and authorization
* Protected API routes
* CRUD operations for trip management
* Reusable Angular components and services

## Project Structure

* `app_admin/` – Angular administrative frontend
* `app_api/` – API controllers, models, authentication, and routes
* `app_server/` – Express server-side rendering components
* `public/` – Static assets
* `data/` – Seed and supporting application data

## Running the Project

### Install Dependencies

Since `node_modules` was removed to reduce file size, dependencies must be reinstalled.

Run:

```bash
npm install
```

For Angular dependencies:

```bash
cd app_admin
npm install
```

### Start the Application

From the root directory:

```bash
npm start
```

For Angular development server:

```bash
cd app_admin
ng serve
```

## Notes

To reduce repository size, temporary and generated folders such as `node_modules` and `.angular` were intentionally excluded. These files can be recreated using the installation steps above.

