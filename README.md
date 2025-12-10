# Visibuy-Test-Requirement
When the program is ran in an IDE, a tkinter window first appears
Here, you click a button, 'Select Images'
The first image to be selected is the image of interest to be compared
Once the two images are selected, the exif metadata is gotten, if available and shown on the terminal
The images are also compared, and displayed with text if they are similar, exactly the same, or different

#Libraries and approach
I used tkinter to create a simple user interface that asked for image files and included a button
Then, I used opencv(cv2) and numpy to obtain the pHash for each image and compare them
And, using the PIL packages and some of it's functions, I was able to retrieve the EXIF metadata and display it, if available.
