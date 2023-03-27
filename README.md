# Gesture_Gaming
play games using your camera. this program detects hand gestures and control the game accordingly.

Requirements :
Opencv
- ( you have to install opencv into your computer )
mediapipe
- pip install mediapipe
pyautogui
- pip install PyAutoGUI

you can play any games which have basic control systems. Here in the demo i have used hillclimb racing and code provided in gestures.py is also optimized for hillclimb racing.
if you want to run any other game then you have to change the logic a little bit.

i have used mediapipe which is able to detect the hand and provide the features extraced from the camera.
![landmarks](https://user-images.githubusercontent.com/86142546/227910077-e5f834c8-e786-401d-91b5-0187f1234233.png)

as you can see from above image media pipe can extract 21 fingers , joints and hand locations.

after getting the locations for the joints i have used pyautogui which can give keyboard commands to the os while the programe is runnig. I have implemented the loic that if the palm is open
then the program is going to simulate pressing right arrow-key which is used for GAS control in the game and when the palm is closed it gives left arrow-key command.

this way you can play any games by modifying the code little bit and setting-up your own commands.

![demo](https://user-images.githubusercontent.com/86142546/227912835-8d88b991-07af-44da-bdec-098369ba54dd.jpeg)


