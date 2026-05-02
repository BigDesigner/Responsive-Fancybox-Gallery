[![GitHub Release](https://img.shields.io/github/v/release/BigDesigner/Responsive-Fancybox-Gallery?style=flat)](https://github.com/BigDesigner/Responsive-Fancybox-Gallery/releases/tag/v1.0.0)
[![GitHub Repo stars](https://img.shields.io/github/stars/BigDesigner/Responsive-Fancybox-Gallery?style=flat)](https://github.com/BigDesigner/Responsive-Fancybox-Gallery)
[![X Follow](https://img.shields.io/twitter/follow/muratgonen?style=flat)](https://x.com/muratgonen)

# Responsive-Fancybox-Gallery
A simple, modern, and responsive fancybox gallery built with HTML5 and CSS3, using the latest versions of Bootstrap 5, Fancybox 5, and Font Awesome 6. Now completely jQuery-free!

## DEMO
Demo 1 : [https://responsive-fancybox-gallery.pages.dev/](https://responsive-fancybox-gallery.pages.dev/)

Demo 2 : [https://bigdesigner.github.io/Responsive-Fancybox-Gallery/](https://bigdesigner.github.io/Responsive-Fancybox-Gallery/)


## Features

- **Bootstrap 5**: Modern responsive design that adapts to all screen sizes.
- **Fancybox 5**: High-performance lightbox functionality for a premium viewing experience.
- **Font Awesome 6**: Crisp icons and smooth hover effects.
- **No jQuery**: Lightweight and faster loading by removing legacy dependencies.
- **1:1 Aspect Ratio**: Uniform image display using modern CSS `aspect-ratio`.

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge, etc.)
- Basic knowledge of HTML and CSS.

### Installation

1. Clone the repository or download the ZIP file.
2. Open the `index.html` file in your web browser.

## Usage

To add more images to the gallery:

1. Place your images in the `images` directory.
2. Add a new `<div class="col-md-3">` section in the `index.html` file for each new image, following the existing format.

**Example:**

```html
<div class="col-md-3">
    <a href="images/new-image.jpg" data-fancybox="gallery" data-caption="Description for New Image">
        <img src="images/new-image.jpg" alt="New Image">
    </a>
</div>
```

## License
This project is licensed under the MIT License. Feel free to use and modify it for your own purposes.

## Acknowledgments

- [Bootstrap](https://getbootstrap.com/) for the responsive framework. 
- [Fancybox](https://fancyapps.com/fancybox/) for the lightbox functionality.
- [Font Awesome](https://fontawesome.com/) for the iconography.
