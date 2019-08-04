# AutoEnoder Conversion From RGB to GrayScale

If you are using Google Colabrotary then just Click on Colab link below:
	https://colab.research.google.com/drive/1VZPjeXDW4AYHF2OPHk9SljsOOmuq7Tox'


## For Python 3 and Above:
For installing necessary librarires, you just need to type following command in terminal or command prompt: <br />
	pip install --upgrade -r requirements.txt  <br />
				&ensp;	or         <br />
	pip3 install --upgrade -r requirements.txt 

## Download The Dataset just enter following commands in terminal or cmd:

## For Training Images
wget --no-check-certificate http://download.tensorflow.org/example_images/flower_photos.tgz \
	-O /Destination/flower_photos.zip
   
## For Testing Images
wget https://www.graphicsfuel.com/wp-content/uploads/2012/02/free-flower-photos.zip -O /Destination/flowers.zip


## For Making Directoires use in your console:
import os <br />
os.mkdir('./color_images') <br />
os.mkdir('./gray_images')  <br /> 
os.mkdir('./test_images')  <br />
os.mkdir('./gen_gray_img') 
