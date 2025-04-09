# My Hugo Site

This is a multi-language Hugo site that supports both English and German content.

## Project Structure

- **archetypes/**: Contains archetypes for creating new content.
  - **default.md**: The default archetype for new pages and posts.
  
- **content/**: Contains the content for the site.
  - **en/**: English content.
    - **_index.md**: The homepage or section content in English.
  - **de/**: German content.
    - **_index.md**: The homepage or section content in German.

- **layouts/**: Contains the layout templates for the site.
  - **_default/**: Default layouts.
    - **baseof.html**: Base template for all pages.
    - **list.html**: Layout for listing pages.
    - **single.html**: Layout for individual content pages.

- **static/**: Contains static files.
  - **images/**: Directory for static images used throughout the site.

- **config.toml**: Configuration file for the Hugo site, including settings for multi-language support.

## Setup Instructions

1. Install Hugo on your machine.
2. Clone this repository to your local machine.
3. Navigate to the project directory.
4. Run `hugo server` to start the local development server.
5. Open your browser and go to `http://localhost:1313` to view the site.

## Multi-Language Support

This site is configured to support both English and German languages. You can switch between languages using the appropriate links in the navigation. Make sure to add content in both languages to provide a complete experience for users.