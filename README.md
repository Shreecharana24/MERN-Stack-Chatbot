# QuickGPT

QuickGPT is a full-stack AI chatbot web application built using the MERN stack (MongoDB, Express.js, React.js, and Node.js). The application enables users to generate AI-based text responses and create images from prompts through integrated AI models.

The project utilizes the Google Gemini AI model for text generation and ImageKit for image processing. A credit-based system is implemented, allowing users to purchase credits via an integrated payment gateway to access AI features.

---

## Features
- **User Authentication**: Secure signup and login functionality.
- **AI Text Generation**: Real-time text responses powered by Google Gemini.
- **AI Image Generation**: Prompt-to-image generation using ImageKit.
- **Credit System**: Logic-based usage tracking for AI features.
- **Payment Integration**: Online payment gateway for credit top-ups.
- **Responsive UI**: Fully adaptive interface built with React.
- **Secure Backend**: Robust API with environment-based configuration and JWT-based security.

---

## Project Motivation
Modern AI applications require the seamless integration of frontend interaction, backend logic, and third-party APIs. QuickGPT was developed to explore the architecture of AI-powered SaaS platforms, focusing on the intersection of generative models, secure payment processing, and state management in a full-stack environment.

---

## Quick Start

### 1. Prerequisites
- **Node.js** (v18 or later)
- **MongoDB** (Local instance or MongoDB Atlas)
- **API Keys**: Google Gemini, ImageKit, and Stripe

### 2. Installation & Setup
Run the following commands in your terminal to clone the project and install all necessary dependencies for both the frontend and backend:

```bash
# Clone the Repository
git clone [https://github.com/your-username/quickgpt.git](https://github.com/your-username/quickgpt.git)
cd quickgpt

# Install Server dependencies
cd server
npm install

# Install Client dependencies
cd ../client
npm install
```

### 3. Environment Configuration

Create a `.env` file inside the **server** directory and add the following environment variables:

```env
MONGO_URI=your_mongodb_connection_string
GEMINI_API_KEY=your_gemini_api_key

IMAGEKIT_PUBLIC_KEY=your_imagekit_public_key
IMAGEKIT_PRIVATE_KEY=your_imagekit_private_key
IMAGEKIT_URL_ENDPOINT=your_imagekit_url

STRIPE_SECRET_KEY=your_stripe_secret_key
```

### 4. Run the Application

Open two terminals to run the backend and frontend simultaneously:


```bash
cd server
npm start
```

```bash
cd client
npm run dev
```

The application will default to: http://localhost:5173

## Tech Stack

| Layer      | Technology |
|-----------|------------|
| Frontend  | React.js, Tailwind CSS |
| Backend   | Node.js, Express.js |
| Database  | MongoDB |
| AI Models | Google Gemini (Text), ImageKit (Image) |
| Payments  | Stripe |

