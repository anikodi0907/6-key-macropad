You will need the following items to build the macropad
|Item|Quantity|Remarks|
|----|--------|-------|
|PCB |1|[PCB files](https://github.com/Aniketh-Udupa/6-key-macropad/tree/main/pcb-hotswap)|
|hotswap sockets|6|Compatible with Kailh and Gateron|
|diodes |6|1n4148 smd or THT|
|switches |6|Only compatible with MX style|
|keycaps|6|Cherry profile is compatible as it has south facing switches|
|Arduino pro micro|1|Alternatives- [sparkfun type c pro micro](https://www.sparkfun.com/products/12640) or [Elite C](https://deskthority.net/wiki/Elite-C)
|case|1|[Case files](https://github.com/Aniketh-Udupa/6-key-macropad/tree/main/case%20files)|

## Assembly
1)solder the diodes 

![back pcb diodes](https://user-images.githubusercontent.com/78634764/183245428-2e7bca13-aea0-4349-8072-06b394196382.png)

2)Solder the hotswap sockets

![back pcb sockets](https://user-images.githubusercontent.com/78634764/183245534-1b613798-facf-4bea-ab6a-be91e8b2c38b.png)

3)Solder the Arduino pro micro with pins.
![back pcb arduino](https://user-images.githubusercontent.com/78634764/183245583-040150a9-0b4a-49fa-ab5b-43ad1bf00143.png)
## Fully built pcb should look like this.
![built pcb](https://user-images.githubusercontent.com/78634764/183245827-d04c1a70-9ccf-495f-947c-2b3ed15c7cf6.png)
<details><summary>.</summary>
<p>
soldering not the best ik
</p>
</details>

# Firmware
Flash the [firmware](https://github.com/Aniketh-Udupa/6-key-macropad/tree/main/firmware) (macropad.hex) onto the board with [QMK toolbox](https://github.com/qmk/qmk_toolbox)
After the firmware has been flashed, go to [VIA](https://usevia.app/#/) and upload SSMP.json from [here](https://github.com/Aniketh-Udupa/6-key-macropad/tree/main/firmware).

Here's a video how to do that.

https://user-images.githubusercontent.com/78634764/183246335-de27bba1-912b-4281-a112-b4ae3c2893b8.mp4


