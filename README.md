# Resume Screener Application

A modern web application built with React, TypeScript, and Tailwind CSS for screening and managing candidate resumes. The application provides an intuitive interface for recruiters to parse, view, and evaluate candidate information efficiently.

## Features

- **Dashboard**: Overview of candidate statistics and metrics
- **Candidate Management**: View and manage candidate profiles
- **Resume Parser**: Upload and parse resumes to extract relevant information
- **Responsive Design**: Works on desktop and tablet devices
- **Modern UI**: Clean and intuitive interface built with Tailwind CSS

## Tech Stack

- **Frontend**: React 18 with TypeScript
- **Styling**: Tailwind CSS
- **Build Tool**: Vite
- **Icons**: Lucide Icons
- **Linting**: ESLint
- **Code Formatting**: Prettier (via ESLint)

## Getting Started

### Prerequisites

- Node.js (v16 or later)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd Resume-Screener
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn
   ```

3. Start the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. Open [http://localhost:5173](http://localhost:5173) to view it in your browser.

## Project Structure

```
project/
├── src/
│   ├── components/     # Reusable UI components
│   │   └── layout/     # Layout components (Header, Sidebar, etc.)
│   ├── pages/         # Page components
│   ├── App.tsx        # Main application component
│   └── main.tsx       # Application entry point
├── public/            # Static assets
├── index.html         # HTML template
└── ...                # Configuration files
```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
