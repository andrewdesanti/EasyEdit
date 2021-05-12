# EasyEdit
## *The Easiest Photo Editing Tool*
### What Is It?
EasyEdit is Andrew DeSanti and Joshua Hornila's final project for CPE462, Introduction to Image Processing and Coding, for the Spring 2021 semester at Stevens Institute of Technology.

This program itself is a simple photo editor. It was tested and intended for both .png and .jpg images, however it is possible that some or perhaps all functions will function for other file formats (Your Milage May Vary!). It includes several simple functions that an end user would want to use for their own photo editing purposes, all while being very simple to understand when compared to a larger photo editor like Photoshop and GIMP.

### How Was It Made?
The program is a MATLAB App, an interactive application built within MATLAB that can perform technical computing tasks. 
- The GUI is created using MATLAB's App Designer tool, a developer-friendly interface useful in creating GUI's for an end user. 
- The logic for the GUI's componants is written in traditional MATLAB and linked automatically to the interactive parts of the GUI. 
-  The MATLAB logic takes advantage of many of MATLAB's built in functions, many coming from the Image Processing and Signal Processing Toolboxes.

### How To Use It, How Does It Work?
Running EasyEdit of course requires MATLAB! Once pathed into your MATLAB enviroment, it should be as simple as running the EasyEdit.mlapp by double-clicking it from MATLAB's built in file explorer to open it in App Designer and pressing "Run". From here, the GUI enviroment can be seen in the "Design View" tab, and the logic for the GUI componants can be viewed from the "Code View" tab. 

Once running, a .png or .jpg file can be imported by typing the file name (Including the Extension!) into the "File Import Name:" box and pressing the "Import The Below Image" button. Assuming the file is contained within the same directory as EasyEdit.mlapp, is spelled correctly, and is a valid format, it should appear within the "Current State of The Image:" grid.  

Every function essentially works the same. With either the press of a button or move of a slider, the correspondng function is ran and the outcome is displayed on the "Current State of The Image:" grid. To apply the change, press "Apply Changes", to cancel, press "Cancel". Once applied, the function cannot be undone within the editor, however, the photo is NOT saved!

Exporting the finished image is very similar to importing. In the "Import and Export" tab, type the desired exported picture filename into the "File Export Name" box and press "Export The Above Image As:". (You have to include the file extension!) The file will be saved to the directory containing EasyEdit.mlapp. 

### Supported Functions:
- 90 Degree Rotations (Counter-Clockwise)
- Invert over Y-Axis
- Convert to Grayscale
- Invert Colors
- Sepia Filter (Only Works for Color Photos!)
- Entropy Filter
- Brightness Slider
- Contrast Slider
- Saturation Slider (Only Works for Color Photos!)
- Blur Slider
- Salt and Pepper Slider
- Speckle Slider
- Sharpen Slider
- Histogram Equalization (Converts to Grayscale)
- 3x3 Mask (Converts to Grayscale)
- Adaptive Tresholding (Statistically, YMMV)

## I pledge my honor that I have abided by the Stevens Honor System:
### *-Andrew DeSanti, Joshua Hornilla*
