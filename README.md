# Vehicle-Number-Plate-Detection-OCR
This program will help you capture the vehicle number plate and reads it using OCR in real time using "haarcascade_russian_plate_number" and "tesseract-OCR" applications.

This application can detect the vehicle number plates, and draws a bounding rectangle on the output screen.
See some example images attached in the "Output View" folder to get an understanding.

When it detects a number plate, it captures only the number plate and it will save that image in the "Scanned" folder.
Please have a look on the attached pics in the "Scanned" folder.

Later it will read the captured number plate using "Tesseract-OCR" and saves the number plate and detected time in the "NumberPlate.csv" file.

Note: This application working fine in capturing number plates, but in reading the number plate using OCR it can perform best only on high resolution video.
