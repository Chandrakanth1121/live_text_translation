1)EAST(efficient and accurate scene text detection) is used to detect text from input image. (refer https://arxiv.org/abs/1704.03155)

2)Once the text is detected, it is cropped out of the input image.

3)The cropped text's quality is improved by a series of image processing tasks like grayscaling, thresholding and filtering.

4)The text is then fed into Google's OCR engine called tesseract. This step outputs the image text in string form

5)The output string is then fed into a english to hindi translator to obtain the hindi version of the image text.

6)This model can be implimented for a video where the user can point at an object and it shows the translated text in Hindi.


refer text_recognition.ipynb file for sample output
