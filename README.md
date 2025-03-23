# QQChat - Modern Chat Interface

A modern chat interface built with Nuxt.js and Tailwind CSS.

## Description

QQChat is a sophisticated chat application that demonstrates the power of Nuxt 3 and Tailwind CSS. It provides a clean, responsive interface with advanced features like code highlighting and AI integration.

## Features

- Modern Nuxt 3 framework
- Tailwind CSS for styling
- Monaco Editor integration for code display
- Responsive design
- Component-based architecture
- AI-powered chat capabilities

## Getting Started

### Prerequisites

- Node.js (v16 or later recommended)
- npm or another package manager

### Installation

1. Clone the repository:
```bash
git clone https://github.com/drinkredwine/qqchat-project.git
```

2. Navigate to the project directory:
```bash
cd qqchat-project
```

3. Install dependencies:
```bash
npm install
```

### Running the Application

To run the application in development mode:

```bash
npm run dev
```

The application will be available at http://localhost:3011.

### Building for Production

To build the application for production:

```bash
npm run build
```

To preview the production build:

```bash
npm run preview
```

## Project Structure

- `app.vue` - The main application component
- `nuxt.config.ts` - Nuxt configuration file
- `package.json` - Project dependencies and scripts
- `tailwind.config.js` - Tailwind CSS configuration
- `assets/css/tailwind.css` - Tailwind CSS imports and custom styles
- `components/` - Vue components using Tailwind CSS
- `composables/` - Reusable Vue composition functions

## Tailwind CSS

This project uses Tailwind CSS for styling. Tailwind is a utility-first CSS framework that allows for rapid UI development with pre-designed utility classes.

### Key Benefits

- Write less custom CSS
- Consistent design system
- Responsive design made easy
- Dark mode support
- Customizable theme

### Usage Example

```vue
<template>
  <div class="p-4 bg-blue-500 text-white rounded-md hover:bg-blue-600">
    This is styled with Tailwind CSS
  </div>
</template>
```

For more information, visit the [Tailwind CSS documentation](https://tailwindcss.com/docs).

## CI/CD

This project uses GitHub Actions for continuous integration and deployment:

- **Linting**: Automatically checks code quality on push and pull requests
- **Testing**: Runs automated tests to ensure functionality
- **Dependency Review**: Scans dependencies for security vulnerabilities
- **Deployment**: Automatically deploys to GitHub Pages when changes are pushed to main

## License

This project is licensed under the MIT License.
