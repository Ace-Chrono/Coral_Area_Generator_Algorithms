
# Running Coral Area Generator

Video Guide: https://youtu.be/jlRUm6rV9ZI

The Coral Area Generator utilizes YOLO V11 and the Segment Anything Model 2 (SAM 2) to automatically find the area of corals in an image. Make sure to download the "Coral Area Generator Folder" with its into your google drive so the code works flawlessly: https://drive.google.com/drive/folders/1I2PxS79XVj3VTLM-lKzeGh2WqyUNf9IB?usp=sharing. From here, you want to upload your TIFF images into the google drive folder, preferably in the folder marked "Coral Recruit Images", or you can use your own folder. Run all the code in the "Coral Area Generatot.ipynb", and follow the prompts that appear at the bottom of the page. This is where you can designate what annotations you want along with the output and input folder location if you used your own. The code will output your inputted images with a "_annotations.coco.json" file and a excel sheet with all the areas in Âµm^2 and related file names. If you have any issues, email me at richardszhao@gmail.com and I will reach out to you ASAP.

## Quality Control

Due to the nature of artificial intelligince there are likely to be images that are not up to your standards and maybe even a few misses. You can search through the outputted images and visually inspect the traces to see if they are up to par, and if not, you may be required to manually retrace them in an application like CellSens.

