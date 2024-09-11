# wise.css - Container System

The **wise.css** container system provides a flexible and responsive layout framework. It includes a variety of container types that can be used to create responsive, fluid, and fixed-width designs. Containers come with options for padding, border-radius, and content alignment to suit different design needs.

## Features

- **Responsive Design**: Containers automatically adjust based on screen size.
- **Fluid Containers**: Full-width containers that span the entire viewport.
- **Custom Padding**: Various options for padding inside containers.
- **Rounded Containers**: Containers with customizable border-radius options.
- **Center Alignment**: Easily center content both horizontally and vertically using Flexbox.

## Table of Contents

- [Installation](#installation)
- [Basic Usage](#basic-usage)
- [Responsive Containers](#responsive-containers)
- [Fluid Containers](#fluid-containers)
- [Padding](#padding)
- [Rounded Containers](#rounded-containers)
- [Centering Content](#centering-content)
- [Browser Support](#browser-support)

## Installation

To use the **wise.css** container system, include the CSS file in your project:

```html
<link rel="stylesheet" href="https://pgnetwork01.github.io/wise/wise.css">
```

## Basic Usage

The `.container` class is the base class for creating a responsive container. By default, it adjusts its width based on the screen size.

```html
<div class="container">
  This is a container.
</div>
```

## Responsive Containers

Responsive containers automatically adjust their width depending on the viewport size. Use the following classes to create containers that adapt to different screen sizes.

- `.container-sm` (max-width: 540px)
- `.container-md` (max-width: 720px)
- `.container-lg` (max-width: 960px)
- `.container-xl` (max-width: 1140px)
- `.container-xxl` (max-width: 1320px)

```html
<div class="container container-sm">Small Container (max-width: 540px)</div>
<div class="container container-md">Medium Container (max-width: 720px)</div>
<div class="container container-lg">Large Container (max-width: 960px)</div>
```

## Fluid Containers

Use `.container-fluid` for containers that should span the entire width of the viewport.

```html
<div class="container-fluid">
  This container is full-width.
</div>
```

## Padding

Add custom padding to containers using the following classes:

- `.container-padding-sm` (Small padding)
- `.container-padding-md` (Medium padding)
- `.container-padding-lg` (Large padding)

```html
<div class="container container-padding-sm">Small Padding</div>
<div class="container container-padding-md">Medium Padding</div>
<div class="container container-padding-lg">Large Padding</div>
```

## Rounded Containers

Create containers with rounded corners using the following classes:

- `.container-rounded` (10px border-radius)
- `.container-rounded-lg` (20px border-radius)
- `.container-rounded-xl` (30px border-radius)

```html
<div class="container container-rounded">10px Rounded Container</div>
<div class="container container-rounded-lg">20px Rounded Container</div>
<div class="container container-rounded-xl">30px Rounded Container</div>
```

## Centering Content

Use `.container-centered` to align content in the center of the container, both horizontally and vertically.

```html
<div class="container container-centered" style="height: 200px;">
  Centered Content
</div>
```

## Browser Support

The **wise.css** container system is supported in all modern browsers, including:

- Chrome
- Firefox
- Safari
- Edge
- Opera

## Example

Here’s an example of how to use the **wise.css** container system:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>wise.css Container Demo</title>
  <link rel="stylesheet" href="https://pgnetwork01.github.io/wise/wise.css">
</head>
<body>

  <div class="container container-md">
    This is a responsive container with a max-width of 720px.
  </div>

  <div class="container-fluid">
    This is a full-width container.
  </div>

  <div class="container container-padding-lg">
    This container has large padding.
  </div>

  <div class="container container-rounded">
    This container has 10px rounded corners.
  </div>

  <div class="container container-centered" style="height: 200px;">
    Centered content inside the container.
  </div>

</body>
</html>
```

## License

This project is licensed under the MIT License.
```

### Explanation:

- The **README.md** file provides clear documentation on how to use different types of containers, including responsive breakpoints, padding, rounded corners, and centering content.
- It includes code examples for each type of container and explanations of their use.
- Users are guided on how to integrate **wise.css** into their projects, along with a complete example at the end for reference.
