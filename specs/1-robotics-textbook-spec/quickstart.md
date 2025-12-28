# Quickstart: Setting up the Docusaurus Project

This guide provides the steps to set up the Docusaurus project for the "Physical AI & Humanoid Robotics" textbook.

## Prerequisites

-   [Node.js](https://nodejs.org/en/) version 16.14 or above.
-   [Yarn](https://yarnpkg.com/) or [npm](https://www.npmjs.com/).

## Installation

1.  **Initialize the Docusaurus project:**

    ```bash
    npx create-docusaurus@latest my-website classic
    ```

2.  **Navigate to the project directory:**

    ```bash
    cd my-website
    ```

3.  **Start the development server:**

    ```bash
    yarn start
    ```

    The site will be available at `http://localhost:3000`.

## Configuration

1.  **`docusaurus.config.js`:** This file contains the main configuration for the site. Update the `title`, `tagline`, `url`, and `baseUrl` fields.

2.  **`sidebars.js`:** This file defines the structure of the sidebar. You will need to manually add each chapter and lesson to this file.

## Content Development

-   All textbook content is located in the `docs` directory.
-   Create a new directory for each chapter.
-   Create a new Markdown file for each lesson.
-   Follow the file naming convention defined in the plan.
-   Add the new chapter and lessons to `sidebars.js`.
