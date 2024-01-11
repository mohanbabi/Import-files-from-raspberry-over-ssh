# Import-files-from-raspberry-over-ssh
note1: your raspberry and your computer should connected to same wifi.
note2: you should know what is your raspberry pi ip address.

steps to follow as bellow:
  1.open your cmd in your PC
  2.Type scp and space.
  3.Type your raspberry pi name along with @ symbol.  ex: pi@192.168.29.235:
  4.File name along with its directory. ex:/home/pi/how_do_drones_work/scripts/2.py heare i want to copy 2.py file so we need to give path also. 
  5. And Space
  6. Now we need to give where we need to copy directory in the PC.  Ex: C:/Users/PAVN/Desktop/Pythonprojects/rpifiles

  Now total command : scp pi@192.168.29.235:/home/pi/how_do_drones_work/scripts/2.py C:/Users/PAVN/Desktop/Pythonprojects/rpifiles
  7. press enter.
  8.next we need to enter raspberry pi password.
  9. if password is correct:
         your file is copyed
    else:
        you need to enter correct password.

scp 
pi@192.168.29.235:
/home/pi/how_do_drones_work/scripts/2.py
