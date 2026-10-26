# Mobile App Notes — Dwija Chaudhari

## What Is React Native?

React Native is a framework for building mobile applications using JavaScript and React.

It supports developing applications for iOS and Android using a shared codebase.

It uses native interface components for mobile applications.

## What Is Expo?

Expo provides tools for developing and testing React Native applications.

The command `npm install` installs the required project dependencies.

The command `npx expo start` launches the Expo development server.

Pressing `w` opens the application in a web browser.

## What I Observed

I opened the mobile project in a separate Visual Studio Code window.

I installed the dependencies using `npm install`.

I started the application using `npx expo start`.

I pressed `w` to launch the application in Chrome.

I encountered a missing navigation import error in `App.js`.

I added the required imports and successfully opened the mobile application.

The application includes Home, Login, and Register screens.

The backend was running on port 4000 with a successful MongoDB connection.

## Git Workflow

### 1. Git Status

```bash
git status
```

This command checks the current branch and identifies modified and untracked files.

### 2. Git Add

```bash
git add -A
```

This command stages relevant documentation and screenshot changes.

### 3. Git Commit

```bash
git commit -m "Update Dwija backend and mobile documentation"
```

This command commits the staged changes.

### 4. Git Push

```bash
git push origin main
```

This command pushes committed changes to the GitHub repository.

## Git Terminal Output Evidence

The terminal showed the repository status and identified changes that needed to be staged.

The `git add -A` command staged the relevant changes. A successful staging command normally produces no output.

The terminal confirmed that the documentation and screenshot changes were committed. The commit output included the number of files changed and the commit message.

The terminal subsequently confirmed that the push to `origin/main` succeeded.

## GitHub Repository

https://github.com/Dwija1212/IFT458-Middleware-2026-Dwija
