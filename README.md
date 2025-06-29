# Frontend_prototype2

# 🚀 Document Q&A Frontend Prototype

A beautiful, modern React-based frontend for a document Q&A application with glass morphism UI effects. Upload PDF files and ask questions with AI-powered answers and source citations.

## 🌐 Live Demo

**[View Live Demo](https://fushionai.github.io/Frontend_prototype)**

## ✨ Features

- 📄 **Drag & Drop PDF Upload** with beautiful glass morphism effects
- 💬 **AI Chat Interface** with natural language Q&A
- 📚 **Source Citations** with page numbers and excerpts
- 🎨 **Modern Glass UI** with backdrop blur and gradients
- 📱 **Fully Responsive** design for all devices
- ⚡ **Instant Mock Responses** for testing
- 🔧 **TypeScript** for type safety and better development

## 🎨 UI Highlights

- **Glass Morphism Design** with backdrop blur effects
- **Gradient Backgrounds** and smooth animations
- **Modern Icons** and visual feedback
- **Loading Animations** and progress indicators
- **Professional Styling** ready for production

## 🛠️ Tech Stack

- **React 18** with TypeScript
- **TailwindCSS** for modern styling
- **shadcn/ui** for beautiful components
- **Lucide React** for crisp icons
- **Mock API** for standalone development

## 🚀 Quick Start

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/fushionai/Frontend_prototype.git
   cd Frontend_prototype
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start development server**:
   ```bash
   npm start
   ```

4. **Open your browser** and navigate to `http://localhost:3000`

## 📁 Project Structure

```
src/
├── components/
│   ├── ui/                 # shadcn/ui components
│   │   ├── button.tsx      # Reusable button component
│   │   ├── input.tsx       # Input field component
│   │   └── card.tsx        # Card container component
│   ├── FileUpload.tsx      # File upload with drag & drop
│   └── ChatInterface.tsx   # AI chat interface
├── hooks/
│   └── useMockApi.ts       # Mock API implementation
├── lib/
│   └── utils.ts           # Utility functions
├── App.tsx                # Main application component
├── index.tsx              # Application entry point
└── index.css              # Global styles with TailwindCSS
```

## 🎯 Usage

### 📄 Uploading Documents
1. **Drag and drop** PDF files onto the upload area
2. **Click "Choose Files"** for manual selection
3. **Watch progress** with beautiful progress indicators
4. **View metadata** including file size and upload date

### 💬 Asking Questions
1. **Type your question** in the chat input
2. **Press Enter** or click the Send button
3. **Get instant responses** with AI-powered answers
4. **View citations** with page numbers and excerpts

### 🎨 UI Features
- **Glass morphism effects** throughout the interface
- **Smooth animations** and hover effects
- **Responsive design** that works on all devices
- **Professional styling** with modern gradients

## ⚙️ Configuration

### Environment Variables

Copy `env.example` to `.env` and configure:

```bash
# API Configuration
REACT_APP_API_BASE_URL=http://localhost:8000
REACT_APP_USE_MOCK_API=true

# Feature Flags
REACT_APP_ENABLE_FILE_UPLOAD=true
REACT_APP_ENABLE_CHAT=true
REACT_APP_ENABLE_CITATIONS=true
```

## 🚀 Deployment

### GitHub Pages (Current)
This app is deployed on GitHub Pages at:
**https://fushionai.github.io/Frontend_prototype**

### Build for Production
```bash
npm run build
```

### Deploy to GitHub Pages
```bash
npm run deploy
```

## 🎭 Mock Data

The application includes realistic mock data for testing:
- **Sample Documents**: Pre-loaded example PDF files
- **Intelligent Responses**: Context-aware Q&A responses
- **Realistic Citations**: Page numbers and file references
- **Upload Simulation**: Progress bars and timing

## 🔗 Integration

### Backend Connection
When ready to connect to your FastAPI backend:
1. Set `REACT_APP_USE_MOCK_API=false`
2. Update API endpoints in `src/hooks/useMockApi.ts`
3. Configure CORS on your backend
4. Test the integration thoroughly

## 🛠️ Development

### Available Scripts
- `npm start` - Start development server
- `npm build` - Build for production
- `npm test` - Run tests
- `npm run deploy` - Deploy to GitHub Pages

### Adding Features
1. Create new components in `src/components/`
2. Use shadcn/ui components for consistency
3. Follow TypeScript patterns
4. Add proper styling with TailwindCSS

## 🎨 Design System

- **Glass Morphism**: Backdrop blur and transparency effects
- **Gradients**: Beautiful color transitions
- **Animations**: Smooth hover and loading effects
- **Typography**: Modern, readable fonts
- **Spacing**: Consistent padding and margins

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Follow the existing code style
4. Add TypeScript types for new features
5. Test your changes thoroughly
6. Submit a pull request

## 📄 License

This project is part of a larger RAG pipeline. The frontend is designed to work independently for development and testing purposes.

## 🌟 Support

- **Live Demo**: [https://fushionai.github.io/Frontend_prototype](https://fushionai.github.io/Frontend_prototype)
- **Issues**: Report bugs and feature requests on GitHub
- **Documentation**: Check the code comments for implementation details

---

**Built with ❤️ using React, TypeScript, and TailwindCSS** 
