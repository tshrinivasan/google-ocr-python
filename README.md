Automation of google ocr using python
=====================================


See a demo video on installation,  setup, usage in Tamil here: https://www.youtube.com/watch?v=PH9TnD67oj4&feature=youtu.be


1. install gdcmdtools from https://github.com/tienfuc/gdcmdtools and complete the setup
2. use "convert" tool by imagemagics to convert a pdf into individual images.

  exaimple:

  convert -density 300  shrini-articles-malaigal.pdf -quality 100 shrini-%03d.jpg

3. run the program

python google-ocr.py

This will upload all the images into google drive, ocr it, download it as a text file and combine all the text file as "ocr-result.txt"


Todo
====

1. Clean the code 
2. Ask a foldername to store all images in a seperate folder, so that we can delete that folder later
3. Download as odt file and merge all odt files as odt file keep better formatting
