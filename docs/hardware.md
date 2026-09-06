# Revision 1 hardware

[Back to the project](../README.md) · [Pinout](pinout.md) · [Photos](gallery.md)

The current build uses separate modules mounted and wired on a prototyping board. There is no custom PCB or enclosure release yet.

| Qty | Part | Identification / status |
| :--- | :--- | :--- |
| 1 | Adafruit KB2040 | Controller; confirmed by the builder and visible board markings |
| 1 | DFPlayer Mini | MP3 playback module; confirmed by the builder |
| 1 | I²C display | Four pins: GND, VCC, SCK, SDA; exact model and resolution unconfirmed |
| 4 | Momentary tactile buttons | D-pad: up, down, left, right |
| 1 | Adafruit mint-tin-sized Perma-Proto board | Visible board label; used as the Rev 1 base |
| 1 | Rechargeable LiPo battery | Power-assembly photo shows a MakerHawk pack labeled 3.7 V / 1000 mAh; final installed specification still to confirm |
| 1 | USB-C battery charger | Appears to be an Adafruit Micro-Lipo board; exact model unconfirmed |
| 1 | Adjustable DC-DC converter | Intended 5 V output; exact model and output measurement unconfirmed |
| 1 | On/off slide switch | Two terminals used in the supplied connection list |
| 1 | Stereo audio socket | Three audio nets: left, right, ground; exact socket and lug order unconfirmed |
| 1 | 1 kΩ resistor | In series between KB2040 TX and DFPlayer RX |
| 1 | microSD card | Music storage; installed capacity and file layout not documented |
| As needed | Hookup wire, solder, insulation | Hand-wired prototype assembly |

Extra switches and loose capacitors appear in early layout photos. They are not treated as confirmed installed components because their final assignments were not supplied.

## Power terminology

The original build notes say “buck converter.” For a 3.7 V single-cell battery and a 5 V output, the required conversion is step-up, so a boost or buck-boost converter is needed. The pictured module's identity should be confirmed before turning this parts list into a shopping list.

## Manufacturer references

- [KB2040 pin labels and power rails](https://learn.adafruit.com/adafruit-kb2040/pinouts)
- [DFPlayer Mini documentation](https://wiki.dfrobot.com/dfr0299)
- [Adafruit USB-C Micro-Lipo charger pinout](https://learn.adafruit.com/adafruit-microlipo-and-minilipo-battery-chargers/pinouts) — candidate charger identification only

The list records what is known from the build notes and photos. No battery-life, audio-quality, or power-consumption measurements have been published yet.
