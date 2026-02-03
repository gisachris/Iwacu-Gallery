# Iwacu Gallery

A professional, client-side web application that showcases artworks from public museum APIs. Built with modern web technologies, prioritizing performance, accessibility, and maintainability.

## 🎨 Features

- **Museum API Integration**: Browse artworks from renowned museums worldwide
- **Responsive Design**: Optimized for all devices and screen sizes
- **Accessibility First**: WCAG 2.1 compliant with keyboard navigation and screen reader support
- **Performance Optimized**: Fast loading with efficient API caching and lazy loading
- **No Backend Required**: Fully client-side application using public APIs

## 🛠️ Tech Stack

- **Frontend**: TypeScript, Vite
- **Styling**: Tailwind CSS
- **APIs**: Public museum APIs (Metropolitan Museum, Rijksmuseum, etc.)
- **Build Tool**: Vite with Rolldown
- **Type Safety**: Full TypeScript implementation

## 🚀 Quick Start

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/iwacu-gallery.git
cd iwacu-gallery
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

## 📜 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally

## 🏗️ Project Structure

```
src/
├── api/          # API integration and data fetching
├── app/          # Application configuration and setup
├── components/   # Reusable UI components
├── pages/        # Page components and routing
├── styles/       # Global styles and Tailwind configuration
├── types/        # TypeScript type definitions
├── utils/        # Utility functions and helpers
└── main.ts       # Application entry point
```

## 🎯 API Integration

The application integrates with several public museum APIs:

- **Metropolitan Museum of Art API**: Extensive collection of artworks
- **Rijksmuseum API**: Dutch art and history
- **Harvard Art Museums API**: Academic art collection

All API calls are made client-side with proper error handling and loading states.

## ♿ Accessibility

- Semantic HTML structure
- ARIA labels and roles
- Keyboard navigation support
- Screen reader compatibility
- High contrast color schemes
- Focus management

## 🚀 Performance

- Lazy loading of images and components
- API response caching
- Optimized bundle size with tree shaking
- Progressive image loading
- Efficient re-rendering with proper memoization

## 🧪 Testing

```bash
# Run tests (when implemented)
npm test

# Run tests in watch mode
npm run test:watch

# Generate coverage report
npm run test:coverage
```

## 📦 Building for Production

```bash
npm run build
```

The build artifacts will be stored in the `dist/` directory.

## 🌐 Deployment

The application can be deployed to any static hosting service:

- **Vercel**: Connect your GitHub repository for automatic deployments
- **Netlify**: Drag and drop the `dist/` folder or connect via Git
- **GitHub Pages**: Use GitHub Actions for automated deployment

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b ft/amazing-feature`)
3. Commit your changes (`git commit -m 'feat: Add amazing feature'`)
4. Push to the branch (`git push origin ft/amazing-feature`)
5. Open a Pull Request

## 📋 Code Style

- ESLint for code linting
- Prettier for code formatting
- TypeScript strict mode enabled
- Conventional commit messages

## 🐛 Known Issues

- Some museum APIs may have rate limiting
- Image loading performance depends on external API response times

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Metropolitan Museum of Art for their open API
- Rijksmuseum for providing access to their collection
- Harvard Art Museums for their comprehensive API
- The open-source community for the amazing tools and libraries

## 📞 Support

If you encounter any issues or have questions:

1. Check the [Issues](https://github.com/yourusername/iwacu-gallery/issues) page
2. Create a new issue with detailed information
3. Contact the maintainers

---

**Made with ❤️ for art enthusiasts worldwide**