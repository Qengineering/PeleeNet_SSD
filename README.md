# PelleeNet_SSD for the ncnn framework
Papers <br/>
https://arxiv.org/pdf/1804.06882.pdf <br/>
Training set: VOC2007 <br/>
Size: 304x304 <br/>
Prediction time: 300 mSec (RPi 4) <br/>
<br/>
Special made for a bare Raspberry Pi see: https://qengineering.eu/opencv-c-examples-on-raspberry-pi.html <br/>
<br/>
To extract and run the network in Code::Blocks <br/>
$ mkdir *MyDir* <br/>
$ cd *MyDir* <br/>
$ wget https://github.com/Qengineering/PelleeNet_SSD/archive/master.zip <br/>
$ unzip -j master.zip <br/>
Remove master.zip and README.md as they are no longer needed. <br/> 
$ rm master.zip <br/>
$ rm README.md <br/> <br/>
Your *MyDir* folder must now look like this: <br/> 
mumbai.jpg <br/>
pelee.bin <br/>
pelee.param <br/>
Pelee.cpb <br/>
peleenetssd_seg.cpp <br/>
 <br/>
Run Pelee.cpb with Code::Blocks. Remember, you also need a working OpenCV 4 on your Raspberry. <br/>

![output image]( https://qengineering.eu/images/PeleeNet_Mumbai.jpg )

