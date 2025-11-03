# AI-Powered Todo List Application

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Overview

This application is an intelligent Todo list manager that integrates an AI assistant using **CopilotKit**. It allows users to manage their tasks through a clean user interface and interact with an AI-powered sidebar to perform actions using natural language.

### Key Features

- **Todo Management**: Create, edit, delete, and mark todos as complete.
- **AI Assistant**: Use the CopilotKit sidebar to add, remove, and modify todos by giving conversational instructions.
- **Local Storage Persistence**: Your todos are automatically saved to the browser's local storage, so you don't lose your data on refresh.
- **Modern Tech Stack**: Built with Next.js, React, TypeScript, and styled with Tailwind CSS.
- **Optimized Setup**: Configured to use `pnpm` for efficient package management.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- Node.js (version 20.9.0 or later recommended)
- pnpm

If you don't have `pnpm` installed, you can install it globally using npm:

```bash
npm install -g pnpm
```

### Installation

1.  **Clone the repository**

    ```bash
    git clone https://github.com/wila-dev/demo-wila.github.io.git
    cd demo-wila.github.io
    ```

2.  **Install dependencies**
    Use `pnpm` to install the project's dependencies as defined in `pnpm-lock.yaml`.
    ```bash
    pnpm install
    ```

### Running the Development Server

To start the development server, run:

```bash
pnpm run dev
```

Open http://localhost:3000 with your browser to see the result.

## Available Scripts

In the project directory, you can run the following commands:

- `pnpm dev`: Runs the app in development mode.
- `pnpm build`: Builds the app for production.
- `pnpm start`: Starts the production server.
- `pnpm lint`: Runs ESLint to analyze the code for potential errors.
