# PeleeNet_SSD for the ncnn framework
![output image]( https://qengineering.eu/images/PeleeNet_Mumbai.jpg )<br/>
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
$ wget https://github.com/Qengineering/PeleeNet_SSD/archive/refs/heads/master.zip <br/>
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
Run Pelee.cpb with Code::Blocks. More info or<br/> 
if you want to connect a camera to the app, follow the instructions at [Hands-On](https://qengineering.eu/deep-learning-examples-on-raspberry-32-64-os.html#HandsOn).

------------

[![paypal](https://qengineering.eu/images/TipJarSmall4.png)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CPZTM5BB3FCYL) 
