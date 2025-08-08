# 3D ASCII Model Viewer

A React-based 3D ASCII art viewer that renders 3D models and text in ASCII characters using Three.js and React Three Fiber.

## Features

- Interactive 3D model viewing with ASCII rendering
- Real-time ASCII art generation
- Adjustable resolution and character sets
- Color customization
- Model scaling controls
- Auto-rotation and camera controls

## Local Development

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn

### Installation

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm run dev
```

3. Open your browser and navigate to `http://localhost:3000`

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## Deployment on Vercel

### Automatic Deployment

1. Push your code to a GitHub repository
2. Go to [Vercel](https://vercel.com) and sign in
3. Click "New Project"
4. Import your GitHub repository
5. Vercel will automatically detect it's a Vite project
6. Click "Deploy"

### Manual Deployment

1. Install Vercel CLI:
```bash
npm install -g vercel
```

2. Build the project:
```bash
npm run build
```

3. Deploy to Vercel:
```bash
vercel --prod
```

### Environment Variables

No environment variables are required for this project.

## Project Structure

```
├── App.tsx                 # Main application component
├── src/
│   └── main.tsx           # React entry point
├── components/
│   └── ui/                # UI components (shadcn/ui)
├── styles/
│   └── globals.css        # Global styles and Tailwind CSS
├── package.json           # Dependencies and scripts
├── vite.config.ts         # Vite configuration
├── tsconfig.json          # TypeScript configuration
└── tailwind.config.js     # Tailwind CSS configuration
```

## Technologies Used

- React 18
- TypeScript
- Vite
- Three.js
- React Three Fiber
- React Three Drei
- Tailwind CSS
- shadcn/ui components
- Radix UI primitives

## License

This project is open source and available under the [MIT License](LICENSE). 