# Trugbild
A FPGA working in serial with HDMI, for some real live video modifications. I'm making it to prove myself, that I can route highspeed PCB and to learn to code FPGA better.

## Features

- Xilinx Spartan 3 XC3S50A
- 2MB Flash memory
- 32MB DRAM memory
- Possibility to power device only from HDMI or from external input

## PCB screenshots
|![](/Images/top.png)|![](/Images/bottom.png)|
|---|---|
## Why "Trugbild"
It is because Trugbild is a german word meaning _illusion_. So I think that is a good name for device which can modify what you see :)

## Develop steps
- [x] Make PCB

- [x] Order PCB fabrication
- [ ] Order elements
- [ ] Solder everything
- [ ] First run
- [ ] Try to run device only with power from HDMI (max. 50mA@5V)
- [ ] Make and test if device can transmit HDMI at Full HD
- [ ] Make some video modification while transmitting
- [ ] Try to add some kind of neuron network to face recognition
- [ ] Try to cover detected faces with some picture or someone face :)
## Comments
### Make PCB
This point took me many hours of designing because this is my first design with FPGA, so I had pretty much to learn. I'm still not sure if everything was routed least good, but I will find it out soon.
### Order PCB fabrication
For this, I used JLCPCB. They have 3.5mils clearance and track width, 0.2mm holes minimum, and four layers just for 8$. That's incredible!
But after uploading gerber files, it comes that they don't have 3.5mils clearance, but 0.09mm (3.543mils), so I must re-route some nets on PCB :( The 5 PCBs cost me total of $15.89 with delivery included.
