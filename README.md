# UI Card Hovers

UI Card Hovers is a lightweight and customizable library for adding interactive hover effects to cards in your web projects. This library simplifies the process of creating engaging user interfaces by adding dynamic and visually appealing hover animations to your card components.

![1](https://github.com/abdul-1432/UI_Card_Hover/assets/124916666/43e2f778-a358-4697-a204-aae6f7937f43)
![2](https://github.com/abdul-1432/UI_Card_Hover/assets/124916666/7b8e6d93-e05f-4455-8f0f-6ab5cab584e0)
![3](https://github.com/abdul-1432/UI_Card_Hover/assets/124916666/728b9f02-7e87-44dd-b031-e016bc343288)
![4](https://github.com/abdul-1432/UI_Card_Hover/assets/124916666/48a02c4e-cedd-4332-af02-8d1518d4c9a5)
![5](https://github.com/abdul-1432/UI_Card_Hover/assets/124916666/0c1adbb4-9b3c-4ead-be08-d0a5a2733c27)

## Features

- **Easy Integration**: With just a few lines of code, you can add captivating hover effects to your card elements, enhancing user interaction and visual appeal.

- **Customizable**: UI Card Hovers provides a range of built-in hover effects, and you can easily customize the animation speed, colors, and other parameters to match your project's design.

- **Responsive**: The hover effects are designed to work smoothly on both desktop and mobile devices, ensuring a consistent and enjoyable user experience across different screen sizes.

## Getting Started

### Installation

You can include UI Card Hovers in your project using the following methods:

1. **CDN**: Include the following stylesheet in the `<head>` section of your HTML file:

   ```HTML
   <link rel="stylesheet" href="https://github.com/abdul-1432/UI_Card_Hover/blob/main/UI%20Card%20Hovers/home.html">
   ```

2. **Download**: Download the `ui-card-hovers.min.css` file from this repository and link it to your HTML.

### Usage

1. Add the `ui-card` class to your card container element:

   ```HTML
   <div class="ui-card">
       <!-- Card content goes here -->
   </div>
   ```

2. Choose a hover effect class and add it to the card container element:

   ```HTML
   <div class="ui-card ui-card-flip">
       <!-- Card content goes here -->
   </div>
   ```

   You can replace `ui-card-flip` with any other available hover effect class.

3. Customize the hover effect (if desired) by adding additional classes and modifying the stylesheet parameters.

### Available Hover Effects

- `ui-card-flip`: Card flips horizontally on hover.
- `ui-card-zoom`: Card zooms in slightly on hover.
- `ui-card-slide`: Card slides up on hover, revealing content.
- `ui-card-rotate`: Card tilts and rotates on hover.

### Example

```html
<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" href="https://cdn.example.com/ui-card-hovers.min.css">
    <style>
        /* Additional custom styles */
        .ui-card {
            width: 250px;
            height: 350px;
            background-color: #f2f2f2;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease-in-out;
        }
    </style>
</head>
<body>
    <div class="ui-card ui-card-flip">
        <img src="card-image.jpg" alt="Card Image">
        <div class="card-content">
            <h3>Card Title</h3>
            <p>Card description goes here.</p>
        </div>
    </div>
</body>
</html>
```

## Customization

To customize the hover effects and styles further, you can modify the provided CSS classes or add your own styles.

## License

UI Card Hovers is released under the [MIT License](LICENSE).

## Acknowledgements

UI Card Hovers was inspired by the need to create more engaging and interactive card-based user interfaces. We are grateful to the open-source community for their contributions and feedback.

---

Feel free to contribute, report issues, or suggest enhancements! We hope you enjoy using UI Card Hovers to create dynamic and visually stunning web interfaces.
