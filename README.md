# Jekyll Project

This is a basic Jekyll project structure for creating a static website or blog. Below are the details of the project files and their purposes.

## Project Structure

```
jekyll-project
├── _config.yml          # Configuration settings for the Jekyll site
├── _data                # Directory for data files (YAML, JSON, CSV)
├── _includes            # Directory for reusable HTML snippets
│   └── header.html      # Header section of the site
├── _layouts             # Directory for layout templates
│   ├── default.html     # Default layout for pages and posts
│   └── post.html        # Layout for blog posts
├── _posts               # Directory for blog posts
│   └── 2023-10-01-welcome-to-jekyll.md  # Sample blog post
├── _sass                # Directory for Sass stylesheets
│   └── main.scss        # Main Sass stylesheet
├── assets               # Directory for assets
│   ├── css              # Directory for CSS files
│   │   └── styles.css   # Custom CSS styles
│   └── js               # Directory for JavaScript files
│       └── scripts.js    # Custom JavaScript
├── Gemfile              # Ruby gems required for the Jekyll project
├── Gemfile.lock         # Locked versions of the gems
└── README.md            # Documentation for the project
```

## Getting Started

1. **Install Prerequisites**: Ensure you have Ruby, RubyGems, and GCC installed on your system.

2. **Install Jekyll and Bundler**: Run the following command to install Jekyll and Bundler:
   ```
   gem install jekyll bundler
   ```

3. **Build the Site**: Navigate to the project directory and run:
   ```
   bundle exec jekyll build
   ```

4. **Serve the Site Locally**: To view your site locally, run:
   ```
   bundle exec jekyll serve
   ```
   Open your browser and go to `http://localhost:4000`.

## Customization

- Modify `_config.yml` to change site settings like title and description.
- Add new posts in the `_posts` directory using the naming convention `YYYY-MM-DD-title.md`.
- Customize styles in `_sass/main.scss` and `assets/css/styles.css`.
- Add interactivity with JavaScript in `assets/js/scripts.js`.

## Resources

- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [GitHub Pages Guide](https://docs.github.com/en/pages)

By following this guide, you can quickly set up and customize your Jekyll site. Happy blogging!