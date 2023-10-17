00:00.0 Host bridge: Intel Corporation Xeon E3-1200 v6/7th Gen Core Processor Host Bridge/DRAM Registers (rev 02)
	Subsystem: Dell Xeon E3-1200 v6/7th Gen Core Processor Host Bridge/DRAM Registers
	Flags: bus master, fast devsel, latency 0
	Capabilities: [e0] Vendor Specific Information: Len=10 <?>
	Kernel driver in use: skl_uncore

00:02.0 VGA compatible controller: Intel Corporation HD Graphics 615 (rev 02) (prog-if 00 [VGA controller])
	DeviceName: Onboard IGD
	Subsystem: Dell HD Graphics 615
	Flags: bus master, fast devsel, latency 0, IRQ 131
	Memory at d7000000 (64-bit, non-prefetchable) [size=16M]
	Memory at b0000000 (64-bit, prefetchable) [size=256M]
	I/O ports at 4000 [size=64]
	Expansion ROM at 000c0000 [virtual] [disabled] [size=128K]
	Capabilities: [40] Vendor Specific Information: Len=0c <?>
	Capabilities: [70] Express Root Complex Integrated Endpoint, MSI 00
	Capabilities: [ac] MSI: Enable+ Count=1/1 Maskable- 64bit-
	Capabilities: [d0] Power Management version 2
	Capabilities: [100] Process Address Space ID (PASID)
	Capabilities: [200] Address Translation Service (ATS)
	Capabilities: [300] Page Request Interface (PRI)
	Kernel driver in use: i915
	Kernel modules: i915

00:04.0 Signal processing controller: Intel Corporation Xeon E3-1200 v5/E3-1500 v5/6th Gen Core Processor Thermal Subsystem (rev 02)
	Subsystem: Dell Xeon E3-1200 v5/E3-1500 v5/6th Gen Core Processor Thermal Subsystem
	Flags: fast devsel, IRQ 16
	Memory at d9620000 (64-bit, non-prefetchable) [size=32K]
	Capabilities: [90] MSI: Enable- Count=1/1 Maskable- 64bit-
	Capabilities: [d0] Power Management version 3
	Capabilities: [e0] Vendor Specific Information: Len=0c <?>
	Kernel driver in use: proc_thermal
	Kernel modules: processor_thermal_device_pci_legacy

00:13.0 Non-VGA unclassified device: Intel Corporation Sunrise Point-LP Integrated Sensor Hub (rev 21)
	Subsystem: Dell Sunrise Point-LP Integrated Sensor Hub
	Flags: bus master, fast devsel, latency 0, IRQ 20
	Memory at d9630000 (64-bit, non-prefetchable) [size=4K]
	Capabilities: [80] Power Management version 3
	Kernel driver in use: intel_ish_ipc
	Kernel modules: intel_ish_ipc

00:14.0 USB controller: Intel Corporation Sunrise Point-LP USB 3.0 xHCI Controller (rev 21) (prog-if 30 [XHCI])
	Subsystem: Dell Sunrise Point-LP USB 3.0 xHCI Controller
	Flags: bus master, medium devsel, latency 0, IRQ 125
	Memory at d9600000 (64-bit, non-prefetchable) [size=64K]
	Capabilities: [70] Power Management version 2
	Capabilities: [80] MSI: Enable+ Count=1/8 Maskable- 64bit+
	Kernel driver in use: xhci_hcd
	Kernel modules: xhci_pci

00:14.2 Signal processing controller: Intel Corporation Sunrise Point-LP Thermal subsystem (rev 21)
	Subsystem: Dell Sunrise Point-LP Thermal subsystem
	Flags: fast devsel, IRQ 18
	Memory at d9631000 (64-bit, non-prefetchable) [size=4K]
	Capabilities: [50] Power Management version 3
	Capabilities: [80] MSI: Enable- Count=1/1 Maskable- 64bit-
	Kernel driver in use: intel_pch_thermal
	Kernel modules: intel_pch_thermal

00:15.0 Signal processing controller: Intel Corporation Sunrise Point-LP Serial IO I2C Controller #0 (rev 21)
	Subsystem: Dell Sunrise Point-LP Serial IO I2C Controller
	Flags: bus master, fast devsel, latency 0, IRQ 16
	Memory at d9632000 (64-bit, non-prefetchable) [size=4K]
	Capabilities: [80] Power Management version 3
	Capabilities: [90] Vendor Specific Information: Len=14 <?>
	Kernel driver in use: intel-lpss
	Kernel modules: intel_lpss_pci

00:15.1 Signal processing controller: Intel Corporation Sunrise Point-LP Serial IO I2C Controller #1 (rev 21)
	Subsystem: Dell Sunrise Point-LP Serial IO I2C Controller
	Flags: bus master, fast devsel, latency 0, IRQ 17
	Memory at d9633000 (64-bit, non-prefetchable) [size=4K]
	Capabilities: [80] Power Management version 3
	Capabilities: [90] Vendor Specific Information: Len=14 <?>
	Kernel driver in use: intel-lpss
	Kernel modules: intel_lpss_pci

00:16.0 Communication controller: Intel Corporation Sunrise Point-LP CSME HECI #1 (rev 21)
	Subsystem: Dell Sunrise Point-LP CSME HECI
	Flags: bus master, fast devsel, latency 0, IRQ 132
	Memory at d9634000 (64-bit, non-prefetchable) [size=4K]
	Capabilities: [50] Power Management version 3
	Capabilities: [8c] MSI: Enable+ Count=1/1 Maskable- 64bit+
	Kernel driver in use: mei_me
	Kernel modules: mei_me

00:16.3 Serial controller: Intel Corporation Sunrise Point-LP Active Management Technology - SOL (rev 21) (prog-if 02 [16550])
	Subsystem: Dell Sunrise Point-LP Active Management Technology - SOL
	Flags: 66MHz, fast devsel, IRQ 19
	I/O ports at 4060 [size=8]
	Memory at d9636000 (32-bit, non-prefetchable) [size=4K]
	Capabilities: [40] MSI: Enable- Count=1/1 Maskable- 64bit+
	Capabilities: [50] Power Management version 3
	Kernel driver in use: serial

00:1c.0 PCI bridge: Intel Corporation Sunrise Point-LP PCI Express Root Port #1 (rev f1) (prog-if 00 [Normal decode])
	Subsystem: Dell Sunrise Point-LP PCI Express Root Port
	Flags: bus master, fast devsel, latency 0, IRQ 120
	Bus: primary=00, secondary=01, subordinate=39, sec-latency=0
	I/O behind bridge: 5000-5fff [size=4K] [16-bit]
	Memory behind bridge: c0000000-d60fffff [size=353M] [32-bit]
	Prefetchable memory behind bridge: 80000000-a1ffffff [size=544M] [32-bit]
	Capabilities: [40] Express Root Port (Slot+), MSI 00
	Capabilities: [80] MSI: Enable+ Count=1/1 Maskable- 64bit-
	Capabilities: [90] Subsystem: Dell Sunrise Point-LP PCI Express Root Port
	Capabilities: [a0] Power Management version 3
	Capabilities: [100] Advanced Error Reporting
	Capabilities: [140] Access Control Services
	Capabilities: [200] L1 PM Substates
	Capabilities: [220] Secondary PCI Express
	Kernel driver in use: pcieport

00:1c.4 PCI bridge: Intel Corporation Sunrise Point-LP PCI Express Root Port #5 (rev f1) (prog-if 00 [Normal decode])
	Subsystem: Dell Sunrise Point-LP PCI Express Root Port
	Flags: bus master, fast devsel, latency 0, IRQ 121
	Bus: primary=00, secondary=3a, subordinate=3a, sec-latency=0
	I/O behind bridge: [disabled] [16-bit]
	Memory behind bridge: d9500000-d95fffff [size=1M] [32-bit]
	Prefetchable memory behind bridge: [disabled] [64-bit]
	Capabilities: [40] Express Root Port (Slot+), MSI 00
	Capabilities: [80] MSI: Enable+ Count=1/1 Maskable- 64bit-
	Capabilities: [90] Subsystem: Dell Sunrise Point-LP PCI Express Root Port
	Capabilities: [a0] Power Management version 3
	Capabilities: [100] Advanced Error Reporting
	Capabilities: [140] Access Control Services
	Capabilities: [200] L1 PM Substates
	Capabilities: [220] Secondary PCI Express
	Kernel driver in use: pcieport

00:1d.0 PCI bridge: Intel Corporation Sunrise Point-LP PCI Express Root Port #9 (rev f1) (prog-if 00 [Normal decode])
	Subsystem: Dell Sunrise Point-LP PCI Express Root Port
	Flags: bus master, fast devsel, latency 0, IRQ 122
	Bus: primary=00, secondary=3b, subordinate=3b, sec-latency=0
	I/O behind bridge: 3000-3fff [size=4K] [16-bit]
	Memory behind bridge: d8b00000-d94fffff [size=10M] [32-bit]
	Prefetchable memory behind bridge: d8000000-d89fffff [size=10M] [32-bit]
	Capabilities: [40] Express Root Port (Slot+), MSI 00
	Capabilities: [80] MSI: Enable+ Count=1/1 Maskable- 64bit-
	Capabilities: [90] Subsystem: Dell Sunrise Point-LP PCI Express Root Port
	Capabilities: [a0] Power Management version 3
	Capabilities: [100] Advanced Error Reporting
	Capabilities: [140] Access Control Services
	Capabilities: [200] L1 PM Substates
	Capabilities: [220] Secondary PCI Express
	Kernel driver in use: pcieport

00:1d.1 PCI bridge: Intel Corporation Sunrise Point-LP PCI Express Root Port #10 (rev f1) (prog-if 00 [Normal decode])
	Subsystem: Dell Sunrise Point-LP PCI Express Root Port
	Flags: bus master, fast devsel, latency 0, IRQ 123
	Bus: primary=00, secondary=3c, subordinate=3c, sec-latency=0
	I/O behind bridge: [disabled] [16-bit]
	Memory behind bridge: d8a00000-d8afffff [size=1M] [32-bit]
	Prefetchable memory behind bridge: [disabled] [64-bit]
	Capabilities: [40] Express Root Port (Slot+), MSI 00
	Capabilities: [80] MSI: Enable+ Count=1/1 Maskable- 64bit-
	Capabilities: [90] Subsystem: Dell Sunrise Point-LP PCI Express Root Port
	Capabilities: [a0] Power Management version 3
	Capabilities: [100] Advanced Error Reporting
	Capabilities: [140] Access Control Services
	Capabilities: [200] L1 PM Substates
	Capabilities: [220] Secondary PCI Express
	Kernel driver in use: pcieport

00:1f.0 ISA bridge: Intel Corporation Device 9d4b (rev 21)
	Subsystem: Dell Device 077a
	Flags: bus master, medium devsel, latency 0

00:1f.2 Memory controller: Intel Corporation Sunrise Point-LP PMC (rev 21)
	Subsystem: Dell Sunrise Point-LP PMC
	Flags: fast devsel
	Memory at d962c000 (32-bit, non-prefetchable) [disabled] [size=16K]

00:1f.3 Audio device: Intel Corporation Sunrise Point-LP HD Audio (rev 21) (prog-if 80)
	Subsystem: Dell Sunrise Point-LP HD Audio
	Flags: bus master, fast devsel, latency 64, IRQ 134
	Memory at d9628000 (64-bit, non-prefetchable) [size=16K]
	Memory at d9610000 (64-bit, non-prefetchable) [size=64K]
	Capabilities: [50] Power Management version 3
	Capabilities: [60] MSI: Enable+ Count=1/1 Maskable- 64bit+
	Kernel driver in use: snd_hda_intel
	Kernel modules: snd_hda_intel, snd_soc_skl, snd_soc_avs

00:1f.4 SMBus: Intel Corporation Sunrise Point-LP SMBus (rev 21)
	Subsystem: Dell Sunrise Point-LP SMBus
	Flags: medium devsel, IRQ 16
	Memory at d9635000 (64-bit, non-prefetchable) [size=256]
	I/O ports at efa0 [size=32]
	Kernel driver in use: i801_smbus
	Kernel modules: i2c_i801

3a:00.0 Non-Volatile memory controller: Sandisk Corp WD Black SN750 / PC SN730 NVMe SSD (prog-if 02 [NVM Express])
	Subsystem: Sandisk Corp WD Black SN750 / PC SN730 NVMe SSD
	Flags: bus master, fast devsel, latency 0, IRQ 16, NUMA node 0
	Memory at d9500000 (64-bit, non-prefetchable) [size=16K]
	Memory at d9504000 (64-bit, non-prefetchable) [size=256]
	Capabilities: [80] Power Management version 3
	Capabilities: [90] MSI: Enable- Count=1/32 Maskable- 64bit+
	Capabilities: [b0] MSI-X: Enable+ Count=65 Masked-
	Capabilities: [c0] Express Endpoint, MSI 00
	Capabilities: [100] Advanced Error Reporting
	Capabilities: [150] Device Serial Number 00-00-00-00-00-00-00-00
	Capabilities: [1b8] Latency Tolerance Reporting
	Capabilities: [300] Secondary PCI Express
	Capabilities: [900] L1 PM Substates
	Kernel driver in use: nvme
	Kernel modules: nvme

3b:00.0 Unassigned class [ff00]: Realtek Semiconductor Co., Ltd. RTS525A PCI Express Card Reader (rev 01)
	Subsystem: Dell RTS525A PCI Express Card Reader
	Flags: bus master, fast devsel, latency 0, IRQ 124
	Memory at d8b00000 (32-bit, non-prefetchable) [size=4K]
	Capabilities: [80] Power Management version 3
	Capabilities: [90] MSI: Enable+ Count=1/1 Maskable- 64bit+
	Capabilities: [b0] Express Endpoint, MSI 00
	Capabilities: [100] Advanced Error Reporting
	Capabilities: [148] Device Serial Number 00-00-00-01-00-4c-e0-00
	Capabilities: [158] Latency Tolerance Reporting
	Capabilities: [160] L1 PM Substates
	Kernel driver in use: rtsx_pci
	Kernel modules: rtsx_pci

3c:00.0 Network controller: Intel Corporation Wireless 8265 / 8275 (rev 78)
	Subsystem: Intel Corporation Wireless 8265 / 8275
	Flags: bus master, fast devsel, latency 0, IRQ 133
	Memory at d8a00000 (64-bit, non-prefetchable) [size=8K]
	Capabilities: [c8] Power Management version 3
	Capabilities: [d0] MSI: Enable+ Count=1/1 Maskable- 64bit+
	Capabilities: [40] Express Endpoint, MSI 00
	Capabilities: [100] Advanced Error Reporting
	Capabilities: [140] Device Serial Number f8-63-3f-ff-ff-58-b3-26
	Capabilities: [14c] Latency Tolerance Reporting
	Capabilities: [154] L1 PM Substates
	Kernel driver in use: iwlwifi
	Kernel modules: iwlwifi, wl
