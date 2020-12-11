# Linux_minit_black_screen_fix_nvidia_20
Install Nvidia proprietary drivers in LinuxMint 20 cinnamon


## if your having problem after fresh installing linux Mint
# for those have Nvidian graphic drive they will face this problem 

Step 1:

you pressed CTRL+ALT+F1 (at the same time)? That should have taken you to a text terminal, 
where you logged in, and stopped mdm?

so you have integrated graphics as well as an nvidia card that you're trying to update the drivers.




Step 2:

$ sudo ubuntu-drivers autoinstall  ## Alternatively
$ sudo apt install nvidia-driver-(__model number___)  // example: sudo apt install nvidia-driver-1050ti
$ sudo reboot



if this doesnt work try this 

$ sudo service mdm stop
$ sudo sh N-334.21.run
$ sudo service mdm start
