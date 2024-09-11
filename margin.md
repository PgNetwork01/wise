# wise.css - Margin Styles

**wise.css** is a lightweight CSS framework that provides a variety of margin and padding classes, among other styles. This section focuses on the margin styles available in **wise.css** to help you control spacing between elements.

## Table of Contents

- [Getting Started](#getting-started)
- [Margin Styles](#margin-styles)
  - [Margin for All Sides](#margin-for-all-sides)
  - [Margin for Specific Sides](#margin-for-specific-sides)
  - [Horizontal and Vertical Margin](#horizontal-and-vertical-margin)
  - [Shorthand Margin Classes](#shorthand-margin-classes)
- [HTML Example](#html-example)

## Getting Started

To start using **wise.css** for margins, include the following link in the `<head>` of your HTML file:

```html
<link rel="stylesheet" href="https://pgnetwork01.github.io/wise/wise.css">
```

Now, you can start using the margin classes provided by **wise.css**.

## Margin Styles

### Margin for All Sides

You can apply margin to all sides of an element with these classes:

- **Extra Small Margin**: `.margin-xs` (4px)
- **Small Margin**: `.margin-sm` (8px)
- **Medium Margin**: `.margin-md` (16px)
- **Large Margin**: `.margin-lg` (24px)
- **Extra Large Margin**: `.margin-xl` (32px)
- **Double Extra Large Margin**: `.margin-xxl` (48px)

#### Example:

```html
<div class="margin-lg">This div has large margin on all sides.</div>
```

### Margin for Specific Sides

Apply margin to a specific side of an element using the following classes:

- **Top Margin**: `.margin-top-[size]`
- **Right Margin**: `.margin-right-[size]`
- **Bottom Margin**: `.margin-bottom-[size]`
- **Left Margin**: `.margin-left-[size]`

Where `[size]` can be `xs`, `sm`, `md`, `lg`, `xl`, or `xxl`.

#### Example:

```html
<div class="margin-top-md">This div has medium top margin.</div>
```

### Horizontal and Vertical Margin

To apply margin only to the horizontal (left and right) or vertical (top and bottom) sides, use:

- **Horizontal Margin**: `.margin-h-[size]`
- **Vertical Margin**: `.margin-v-[size]`

#### Example:

```html
<div class="margin-h-lg">This div has large horizontal margin (left and right).</div>
```

### Shorthand Margin Classes

You can also apply margin to all sides with shorthand classes like:

- **Extra Small Margin**: `.margin-all-xs`
- **Small Margin**: `.margin-all-sm`
- **Medium Margin**: `.margin-all-md`
- **Large Margin**: `.margin-all-lg`
- **Extra Large Margin**: `.margin-all-xl`
- **Double Extra Large Margin**: `.margin-all-xxl`

#### Example:

```html
<div class="margin-all-md">This div has medium margin on all sides.</div>
```

## HTML Example

Here is a complete HTML example to test different margin classes:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Margin Examples - wise.css</title>
  <link rel="stylesheet" href="https://pgnetwork01.github.io/wise/wise.css">
  <style>
    .box {
      border: 1px solid #ddd;
      margin-bottom: 10px;
    }
  </style>
</head>
<body>

  <h1>Margin Examples</h1>

  <!-- Margin for All Sides -->
  <div class="box margin-xs">Margin XS</div>
  <div class="box margin-sm">Margin SM</div>
  <div class="box margin-md">Margin MD</div>
  <div class="box margin-lg">Margin LG</div>
  <div class="box margin-xl">Margin XL</div>
  <div class="box margin-xxl">Margin XXL</div>

  <!-- Margin for Specific Sides -->
  <div class="box margin-top-md">Margin Top MD</div>
  <div class="box margin-right-md">Margin Right MD</div>
  <div class="box margin-bottom-md">Margin Bottom MD</div>
  <div class="box margin-left-md">Margin Left MD</div>

  <!-- Horizontal and Vertical Margin -->
  <div class="box margin-h-md">Margin Horizontal MD</div>
  <div class="box margin-v-md">Margin Vertical MD</div>

  <!-- Margin with Shorthand -->
  <div class="box margin-all-md">Margin All MD</div>

</body>
</html>
```

## Contribution

Feel free to contribute by submitting issues or pull requests on the [GitHub repository](https://github.com/your-repo/wise.css).

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
```

### Key Features:
- **Margin for all sides**: Classes like `.margin-md` for controlling margin on all sides of an element.
- **Specific side margins**: Allows setting margins on specific sides like `.margin-top-md`.
- **Horizontal and vertical margins**: Separate classes for controlling horizontal and vertical margins like `.margin-h-md` and `.margin-v-md`.
- **Shorthand classes**: Easy-to-use shorthand margin classes like `.margin-all-md`.
