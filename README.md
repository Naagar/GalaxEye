# Sandeep_Nagar_GalaxEye
An algorithm that takes a .jpg image of an arbitrary size with 3 channels (Red, Green, Blue) and returns a string with either of the two values: “Day” or “Night”.

- We know in black and white images (night images, true for most cases), the difference between pixels' RGB values is near to zero.
 
- Therefore, calculate the differences between channels for all pixels (R-G, G-B, B-R).

- Afterwards, consider the square of the differences avoiding negative values.

- And then we find the mean values for all differences.

- If this mean value is near to zero then the image is taken at night, otherwise it is taken in day light.
