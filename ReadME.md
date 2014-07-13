Warning
=======

As with all my projects, this is a Work In Progress
Again this is a Work In Progress!  

There are no warranties or Guarantees of any type that these hardware designs are usable for anything. But I hope they are. 

Teensy 3.1
===
If you have been following along at all on the Lynxmotion or Trossen Forums, you probably noticed that I am having a lot of fun with the Teensy 3.1 processors.  For those who don't know anything about the Teensy, you should look up at: http://www.pjrc.com/teensy/index.html

You can also purchase these at some other places including:
https://www.sparkfun.com/products/12646
http://store.oshpark.com/products/teensy-3-1

Breakout Boards
===
I have been having some fun using DipTrace to design some logical break out boards for the Teensy.  There is lots of stuff talking about these boards up on Lynxmotion

These boards are described and talked about on several forum threads including:
http://www.lynxmotion.net/viewtopic.php?f=26&t=9119

http://forums.trossenrobotics.com/showthread.php?6632-PhantomX-using-a-Teensy-3-1

Fabrication
---

The zip files that I have included in this project are sufficient to send off to at least a few different places.  The ones I have used for this are OSHPark and Seeedstudio.  You simply have to start the order process and upload the zip files...

OSHPARK - http://www.oshpark.com/

Once you enter this site, there is a button "Get Started Now" - The next page has a button, "Select a file on your computer", which will bring up a file upload dialog, where you can then upload one of these zip files.  Example: TeensyDuinoSimpleV0001.zip, it will then ask you for a project name, description and email address.  Once you enter these you will see the button changes to Processing File... 

It should then show you pictures of what the board should look like... and lead you to the point of ordering. 


SeeedStudio - http://www.seeedstudio.com/service/index.php?r=site/pcbService

Brings up a page, I normally choose:
PCB Qty: 5
PCB Layer: 2
PCB Thickness: 1.6mm
PCB Dimension 10cm Max*10cm Max
PCB Color: Green
Surface Finish: Hasl

You then hit the next button, which will bring you to the next page, where you can hit the browse button to select a zip file to upload.  You an use the zip file I mentioned under oshpark here as well.  The only difference in the zip file is the name of the Drill file, so I duplicated that file with both names in the zip files.





Teensy Shield with XBee
---

This board was designed to be the same size as several of the boards I have used over the years from Lynxmotion and Basic Micro.  In particular they are 3" by 2.3" and have mounting holes that are .15" in from the corners. 

The boards are setup with 3 pin servo headers for many of the IO pins as well, there is connectors for Robotis Ax Servos, plus other stuff, such as XBee and Speaker.  

Teensy Shield with Arduino Headers
---

This breakout board is a bit larger, as some others were interested in having Arduino stackable headers, so I am currently playing around with a V.01 of this, which appears to be working. 

**Update**: I had some issues with the 3.3v circuit, where the Voltage Regulator appeared to be shorting out so we had more or less 5v on the 3.3v circuit.  Could fix by removing VR and simply jumpering from the 3.3v output of the Teensy.   So decided to make a V0.2 with more spacing between those pins, no vias under the VR, plus an easy way to not populate the 3.3v VR and instead use the power of the teensy.  

Teensy Shield with Arduino Headers Through Hole
---

For the fun of it, I hacked up the v0.2 above to only use through hole components as to make it easier to solder.  I ordered a set of these fabricated at Seeedstudio, will see how well they work.  

Again warning: WIP

Other Breakout Boards
---

There are some others who are developing much simpler breakout boards for the Teensy 3.1 that have Arduino headers and the like.  There is several threads talking about this including one on the Teensy forum:

http://forum.pjrc.com/threads/25620-Teensy-3-1-to-Arduno-Shield-DIY-Adaptor


Questions
===

Again this is a DIY project, If you have any questions or suggestions, it is probably easiest to discuss it up on the different forums: Lynxmotion, Trossen Robotics, PJRC.

Thanks