https://www.pyimagesearch.com/2015/06/15/install-opencv-3-0-and-python-2-7-on-osx/
https://www.pyimagesearch.com/2016/12/19/install-opencv-3-on-macos-with-homebrew-the-easy-way/
brew update
brew install python

pip install virtualenv virtualenvwrapper

source virtualenvwrapper.sh
mkvirtualenv env

pip install numpy

# cmake utility
brew install cmake pkg-config

# image IO
brew install jpeg libpng libtiff openexr

# opencv helper
brew install eigen tbb

# install opencv-python
pip install opencv-python

python
import cv2
cv2.__version__

