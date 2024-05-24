
# Coral Area Generator V1

The Coral Area Generator V1 utilizes YOLO V8 and the Segment Anything Model (SAM) to automatically find the area of corals in an image. 

## Getting Started

Make sure to download the "Coral Area Generator Folder" with its specific formats and ml models into your google drive so the code works flawlessly: https://drive.google.com/drive/folders/1I2PxS79XVj3VTLM-lKzeGh2WqyUNf9IB?usp=sharing

## Importing Images as Inputs

Navigate to "Coral Area Generator Folder/Images" and here you will see three folders, called objective 1, 2, and 3. If you are coral researchers from the University of North Carolina Wilmington and were the ones that colaborated with Dr. Chen, use the three objective settings you used, with the objective with most zoom matching up with folder "objective 1" and so on. Sort your images and put them into the matching objective folders. For reference, the conversion ratios of the objective folders respectively are 2.1333333333333337, 3.2801715874233124, 6.8547175480769198. 

## Importing Images to Find Conversion Ratios

If you use the application "cellSens" and have any traced images, navigate to "Coral Area Generator Folder/Images/Conversion Finders" and place the images you would like to use as references for conversion ratios here. In the notebook, run the "Install Dependencies and Libraries" section and then the "Find Conversion Ratios of Similar Images" section to get the conversion ratios. it will output in a format like:

_20220910_25_1_measure.tif\
Physical Size X: 2.1333333333333337 Âµm\
Physical Size Y: 2.1333333333333333 Âµm

Use either Physical Size X or Physical Size Y as your conversion ratio, and then change or add a value in "objective_conversions" in the "Find Conversion Ratios of Similar Images" section. Just make sure that if you use your own folder, match it up with the same index location and replace or add a directory name in the "folder_read_paths" list in the "Run Area Generator" section.

## Running the code

Simply run all the kernels and the code will output your inputted images with a blue mask in the "Coral Area Generator Folder/Code Output" folder with a excel sheet with all the areas in Âµm^2 and related file name. If you have any issues, email me at richardszhao@gmail.com and I will reach out to you ASAP.

