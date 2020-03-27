# Prototyping-Interactive-Systems--Smart-Toothbrush
Arduino AccelerometerADXL345- code: 
GROUP PROJECT:
Our group, me (Ayushi Jain, ayushij2704@gmail.com), Chintan Puggalok(@chintan19239@iiitd.ac.in) and (Hari P. Nambiar(@hari19041@iiitd.ac.in))) had made a toothbrush which could detect the type of tooth being brushed depending on the orientation of the brush and instruct the user to brush accordingly, using different modes, to enable the most efficient brushing possible. 
Applications and tools used:

1. arduino nano
2. ADXL345
3. Bluetooth module HC-05
4. DC Motor
5. Two switches
6. Wix.com website builder to build website
7. To build an app:    
  
HOW IT WORKS: 

1. Detect orientation of the brush using accelerometer:  
  If the brush bristles are horizontal(as detected by accelerometer), it would mean that the user is nmost probable brushing incisors.     If the brush bristles are vertically downwards(as detected by accelerometer), it would mean that user is brushing lower molars. Else     if brush bristles are vertically upwards(as detected by accelerometer), it would mean that user is brushing top molars. Else if brush   bristles are diagonally facing, it implies that the user is most probably brushing canines. Other than this, we have made video and aa   website to demonstrate use of the toothbrush. 
2. Send information of the type of tooth being brushed to the app which, depending on the tooth detected guides the user how to brush the tooth efficiently 
3. Website to represent our product  
4. Video to explain our product in detail  
To run the toothbrush, you need an arsuino which is has power(supplied through battery).
Attached files:
1. The final code of arduino-accelerometer-bluetooth.
2. The video explaining the product
3. The link of website: https://chintan19239.wixsite.com/website
