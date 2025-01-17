# ExpoWebMobileNxMonorepo

This is an NX monorepo intented to be used as a template or example for starting a cross platform web and mobile application.

# Tool Stack:
* TypeScript
* Expo for web and mobile
* Redux toolkit with thunks for state management.
* Expo router.
* React hook form.
* Jest and react-testing-library.
* ESLint and Prettier.
* Paper for a a UI lib for web and mobile.
* AWS Amplify for hosting, database, and deployment

# Getting started

1. Install Node. I recommend using [nvm](https://github.com/nvm-sh/nvm) or a similar tool to track versions
1. Install NX cli tools `npm i nx -g`
1. Clone this repo and open a terminal in it
1. Install dependencies `npm i`
1. You're done! You can start the application for web

## Mobile

Mobile dev requires installing Android Studio and Java for Android and Xcode for IOS (MacOS only)

# Start the application

Run `npx nx serve expo` to start the development server. Happy coding!

# Build for production

Run `npx nx build expo` to build the application. The build artifacts are stored in the output directory (e.g. `dist/` or `build/`), ready to be deployed.

# <a alt="Nx logo" href="https://nx.dev" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/nrwl/nx/master/images/nx-logo.png" width="45"></a>

✨ **This workspace has been generated by [Nx, Smart Monorepos · Fast CI.](https://nx.dev)** ✨

## Integrate NX with editors

Enhance your Nx experience by installing [Nx Console](https://nx.dev/nx-console) for your favorite editor. Nx Console
provides an interactive UI to view your projects, run tasks, generate code, and more! Available for VSCode, IntelliJ and
comes with a LSP for Vim users.

## Explore the project graph

Run `npx nx graph` to show the graph of the workspace.
It will show tasks that you can run with Nx.

- [Learn more about Exploring the Project Graph](https://nx.dev/core-features/explore-graph)
