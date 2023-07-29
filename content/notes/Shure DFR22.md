---
title: "Shure DFR22"
---

- [User Manual](https://pubs.shure.com/guide/DFR22/en-US)
- [Software User Guide](https://content-files.shure.com/Pubs/dfr22/dfr22-software-guide-en-us.pdf)

This is a DSP platform ([website](https://www.shure.com/en-US/products/mixers/dfr22?variant=DFR22)) that we use to run audio processing on the Mains signal. It is configured as the pre-EQ insert on the main LR as an offboard insert (send on Allen & Heath AR84 output channel 3 & 4, insert return on board input 43 & 44).

The primary purpose of this is feedback reduction (hence the name, DFR = Digital Feedback Reduction), but it also can have more processing configured, and I'm not sure what the full configuration is. The software is compatible with Windows 98, NT, ME, 2000 Professional, or XP. According to an article on their website it's also compatible with Windows 7 and 8.

This device is configurable. Matt West has connected to it with a Virtual Machine running Windows XP. The device is set up with a Dual mono configuration with each channel (Left and Right) having the following signal processing:
- 16-channel Dynamic Feedback Reduction, which automatically detects frequencies on the edge of feeding back and adds narrow notch filters.
- 10-band PEQ (configured to flat)
- 30-band GEQ (configured to flat)
- Limiter (disabled)

# I/O
- XLR Input (2 channels)
	- [[notes/Allen & Heath AR84]] output channel 3 & 4
- XLR Output (2 channels)
	- [[notes/Allen & Heath GLD-112]] board input 43 & 44