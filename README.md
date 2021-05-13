# Include-for-LVDOWin-in-Linux
Include for LVDOWin in Linux

Place the Include folder in the LVDOWin folder

https://github.com/Skylion007/LVDOWin

LVDO (pronounced as ludou) is a video steganography implementation by StarBrilliant using DCT coefficients.

It is used to encode files or data into video files.

We can put files on Youtube, VHS or even 8mm tape.

But LVDOWin is not compatible with linux.

Follow this tutorial:

First, install the dependencies: 

sudo apt-get install build-essential git cmake libqt4-dev libphonon-dev python2.7-dev libxml2-dev libxslt1-dev libqtwebkit-dev

Then, download PySide:

https://files.pythonhosted.org/packages/36/ac/ca31db6f2225844d37a41b10615c3d371587677efd074db29855e7035de6/PySide-1.2.4.tar.gz

pip install PySide does not work with Python3.

It must be installed manually:

Unzip PySide-1.2.4.tar.gz.

cd PySide-1.2.4

sudo python2 setup.py install (It takes about two hours)

cd ..

Then, download LVDOWin:

git clone https://github.com/Skylion007/LVDOWin.git

Delete the Include folder.

Then, download this repositories:

git clone https://github.com/Benji07p/Include-for-LVDOWin-in-Linux.git

Unzip Include.zip

Copy the Include folder on the LVDOWin folder.

cd LVDOWin/src

make

cd ..

The Include folder in this Github is useless but I put it in case ...
