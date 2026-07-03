# 🌾 AGRO ASSIST - Smart Agriculture Web Portal

> Empowering farmers with AI-driven soil analysis, crop recommendations, yield predictions, and real-time market prices.

[![Deployed on Vercel](https://img.shields.io/badge/Deployed-Vercel-000000?logo=vercel)](https://agro-assist-zeta.vercel.app)

## 📋 Overview

**AGRO ASSIST** is an intelligent agricultural platform designed to help farmers make data-driven decisions. By leveraging computer vision and AI, it analyzes soil conditions from photos and provides personalized recommendations for crop selection, yield estimation, and market price insights.

### Key Features

- 📸 **Soil Image Analysis** - Upload soil photos for instant analysis
- 🌱 **Crop Recommendations** - Get personalized crop suggestions based on soil conditions
- 📊 **Yield Estimation** - Predict crop yields with AI models
- 💰 **Market Prices** - Real-time agricultural market pricing data
- 🌐 **Multi-language Support** - Available in English and Tamil
- 📱 **Responsive Design** - Works seamlessly on desktop and mobile devices

## 🛠️ Tech Stack

### Frontend
- **React 18.3** - UI library with modern hooks
- **TypeScript** - Type-safe JavaScript
- **Vite** - Lightning-fast build tool
- **TailwindCSS** - Utility-first styling
- **shadcn/ui** - High-quality component library built on Radix UI
- **React Router v6** - Client-side routing
- **React Hook Form + Zod** - Form handling with validation

### Backend & Database
- **Supabase** - PostgreSQL database and authentication
- **TanStack React Query** - Server state management and caching

### Deployment
- **Vercel** - Serverless hosting and CI/CD

### UI/UX Components
- **Radix UI** - Unstyled, accessible components
- **Lucide React** - Icon library
- **Sonner** - Toast notifications
- **Recharts** - Data visualization

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ or Bun runtime
- npm, yarn, or bun package manager

### Installation

```bash
# Clone the repository
git clone https://github.com/Aswin-5018/agro-assist.git
cd agro-assist

# Install dependencies
npm install
# or
bun install

# Set up environment variables
cp .env.example .env.local
# Add your Supabase credentials to .env.local
```

### Development

```bash
# Start the development server
npm run dev
# or
bun run dev

# The app will be available at http://localhost:5173
```

### Build

```bash
# Create a production build
npm run build

# Preview the production build locally
npm run preview
```

## 📁 Project Structure

```
agro-assist/
├── src/
│   ├── pages/              # Application pages (Index, Analyze, Results)
│   ├── components/         # Reusable UI components
│   ├── lib/               # Utility functions and helpers
│   ├── App.tsx            # Main app component with routing
│   └── main.tsx           # Entry point
├── supabase/              # Database migrations and schema
├── public/                # Static assets
├── index.html             # HTML template
├── vite.config.ts         # Vite configuration
├── tailwind.config.ts     # TailwindCSS configuration
└── tsconfig.json          # TypeScript configuration
```

## 🔄 Workflow

1. **Home Page** - User uploads soil photo and enters location details
2. **Analysis Page** - AI analyzes the soil image and processes data
3. **Results Page** - Displays crop recommendations, yield predictions, and market prices

## 🔐 Environment Variables

Create a `.env.local` file in the root directory:

```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

## 📝 Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server |
| `npm run build` | Create production build |
| `npm run build:dev` | Build with development mode |
| `npm run preview` | Preview production build |
| `npm run lint` | Run ESLint code checker |

## 🌐 Live Demo

Visit the deployed application: [https://agro-assist-zeta.vercel.app](https://agro-assist-zeta.vercel.app)

## 📊 Language Stats

- **TypeScript**: 96.7%
- **CSS**: 2.1%
- **Other**: 1.2%

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

### Steps to contribute:
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the MIT License.

## 👤 Author

**Aswin** - [GitHub Profile](https://github.com/Aswin-5018)

## 💡 Acknowledgments

- Built with [shadcn/ui](https://ui.shadcn.com) components
- Hosted on [Vercel](https://vercel.com)
- Database powered by [Supabase](https://supabase.com)

---

**Star ⭐ this repo if you find it helpful!**
