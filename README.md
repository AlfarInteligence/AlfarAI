# AlfarAI - 3D Image Generation Platform

![AlfarAI Banner](https://images.unsplash.com/photo-1633356122544-f134324a6cee?auto=format&fit=crop&w=1200&q=80)

AlfarAI is a modern web application that transforms text descriptions into stunning 3D images using artificial intelligence. Built with React, TypeScript, and the Stability AI API, it offers an intuitive interface for creating high-quality 3D renders.

## 🚀 Features

- **AI-Powered Image Generation**: Transform text descriptions into detailed 3D images
- **Multiple Style Options**: Choose from various rendering styles including 3D render, realistic, stylized, and abstract
- **Quality Control**: Select different quality levels to balance between generation speed and image detail
- **Batch Generation**: Create multiple variations of your concept in a single generation
- **Modern UI**: Beautiful, responsive interface with dark mode and glass morphism design
- **Real-time Preview**: See your generated images instantly in the preview panel
- **Download Options**: Easily download and save your generated images

## 🛠️ Technology Stack

- **Frontend**: React + TypeScript
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Routing**: React Router
- **AI Integration**: Stability AI API
- **Build Tool**: Vite

## 📋 Prerequisites

Before you begin, ensure you have:

- Node.js (v18 or higher)
- A Stability AI API key (get one at [platform.stability.ai](https://platform.stability.ai))

## 🚀 Getting Started

1. Clone the repository:
   \`\`\`bash
   git clone https://github.com/yourusername/alfarai.git
   cd alfarai
   \`\`\`

2. Install dependencies:
   \`\`\`bash
   npm install
   \`\`\`

3. Create a \`.env\` file in the root directory:
   \`\`\`env
   VITE_STABILITY_API_KEY=your-stability-ai-api-key
   \`\`\`

4. Start the development server:
   \`\`\`bash
   npm run dev
   \`\`\`

## 🔧 Configuration

The application can be configured through the following environment variables:

- \`VITE_STABILITY_API_KEY\`: Your Stability AI API key

## 📦 Building for Production

To create a production build:

\`\`\`bash
npm run build
\`\`\`

The built files will be in the \`dist\` directory.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (\`git checkout -b feature/AmazingFeature\`)
3. Commit your changes (\`git commit -m 'Add some AmazingFeature'\`)
4. Push to the branch (\`git push origin feature/AmazingFeature\`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Stability AI](https://stability.ai) for their powerful image generation API
- [Lucide](https://lucide.dev) for the beautiful icons
- [Tailwind CSS](https://tailwindcss.com) for the utility-first CSS framework
