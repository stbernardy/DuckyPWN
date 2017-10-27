# DuckyPWN

                                                                                                                       
    ____  __  __________ ____  ______ _       ___   __
   / __ \/ / / / ____/ //_/\ \/ / __ \ |     / / | / /
  / / / / / / / /   / ,<    \  / /_/ / | /| / /  |/ / 
 / /_/ / /_/ / /___/ /| |   / / ____/| |/ |/ / /|  /  
/_____/\____/\____/_/ |_|  /_/_/     |__/|__/_/ |_/   
                                                      
                                                                                                               
This payload will allow an attacker to reset a users password from the USB Rubber Ducky. For Windows, you will need to insert the username of the victim into the file. For Linux, it changes the root password.... if that account is not disabled.

Using Duckyencoder:

Run this command in your terminal (Mac or Linux). Usually the path is /media/sda1 or /media/sda2 


java -jar duckencoder.jar -i FILENAME.txt -o /PATH/TO/SD/CARD