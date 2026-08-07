# Khurram Shehzad's Portfolio

This is the personal portfolio and resume website of **Khurram Shehzad**, hosted on GitHub Pages at [khurram18.github.io](https://khurram18.github.io). 

It is a responsive, single-page web app built on top of the Devfolio template using Bulma, Sass, Font Awesome, and Flickity.

## Project Structure

The project has the following directory structure:
* **`/css`** and **`/js`**: Contains the compiled and bundled production assets (`main.bundle.css` and `bundle.js`) served by GitHub Pages.
* **`/img`**: Image assets used across the portfolio, including project carousels and logos.
* **`/docs`**: Document templates (e.g., resume files).
* **`/src`**: The build environment containing source Sass files, entry scripts, Webpack config, and dependencies.

---

## Setup & Development

To make updates to the styles or scripts, follow these steps:

### 1. Install Dependencies
Navigate to the `/src` directory and install the packages:
```bash
cd src
npm install
```

### 2. Build Assets
Run the build script to compile and bundle Sass/JS files. Webpack is configured to output build assets to `src/dist`:
```bash
npm run build
```

### 3. Deploy Updates
After compilation, copy the updated assets from `src/dist` to the root folders:
* Copy `src/dist/css/main.bundle.css` to `css/main.bundle.css`
* Copy `src/dist/js/bundle.js` to `js/bundle.js`

Once copied and committed to the `master` branch, GitHub Pages will automatically deploy the updates.

---

## Technologies Used
* **Framework**: [Bulma CSS](https://bulma.io/) (via Sass)
* **Bundler**: Webpack 5
* **Components**: Flickity (Carousels) & Font Awesome (Icons)
