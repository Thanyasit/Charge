# Light Control With Color
<h2>Description</h2>
This code allows you to control a light using a photoresistor and a button, and also displays different colors on a NeoPixel strip based on the light level. The light is turned on and off using a relay, and the color of the NeoPixel strip is determined by the light level detected by the photoresistor.<br><b>2020</b>
<h2>Getting Started</h2>
To get started with this code, you will need the following components:<br><br>

- An Arduino board<br>
- A photoresistor<br>
- A 10k ohm resistor<br>
- A button<br>
- A relay<br>
- A NeoPixel strip<br>
- Jumper wires<br>
<h2>Installation</h2>
1. Connect the photoresistor to analog pin A0 on the Arduino board, and connect the 10k ohm resistor from the same pin to ground.<br>
2. Connect the button to digital pin 2 on the Arduino board, and use the internal pull-up resistor.<br>
3. Connect the relay to digital pin 6 on the Arduino board.<br>
4. Connect the NeoPixel strip to digital pin 8 on the Arduino board.<br>
5. Upload the code to the Arduino board using the Arduino IDE or any other IDE that supports the Arduino board.<br>
<h2>Usage</h2>
When you press the button, the light will turn on or off depending on its current state. The NeoPixel strip will display different colors based on the light level detected by the photoresistor. If the light level is high enough, the relay will turn on and the light will be on. If the light level is too low, the relay will turn off and the light will be off.

## Example

<p align="center">
<img src="https://user-images.githubusercontent.com/77733903/226977739-f93125a1-8c8d-43e4-bcfe-9a56961a4d63.jpg" width="500">
</p>

<h2>License</h2>

This code is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
