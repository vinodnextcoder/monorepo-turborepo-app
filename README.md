# TurboRepo Monorepo: Backend and Frontend Example



This is a simple monorepo project using **TurboRepo** to manage both a **backend (Express.js)** and a **frontend (React)** app. TurboRepo helps us run and build these apps efficiently while sharing dependencies and configurations.



- **`apps/backend/`**: The backend app built with Express.js.
- **`apps/web/`**: The frontend app built with React.
- **`packages/`**: Shared code or packages that can be used across apps.
- **`turbo.json`**: TurboRepo configuration to manage tasks and caching.

## Setup

Follow these steps to get started with this project.

### 1. Clone the Repository

```bash
git clone <repository-url>
cd my-turbo-repo
```

 ### 2. Install Dependencies

To install all dependencies for both backend and frontend apps, run:

```bash
npm install
```
This will install the necessary dependencies for both apps and set up the workspaces.

### 3. Run the Project

To start both the frontend and backend apps, use the following command:
```bash
npm run dev
```

The backend will run on http://localhost:3001.
The frontend (React app) will be available on the default React port (http://localhost:3000 or similar).


License

This project is licensed under the MIT License.
