# Local Invoicing Application

A modern, local-first invoicing application built with React, Fireproof, and shadcn/ui.

## Features

- **Local-First Data Storage**: All your data stays on your device using Fireproof
- **Beautiful UI**: Modern interface built with shadcn/ui components and Tailwind CSS v4
- **Customer Management**: Easily add, edit, and organize customer information
- **Invoice Generation**: Create and manage professional invoices
- **Products Catalog**: Maintain a list of your products or services (optional)
- **No Backend Required**: Everything runs directly in your browser

## Technology Stack

- **Frontend Framework**: React with TypeScript
- **Build Tool**: Vite
- **Styling**: Tailwind CSS v4
- **UI Components**: shadcn/ui
- **Database**: Fireproof (local-first document database)
- **Routing**: React Router

## Getting Started

### Installation

```bash
# Clone the repository
git clone <repository-url>
cd invoice-app

# Install dependencies
npm install

# Start the development server
npm run dev
```

### Usage

1. Navigate to the application in your browser (typically at http://localhost:5173)
2. Add customers in the Customers section
3. Create invoices for your customers
4. View your dashboard for a quick overview of your business

## Project Structure

```
invoice-app/
├── src/
│   ├── components/         # UI components
│   │   ├── customers/      # Customer-related components
│   │   ├── invoices/       # Invoice-related components 
│   │   ├── layout/         # Layout components
│   │   ├── products/       # Product-related components
│   │   └── ui/             # shadcn/ui components
│   ├── lib/
│   │   └── db/             # Fireproof database setup and hooks
│   ├── pages/              # Page components
│   ├── App.tsx             # Main application component
│   └── main.tsx            # Application entry point
└── package.json            # Project dependencies
```

## Data Persistence

All data is stored locally in your browser using Fireproof, a local-first database. There's no need for a server or internet connection to use the application.

## License

MIT

---

This project was scaffolded with Vite and React.
