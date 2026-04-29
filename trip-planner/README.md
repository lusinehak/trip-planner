# Trip Planner Project

## Overview
The Trip Planner project is a monorepo that contains both backend and frontend applications. The backend is built using NestJS, while the frontend is developed with React. This structure allows for efficient development and sharing of code between the two applications.

## Project Structure
```
trip-planner
├── apps
│   ├── backend        # Backend application (NestJS)
│   ├── frontend       # Frontend application (React)
├── libs
│   ├── shared         # Shared library for common utilities and components
├── nx.json            # Nx workspace configuration
├── package.json       # NPM dependencies and scripts
├── tsconfig.base.json # Base TypeScript configuration
└── README.md          # Project documentation
```

## Getting Started

### Prerequisites
- Node.js (version 14 or higher)
- npm or yarn

### Installation
1. Clone the repository:
   ```
   git clone <repository-url>
   cd trip-planner
   ```

2. Install dependencies:
   ```
   npm install
   ```

### Running the Applications

#### Backend
To start the backend application, navigate to the backend directory and run:
```
cd apps/backend
npm run start
```

#### Frontend
To start the frontend application, navigate to the frontend directory and run:
```
cd apps/frontend
npm start
```

### Building the Applications
To build the applications for production, run the following commands:

#### Backend
```
cd apps/backend
npm run build
```

#### Frontend
```
cd apps/frontend
npm run build
```

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.