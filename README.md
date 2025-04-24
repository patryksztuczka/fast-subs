# Fast Subs

> A powerful desktop application for efficient video subtitle processing, built with Tauri 2.0

## Table of Contents
- [Overview](#overview)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Project Scope](#project-scope)
- [Project Status](#project-status)
- [License](#license)

## Overview

Fast Subs is a modern desktop application designed for efficient video subtitle processing. Built with Tauri 2.0, it combines the performance of native applications with the flexibility of web technologies. The application provides secure access to operating system APIs, enabling robust video file operations while maintaining low resource usage and small application size.

## Tech Stack

### Frontend
- **TypeScript 5** - Static typing and enhanced IDE support
- **React 19** - UI library for building interactive interfaces
- **Tailwind CSS** - Utility-first CSS framework
- **Shadcn/ui** - Accessible React component library

### Backend
- **Rust** - Powers the core functionality:
  - Video file processing
  - Logging system (INFO, WARN, ERROR, DEBUG)
  - Video and subtitle format handling
  - Transcription engine integration

### Development Tools
- **ESLint** - Static code analysis and coding standards enforcement
- **Prettier** - Automated code formatting
- **PostHog** - Application usage analytics

### CI/CD & Version Control
- **GitHub Actions** - Automated CI/CD processes
- **Automated Testing** - Code validation
- **Automated Builds** - Application building
- **Version Management** - Release management

## Getting Started

### Prerequisites

- Node.js (Latest LTS version recommended)
- Rust (Latest stable version)
- Git

### Installation

1. Clone the repository
```bash
git clone https://github.com/your-username/fast-subs.git
cd fast-subs
```

2. Install dependencies
```bash
pnpm install
```

3. Start the development environment
```bash
pnpm run tauri dev
```

## Available Scripts

- `pnpm run dev` - Start the Vite development server
- `pnpm run build` - Build the TypeScript code and create production bundle
- `pnpm run preview` - Preview the production build locally
- `pnpm run tauri` - Run Tauri-specific commands

## Project Scope

Fast Subs focuses on providing:

- Efficient desktop application with web interface
- Secure access to OS-level APIs
- Video file operations and processing
- File system integration
- Low resource consumption
- Small application footprint

### Quality Standards

- Strict TypeScript configuration
- Automated code formatting
- Conventional Commits for standardized commit messages
- Comprehensive testing and validation

## Project Status

- Current Version: 0.1.0
- Stage: Early Development
- Type: Private Package

## License

TBD - License information will be added in future updates.

---

For more information about the project, please contact the project maintainers.
