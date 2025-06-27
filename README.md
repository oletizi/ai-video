# AI Video

A project for AI-powered video processing and generation.

## Description

This repository contains tools and utilities for working with AI-generated video content, including processing, generation, and manipulation capabilities. The project consists of:

- **Backend**: TypeScript/Node.js API for video processing
- **Frontend**: Astro.js web interface for video management and visualization

## Getting Started

### Prerequisites

- Node.js 18+
- npm or yarn

### Installation

```bash
# Clone the repository
git clone git@github.com:oletizi/ai-video.git
cd ai-video

# Install dependencies
npm install
```

### Development

#### Backend (TypeScript/Node.js)
```bash
# Build TypeScript
npm run build

# Watch for changes
npm run dev

# Run the application
npm start
```

#### Frontend (Astro.js)
```bash
# Start development server
npm run astro:dev

# Build for production
npm run astro:build

# Preview production build
npm run astro:preview
```

### Usage

1. Start the Astro development server: `npm run astro:dev`
2. Open your browser to `http://localhost:4321`
3. Use the web interface to manage and process videos

## Features

- **Video Processing**: Intelligent video enhancement and optimization
- **AI Generation**: Create stunning videos with AI assistance
- **Real-time Analysis**: Advanced video analytics and insights
- **Modern Web Interface**: Built with Astro.js for optimal performance
- **TypeScript Backend**: Robust API with full type safety

## Project Structure

```
ai-video/
├── src/                    # TypeScript backend source
│   └── index.ts           # Main backend entry point
├── pages/                 # Astro frontend pages
│   └── index.astro        # Main web page
├── public/                # Static assets
├── dist/                  # Compiled backend (after build)
├── package.json
├── tsconfig.json
├── astro.config.mjs
└── README.md
```

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

- GitHub: [@oletizi](https://github.com/oletizi) 