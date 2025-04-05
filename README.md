```
src/
├── assets/                # Static assets (images, fonts)
│   ├── fonts/
│   ├── images/
│
├── components/            # Re-usable UI Components
│   ├── dumb/              # Small(ish), stateless dumb components (Button, Input, Label)
│   ├── average/           # Slightly more complex, composes dumb components... probably not mature enough to manage state yet
│   ├── smart/             # Larger more complex UI structures, may manage state, composes avg and dumb components
│   ├── templates/         # Page layouts (AuthLayout, DashboardLayout, ErrorBoundary, 404)
│
├── lib/                   # Business logic and utilities
│   ├── constants/         # Global constants
│   ├── helpers/           # Utility functions
│   ├── hooks/             # Custom reusable hooks
│   ├── store/             # State management (Redux/Zustand)
│   ├── types/types.ts     # Shared TypeScript types and interfaces
│
├── pages/                 # Page components by domain(Projects, Analytics, Dashboard, etc...)
│   ├── Projects/          # Contains domain specific components, hooks, styles, unit tests, etc
│   ├── App.tsx       # Main app entry point
├── routes/                # Centralized app routing
│   ├── routes.tsx
│
├── services/              # API services (data layer, crud operations, etc based on transport needs)
│   ├── base/              # base service definitions
|   |   ├── BaseService.ts # Base service class, provides a base interface each service should implement(or inherit)
|   |   ├── pagination.ts  # Api Pagination schema/types & utility fns
|   |   ├── filters.ts     # Api filter schema/types & utility fns
|   |   ├── sort.ts        # Api sort schema/types & utility fns
│   ├── users/             # Example users service
│   │   ├── UsersService.ts  # API service for users resource
│   ├── filestorage/       # Example file storage service
│   │   ├── FileStoreageService.ts  # API service for managing user/tenant files
│
├── styles/                # Global styles (CSS Modules, Tailwind, etc.)
│   ├── globals.css
│
├── index.tsx              # Root app entry file (React, Vue, etc)
├── .env.local             # Environment variables
├── .gitignore
├── package.json

```
