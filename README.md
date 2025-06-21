# The Rise of Agentic AI

This project is a single-page interactive guide exploring the evolution of AI agents. It covers the core components of AI agents, the timeline of Large Language Model (LLM) releases that have fueled their development, and an overview of the toolkits available for agentic AI development.

## Features

- **Interactive Theme Toggle**: Users can switch between light and dark modes. The theme preference is also detected from the user's system settings.
- **Responsive Design**: The page is designed to be accessible and visually appealing across various devices and screen sizes, built with Tailwind CSS.
- **Timeline of LLM Releases**: A chronological list of significant LLM releases, highlighting their impact on AI agent capabilities.
- **Core Components of AI Agents**: Detailed explanations of Perception, Planning, Action, and Memory in the context of AI agents.
- **Agentic Developer's Toolkit**: A curated list of AI-native IDEs, agents, and platforms that are shaping the future of software development.
- **Hover Effects**: Interactive hover effects on cards for better user experience.
- **Custom Styling**: Utilizes Google Fonts and custom CSS variables for a consistent and modern look and feel.

## Page Structure

The HTML page (`index.html`) is structured as follows:

1.  **Header**:
    *   Displays the title "Agentic AI".
    *   Includes a theme toggle button (Light/Dark mode).

2.  **Main Content**:
    *   **Introduction Section**:
        *   Headline: "The Rise of Agentic AI".
        *   A brief overview of the page's content.
    *   **What is an AI Agent? Section**:
        *   Explains the concept of an AI Agent.
        *   Details the core components: Perception, Planning, Action, and Memory, presented in card-style layouts.
    *   **LLM Release Timeline Section**:
        *   Presents a table view of key LLM releases from March 2023 to Q2 2025 (projected).
        *   Each entry includes the date, company, model/family, and its key innovation/impact.
        *   Uses a visual timeline indicator for each entry.
    *   **The Agentic Developer's Toolkit Section**:
        *   Surveys tools for building with AI models.
        *   Categorized into:
            *   **Editors**: (e.g., Cursor, Windsurf)
            *   **Agents**: (e.g., Claude Code, Jules, Cline, Roo)
            *   **Platforms**: (e.g., GitHub Copilot, Augment)
        *   Each tool is presented in a card with a brief description.

3.  **Footer**:
    *   Contains a copyright notice.

4.  **Styling and Interactivity**:
    *   **Tailwind CSS**: Used for rapid UI development and responsive design.
    *   **Custom CSS**:
        *   Defines light and dark theme variables (`:root` and `.dark`).
        *   Styles for the main body, timeline items, cards, and theme toggle.
        *   Imports the 'Inter' font from Google Fonts.
    *   **JavaScript**:
        *   Handles theme toggling functionality.
        *   Initializes the theme based on system preference (`prefers-color-scheme`).
        *   Adds hover effects to cards (changes border color).
        *   Includes a small animation effect when toggling themes.

## How to View

Simply open the `index.html` file in a web browser.

## Technologies Used

*   HTML5
*   Tailwind CSS
*   JavaScript (vanilla)
*   Google Fonts ('Inter')
