# PCB Design Workshop

## Perfboard prototyping
For our Dreadnought proyect [ADD LINK] I have been trusted to take care of the hardware, as that is my speciality. The required elements to wire together are 4xServos, an ESP32CAM and a 9V battery with 2 resistors to drop the voltage to 5V.

The first task is to test everything in a standard breadboard.

[ADD IMAGE]

Then grow some gonads and solder it all to a perfboard.

[ADD IMAGE]

We use quick-connect connectors to avoid soldering the ESP and the servos directly, this allows us to replace them in case they go bad, or to reuse them for other proyects.

[ADD IMAGE]

## Silicon prototyping
Now, in case we had to mass produce our components, we could make the perfboard design in a silicon wafer.

[ADD IMAGE]

Thanks to the precise machining and help from a pick and place machine our board ends up smaller and sturdier compared to our perfboard prototype.
If it was required, using these gerber files we could place an order on any PCB fullfilment websites.

[ADD IMAGE]
