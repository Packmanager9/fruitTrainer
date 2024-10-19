
This project uses pixel data lifted from images present in this directory, 
to test this project locally, you will need to run the wd382.html file in a browser such as chrome.

On mac you will need to run the following command in your terminal 

open -n -a "Google Chrome" --args --user-data-dir=/tmp/temp_chrome_user_data_dir http://localhost:3000/ --disable-web-security 

On windows run the following from within the directory of chrome

chrome.exe  --disable-site-isolation-trials --disable-web-security --user-data-dir="D:\temp"

These commands open an instance of chrome with disabled security, this allows the pixel data to be from a local origin. 

Once the wd382.html has loaded, it will access the image files when prompted and load them into the program. 


There are some hotkeys to operate the model, which are as follows:

Use Space to initiate training, this will take seevral seconds as the data is created from the images, but can be seen in the console as it counts to 9100 before it starts.

I forget the rest, check the code for the keysPressed object to see. 

