# PCA9540BD big breakout board #
 
Schematics for a breakout board PCA9540BD component (http://www.nxp.com/documents/data_sheet/PCA9540B.pdf).

## About the PCA9540BD ##

The PCA9540BD is a 2-channel I2C-bus multiplexer.

Let's say that you want to get data from 2 components through I2C but they both have the same I2C address. The PCA9540BD allows you to redirect the SCA and SDA pins to (SCA0, SDA0) or (SCA1, SDA1).

## About this breakout board ##

The PCA9540BD pins have a pitch of 0.05 inches making the component difficult to connect to your arduino. This breakout board allows you to connect the PCA9540BD component to a classical prototype board.

<img src="http://sebastien.drouyer.com/images_for_projects_readme/PCA9540BD/big_breakout.png" />

All pins are conveniently labelled so that your circuit stays easily readable.

The schematics are under the GPLv3+ license.

## Library for arduino ##

I have implemented a driver for arduino allowing you to control the component. It is available in this [repository](https://github.com/sdrdis/PCA9540BD).

## About the author ##

[See the blog post about the project.](http://sebastien.drouyer.com/projects/pca9540bd-driver-for-arduino-breakout-boards-schematics.html)

Sebastien Drouyer - [website](http://sebastien.drouyer.com) - [twitter](https://twitter.com/sdrdis)
