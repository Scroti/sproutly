# Sproutly - Environmental Impact Tracker

Sproutly is a Progressive Web Application (PWA) built with React and Vite that helps households track their carbon footprint based on daily activities such as travel, energy use, and diet. It enables multiple users per household to collaboratively monitor and improve their environmental impact.

## Features

- User authentication and household management with roles (admin/member)
- Daily activity logging for travel, energy usage, and diet by household members
- Aggregated carbon footprint calculation at individual and household level
- Interactive dashboards with data visualization of footprint trends
- Personalized eco-friendly suggestions and goals for footprint reduction
- Offline support as a PWA with service worker caching
- Responsive design for web and mobile usage

## Technologies Used

- React 18 with Vite bundler
- React Router for navigation
- Context API / Redux for state management
- Node.js + Express backend (API and authentication management)
- MongoDB or PostgreSQL for data persistence
- vite-plugin-pwa for PWA support
- Chart.js / D3.js for visualization
- JWT for secure authentication

## Getting Started

### Prerequisites

- Node.js v18 or higher
- npm or yarn
- MongoDB/PostgreSQL instance or any other preferred database

### Installation

1. Clone the repository  
\`\`\`
git clone https://github.com/yourusername/sproutly.git
cd sproutly
\`\`\`

2. Install frontend dependencies and run dev server  
\`\`\`
cd frontend
npm install
npm run dev
\`\`\`

3. Set up and run backend  
\`\`\`
cd ../backend
npm install
npm run start
\`\`\`

4. Configure environment variables for API endpoints, database, and JWT secrets as needed.

### Build for Production

\`\`\`
cd frontend
npm run build
\`\`\`

Deploy the backend and serve the frontend's \`dist\` folder with any static file server.

## PWA Features

- Add to Home Screen prompt support
- Offline caching with service worker (via vite-plugin-pwa)
- Fast load times and smooth user experience

## Contributing

Contributions are welcome! Please open issues or pull requests for features, bug fixes, or enhancements.

## License

[MIT License](LICENSE)

---

Sproutly empowers households to grow greener habits and reduce carbon footprint together.
