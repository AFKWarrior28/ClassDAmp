# ClassDAmp
Class-D Amplifier soldering and electronics exercise at the University of Waterloo, Department of Physics and Astronomy. Kits are available for free to members of the University of Waterloo community, including staff and faculty. All we ask for is a willingness to learn and explore the amazing world of electronics!

A class-D amplifier is a type of audio amplifier that works by turning an analog (continuous) audio signal into a digital (either on or off) signal, amplifying it, then converting it back into an analog signal for speakers to play. Essentially, it's what allows computers and phones to power large speakers. In this project, you will learn the basics of soldering and electronic components while building your very own amplifier-speaker combo!

In order to recieve a kit, you must complete the Science Resource Shop Orientation course (self-register on LEARN). Once that is complete, please email me at j6hao@uwaterloo.ca to arrange for a kit pickup.  


# Science Resource Shop
The [Science Resource Shop](https://uwaterloo.ca/science-technical-services/about-science-technical-services/science-resource-shop) is located in the room PHY135. Besides soldering, they offer a wide array of tools and machines such as lathes, mills, bandsaws, and 3D printers. I highly recommend exploring the various tools offered to create a unique housing for your speaker and PCB. A sample 3D design is included in this repository, and I encourage you to improve upon my design.

# Instructional Videos

[Here](https://youtube.com/playlist?list=PLA1I_6hQhSNaFf6GUz-gZa_wceobiq_6l&si=VTzpREcftJKnDZTa) is a playlist of instructional videos that I am making for this project. There is important info in the description of each video, so please watch them as needed and read carefully! It's my first time making videos like this, so please excuse the horrible production value :3 

UPDATE: More videos are still coming out! The original set of videos will be updated with voiceover versions as well to try and combat the sound issue. Should be available by the end of the week (16/01/26)


# PCB Design
All PCB design is conducted using the free software [KiCAD](https://www.kicad.org). All final design files for the PCB are included in this repository, and I encourage you to explore them and improve upon my design.


# Speaker Housing
The speaker boxes are designed to share the same back. The back can be mounted on the box using magnets, but the tolerances allow for a good friction fit. Included in the design are sockets for 4x 8-32 heat-set inserts for mounting the speaker and 3x 4-40 or M3 set screws for mounting the PCB. The 3 mounting holes on the PCB are sized for M3 but are also compatable with 4-40 fittings.

# Custom Development Area
The custom development area included on the ClassDAmp PCB is an area for you to explore and create. Before soldering components to the PCB, it is recommended that you test your circuit on a breadboard. After building on the custom development area, use an external power supply (not USB-C!) to check the functionality of your circuit to prevent any damage to your power supply in the event of a short circuit.  

The USB-C power supply is designed to be able to provide 5VDC with a maximum current draw of 3A. Always check the specification of your power supply and make sure it can supply the necessary current. If your circuit requires more power you will have to create your own power supply.

