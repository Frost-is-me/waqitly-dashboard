# 🚀 Waqitly Dashboard

A high-performance, modern, and feature-rich admin dashboard built with **React 19**, **TypeScript**, and **Vite**. Designed for seamless service management, reservations tracking, and team coordination.

![Dashboard Preview](docs/preview.png)

## ✨ Key Features

- 🌓 **Dark & Light Mode**: Built-in theme switching using `next-themes`.
- 🌍 **Multi-language & RTL Support**: Seamless switching between English and Arabic (RTL) using `i18next`.
- 📊 **Dynamic Analytics**: Interactive data visualization powered by `Recharts`.
- 📅 **Reservation Management**: Comprehensive system to track and manage bookings.
- 👥 **Team Management**: Interface for managing staff roles and permissions.
- 🏗️ **Service Creation**: Intuitive workflow for adding and configuring new services.
- 🖱️ **Drag & Drop UI**: Enhanced user experience with `@dnd-kit`.
- ⚡ **Optimized Performance**: Built on Vite for lightning-fast HMR and build times.
- 📱 **Fully Responsive**: Mobile-first design using Tailwind CSS v4.

## 🛠️ Tech Stack

- **Frontend Framework**: [React 19](https://react.dev/)
- **Build Tool**: [Vite](https://vitejs.dev/)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com/)
- **State Management**: [Zustand](https://github.com/pmndrs/zustand)
- **Data Fetching**: [TanStack Query (React Query)](https://tanstack.com/query/latest)
- **UI Components**: [Radix UI](https://www.radix-ui.com/), [Lucide React](https://lucide.dev/), [Tabler Icons](https://tabler.io/icons)
- **Routing**: [React Router v7](https://reactrouter.com/)
- **Charts**: [Recharts](https://recharts.org/)
- **Tables**: [TanStack Table](https://tanstack.com/table/latest)
- **Forms & Validation**: [Zod](https://zod.dev/)
- **Internationalization**: [i18next](https://www.i18next.com/)

## 📂 Project Structure

```bash
src/
├── app/            # App-level configurations
├── components/     # Reusable UI components (Shared, Pages, UI)
├── hooks/          # Custom React hooks
├── lib/            # External library configurations (Axios, etc.)
├── locales/        # Translation files (EN, AR)
├── pages/          # Individual dashboard pages
├── services/       # API service layers
├── stores/         # Zustand state stores
├── styles/         # Global styles and Tailwind configs
├── types/          # TypeScript interfaces and types
└── utils/          # Helper functions
```

## 🚀 Getting Started

### Prerequisites

- **Node.js**: v18.x or higher
- **Package Manager**: `pnpm` (recommended) or `npm`

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Frost-is-me/waqitly-frontend-dashboard-my-local-version.git
   ```

2. Navigate to the project directory:
   ```bash
   cd waqitly-frontend-dashboard-my-local-version
   ```

3. Install dependencies:
   ```bash
   pnpm install
   ```

### Running Locally

To start the development server:
```bash
pnpm run dev
```
The application will be available at `http://localhost:5173`.

### Building for Production

To create an optimized production build:
```bash
pnpm run build
```

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

---
Developed with ❤️ by [Frost-is-me](https://github.com/Frost-is-me)
