A device for overriding / injecting EDID information into VGA/DVI/HDMI video
cables.

Based on the idea at
[vgaedidinjector](https://github.com/datenwolf/vgaedidinjector) but with a much
cheaper BOM. It shares no code or design elements with the original design
however.

Uses a Silicon Labs C8051F38x processor as;
 * Has two hardware I2C interfaces (input + output).
 * Has hardware USB subsystem.
 * Runs of 5V power with no external components.
 * Has internal oscillator.
 * I/O pins are 5V compatible.
 * Has good sdcc support.
 * Costs $1.83 USD in individual quantities.
 * Is hand solderable.

More info:
 * [Datasheet](http://www.silabs.com/Support%20Documents/TechnicalDocs/C8051F38x.pdf)
 * SiLab's part number: C8051F387-GQ
 * Digikey part Number: [336-2032-ND](http://www.digikey.com/product-detail/en/C8051F387-GQ/336-2032-ND/2601833)

# Other parts

## Connectors

 * HDMI connectors
  * **With** locking screw flange
   * `CONN RCPT HDMI W/FLANGE R/A SMD`
   * Manufacture part number: [FCI 10029449-002TLF]
   * Digikey part number: [609-1011-ND](http://www.digikey.com/product-search/en?KeyWords=609-1011-ND&WT.z_header=search_go)
   * [Datasheet](http://portal.fciconnect.com/Comergent//fci/drawing/10029449.pdf)
   * ![Product Image](http://media.digikey.com/photos/FCI%20Photos/10029449-002TLF.jpg)
   * Cost: $1.17 USD in individual quantities.

  * **Without** locking screw flange.
   * `CONN HDMI RECPT 19POS SMT R/A`
   * Manufacture part number: [FCI 10029449-111RLF]
   * Digikey part number: [609-4614-1-ND](http://www.digikey.com/product-detail/en/10029449-111RLF/609-4614-1-ND/2785376)
   * [Datasheet](http://portal.fciconnect.com/Comergent//fci/drawing/10029449.pdf)
   * ![Product Image](http://media.digikey.com/Photos/FCI%20Photos/10029449-111RLF.JPG)
   * Cost: $0.73 USD in individual quantities.


# Editing

The designs in this repository was made using
[KiCad](http://www.kicad-pcb.org/) version **4.0.4**.

# License

Copyright 2014 Tim "mithro" Ansell licensed under a
Creative Commons Attribution-ShareAlike 4.0 International License.

You should have received a copy of the license along with this
work.  If not, see <http://creativecommons.org/licenses/by-sa/4.0/>.

![Creative Commons License Logo](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)
