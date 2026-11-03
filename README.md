# WindowServer2022Setup
This is an quick installation guide of Window Server 2022 using Window 10 OS.

#Requirement: 

1. Virtual Box->https://www.virtualbox.org/wiki/Downloads
2. Window Server 2022 ISO->https://www.microsoft.com/en-us/evalcenter/download-windows-server-2022

#StepByStep

Step 1: Install the hypervisor Virtual Box onto your PC. Once you install, you should see this screen. Click on the icon "New".
 ![img alt](https://github.com/ChangITTech/WindowServer2022Setup/blob/0a3b91c81d4573120d15256fc030f904d8918e52/image/part1.PNG)


Step 2:One you click on "New". These options will be available to customize. For VM Name: I had it ChangServer, you can give any name you want. For the ISO image option, make sure to select the Window Server 2022 ISO, downloaded from above. Finally, uncheck the "Proceed with Unattended Installation", and click "Next" to go to the next page.

Step 3: On this page, we are going to allocate resource from our current PC to the Window Server 2022 VM we are making. It is recommend to allocate "4Gb" of RAM, Base Memory. It is also recommend to allocate 2 CPU. As for size, we are going to allocate 50Gb of storage.

Step 4: Once, you're down with VM allocation. You Virtual Box Manager should look something like this. From here, we should run the Window server 2022 VM we just made.

