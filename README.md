# imageDifferences
This MATLAB project detects differences between two images by comparing their pixel values and highlighting the changes. It’s useful for spotting differences in images, debugging visual discrepancies, and comparing modified designs.

✨ Features
  Loads and processes two images
  Converts images to grayscale (if needed)
  Computes pixel-wise absolute difference
  Highlights differences in red for easy visualization
  Simple and easy-to-understand code

🔧 How It Works
Load two images (image1.jpg & image2.jpg).

Convert them to grayscale (if they are colored).

Compute the absolute difference between the two images.

Apply a threshold to detect meaningful changes.

Highlight the detected differences in red on the original image.

📌 Usage
Place your images in the same folder as the script.

Run the MATLAB script:

matlab
Copy
Edit
image_difference.m
The result will show both original images, their grayscale versions, and the highlighted differences.

🎯 Applications
🔹 Spot the difference in image pairs
🔹 Detect tampered or altered images
🔹 Compare edited designs
🔹 Debug UI/UX changes in software screenshots
