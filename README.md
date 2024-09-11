# wise.css

**wise.css** is a lightweight CSS framework designed for fast and simple web development. It provides a clean and easy-to-use structure similar to w3.css but with optimized, customizable components. With a focus on simplicity, **wise.css** allows you to quickly style your HTML elements with minimal effort.

## Features

- **Responsive Design**: Built to be responsive, ensuring that your website looks great on all devices.
- **Customizable Components**: Includes ready-to-use components such as buttons, navbars, forms, grids, and more.
- **Minimalistic and Lightweight**: The framework is easy to use and does not rely on JavaScript or external dependencies.
- **Cross-Browser Compatibility**: Compatible with all modern browsers.

## Installation

To use **wise.css**, you can either link to it directly from the [GitHub Pages](https://pgnetwork01.github.io/wise/wise.css) or download it and host it yourself.

### Option 1: Link to CDN

```html
<link rel="stylesheet" href="https://pgnetwork01.github.io/wise/wise.css">
```

### Option 2: Download and Host Locally

1. Download the `wise.css` file from the repository.
2. Add the `wise.css` file to your project.
3. Link it in your HTML:

```html
<link rel="stylesheet" href="path-to-your-project/wise.css">
```

## Usage

**wise.css** includes a variety of utility classes and pre-defined components. Below are some examples to get you started.

### 1. Body Reset

By default, **wise.css** resets the body margin to ensure consistent spacing across browsers.

```css
body {
  margin: 0;
  padding: 0;
  font-family: Arial, sans-serif;
}
```

### 2. Buttons

You can easily create stylish buttons using the `.btn` class.

```html
<button class="btn">Click Me</button>
```

Customizable styles for buttons are included for primary, secondary, and danger states.

```html
<button class="btn btn-primary">Primary Button</button>
<button class="btn btn-secondary">Secondary Button</button>
<button class="btn btn-danger">Danger Button</button>
```

### 3. Navbar

Create responsive, fixed, or dropdown navbars with minimal code. Use the `.navbar` class to create a horizontal navbar:

```html
<div class="navbar">
  <a href="#home">Home</a>
  <a href="#about">About</a>
  <a href="#contact">Contact</a>
</div>
```

For a fixed navbar, use the `.fixed-navbar` class:

```html
<div class="fixed-navbar">
  <a href="#home">Home</a>
  <a href="#about">About</a>
  <a href="#contact">Contact</a>
</div>
```

### 4. Grid Layout

Create responsive grids using the `.row` and `.col` classes.

```html
<div class="row">
  <div class="col-4">Column 1</div>
  <div class="col-4">Column 2</div>
  <div class="col-4">Column 3</div>
</div>
```

### 5. Forms

Style your forms easily using **wise.css** form classes.

```html
<form>
  <label for="name">Name:</label>
  <input type="text" id="name" class="input-text">
  
  <label for="email">Email:</label>
  <input type="email" id="email" class="input-text">

  <input type="submit" value="Submit" class="btn btn-primary">
</form>
```

### 6. Typography

**wise.css** provides simple styles for headings, paragraphs, and links:

```html
<h1>Main Heading</h1>
<p>This is a paragraph with default styling.</p>
<a href="#">This is a link</a>
```

## Example

Here’s a full example combining multiple components:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>wise.css Example</title>
  <link rel="stylesheet" href="https://pgnetwork01.github.io/wise/wise.css">
</head>
<body>

  <div class="navbar">
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </div>

  <div class="container">
    <h1>Welcome to wise.css</h1>
    <p>This is an example of using the wise.css framework. Below is a form and a grid layout.</p>

    <form>
      <label for="name">Name:</label>
      <input type="text" id="name" class="input-text">
      
      <label for="email">Email:</label>
      <input type="email" id="email" class="input-text">
      
      <input type="submit" value="Submit" class="btn btn-primary">
    </form>

    <div class="row">
      <div class="col-4">Column 1</div>
      <div class="col-4">Column 2</div>
      <div class="col-4">Column 3</div>
    </div>
  </div>

</body>
</html>
```

## Docs

- [Buttons](/btns.md)
- [Padding](/padding.md)
- [Margin](/margin.md)
- [Container](/container.md)
- [Additional Styles](#additional-styles)
- [HTML Example](#html-example)

## Contribution

If you would like to contribute to **wise.css**, feel free to submit pull requests or report issues in the repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

### How This Works:
- The `README.md` file provides **installation instructions**, **usage examples**, and **detailed explanations** of the key components available in **wise.css**.
- Developers can quickly get started by linking the framework via CDN or downloading the stylesheet.
- They can refer to the included code snippets for integrating buttons, navbars, forms, and grid layouts in their projects.

