# Responsive-Fancbox-Gallery
A simple and responsive fancbox gallery built with HTML, CSS, and JavaScript using Bootstrap and Fancybox.

## DEMO
[https://responsive-fancybox-gallery.pages.dev/](https://responsive-fancybox-gallery.pages.dev/)


## Features

- Responsive design that adapts to various screen sizes.
- Lightbox functionality to view images in a larger format.
- Smooth hover effects with a magnifying glass icon using Font Awesome.
- 1:1 aspect ratio for images ensuring uniformity in display.

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, etc.)
- Basic knowledge of HTML, CSS, and JavaScript

### Installation

1. Clone the repository or download the ZIP file.
2. Open the `index.html` file in your web browser.

## Usage

To add more images to the gallery:

1. Place your images in the `images` directory.
2. Add a new `<div class="col-md-3">` section in the `index.html` file for each new image, following the existing format.

**Example:**

```
<div class="col-md-3">
    <a href="images/new-image.jpg" data-fancybox="gallery" data-caption="Description for New Image"><img src="images/new-image.jpg" alt="New Image"></a>
</div>
```
## License
This project is licensed under the MIT License. Feel free to use and modify it for your own purposes.

## Acknowledgments

[Bootstrap](https://getbootstrap.com/) for the responsive framework. 
[Fancybox]([https://fontawesome.com/](http://fancyapps.com/fancybox/)) for the lightbox functionality.
[Font Awesome](https://fontawesome.com/) for the iconography.
