# DynamicBlog

This script takes user input (title, body, and *optional* image) via a tkinter gui and converts into html code.

The script looks for a specific html comment within the .html file and adds the new code underneath. New entries will always be shown on top.

 - Note: if an image is selected, the script copies the image (using shutil) to the scripts local working directory in an "image" folder.
 
 tkinter: https://docs.python.org/3/library/tkinter.html
 shutil: https://docs.python.org/3/library/shutil.html
