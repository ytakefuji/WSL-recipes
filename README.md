# WSL-recipes

WSL stands for Windows Subsystem for Linux.

When installing Ubuntu on Windows using Microsoft Store, 
you can run Linux commands.

When installing Python3.x on WSL, your Python program using miniconda is 
at /home/your_name/miniconda3/bin/python.

Since WSL did not fully implement USB device drivers, 
the USB device including camera cannot be used on WSL.

However, you can run the USB camera on WSL!

You can run the executable Python on Windows 10 from WSL.

To use the Windows's Python, .profile or .bashrc should have the following:

alias wpython='/mnt/c/cygwin/home/your_name/miniconda3/python.exe'

$ source .profile or .bashrc

$ wpython camera_application.py

