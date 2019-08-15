# Class Minion

I have rearranged the Class Minion filesystem and scripts so we can more easily do version control and deploy software updates with relative ease.

In order to set up a new camera system -->

1: Go to https://www.raspberrypi.org/downloads/raspbian/ and write the filesystem to a blank uSD card.

2: Connect a RPi computer to ethernet, monitor, keyboard and mouse. Apply power and watch the boot sequence.

3: Follow the default raspbian install wizard (The only setting retained here is your password of choice)

4: After the Pi reboots, open a terminal and execute ~ $ sudo git clone https://github.com/jacksonsugar/Class_Minion.git

5: Once you have my scripts $ sudo python Class_Minion/minion_install.py

6: Answer the questions and watch the computer reboot a couple times

7: Once the pi boots up, runs a filesystem check and takes a photo, it is properly configured for deployment

8: Clone the repository to your local machine as well and copy the Class_Minion_uC folder to your desktop

9: Open Arduino IDE and upload the Class_Minion_uC.ino script to the Nano

10: Connect the computer and micro-controller to the PCB

Done.
