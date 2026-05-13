# ChatSync - Frontend

A modern, responsive frontend application for ChatSync, a microservice-based real-time chat platform. Built with Next.js and TypeScript, featuring real-time messaging, user authentication, and a sleek interface powered by Tailwind CSS.

## 🔗 Related Repositories

[![GitHub](https://img.shields.io/badge/Frontend-ChatSync%20Frontend-blue)](https://github.com/NavjotSuman/chatApp-microservice-Frontend)
[![GitHub](https://img.shields.io/badge/Backend-ChatSync%20Backend-green)](https://github.com/NavjotSuman/chatApp-microservice-Backend)

## 🚀 Features

- **Real-time Messaging**: Instant chat communication using Socket.io
- **User Authentication**: Secure login and registration with JWT tokens
- **Email Verification**: Account verification system for enhanced security
- **User Profiles**: Personalized user profiles and settings
- **Responsive Design**: Mobile-first design with Tailwind CSS
- **Modern UI**: Clean, intuitive interface with Lucide icons
- **Toast Notifications**: Real-time feedback and alerts using React Hot Toast

## 🛠️ Tech Stack

- **Framework**: Next.js 15 with App Router
- **Language**: TypeScript
- **Styling**: Tailwind CSS 4
- **State Management**: React Context API
- **Real-time Communication**: Socket.io Client
- **HTTP Client**: Axios
- **Icons**: Lucide React
- **Utilities**: Moment.js, JS-Cookie

## 📋 Prerequisites

- Node.js (v18 or higher)
- npm, yarn, pnpm, or bun
- Backend services running (see backend README)

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd frontend
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   # or
   bun install
   ```

3. **Environment Setup**
   Create a `.env.local` file in the root directory:
   ```env
   NEXT_PUBLIC_API_URL=http://localhost:5001
   NEXT_PUBLIC_SOCKET_URL=http://localhost:5002
   NEXT_PUBLIC_APP_ENV=development
   ```

4. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   # or
   bun dev
   ```

5. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📁 Project Structure

```
frontend/
├── src/
│   ├── app/                 # Next.js App Router pages
│   │   ├── chat/           # Chat interface page
│   │   ├── login/          # Login page
│   │   ├── profile/        # User profile page
│   │   ├── verify/         # Email verification page
│   │   ├── layout.tsx      # Root layout
│   │   ├── page.tsx        # Home page
│   │   └── globals.css     # Global styles
│   ├── components/         # Reusable React components
│   └── context/            # React Context providers
├── public/                 # Static assets
├── .env                    # Environment variables
├── next.config.ts          # Next.js configuration
├── tailwind.config.js      # Tailwind CSS configuration
└── package.json            # Dependencies and scripts
```

## 🔧 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## 🌐 API Integration

The frontend communicates with the following backend services:

- **User Service** (Port 5001): Authentication, user management
- **Chat Service** (Port 5002): Real-time messaging
- **Mail Service** (Port 5003): Email notifications

## 🔒 Environment Variables

| Variable | Description | Default |
|----------|-------------|---------|
| `NEXT_PUBLIC_API_URL` | User service API URL | `http://localhost:5001` |
| `NEXT_PUBLIC_SOCKET_URL` | Chat service WebSocket URL | `http://localhost:5002` |
| `NEXT_PUBLIC_APP_ENV` | Application environment | `development` |




## 👨‍💻 Author

**Navjot Suman**

## 🙏 Acknowledgments

- [Next.js](https://nextjs.org/) - The React Framework
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [Socket.io](https://socket.io/) - Real-time communication
- [Lucide](https://lucide.dev/) - Beautiful icons</content>
<parameter name="filePath">frontend/README.md