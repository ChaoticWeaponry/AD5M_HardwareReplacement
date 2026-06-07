# Mainboard Section  

**Document of Schematics/Installation/Configuration** [BTT Wiki](https://global.bttwiki.com/M8P-V2_0.html)  

Parts Required:  

-FPC 30p 1mm PCB (For adapting the AD5M bed ribbon to interface with the new mainboard) [From Amazon](https://a.co/d/09iN6a9x)  
-Mainboard Dependent - 3 Stepper Motor Drivers (I used TMC2240 with my Manta M8P v2) [From Amazon](https://a.co/d/0ccSFjxs)   
-A large external MOSFET for the bed heater [From Amazon](https://a.co/d/080Fl4P3)  
-A slim 140mm fan [From Amazon](https://a.co/d/0aiYGzja)  

**MOSFET Section:**  
The Manta M8P and many other mainboard come with on-board MOSFETS to drive a bed heater. The M8P is rated to ~10 Amps, which is pretty much exactly the power rating of the stock AD5M bed heater (250w).  

I would *strongly* suggest that you include an external MOSFET like I listed above. It's stupid-overkill regarding power rating, but I would much rather err on the side of caution.  

Follow the pinouts of the respective external MOSFET that you purchase, they should be pretty self-explanatory. 2 terminals for main power in, 2 terminals for bed power out, 2 terminals for bed control (coming from the mainboard).  


**Bed Electrical Connection:**  
