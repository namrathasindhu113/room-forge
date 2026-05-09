# Room Forge

A modern, full-stack web application for room and space management, built with cutting-edge technologies and cloud-native architecture.

**Live Demo:** [room-forge.vercel.app](https://room-forge.vercel.app)

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Available Scripts](#available-scripts)
- [Configuration](#configuration)
- [Development](#development)
- [Building for Production](#building-for-production)
- [Contributing](#contributing)
- [License](#license)
- [About](#about)

## 🎯 Overview

Room Forge is a comprehensive solution for managing room bookings and space allocation. It leverages modern web technologies including Next.js 15, React 18, Firebase, and Google's Genkit AI framework to provide an intuitive and powerful user experience.

The application features a robust component library built with Radix UI, type-safe form handling with React Hook Form and Zod validation, and responsive data visualization powered by Recharts.

## ✨ Features

- **User-Friendly Interface**: Built with Radix UI components for accessibility and consistency
- **Real-Time Database**: Firebase integration for seamless data synchronization
- **Form Validation**: Robust form handling with React Hook Form and Zod schema validation
- **AI-Powered Insights**: Genkit AI integration for intelligent recommendations
- **Data Visualization**: Interactive charts and analytics with Recharts
- **Type Safety**: Full TypeScript support for enhanced development experience
- **Responsive Design**: Mobile-first approach with Tailwind CSS
- **Authentication**: Secure Firebase authentication

## 🛠️ Tech Stack

| Category | Technology |
|----------|-----------|
| **Framework** | Next.js 15 |
| **Runtime** | Node.js 20 |
| **Language** | TypeScript |
| **Styling** | Tailwind CSS |
| **UI Components** | Radix UI |
| **Database** | Firebase |
| **Authentication** | Firebase Auth |
| **Forms** | React Hook Form + Zod |
| **AI/ML** | Google Genkit |
| **Charts** | Recharts |
| **Package Manager** | npm |

## 📋 Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js 20** or higher
- **npm** or **yarn** package manager
- A **Firebase project** with Firestore and Authentication enabled
- **Google Cloud** account with Genkit API access

## 🚀 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Namrathasindhu113/Room-forge.git
cd Room-forge
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env.local` file in the root directory and add your Firebase and Genkit credentials:

```env
# Firebase Configuration
NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_auth_domain
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_storage_bucket
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id

# Genkit Configuration
GENKIT_API_KEY=your_genkit_api_key
```

## 🎯 Getting Started

### Development Server

Start the development server with Turbopack for faster builds:

```bash
npm run dev
```

The application will be available at `http://localhost:9002`

### Type Checking

Ensure all TypeScript types are correct:

```bash
npm run typecheck
```

## 📁 Project Structure

```
src/
├── app/                    # Next.js app directory
│   └── page.tsx           # Main entry point
├── ai/                    # AI/Genkit integration
│   └── dev.ts             # Development AI configuration
├── components/            # Reusable React components
├── lib/                   # Utility functions and helpers
└── styles/                # Global styles

public/                    # Static assets
.env.local                 # Environment variables (not committed)
package.json              # Project dependencies
tsconfig.json             # TypeScript configuration
```

## 📝 Available Scripts

| Command | Description |
|---------|------------|
| `npm run dev` | Start development server with Turbopack on port 9002 |
| `npm run genkit:dev` | Start Genkit AI development server |
| `npm run genkit:watch` | Start Genkit with file watching enabled |
| `npm run build` | Build optimized production bundle |
| `npm start` | Start production server |
| `npm run lint` | Run ESLint to check code quality |
| `npm run typecheck` | Type-check TypeScript without emitting files |

## ⚙️ Configuration

### Firebase Setup

1. Create a Firebase project at [firebase.google.com](https://firebase.google.com)
2. Enable Firestore Database and Authentication
3. Add your credentials to `.env.local`

### Genkit AI Setup

1. Enable the Genkit API in your Google Cloud project
2. Create appropriate service credentials
3. Add your API key to `.env.local`

## 💻 Development

### Code Quality

This project includes built-in linting and type checking:

```bash
# Check for linting issues
npm run lint

# Fix linting issues automatically
npm run lint -- --fix

# Validate TypeScript
npm run typecheck
```

### Development with AI Features

To develop with Genkit AI features:

```bash
npm run genkit:watch
```

This starts the Genkit development server with file watching for real-time updates.

## 🏗️ Building for Production

### Create Optimized Build

```bash
npm run build
```

### Start Production Server

```bash
npm start
```

The production build is optimized for performance and ready for deployment on platforms like Vercel.

## 🤝 Contributing

Contributions are welcome! Please follow these guidelines:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the MIT License. See the LICENSE file for details.

## 📞 Support

For issues, questions, or suggestions, please:

- Open an issue on [GitHub Issues](https://github.com/Namrathasindhu113/Room-forge/issues)
- Check existing documentation and closed issues
- Contact the maintainer

## 👤 About

**Author:** [Namrathasindhu113](https://github.com/Namrathasindhu113)  
**Role:** Full Stack Developer  
**Project:** Room Forge - Space & Room Management System

This project is maintained and actively developed by Namratha Sindhu M. For more information about the author or to collaborate, feel free to reach out through GitHub.

---

**Last Updated:** May 2026  
**Maintained by:** [Namrathasindhu113](https://github.com/Namrathasindhu113)
