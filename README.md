# 10-web-time-display

# 10 Web Time Display

A high-fidelity digital timekeeping application featuring precision mechanics, customizable visual themes, and an immersive user interface.

## Tech Stack

- **Frontend**: React 19, TypeScript, Tailwind CSS v4
- **Build Tool**: Vite 6
- **Icons**: Lucide React
- **Animations**: Framer Motion
- **Testing**: Vitest



## ✨ Features

This repository has been upgraded with the following features:

1. **Add React.memo for performance** ✅
2. **Implement custom hooks** ✅
3. **Add context API for state** ✅
4. **Implement lazy loading** ✅
5. **Add error boundaries** ✅
6. **Create reusable components** ✅
7. **Add TypeScript types** ✅
8. **Implement responsive design** ✅
9. **Add animations with Framer Motion** ✅
10. **Create unit tests with React Testing Library** ✅

---

## 🚀 Quick Start

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build
```

## 📦 Tech Stack

- Modern web framework
- Optimized for performance
- Responsive design
- Accessibility ready

## 🛠️ Installation

```bash
git clone https://github.com/mk-knight23/10-web-time-display.git
cd 10-web-time-display
npm install
```

## 🏗️ Architecture

### Project Structure

```
10-web-time-display/
├── src/
│   ├── components/      # React components
│   │   ├── clock/      # Clock display components
│   │   ├── controls/   # UI controls
│   │   └── theme/      # Theme switcher
│   ├── hooks/          # Custom React hooks
│   │   ├── useTime.ts  # Time management hook
│   │   └── useTheme.ts # Theme management hook
│   ├── context/        # React Context providers
│   │   └── ThemeContext.tsx
│   ├── types/          # TypeScript type definitions
│   └── main.tsx        # Application entry point
├── public/             # Static assets
├── index.html          # HTML template
├── vite.config.ts      # Vite configuration
├── tsconfig.json       # TypeScript configuration
└── tailwind.config.ts  # Tailwind CSS configuration
```

### Technology Stack

| Layer | Technology |
|-------|------------|
| **Frontend** | React 19 + TypeScript |
| **Build Tool** | Vite 6 |
| **Styling** | Tailwind CSS v4 |
| **Animations** | Framer Motion |
| **Icons** | Lucide React |
| **Testing** | Vitest |
| **Deployment** | Vercel, Firebase, Render |

### Key Architectural Patterns

- **Component Composition**: Reusable clock components
- **Custom Hooks**: Time and theme management logic
- **Context API**: Global theme state
- **Type Safety**: Full TypeScript coverage
- **Performance**: React.memo, lazy loading
- **Error Handling**: Error boundaries
- **Animation**: Framer Motion for smooth transitions

### Data Flow

```
useTime Hook → Time Update → Clock Component → UI Render
useTheme Hook → Theme State → ThemeContext → Component Theme
```

## 🌐 Deployment

### Live URLs

| Platform | URL |
|----------|-----|
| Vercel | [Deployed Link] |
| Firebase | [Deployed Link] |
| Render | [Deployed Link] |

### Deploy to Vercel

```bash
# Install Vercel CLI
npm install -g vercel

# Deploy
vercel
```

### Deploy to Firebase

```bash
# Install Firebase CLI
npm install -g firebase-tools

# Initialize Firebase (if not done)
firebase init hosting

# Build
npm run build

# Deploy
firebase deploy
```

### Deploy to Render

```bash
# Install Render CLI
npm install -g render

# Deploy
render deploy
```

### Environment Variables

Create `.env.local`:

```env
# API keys if needed
VITE_API_KEY=your_api_key
```

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

### Setup

```bash
# Clone and navigate
git clone https://github.com/mk-knight23/10-web-time-display.git
cd 10-web-time-display

# Install dependencies
npm install

# Start development server
npm run dev
```

### Making Changes

1. Create a feature branch: `git checkout -b feature/your-feature`
2. Make your changes to components
3. Run tests: `npm run test`
4. Run type checking: `npm run type-check`
5. Test locally
6. Submit a pull request with description

### Code Style Guidelines

- Use TypeScript for all files
- Follow React best practices
- Use functional components with hooks
- Write descriptive variable names
- Add comments for complex logic
- Ensure accessibility (ARIA labels, keyboard nav)
- Test on mobile and desktop

### Feature Ideas

- Add world clock with timezone support
- Implement stopwatch/timer functionality
- Add alarm/snooze features
- Create custom clock themes
- Add sound effects
- Implement weather integration
- Create calendar view

### Testing

```bash
# Run tests
npm run test

# Run tests with coverage
npm run test:coverage

# Run type checking
npm run type-check
```

## 📝 License

MIT

---

*Last updated: 2026-02-28*

