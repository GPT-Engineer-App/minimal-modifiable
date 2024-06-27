# Bare-Bones Web Application

This is a minimal web application setup using React, Tailwind CSS, and shadcn-ui components. You can use this as a starting point to build your application.

## Project Structure

- `src/`: Contains the source code of the application.
  - `pages/`: Contains the page components.
  - `components/`: Contains reusable UI components.
  - `App.jsx`: The main application component.
  - `index.css`: The main CSS file.
  - `main.jsx`: The entry point of the application.
- `public/`: Contains public assets like images and icons.
- `README.md`: This file.

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. Install the dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

### Running the Application

To start the development server, run:
```bash
npm run dev
# or
yarn dev
```

The application will be available at `http://localhost:3000`.

### Building the Application

To build the application for production, run:
```bash
npm run build
# or
yarn build
```

The built files will be in the `dist/` directory.

### Modifying the Application

- To add new pages, create a new file in the `src/pages/` directory and add a new route in `src/App.jsx`.
- To add new components, create a new file in the `src/components/` directory and import it where needed.
- To modify styles, edit the `src/index.css` file or add new CSS files as needed.

### Learn More

- [React Documentation](https://reactjs.org/docs/getting-started.html)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [shadcn-ui Documentation](https://shadcn.dev/docs)

Happy coding!