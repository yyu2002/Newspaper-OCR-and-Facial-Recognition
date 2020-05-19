# Newspaper-OCR-and-Facial-Recognition
In this project, we take a ZIP file of images and process them, using the zipfile, PIL, pytesseract, and cv2 libraries. The files in the ZIP file we provide are newspaper images. Throughout the project, we search through the images looking for the occurrences of keywords and faces using optical character recognition, facial detection, and image composition. E.g. if you search for "pizza" it will return a contact sheet of all of the faces which were located on the newspaper page which mentions "pizza".

Each page of the newspapers is saved as a single PNG image in a file called small_img.zip. These newspapers are in english, and contain a variety of stories, advertisements and images.

I run the code on a small zip files. 
## How to view notebooks without error 
Due to the large file size of the notebook, it's better to view the notebook at `https://nbviewer.jupyter.org/` at the specific link: https://nbviewer.jupyter.org/github/yyu2002/Newspaper-OCR-and-Facial-Recognition/blob/master/OCR_and_facial_recognition.ipynb

## Important Notes 
The Jupyter Notebook files are quite large (30 mb), and may take a minute to load and render. Once in a while, there's problems opening the Jupyter Notebook on github, but that's out of my control.

## To add repository for contributors
`git clone https://github.com/yyu2002/Newspaper-OCR-and-Facial-Recognition`

`git remote add origin https://github.com/yyu2002/Newspaper-OCR-and-Facial-Recognition`

`git remote -v`

`git pull/push`

