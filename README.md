````md
# Room Forge

A modern full-stack web platform for creating and managing virtual escape room experiences. Room Forge enables creators to design interactive puzzle-based environments with AI-assisted workflows, real-time cloud integration, and scalable architecture.

---

## Live Demo

https://room-forge.vercel.app

---

## Features

- Drag-and-drop room builder
- Interactive puzzle creation tools
- AI-powered puzzle suggestions
- Real-time Firebase database integration
- Secure user authentication
- Responsive modern UI
- Analytics and player tracking
- Type-safe development using TypeScript
- Cloud deployment with Vercel

---

## Tech Stack

| Category | Technology |
|----------|-------------|
| Framework | Next.js 15 |
| Language | TypeScript |
| Frontend | React 18 |
| Styling | Tailwind CSS |
| UI Components | Radix UI |
| Database | Firebase Firestore |
| Authentication | Firebase Auth |
| AI Integration | Google Genkit |
| Forms | React Hook Form + Zod |
| Charts | Recharts |
| Deployment | Vercel |

---

## Installation

### Clone Repository

```bash
git clone https://github.com/Namrathasindhu113/Room-forge.git

cd Room-forge
````

### Install Dependencies

```bash
npm install
```

### Configure Environment Variables

Create a `.env.local` file in the root directory.

```env
NEXT_PUBLIC_FIREBASE_API_KEY=

NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=

NEXT_PUBLIC_FIREBASE_PROJECT_ID=

NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=

NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=

NEXT_PUBLIC_FIREBASE_APP_ID=

GENKIT_API_KEY=
```

---

## Running the Project

### Development Server

```bash
npm run dev
```

Application runs at:

```bash
http://localhost:9002
```

---

## Available Scripts

| Command              | Description                  |
| -------------------- | ---------------------------- |
| npm run dev          | Start development server     |
| npm run build        | Build production application |
| npm start            | Start production server      |
| npm run lint         | Run ESLint                   |
| npm run typecheck    | TypeScript validation        |
| npm run genkit:dev   | Start AI development server  |
| npm run genkit:watch | Start AI watch mode          |

---

## Project Structure

```bash
src/
├── app/
├── ai/
├── components/
├── lib/
├── styles/

public/
package.json
tsconfig.json
```

---

## Production Build

```bash
npm run build

npm start
```

---

## Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit changes
4. Push the branch
5. Open a Pull Request

---

## License

This project is licensed under the MIT License.

---

## Author

Namratha Sindhu M
AI and Full Stack Developer

---

## Project Vision

Room Forge is designed to simplify virtual escape room creation through modern web technologies, scalable infrastructure, and AI-assisted game design workflows.

```
```
