#Low Noise Amplifier

I worked on the design at the Rosenstein Laboratory for Embedded Electronics, Brown University in Summer 2014  


The initial schematic capture was conducted in DxDesigner  
Stage 1 was low noise and low gain  
Stage 2 was medium noise, high gain  
A boost amplifier was also included to increase the GBW of the LNA 


The Printed Circuit Board (PCB) for the LNA was designed in PADS Layout   
The PCB consisted of 4 layers  
The top and bottom layer each had one LNA  
Plane 2 and Plane 3 were the power and ground planes respectively  
Components were connected to the planes with vias  
The top and bottom layer were identical expect for a vertical offset  
The offset was necessary because the input jacks for the amplifiers were through hole components  


Apart from the input jacks and the  motherboard connector, all other parts were surface mounts  
0603 Capacitors and Resisters and SOIC parts were soldered on the amplifier using a microscope  

The screenshots of the gerber files for each of the layers have been included in this repository as a pdf file  
Also included are the images of the top and bottom surfaces of the LNA's showing each of the two amplifiers  
