```
src/
├── assets/                # Static assets (images, fonts, etc.)
│   ├── fonts/
│   ├── images/
│
├── components/            # Re-usable UI Components
│   ├── basic/             # Simple, atomic components (Button, Input, Label) - no state, pure UI
│   ├── composites/        # Composed components, combining basic components (Card, Modal, FormField)
│   ├── containers/        # Stateful or complex UI components (UserList, DashboardPanel)
│   ├── layouts/           # High-level structural components (AuthLayout, DashboardLayout)
│   ├── boundaries/        # Error boundaries, fallback components (ErrorBoundary, 404Page)
│
├── lib/                   # Business logic and utilities
│   ├── constants/         # Global constants
│   ├── utils/             # Utility functions and helpers
│   ├── hooks/             # Custom reusable hooks
│   ├── store/             # State management (Redux/Zustand)
│   ├── types/             # Shared TypeScript types and interfaces
│
├── pages/                 # Page components by domain (Projects, Analytics, Dashboard, etc.)
│   ├── Projects/          # Contains domain-specific components, hooks, styles, unit tests, etc.
│   ├── App.tsx            # Main app entry point
│
├── routes/                # Centralized app routing
│   ├── routes.tsx
│
├── services/              # API services (data layer, CRUD operations, transport-specific logic)
│   ├── base/              # Base service definitions and common service logic
│   │   ├── BaseService.ts # Base service class with interface for consistency
│   │   ├── pagination.ts  # Pagination utility functions and types
│   │   ├── filters.ts     # Filter utility functions and types
│   │   ├── sort.ts        # Sorting utility functions and types
│   ├── users/             # User-related API services
│   │   ├── UsersService.ts # Service for user management
│   ├── filestorage/       # File storage API services
│   │   ├── FileStorageService.ts # Service for file management
│
├── styles/                # Global styles (CSS Modules, Tailwind, etc.)
│   ├── globals.css
│
├── index.tsx              # Root app entry file (React, Vue, etc.)
├── .env.local             # Environment variables
├── .gitignore
├── package.json
```
