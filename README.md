# ALX Listing App

This project is a foundational setup for an Airbnb clone called the ALX Listing App. It sets up a clean and scalable codebase using modern web technologies including Next.js, TypeScript, TailwindCSS, and ESLint.

## Project Structure

- **components/**: Contains reusable React components.
  - **common/Card.tsx**: A reusable card component to display property listings.
  - **common/Button.tsx**: A reusable button component for UI actions.
- **interfaces/**: Contains TypeScript interfaces for type safety.
  - **index.ts**: Central location for shared component props.
- **constants/**: Stores reusable static data such as config values and API endpoints.
- **public/assets/**: Stores images, icons, and other assets.
- **styles/globals.css**: Tailwind CSS styles imported here.
- **pages/index.tsx**: Homepage using the reusable components.

## Getting Started

1. Install dependencies:

```bash
npm install
```

2. Run the development server:

```bash
npm run dev
```

3. Open [http://localhost:3000](http://localhost:3000) to view the app.

## Technologies

- Next.js 13+
- TypeScript
- TailwindCSS
- ESLint
