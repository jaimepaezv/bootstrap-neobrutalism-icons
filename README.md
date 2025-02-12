# Neobrutalist Bootstrap Buttons

**Give your Bootstrap 5.3 buttons a raw, edgy, and unapologetically digital makeover with a Neobrutalist twist!**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Bootstrap 5.3.x Compatible](https://img.shields.io/badge/Bootstrap-5.3.x-blueviolet.svg)](https://getbootstrap.com/)
[![CSS Valid](https://img.shields.io/badge/CSS-Valid-brightgreen.svg)](https://jigsaw.w3.org/css-validator/) <!-- Replace with actual validation link if you validate -->

[**✨ View Live Demo ✨**](#) <!-- Replace with your actual live demo link if you host it online -->

## Introduction to Neobrutalist Bootstrap Buttons

This project provides a CSS utility layer built on top of Bootstrap 5.3 to redefine the default button styles with a **Neobrutalist aesthetic**. Neobrutalism, in the context of web design, embraces a raw, almost unfinished digital look. It's characterized by:

*   **Bold Typography:** Often uses system fonts and emphasizes clarity over finesse (though not directly implemented in *just* buttons here, it's part of the broader style).
*   **Sharp Corners:** Rejects rounded edges for a more angular and digital feel.
*   **Thick Borders:** Emphasizes outlines and separation through prominent borders.
*   **Geometric Shapes and Layouts:**  Simple, strong shapes and grid-based layouts are common (button shapes are inherently geometric!).
*   **Subtle Shadows and Depth:**  Used sparingly to create a sense of layering and physicality in the digital space.
*   **Limited Color Palettes:** Often sticks to a few high-contrast colors to maintain focus and visual impact.

This utility aims to bring this distinctive style to your Bootstrap projects, offering a unique and assertive button design. We've chosen a limited color palette of **white, black, and orange** to exemplify the neobrutalist principle of focused color usage, while still providing flexibility through Bootstrap's button variations.

**Why Neobrutalism with Bootstrap?**

You might ask, "Why combine the raw, almost anti-design ethos of neobrutalism with a structured framework like Bootstrap?"  Here's the justification:

*   **Bootstrap's Flexibility is Key:** Bootstrap 5.3, built with CSS variables, is incredibly flexible. It's designed to be themed and customized. This project leverages Bootstrap's variable system to redefine the core button styles without rewriting the entire component structure.

*   **Ease of Adaptation and Theming:** Bootstrap's architecture makes it surprisingly easy to adapt its components to drastically different visual styles. By overriding a set of CSS variables, we can transform the look and feel of Bootstrap's buttons to embody neobrutalism, proving its adaptability beyond its default styling.

*   **Because We Can! (Creative Exploration):**  Sometimes, the most interesting projects arise from exploring unexpected combinations.  This project is a testament to the idea that you can push frameworks like Bootstrap beyond their typical use cases and create something visually striking and unique. It's a fun experiment in juxtaposing structured utility with raw aesthetic.  Why not bring a bit of digital grit to a widely-used UI framework?

## Features

*   **Neobrutalist Button Styling:** Buttons are transformed with sharp corners, thicker borders, and subtle offset shadows characteristic of neobrutalism.
*   **White, Black, and Orange Color Palette:**  Adheres to a focused color scheme, using white, black, and orange for a high-contrast and visually impactful look.
*   **Overridden Bootstrap Variables:**  Implements a layer over Bootstrap by redefining key button CSS variables, ensuring maintainability and compatibility.
*   **Styling for All Button Types:**  Applies the neobrutalist style consistently across all Bootstrap button variations:
    *   Default `.btn`
    *   Contextual buttons: `.btn-primary`, `.btn-secondary`, `.btn-success`, `.btn-danger`, `.btn-warning`, `.btn-info`, `.btn-light`, `.btn-dark`
    *   Link button `.btn-link`
    *   Outline buttons: `.btn-outline-*`
*   **Enhanced Hover and Active/Focus States:**  Provides clear visual feedback for user interaction with pronounced hover effects (larger shadows, slight translation) and active/focus states (inset shadows, "pressed" effect).
*   **Clean and Well-Commented CSS:**  The provided CSS (`neobrutalist-bootstrap-buttons.css`) is well-organized and commented for easy understanding and customization.

## Installation

To use these neobrutalist Bootstrap buttons in your project:

1.  **Download `neobrutalist-bootstrap-buttons.css`:**  Download the `neobrutalist-bootstrap-buttons.css` file from this repository.

2.  **Include Bootstrap 5.3 CSS:** Ensure you have Bootstrap 5.3 CSS included in your HTML. If you're using Bootstrap from a CDN, you'll likely have a line like this in your `<head>`:

    ```html
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    ```

3.  **Include `neobrutalist-bootstrap-buttons.css` After Bootstrap:**  Link the `neobrutalist-bootstrap-buttons.css` file **after** the Bootstrap CSS file in your HTML. This is crucial for your overrides to take effect:

    ```html
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Your Neobrutalist Project</title>
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
        <link rel="stylesheet" href="neobrutalist-bootstrap-buttons.css"> <!--  ✅ IMPORTANT: Link AFTER Bootstrap CSS -->
        </head>
    <body>
        <!-- Your page content -->
    </body>
    </html>
    ```

4.  **That's it!** Your Bootstrap buttons in your project should now be styled with the neobrutalist look.

## Usage

Simply use Bootstrap's standard button classes in your HTML. The `neobrutalist-bootstrap-buttons.css` will automatically style them:

```html
<button type="button" class="btn">Default Button</button>
<button type="button" class="btn btn-primary">Primary Button</button>
<button type="button" class="btn btn-secondary">Secondary Button</button>
<button type="button" class="btn btn-success">Success Button</button>
<button type="button" class="btn btn-danger">Danger Button</button>
<button type="button" class="btn btn-warning">Warning Button</button>
<button type="button" class="btn btn-info">Info Button</button>
<button type="button" class="btn btn-light">Light Button</button>
<button type="button" class="btn btn-dark">Dark Button</button>
<button type="button" class="btn btn-link">Link Button</button>

<button type="button" class="btn btn-outline-primary">Primary Outline</button>
<button type="button" class="btn btn-outline-secondary">Secondary Outline</button>
<!-- ... and so on for other outline buttons ... -->
```

Refer to the neobrutalist-bootstrap-buttons.html file for a complete example.

## Customization

You can easily customize the neobrutalist button style further by modifying the CSS variables and rules in neobrutalist-bootstrap-buttons.css:

- **Color Palette:** Change the --bs-white, --bs-black, and --bs-orange variables in the :root selector to adjust the color scheme.

- **Border Thickness:** Modify the --neobrutalist-border-width variable to make borders thicker or thinner.

- **Shadows:** Adjust the box-shadow properties in the .btn, .btn:hover, and .btn:active rules to change the shadow offset, blur, and color.

- **Hover and Active Effects:** Customize the transform and other CSS properties in the :hover and :active rules to modify the interactive effects.

- **Font Styles:** While this project primarily focuses on button colors and shapes, you could extend the CSS to also redefine button font styles (font-family, font-weight, etc.) for a more complete neobrutalist typographic approach.

## Why Neobrutalism + Bootstrap? (Elaborated)

As mentioned in the introduction, the combination might seem unconventional, but it's a powerful demonstration of Bootstrap's versatility.

- **Bootstrap's Foundation is Robust:** Bootstrap provides a solid, accessible, and responsive base. We are not discarding this foundation, but rather re-skinning it. This allows us to benefit from Bootstrap's grid system, utility classes, and JavaScript components while applying a completely different visual layer.

- **Separation of Concerns:** This approach clearly separates structure and style. Bootstrap handles the layout and component functionality, while neobrutalist-bootstrap-buttons.css focuses purely on the visual presentation. This separation makes maintenance and further customization cleaner and easier.

- **Challenging Conventions:** Neobrutalism, by its nature, challenges typical web design conventions. Applying it to a widely-used framework like Bootstrap is a way to explore how even established tools can be used in unexpected and unconventional ways. It's about pushing boundaries and seeing what's possible.

## Contributing

Contributions are welcome! If you have ideas for improvements, bug fixes, or further neobrutalist styling enhancements, please feel free to:

1. **Fork the repository.**

2. **Create a branch for your feature or fix.**

3. **Make your changes and commit them.**

4. **Submit a pull request.**

Please also report any issues or suggestions through the issue tracker.

## License

This project is licensed under the [MIT License](https://www.google.com/url?sa=E&q=LICENSE) - see the LICENSE file for details.

## Screenshot (Demo)

![image](https://github.com/user-attachments/assets/9df4f15c-e88c-4840-937b-9e593474ec99)
