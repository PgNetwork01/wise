# wise.css

**wise.css** is a lightweight, utility-first CSS framework that provides a wide variety of customizable styles, including buttons, padding, and other UI components.

## Table of Contents

- [Getting Started](#getting-started)
- [Padding Styles](#padding-styles)
  - [Padding for All Sides](#padding-for-all-sides)
  - [Padding for Specific Sides](#padding-for-specific-sides)
  - [Horizontal and Vertical Padding](#horizontal-and-vertical-padding)
  - [Padding with Shorthand](#padding-with-shorthand)
- [HTML Example](#html-example)

## Getting Started

To start using **wise.css**, simply include the following link in the `<head>` section of your HTML file:

```html
<link rel="stylesheet" href="https://pgnetwork01.github.io/wise/wise.css">
```

This will give you access to all the styles defined in **wise.css**, including the newly added padding classes.

## Padding Styles

**wise.css** provides a variety of padding options that can be applied to elements. These classes make it easy to control the spacing inside your elements.

### Padding for All Sides

You can apply padding to all sides of an element using the `.padding-[size]` class. Available sizes include:

- **Extra Small Padding**: `.padding-xs` (4px)
- **Small Padding**: `.padding-sm` (8px)
- **Medium Padding**: `.padding-md` (16px)
- **Large Padding**: `.padding-lg` (24px)
- **Extra Large Padding**: `.padding-xl` (32px)
- **Double Extra Large Padding**: `.padding-xxl` (48px)

#### Example:

```html
<div class="padding-lg">This div has large padding on all sides.</div>
```

### Padding for Specific Sides

If you want to apply padding only to a specific side of an element (top, right, bottom, or left), you can use the following classes:

- **Top Padding**: `.padding-top-[size]`
- **Right Padding**: `.padding-right-[size]`
- **Bottom Padding**: `.padding-bottom-[size]`
- **Left Padding**: `.padding-left-[size]`

#### Example:

```html
<div class="padding-top-md">This div has medium padding on the top side.</div>
```

### Horizontal and Vertical Padding

To apply padding only on the horizontal (left and right) or vertical (top and bottom) sides, use these classes:

- **Horizontal Padding**: `.padding-h-[size]`
- **Vertical Padding**: `.padding-v-[size]`

#### Example:

```html
<div class="padding-h-lg">This div has large horizontal padding (left and right).</div>
```

### Padding with Shorthand

You can also apply padding uniformly on all sides using shorthand classes:

- **Extra Small Padding**: `.padding-all-xs`
- **Small Padding**: `.padding-all-sm`
- **Medium Padding**: `.padding-all-md`
- **Large Padding**: `.padding-all-lg`
- **Extra Large Padding**: `.padding-all-xl`
- **Double Extra Large Padding**: `.padding-all-xxl`

#### Example:

```html
<div class="padding-all-md">This div has medium padding on all sides.</div>
```

## HTML Example

Here is a full HTML example demonstrating the padding styles in **wise.css**:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Padding Examples - wise.css</title>
  <link rel="stylesheet" href="https://pgnetwork01.github.io/wise/wise.css">
  <style>
    .box {
      border: 1px solid #ddd;
      margin: 10px 0;
    }
  </style>
</head>
<body>

  <h1>Padding Examples</h1>

  <!-- Padding for All Sides -->
  <div class="box padding-xs">Padding XS</div>
  <div class="box padding-sm">Padding SM</div>
  <div class="box padding-md">Padding MD</div>
  <div class="box padding-lg">Padding LG</div>
  <div class="box padding-xl">Padding XL</div>
  <div class="box padding-xxl">Padding XXL</div>

  <!-- Padding for Specific Sides -->
  <div class="box padding-top-md">Padding Top MD</div>
  <div class="box padding-right-md">Padding Right MD</div>
  <div class="box padding-bottom-md">Padding Bottom MD</div>
  <div class="box padding-left-md">Padding Left MD</div>

  <!-- Horizontal and Vertical Padding -->
  <div class="box padding-h-md">Padding Horizontal MD</div>
  <div class="box padding-v-md">Padding Vertical MD</div>

  <!-- Padding with Shorthand -->
  <div class="box padding-all-md">Padding All MD</div>

</body>
</html>
```

## Contribution

Feel free to contribute to **wise.css** by submitting issues or pull requests on the [GitHub repository](https://github.com/your-repo/wise.css).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

### How to Use This Documentation:
- This `README.md` file provides a clear structure for understanding the padding classes.
- It includes examples for using padding on all sides, specific sides, and shorthand padding classes.
- The full HTML example helps users see the padding styles in action.

Feel free to further customize this file to fit your project's specific requirements.
