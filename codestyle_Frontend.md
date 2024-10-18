# Frontend Codestyle for Contact Management System

This document outlines the coding standards and best practices for frontend development using Vue.js and related technologies.

## Basic Rules

- **Indentation**: Use 2 spaces for indentation.
- **Line Length**: No more than 100 characters per line.

## Naming Conventions

- **Components**: Use PascalCase: `MyComponent.vue`
- **Variables and Functions**: Use camelCase: `myFunction`
- **Constants**: Use ALL_CAPS with underscores: `MY_CONSTANT`

## Comments

- Use Vue-style comments: `<!-- This is a comment -->`

## File and Directory Structure

- Maintain a clear directory structure with components organized together.
- Use `.vue` files for single-file components.
- Separate components, services, utilities, etc., into different directories.

## Vue Components

- Organize Vue components into three sections: `<template>`, `<script>`, and `<style>`.
- Keep the HTML structure in `<template>` clear and logic simple.
- Define component logic and data in `<script>`.
- Define component styles in `<style>`, using Scoped styles to avoid conflicts.

## JavaScript

- Utilize ES6+ features such as arrow functions, template literals, and destructuring.
- Avoid global variables; declare variables with `let` and `const`.
- Name functions and variables using `camelCase`.
- Name classes using `PascalCase`.
- Name private variables and functions using `snake_case`.

## HTML

- Use lowercase letters and double dashes for HTML attribute names (e.g., `data-*`).
- Maintain clear nesting and indentation in HTML structure.

## CSS

- Follow BEM naming conventions for CSS classes.
- Keep CSS selectors concise and avoid excessive nesting.
- Use SCSS variables, mixins, and functions for maintainability.

## Code Formatting

- Use tools like Prettier or ESLint to automatically format code.
- Configure EditorConfig to standardize file formatting, such as line endings and indentation size.

## Code Comments

- Add clear comments to explain the purpose and implementation of complex logic or non-obvious code.
- Use JSDoc comments to describe function parameters, return values, and thrown errors.

Adhere to these guidelines to maintain consistency and quality in your frontend codebase. Adjust and extend this guide as needed based on project-specific requirements.