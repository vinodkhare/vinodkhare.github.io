# My Jekyll Site

This is a basic Jekyll site that includes an About page and a blog section.

## Project Structure

```
my-jekyll-site
├── _includes
├── _layouts
│   └── default.html
├── _posts
│   └── 2023-01-01-welcome-to-jekyll.md
├── _site
├── about.md
├── blog.md
├── _config.yml
└── README.md
```

## Getting Started

To set up and run this Jekyll site, follow these steps:

1. **Install Jekyll**: Make sure you have Ruby and Bundler installed. Then, install Jekyll by running:
   ```
   gem install jekyll bundler
   ```

2. **Clone the Repository**: Clone this repository to your local machine:
   ```
   git clone <repository-url>
   cd my-jekyll-site
   ```

3. **Install Dependencies**: Run the following command to install the necessary gems:
   ```
   bundle install
   ```

4. **Run the Jekyll Server**: Start the Jekyll server with:
   ```
   bundle exec jekyll serve
   ```

5. **Access the Site**: Open your web browser and go to `http://localhost:4000` to view your site.

## About Page

The About page can be found at `/about`. It contains information about the site or the author.

## Blog

The blog section can be accessed at `/blog`. It includes links to individual blog posts and an overview of recent posts.

## License

This project is licensed under the MIT License.