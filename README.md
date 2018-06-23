# PhotoMosaic
Using OpenMP to create photo mosaic effect

## Comments
  - take out -fopenmp flag to run in serial or if the library is not supported
  - this project only works on a Linux machine (has not implemented file search for Windows yet)
  - has not created Makefile yet for compilation
  - replace the rgbTable to reset the database
## Commands
### Pre-process:
  - Create img folder and add any number of images to add to the database
  - Compile using "g++ -fopenmp process.cpp -o [filename]"
  - Execute using "./[filename]"
### Create Mosaic:
  - Get a target image (the higher the quality the better)
  - Compile using "g++ -fopenmp main.cpp -o [filename]"
  - Execute using "./[filename]"
  
## Reference:
  - Edge Detection Algorithm: http://www.pages.drexel.edu/~nk752/Research/cannyTut2.html#Step 1
  - Read and Write JPG: https://github.com/nothings/stb
  - Get Filenames: http://www.martinbroadhurst.com/list-the-files-in-a-directory-in-c.html
