# RAM - The Random Access Memory
---

Allows the creation of video memory effects.

Memory Table:
0x0 -> 0x2FFF - The Video RAM
0x3000 -> 0x5FFF - The Label Image
0x6000 -> 0x15FFF - The FDD RAM

---

?> The FDD RAM is used by DiskOS when saving your game into a .png.

---

* **Version:** 1.0.0
* **Available since LIKO-12:** v0.6.0
* **Last updated in LIKO-12:** v0.8.0

---
### Methods
---
* [memcpy](/Documentation/Peripherals/RAM/memcpy.md): Copies data in RAM.
* [memget](/Documentation/Peripherals/RAM/memget.md): Gets data from RAM.
* [memset](/Documentation/Peripherals/RAM/memset.md): Sets data to RAM.
* [peek4](/Documentation/Peripherals/RAM/peek4.md): Peeks a half byte section in RAM.
* [peek](/Documentation/Peripherals/RAM/peek.md): Peeks a byte section in RAM.
* [poke4](/Documentation/Peripherals/RAM/poke4.md): Pokes a half byte section in RAM.
* [poke](/Documentation/Peripherals/RAM/poke.md): Pokes a byte section in RAM.
