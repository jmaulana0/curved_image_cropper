# Curved Image Cropper

A simple web-based tool for cropping images with curved edges. Upload an image, adjust the curve parameters using sliders, and download the result as a PNG with transparency.

## Features

- **Image Upload**: Support for various image formats
- **Real-time Preview**: See changes instantly as you adjust the curve
- **Adjustable Curve**: Three sliders to control:
  - Left edge height
  - Right edge height
  - Curve bend depth
- **Transparent Background**: Output maintains transparency with a checkerboard preview
- **High-Resolution Output**: Canvas renders at original image resolution

## How to Use

1. Open `index.html` in your web browser
2. Click "Upload Image" to select an image file
3. Adjust the three sliders to shape the curve:
   - **Left Edge Height**: Controls how far down the left side extends
   - **Right Edge Height**: Controls how far down the right side extends
   - **Curve Bend (Depth)**: Controls the curvature between the edges
4. Preview the result in real-time
5. Click "Download Image" to save the cropped image as PNG

## Technologies Used

- **HTML5 Canvas**: For image manipulation and rendering
- **Tailwind CSS**: For styling and responsive design
- **Vanilla JavaScript**: For interactivity and canvas operations

## Browser Support

Works in all modern browsers that support HTML5 Canvas and File API.

## License

MIT License - feel free to use and modify as needed.