# PCB Design Workshop

## Perfboard prototyping
For our [dreadnought proyect](https://github.com/forge-world-6798/Mecatronica-Proyecto) I have been trusted to take care of the hardware, as that is my strong suit. The required elements to wire together are 4xServos, and an ESP32CAM.

To power it all I went with a 9V battery with 2 resistors to drop the voltage to 5V, following this diagram.

[Drop Down](1-DropDown.png)

Unfortunately, after testing everything in a standard breadboard, we see that this configuration does not provide enough amperage and consistent voltage to power the components, so we went with a phone battery to power the system.

[Breadboard](2-Breadboard.png)

Then finally solder it all to a perfboard.

[Perfboard](3-Perfboard.png)

We use quick-connect connectors to avoid soldering the ESP and the servos directly, this allows us to replace them in case they go bad, or to reuse them for other proyects.

## Silicon prototyping
Now, in case we had to mass produce our components, we could make the perfboard design in a silicon wafer.

[Gerber](4-Gerber.png)

Thanks to the precise machining and help from a pick and place machine our board ends up smaller and sturdier compared to our perfboard prototype.
If it was required, using these gerber files we could place an order on any PCB fullfilment websites.

[Quote](5-Quote.png)

In the end, we decided that for our proyect this was unnecesary.

