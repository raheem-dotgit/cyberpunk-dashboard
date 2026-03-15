# Cyberpunk Dashboard

A futuristic, cyberpunk-themed tactical operations dashboard with neon aesthetics and immersive UI. Perfect for gaming interfaces, control panels, or data visualization projects.

![Next.js](https://img.shields.io/badge/Next.js-16.1.6-black?style=flat-square&logo=next.js)
![React](https://img.shields.io/badge/React-19.2.4-61DAFB?style=flat-square&logo=react)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4.x-38B2AC?style=flat-square&logo=tailwind-css)

## Live Demo

[View Live Demo on Vercel](https://cyberpunk-dashboard.vercel.app)

## Features

- Cyberpunk-inspired dark theme with neon accents
- Tactical operations command center UI
- Collapsible sidebar navigation
- Multiple dashboard views:
  - Command Center Overview
  - Agent Network
  - Operations Tracking
  - Intelligence Reports
  - Systems Monitoring
- Interactive charts and data visualization
- Responsive design
- Smooth animations and transitions

## Tech Stack

- **Framework:** Next.js 16 (App Router)
- **UI:** React 19, Tailwind CSS 4
- **Charts:** Recharts
- **Icons:** Lucide React
- **UI Components:** Radix UI, shadcn/ui
- **Language:** TypeScript

## Getting Started

### Prerequisites

- Node.js 18+
- pnpm (recommended)

### Installation

```bash
# Clone the repository
git clone https://github.com/raheem-dotgit/cyberpunk-dashboard.git

# Navigate to the project directory
cd cyberpunk-dashboard

# Install dependencies
pnpm install

# Start the development server
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) to view the dashboard.

## Project Structure

```
├── app/
│   ├── layout.tsx
│   ├── page.tsx
│   ├── command-center/
│   ├── agent-network/
│   ├── operations/
│   ├── intelligence/
│   └── systems/
├── components/
│   └── ui/
└── public/
```

## Customization

1. Modify the color scheme in `globals.css` (neon orange, cyan, etc.)
2. Update dashboard sections with your own data
3. Add new views by creating pages in the `app` directory
4. Customize charts in each section component

## Author

**Raheem**

- GitHub: [@raheem-dotgit](https://github.com/raheem-dotgit)
- LinkedIn: [ab-raheem](https://www.linkedin.com/in/ab-raheem)
- Email: raheem.dev7@gmail.com

## License

MIT License - feel free to use this project for your own purposes.
