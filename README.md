# color_correction
Using OpenCV to color correctimages with Pantone color cards.
Make sure all the python and opencv packages are there before running the code.
The code takes input of input.jpg .
Identifies and extracts the Pantone Color Card. It creates a new image with just the card area.
Matches the histogram of the input Pantone Color Card with that of reference.
You can run the script using the following command and parameters: 
python color_correction,py -r reference.jpg -i input.jpg
