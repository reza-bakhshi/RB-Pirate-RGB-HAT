<div align="center">

# RB-Pirate RGB & Button HAT

**Optional RGB lighting and physical-button expansion for RB-Pirate**

[![RGB LEDs: 16× SK6812](https://img.shields.io/badge/RGB%20LEDs-16%C3%97%20SK6812-c51a4a?style=flat-square)](#hardware-features)
[![PCB: 2 layers](https://img.shields.io/badge/PCB-2%20layers-2f855a?style=flat-square)](#hardware-features)
[![Designed with KiCad 10](https://img.shields.io/badge/KiCad-10-314cb0?style=flat-square)](https://www.kicad.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-f5c518?style=flat-square)](LICENSE)

</div>

RB-Pirate RGB & Button HAT adds programmable RGB visual feedback and a physical
user button to the [RB-Pirate](https://github.com/reza-bakhshi/RB-Pirate)
hardware debugging tool. It enables status lighting, animations, button-based
mode control, and scriptable user input through the RB-Pirate firmware.

The HAT is completely optional. RB-Pirate remains fully functional without it,
so the expansion can be installed only when visual feedback or a physical
button is useful.

## PCB gallery

<table>
  <tr>
    <th width="50%">Top</th>
    <th width="50%">Bottom</th>
  </tr>
  <tr>
    <td><img src="img/top.png" alt="Top side of the RB-Pirate RGB and Button HAT"></td>
    <td><img src="img/bottom.png" alt="Bottom side of the RB-Pirate RGB and Button HAT"></td>
  </tr>
</table>

## Hardware features

- 16 individually addressable SK6812 RGB LEDs arranged around the board
- Side-facing LEDs for perimeter lighting and visual effects
- One 100 nF local decoupling capacitor for each RGB LED
- Large central momentary push button
- Dedicated RGB data and button signals
- Compact four-pin, 2.54 mm SMD connection to RB-Pirate
- Four mounting holes for mechanical alignment
- Two-layer, 1.6 mm PCB
- KiCad 10 schematic and PCB design files

## Firmware features

When used with the
[custom RB-Pirate firmware](https://github.com/reza-bakhshi/RB-Pirate-Firmware),
the HAT provides:

- RGB status indication
- Startup and activity animations
- Introduction and party-mode effects
- Physical escape and mode-control input
- Scriptable button input for automation and custom workflows

## Connector pinout

The HAT connects to RB-Pirate through connector **J1**.

| Pin | Signal | Description |
|:---:|---|---|
| 1 | RGB_IN | Serial data input for the SK6812 LED chain |
| 2 | BUTTON | User-button signal to RB-Pirate |
| 3 | VDD / VUSB | Power input for the HAT |
| 4 | GND | Ground |

> [!NOTE]
> Power off RB-Pirate before installing or removing the HAT. Check connector
> orientation and pin alignment before applying power.

## Related projects

- [RB-Pirate hardware](https://github.com/reza-bakhshi/RB-Pirate)
- [RB-Pirate firmware](https://github.com/reza-bakhshi/RB-Pirate-Firmware)

## License

This project is released under the [MIT License](LICENSE).

Third-party symbols, footprints, models, and other bundled resources remain
subject to their respective licenses.

---

<div align="center">
  <sub>Optional light and button control for the RB-Pirate ecosystem.</sub>
</div>
