Components:
- IDC Sockets (x4): EHF-120-01-L-D - 1.27mm/.050in Shrouded Ejector Header IDC, 40 Pin, 2 Row, 10µin Gold/Tin, Through Hole (https://www.samtec.com/products/ehf-120-01-l-d)
- IDC Cables (x4): FFSD-20-D-24.00-01-N-SR - .050" Low Profile Tiger Eye™ IDC Ribbon Cable Assembly (https://www.samtec.com/products/ffsd-20-d-24.00-01-n-sr)
- Pogo pins (x121): P70-5000045R Individual SMT Spring Loaded Pogo Pin, 2.4mm high (https://www.harwin.com/products/P70-5000045R)
- 1-3 Piezo-composite 111x11 array of electrodes on one side with a 3.1mm pitch, 0.1mm kerf, 3mm element width, common GND electrode on other side, CuSN plated, see pdf (Smart Materials).
- Copper Tape
- Crocodile clip
- PCB 
- 3D Printed Lens (see below)

# How to 3D print a holographic acoustic lens
Using an stl. file with a resolution similar to that required to simulate the source can be challenging - for me fusion crashed a lot. So it is easier to only generate the surface and use that to slice a simpler model.

- Use the attached jupyter notebook to generate a stl. surface
- Open the lens_blank file in fusion
- Import the stl. into fusion
- Use the surface to slice through the blank
- 3D print
