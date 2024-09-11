
# Button Styles in wise.css

**wise.css** provides a variety of button styles that are easy to use and customize. This document covers the different types of buttons available, including color variations, sizes, and additional styles.

## Table of Contents

- [Basic Buttons](#basic-buttons)
- [Button Colors](#button-colors)
- [Button Sizes](#button-sizes)
- [Outline Buttons](#outline-buttons)
- [Additional Styles](#additional-styles)
- [HTML Example](#html-example)

## Basic Buttons

The base class `.btn` provides the foundation for all button styles. By adding specific modifier classes, you can customize the button's appearance.

### Default Button

**Class**: `.btn`

```html
<button class="btn">Default Button</button>
```

### Example

<button class="btn">Default Button</button>

## Button Colors

**wise.css** includes several predefined button color classes. Each class applies a specific background color and text color.

- **Primary Button**
  - **Class**: `.btn-primary`
  - **Example**:
  ```html
  <button class="btn btn-primary">Primary</button>
  ```

  <button class="btn btn-primary">Primary</button>

- **Secondary Button**
  - **Class**: `.btn-secondary`
  - **Example**:
  ```html
  <button class="btn btn-secondary">Secondary</button>
  ```

  <button class="btn btn-secondary">Secondary</button>

- **Danger Button**
  - **Class**: `.btn-danger`
  - **Example**:
  ```html
  <button class="btn btn-danger">Danger</button>
  ```

  <button class="btn btn-danger">Danger</button>

- **Success Button**
  - **Class**: `.btn-success`
  - **Example**:
  ```html
  <button class="btn btn-success">Success</button>
  ```

  <button class="btn btn-success">Success</button>

- **Warning Button**
  - **Class**: `.btn-warning`
  - **Example**:
  ```html
  <button class="btn btn-warning">Warning</button>
  ```

  <button class="btn btn-warning">Warning</button>

- **Info Button**
  - **Class**: `.btn-info`
  - **Example**:
  ```html
  <button class="btn btn-info">Info</button>
  ```

  <button class="btn btn-info">Info</button>

## Button Sizes

Buttons can be resized using size modifier classes:

- **Small Button**
  - **Class**: `.btn-small`
  - **Example**:
  ```html
  <button class="btn btn-primary btn-small">Small Button</button>
  ```

  <button class="btn btn-primary btn-small">Small Button</button>

- **Large Button**
  - **Class**: `.btn-large`
  - **Example**:
  ```html
  <button class="btn btn-primary btn-large">Large Button</button>
  ```

  <button class="btn btn-primary btn-large">Large Button</button>

## Outline Buttons

Outline buttons have a transparent background with a colored border. They can be used with the following classes:

- **Primary Outline Button**
  - **Class**: `.btn-outline-primary`
  - **Example**:
  ```html
  <button class="btn btn-outline-primary">Primary Outline</button>
  ```

  <button class="btn btn-outline-primary">Primary Outline</button>

- **Secondary Outline Button**
  - **Class**: `.btn-outline-secondary`
  - **Example**:
  ```html
  <button class="btn btn-outline-secondary">Secondary Outline</button>
  ```

  <button class="btn btn-outline-secondary">Secondary Outline</button>

- **Danger Outline Button**
  - **Class**: `.btn-outline-danger`
  - **Example**:
  ```html
  <button class="btn btn-outline-danger">Danger Outline</button>
  ```

  <button class="btn btn-outline-danger">Danger Outline</button>

## Additional Styles

**wise.css** offers additional styles for buttons to enhance their appearance:

- **Rounded Button**
  - **Class**: `.btn-rounded`
  - **Example**:
  ```html
  <button class="btn btn-primary btn-rounded">Rounded Button</button>
  ```

  <button class="btn btn-primary btn-rounded">Rounded Button</button>

- **Shadow Button**
  - **Class**: `.btn-shadow`
  - **Example**:
  ```html
  <button class="btn btn-primary btn-shadow">Shadow Button</button>
  ```

  <button class="btn btn-primary btn-shadow">Shadow Button</button>

- **Block Button**
  - **Class**: `.btn-block`
  - **Example**:
  ```html
  <button class="btn btn-primary btn-block">Block Button</button>
  ```

  <button class="btn btn-primary btn-block">Block Button</button>

## Disabled State

The disabled state of a button is styled to indicate that it is not interactive. Use the `disabled` attribute to apply this style.

### Example

**Class**: `.btn:disabled`

```html
<button class="btn btn-primary" disabled>Disabled Button</button>
```

<button class="btn btn-primary" disabled>Disabled Button</button>

## HTML Example

Here is a full HTML example demonstrating various button styles:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Button Examples - wise.css</title>
  <link rel="stylesheet" href="https://pgnetwork01.github.io/wise/wise.css">
</head>
<body>

  <h1>Button Examples</h1>

  <!-- Basic Buttons -->
  <button class="btn btn-primary">Primary</button>
  <button class="btn btn-secondary">Secondary</button>
  <button class="btn btn-danger">Danger</button>
  <button class="btn btn-success">Success</button>
  <button class="btn btn-warning">Warning</button>
  <button class="btn btn-info">Info</button>

  <!-- Outline Buttons -->
  <button class="btn btn-outline-primary">Primary Outline</button>
  <button class="btn btn-outline-secondary">Secondary Outline</button>
  <button class="btn btn-outline-danger">Danger Outline</button>

  <!-- Button Sizes -->
  <button class="btn btn-primary btn-small">Small Button</button>
  <button class="btn btn-primary">Normal Button</button>
  <button class="btn btn-primary btn-large">Large Button</button>

  <!-- Rounded Button -->
  <button class="btn btn-primary btn-rounded">Rounded Button</button>

  <!-- Block Button -->
  <button class="btn btn-primary btn-block">Block Button</button>

  <!-- Shadow Button -->
  <button class="btn btn-primary btn-shadow">Shadow Button</button>

  <!-- Disabled Button -->
  <button class="btn btn-primary" disabled>Disabled Button</button>

</body>
</html>
```

## Contribution

Feel free to contribute to **wise.css** by submitting issues or pull requests on the [GitHub repository](https://github.com/your-repo/wise.css).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

### How to Use This Documentation:
- This `README.md` file visually shows each button type alongside its class name and example HTML code.
- It helps users quickly understand how each button style looks and how to use the appropriate classes.

Feel free to further customize this documentation based on your specific needs or updates to **wise.css**.
