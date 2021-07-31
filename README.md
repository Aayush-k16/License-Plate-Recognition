# License-Plate-Recognition

The project has been built on MATLAB R2019B

Steps to run the License Plate Recognition project:
  - Download the image processing toolbox from MATLAB if you don't have it already (link: https://www.mathworks.com/products/image.html)
  - Clone this repository using the command **git clone https://github.com/Aayush-k16/License-Plate-Recognition.git** on your cmd or terminal.
  - Save the folder from where MATLAB can access it.
  - Open MATLAB (yeah, it takes a lot of time to start-up -- be patient) - open the folder you just downloaded.
  - Choose the lpr.m file and **modify line number 3** with the path of any vehicle's image having license plate in the clear. 
  - Click on build and run the program
  - The characters read from the image should be displayed separately -- thereby showcasing successful segmentation and the segmented charcaters will be read by matching it from the char file (a database) and checking the similarity between the recognised character and each character present in the database. The output will be displayed on MATLAB itself.

For doubts regarding running the program: mailto kumar.aayush1609@gmail.com
