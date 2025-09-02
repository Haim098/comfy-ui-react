# ComfyUI React Frontend

A modern React frontend application for ComfyUI with TypeScript and Vite.

## Features

- React 18 with TypeScript
- Vite for fast development and building
- ESLint for code quality
- Modern development tooling

## Getting Started

### Prerequisites

- Node.js (version 18 or higher)
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/Haim098/comfy-ui-react.git

# Navigate to the project directory
cd comfy-ui-react

# Install dependencies
npm install
```

### Development

```bash
# Start the development server
npm run dev
```

The application will be available at `http://localhost:5173`

### Building

```bash
# Build for production
npm run build
```

### Linting

```bash
# Run ESLint
npm run lint
```

## Project Structure

```
comfy-ui-react/
├── public/           # Static assets
├── src/             # Source code
│   ├── assets/      # Images, icons, etc.
│   ├── App.tsx      # Main App component
│   ├── App.css      # App styles
│   ├── main.tsx     # Application entry point
│   └── index.css    # Global styles
├── package.json     # Dependencies and scripts
├── tsconfig.json    # TypeScript configuration
├── vite.config.ts   # Vite configuration
└── eslint.config.js # ESLint configuration
```

## Technologies Used

- **React** - UI library
- **TypeScript** - Type safety
- **Vite** - Build tool and dev server
- **ESLint** - Code linting

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the MIT License.