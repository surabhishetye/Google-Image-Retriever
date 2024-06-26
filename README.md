# Google-Image-Retriever
Scrap Google search images using Python3-Selenium and download to your system. You need to provide a search query and number of images to be downloaded to the script.


## Dependencies

1. **Install Selenium Python**  
   pip install selenium
   
2. **Gecko driver** for **Firefox** or **Chrome driver** for **Chrome** browser.  
   Download geckodriver.exe from https://github.com/mozilla/geckodriver/releases or chromedriver.exe from                                 https://chromedriver.chromium.org/downloads  
   Need to have gecko driver (or Chrome driver) in the same directory as the python script.
   Incase of chrome driver, the script will need to be run with Chrome browser (by using driver = webdriver.Chrome() on line 20).

## Running the Python script

python google_image_retriever.py "<search_query>" <number_of_images> <is_thumbnail>
   
if <is_thumbnail> is set to 0 (or False), it will try downloading the full image. If it is set to 1 (or True), then it will try downloading the thumbnails.

## Disclaimer

The copyrights for the images are owned by the respective websites or users creating the image. The images downloaded should be for educational purposes only.
