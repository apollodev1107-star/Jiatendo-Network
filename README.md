# Jiatendo Network

> **Bringing back Nintendo**

Jiatendo Network is an open-source program and free beta service that provides online functionality for Nintendo consoles. Similar to Pretendo, Wiimmfi, and Level256, but more advanced. We make servers 100x faster and enable open communication with developers around the world.

## 🎮 Supported Consoles

- Nintendo DS
- Nintendo DSi
- Nintendo 3DS
- Nintendo Wii
- Nintendo Wii U

## ✨ Features

- **User Authentication**: Secure registration and login system with JWT tokens
- **User Profiles**: Customizable user profiles with avatar support
- **Project Progression Tracking**: Real-time status updates on various game server developments
- **Blog System**: Share updates and news about the network
- **Team Showcase**: Meet the developers behind Jiatendo Network
- **FAQ Section**: Get answers to common questions
- **Responsive Design**: Beautiful, modern UI that works on all devices
- **Animated UI**: Smooth animations powered by Framer Motion
- **Snowfall Effect**: Festive seasonal animations

## 🛠️ Tech Stack

### Frontend
- **Next.js 15** - React framework with App Router
- **React 19** - UI library
- **TypeScript** - Type-safe development
- **Tailwind CSS 4** - Utility-first CSS framework
- **Framer Motion** - Animation library
- **Lucide React** - Icon library
- **React Icons** - Additional icon sets
- **Sonner** - Toast notifications

### Backend
- **Next.js API Routes** - Serverless API endpoints
- **MongoDB** - Database (via Mongoose)
- **JWT** - Authentication tokens
- **bcryptjs** - Password hashing

## 📋 Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js** (v18 or higher)
- **npm** or **yarn** or **pnpm**
- **MongoDB** (local instance or MongoDB Atlas connection string)

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/Blog-Site-UI.git
cd Blog-Site-UI
```

### 2. Install Dependencies

```bash
npm install
# or
yarn install
# or
pnpm install
```

### 3. Environment Variables

Create a `.env.local` file in the root directory and add the following:

```env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
```

**Example:**
```env
MONGODB_URI=mongodb://localhost:27017/jiatendo
JWT_SECRET=your_super_secret_jwt_key_here
```

> **Note**: For production, use a strong, randomly generated JWT secret. Never commit `.env.local` to version control.

### 4. Run the Development Server

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to see the result.

### 5. Build for Production

```bash
npm run build
npm start
```

## 📁 Project Structure

```
Blog-Site-UI/
├── public/                 # Static assets
│   ├── blog/              # Blog images
│   ├── images/            # General images
│   ├── screenshots/       # Screenshot assets
│   └── team/              # Team member images
├── src/
│   ├── app/               # Next.js App Router pages
│   │   ├── about/         # About page
│   │   ├── api/           # API routes
│   │   │   ├── auth/      # Authentication endpoints
│   │   │   └── user/      # User endpoints
│   │   ├── login/         # Login page
│   │   ├── register/      # Registration page
│   │   ├── profile/        # User profile page
│   │   ├── progression/   # Project progression page
│   │   └── supportlist/   # Support list page
│   ├── components/        # React components
│   │   ├── auth/          # Authentication components
│   │   ├── common/        # Shared components (Header, Footer)
│   │   ├── homeComponents/ # Homepage components
│   │   ├── progression/   # Progression components
│   │   └── snow/          # Snowfall animation
│   ├── context/           # React Context providers
│   ├── models/            # Database models
│   ├── styles/            # Global styles
│   └── utils/             # Utility functions
├── eslint.config.mjs      # ESLint configuration
├── next.config.ts         # Next.js configuration
├── package.json           # Dependencies and scripts
├── postcss.config.mjs     # PostCSS configuration
├── tailwind.config.ts     # Tailwind CSS configuration
└── tsconfig.json          # TypeScript configuration
```

## 🎯 Available Scripts

- `npm run dev` - Start development server with Turbopack
- `npm run build` - Build the application for production
- `npm start` - Start the production server
- `npm run lint` - Run ESLint to check code quality
- `npm run vercel-build` - Build script optimized for Vercel deployment

## 🔐 API Endpoints

### Authentication
- `POST /api/auth/register` - Register a new user
- `POST /api/auth/login` - Login user
- `GET /api/auth/me` - Get current user information

### User
- `GET /api/user/avatar` - Get user avatar

## 🤝 Contributing

Contributions are welcome! This project is open source and community-driven. We believe in people—no matter your country, background, or level, you deserve to thrive.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the **GNU Affero General Public License v3.0** (AGPL-3.0).

See the [LICENSE](LICENSE) file for more details.

## 🌐 Community

Join our community to get support, share ideas, and connect with other developers:

- **Discord**: [Join our Discord server](https://discord.gg/jiatendo) (supports all languages!)
- **GitHub**: [Report issues or suggest features](https://github.com/yourusername/Blog-Site-UI/issues)

## 🙏 Acknowledgments

- Inspired by Pretendo, Wiimmfi, and Level256
- Built with love by the Jiatendo Network team
- Special thanks to all contributors and the Nintendo homebrew community

## 📧 Contact

For questions, support, or collaboration opportunities, please reach out through our Discord server or open an issue on GitHub.

---

**Made with ❤️ by the Jiatendo Network Team**

*"The Ultimate Jias lives in every gamer's soul."*
