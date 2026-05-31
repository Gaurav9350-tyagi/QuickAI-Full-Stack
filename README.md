QuickAI – AI-Powered Content & Image Generation Platform
A modern full-stack AI SaaS application that enables users to generate articles, blog titles, AI images, remove image backgrounds, remove unwanted objects, and analyze resumes using cutting-edge AI technology.
[Live Demo]: https://quick-ai-full-stack-7jrr-r4lutwan5.vercel.app/

About The Project
QuickAI is a feature-rich AI-powered SaaS platform designed to simplify content creation and image editing workflows. The application combines multiple AI tools into a single intuitive dashboard, allowing users to generate high-quality content, create AI-generated images, perform advanced image editing, and receive professional resume feedback.
Built with a modern React frontend and Node.js backend, QuickAI demonstrates full-stack development skills including authentication, API integration, cloud storage, AI services, and responsive UI design.
The project focuses on providing a seamless user experience while integrating real-world AI capabilities commonly found in modern SaaS products.


## Key Features

### 🔐 Authentication & User Management

* Secure user authentication and authorization with Clerk
* Protected routes and role-based access control
* Personalized user dashboard and content management

### 🤖 AI Content Generation

* AI-powered article generation
* Intelligent blog title creation
* Fast, scalable content generation workflows

### 🎨 AI Image Generation & Editing

* Text-to-image generation using AI
* Multiple artistic and realistic image styles
* Background removal and object removal capabilities
* Cloud-based image storage and management

### 📄 Resume Analysis

* AI-driven resume review and feedback
* Professional recommendations for improvement
* PDF resume upload and processing

### 🌐 Community & Content Sharing

* Publish and showcase AI-generated content
* Like and interact with community creations
* Public and private content visibility options

### 📊 User Dashboard

* Track and manage generated content
* Access creation history and analytics
* Centralized workspace for all AI tools

## Technologies Used

This project was built using modern full-stack technologies, cloud services, and AI integrations to deliver a scalable and production-ready SaaS application.

### Frontend

* **React.js** – Component-based UI development and state management.
* **Vite** – Fast development server and optimized production builds.
* **Tailwind CSS** – Utility-first CSS framework for responsive and modern UI design.
* **Axios** – HTTP client for seamless API communication.
* **React Router DOM** – Client-side routing and navigation.
* **React Hot Toast** – User-friendly notifications and alerts.
* **Clerk React SDK** – Secure authentication and user session management.
* **Lucide React** – Modern and customizable icon library.

### Backend

* **Node.js** – JavaScript runtime for scalable server-side applications.
* **Express.js** – Lightweight framework for building RESTful APIs.
* **Clerk Express SDK** – Authentication, authorization, and protected routes.
* **Multer** – File upload handling and processing.
* **Cloudinary SDK** – Cloud-based image storage and transformation.
* **REST APIs** – Structured communication between frontend and backend services.

### Database

* **Neon PostgreSQL** – Serverless PostgreSQL database for storing user data and generated content.

### AI Services

* **Google Gemini AI** – Powers article generation, blog title creation, and resume analysis.
* **AI Image Generation APIs** – Enables text-to-image creation and advanced image processing capabilities.

### Cloud & Deployment

* **Vercel** – Frontend and backend deployment with serverless infrastructure.
* **Cloudinary** – Media storage, optimization, and image transformations.
* **Neon Database** – Cloud-hosted PostgreSQL database with serverless architecture.

## How To Use

To run QuickAI locally on your system, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/Gaurav9350-tyagi/QuickAI-Full-Stack.git
```

### 2. Navigate to the Project Directory

```bash
cd QuickAI-Full-Stack
```

### 3. Setup the Backend

Navigate to the server folder and install dependencies:

```bash
cd server
npm install
```

Create a `.env` file and add the required environment variables:

```env
DATABASE_URL=
CLERK_SECRET_KEY=
GEMINI_API_KEY=
CLIPDROP_API_KEY=
CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=
```

Start the backend server:

```bash
npm run server
```

### 4. Setup the Frontend

Open a new terminal and navigate to the client folder:

```bash
cd client
npm install
```

Create a `.env` file and add:

```env
VITE_CLERK_PUBLISHABLE_KEY=
VITE_BASE_URL=http://localhost:3000
```

Start the frontend development server:

```bash
npm run dev
```

### 5. Open the Application

Visit:

```text
http://localhost:5173
```

Create an account or sign in to access the AI-powered tools, including article generation, blog title generation, image generation, image editing, and resume analysis.

Author
Gaurav Tyagi
