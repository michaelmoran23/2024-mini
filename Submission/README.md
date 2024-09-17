Wenhao Cao and Michael Moran

EC463 Mini Project

Boston University 




Exercise 1: 

In the light environment, the value detected is about 31000; in the dark environment, the value detected is about 52000.

According to the duty_cycle equation, as duty_cycle is small than the light will off, therefore the vaule of duty_cycle should be close to 0 if clip(0/any number), which the min_bright should be the value detected in the dark_environment. Since we have the min_bright and we want the duty_cycle close to 1, then it's clip(-1/-1), therefore we have the max_bright 

Exercise 2: 

We decided to play a part of the song 'Happy Birthday'. 


Exercise 3: 
First thing is to test the game, which is simpel.
Seoncd thing is to let the raspberry pi connected to wifi.
Third thing is find a cloud service platform. I chosen Google Sheet functioned by Google script at the beginning, and We are sure that the wifi-function is good (by urequest of google.com); We are sure the Google Script is controlling the Google Sheet (by writing something into the sheet directly) as well. However, we failed to connect the raspberry pi pico to the Google Script (it should be easy since it only adds the url into the code). 
In the end, we chage the platform (Thingspesk from Matlab) and all work fine.
