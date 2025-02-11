# mirror

This code creates a dynamic video-based visual effect using p5.js. It performs the following actions:

1. **Preload Function**: 
   - Loads a series of GIF images into an array.

2. **Setup Function**: 
   - Accesses the user's camera and sets up the video stream.
   - The video is resized to fit a grid based on the window size, with columns and rows calculated accordingly.

3. **Draw Function**:
   - Analyzes the video pixels for their brightness values.
   - Based on the brightness, a corresponding GIF is selected from the array.
   - Each GIF is displayed in a grid cell, with a random section of the GIF shown based on the cell's position.

The final result is a pixelated video grid where GIFs are displayed based on the brightness of the video feed.
