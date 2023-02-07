# Holoscope_V2

This project is a second iteration of our research in a transmissive lensless holographic microscope intended for more genaric experimentation with configurations. 

Below is a raw capture and post processed image of Arthrospira using the Numerical Propagation plugin for Fiji using the designs in this repository: 

![Screen Shot 2023-01-10 at 11 25 53 AM](https://user-images.githubusercontent.com/77997125/217363907-5f61984c-c382-42eb-9a3a-6e0455476d61.png)


This system relies on 5 primary types of components: A light source and mounting (LED or Laser (Laser provide better resolution), a pinhole (from 15-250 microns OD), a CCD sensor (Smallest pixel pitch acheieveable), a method for hold a sample (Microscope slide/microfluidic channel), and the spacing bodies necessary to position and hold the parts together. 

This specific design uses the following components:
  - Light Source (409nm Laser Didoe) 
  - Thorlabs LDM21 Laser Diode Mount (https://www.thorlabs.com/thorproduct.cfm?partnumber=LDM21)
  - Thorlabs Laser Diode Controller (Not necessary for operation, any stable LD controller will work) (https://www.thorlabs.com/thorproduct.cfm?partnumber=LDC205C)
  - 15 micron mounted pinhole (https://www.thorlabs.com/thorproduct.cfm?partnumber=P15HK)
  - Arducam 8 MP Raspberry Pi Camera (Lens and IR Filter removed) (https://www.arducam.com/product/8mp-imx219-camera-module-for-raspberry-pi-b0394/)

Please note that the general nature of this typic of microscope is rather forgiving. Different applications can benefit from differing configurations, as such, this design incorporates spacers and mounts that try to genearlize as much as possible in the physical stackup so that people can experiment on their own! 

Below is a cross-sectional view of this design:

![MicrosoftTeams-image](https://user-images.githubusercontent.com/77997125/217364639-a8549a86-37c3-4963-8b40-3681e8fb6b38.png)
