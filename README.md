# Object-Detection

References: 
https://github.com/ari-dasci/OD-WeaponDetection
https://www.digikey.com/en/maker/projects/how-to-perform-object-detection-with-tensorflow-lite-on-raspberry-pi/b929e1519c7c43d5b2c6f89984883588
https://sci2s.ugr.es/weapons-detection#Public%20datasets

##### Instructions #####

Activate Virtual Enviroment

Install Dependencies:
libjpeg-dev 
libtiff5-dev 
libjasper-dev 
libpng12-dev 
libavcodec-dev 
libavformat-dev 
libswscale-dev 
libv4l-dev 
libxvidcore-dev 
libx264-dev
qt4-dev-tools 
libatlas-base-dev 
libhdf5-103 

Install OpenCV 4.1.0.25

Install Tensorflow Lite in virtual enviroment

###### Terminal Commands: ########

source tflite-env/bin/activate

sudo apt -y install libjpeg-dev libtiff5-dev libjasper-dev libpng12-dev libavcodec-dev libavformat-dev libswscale-dev libv4l-dev libxvidcore-dev libx264-dev

sudo apt -y install qt4-dev-tools libatlas-base-dev libhdf5-103 

python -m pip install opencv-contrib-python==4.1.0.25

python -m pip install <paste in .whl link>
  
