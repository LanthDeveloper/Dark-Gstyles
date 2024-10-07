# Dark-Gstyles

## Description

`dark-gstyles` is a comprehensive package of dark-themed CSS styles, designed for easy integration and reuse across various web projects. It provides a consistent and visually appealing dark mode experience.

## Features

- Pre-designed dark theme styles
- Easy to implement and customize
- Lightweight and performance-optimized
- Compatible with modern web frameworks

## Installation

You can install `dark-gstyles` using npm or yarn:

```bash
npm install dark-gstyles
```

or

```bash
yarn add dark-gstyles
```

## Usage

After installation, import the CSS file in your project:

- gs-dark: Indicates dark styles by default.
- gs-normal: Indicates styles without default colors.

```css
@import "dark-gstyles/gs-dark.css";
```

For JavaScript/TypeScript projects, you can import it in your entry file:

```javascript
import "dark-gstyles/gs-dark.css";
```

## Customization

You can override default styles by adding your custom CSS after importing `dark-gstyles`. For example:

```css
@import "dark-gstyles/gs-dark.css";

/* Your custom styles here */
body {
  --dark-background: #1a1a1a;
}
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
