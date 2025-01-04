Green Screen Removal using OpenCV

Overview

This project provides a simple and efficient way to remove green screens from images and videos using OpenCV. The script uses chroma keying to detect and replace the green screen with a background image or video.

Requirements
- OpenCV 4.x or later
- Python 3.x or later
- NumPy
*Usage*
---------
1. Clone the repository or download the script.
2. Install the required dependencies using pip: `pip install opencv-python numpy`
3. Run the script using Python: `python (link unavailable)`
*Command-Line Arguments*
-----------------------------
- `--input`: Input image or video file path.
- `--background`: Background image or video file path.
- `--output`: Output file path.
- `--threshold`: Threshold value for chroma keying (default: 30).
*Example Usage*
-----------------
- Remove green screen from an image: `python (link unavailable) --input input_image.jpg --background background_image.jpg --output output_image.jpg`
- Remove green screen from a video: `python (link unavailable) --input input_video.mp4 --background background_video.mp4 --output output_video.mp4`
*Code Explanation*
----------------------

The script uses the following steps to remove the green screen:

1. Load the input image or video using OpenCV.
2. Convert the image or video to the HSV color space.
3. Apply chroma keying to detect the green screen.
4. Replace the green screen with the background image or video.
5. Save the output image or video.
*Tips and Variations*
-------------------------
- Adjust the threshold value to fine-tune the chroma keying.
- Use a different background image or video for each frame of the input video.
- Apply additional image processing techniques, such as blur or sharpen, to the output image or video.
*License*
------------

This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments

This project uses OpenCV, a computer vision library developed by Intel. See the OpenCV website for more information.
