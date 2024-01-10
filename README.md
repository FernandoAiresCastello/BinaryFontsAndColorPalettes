# Binary Fonts and Color Palettes

This is a collection of files containing the definition of character fonts and color palettes from various classic computers and videogame consoles.

All files are in plain-text format where each line represents a character (in font files) or color (in palette files).

For character font files, each line representing an individual character is in a "binary string" format that contains 64 pixels, where 0 stands for "pixel off" and 1 stands for "pixel on". By arranging the digits from left to right in an 8x8 square you can get the pattern of that character for subsequent rendering.

For color palette files, each line representing an individual color is in an "RGB" format that contains a 24-bit hexadecimal value, such as FF0000 (red), 00FF00 (green), 0000FF (blue), FFFFFF (white) or 000000 (black). There is no transparency/alpha component.
