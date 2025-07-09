# Tom Barbereau's Personal Website

This is the source code for Tom Barbereau's personal academic website, built with [Hugo](https://gohugo.io/) and using the [Typo](https://github.com/tomfran/typo) theme.

## Features

- Academic portfolio and blog
- Posts and pages written in Markdown
- Responsive, minimal design
- SEO-friendly configuration
- Social links (LinkedIn, GitHub, Google Scholar, Bluesky)

## Getting Started

1. **Clone the repository:**
   ```sh
   git clone https://github.com/tom-barbereau/tom-barbereau.github.io-main.git
   cd tom-barbereau.github.io-main
   ```

2. **Install Hugo:**  
   [Install Hugo](https://gohugo.io/getting-started/installing/) if you haven't already.

3. **Initialize submodules (for the Typo theme):**
   ```sh
   git submodule update --init --recursive
   ```

4. **Run the development server:**
   ```sh
   hugo server
   ```
   Visit [http://localhost:1313](http://localhost:1313) in your browser.

## Creating a New Post

```sh
hugo new posts/my-new-post/index.md
```
Edit the new file in `content/posts/my-new-post/index.md`.

## Deployment

The site can be deployed to GitHub Pages or any static hosting provider.  
Build the site with:

```sh
hugo
```
The generated files will be in the `public/` directory.

## License

This project is for personal and academic use.  
Theme: [Typo](https://github.com/tomfran/typo) (see its repository for license).