This code is built on a softcore processor on a Altera DE2 board running a Cyclone 2 FPGA. 

The code of interest is the GPS.C located in the Software/gps/ directory.
This code takes a raw GPS input and parses it for display on an LCD screen, and various LEDs.
It is capable of displaying the following:
  - Latitude
  - Longitude
  - Elevation (converted to Feet)
  - Time (converted to mountain time)
  - Satellite ID numbers (to identify the which sateillite the information is based on)
