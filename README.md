# Bass-treble-and-volume-control-audio-preamp-circuit
To control Bass, treble and volume of sound signal before giving it to power amplifier, we have to modify the overall frequency response. Also we did not need any external voltage to operate this.
More info on my hackster page, visit from here: https://www.hackster.io/sainisagar7294/bass-treble-and-volume-control-audio-preamp-circuit-73bd1e
Watch video from here: https://www.youtube.com/watch?v=AZhVRB6vmug&feature=emb_imp_woyt

Hello everyone, good to see you back here. Today in this tutorial we are going to make a preamp circuit without using any kind of transistor or ic. This preamplifier circuit will able to control and adjust Bass, Treble and volume manually.
In this tutorial we are making two preamplifier (Bass, treble and volume control) circuits.I will demonstrate you how both the circuits and different from each other. In the section a Youtube video is embedded so that we can easily compare both the circuits.
Preamplifier:

caption (optional)
This is a complex circuit which is used to modify the sound signal before giving it to main power amplifier. Because sound signal consists a lot of up-down frequency curves. For Bass we need low frequency signal instead of high, so high frequency is cut-off by the circuit. Similarly in treble we need high frequency for better response. That’s why we are designing a preamp to make the overall signal (bass-treble and volume) adjustable.

caption (optional)
This is the prototype PCB for the same circuit.
Circuit components:
For mono-amplifier board:
4pcs 100nf polyester film capacitor
2pcs 1k 0.25-ohm resistor
3pcs potentiometers (signal channel)
For stereo-amplifier board:
8pcs 100nf polyester film capacitor
4pcs 1k 0.25-ohm resistor
3pcs potentiometers (stereo-double channel)
Circuit diagram:

caption (optional)
Download all files regarding this project.
Gerber files:

caption (optional)
Downlaod all files from here.
Circuit description:
Here we are using three potentiometers (two of 100k and one of 50k). by 100k potentiometers we can adjust Bass and Treble. Volume level can be controlled using 50k potentiometer. In this circuit we will only use passive components that’s why project become much simpler.
Polyester film 100nF capacitors and 1kohm 0.25 watts resistors are used in this circuit. We can choose some close values to them.
To make this circuit compatible to stereo amplifier we have to use stereo double potentiometers and all the components are doubled then.
Result:
After reviewing this circuit and making some noise with this, everything is going fine but passive components are not able to cut the frequency curve as desired so I changed my mind and then go for prototype PCB.
*The above circuit is very good and will be work fine, for more follow the next circuit.
For that I discover some circuits on internet then make the schematics accordingly. This time we sent our files to JLCPCB to get best prototype board.
Gerber files:
Download all the files from here.

caption (optional)


caption (optional)
Circuit components:
Potentiometer (100k, 50k)
Capacitors (4.7uf, 220uf)
Bc548 transistor
Resistors (150k, 100k, 47k, 10k, 6.8k, 1k)
Polyester film capacitors (220pf, 100nf, 47nf)
Screw terminal
Circuit description:
this is a stereo preamplifier circuit and through this we can control bass, treble and volume of the sound signal in a very professional way. This circuit has good frequency response. All the components used here are easily available in online or offline market. This circuit basically follows the same phenomena as above one but one step modified. To power up the transistor circuit we have to supply +12 volt to this circuit.
Result:
Overall sound control is good, there is no any type of humming. For more better response, we can use high quality capacitors and resistors.
For more circuits and detailed description follow us on Instagram page. This circuit can me modified more for best results till then stay tuned with us.
PCB designs and making:
We can make pcb at home or we can use breadboard to develop this circuit but for better performance and simplicity we made a circuit using EasyEDA and then order the PCB from JLCPCB

caption (optional)
I made some changes in the PCB circuit, originally it was made by electro India so all credit goes to him.
Video:

caption (optional)
This is video information about this project. This video has all information regarding soldering and components placing. Watch this video to listen speaker sound and bass.
JLCPCB:
I have my own Arduino boards because of JLCPCB to program them/troubleshoot them and learn from them. If you want to make your own board, the JLCPCB SMT service can be the solution.

caption (optional)
JLCPCB is the one of the most popular PCB makers. Price is just $2 for 2, 4 and 6 layer PCB. They just launched new purple solder mask, aluminum Pcb and 3d printing service in very low cost. Pcb quality is not compromised at any cost. Check them out right now from Here.

caption (optional)
JLCPCB Is also providing new user coupons and sign-up rewards of up to $30. So, check them out from here. Register using this link to get Free PCB assembly service coupons. Get your 2 layer to 6-layer PCB’s just in $2, stencil and PCB assembly service in just $7.
For PC: https://jlcpcb.com/SSR For mobile phone: http://m.jlcpcb.com/ssi
Here are some exciting projects, which you may like:
Here are some exciting projects, which you may like:
1) How to make Arduino Uno clone board.    
2) How to program Arduino Using Smart Phone.
3) Arduino Nano clone board problems and solutions.
4) How to make Inductance Meter Using Arduino.
5) Raspberry Pi- PICO Oscilloscope.

caption (optional)
Think you enjoyed my work, stay tuned. Follow us on Instagram (sagar_saini_7294) and hackaday.
please support us- No donations, just follow and leave a comment.
