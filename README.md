# CodeVisionAVR_Omibo_Control
This is a model prepared in CodeVisionAVR Software, the file is written in c program, then the file is converted to hex file.

This is used to control an Omibo_Bot to move Forward, Backward, Left and Right.
All you need to do is Open-Up CodeVisionAVR Software and then Create a new project, specify the Micro-Controller that you are using, In this case, I have used Atmega16A, Specify all the timer condition, if needed.

Also, in the options, you need to go in USart and select receiver there, this is becasue we will be using Bluetooth module to control the bot.

Once, this is completed, make the connections

After the connections, make a .C file which specifies the PORT which needs to be ON, by the command specified by User.

Here in this case, a-Forward
                   c-Backward
                   d-Left
                   e-Right
Then Compile the file, Then Built it and then Rebuilt it from the options on the title bar.

Once,this is done, You can Use SinaProg, It is a software used for the dumping of the code that has been creatred to hardware.

You need to install all the USBasp drivers for this.
Debug this, if you find any errors.
