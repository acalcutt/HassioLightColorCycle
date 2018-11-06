Please find below the various piece of code that together control my RGB light to loop in Rainbow.
Every two seconds, it change from one colour to another based on the value of the second.
So it compute 30 differents RGB value in a "circle", all with the same Saturation and Brightness both forced to 1.0
The transition from one colour to another is done in one seconds.

The name of my Tradfri RGB light bulb is "light.couleur"

A link to my video on Twitter:
https://twitter.com/DavidGlaude/status/1059596285991366657

Source code for the Hue based RGB computation from last post of this:
https://community.home-assistant.io/t/hue-random-color-autiomation-help/52122/10

PS: I am totally not a Home Assistant expert, so there might be better way to implement this.
    Fell free to comment or propose better way to control that.
    Such as verifying if the light is on (as a condition) before changing the RGB colour.
    Anything really, today I just want it to work, but I am ready to learn.