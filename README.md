# Download 
1. download xilab-1.17.10-x86_64.AppImage.tar.gz (from http://files.xisupport.com/Software.en.html)
2. download libximc-2.12.5-all.tar.gz (from http://files.xisupport.com/Software.en.html)

# Запустить xilab 
1. Если не видит контроллер, settings -> scan for local XIMC servirs, rescan
2. Open Axis 3 -> settings -> stepper motor set nominal current = 100 mA, Feedback = None
3. Check 

# Install packages
1. sudo apt install ./ximc-2.12.5/ximc/deb/libximc7_2.12.5-1_i386.deb
2. sudo apt install ./ximc-2.12.5/ximc/deb/libximc7-dev_2.12.5-1_i386.deb

# Run
python3 main.py


