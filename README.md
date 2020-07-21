# Photo-Sketching
A small code that can convert an image to a pencil sketch like image. An image is basically an array of numbers to Python. So we can perform a variety of matrix manipulations to get some very interesting results. This code shows how to reduce an image into a ‘pencil’ outline.

## Steps Followed
- Read the input image as gray scale image
- Remove any noise using a gaussian filter
- Create a negative image (invert the image)
- Dodge these two images(gray and inverted images). These two images reinforces some edges and complements some edges. Alternatively, these two images can be blended with different weights
- Show the image and wait for a keystroke to close the display

## Results
<div style="float:left">
<div style="float:left"><img width="45%" src="https://github.com/jyoti0225/Photo-Sketching/blob/master/input_img.png" />
<img width="45%" src="https://github.com/jyoti0225/Photo-Sketching/blob/master/output_img.png" /></div>
</div>
<br /><br />
