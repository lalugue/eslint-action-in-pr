# ESLint workflow in a pull request

A sample GitHub Actions workflow file for executing an ESLint check in a pull request commit

- Runs only for commits in pull requests that target the `main` branch, this could be useful for codebases that are not fully "linted" beforehand
- Cancels workflow runs of previous commits if a new commit is pushed to the pull request's branch
- Could potentially be extended to execute other frontend tasks

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
