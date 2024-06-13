# Eats.com Backend

Welcome to the Eats.com backend repository! This project provides the API and server-side functionalities for the Eats.com application, built with Node.js, Express, and MongoDB.

## Live Demo
Check out the live site: https://eats-com-backend.onrender.com

## Features
- **Node.js** with **Express** for scalable server-side logic
- **MongoDB** for database management
- **Auth0** for secure authentication
- **Stripe** for payment processing
- **Cloudinary** for image handling

## Installation

1. Clone the repository
    ```bash
    git clone https://github.com/rohanbabbar983/Eats.com-Backend.git
    cd Eats.com-Backend
    ```

2. Install dependencies
    ```bash
    npm install
    ```

3. Create a `.env` file in the root directory and add the necessary environment variables:
    ```env
    PORT=7000
    MONGODB_CONNECTION_STRING=your_mongo_uri
    AUTH0_AUDIENCE=your_auth0_audience
    AUTH0_ISSUER_BASE_URL=your_auth0_issuer_base_url
    STRIPE_SECRET_KEY=your_stripe_secret_key
    STRIPE_WEBHOOK_SECRET=your_stripe_webhook_secret
    CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
    CLOUDINARY_API_KEY=your_cloudinary_api_key
    CLOUDINARY_API_SECRET=your_cloudinary_api_secret
    FRONTEND_URL=your_frontend_url
    ```

4. Start the server
    ```bash
    npm run dev
    ```

## Usage

The backend server will run on `http://localhost:7000`.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
