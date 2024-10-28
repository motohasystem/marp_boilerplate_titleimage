
# Title Image Boilerplate for Marp

This repository provides a boilerplate for creating title image slides for blog posts using Marp. Follow the steps below to easily generate a title image.

The target output image size is 1280x680. You can customize `title_image.css` if adjustments are necessary.

## Sample Title Image

### Input Image

<img src="./img/paint_with_acrylic.png" width="200px" />

### MARP (Part of index.md)

```
# <!-- class: normal -->
Painting New Year Decorations with Acrylic Paint

![bg fit 100%](img/paint_with_acrylic.png)
```

### Output Image

<img src="./img/title.png" width="300px" />

# Usage

## Requirements

- Node.js
- Marp CLI

## Setup

1. Install Node.js.
2. Install Marp CLI globally.

   ```bash
   npm install -g @marp-team/marp-cli
   ```

3. Clone this repository.

   ```bash
   git clone https://github.com/motohasystem/marp_boilerplate_titleimage
   cd marp_boilerplate_titleimage
   ```

## Creating Slides

1. Edit the `index.md` file to add the slide content. You can create slides in Markdown format.

2. Run `make.bat` to generate the slides as an image.

   ```bash
   make.bat
   ```

   This will generate an image file named `index.png`.

## Using Custom Themes

- A custom CSS theme is included in the `themes` folder. You can specify the theme used in `make.bat`.

  Example: To use `themes/title_image.css`, modify the `--theme` option in `make.bat`.

## Notes

- Note that `make.bat` is a batch file for Windows.
- To customize slide design, edit the CSS files in the `themes` folder.

Enjoy creating fantastic slides with this boilerplate!