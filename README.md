[![N|Solid](https://education.gov.gy/web/media/k2/items/cache/6d4f9be9bbf8e6f07458f60414b62a53_XL.jpg)](https://education.gov.gy/web/media/k2/items/cache/6d4f9be9bbf8e6f07458f60414b62a53_XL.jpg)
# Colour Detection using Python !
[~ By Mayuresh Patil]()

Colour detection is the process of detecting the name of any color. Simple isn’t it? Well, for humans this is an extremely easy task but for computers, it is not straightforward. Human eyes and brains work together to translate light into color. Light receptors that are present in our eyes transmit the signal to the brain. Our brain then recognizes the color. Since childhood, we have mapped certain lights with their color names. We will be using the somewhat same strategy to detect color names.

## The Dataset
Colors are made up of 3 primary colors; red, green, and blue. In computers, we define each color value within a range of 0 to 255. So in how many ways we can define a color? The answer is 256*256*256 = 16,581,375. There are approximately 16.5 million different ways to represent a color. In our dataset, we need to map each color’s values with their corresponding names. But don’t worry, we don’t need to map all the values. We will be using a dataset that contains RGB values with their corresponding names. The CSV file for our dataset has been taken from this link:

## Dependencies
```
pip install opencv-python numpy pandas
```
