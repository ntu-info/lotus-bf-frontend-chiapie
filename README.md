# LoTUS-BF Frontend

A modern React-based frontend application for the LoTUS-BF (Longitudinal Tracking Using Serial Brain imaging Framework) project.

## Features

- 🧠 **Brain Imaging Visualization**: Interactive NIfTI viewer for brain imaging data
- 📊 **Studies Table**: Sortable and searchable studies database with Year, Journal, Title, and Authors
- 🎨 **Modern UI**: Beautiful pink & green gradient theme with smooth animations
- 🐸 **Delightful Animations**: Lotus flowers and jumping frog animations
- 📱 **Responsive Design**: Works seamlessly on desktop and mobile devices

## Tech Stack

- **Framework**: React 19.2
- **Build Tool**: Vite 7.1
- **Imaging**: NiiVue for NIfTI visualization
- **Styling**: Custom CSS with pink & green theme

## Getting Started

### Prerequisites

- Node.js (LTS version recommended)

### Installation

1. **Install dependencies**:
   ```bash
   npm install
   ```

2. **Run development server**:
   ```bash
   npm run dev
   ```
   The application will be available at `http://localhost:5173`

3. **Build for production**:
   ```bash
   npm run build
   ```
   The built files will be in the `./dist` folder

### Troubleshooting

If you encounter issues with incompatible packages:

```bash
# Install latest LTS version of Node.js
nvm install --lts

# Remove existing packages
rm -rf node_modules package-lock.json

# Reinstall packages
npm install
```

## Project Structure

```
├── src/
│   ├── components/      # React components
│   ├── hooks/           # Custom React hooks
│   ├── App.jsx          # Main application component
│   ├── App.css          # Application styles
│   └── main.jsx         # Entry point
├── assets/
│   └── custom-styles.css # Custom styling overrides
├── public/              # Static assets
├── dist/                # Production build (generated)
└── index.html           # HTML template
```

## Design Features

### Color Theme
- **Primary Pink**: `#F5BABB` - Used for headers and primary UI elements
- **Accent Green**: `#59AC77` - Used for interactive elements
- **Gradient**: Pink to Green gradients throughout the interface

### Custom Styling
The application uses a custom styles overlay (`assets/custom-styles.css`) that provides:
- Solid pink table headers for better readability
- Digital lotus logo with spinning animation
- Single jumping frog animation
- 4 floating lotus flowers at the bottom

## Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run lint` - Run ESLint
- `npm run preview` - Preview production build

## Deployment

The application is configured with a base path for deployment:
- Base path: `/lotus-bf-frontend-chiapie/`

To deploy:
1. Build the project: `npm run build`
2. Upload the contents of the `dist/` folder to your web server

## License

This project is part of an academic assignment.

## Contributing

This is an assignment repository. Please follow your institution's academic integrity guidelines.
