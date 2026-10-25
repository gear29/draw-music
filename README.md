# draw-music
The music drawing device
This will hold a pcb that will have two sider one that controls volume and one that controls frequency making it so that when connected at 90 deg they can act like a coordinate system making it so when you slide them to find a coordinate on the grid it will emulate a sound. The pcb will be held in a 3d printed case so it can also hold paper and have the 2 sliders connected where a pen can rest so when you draw on the paper it makes music. IT will not need any computing power since the pcb dose all the procesing for the sound manuly and makes it just by using a vco (voltage controled oscillator) and a volume module making it so it can make the sound with almost no hesitation.

BOM
"Reference","Qty","Value","DNP","Exclude from BOM","Exclude from Board","Footprint","Datasheet"
"10nf1,10nF3,220µF1","3","C","","","","Capacitor_SMD:CP_Elec_3x5.3","~"
"10nf2,10nf4","2","R_Potentiometer","","","","Potentiometer_THT:Potentiometer_Bourns_PTA6043_Single_Slide","~"
"10nF5","1","Timeing cap","","","","Capacitor_SMD:CP_Elec_3x5.3","~"
"LS1","1","Speaker","","","","Buzzer_Beeper:Speaker_CUI_CMR-1206S-67","~"
"R1","1","R","","","","Resistor_SMD:R_0201_0603Metric","~"
"U1","1","LM555xM","","","","Package_SO:SOIC-8_3.9x4.9mm_P1.27mm","http://www.ti.com/lit/ds/symlink/lm555.pdf"
"U2","1","volume incres","","","","Package_DIP:DIP-8_W7.62mm","http://www.ti.com/lit/ds/symlink/lm386.pdf"


<img width="726" height="578" alt="image" src="https://github.com/user-attachments/assets/d2d1bc68-63b5-4323-bb7e-7447f1ce2636" />
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/8d5d6e65-e098-4bc6-a26c-85adc383113a" />
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/45fbc859-12bc-44fd-b6d1-83213eadef72" />
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/cef1bd0e-d047-4dc2-8440-1cb37c86ea06" />

