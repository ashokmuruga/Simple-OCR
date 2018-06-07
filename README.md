# Simple-OCR

Source: Learnopencv

The program behaves like a simple OCR.It scans a simple image and prints the text contents available in the image.

Install the following dependencies

sudo add-apt-repository ppa:alex-p/tesseract-ocr
sudo apt-get update
sudo apt install tesseract-ocr
sudo apt install libtesseract-dev
sudo pip install pytesseract

open a editor & copy the ocr_simple.py,Save it
Keep a scanned image in the same directory where ocr_simple.py is available

Run as
python ocr_simple.py image1.jpg 


For the regional languages,first update the system settings to install the regional fonts.Restart the system
AND
Install the fonts for tesseract using the following commands pertaining to malayalam,tamil,telugu and kannada fonts respectively.

sudo apt-get install tesseract-ocr-mal
sudo apt-get install tesseract-ocr-tam
sudo apt-get install tesseract-ocr-tel
sudo apt-get install tesseract-ocr-kan


