# fix-pip-arch-python
A simple.py file to fix pip on arch when it doesnt work ( you have to remove python-pip on arch to make the file work)

sudo pacman -R python-pip
curl -O https://raw.github.com/pypa/pip/master/contrib/get-pip.py
sudo python get-pip.py

i have the py file on releases if the link provided doesn't work
