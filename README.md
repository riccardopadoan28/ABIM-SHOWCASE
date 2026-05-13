# ABIM Showcase Site

This repository contains the source code for the ABIM Showcase website, built using GitHub Pages and Jekyll. The site serves as a platform to showcase the ABIM Showcase application, providing information and resources related to its features and usage.

## Project Structure

The project is organized as follows:

- **_config.yml**: Configuration settings for the GitHub Pages site, including theme settings and site-wide options.
- **Gemfile**: Specifies the Ruby gems required for the project, including Jekyll and other dependencies.
- **.gitignore**: Lists files and directories to be ignored by Git, such as temporary files and build artifacts.
- **index.md**: The main landing page of the website, containing introductory content and links to other sections.
- **_layouts/default.html**: Defines the default layout for the pages, including HTML structure and references to stylesheets and scripts.
- **_includes/head.html**: Contains the head section of the HTML, including meta tags and links to stylesheets.
- **assets/css/style.css**: Custom CSS styles for the website.
- **_posts/2026-01-01-welcome.md**: A sample blog post written in Markdown, including metadata and content.
- **README.md**: Documentation for the project, including setup and usage instructions.
- **.github/workflows/pages.yml**: Defines the GitHub Actions workflow for deploying the site to GitHub Pages.

## Setup Instructions

To set up the project locally, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Install the required gems by running `bundle install`.
4. Serve the site locally using `bundle exec jekyll serve`.
5. Open your web browser and go to `http://localhost:4000` to view the site.

## Usage

This site is intended to provide information about the ABIM Showcase application. You can add new content by creating new Markdown files in the `_posts` directory or by editing the `index.md` file.

## Contributing

Contributions are welcome! If you have suggestions or improvements, please submit a pull request.

## License

This project is licensed under the terms of the Demonstration-Only Proprietary License (DoPL). Please refer to the LICENSE file for more details.