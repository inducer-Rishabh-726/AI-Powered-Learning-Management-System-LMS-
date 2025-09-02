# 🎓 AI-Powered Learning Management System (LMS)
An AI-powered LMS SaaS platform built with Next.js, offering intelligent voice tutors, subscription management, and real-time interactive learning for a modern education experience.

## 🌟 Overview
Transform the way people learn with our cutting-edge AI-powered Learning Management System. This modern SaaS platform combines the power of artificial intelligence with intuitive design to create personalized, engaging educational experiences. Built with Next.js 14 and powered by advanced voice AI technology, our LMS offers interactive tutoring sessions that adapt to each learner's unique needs and pace.
Whether you're an educator looking to enhance your teaching methods or a learner seeking personalized guidance, our platform provides the tools and technology to make education more accessible, effective, and enjoyable. From voice-powered AI tutors to comprehensive progress tracking, every feature is designed to maximize learning outcomes.

## 📖 About

### The Vision
We believe that learning should be personal, interactive, and accessible to everyone. Our AI-powered LMS bridges the gap between traditional education and the future of learning by leveraging conversational AI technology. Students can engage with specialized AI tutors through natural voice interactions, making complex subjects more approachable and learning more engaging.

### What Makes Us Different
- **Conversational Learning**: Our AI voice tutors don't just deliver content—they engage in meaningful conversations, answer questions, and adapt their teaching style to match each student's learning preferences
- **Scalable SaaS Architecture**: Built from the ground up as a Software-as-a-Service platform, designed to grow with your educational needs
- **Modern Technology Stack**: Leveraging the latest in web development, AI, and cloud technologies to ensure optimal performance and reliability
- **User-Centric Design**: Every interface element is crafted with the user experience in mind, ensuring both educators and learners can focus on what matters most—learning

### Core Philosophy
Education should evolve with technology, not be constrained by it. Our platform empowers educators to create more impactful learning experiences while giving students the personalized attention they deserve. By combining human expertise with AI capabilities, we're not replacing teachers—we're amplifying their impact and making quality education more accessible to learners everywhere.

## ✨ Features

### 🤖 AI & Learning
- **AI Voice Agents**: Conversational AI tutors specializing in various subjects
- **Custom Tutor Creation**: Build personalized AI tutors with specific subjects and conversation styles
- **Interactive Sessions**: Real-time voice interactions with low-latency responses
- **Session History**: Track and review previous learning sessions

### 🔐 Authentication & Security
- **Secure Authentication**: Multi-provider sign-in with Clerk (Google, email, etc.)
- **User Management**: Comprehensive user profiles and preferences
- **Role-based Access**: Different permission levels for students and administrators

### 💳 Subscription & Billing
- **Flexible Plans**: Multiple subscription tiers with different features
- **Payment Processing**: Secure payment handling with Stripe integration
- **Billing Management**: Easy plan upgrades, downgrades, and payment details management
- **Usage Analytics**: Track learning progress and platform usage

### 📱 User Experience
- **Modern UI/UX**: Clean, intuitive design built with shadcn/ui components
- **Responsive Design**: Seamless experience across desktop, tablet, and mobile devices
- **Search & Discovery**: Advanced search functionality with filters
- **Bookmarking System**: Save and organize favorite tutors and content
- **Real-time Updates**: Live data synchronization across all devices

### 🔧 Technical Features
- **Performance Monitoring**: Error tracking and optimization with Sentry
- **Type Safety**: Full TypeScript implementation for robust development
- **Schema Validation**: Data integrity with Zod validation
- **Modular Architecture**: Reusable components and scalable codebase

## 🛠️ Tech Stack

### Frontend
- **[Next.js 14](https://nextjs.org/)** - React framework with server-side rendering
- **[TypeScript](https://www.typescriptlang.org/)** - Type-safe JavaScript development
- **[Tailwind CSS](https://tailwindcss.com/)** - Utility-first CSS framework
- **[shadcn/ui](https://ui.shadcn.com/)** - Modern component library

### Backend & Database
- **[Supabase](https://supabase.com/)** - Backend-as-a-Service with PostgreSQL
- **[Clerk](https://clerk.com/)** - Authentication and user management
- **[Zod](https://zod.dev/)** - TypeScript-first schema validation

### AI & Voice
- **[Vapi](https://vapi.ai/)** - Voice AI platform for conversational agents

### Monitoring & Analytics
- **[Sentry](https://sentry.io/)** - Error tracking and performance monitoring

## 🚀 Quick Start

### Prerequisites

Ensure you have the following installed:

- **Node.js** (v18 or higher)
- **npm** or **yarn**
- **Git**

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/adrianhajdin/saas-app.git
   cd saas-app
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env
   ```
   Then fill in your environment variables (see [Environment Setup](#-environment-setup))

4. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

5. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 🔧 Environment Setup

Create a `.env` file in the root directory with the following variables:

```env
# Sentry Configuration
SENTRY_AUTH_TOKEN=your_sentry_auth_token

# Vapi Voice AI
NEXT_PUBLIC_VAPI_WEB_TOKEN=your_vapi_web_token

# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_IN_FALLBACK_REDIRECT_URL=/
NEXT_PUBLIC_CLERK_SIGN_UP_FALLBACK_REDIRECT_URL=/

# Supabase Database
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
```

### 🔑 Getting API Keys

1. **[Supabase](https://supabase.com/)** - Create a project and get your URL and anon key
2. **[Clerk](https://clerk.com/)** - Set up authentication and get your keys
3. **[Sentry](https://sentry.io/)** - Create a project for error monitoring
4. **[Vapi](https://vapi.ai/)** - Sign up for voice AI capabilities

## 📁 Project Structure

```
saas-app/
├── app/                    # Next.js 14 app directory
│   ├── (auth)/            # Authentication routes
│   ├── (dashboard)/       # Dashboard pages
│   ├── api/               # API routes
│   └── globals.css        # Global styles
├── components/            # Reusable UI components
│   ├── ui/               # shadcn/ui components
│   └── shared/           # Custom shared components
├── lib/                  # Utility functions and configurations
├── hooks/                # Custom React hooks
├── types/                # TypeScript type definitions
├── public/               # Static assets
└── README.md
```

---

**Ready to revolutionize online learning? Get started today!** 🚀
