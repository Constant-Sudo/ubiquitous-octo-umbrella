# Tailwind Website

This project is a simple website built using Tailwind CSS for styling and custom JavaScript for interactivity.

## Project Structure

```
tailwind-website
├── index.html               # Main HTML file (in root for GitHub Pages)
├── src
│   ├── css
│   │   └── input.css        # Main CSS file with Tailwind directives
│   └── js
│       └── main.js          # Custom JavaScript functionality
├── public
│   └── assets               # Directory for static assets
│       └── styles.css       # Built CSS file
├── package.json             # npm configuration file
├── tailwind.config.js       # Tailwind CSS configuration file
├── postcss.config.js        # PostCSS configuration file
└── README.md                # Project documentation
```

## Getting Started

To get started with this project, follow these steps:

1. **Clone the repository:**
   ```
   git clone <repository-url>
   cd tailwind-website
   ```

2. **Install dependencies:**
   ```
   npm install
   ```

3. **Build the CSS:**
   ```
   npx postcss src/css/input.css -o public/assets/styles.css
   ```

4. **Open the HTML file:**
   Open `index.html` in your browser to view the website.

## Usage

You can customize the Tailwind CSS configuration in `tailwind.config.js` to change the default styles. Add your custom JavaScript functionality in `src/js/main.js`.

## Contributing

Feel free to submit issues or pull requests if you have suggestions or improvements for the project.

## License

This project is open source and available under the [MIT License](LICENSE).