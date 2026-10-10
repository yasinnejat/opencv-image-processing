# Image Processing with OpenCV

A Jupyter Notebook that walks through the basic image processing operations in **OpenCV**: loading an image, converting color spaces, cropping, resizing, thresholding and blurring.

## Files
- `opencv_image_processing.ipynb` — the Jupyter Notebook.
- `requirements.txt` — Python dependencies.

## Before you run it
The notebook reads an image named `face.jpg` from the same folder. The image is **not included** in this repository (it is listed in `.gitignore`), so add your own photo with that name. The crop coordinates in the notebook (`[50:450, 125:575]`) were chosen for one specific image, so adjust them to fit yours.

## Run the project
1. Install Python 3.10 or newer.
2. In this folder, install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Put your image next to the notebook and name it `face.jpg`.
4. Open `opencv_image_processing.ipynb` in Jupyter Notebook, JupyterLab, or VS Code and run the cells from top to bottom.

`cv2.imshow` opens a desktop window, so run the notebook on your own computer rather than in a headless environment. Press any key in the image window to continue.

## Workflow
1. Load an image with `cv2.imread`.
2. Display it with `cv2.imshow` and inspect pixel values.
3. Convert from BGR to RGB with `cv2.cvtColor` and display it with Matplotlib.
4. Crop a region of interest using array slicing.
5. Resize the cropped region to 100 x 100 pixels.
6. Convert to grayscale.
7. Apply a binary threshold.
8. Apply a Gaussian blur.

## Technologies
Python, OpenCV, Matplotlib, Jupyter Notebook.
