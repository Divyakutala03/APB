The Advanced Peripheral Bus (APB) is part of the Advanced Microcontroller Bus Architecture
(AMBA) protocol family. It defines a low-cost interface that is optimized for minimal power 
consumption and reduced interface complexity.
The APB protocol is not pipelined, use it to connect to low-bandwidth peripherals that do not 
require the high performance of the AXI protocol.
The APB protocol relates a signal transition to the rising edge of the clock, to simplify the 
integration of APB peripherals into any design flow. Every transfer takes at least two cycles.
The APB can interface with:
• AMBA Advanced High-performance Bus (AHB)
• AMBA Advanced High-performance Bus Lite (AHB-Lite)
• AMBA Advanced Extensible Interface (AXI)
• AMBA Advanced Extensible Interface Lite (AXI4-Lite)
You can use it to access the programmable control registers of peripheral devices.
