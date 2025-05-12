# Ecommerence Frontend (Angular)

## Project Description
This is the frontend for an e-commerce platform built with Angular. It provides a modern, responsive shopping experience, including product browsing, cart management, checkout with Stripe and Cash on Delivery, user authentication, and order tracking.

This is the public showcase version of the Angular frontend for the Ecommerence full-stack e-commerce platform.

Live Demo: https://nshoppe.shop/login

## Features
- User registration and login
- Product catalog with categories and search
- Shopping cart and checkout
- Payment integration (Stripe, Cash on Delivery)
- Order history and details
- Responsive design for desktop and mobile
- Profile management

## Prerequisites
- Node.js (v16 or higher recommended)
- npm (v8 or higher)
- Angular CLI (`npm install -g @angular/cli`)

## Installation
1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd EcommerenceFrontEnd/ecommerencefrontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```

## Running the App
Start the development server:

### Run Locally

```bash
ng serve

```
Visit [http://localhost:4200](http://localhost:4200) in your browser.

### Build for Production
```bash
ng build --configuration production
```

## Environment Configuration
Create or modify the following file:

```ts
// src/environments/environment.ts
export const environment = {
  production: false,
  apiUrl: 'https://swagger-nshoppe.com/api'  
};

## Folder Structure
- `src/app/pages/` — Main application pages (products, cart, checkout, account, etc.)
- `src/app/services/` — Angular services for API, authentication, cart, orders, etc.
- `src/app/models/` — TypeScript interfaces and models
- `src/app/core/` — Core utilities and shared services
- `src/assets/` — Static assets (images, logos, etc.)

## Technologies Used
- Angular 19
- Bootstrap 5
- RxJS
- Stripe API (for payments)
- REST API backend (for authentication, products, orders, user)

## Customization
- Update API endpoints in `environment.ts` as needed for your backend.
- Modify styles in `src/styles.css` or component-specific CSS files.

##  Contact

Want to collaborate or hire? Let's connect!  
Email: saimawkhann@gmail.com