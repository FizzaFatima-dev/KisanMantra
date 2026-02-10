# 🌱 KisanMitra - Smart Farm Planning & Market Intelligence

KisanMitra is an AI-powered web application that helps farmers make informed decisions about crop selection, farm planning, and market access. Our mission is to reduce farming risks and improve profitability through data-driven insights.

## ✨ Features

- **Smart Crop Planner**: Get personalized crop recommendations based on location, soil type, water availability, and season
- **Budget & Loan Risk Checker**: Calculate affordability and debt risk for different crops
- **Smart Selling Plan**: Find the best markets, track prices, and avoid overproduction risks
- **Soil Scanner**: Upload soil photos for instant AI-powered analysis in multiple languages
- **Soil Type Guide**: Learn about different soil types and their characteristics
- **Marketplace**: Connect directly with buyers without middlemen for fair pricing
- **Farming Resources**: Access agricultural guides and expert tips
- **Expert Support**: Get in touch with agricultural experts for personalized guidance

## 🚀 Live Demo

Visit the live application: [https://farmer-crop-advisor.web.app](https://farmer-crop-advisor.web.app)

## 💻 Tech Stack

- **Frontend**: React 18.3 + TypeScript
- **Build Tool**: Vite
- **Styling**: Tailwind CSS + shadcn/ui components
- **State Management**: React Query, React Hook Form
- **Routing**: React Router v6
- **Icons**: Lucide React
- **Backend**: Firebase (Firestore, Authentication, Hosting)
- **Testing**: Vitest

## 📋 Prerequisites

- Node.js (v16 or higher)
- npm or bun
- Git
- Firebase CLI (for deployment)

## 🛠️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/your-repo-name.git
   cd your-repo-name
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   bun install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```
   The app will be available at `http://localhost:8080`

## 🏗️ Project Structure

```
src/
├── components/          # Reusable React components
│   ├── ui/             # shadcn/ui components
│   ├── SoilScanner.tsx
│   ├── SoilTypes.tsx
│   ├── CropRecommendations.tsx
│   ├── Marketplace.tsx
│   ├── Resources.tsx
│   ├── Contact.tsx
│   └── ...
├── pages/              # Page components
│   ├── Home.tsx        # Landing page
│   ├── FarmPlanner.tsx # Multi-step farm planning wizard
│   └── NotFound.tsx    # 404 page
├── hooks/              # Custom React hooks
├── lib/                # Utility functions
├── assets/             # Images and static files
├── App.tsx             # Main app component with routing
├── main.tsx            # Application entry point
└── index.css          # Global styles
```

## 📝 Available Scripts

- **`npm run dev`** - Start development server with hot reload
- **`npm run build`** - Build for production
- **`npm run preview`** - Preview production build locally
- **`npm run lint`** - Run ESLint to check code quality
- **`npm run test`** - Run tests with Vitest
- **`npm run test:watch`** - Run tests in watch mode

## 🚀 Deployment

### Deploy to Firebase Hosting

1. **Build the project**
   ```bash
   npm run build
   ```

2. **Deploy**
   ```bash
   firebase deploy --only hosting
   ```

The application will be deployed to Firebase Hosting.

## 🌐 Routes

- `/` - Home page with hero section and feature overview
- `/farm-plan` - Multi-step farm planning wizard
- `*` - 404 Not Found page

## 🎨 Design System

The app uses Tailwind CSS with a custom theme and shadcn/ui component library for consistent, accessible UI components.

## 🧪 Testing

Run tests with:
```bash
npm run test
```

Watch mode for development:
```bash
npm run test:watch
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License.

## 📞 Support

For issues, questions, or feedback:
- Open an issue on GitHub
- Email: info@AgroZinfo.com

---

**Made with 💚 for farmers, by the KisanMitra team**
- Edit files directly within the Codespace and commit and push your changes once you're done.

## What technologies are used for this project?

This project is built with:

- Vite
- TypeScript
- React
- shadcn-ui
- Tailwind CSS

## How can I deploy this project?

Simply open [Lovable](https://lovable.dev/projects/REPLACE_WITH_PROJECT_ID) and click on Share -> Publish.

## Can I connect a custom domain to my Lovable project?

Yes, you can!

To connect a domain, navigate to Project > Settings > Domains and click Connect Domain.

Read more here: [Setting up a custom domain](https://docs.lovable.dev/features/custom-domain#custom-domain)
