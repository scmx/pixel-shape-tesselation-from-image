# pixel-shape-tesselation-from-image

> 🖼️✨ Convert images into tessellating pixel shape art! Upload an image to
> generate a pixel layout with customizable shapes and colors. Perfect for
> printing custom building instructions. 🎨🔲🖨️

## Pixel Shape Tessellation from Image (Early Development)

An upcoming simple web tool that converts an image into a 2D pixel art design.
Users can upload an image, and the tool generates a tessellated pixel art
layout based on a chosen tesselating single-colored pixel shape in a set of
available colors and quantities. The tool will support various pixelated shapes
that tessellate together to create a cohesive design.

This project aims to be generic, supporting different pixel shapes. A separate
project may focus on specific tessellating pixel shapes whose names are not
mentioned here.

[View the current version deployed here](https://scmx.github.io/pixel-shape-tessellation-from-image/)

## Planned Features

1. **Load an image**: Upload an image using an input field
2. **Draw image on canvas**: Render the uploaded image on an HTML5 canvas
3. **Define tessellating pixel shape**: Load or define a pixel shape that tessellates
4. **Extract pixel data**: Extract pixel data from the image and fit it to the
   defined shape
5. **List available colors**: Display a list of available colors and their quantities
6. **Generate pixel art layout**: Create a tessellated layout of pixel shapes
   over the image, mapping pixel areas to the best-fitting shapes and colors
7. **Display result**: Show the final pixel art design on the canvas
8. **CSS for printing**: Include styling for printing the pixel art instructions

## Future Ideas

- **Advanced color list**: Implement a more detailed list for available colors,
  allowing users to specify quantities and types
- **Drag-and-drop functionality**: Enable users to drag and drop images
  anywhere on the page to upload them
- **Print button**: Add a button to print the resulting pixel art design
- **Adjustable grid and zoom level**: Provide options for users to adjust the
  grid size and zoom level before generating the design
- **Manual shape swapping**: Allow users to manually swap out shapes in the
  design for customization purposes
- **Remove edge shapes**: Option to remove shapes on the edge of the image to
  create a more seamless design

## Tech Stack

- **HTML**: For page structure and image input functionality
- **JavaScript**: For image processing, pixel extraction, color matching, and
  rendering the pixel art layout
- **CSS**: For styling the interface and ensuring printable instructions
- **GitHub Pages**: Deployed to GitHub Pages for easy access and hosting

## Usage

1. Open the project in your browser
2. Upload an image
3. The tool will:
   - Draw the image on the canvas
   - Extract pixel data from the image
   - Generate a tessellated pixel art layout based on the defined shapes
   - Display the result with matching pixel shapes and colors
4. Print the result using the print button (if available)

## Roadmap

- [ ] **Load an image**: Implement image upload functionality
- [ ] **Draw image on canvas**: Render the uploaded image on the HTML5 canvas
- [ ] **Define tessellating pixel shape**: Set up a tessellating pixel shape
- [ ] **Extract pixel data**: Extract and process pixel data from the image
- [ ] **List available colors**: Provide a list of available colors and quantities
- [ ] **Generate pixel art layout**: Create a tessellated pixel art layout
      based on color matching
- [ ] **Display result**: Show the final design on the canvas
- [ ] **CSS for printing**: Add print CSS styling
- [ ] **Print button**: Include a button for printing
- [ ] **Drag-and-drop functionality**: Support drag-and-drop image upload
- [ ] **Advanced color list**: Implement a detailed color list
- [ ] **Preview during drag and drop**: Show a preview while dropping an image
- [ ] **Adjustable grid and zoom level**: Add options for grid size and zoom
      level adjustments
- [ ] **Different color matching algorithms**: Explore additional color
      matching algorithms
- [ ] **Manual shape swapping**: Allow manual swapping or skipping of shapes
- [ ] **Printable building instructions**: Generate printable instructions with
      color details
