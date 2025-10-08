# Adople AI Marketplace

A modern, feature-rich marketplace platform built with Next.js 15, showcasing AI-powered software tools and digital products. This marketplace provides a seamless shopping experience with dark/light theme support, product showcases, and integrated cart functionality.

## 🚀 Features

### Core Functionality
- **Product Showcase**: Beautiful product pages with detailed descriptions, pricing, and reviews
- **Shopping Cart**: Integrated cart system with tier-based pricing
- **Theme Support**: Dark and light mode with persistent theme selection
- **Responsive Design**: Mobile-first design that works across all devices
- **Product Categories**: Organized product browsing with filtering capabilities

### Product Categories
- **AI Agents**: Voice agents and AI-powered tools
- **Email Tools**: Email verification and management solutions
- **Document Processing**: PDF and document analysis tools
- **Streaming Tools**: Live streaming and content creation software
- **Business Tools**: Various business productivity applications

### Technical Features
- **Next.js 15**: Latest React framework with App Router
- **TypeScript**: Full type safety throughout the application
- **Tailwind CSS**: Utility-first CSS framework for styling
- **Radix UI**: Accessible component primitives
- **Lucide React**: Beautiful icon library
- **Form Handling**: React Hook Form with Zod validation

## 🛠️ Tech Stack

- **Framework**: Next.js 15 with App Router
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **UI Components**: Radix UI primitives
- **Icons**: Lucide React
- **Forms**: React Hook Form + Zod
- **Theme**: next-themes
- **Analytics**: Vercel Analytics

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Ajay2k04/AdopleAI_Marketplace.git
   cd AdopleAI_Marketplace
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   pnpm install
   # or
   yarn install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   # or
   pnpm dev
   # or
   yarn dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 🏗️ Project Structure

```
├── app/                          # Next.js App Router
│   ├── (site)/                   # Site pages
│   │   ├── about/               # About page
│   │   ├── contact/             # Contact page
│   │   ├── login/               # Authentication
│   │   └── signup/              # User registration
│   ├── products/                # Product pages
│   │   ├── ai-agents/           # AI Agents product
│   │   ├── email-verifier/      # Email verification tool
│   │   ├── document-insights/   # Document processing
│   │   └── restreamer/          # Streaming tools
│   ├── cart/                    # Shopping cart
│   ├── checkout/                # Checkout process
│   └── deals/                   # Special offers
├── components/                   # Reusable components
│   ├── ui/                      # UI component library
│   └── theme-provider.tsx       # Theme management
├── lib/                         # Utility functions
│   ├── products.ts              # Product data
│   ├── cart.ts                  # Cart functionality
│   └── utils.ts                 # Helper utilities
└── public/                      # Static assets
```

## 🎨 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## 🛍️ Products

### Featured Products

1. **Adople Voice Agent** - Transform static documents into dynamic conversations
2. **Email Verifier Pro** - Advanced email validation and verification
3. **Document Insights** - AI-powered document analysis
4. **Restreamer Pro** - Professional live streaming solution
5. **Grigora** - Business automation platform
6. **Jodian** - Project management and collaboration tool

### Pricing Tiers

- **Starter**: Basic features for individuals
- **Professional**: Advanced features for small teams
- **Enterprise**: Full features for large organizations

## 🎯 Key Pages

- **Homepage** (`/`) - Main landing page with featured products
- **Products** (`/products/*`) - Individual product pages
- **Deals** (`/deals`) - Special offers and discounts
- **Cart** (`/cart`) - Shopping cart management
- **Checkout** (`/checkout`) - Purchase completion
- **Learn** (`/learn/*`) - Educational content and guides

## 🔧 Configuration

### Environment Variables

Create a `.env.local` file in the root directory:

```env
NEXT_PUBLIC_APP_URL=http://localhost:3000
# Add other environment variables as needed
```

### Theme Configuration

The app supports both dark and light themes. Theme preference is stored in localStorage and persists across sessions.

## 🚀 Deployment

### Vercel (Recommended)

1. Push your code to GitHub
2. Connect your repository to Vercel
3. Deploy with zero configuration

### Other Platforms

The app can be deployed to any platform that supports Next.js:
- Netlify
- AWS Amplify
- Railway
- DigitalOcean App Platform

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🆘 Support

For support, email support@adople.ai or join our Discord community.

## 🔗 Links

- **Website**: [Adople AI](https://adople.ai)
- **Documentation**: [Docs](https://docs.adople.ai)
- **Community**: [Discord](https://discord.gg/adople)

---

Built with ❤️ by the Adople AI Team