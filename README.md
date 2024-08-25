# Hono With Auth

hono-with-auth is a modern web application built with Next.js that integrates Hono and Drizzle for handling authentication and database operations. This project leverages a robust tech stack, including TypeScript, Tailwind CSS for styling, and Zod for schema validation. The application is designed with scalability and security in mind, featuring authentication through the @auth/core package and database interactions powered by drizzle-orm. The project is equipped with a variety of UI components from the Radix UI library, enhancing both user experience and accessibility. The integration of react-query ensures efficient data fetching and state management, making this project a comprehensive solution for building secure and responsive web applications.

## Demo

[[hono with auth demo]](demo.gif)

## Table of Contents

- [Hono With Auth](#hono-with-auth)
  - [Demo](#demo)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
  - [Technologies Used](#technologies-used)
  - [Installation](#installation)

## Features

- User Authentication: Secure user authentication using @auth/core and @hono/auth-js, including support for session management and token-based authentication.

- Database Integration: Seamless integration with PostgreSQL via drizzle-orm, providing a powerful and type-safe ORM for managing database queries and migrations.

- Schema Validation: Strong input validation using Zod, ensuring data integrity and providing clear error messages for invalid inputs.

- UI Components: A set of responsive and accessible UI components built with Radix UI and styled using Tailwind CSS, including avatars, dropdown menus, and more.

- State Management: Efficient state management and data fetching using react-query, allowing for optimized data handling and caching.

- Tailwind CSS Utilities: Enhanced styling capabilities with utilities like tailwind-merge and tailwindcss-animate, enabling quick and consistent design implementation.

- Developer Tools: Integrated developer tools such as ESLint for linting, TypeScript for static typing, and Drizzle Kit for database schema generation and management.

- Component Customization: Easy-to-use component customization with class-variance-authority and clsx, allowing for dynamic styling based on component state and props.

## Technologies Used

- **Next.js**: A React framework for building fast, server-rendered web applications.
- **React**: A JavaScript library for building user interfaces.
- **Hono**: A small, simple, and performant web framework for building APIs and web applications.
- **Drizzle ORM**: A lightweight and type-safe ORM for handling database interactions with PostgreSQL.
- **Tailwind CSS**: A utility-first CSS framework for rapidly building custom designs.
- **Zod**: A TypeScript-first schema declaration and validation library.
- **Radix UI**: A library of accessible and customizable UI components for React.
- **React Query**: A data-fetching library for managing server-state in React applications.
- **TypeScript**: A superset of JavaScript that adds static typing to the language.
- **ESLint**: A tool for identifying and fixing linting issues in your code.
- **PostgreSQL**: A powerful, open-source relational database management system.
- **Neon Database**: A serverless PostgreSQL solution for modern web applications.
- **Dotenv**: A module for loading environment variables from a `.env` file.
- **CUID2**: A collision-resistant unique identifier generator for creating stable, human-readable IDs.
- **Lucide React**: A library of beautiful and customizable icons for React applications.

## Installation

To get started with this project, clone the repository and install the dependencies:

```bash
git clone https://github.com/realvishalrana/hono-with-auth.git
npm install
npm run dev
