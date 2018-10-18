# RAM.peek4
---

Peeks (reads) a half byte section in video memory.

---

?> The address is for the specific half byte.

---

* **Available since:** _RAM:_ v1.0.0, _LIKO-12_: v0.6.0
* **Last updated in:** _RAM:_ v1.0.0, _LIKO-12_: v0.6.0

---

```lua
local value = RAM.peek4(address)
```

---
### Arguments
---

* **address (number):** An address to the location to read.


---
### Returns
---

* **value (number):** Value of the half byte, that was read.

