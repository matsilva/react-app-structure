src/
├── assets/                # Static assets (images, fonts)
│   ├── fonts/
│   ├── images/
│
├── components/            # UI Components (Atomic Design)
│   ├── atoms/             # Smallest reusable components (Button, Input, Label)
│   ├── molecules/         # Grouped atoms forming functional components
│   ├── organisms/         # Complex UI structures combining molecules
│   ├── templates/         # Page layouts (AuthLayout, DashboardLayout)
│
├── lib/                   # Business logic and utilities
│   ├── constants/         # Global constants
│   ├── helpers/           # Utility functions
│   ├── hooks/             # Custom reusable hooks
│   ├── store/             # State management (Redux/Zustand)
│   ├── queryClient.ts     # React Query client
│
├── pages/                 # Page components (LoginPage, DashboardPage)
│
├── routes/                # Centralized app routing
│   ├── routes.tsx
│
├── services/              # API services (fetching data)
│   ├── apiClient.ts       # Axios client for API calls
│   ├── products/          # Product API services
│   │   ├── queries/queries.ts # React Query fetching
|   |     ├──keys/keys.ts # Query keys
│   │   ├── mutations.ts   # React Query mutations
│   │   ├── api.ts         # API functions
│
├── styles/                # Global styles (CSS Modules, Tailwind, etc.)
│   ├── globals.css
│
├── App.tsx                # Main app entry point
├── index.tsx              # React root file
├── .env.local             # Environment variables
├── .gitignore
├── package.json
