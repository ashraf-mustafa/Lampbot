# Lampbot project

   This is part of a lamp robots (LAMPBOT) in our fourth semester in second year, working with a group of students from the second year of The internet of things and third year of Electronics engineering, the purpose of the project is to make a group of lamp robots able to interact with people in many ways such as detecting and tracking faces, recognizing the emotions of the person in front of them and respond by  changing the shape of their eyes, moving and rotating according to the person's face location and turning towards the direction where the voice come from as well

   My job in this project was to work on the real-time emotion recognition and send the data (integer numbers) to the team working on the lamp robot's eyes via RoboRealm software where it is then converted to specific emotional shapes according to the emotion recognized on the person's face
  
   The software was created by Octavia Arriaga, Paul G.Ploger and Matias Valdenegro using the convolutional neural network (CNN) and the FER-2013 emotion dataset which contains more than 35.000 grayscale images where each image belongs to one of the following classes (angry, disgust, fear, happy, sad, surprise and natural) and the code is released under an open-source licence. I used only five emotions (happy, sad, angry, surprised and neutral) 
  
  The code is in python language and  in order to send the data to the LED's that form different shapes, I had to edit the code so that the software becomes a server to send the data in sockets via RoboRealm by creating a variable that interacts with other features of the Lamp like the face detection and the voice direction detection that work in harmony to get the desired outcome.
  Each emotion is sent to the LEDs as an integer number to the LEDs (0 for neutral, 1 for angry, 2 for sad, 4 for happy and 5 for surprised) to be then translated to different LED shapes 

  The project was published on the siliconrepublic.com on the 26th of June 2019 (https://www.siliconrepublic.com/machines/lampbot-wit-home-robot-assistant)


![Alt text](https://github.com/ashraf-mustafa/Lampbot/blob/master/siliconrep.png?raw=true)

![Alt text](https://github.com/ashraf-mustafa/Lampbot/blob/master/lampbot.jpg?raw=true)



