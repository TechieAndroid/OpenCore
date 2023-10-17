[    0.000000] Linux version 6.4.12-arch1-1 (linux@archlinux) (gcc (GCC) 13.2.1 20230801, GNU ld (GNU Binutils) 2.41.0) #1 SMP PREEMPT_DYNAMIC Thu, 24 Aug 2023 00:38:14 +0000
[    0.000000] Command line: BOOT_IMAGE=/arch/boot/x86_64/vmlinuz-linux archisobasedir=arch archisodevice=UUID=2023-09-01-10-45-56-00
[    0.000000] BIOS-provided physical RAM map:
[    0.000000] BIOS-e820: [mem 0x0000000000000000-0x0000000000057fff] usable
[    0.000000] BIOS-e820: [mem 0x0000000000058000-0x0000000000058fff] reserved
[    0.000000] BIOS-e820: [mem 0x0000000000059000-0x000000000009cfff] usable
[    0.000000] BIOS-e820: [mem 0x000000000009d000-0x00000000000fffff] reserved
[    0.000000] BIOS-e820: [mem 0x0000000000100000-0x000000004ba2ffff] usable
[    0.000000] BIOS-e820: [mem 0x000000004ba30000-0x000000004ba30fff] ACPI NVS
[    0.000000] BIOS-e820: [mem 0x000000004ba31000-0x000000004ba31fff] reserved
[    0.000000] BIOS-e820: [mem 0x000000004ba32000-0x00000000697d7fff] usable
[    0.000000] BIOS-e820: [mem 0x00000000697d8000-0x000000006a989fff] reserved
[    0.000000] BIOS-e820: [mem 0x000000006a98a000-0x000000006af89fff] ACPI NVS
[    0.000000] BIOS-e820: [mem 0x000000006af8a000-0x000000006affefff] ACPI data
[    0.000000] BIOS-e820: [mem 0x000000006afff000-0x000000006affffff] usable
[    0.000000] BIOS-e820: [mem 0x000000006b000000-0x000000006fffffff] reserved
[    0.000000] BIOS-e820: [mem 0x00000000fe010000-0x00000000fe010fff] reserved
[    0.000000] BIOS-e820: [mem 0x00000000ff400000-0x00000000ffffffff] reserved
[    0.000000] BIOS-e820: [mem 0x0000000100000000-0x000000028dffffff] usable
[    0.000000] NX (Execute Disable) protection: active
[    0.000000] e820: update [mem 0x69675018-0x69685057] usable ==> usable
[    0.000000] e820: update [mem 0x69675018-0x69685057] usable ==> usable
[    0.000000] extended physical RAM map:
[    0.000000] reserve setup_data: [mem 0x0000000000000000-0x0000000000057fff] usable
[    0.000000] reserve setup_data: [mem 0x0000000000058000-0x0000000000058fff] reserved
[    0.000000] reserve setup_data: [mem 0x0000000000059000-0x000000000009cfff] usable
[    0.000000] reserve setup_data: [mem 0x000000000009d000-0x00000000000fffff] reserved
[    0.000000] reserve setup_data: [mem 0x0000000000100000-0x000000004ba2ffff] usable
[    0.000000] reserve setup_data: [mem 0x000000004ba30000-0x000000004ba30fff] ACPI NVS
[    0.000000] reserve setup_data: [mem 0x000000004ba31000-0x000000004ba31fff] reserved
[    0.000000] reserve setup_data: [mem 0x000000004ba32000-0x0000000069675017] usable
[    0.000000] reserve setup_data: [mem 0x0000000069675018-0x0000000069685057] usable
[    0.000000] reserve setup_data: [mem 0x0000000069685058-0x00000000697d7fff] usable
[    0.000000] reserve setup_data: [mem 0x00000000697d8000-0x000000006a989fff] reserved
[    0.000000] reserve setup_data: [mem 0x000000006a98a000-0x000000006af89fff] ACPI NVS
[    0.000000] reserve setup_data: [mem 0x000000006af8a000-0x000000006affefff] ACPI data
[    0.000000] reserve setup_data: [mem 0x000000006afff000-0x000000006affffff] usable
[    0.000000] reserve setup_data: [mem 0x000000006b000000-0x000000006fffffff] reserved
[    0.000000] reserve setup_data: [mem 0x00000000fe010000-0x00000000fe010fff] reserved
[    0.000000] reserve setup_data: [mem 0x00000000ff400000-0x00000000ffffffff] reserved
[    0.000000] reserve setup_data: [mem 0x0000000100000000-0x000000028dffffff] usable
[    0.000000] efi: EFI v2.5 by EDK II
[    0.000000] efi: TPMFinalLog=0x6af82000 SMBIOS=0x69946000 ACPI=0x6affe000 ACPI 2.0=0x6affe014 ESRT=0x69901018 MEMATTR=0x66f4e018 MOKvar=0x66f50000 INITRD=0x6968fa98 TPMEventLog=0x69686018 
[    0.000000] efi: Not removing mem40: MMIO range=[0xfe010000-0xfe010fff] (4KB) from e820 map
[    0.000000] efi: Remove mem41: MMIO range=[0xff400000-0xffffffff] (12MB) from e820 map
[    0.000000] e820: remove [mem 0xff400000-0xffffffff] reserved
[    0.000000] SMBIOS 3.0 present.
[    0.000000] DMI: Dell Inc. XPS 13 9365/0RV2GG, BIOS 2.24.0 08/16/2022
[    0.000000] tsc: Detected 1600.000 MHz processor
[    0.000000] tsc: Detected 1599.960 MHz TSC
[    0.001119] e820: update [mem 0x00000000-0x00000fff] usable ==> reserved
[    0.001127] e820: remove [mem 0x000a0000-0x000fffff] usable
[    0.001146] last_pfn = 0x28e000 max_arch_pfn = 0x400000000
[    0.001156] x86/PAT: Configuration [0-7]: WB  WC  UC- UC  WB  WP  UC- WT  
[    0.002100] last_pfn = 0x6b000 max_arch_pfn = 0x400000000
[    0.026520] esrt: Reserving ESRT space from 0x0000000069901018 to 0x0000000069901050.
[    0.026533] e820: update [mem 0x66f50000-0x66f50fff] usable ==> reserved
[    0.026567] Using GB pages for direct mapping
[    0.027762] Secure boot disabled
[    0.027764] RAMDISK: [mem 0x41bd5000-0x46fb3fff]
[    0.027809] ACPI: Early table checksum verification disabled
[    0.027815] ACPI: RSDP 0x000000006AFFE014 000024 (v02 INTEL )
[    0.027824] ACPI: XSDT 0x000000006AFBB188 000114 (v01 INTEL  KBL-ULT  00000000      01000013)
[    0.027837] ACPI: FACP 0x000000006AFFA000 00010C (v05 INTEL  KBL-ULT  00000000 MSFT 0000005F)
[    0.027848] ACPI: DSDT 0x000000006AFCC000 02A463 (v02 INTEL  CBX3     01072009 INTL 20160422)
[    0.027855] ACPI: FACS 0x000000006AE60000 000040
[    0.027861] ACPI: UEFI 0x000000006AE75000 000042 (v01 INTEL  EDK2     00000002      01000013)
[    0.027868] ACPI: SSDT 0x000000006AFFB000 0012A7 (v02 SaSsdt SaSsdt   00003000 INTL 20160422)
[    0.027875] ACPI: HPET 0x000000006AFF9000 000038 (v01 INTEL  KBL-ULT  00000001 MSFT 0000005F)
[    0.027882] ACPI: APIC 0x000000006AFF8000 00012C (v03 INTEL  KBL-ULT  00000001 MSFT 0000005F)
[    0.027889] ACPI: MCFG 0x000000006AFF7000 00003C (v01 INTEL  KBL-ULT  00000001 MSFT 0000005F)
[    0.027895] ACPI: SSDT 0x000000006AFCB000 000EF1 (v02 INTEL  Ther_Rvp 00001000 INTL 20160422)
[    0.027902] ACPI: SSDT 0x000000006AFCA000 0009D7 (v02 DELL   xh_Dell_ 00000000 INTL 20160422)
[    0.027909] ACPI: SSDT 0x000000006AFC8000 0017AE (v02 CpuRef CpuSsdt  00003000 INTL 20160422)
[    0.027915] ACPI: LPIT 0x000000006AFC7000 000094 (v01 INTEL  KBL-ULT  00000000 MSFT 0000005F)
[    0.027922] ACPI: WSMT 0x000000006AFC6000 000028 (v01 INTEL  KBL-ULT  00000000 MSFT 0000005F)
[    0.027928] ACPI: SSDT 0x000000006AFC5000 000161 (v02 INTEL  HdaDsp   00000000 INTL 20160422)
[    0.027935] ACPI: SSDT 0x000000006AFC4000 00029F (v02 INTEL  sensrhub 00000000 INTL 20160422)
[    0.027941] ACPI: SSDT 0x000000006AFC3000 000346 (v01 INTEL  EInkApp  00000000 INTL 20160422)
[    0.027948] ACPI: SSDT 0x000000006AFC2000 000E42 (v02 INTEL  PtidDevc 00001000 INTL 20160422)
[    0.027954] ACPI: SSDT 0x000000006AFC1000 00051E (v02 INTEL  zpodd    00001000 INTL 20160422)
[    0.027961] ACPI: DBGP 0x000000006AFC0000 000034 (v01 INTEL           00000002 MSFT 0000005F)
[    0.027968] ACPI: DBG2 0x000000006AFBF000 000054 (v00 INTEL           00000002 MSFT 0000005F)
[    0.027974] ACPI: SSDT 0x000000006AFBE000 0003DB (v02 INTEL  Tpm2Tabl 00001000 INTL 20160422)
[    0.027981] ACPI: TPM2 0x000000006AFBD000 000034 (v03 INTEL  EDK2     00000002      01000013)
[    0.027988] ACPI: SLIC 0x000000006AFBC000 000176 (v03 DELL   CBX3     06222004 MSFT 00010013)
[    0.027994] ACPI: BOOT 0x000000006AFFD000 000028 (v01 CBX3            00000002 MSFT 01000013)
[    0.028001] ACPI: SSDT 0x000000006AFB6000 004DA1 (v02 DptfTa DptfTabl 00001000 INTL 20160422)
[    0.028008] ACPI: SSDT 0x000000006AFAB000 00A8E1 (v02 GddvDu GddvDumm 00001000 INTL 20160422)
[    0.028014] ACPI: MSDM 0x000000006AFAA000 000055 (v03 DELL   CBX3     06222004 AMI  00010013)
[    0.028021] ACPI: NHLT 0x000000006AFA9000 00002D (v00 INTEL  EDK2     00000002      01000013)
[    0.028028] ACPI: SSDT 0x000000006AFA8000 000156 (v02 Intel  ADebTabl 00001000 INTL 20160422)
[    0.028034] ACPI: FPDT 0x000000006AFA7000 000034 (v01 INTEL  EDK2     00000002      01000013)
[    0.028041] ACPI: ASF! 0x000000006AFA6000 0000A0 (v32 INTEL   HCG     00000001 TFSM 000F4240)
[    0.028047] ACPI: BGRT 0x000000006AFA5000 000038 (v01 INTEL  EDK2     00000002      01000013)
[    0.028053] ACPI: Reserving FACP table memory at [mem 0x6affa000-0x6affa10b]
[    0.028057] ACPI: Reserving DSDT table memory at [mem 0x6afcc000-0x6aff6462]
[    0.028059] ACPI: Reserving FACS table memory at [mem 0x6ae60000-0x6ae6003f]
[    0.028061] ACPI: Reserving UEFI table memory at [mem 0x6ae75000-0x6ae75041]
[    0.028062] ACPI: Reserving SSDT table memory at [mem 0x6affb000-0x6affc2a6]
[    0.028064] ACPI: Reserving HPET table memory at [mem 0x6aff9000-0x6aff9037]
[    0.028066] ACPI: Reserving APIC table memory at [mem 0x6aff8000-0x6aff812b]
[    0.028068] ACPI: Reserving MCFG table memory at [mem 0x6aff7000-0x6aff703b]
[    0.028070] ACPI: Reserving SSDT table memory at [mem 0x6afcb000-0x6afcbef0]
[    0.028071] ACPI: Reserving SSDT table memory at [mem 0x6afca000-0x6afca9d6]
[    0.028073] ACPI: Reserving SSDT table memory at [mem 0x6afc8000-0x6afc97ad]
[    0.028075] ACPI: Reserving LPIT table memory at [mem 0x6afc7000-0x6afc7093]
[    0.028077] ACPI: Reserving WSMT table memory at [mem 0x6afc6000-0x6afc6027]
[    0.028078] ACPI: Reserving SSDT table memory at [mem 0x6afc5000-0x6afc5160]
[    0.028080] ACPI: Reserving SSDT table memory at [mem 0x6afc4000-0x6afc429e]
[    0.028082] ACPI: Reserving SSDT table memory at [mem 0x6afc3000-0x6afc3345]
[    0.028084] ACPI: Reserving SSDT table memory at [mem 0x6afc2000-0x6afc2e41]
[    0.028086] ACPI: Reserving SSDT table memory at [mem 0x6afc1000-0x6afc151d]
[    0.028087] ACPI: Reserving DBGP table memory at [mem 0x6afc0000-0x6afc0033]
[    0.028089] ACPI: Reserving DBG2 table memory at [mem 0x6afbf000-0x6afbf053]
[    0.028091] ACPI: Reserving SSDT table memory at [mem 0x6afbe000-0x6afbe3da]
[    0.028093] ACPI: Reserving TPM2 table memory at [mem 0x6afbd000-0x6afbd033]
[    0.028095] ACPI: Reserving SLIC table memory at [mem 0x6afbc000-0x6afbc175]
[    0.028096] ACPI: Reserving BOOT table memory at [mem 0x6affd000-0x6affd027]
[    0.028098] ACPI: Reserving SSDT table memory at [mem 0x6afb6000-0x6afbada0]
[    0.028100] ACPI: Reserving SSDT table memory at [mem 0x6afab000-0x6afb58e0]
[    0.028102] ACPI: Reserving MSDM table memory at [mem 0x6afaa000-0x6afaa054]
[    0.028104] ACPI: Reserving NHLT table memory at [mem 0x6afa9000-0x6afa902c]
[    0.028106] ACPI: Reserving SSDT table memory at [mem 0x6afa8000-0x6afa8155]
[    0.028107] ACPI: Reserving FPDT table memory at [mem 0x6afa7000-0x6afa7033]
[    0.028109] ACPI: Reserving ASF! table memory at [mem 0x6afa6000-0x6afa609f]
[    0.028111] ACPI: Reserving BGRT table memory at [mem 0x6afa5000-0x6afa5037]
[    0.028268] No NUMA configuration found
[    0.028270] Faking a node at [mem 0x0000000000000000-0x000000028dffffff]
[    0.028277] NODE_DATA(0) allocated [mem 0x28dffb000-0x28dffffff]
[    0.028325] Zone ranges:
[    0.028327]   DMA      [mem 0x0000000000001000-0x0000000000ffffff]
[    0.028331]   DMA32    [mem 0x0000000001000000-0x00000000ffffffff]
[    0.028335]   Normal   [mem 0x0000000100000000-0x000000028dffffff]
[    0.028338]   Device   empty
[    0.028340] Movable zone start for each node
[    0.028342] Early memory node ranges
[    0.028343]   node   0: [mem 0x0000000000001000-0x0000000000057fff]
[    0.028346]   node   0: [mem 0x0000000000059000-0x000000000009cfff]
[    0.028348]   node   0: [mem 0x0000000000100000-0x000000004ba2ffff]
[    0.028351]   node   0: [mem 0x000000004ba32000-0x00000000697d7fff]
[    0.028353]   node   0: [mem 0x000000006afff000-0x000000006affffff]
[    0.028355]   node   0: [mem 0x0000000100000000-0x000000028dffffff]
[    0.028359] Initmem setup node 0 [mem 0x0000000000001000-0x000000028dffffff]
[    0.028367] On node 0, zone DMA: 1 pages in unavailable ranges
[    0.028371] On node 0, zone DMA: 1 pages in unavailable ranges
[    0.028414] On node 0, zone DMA: 99 pages in unavailable ranges
[    0.032910] On node 0, zone DMA32: 2 pages in unavailable ranges
[    0.033015] On node 0, zone DMA32: 6183 pages in unavailable ranges
[    0.050453] On node 0, zone Normal: 20480 pages in unavailable ranges
[    0.050591] On node 0, zone Normal: 8192 pages in unavailable ranges
[    0.050605] Reserving Intel graphics memory at [mem 0x6c000000-0x6fffffff]
[    0.051247] ACPI: PM-Timer IO Port: 0x1808
[    0.051261] ACPI: LAPIC_NMI (acpi_id[0x01] high edge lint[0x1])
[    0.051265] ACPI: LAPIC_NMI (acpi_id[0x02] high edge lint[0x1])
[    0.051267] ACPI: LAPIC_NMI (acpi_id[0x03] high edge lint[0x1])
[    0.051269] ACPI: LAPIC_NMI (acpi_id[0x04] high edge lint[0x1])
[    0.051270] ACPI: LAPIC_NMI (acpi_id[0x05] high edge lint[0x1])
[    0.051272] ACPI: LAPIC_NMI (acpi_id[0x06] high edge lint[0x1])
[    0.051274] ACPI: LAPIC_NMI (acpi_id[0x07] high edge lint[0x1])
[    0.051275] ACPI: LAPIC_NMI (acpi_id[0x08] high edge lint[0x1])
[    0.051277] ACPI: LAPIC_NMI (acpi_id[0x09] high edge lint[0x1])
[    0.051279] ACPI: LAPIC_NMI (acpi_id[0x0a] high edge lint[0x1])
[    0.051280] ACPI: LAPIC_NMI (acpi_id[0x0b] high edge lint[0x1])
[    0.051282] ACPI: LAPIC_NMI (acpi_id[0x0c] high edge lint[0x1])
[    0.051283] ACPI: LAPIC_NMI (acpi_id[0x0d] high edge lint[0x1])
[    0.051285] ACPI: LAPIC_NMI (acpi_id[0x0e] high edge lint[0x1])
[    0.051287] ACPI: LAPIC_NMI (acpi_id[0x0f] high edge lint[0x1])
[    0.051288] ACPI: LAPIC_NMI (acpi_id[0x10] high edge lint[0x1])
[    0.051318] IOAPIC[0]: apic_id 2, version 32, address 0xfec00000, GSI 0-119
[    0.051324] ACPI: INT_SRC_OVR (bus 0 bus_irq 0 global_irq 2 dfl dfl)
[    0.051328] ACPI: INT_SRC_OVR (bus 0 bus_irq 9 global_irq 9 high level)
[    0.051338] ACPI: Using ACPI (MADT) for SMP configuration information
[    0.051340] ACPI: HPET id: 0x8086a201 base: 0xfed00000
[    0.051357] e820: update [mem 0x66e05000-0x66e86fff] usable ==> reserved
[    0.051383] TSC deadline timer available
[    0.051385] smpboot: Allowing 4 CPUs, 0 hotplug CPUs
[    0.051416] PM: hibernation: Registered nosave memory: [mem 0x00000000-0x00000fff]
[    0.051420] PM: hibernation: Registered nosave memory: [mem 0x00058000-0x00058fff]
[    0.051424] PM: hibernation: Registered nosave memory: [mem 0x0009d000-0x000fffff]
[    0.051428] PM: hibernation: Registered nosave memory: [mem 0x4ba30000-0x4ba30fff]
[    0.051430] PM: hibernation: Registered nosave memory: [mem 0x4ba31000-0x4ba31fff]
[    0.051433] PM: hibernation: Registered nosave memory: [mem 0x66e05000-0x66e86fff]
[    0.051437] PM: hibernation: Registered nosave memory: [mem 0x66f50000-0x66f50fff]
[    0.051440] PM: hibernation: Registered nosave memory: [mem 0x69675000-0x69675fff]
[    0.051444] PM: hibernation: Registered nosave memory: [mem 0x69685000-0x69685fff]
[    0.051447] PM: hibernation: Registered nosave memory: [mem 0x697d8000-0x6a989fff]
[    0.051449] PM: hibernation: Registered nosave memory: [mem 0x6a98a000-0x6af89fff]
[    0.051450] PM: hibernation: Registered nosave memory: [mem 0x6af8a000-0x6affefff]
[    0.051454] PM: hibernation: Registered nosave memory: [mem 0x6b000000-0x6fffffff]
[    0.051456] PM: hibernation: Registered nosave memory: [mem 0x70000000-0xfe00ffff]
[    0.051457] PM: hibernation: Registered nosave memory: [mem 0xfe010000-0xfe010fff]
[    0.051459] PM: hibernation: Registered nosave memory: [mem 0xfe011000-0xffffffff]
[    0.051462] [mem 0x70000000-0xfe00ffff] available for PCI devices
[    0.051465] Booting paravirtualized kernel on bare hardware
[    0.051468] clocksource: refined-jiffies: mask: 0xffffffff max_cycles: 0xffffffff, max_idle_ns: 6370452778343963 ns
[    0.064823] setup_percpu: NR_CPUS:320 nr_cpumask_bits:4 nr_cpu_ids:4 nr_node_ids:1
[    0.065345] percpu: Embedded 64 pages/cpu s225280 r8192 d28672 u524288
[    0.065359] pcpu-alloc: s225280 r8192 d28672 u524288 alloc=1*2097152
[    0.065364] pcpu-alloc: [0] 0 1 2 3 
[    0.065404] Kernel command line: BOOT_IMAGE=/arch/boot/x86_64/vmlinuz-linux archisobasedir=arch archisodevice=UUID=2023-09-01-10-45-56-00
[    0.065523] Unknown kernel command line parameters "BOOT_IMAGE=/arch/boot/x86_64/vmlinuz-linux archisobasedir=arch archisodevice=UUID=2023-09-01-10-45-56-00", will be passed to user space.
[    0.065611] random: crng init done
[    0.066914] Dentry cache hash table entries: 1048576 (order: 11, 8388608 bytes, linear)
[    0.067566] Inode-cache hash table entries: 524288 (order: 10, 4194304 bytes, linear)
[    0.067696] Fallback order for Node 0: 0 
[    0.067701] Built 1 zonelists, mobility grouping on.  Total pages: 2029815
[    0.067704] Policy zone: Normal
[    0.068034] mem auto-init: stack:all(zero), heap alloc:on, heap free:off
[    0.068041] software IO TLB: area num 4.
[    0.120340] Memory: 7811104K/8248776K available (16384K kernel code, 2120K rwdata, 12780K rodata, 3348K init, 3984K bss, 437412K reserved, 0K cma-reserved)
[    0.120598] SLUB: HWalign=64, Order=0-3, MinObjects=0, CPUs=4, Nodes=1
[    0.120622] Kernel/User page tables isolation: enabled
[    0.120683] ftrace: allocating 47559 entries in 186 pages
[    0.139262] ftrace: allocated 186 pages with 5 groups
[    0.139403] Dynamic Preempt: full
[    0.139458] rcu: Preemptible hierarchical RCU implementation.
[    0.139460] rcu: 	RCU restricting CPUs from NR_CPUS=320 to nr_cpu_ids=4.
[    0.139463] rcu: 	RCU priority boosting: priority 1 delay 500 ms.
[    0.139466] 	Trampoline variant of Tasks RCU enabled.
[    0.139467] 	Rude variant of Tasks RCU enabled.
[    0.139468] 	Tracing variant of Tasks RCU enabled.
[    0.139469] rcu: RCU calculated value of scheduler-enlistment delay is 30 jiffies.
[    0.139471] rcu: Adjusting geometry for rcu_fanout_leaf=16, nr_cpu_ids=4
[    0.146322] NR_IRQS: 20736, nr_irqs: 1024, preallocated irqs: 16
[    0.146583] rcu: srcu_init: Setting srcu_struct sizes based on contention.
[    0.146904] kfence: initialized - using 2097152 bytes for 255 objects at 0x(____ptrval____)-0x(____ptrval____)
[    0.146979] Console: colour dummy device 80x25
[    0.146985] printk: console [tty0] enabled
[    0.147080] ACPI: Core revision 20230331
[    0.147639] hpet: HPET dysfunctional in PC10. Force disabled.
[    0.147642] APIC: Switch to symmetric I/O mode setup
[    0.148874] x2apic: IRQ remapping doesn't support X2APIC mode
[    0.152964] clocksource: tsc-early: mask: 0xffffffffffffffff max_cycles: 0x170fff30cc4, max_idle_ns: 440795237869 ns
[    0.152978] Calibrating delay loop (skipped), value calculated using timer frequency.. 3201.25 BogoMIPS (lpj=5333200)
[    0.153029] x86/cpu: SGX disabled by BIOS.
[    0.153047] CPU0: Thermal monitoring enabled (TM1)
[    0.153140] process: using mwait in idle threads
[    0.153147] Last level iTLB entries: 4KB 64, 2MB 8, 4MB 8
[    0.153151] Last level dTLB entries: 4KB 64, 2MB 0, 4MB 0, 1GB 4
[    0.153161] Spectre V1 : Mitigation: usercopy/swapgs barriers and __user pointer sanitization
[    0.153166] Spectre V2 : Mitigation: IBRS
[    0.153168] Spectre V2 : Spectre v2 / SpectreRSB mitigation: Filling RSB on context switch
[    0.153170] Spectre V2 : Spectre v2 / SpectreRSB : Filling RSB on VMEXIT
[    0.153172] RETBleed: Mitigation: IBRS
[    0.153176] Spectre V2 : mitigation: Enabling conditional Indirect Branch Prediction Barrier
[    0.153179] Spectre V2 : User space: Mitigation: STIBP via prctl
[    0.153182] Speculative Store Bypass: Mitigation: Speculative Store Bypass disabled via prctl
[    0.153201] MDS: Mitigation: Clear CPU buffers
[    0.153203] TAA: Mitigation: TSX disabled
[    0.153205] MMIO Stale Data: Mitigation: Clear CPU buffers
[    0.153217] SRBDS: Mitigation: Microcode
[    0.153222] GDS: Vulnerable: No microcode
[    0.153237] x86/fpu: Supporting XSAVE feature 0x001: 'x87 floating point registers'
[    0.153241] x86/fpu: Supporting XSAVE feature 0x002: 'SSE registers'
[    0.153244] x86/fpu: Supporting XSAVE feature 0x004: 'AVX registers'
[    0.153247] x86/fpu: Supporting XSAVE feature 0x008: 'MPX bounds registers'
[    0.153250] x86/fpu: Supporting XSAVE feature 0x010: 'MPX CSR'
[    0.153254] x86/fpu: xstate_offset[2]:  576, xstate_sizes[2]:  256
[    0.153259] x86/fpu: xstate_offset[3]:  832, xstate_sizes[3]:   64
[    0.153263] x86/fpu: xstate_offset[4]:  896, xstate_sizes[4]:   64
[    0.153267] x86/fpu: Enabled xstate features 0x1f, context size is 960 bytes, using 'compacted' format.
[    0.156306] Freeing SMP alternatives memory: 40K
[    0.156306] pid_max: default: 32768 minimum: 301
[    0.156306] LSM: initializing lsm=capability,landlock,lockdown,yama,bpf,integrity
[    0.156306] landlock: Up and running.
[    0.156306] Yama: becoming mindful.
[    0.156306] LSM support for eBPF active
[    0.156306] Mount-cache hash table entries: 16384 (order: 5, 131072 bytes, linear)
[    0.156306] Mountpoint-cache hash table entries: 16384 (order: 5, 131072 bytes, linear)
[    0.156306] smpboot: CPU0: Intel(R) Core(TM) i5-7Y57 CPU @ 1.20GHz (family: 0x6, model: 0x8e, stepping: 0x9)
[    0.156306] cblist_init_generic: Setting adjustable number of callback queues.
[    0.156306] cblist_init_generic: Setting shift to 2 and lim to 1.
[    0.156306] cblist_init_generic: Setting adjustable number of callback queues.
[    0.156306] cblist_init_generic: Setting shift to 2 and lim to 1.
[    0.156306] cblist_init_generic: Setting adjustable number of callback queues.
[    0.156306] cblist_init_generic: Setting shift to 2 and lim to 1.
[    0.156306] Performance Events: PEBS fmt3+, Skylake events, 32-deep LBR, full-width counters, Intel PMU driver.
[    0.156306] ... version:                4
[    0.156306] ... bit width:              48
[    0.156306] ... generic registers:      4
[    0.156306] ... value mask:             0000ffffffffffff
[    0.156306] ... max period:             00007fffffffffff
[    0.156306] ... fixed-purpose events:   3
[    0.156306] ... event mask:             000000070000000f
[    0.156306] signal: max sigframe size: 2032
[    0.156306] Estimated ratio of average max frequency by base frequency (times 1024): 1856
[    0.156306] rcu: Hierarchical SRCU implementation.
[    0.156306] rcu: 	Max phase no-delay instances is 1000.
[    0.156306] NMI watchdog: Enabled. Permanently consumes one hw-PMU counter.
[    0.156306] smp: Bringing up secondary CPUs ...
[    0.156306] x86: Booting SMP configuration:
[    0.156306] .... node  #0, CPUs:      #1 #2
[    0.157813] MDS CPU bug present and SMT on, data leak possible. See https://www.kernel.org/doc/html/latest/admin-guide/hw-vuln/mds.html for more details.
[    0.157813] MMIO Stale Data CPU bug present and SMT on, data leak possible. See https://www.kernel.org/doc/html/latest/admin-guide/hw-vuln/processor_mmio_stale_data.html for more details.
[    0.157813]  #3
[    0.160050] smp: Brought up 1 node, 4 CPUs
[    0.160050] smpboot: Max logical packages: 1
[    0.160050] smpboot: Total of 4 processors activated (12804.00 BogoMIPS)
[    0.163525] devtmpfs: initialized
[    0.163525] x86/mm: Memory block size: 128MB
[    0.164753] ACPI: PM: Registering ACPI NVS region [mem 0x4ba30000-0x4ba30fff] (4096 bytes)
[    0.164753] ACPI: PM: Registering ACPI NVS region [mem 0x6a98a000-0x6af89fff] (6291456 bytes)
[    0.164753] clocksource: jiffies: mask: 0xffffffff max_cycles: 0xffffffff, max_idle_ns: 6370867519511994 ns
[    0.164753] futex hash table entries: 1024 (order: 4, 65536 bytes, linear)
[    0.164753] pinctrl core: initialized pinctrl subsystem
[    0.166438] PM: RTC time: 23:44:09, date: 2023-10-10
[    0.167596] NET: Registered PF_NETLINK/PF_ROUTE protocol family
[    0.167971] DMA: preallocated 1024 KiB GFP_KERNEL pool for atomic allocations
[    0.168117] DMA: preallocated 1024 KiB GFP_KERNEL|GFP_DMA pool for atomic allocations
[    0.168251] DMA: preallocated 1024 KiB GFP_KERNEL|GFP_DMA32 pool for atomic allocations
[    0.168280] audit: initializing netlink subsys (disabled)
[    0.168311] audit: type=2000 audit(1696981449.013:1): state=initialized audit_enabled=0 res=1
[    0.168311] thermal_sys: Registered thermal governor 'fair_share'
[    0.168311] thermal_sys: Registered thermal governor 'bang_bang'
[    0.168311] thermal_sys: Registered thermal governor 'step_wise'
[    0.168311] thermal_sys: Registered thermal governor 'user_space'
[    0.168311] thermal_sys: Registered thermal governor 'power_allocator'
[    0.168311] cpuidle: using governor ladder
[    0.168311] cpuidle: using governor menu
[    0.168311] Simple Boot Flag at 0x47 set to 0x80
[    0.168311] ACPI FADT declares the system doesn't support PCIe ASPM, so disable it
[    0.168311] acpiphp: ACPI Hot Plug PCI Controller Driver version: 0.5
[    0.168311] PCI: MMCONFIG for domain 0000 [bus 00-ff] at [mem 0xe0000000-0xefffffff] (base 0xe0000000)
[    0.168311] PCI: not using MMCONFIG
[    0.168311] PCI: Using configuration type 1 for base access
[    0.168311] ENERGY_PERF_BIAS: Set to 'normal', was 'performance'
[    0.169733] kprobes: kprobe jump-optimization is enabled. All kprobes are optimized if possible.
[    0.169748] HugeTLB: registered 1.00 GiB page size, pre-allocated 0 pages
[    0.169748] HugeTLB: 16380 KiB vmemmap can be freed for a 1.00 GiB page
[    0.169748] HugeTLB: registered 2.00 MiB page size, pre-allocated 0 pages
[    0.169748] HugeTLB: 28 KiB vmemmap can be freed for a 2.00 MiB page
[    0.170115] fbcon: Taking over console
[    0.170115] ACPI: Added _OSI(Module Device)
[    0.170115] ACPI: Added _OSI(Processor Device)
[    0.170115] ACPI: Added _OSI(3.0 _SCP Extensions)
[    0.170115] ACPI: Added _OSI(Processor Aggregator Device)
[    0.291672] ACPI: 14 ACPI AML tables successfully acquired and loaded
[    0.297427] ACPI: [Firmware Bug]: BIOS _OSI(Linux) query ignored
[    0.328082] ACPI: Dynamic OEM Table Load:
[    0.328111] ACPI: SSDT 0xFFFF9A2A00DCD000 000507 (v02 PmRef  Cpu0Ist  00003000 INTL 20160422)
[    0.331902] ACPI: \_PR_.PR00: _OSC native thermal LVT Acked
[    0.336391] ACPI: Dynamic OEM Table Load:
[    0.336412] ACPI: SSDT 0xFFFF9A2A00D6C000 0003FF (v02 PmRef  Cpu0Cst  00003001 INTL 20160422)
[    0.341215] ACPI: Dynamic OEM Table Load:
[    0.341236] ACPI: SSDT 0xFFFF9A2A00DAB000 000D14 (v02 PmRef  ApIst    00003000 INTL 20160422)
[    0.347215] ACPI: Dynamic OEM Table Load:
[    0.347234] ACPI: SSDT 0xFFFF9A2A00D6D000 00030A (v02 PmRef  ApCst    00003000 INTL 20160422)
[    0.356065] ACPI: EC: EC started
[    0.356068] ACPI: EC: interrupt blocked
[    0.362594] ACPI: EC: EC_CMD/EC_SC=0x934, EC_DATA=0x930
[    0.362601] ACPI: \_SB_.PCI0.LPCB.ECDV: Boot DSDT EC used to handle transactions
[    0.362605] ACPI: Interpreter enabled
[    0.362715] ACPI: PM: (supports S0 S3 S4 S5)
[    0.362718] ACPI: Using IOAPIC for interrupt routing
[    0.367120] PCI: MMCONFIG for domain 0000 [bus 00-ff] at [mem 0xe0000000-0xefffffff] (base 0xe0000000)
[    0.375511] PCI: MMCONFIG at [mem 0xe0000000-0xefffffff] reserved as ACPI motherboard resource
[    0.375548] PCI: Using host bridge windows from ACPI; if necessary, use "pci=nocrs" and report a bug
[    0.375551] PCI: Using E820 reservations for host bridge windows
[    0.378689] ACPI: Enabled 8 GPEs in block 00 to 7F
[    0.406814] ACPI: \_SB_.PCI0.RP10.PXSX.WRST: New power resource
[    0.451475] ACPI: \_TZ_.FN00: New power resource
[    0.451709] ACPI: \_TZ_.FN01: New power resource
[    0.451939] ACPI: \_TZ_.FN02: New power resource
[    0.452166] ACPI: \_TZ_.FN03: New power resource
[    0.452397] ACPI: \_TZ_.FN04: New power resource
[    0.455662] ACPI: PCI Root Bridge [PCI0] (domain 0000 [bus 00-fe])
[    0.455678] acpi PNP0A08:00: _OSC: OS supports [ExtendedConfig ASPM ClockPM Segments MSI EDR HPX-Type3]
[    0.455978] acpi PNP0A08:00: _OSC: platform does not support [PCIeHotplug SHPCHotplug PME AER]
[    0.456562] acpi PNP0A08:00: _OSC: OS now controls [PCIeCapability LTR DPC]
[    0.456567] acpi PNP0A08:00: FADT indicates ASPM is unsupported, using BIOS configuration
[    0.462602] PCI host bridge to bus 0000:00
[    0.462608] pci_bus 0000:00: root bus resource [io  0x0000-0x0cf7 window]
[    0.462614] pci_bus 0000:00: root bus resource [io  0x0d00-0xffff window]
[    0.462619] pci_bus 0000:00: root bus resource [mem 0x000a0000-0x000fffff window]
[    0.462623] pci_bus 0000:00: root bus resource [mem 0x70000000-0xdfffffff window]
[    0.462627] pci_bus 0000:00: root bus resource [mem 0xfd000000-0xfe7fffff window]
[    0.462630] pci_bus 0000:00: root bus resource [bus 00-fe]
[    0.462842] pci 0000:00:00.0: [8086:590c] type 00 class 0x060000
[    0.463017] pci 0000:00:02.0: [8086:591e] type 00 class 0x030000
[    0.463036] pci 0000:00:02.0: reg 0x10: [mem 0xd7000000-0xd7ffffff 64bit]
[    0.463049] pci 0000:00:02.0: reg 0x18: [mem 0xb0000000-0xbfffffff 64bit pref]
[    0.463059] pci 0000:00:02.0: reg 0x20: [io  0x4000-0x403f]
[    0.463095] pci 0000:00:02.0: BAR 2: assigned to efifb
[    0.463102] pci 0000:00:02.0: Video device with shadowed ROM at [mem 0x000c0000-0x000dffff]
[    0.463573] pci 0000:00:04.0: [8086:1903] type 00 class 0x118000
[    0.463592] pci 0000:00:04.0: reg 0x10: [mem 0xd9620000-0xd9627fff 64bit]
[    0.464327] pci 0000:00:13.0: [8086:9d35] type 00 class 0x000000
[    0.464355] pci 0000:00:13.0: reg 0x10: [mem 0xd9630000-0xd9630fff 64bit]
[    0.465612] pci 0000:00:14.0: [8086:9d2f] type 00 class 0x0c0330
[    0.465640] pci 0000:00:14.0: reg 0x10: [mem 0xd9600000-0xd960ffff 64bit]
[    0.465740] pci 0000:00:14.0: PME# supported from D3hot D3cold
[    0.467370] pci 0000:00:14.2: [8086:9d31] type 00 class 0x118000
[    0.467400] pci 0000:00:14.2: reg 0x10: [mem 0xd9631000-0xd9631fff 64bit]
[    0.467747] pci 0000:00:15.0: [8086:9d60] type 00 class 0x118000
[    0.467958] pci 0000:00:15.0: reg 0x10: [mem 0xd9632000-0xd9632fff 64bit]
[    0.469549] pci 0000:00:15.1: [8086:9d61] type 00 class 0x118000
[    0.469752] pci 0000:00:15.1: reg 0x10: [mem 0xd9633000-0xd9633fff 64bit]
[    0.471237] pci 0000:00:16.0: [8086:9d3a] type 00 class 0x078000
[    0.471267] pci 0000:00:16.0: reg 0x10: [mem 0xd9634000-0xd9634fff 64bit]
[    0.471367] pci 0000:00:16.0: PME# supported from D3hot
[    0.472545] pci 0000:00:16.3: [8086:9d3d] type 00 class 0x070002
[    0.472570] pci 0000:00:16.3: reg 0x10: [io  0x4060-0x4067]
[    0.472585] pci 0000:00:16.3: reg 0x14: [mem 0xd9636000-0xd9636fff]
[    0.472825] pci 0000:00:1c.0: [8086:9d10] type 01 class 0x060400
[    0.472960] pci 0000:00:1c.0: PME# supported from D0 D3hot D3cold
[    0.474485] pci 0000:00:1c.4: [8086:9d14] type 01 class 0x060400
[    0.474618] pci 0000:00:1c.4: PME# supported from D0 D3hot D3cold
[    0.476115] pci 0000:00:1d.0: [8086:9d18] type 01 class 0x060400
[    0.476237] pci 0000:00:1d.0: PME# supported from D0 D3hot D3cold
[    0.477697] pci 0000:00:1d.1: [8086:9d19] type 01 class 0x060400
[    0.477820] pci 0000:00:1d.1: PME# supported from D0 D3hot D3cold
[    0.479349] pci 0000:00:1f.0: [8086:9d4b] type 00 class 0x060100
[    0.480172] pci 0000:00:1f.2: [8086:9d21] type 00 class 0x058000
[    0.480192] pci 0000:00:1f.2: reg 0x10: [mem 0xd962c000-0xd962ffff]
[    0.480862] pci 0000:00:1f.3: [8086:9d71] type 00 class 0x040380
[    0.480893] pci 0000:00:1f.3: reg 0x10: [mem 0xd9628000-0xd962bfff 64bit]
[    0.480928] pci 0000:00:1f.3: reg 0x20: [mem 0xd9610000-0xd961ffff 64bit]
[    0.480997] pci 0000:00:1f.3: PME# supported from D3hot D3cold
[    0.482824] pci 0000:00:1f.4: [8086:9d23] type 00 class 0x0c0500
[    0.482879] pci 0000:00:1f.4: reg 0x10: [mem 0xd9635000-0xd96350ff 64bit]
[    0.482934] pci 0000:00:1f.4: reg 0x20: [io  0xefa0-0xefbf]
[    0.483691] pci 0000:00:1c.0: PCI bridge to [bus 01-39]
[    0.483707] pci 0000:00:1c.0:   bridge window [mem 0xc0000000-0xd60fffff]
[    0.483716] pci 0000:00:1c.0:   bridge window [mem 0x80000000-0xa1ffffff 64bit pref]
[    0.483838] pci 0000:3a:00.0: [15b7:5006] type 00 class 0x010802
[    0.483869] pci 0000:3a:00.0: reg 0x10: [mem 0xd9500000-0xd9503fff 64bit]
[    0.483911] pci 0000:3a:00.0: reg 0x20: [mem 0xd9504000-0xd95040ff 64bit]
[    0.484306] pci 0000:00:1c.4: PCI bridge to [bus 3a]
[    0.484315] pci 0000:00:1c.4:   bridge window [mem 0xd9500000-0xd95fffff]
[    0.484423] pci 0000:3b:00.0: [10ec:525a] type 00 class 0xff0000
[    0.484456] pci 0000:3b:00.0: reg 0x14: [mem 0xd8b00000-0xd8b00fff]
[    0.484608] pci 0000:3b:00.0: supports D1 D2
[    0.484611] pci 0000:3b:00.0: PME# supported from D1 D2 D3hot D3cold
[    0.484889] pci 0000:00:1d.0: PCI bridge to [bus 3b]
[    0.484895] pci 0000:00:1d.0:   bridge window [io  0x3000-0x3fff]
[    0.484901] pci 0000:00:1d.0:   bridge window [mem 0xd8b00000-0xd94fffff]
[    0.484909] pci 0000:00:1d.0:   bridge window [mem 0xd8000000-0xd89fffff 64bit pref]
[    0.485418] pci 0000:3c:00.0: [8086:24fd] type 00 class 0x028000
[    0.485510] pci 0000:3c:00.0: reg 0x10: [mem 0xd8a00000-0xd8a01fff 64bit]
[    0.486074] pci 0000:3c:00.0: PME# supported from D0 D3hot D3cold
[    0.486306] pci 0000:00:1d.1: PCI bridge to [bus 3c]
[    0.486306] pci 0000:00:1d.1:   bridge window [mem 0xd8a00000-0xd8afffff]
[    0.494898] ACPI: PCI: Interrupt link LNKA configured for IRQ 11
[    0.495052] ACPI: PCI: Interrupt link LNKB configured for IRQ 10
[    0.496440] ACPI: PCI: Interrupt link LNKC configured for IRQ 11
[    0.496588] ACPI: PCI: Interrupt link LNKD configured for IRQ 11
[    0.496738] ACPI: PCI: Interrupt link LNKE configured for IRQ 11
[    0.496885] ACPI: PCI: Interrupt link LNKF configured for IRQ 11
[    0.497031] ACPI: PCI: Interrupt link LNKG configured for IRQ 11
[    0.497178] ACPI: PCI: Interrupt link LNKH configured for IRQ 11
[    0.527952] Low-power S0 idle used by default for system suspend
[    0.553893] ACPI: EC: interrupt unblocked
[    0.553897] ACPI: EC: event unblocked
[    0.553911] ACPI: EC: EC_CMD/EC_SC=0x934, EC_DATA=0x930
[    0.553914] ACPI: EC: GPE=0x14
[    0.553918] ACPI: \_SB_.PCI0.LPCB.ECDV: Boot DSDT EC initialization complete
[    0.553923] ACPI: \_SB_.PCI0.LPCB.ECDV: EC: Used to handle transactions and events
[    0.554135] iommu: Default domain type: Translated 
[    0.554135] iommu: DMA domain TLB invalidation policy: lazy mode 
[    0.554135] SCSI subsystem initialized
[    0.554135] libata version 3.00 loaded.
[    0.554135] ACPI: bus type USB registered
[    0.554135] usbcore: registered new interface driver usbfs
[    0.554135] usbcore: registered new interface driver hub
[    0.554135] usbcore: registered new device driver usb
[    0.554135] pps_core: LinuxPPS API ver. 1 registered
[    0.554135] pps_core: Software ver. 5.3.6 - Copyright 2005-2007 Rodolfo Giometti <giometti@linux.it>
[    0.554135] PTP clock support registered
[    0.554135] EDAC MC: Ver: 3.0.0
[    0.554135] efivars: Registered efivars operations
[    0.557117] NetLabel: Initializing
[    0.557120] NetLabel:  domain hash size = 128
[    0.557123] NetLabel:  protocols = UNLABELED CIPSOv4 CALIPSO
[    0.557164] NetLabel:  unlabeled traffic allowed by default
[    0.557175] mctp: management component transport protocol core
[    0.557177] NET: Registered PF_MCTP protocol family
[    0.557185] PCI: Using ACPI for IRQ routing
[    0.580481] PCI: pci_cache_line_size set to 64 bytes
[    0.581127] e820: reserve RAM buffer [mem 0x00058000-0x0005ffff]
[    0.581158] e820: reserve RAM buffer [mem 0x0009d000-0x0009ffff]
[    0.581161] e820: reserve RAM buffer [mem 0x4ba30000-0x4bffffff]
[    0.581165] e820: reserve RAM buffer [mem 0x66e05000-0x67ffffff]
[    0.581168] e820: reserve RAM buffer [mem 0x66f50000-0x67ffffff]
[    0.581171] e820: reserve RAM buffer [mem 0x69675018-0x6bffffff]
[    0.581174] e820: reserve RAM buffer [mem 0x697d8000-0x6bffffff]
[    0.581177] e820: reserve RAM buffer [mem 0x6b000000-0x6bffffff]
[    0.581179] e820: reserve RAM buffer [mem 0x28e000000-0x28fffffff]
[    0.582995] pci 0000:00:02.0: vgaarb: setting as boot VGA device
[    0.582997] pci 0000:00:02.0: vgaarb: bridge control possible
[    0.583000] pci 0000:00:02.0: vgaarb: VGA device added: decodes=io+mem,owns=io+mem,locks=none
[    0.583017] vgaarb: loaded
[    0.583195] clocksource: Switched to clocksource tsc-early
[    0.604643] VFS: Disk quotas dquot_6.6.0
[    0.604672] VFS: Dquot-cache hash table entries: 512 (order 0, 4096 bytes)
[    0.604850] pnp: PnP ACPI init
[    0.605284] system 00:00: [mem 0xfd000000-0xfdabffff] has been reserved
[    0.605293] system 00:00: [mem 0xfdad0000-0xfdadffff] has been reserved
[    0.605299] system 00:00: [mem 0xfdb00000-0xfdffffff] has been reserved
[    0.605303] system 00:00: [mem 0xfe000000-0xfe01ffff] could not be reserved
[    0.605308] system 00:00: [mem 0xfe036000-0xfe03bfff] has been reserved
[    0.605312] system 00:00: [mem 0xfe03d000-0xfe3fffff] has been reserved
[    0.605317] system 00:00: [mem 0xfe410000-0xfe7fffff] has been reserved
[    0.606159] system 00:01: [io  0x2000-0x20fe] has been reserved
[    0.606637] system 00:02: [io  0x0680-0x069f] has been reserved
[    0.606643] system 00:02: [io  0xffff] has been reserved
[    0.606647] system 00:02: [io  0xffff] has been reserved
[    0.606651] system 00:02: [io  0xffff] has been reserved
[    0.606654] system 00:02: [io  0x1800-0x18fe] has been reserved
[    0.606658] system 00:02: [io  0x164e-0x164f] has been reserved
[    0.607007] system 00:04: [io  0x1854-0x1857] has been reserved
[    0.613365] system 00:08: [mem 0xfed10000-0xfed17fff] has been reserved
[    0.613373] system 00:08: [mem 0xfed18000-0xfed18fff] has been reserved
[    0.613378] system 00:08: [mem 0xfed19000-0xfed19fff] has been reserved
[    0.613383] system 00:08: [mem 0xe0000000-0xefffffff] has been reserved
[    0.613387] system 00:08: [mem 0xfed20000-0xfed3ffff] has been reserved
[    0.613391] system 00:08: [mem 0xfed90000-0xfed93fff] has been reserved
[    0.613396] system 00:08: [mem 0xfed45000-0xfed8ffff] has been reserved
[    0.613401] system 00:08: [mem 0xff000000-0xffffffff] has been reserved
[    0.613405] system 00:08: [mem 0xfee00000-0xfeefffff] has been reserved
[    0.613410] system 00:08: [mem 0x70000000-0x7001ffff] has been reserved
[    0.617942] pnp: PnP ACPI: found 9 devices
[    0.625194] clocksource: acpi_pm: mask: 0xffffff max_cycles: 0xffffff, max_idle_ns: 2085701024 ns
[    0.625343] NET: Registered PF_INET protocol family
[    0.625508] IP idents hash table entries: 131072 (order: 8, 1048576 bytes, linear)
[    0.629162] tcp_listen_portaddr_hash hash table entries: 4096 (order: 4, 65536 bytes, linear)
[    0.629227] Table-perturb hash table entries: 65536 (order: 6, 262144 bytes, linear)
[    0.629295] TCP established hash table entries: 65536 (order: 7, 524288 bytes, linear)
[    0.629667] TCP bind hash table entries: 65536 (order: 9, 2097152 bytes, linear)
[    0.630228] TCP: Hash tables configured (established 65536 bind 65536)
[    0.630355] MPTCP token hash table entries: 8192 (order: 5, 196608 bytes, linear)
[    0.630415] UDP hash table entries: 4096 (order: 5, 131072 bytes, linear)
[    0.630461] UDP-Lite hash table entries: 4096 (order: 5, 131072 bytes, linear)
[    0.630553] NET: Registered PF_UNIX/PF_LOCAL protocol family
[    0.630567] NET: Registered PF_XDP protocol family
[    0.630578] pci 0000:00:1c.0: bridge window [io  0x1000-0x0fff] to [bus 01-39] add_size 1000
[    0.630601] pci 0000:00:1c.0: BAR 13: assigned [io  0x5000-0x5fff]
[    0.630610] pci 0000:00:1c.0: PCI bridge to [bus 01-39]
[    0.630617] pci 0000:00:1c.0:   bridge window [io  0x5000-0x5fff]
[    0.630624] pci 0000:00:1c.0:   bridge window [mem 0xc0000000-0xd60fffff]
[    0.630631] pci 0000:00:1c.0:   bridge window [mem 0x80000000-0xa1ffffff 64bit pref]
[    0.630640] pci 0000:00:1c.4: PCI bridge to [bus 3a]
[    0.630647] pci 0000:00:1c.4:   bridge window [mem 0xd9500000-0xd95fffff]
[    0.630658] pci 0000:00:1d.0: PCI bridge to [bus 3b]
[    0.630662] pci 0000:00:1d.0:   bridge window [io  0x3000-0x3fff]
[    0.630668] pci 0000:00:1d.0:   bridge window [mem 0xd8b00000-0xd94fffff]
[    0.630674] pci 0000:00:1d.0:   bridge window [mem 0xd8000000-0xd89fffff 64bit pref]
[    0.630682] pci 0000:00:1d.1: PCI bridge to [bus 3c]
[    0.630688] pci 0000:00:1d.1:   bridge window [mem 0xd8a00000-0xd8afffff]
[    0.630699] pci_bus 0000:00: resource 4 [io  0x0000-0x0cf7 window]
[    0.630704] pci_bus 0000:00: resource 5 [io  0x0d00-0xffff window]
[    0.630708] pci_bus 0000:00: resource 6 [mem 0x000a0000-0x000fffff window]
[    0.630711] pci_bus 0000:00: resource 7 [mem 0x70000000-0xdfffffff window]
[    0.630715] pci_bus 0000:00: resource 8 [mem 0xfd000000-0xfe7fffff window]
[    0.630719] pci_bus 0000:01: resource 0 [io  0x5000-0x5fff]
[    0.630722] pci_bus 0000:01: resource 1 [mem 0xc0000000-0xd60fffff]
[    0.630725] pci_bus 0000:01: resource 2 [mem 0x80000000-0xa1ffffff 64bit pref]
[    0.630729] pci_bus 0000:3a: resource 1 [mem 0xd9500000-0xd95fffff]
[    0.630733] pci_bus 0000:3b: resource 0 [io  0x3000-0x3fff]
[    0.630736] pci_bus 0000:3b: resource 1 [mem 0xd8b00000-0xd94fffff]
[    0.630739] pci_bus 0000:3b: resource 2 [mem 0xd8000000-0xd89fffff 64bit pref]
[    0.630743] pci_bus 0000:3c: resource 1 [mem 0xd8a00000-0xd8afffff]
[    0.632089] PCI: CLS 0 bytes, default 64
[    0.632111] PCI-DMA: Using software bounce buffering for IO (SWIOTLB)
[    0.632113] software IO TLB: mapped [mem 0x0000000062e05000-0x0000000066e05000] (64MB)
[    0.632211] Trying to unpack rootfs image as initramfs...
[    0.633539] Initialise system trusted keyrings
[    0.633558] Key type blacklist registered
[    0.633651] workingset: timestamp_bits=41 max_order=21 bucket_order=0
[    0.633691] zbud: loaded
[    0.634094] integrity: Platform Keyring initialized
[    0.634106] integrity: Machine keyring initialized
[    0.653544] Key type asymmetric registered
[    0.653553] Asymmetric key parser 'x509' registered
[    0.653610] Block layer SCSI generic (bsg) driver version 0.4 loaded (major 242)
[    0.653727] io scheduler mq-deadline registered
[    0.653732] io scheduler kyber registered
[    0.653762] io scheduler bfq registered
[    0.656439] shpchp: Standard Hot Plug PCI Controller Driver version: 0.4
[    0.661332] ACPI: AC: AC Adapter [AC] (off-line)
[    0.661519] input: Lid Switch as /devices/LNXSYSTM:00/LNXSYBUS:00/PNP0C0D:00/input/input0
[    0.663025] ACPI: button: Lid Switch [LID0]
[    0.663112] input: Power Button as /devices/LNXSYSTM:00/LNXSYBUS:00/PNP0C0C:00/input/input1
[    0.666347] ACPI: button: Power Button [PBTN]
[    0.666541] input: Sleep Button as /devices/LNXSYSTM:00/LNXSYBUS:00/PNP0C0E:00/input/input2
[    0.666598] ACPI: button: Sleep Button [SBTN]
[    0.666684] input: Power Button as /devices/LNXSYSTM:00/LNXPWRBN:00/input/input3
[    0.669702] ACPI: button: Power Button [PWRF]
[    0.672191] thermal LNXTHERM:00: registered as thermal_zone0
[    0.672200] ACPI: thermal: Thermal Zone [TZ00] (28 C)
[    0.672874] thermal LNXTHERM:01: registered as thermal_zone1
[    0.672880] ACPI: thermal: Thermal Zone [TZ01] (30 C)
[    0.673541] Serial: 8250/16550 driver, 32 ports, IRQ sharing enabled
[    0.677927] serial 0000:00:16.3: enabling device (0001 -> 0003)
[    0.679558] 0000:00:16.3: ttyS4 at I/O 0x4060 (irq = 19, base_baud = 115200) is a 16550A
[    0.680458] hpet_acpi_add: no address or irqs in _CRS
[    0.680633] Non-volatile memory driver v1.3
[    0.680638] Linux agpgart interface v0.103
[    0.730406] Freeing initrd memory: 85884K
[    0.732347] ACPI: battery: Slot [BAT0] (battery present)
[    0.839776] ACPI Error: Thread 2981888 cannot release Mutex [PATM] acquired by thread 8823040 (20230331/exmutex-378)
[    0.839808] ACPI Error: Aborting method \_SB.PCI0.LPCB.ECDV._Q66 due to previous error (AE_AML_NOT_OWNER) (20230331/psparse-529)
[    1.429821] ------------[ cut here ]------------
[    1.429827] WARNING: CPU: 1 PID: 1 at kernel/workqueue.c:3185 __flush_work.isra.0+0x270/0x280
[    1.429845] Modules linked in:
[    1.429851] CPU: 1 PID: 1 Comm: swapper/0 Not tainted 6.4.12-arch1-1 #1 3e6fa2753a2d75925c34ecb78e22e85a65d083df
[    1.429859] Hardware name: Dell Inc. XPS 13 9365/0RV2GG, BIOS 2.24.0 08/16/2022
[    1.429862] RIP: 0010:__flush_work.isra.0+0x270/0x280
[    1.429872] Code: 8b 04 25 00 37 03 00 48 89 44 24 40 48 8b 73 30 8b 4b 28 e9 e3 fe ff ff 40 30 f6 4c 8b 3e e9 21 fe ff ff 0f 0b e9 3a ff ff ff <0f> 0b e9 33 ff ff ff e8 b4 1f c9 00 0f 1f 40 00 90 90 90 90 90 90
[    1.429877] RSP: 0000:ffffbd7200087b80 EFLAGS: 00010246
[    1.429882] RAX: 0000000000000000 RBX: ffff9a2a01ffd428 RCX: 0000000000000000
[    1.429886] RDX: 0000000000000004 RSI: ffffbd7200478008 RDI: ffffbd7200087bc8
[    1.429890] RBP: ffff9a2a01ffd468 R08: 0000000000000002 R09: 0000000000000000
[    1.429893] R10: 0000000000000001 R11: 0000000000000100 R12: ffff9a2a008f7000
[    1.429897] R13: ffffbd7200087b80 R14: 0000000000000001 R15: ffff9a2a00d8a010
[    1.429900] FS:  0000000000000000(0000) GS:ffff9a2b85c80000(0000) knlGS:0000000000000000
[    1.429904] CS:  0010 DS: 0000 ES: 0000 CR0: 0000000080050033
[    1.429908] CR2: 0000000000000000 CR3: 0000000259220001 CR4: 00000000003706e0
[    1.429912] DR0: 0000000000000000 DR1: 0000000000000000 DR2: 0000000000000000
[    1.429915] DR3: 0000000000000000 DR6: 00000000fffe0ff0 DR7: 0000000000000400
[    1.429918] Call Trace:
[    1.429922]  <TASK>
[    1.429925]  ? __flush_work.isra.0+0x270/0x280
[    1.429934]  ? __warn+0x81/0x130
[    1.429943]  ? __flush_work.isra.0+0x270/0x280
[    1.429952]  ? report_bug+0x171/0x1a0
[    1.429960]  ? handle_bug+0x3c/0x80
[    1.429968]  ? exc_invalid_op+0x17/0x70
[    1.429976]  ? asm_exc_invalid_op+0x1a/0x20
[    1.429990]  ? __flush_work.isra.0+0x270/0x280
[    1.430002]  tpm_tis_remove+0xaa/0x100
[    1.430011]  tpm_tis_core_init+0x235/0xa00
[    1.430020]  tpm_tis_plat_probe+0xda/0x120
[    1.430030]  platform_probe+0x41/0xa0
[    1.430037]  really_probe+0x19b/0x3e0
[    1.430044]  ? __pfx___driver_attach+0x10/0x10
[    1.430050]  __driver_probe_device+0x78/0x160
[    1.430057]  driver_probe_device+0x1f/0x90
[    1.430063]  __driver_attach+0xd2/0x1c0
[    1.430070]  bus_for_each_dev+0x85/0xd0
[    1.430076]  bus_add_driver+0x116/0x220
[    1.430083]  driver_register+0x59/0x100
[    1.430090]  ? __pfx_init_tis+0x10/0x10
[    1.430098]  init_tis+0x34/0x100
[    1.430107]  ? __pfx_init_tis+0x10/0x10
[    1.430113]  do_one_initcall+0x5a/0x240
[    1.430125]  kernel_init_freeable+0x1d4/0x320
[    1.430136]  ? __pfx_kernel_init+0x10/0x10
[    1.430146]  kernel_init+0x1a/0x1c0
[    1.430154]  ret_from_fork+0x29/0x50
[    1.430168]  </TASK>
[    1.430170] ---[ end trace 0000000000000000 ]---
[    1.430358] tpm_tis: probe of MSFT0101:00 failed with error -1
[    1.430548] AMD-Vi: AMD IOMMUv2 functionality not available on this system - This is not a bug.
[    1.430662] ACPI: bus type drm_connector registered
[    1.432282] usbcore: registered new interface driver usbserial_generic
[    1.432296] usbserial: USB Serial support registered for generic
[    1.432696] rtc_cmos 00:03: RTC can wake from S4
[    1.433565] rtc_cmos 00:03: registered as rtc0
[    1.433700] rtc_cmos 00:03: setting system clock to 2023-10-10T23:44:10 UTC (1696981450)
[    1.433750] rtc_cmos 00:03: alarms up to one month, y3k, 242 bytes nvram
[    1.434053] intel_pstate: Intel P-state driver initializing
[    1.434542] intel_pstate: HWP enabled
[    1.434667] ledtrig-cpu: registered to indicate activity on CPUs
[    1.435844] [drm] Initialized simpledrm 1.0.0 20200625 for simple-framebuffer.0 on minor 0
[    1.442314] Console: switching to colour frame buffer device 240x67
[    1.447906] simple-framebuffer simple-framebuffer.0: [drm] fb0: simpledrmdrmfb frame buffer device
[    1.448012] hid: raw HID events driver (C) Jiri Kosina
[    1.448123] intel_pmc_core INT33A1:00:  initialized
[    1.448272] drop_monitor: Initializing network drop monitor service
[    1.536242] Initializing XFRM netlink socket
[    1.536423] NET: Registered PF_INET6 protocol family
[    1.541894] Segment Routing with IPv6
[    1.541906] RPL Segment Routing with IPv6
[    1.541965] In-situ OAM (IOAM) with IPv6
[    1.542123] NET: Registered PF_PACKET protocol family
[    1.544459] microcode: Microcode Update Driver: v2.2.
[    1.544490] IPI shorthand broadcast: enabled
[    1.557072] sched_clock: Marking stable (1550010888, 6259350)->(1632236946, -75966708)
[    1.557875] registered taskstats version 1
[    1.559077] Loading compiled-in X.509 certificates
[    1.575575] Loaded X.509 cert 'Build time autogenerated kernel key: 333e1bae8548937ea28bdd550a94d2aba8351419'
[    1.577014] zswap: loaded using pool zstd/zsmalloc
[    1.580799] Key type .fscrypt registered
[    1.580802] Key type fscrypt-provisioning registered
[    1.582336] integrity: Loading X.509 certificate: UEFI:db
[    1.582373] integrity: Loaded X.509 cert 'Dell Inc. UEFI DB: 5ddb772dc880660055ba0bc131886bb630a639e7'
[    1.582375] integrity: Loading X.509 certificate: UEFI:db
[    1.582406] integrity: Loaded X.509 cert 'Microsoft Corporation UEFI CA 2011: 13adbf4309bd82709c8cd54f316ed522988a1bd4'
[    1.582408] integrity: Loading X.509 certificate: UEFI:db
[    1.582433] integrity: Loaded X.509 cert 'Microsoft Windows Production PCA 2011: a92902398e16c49778cd90f99e4f9ae17c55af53'
[    1.584835] PM:   Magic number: 11:900:756
[    1.584849] tty ttyS7: hash matches
[    1.591568] RAS: Correctable Errors collector initialized.
[    1.591660] clk: Disabling unused clocks
[    1.592840] Freeing unused decrypted memory: 2036K
[    1.593199] Freeing unused kernel image (initmem) memory: 3348K
[    1.613216] Write protecting the kernel read-only data: 30720k
[    1.613661] Freeing unused kernel image (rodata/data gap) memory: 1556K
[    1.646283] tsc: Refined TSC clocksource calibration: 1607.997 MHz
[    1.646288] clocksource: tsc: mask: 0xffffffffffffffff max_cycles: 0x172da757658, max_idle_ns: 440795229495 ns
[    1.646307] clocksource: Switched to clocksource tsc
[    1.661052] x86/mm: Checked W+X mappings: passed, no W+X pages found.
[    1.661056] rodata_test: all tests were successful
[    1.661057] x86/mm: Checking user space page tables
[    1.705682] x86/mm: Checked W+X mappings: passed, no W+X pages found.
[    1.705693] Run /init as init process
[    1.705694]   with arguments:
[    1.705695]     /init
[    1.705696]   with environment:
[    1.705697]     HOME=/
[    1.705698]     TERM=linux
[    1.705698]     BOOT_IMAGE=/arch/boot/x86_64/vmlinuz-linux
[    1.705699]     archisobasedir=arch
[    1.705700]     archisodevice=UUID=2023-09-01-10-45-56-00
[   10.236769] wmi_bus wmi_bus-PNP0C14:01: WQBC data block query control method not found
[   10.386964] rtsx_pci 0000:3b:00.0: enabling device (0000 -> 0002)
[   10.402580] cryptd: max_cpu_qlen set to 1000
[   10.403581] xhci_hcd 0000:00:14.0: xHCI Host Controller
[   10.403591] xhci_hcd 0000:00:14.0: new USB bus registered, assigned bus number 1
[   10.404697] xhci_hcd 0000:00:14.0: hcc params 0x200077c1 hci version 0x100 quirks 0x0000000081109810
[   10.405269] xhci_hcd 0000:00:14.0: xHCI Host Controller
[   10.405274] xhci_hcd 0000:00:14.0: new USB bus registered, assigned bus number 2
[   10.405278] xhci_hcd 0000:00:14.0: Host supports USB 3.0 SuperSpeed
[   10.405334] usb usb1: New USB device found, idVendor=1d6b, idProduct=0002, bcdDevice= 6.04
[   10.405338] usb usb1: New USB device strings: Mfr=3, Product=2, SerialNumber=1
[   10.405340] usb usb1: Product: xHCI Host Controller
[   10.405343] usb usb1: Manufacturer: Linux 6.4.12-arch1-1 xhci-hcd
[   10.405344] usb usb1: SerialNumber: 0000:00:14.0
[   10.411237] hub 1-0:1.0: USB hub found
[   10.411269] hub 1-0:1.0: 12 ports detected
[   10.420640] AVX2 version of gcm_enc/dec engaged.
[   10.420679] AES CTR mode by8 optimization enabled
[   10.421011] i8042: PNP: PS/2 Controller [PNP0303:PS2K,PNP0f13:PS2M] at 0x60,0x64 irq 1,12
[   10.426824] usb usb2: New USB device found, idVendor=1d6b, idProduct=0003, bcdDevice= 6.04
[   10.426829] usb usb2: New USB device strings: Mfr=3, Product=2, SerialNumber=1
[   10.426832] usb usb2: Product: xHCI Host Controller
[   10.426835] usb usb2: Manufacturer: Linux 6.4.12-arch1-1 xhci-hcd
[   10.426837] usb usb2: SerialNumber: 0000:00:14.0
[   10.427108] hub 2-0:1.0: USB hub found
[   10.427132] hub 2-0:1.0: 6 ports detected
[   10.427844] i8042: Warning: Keylock active
[   10.428369] usb: port power management may be unreliable
[   10.435123] serio: i8042 KBD port at 0x60,0x64 irq 1
[   10.446314] serio: i8042 AUX port at 0x60,0x64 irq 12
[   10.522897] input: AT Translated Set 2 keyboard as /devices/platform/i8042/serio0/input/input4
[   10.556239] nvme nvme0: pci function 0000:3a:00.0
[   10.564135] nvme nvme0: 4/0/0 default/read/poll queues
[   10.567411]  nvme0n1: p1 p2
[   10.669626] usb 1-2: new full-speed USB device number 2 using xhci_hcd
[   10.810700] usb 1-2: New USB device found, idVendor=8087, idProduct=0a2b, bcdDevice= 0.10
[   10.810704] usb 1-2: New USB device strings: Mfr=0, Product=0, SerialNumber=0
[   10.933015] usb 2-1: new SuperSpeed USB device number 2 using xhci_hcd
[   10.951390] usb 2-1: New USB device found, idVendor=090c, idProduct=1000, bcdDevice=11.00
[   10.951396] usb 2-1: New USB device strings: Mfr=1, Product=2, SerialNumber=3
[   10.951398] usb 2-1: Product: Flash Drive FIT
[   10.951399] usb 2-1: Manufacturer: Samsung
[   10.951400] usb 2-1: SerialNumber: 0378622040001607
[   10.956358] Console: switching to colour dummy device 80x25
[   10.976694] i915 0000:00:02.0: vgaarb: deactivate vga console
[   10.979280] i915 0000:00:02.0: vgaarb: changed VGA decodes: olddecodes=io+mem,decodes=io+mem:owns=io+mem
[   10.980338] i915 0000:00:02.0: [drm] Finished loading DMC firmware i915/kbl_dmc_ver1_04.bin (v1.4)
[   11.025548] i915 0000:00:02.0: [drm] [ENCODER:102:DDI B/PHY B] is disabled/in DSI mode with an ungated DDI clock, gate it
[   11.034300] i915 0000:00:02.0: [drm] [ENCODER:118:DDI C/PHY C] is disabled/in DSI mode with an ungated DDI clock, gate it
[   11.058906] [drm] Initialized i915 1.6.0 20201103 for 0000:00:02.0 on minor 1
[   11.068462] ACPI: video: Video Device [GFX0] (multi-head: yes  rom: no  post: no)
[   11.070221] input: Video Bus as /devices/LNXSYSTM:00/LNXSYBUS:00/PNP0A08:00/LNXVIDEO:00/input/input6
[   11.076330] usb 1-7: new full-speed USB device number 3 using xhci_hcd
[   11.096255] usb-storage 2-1:1.0: USB Mass Storage device detected
[   11.096712] scsi host0: usb-storage 2-1:1.0
[   11.096990] usbcore: registered new interface driver usb-storage
[   11.218564] usb 1-7: New USB device found, idVendor=138a, idProduct=0091, bcdDevice= 1.64
[   11.218570] usb 1-7: New USB device strings: Mfr=0, Product=0, SerialNumber=1
[   11.218572] usb 1-7: SerialNumber: fbe4b8075709
[   11.279970] fbcon: i915drmfb (fb0) is primary device
[   11.302642] Console: switching to colour frame buffer device 240x67
[   11.320890] i915 0000:00:02.0: [drm] fb0: i915drmfb frame buffer device
[   11.343676] usbcore: registered new interface driver uas
[   11.619668] usb 1-9: new high-speed USB device number 4 using xhci_hcd
[   11.810491] usb 1-9: New USB device found, idVendor=0bda, idProduct=58c8, bcdDevice=67.15
[   11.810497] usb 1-9: New USB device strings: Mfr=3, Product=1, SerialNumber=2
[   11.810498] usb 1-9: Product: Integrated_Webcam_HD
[   11.810500] usb 1-9: Manufacturer: CN05DX887248775I0396A00
[   11.810501] usb 1-9: SerialNumber: 200901010001
[   12.744587] scsi 0:0:0:0: Direct-Access     Samsung  Flash Drive FIT  1100 PQ: 0 ANSI: 6
[   12.745425] sd 0:0:0:0: [sda] 250626566 512-byte logical blocks: (128 GB/120 GiB)
[   12.745598] sd 0:0:0:0: [sda] Write Protect is off
[   12.745607] sd 0:0:0:0: [sda] Mode Sense: 43 00 00 00
[   12.745758] sd 0:0:0:0: [sda] Write cache: enabled, read cache: enabled, doesn't support DPO or FUA
[   12.754591]  sda: sda1 sda2
[   12.754874] sd 0:0:0:0: [sda] Attached SCSI removable disk
[   12.992450] device-mapper: uevent: version 1.0.3
[   12.992561] device-mapper: ioctl: 4.48.0-ioctl (2023-03-01) initialised: dm-devel@redhat.com
[   13.111976] ISO 9660 Extensions: Microsoft Joliet Level 3
[   13.112610] ISO 9660 Extensions: RRIP_1991A
[   15.732586] loop: module loaded
[   15.733170] loop0: detected capacity change from 0 to 1397960
[   15.743482] squashfs: version 4.0 (2009/01/31) Phillip Lougher
[   15.757671] overlayfs: "xino" feature enabled using 2 upper inode bits.
[   16.910982] systemd[1]: systemd 254.1-1-arch running in system mode (+PAM +AUDIT -SELINUX -APPARMOR -IMA +SMACK +SECCOMP +GCRYPT +GNUTLS +OPENSSL +ACL +BLKID +CURL +ELFUTILS +FIDO2 +IDN2 -IDN +IPTC +KMOD +LIBCRYPTSETUP +LIBFDISK +PCRE2 -PWQUALITY +P11KIT -QRENCODE +TPM2 +BZIP2 +LZ4 +XZ +ZLIB +ZSTD +BPF_FRAMEWORK +XKBCOMMON +UTMP -SYSVINIT default-hierarchy=unified)
[   16.910989] systemd[1]: Detected architecture x86-64.
[   16.935779] systemd[1]: Detected first boot.
[   16.961229] systemd[1]: Hostname set to <archiso>.
[   16.962473] systemd[1]: Initializing machine ID from random generator.
[   17.173169] systemd[1]: bpf-lsm: LSM BPF program attached
[   18.187682] systemd[1]: Populated /etc with preset unit settings.
[   18.291030] systemd[1]: Queued start job for default target Graphical Interface.
[   18.319939] systemd[1]: Created slice Slice /system/getty.
[   18.321328] systemd[1]: Created slice Slice /system/modprobe.
[   18.322319] systemd[1]: Created slice User and Session Slice.
[   18.322778] systemd[1]: Started Dispatch Password Requests to Console Directory Watch.
[   18.323250] systemd[1]: Started Forward Password Requests to Wall Directory Watch.
[   18.324000] systemd[1]: Set up automount Arbitrary Executable File Formats File System Automount Point.
[   18.324302] systemd[1]: Reached target Local Encrypted Volumes.
[   18.324580] systemd[1]: Reached target Local Integrity Protected Volumes.
[   18.324875] systemd[1]: Reached target Path Units.
[   18.325118] systemd[1]: Reached target Remote Encrypted Volumes.
[   18.325358] systemd[1]: Reached target Remote File Systems.
[   18.325597] systemd[1]: Reached target Slice Units.
[   18.325848] systemd[1]: Reached target Swaps.
[   18.326108] systemd[1]: Reached target Local Verity Protected Volumes.
[   18.326597] systemd[1]: Listening on Device-mapper event daemon FIFOs.
[   18.330946] systemd[1]: Listening on LVM2 poll daemon socket.
[   18.335909] systemd[1]: Listening on Process Core Dump Socket.
[   18.336517] systemd[1]: Listening on Journal Audit Socket.
[   18.336871] systemd[1]: Listening on Journal Socket (/dev/log).
[   18.337234] systemd[1]: Listening on Journal Socket.
[   18.337671] systemd[1]: Listening on Network Service Netlink Socket.
[   18.339169] systemd[1]: Listening on udev Control Socket.
[   18.339502] systemd[1]: Listening on udev Kernel Socket.
[   18.339943] systemd[1]: Listening on User Database Manager Socket.
[   18.341568] systemd[1]: Mounting Huge Pages File System...
[   18.343120] systemd[1]: Mounting POSIX Message Queue File System...
[   18.344970] systemd[1]: Mounting Kernel Debug File System...
[   18.346462] systemd[1]: Mounting Kernel Trace File System...
[   18.347860] systemd[1]: Mounting Temporary Directory /tmp...
[   18.368701] systemd[1]: Starting Create List of Static Device Nodes...
[   18.369858] systemd[1]: Starting Monitoring of LVM2 mirrors, snapshots etc. using dmeventd or progress polling...
[   18.371603] systemd[1]: Starting Load Kernel Module configfs...
[   18.373089] systemd[1]: Starting Load Kernel Module dm_mod...
[   18.374864] systemd[1]: Starting Load Kernel Module drm...
[   18.376434] systemd[1]: Starting Load Kernel Module efi_pstore...
[   18.377896] systemd[1]: Starting Load Kernel Module fuse...
[   18.380396] systemd[1]: Starting Load Kernel Module loop...
[   18.385705] systemd[1]: Starting Journal Service...
[   18.526042] fuse: init (API version 7.38)
[   18.546466] systemd[1]: Starting Load Kernel Modules...
[   18.548343] systemd[1]: Starting Generate network units from Kernel command line...
[   18.548947] systemd[1]: TPM2 PCR Machine ID Measurement was skipped because of an unmet condition check (ConditionPathExists=/sys/firmware/efi/efivars/StubPcrKernelImage-4a67b082-0a4c-41cf-b6c7-440b29bb8c4f).
[   18.550128] systemd[1]: Starting Remount Root and Kernel File Systems...
[   18.551839] systemd[1]: Starting Wait Until Kernel Time Synchronized...
[   18.554006] systemd[1]: Starting Coldplug All udev Devices...
[   18.557497] systemd[1]: Mounted Huge Pages File System.
[   18.558614] systemd[1]: Mounted POSIX Message Queue File System.
[   18.559715] systemd[1]: Mounted Kernel Debug File System.
[   18.560823] systemd[1]: Mounted Kernel Trace File System.
[   18.561922] systemd[1]: Mounted Temporary Directory /tmp.
[   18.574256] systemd-journald[405]: Collecting audit messages is enabled.
[   18.589811] systemd[1]: Finished Create List of Static Device Nodes.
[   18.591428] audit: type=1130 audit(1696981467.652:2): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=kmod-static-nodes comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=success'
[   18.591852] systemd[1]: modprobe@configfs.service: Deactivated successfully.
[   18.606479] systemd[1]: Finished Load Kernel Module configfs.
[   18.607017] audit: type=1130 audit(1696981467.669:3): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=modprobe@configfs comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=success'
[   18.607034] audit: type=1131 audit(1696981467.669:4): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=modprobe@configfs comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=success'
[   18.607353] systemd[1]: modprobe@dm_mod.service: Deactivated successfully.
[   18.623159] systemd[1]: Finished Load Kernel Module dm_mod.
[   18.624263] audit: type=1130 audit(1696981467.685:5): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=modprobe@dm_mod comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=success'
[   18.624277] audit: type=1131 audit(1696981467.685:6): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=modprobe@dm_mod comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=success'
[   18.624413] systemd[1]: Started Journal Service.
[   18.625526] audit: type=1130 audit(1696981467.685:7): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=systemd-journald comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=success'
[   18.647307] audit: type=1130 audit(1696981467.709:8): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=modprobe@drm comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=success'
[   18.647314] audit: type=1131 audit(1696981467.709:9): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=modprobe@drm comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=success'
[   18.675343] audit: type=1130 audit(1696981467.735:10): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=modprobe@efi_pstore comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=success'
[   18.675386] audit: type=1131 audit(1696981467.735:11): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=modprobe@efi_pstore comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=success'
[   18.819979] Asymmetric key parser 'pkcs8' registered
[   18.964467] systemd-journald[405]: Received client request to flush runtime journal.
[   20.964064] cfg80211: Loading compiled-in X.509 certificates for regulatory database
[   20.964305] Loaded X.509 cert 'sforshee: 00b28ddf47aef9cea7'
[   21.273446] i801_smbus 0000:00:1f.4: enabling device (0000 -> 0003)
[   21.273665] i801_smbus 0000:00:1f.4: SPD Write Disable is set
[   21.273701] i801_smbus 0000:00:1f.4: SMBus using PCI interrupt
[   21.273799] pci 0000:00:1f.1: [8086:9d20] type 00 class 0x058000
[   21.273863] pci 0000:00:1f.1: reg 0x10: [mem 0xfd000000-0xfdffffff 64bit]
[   21.311917] i2c i2c-6: 2/2 memory slots populated (from DMI)
[   21.577573] intel_ish_ipc 0000:00:13.0: enabling device (0000 -> 0002)
[   21.609637] intel-lpss 0000:00:15.0: enabling device (0000 -> 0002)
[   21.609948] idma64 idma64.0: Found Intel integrated DMA 64-bit
[   21.657064] intel-lpss 0000:00:15.1: enabling device (0000 -> 0002)
[   21.657951] idma64 idma64.1: Found Intel integrated DMA 64-bit
[   22.153489] Consider using thermal netlink events interface
[   22.182481] mei_me 0000:00:16.0: enabling device (0004 -> 0006)
[   22.401457] input: Intel Virtual Buttons as /devices/pci0000:00/0000:00:1f.0/PNP0C09:00/INT33D6:00/input/input7
[   22.402872] input: Intel Virtual Switches as /devices/pci0000:00/0000:00:1f.0/PNP0C09:00/INT33D6:00/input/input8
[   22.404934] input: DLL077A:01 06CB:76AF Mouse as /devices/pci0000:00/0000:00:15.1/i2c_designware.1/i2c-8/i2c-DLL077A:01/0018:06CB:76AF.0001/input/input9
[   22.405035] input: DLL077A:01 06CB:76AF Touchpad as /devices/pci0000:00/0000:00:15.1/i2c_designware.1/i2c-8/i2c-DLL077A:01/0018:06CB:76AF.0001/input/input10
[   22.405142] hid-generic 0018:06CB:76AF.0001: input,hidraw0: I2C HID v1.00 Mouse [DLL077A:01 06CB:76AF] on i2c-DLL077A:01
[   22.418756] input: WCOM482F:00 056A:482F Touchscreen as /devices/pci0000:00/0000:00:15.0/i2c_designware.0/i2c-7/i2c-WCOM482F:00/0018:056A:482F.0002/input/input12
[   22.418832] input: WCOM482F:00 056A:482F as /devices/pci0000:00/0000:00:15.0/i2c_designware.0/i2c-7/i2c-WCOM482F:00/0018:056A:482F.0002/input/input13
[   22.418880] input: WCOM482F:00 056A:482F Stylus as /devices/pci0000:00/0000:00:15.0/i2c_designware.0/i2c-7/i2c-WCOM482F:00/0018:056A:482F.0002/input/input14
[   22.418919] input: WCOM482F:00 056A:482F as /devices/pci0000:00/0000:00:15.0/i2c_designware.0/i2c-7/i2c-WCOM482F:00/0018:056A:482F.0002/input/input15
[   22.418960] input: WCOM482F:00 056A:482F Mouse as /devices/pci0000:00/0000:00:15.0/i2c_designware.0/i2c-7/i2c-WCOM482F:00/0018:056A:482F.0002/input/input16
[   22.419009] hid-generic 0018:056A:482F.0002: input,hidraw1: I2C HID v1.00 Mouse [WCOM482F:00 056A:482F] on i2c-WCOM482F:00
[   22.452439] Intel(R) Wireless WiFi driver for Linux
[   22.452803] iwlwifi 0000:3c:00.0: enabling device (0000 -> 0002)
[   22.464920] iwlwifi 0000:3c:00.0: Detected crf-id 0xbadcafe, cnv-id 0x10 wfpm id 0x80000000
[   22.465057] iwlwifi 0000:3c:00.0: PCI dev 24fd/8050, rev=0x230, rfid=0xd55555d5
[   22.512516] acpi INT33D5:00: intel-hid: created platform device
[   22.512775] input: Intel HID events as /devices/platform/INT33D5:00/input/input17
[   22.662880] input: PC Speaker as /devices/platform/pcspkr/input/input18
[   22.687637] iwlwifi 0000:3c:00.0: loaded firmware version 36.ca7b901d.0 8265-36.ucode op_mode iwlmvm
[   23.131502] wl: loading out-of-tree module taints kernel.
[   23.131509] wl: module license 'MIXED/Proprietary' taints kernel.
[   23.131511] Disabling lock debugging due to kernel taint
[   23.131512] wl: module verification failed: signature and/or required key missing - tainting kernel
[   23.131513] wl: module license taints kernel.
[   23.317390] mc: Linux media interface: v0.10
[   23.317411] input: Dell WMI hotkeys as /devices/platform/PNP0C14:01/wmi_bus/wmi_bus-PNP0C14:01/9DBB5994-A997-11DA-B012-B622A1EF5492/input/input19
[   23.475492] proc_thermal 0000:00:04.0: enabling device (0000 -> 0002)
[   23.479664] intel_rapl_common: Found RAPL domain package
[   23.479667] intel_rapl_common: Found RAPL domain dram
[   23.487627] iTCO_vendor_support: vendor-support=0
[   23.487733] intel_rapl_common: Found RAPL domain package
[   23.487736] intel_rapl_common: Found RAPL domain core
[   23.487739] intel_rapl_common: Found RAPL domain uncore
[   23.487741] intel_rapl_common: Found RAPL domain dram
[   23.487742] intel_rapl_common: Found RAPL domain psys
[   23.490647] videodev: Linux video capture interface: v2.00
[   23.499609] ish-hid {33AECD58-B679-4E54-9BD9-A04D34F0C226}: [hid-ish]: enum_devices_done OK, num_hid_devices=5
[   23.521240] hid-generic 001F:8086:0001.0003: hidraw2: SENSOR HUB HID v2.00 Device [hid-ishtp 8086:0001] on 
[   23.543244] hid-generic 001F:8086:0001.0004: hidraw0: SENSOR HUB HID v2.00 Device [hid-ishtp 8086:0001] on 
[   23.552402] hid-generic 001F:8086:0001.0005: hidraw3: SENSOR HUB HID v2.00 Device [hid-ishtp 8086:0001] on 
[   23.553391] input: DLL077A:01 06CB:76AF Mouse as /devices/pci0000:00/0000:00:15.1/i2c_designware.1/i2c-8/i2c-DLL077A:01/0018:06CB:76AF.0001/input/input21
[   23.554015] input: DLL077A:01 06CB:76AF Touchpad as /devices/pci0000:00/0000:00:15.1/i2c_designware.1/i2c-8/i2c-DLL077A:01/0018:06CB:76AF.0001/input/input22
[   23.554115] hid-multitouch 0018:06CB:76AF.0001: input,hidraw4: I2C HID v1.00 Mouse [DLL077A:01 06CB:76AF] on i2c-DLL077A:01
[   23.564168] hid-generic 001F:8087:0AC3.0006: hidraw5: SENSOR HUB HID v2.00 Device [hid-ishtp 8087:0AC3] on 
[   23.569141] hid-generic 001F:8087:0AC3.0007: hidraw6: SENSOR HUB HID v2.00 Device [hid-ishtp 8087:0AC3] on 
[   23.577446] mei_hdcp 0000:00:16.0-b638ab7e-94e2-4ea2-a552-d1c54b627f04: bound 0000:00:02.0 (ops i915_hdcp_ops [i915])
[   23.635814] RAPL PMU: API unit is 2^-32 Joules, 5 fixed counters, 655360 ms ovfl timer
[   23.635820] RAPL PMU: hw unit of domain pp0-core 2^-14 Joules
[   23.635822] RAPL PMU: hw unit of domain package 2^-14 Joules
[   23.635824] RAPL PMU: hw unit of domain dram 2^-14 Joules
[   23.635825] RAPL PMU: hw unit of domain pp1-gpu 2^-14 Joules
[   23.635827] RAPL PMU: hw unit of domain psys 2^-14 Joules
[   23.880834] iTCO_wdt iTCO_wdt: Found a Intel PCH TCO device (Version=4, TCOBASE=0x0400)
[   23.880989] iTCO_wdt iTCO_wdt: initialized. heartbeat=30 sec (nowayout=0)
[   23.883950] mousedev: PS/2 mouse device common for all mice
[   23.884584] usbcore: registered new interface driver usbhid
[   23.884587] usbhid: USB HID core driver
[   23.932014] iwlwifi 0000:3c:00.0: Detected Intel(R) Dual Band Wireless AC 8265, REV=0x230
[   23.932137] thermal thermal_zone10: failed to read out thermal zone (-61)
[   23.998249] iwlwifi 0000:3c:00.0: base HW address: f8:63:3f:58:b3:26, OTP minor version: 0x4
[   24.019094] kauditd_printk_skb: 37 callbacks suppressed
[   24.019098] audit: type=1130 audit(1696981473.079:49): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=systemd-backlight@leds:dell::kbd_backlight comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=success'
[   24.024460] Bluetooth: Core ver 2.22
[   24.024488] NET: Registered PF_BLUETOOTH protocol family
[   24.024490] Bluetooth: HCI device and connection manager initialized
[   24.024495] Bluetooth: HCI socket layer initialized
[   24.024498] Bluetooth: L2CAP socket layer initialized
[   24.024504] Bluetooth: SCO socket layer initialized
[   24.026607] snd_hda_intel 0000:00:1f.3: DSP detected with PCI class/subclass/prog-if info 0x040380
[   24.026643] snd_hda_intel 0000:00:1f.3: enabling device (0000 -> 0002)
[   24.026946] snd_hda_intel 0000:00:1f.3: bound 0000:00:02.0 (ops i915_audio_component_bind_ops [i915])
[   24.030350] usb 1-9: Found UVC 1.00 device Integrated_Webcam_HD (0bda:58c8)
[   24.043068] usb 1-9: Found UVC 1.00 device Integrated_Webcam_HD (0bda:58c8)
[   24.045368] usbcore: registered new interface driver uvcvideo
[   24.074825] ieee80211 phy0: Selected rate control algorithm 'iwl-mvm-rs'
[   24.216582] snd_hda_codec_realtek hdaudioC0D0: autoconfig for ALC3271: line_outs=1 (0x17/0x0/0x0/0x0/0x0) type:speaker
[   24.216593] snd_hda_codec_realtek hdaudioC0D0:    speaker_outs=0 (0x0/0x0/0x0/0x0/0x0)
[   24.216597] snd_hda_codec_realtek hdaudioC0D0:    hp_outs=1 (0x21/0x0/0x0/0x0/0x0)
[   24.216602] snd_hda_codec_realtek hdaudioC0D0:    mono: mono_out=0x0
[   24.216604] snd_hda_codec_realtek hdaudioC0D0:    inputs:
[   24.216607] snd_hda_codec_realtek hdaudioC0D0:      Headset Mic=0x19
[   24.216611] snd_hda_codec_realtek hdaudioC0D0:      Headphone Mic=0x1b
[   24.216614] snd_hda_codec_realtek hdaudioC0D0:      Internal Mic=0x12
[   24.222186] usbcore: registered new interface driver btusb
[   24.224170] Bluetooth: hci0: Bootloader revision 0.0 build 26 week 38 2015
[   24.225175] Bluetooth: hci0: Device revision is 16
[   24.225179] Bluetooth: hci0: Secure boot is enabled
[   24.225182] Bluetooth: hci0: OTP lock is enabled
[   24.225184] Bluetooth: hci0: API lock is enabled
[   24.225185] Bluetooth: hci0: Debug lock is disabled
[   24.225187] Bluetooth: hci0: Minimum firmware build 1 week 10 2014
[   24.320766] Bluetooth: hci0: Found device firmware: intel/ibt-12-16.sfi
[   24.362344] input: Wacom HID 482F Pen as /devices/pci0000:00/0000:00:15.0/i2c_designware.0/i2c-7/i2c-WCOM482F:00/0018:056A:482F.0002/input/input24
[   24.362697] input: Wacom HID 482F Finger as /devices/pci0000:00/0000:00:15.0/i2c_designware.0/i2c-7/i2c-WCOM482F:00/0018:056A:482F.0002/input/input25
[   24.363181] wacom 0018:056A:482F.0002: hidraw0: I2C HID v1.00 Mouse [WCOM482F:00 056A:482F] on i2c-WCOM482F:00
[   24.422338] iwlwifi 0000:3c:00.0: Registered PHC clock: iwlwifi-PTP, with index: 0
[   24.551235] audit: type=1130 audit(1696981473.612:50): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=systemd-rfkill comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=success'
[   25.254937] input: HDA Intel PCH Headphone Mic as /devices/pci0000:00/0000:00:1f.3/sound/card0/input27
[   25.255044] input: HDA Intel PCH HDMI/DP,pcm=3 as /devices/pci0000:00/0000:00:1f.3/sound/card0/input28
[   25.255137] input: HDA Intel PCH HDMI/DP,pcm=7 as /devices/pci0000:00/0000:00:1f.3/sound/card0/input29
[   25.255245] input: HDA Intel PCH HDMI/DP,pcm=8 as /devices/pci0000:00/0000:00:1f.3/sound/card0/input30
[   25.529379] intel_tcc_cooling: Programmable TCC Offset detected
[   25.677096] audit: type=1130 audit(1696981474.735:51): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=systemd-vconsole-setup comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=success'
[   25.808296] Bluetooth: hci0: Waiting for firmware download to complete
[   25.809180] Bluetooth: hci0: Firmware loaded in 1453521 usecs
[   25.809274] Bluetooth: hci0: Waiting for device to boot
[   25.822144] Bluetooth: hci0: Device booted in 12624 usecs
[   25.822151] Bluetooth: hci0: Malformed MSFT vendor event: 0x02
[   25.860096] Bluetooth: hci0: Found Intel DDC parameters: intel/ibt-12-16.ddc
[   25.863205] Bluetooth: hci0: Applying Intel DDC parameters completed
[   25.864204] Bluetooth: hci0: Firmware revision 0.1 build 19 week 44 2021
[   25.866194] Bluetooth: hci0: Reading supported features failed (-16)
[   25.866958] Bluetooth: hci0: Error reading debug features
[   26.239509] audit: type=1130 audit(1696981475.299:52): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=modprobe@dm_mod comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=success'
[   26.239518] audit: type=1131 audit(1696981475.299:53): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=modprobe@dm_mod comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=success'
[   26.267396] audit: type=1130 audit(1696981475.329:54): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=modprobe@efi_pstore comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=success'
[   26.267415] audit: type=1131 audit(1696981475.329:55): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=modprobe@efi_pstore comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=success'
[   26.286135] audit: type=1130 audit(1696981475.345:56): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=modprobe@loop comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=success'
[   26.286144] audit: type=1131 audit(1696981475.345:57): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=modprobe@loop comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=success'
[   26.320777] audit: type=1130 audit(1696981475.382:58): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=systemd-udev-settle comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=success'
[   29.493209] audit: type=1131 audit(1696981478.555:59): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=systemd-rfkill comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=success'
[   30.310376] audit: type=1130 audit(1696981479.375:60): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=ldconfig comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=success'
[   30.397583] audit: type=1130 audit(1696981479.462:61): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=systemd-update-done comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=success'
[   30.441722] audit: type=1334 audit(1696981479.505:62): prog-id=37 op=LOAD
[   30.445741] audit: type=1334 audit(1696981479.505:63): prog-id=38 op=LOAD
[   30.445928] audit: type=1334 audit(1696981479.505:64): prog-id=39 op=LOAD
[   30.446018] audit: type=1334 audit(1696981479.505:65): prog-id=40 op=LOAD
[   30.496982] audit: type=1334 audit(1696981479.559:66): prog-id=41 op=LOAD
[   30.497123] audit: type=1334 audit(1696981479.559:67): prog-id=42 op=LOAD
[   30.497184] audit: type=1334 audit(1696981479.559:68): prog-id=43 op=LOAD
[   30.644857] NET: Registered PF_ALG protocol family
[   31.368481] NET: Registered PF_QIPCRTR protocol family
[   36.731699] kauditd_printk_skb: 13 callbacks suppressed
[   36.731702] audit: type=1101 audit(1696981485.792:82): pid=677 uid=0 auid=4294967295 ses=4294967295 msg='op=PAM:accounting grantors=pam_access,pam_unix,pam_permit,pam_time acct="root" exe="/usr/bin/login" hostname=archiso addr=? terminal=/dev/tty1 res=success'
[   36.757206] audit: type=1103 audit(1696981485.819:83): pid=677 uid=0 auid=4294967295 ses=4294967295 msg='op=PAM:setcred grantors=pam_securetty,pam_shells,pam_faillock,pam_permit,pam_env,pam_faillock acct="root" exe="/usr/bin/login" hostname=archiso addr=? terminal=/dev/tty1 res=success'
[   36.757301] audit: type=1006 audit(1696981485.819:84): pid=677 uid=0 old-auid=4294967295 auid=0 tty=tty1 old-ses=4294967295 ses=1 res=1
[   36.757306] audit: type=1300 audit(1696981485.819:84): arch=c000003e syscall=1 success=yes exit=1 a0=4 a1=7ffcb022a880 a2=1 a3=0 items=0 ppid=1 pid=677 auid=0 uid=0 gid=0 euid=0 suid=0 fsuid=0 egid=0 sgid=0 fsgid=0 tty=tty1 ses=1 comm="login" exe="/usr/bin/login" key=(null)
[   36.757318] audit: type=1327 audit(1696981485.819:84): proctitle=2F62696E2F6C6F67696E002D70002D66002D2D
[   36.877565] audit: type=1130 audit(1696981485.942:85): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=user-runtime-dir@0 comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=success'
[   36.945922] audit: type=1101 audit(1696981486.005:86): pid=683 uid=0 auid=4294967295 ses=4294967295 msg='op=PAM:accounting grantors=pam_access,pam_unix,pam_permit,pam_time acct="root" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=success'
[   36.945978] audit: type=1103 audit(1696981486.005:87): pid=683 uid=0 auid=4294967295 ses=4294967295 msg='op=PAM:setcred grantors=? acct="root" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[   36.946064] audit: type=1006 audit(1696981486.005:88): pid=683 uid=0 old-auid=4294967295 auid=0 tty=(none) old-ses=4294967295 ses=2 res=1
[   36.946067] audit: type=1300 audit(1696981486.005:88): arch=c000003e syscall=1 success=yes exit=1 a0=9 a1=7ffe381cbbc0 a2=1 a3=0 items=0 ppid=1 pid=683 auid=0 uid=0 gid=0 euid=0 suid=0 fsuid=0 egid=0 sgid=0 fsgid=0 tty=(none) ses=2 comm="(systemd)" exe="/usr/lib/systemd/systemd" key=(null)
[  143.127579] kauditd_printk_skb: 65 callbacks suppressed
[  143.127587] audit: type=1130 audit(1696981592.192:123): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=systemd-networkd-wait-online comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  143.130371] audit: type=1334 audit(1696981592.192:124): prog-id=60 op=LOAD
[  145.753794] audit: type=1130 audit(1696981594.819:125): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  145.780022] audit: type=1334 audit(1696981594.845:126): prog-id=60 op=UNLOAD
[  155.853876] audit: type=1334 audit(1696981604.915:127): prog-id=61 op=LOAD
[  156.037014] audit: type=1130 audit(1696981605.102:128): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  156.053330] audit: type=1334 audit(1696981605.119:129): prog-id=61 op=UNLOAD
[  166.102839] audit: type=1334 audit(1696981615.162:130): prog-id=62 op=LOAD
[  166.280376] audit: type=1130 audit(1696981615.345:131): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  166.293284] audit: type=1334 audit(1696981615.359:132): prog-id=62 op=UNLOAD
[  176.353868] audit: type=1334 audit(1696981625.415:133): prog-id=63 op=LOAD
[  176.537127] audit: type=1130 audit(1696981625.602:134): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  176.560128] audit: type=1334 audit(1696981625.625:135): prog-id=63 op=UNLOAD
[  186.602709] audit: type=1334 audit(1696981635.662:136): prog-id=64 op=LOAD
[  186.783765] audit: type=1130 audit(1696981635.849:137): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  186.806666] audit: type=1334 audit(1696981635.872:138): prog-id=64 op=UNLOAD
[  196.852693] audit: type=1334 audit(1696981645.912:139): prog-id=65 op=LOAD
[  197.033691] audit: type=1130 audit(1696981646.099:140): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  197.056621] audit: type=1334 audit(1696981646.122:141): prog-id=65 op=UNLOAD
[  207.103866] audit: type=1334 audit(1696981656.165:142): prog-id=66 op=LOAD
[  207.283616] audit: type=1130 audit(1696981656.349:143): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  207.313294] audit: type=1334 audit(1696981656.379:144): prog-id=66 op=UNLOAD
[  217.352720] audit: type=1334 audit(1696981666.412:145): prog-id=67 op=LOAD
[  217.533643] audit: type=1130 audit(1696981666.599:146): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  217.566624] audit: type=1334 audit(1696981666.632:147): prog-id=67 op=UNLOAD
[  227.603601] audit: type=1334 audit(1696981676.665:148): prog-id=68 op=LOAD
[  227.787033] audit: type=1130 audit(1696981676.852:149): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  227.809904] audit: type=1334 audit(1696981676.875:150): prog-id=68 op=UNLOAD
[  237.852748] audit: type=1334 audit(1696981686.912:151): prog-id=69 op=LOAD
[  238.033757] audit: type=1130 audit(1696981687.099:152): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  238.053280] audit: type=1334 audit(1696981687.119:153): prog-id=69 op=UNLOAD
[  248.103453] audit: type=1334 audit(1696981697.165:154): prog-id=70 op=LOAD
[  248.283674] audit: type=1130 audit(1696981697.349:155): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  248.299907] audit: type=1334 audit(1696981697.365:156): prog-id=70 op=UNLOAD
[  258.352592] audit: type=1334 audit(1696981707.412:157): prog-id=71 op=LOAD
[  258.533656] audit: type=1130 audit(1696981707.599:158): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  258.563345] audit: type=1334 audit(1696981707.629:159): prog-id=71 op=UNLOAD
[  268.603056] audit: type=1334 audit(1696981717.665:160): prog-id=72 op=LOAD
[  268.787065] audit: type=1130 audit(1696981717.852:161): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  268.809973] audit: type=1334 audit(1696981717.875:162): prog-id=72 op=UNLOAD
[  278.853516] audit: type=1334 audit(1696981727.915:163): prog-id=73 op=LOAD
[  279.033712] audit: type=1130 audit(1696981728.099:164): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  279.066644] audit: type=1334 audit(1696981728.132:165): prog-id=73 op=UNLOAD
[  289.103215] audit: type=1334 audit(1696981738.165:166): prog-id=74 op=LOAD
[  289.276948] audit: type=1130 audit(1696981738.342:167): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  289.306567] audit: type=1334 audit(1696981738.372:168): prog-id=74 op=UNLOAD
[  299.353463] audit: type=1334 audit(1696981748.415:169): prog-id=75 op=LOAD
[  299.533705] audit: type=1130 audit(1696981748.599:170): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  299.556585] audit: type=1334 audit(1696981748.622:171): prog-id=75 op=UNLOAD
[  309.603112] audit: type=1334 audit(1696981758.665:172): prog-id=76 op=LOAD
[  309.797014] audit: type=1130 audit(1696981758.862:173): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  309.826595] audit: type=1334 audit(1696981758.892:174): prog-id=76 op=UNLOAD
[  319.853035] audit: type=1334 audit(1696981768.915:175): prog-id=77 op=LOAD
[  320.040366] audit: type=1130 audit(1696981769.105:176): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  320.063230] audit: type=1334 audit(1696981769.129:177): prog-id=77 op=UNLOAD
[  324.056879] usb 1-9: reset high-speed USB device number 4 using xhci_hcd
[  324.323116] usb 1-9: USB disconnect, device number 4
[  324.613848] usb 1-9: new high-speed USB device number 5 using xhci_hcd
[  325.573931] usb usb1-port9: Cannot enable. Maybe the USB cable is bad?
[  326.533157] usb usb1-port9: Cannot enable. Maybe the USB cable is bad?
[  326.533316] usb usb1-port9: attempt power cycle
[  327.566543] usb usb1-port9: Cannot enable. Maybe the USB cable is bad?
[  328.526580] usb usb1-port9: Cannot enable. Maybe the USB cable is bad?
[  328.526736] usb usb1-port9: unable to enumerate USB device
[  330.103786] audit: type=1334 audit(1696981779.165:178): prog-id=78 op=LOAD
[  330.293687] audit: type=1130 audit(1696981779.359:179): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  330.316570] audit: type=1334 audit(1696981779.382:180): prog-id=78 op=UNLOAD
[  340.352766] audit: type=1334 audit(1696981789.412:181): prog-id=79 op=LOAD
[  340.530380] audit: type=1130 audit(1696981789.595:182): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  340.553231] audit: type=1334 audit(1696981789.619:183): prog-id=79 op=UNLOAD
[  350.603781] audit: type=1334 audit(1696981799.665:184): prog-id=80 op=LOAD
[  350.783683] audit: type=1130 audit(1696981799.849:185): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  350.806615] audit: type=1334 audit(1696981799.872:186): prog-id=80 op=UNLOAD
[  360.852677] audit: type=1334 audit(1696981809.912:187): prog-id=81 op=LOAD
[  361.033659] audit: type=1130 audit(1696981810.099:188): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  361.056599] audit: type=1334 audit(1696981810.122:189): prog-id=81 op=UNLOAD
[  371.103033] audit: type=1334 audit(1696981820.165:190): prog-id=82 op=LOAD
[  371.290383] audit: type=1130 audit(1696981820.355:191): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  371.313289] audit: type=1334 audit(1696981820.379:192): prog-id=82 op=UNLOAD
[  381.353779] audit: type=1334 audit(1696981830.415:193): prog-id=83 op=LOAD
[  381.557053] audit: type=1130 audit(1696981830.622:194): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  381.579913] audit: type=1334 audit(1696981830.645:195): prog-id=83 op=UNLOAD
[  391.602973] audit: type=1334 audit(1696981840.665:196): prog-id=84 op=LOAD
[  391.790360] audit: type=1130 audit(1696981840.855:197): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  391.813266] audit: type=1334 audit(1696981840.879:198): prog-id=84 op=UNLOAD
[  401.852606] audit: type=1334 audit(1696981850.912:199): prog-id=85 op=LOAD
[  401.976192] usb 1-9: new high-speed USB device number 9 using xhci_hcd
[  402.046935] audit: type=1130 audit(1696981851.112:200): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  402.069911] audit: type=1334 audit(1696981851.135:201): prog-id=85 op=UNLOAD
[  402.160871] usb 1-9: New USB device found, idVendor=0bda, idProduct=58c8, bcdDevice=67.15
[  402.160886] usb 1-9: New USB device strings: Mfr=3, Product=1, SerialNumber=2
[  402.160892] usb 1-9: Product: Integrated_Webcam_HD
[  402.160897] usb 1-9: Manufacturer: CN05DX887248775I0396A00
[  402.160901] usb 1-9: SerialNumber: 200901010001
[  402.165644] usb 1-9: Found UVC 1.00 device Integrated_Webcam_HD (0bda:58c8)
[  402.175813] usb 1-9: Found UVC 1.00 device Integrated_Webcam_HD (0bda:58c8)
[  412.102740] audit: type=1334 audit(1696981861.162:202): prog-id=86 op=LOAD
[  412.276970] audit: type=1130 audit(1696981861.342:203): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  412.309956] audit: type=1334 audit(1696981861.375:204): prog-id=86 op=UNLOAD
[  422.352751] audit: type=1334 audit(1696981871.412:205): prog-id=87 op=LOAD
[  422.533614] audit: type=1130 audit(1696981871.599:206): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  422.549920] audit: type=1334 audit(1696981871.615:207): prog-id=87 op=UNLOAD
[  432.604241] audit: type=1334 audit(1696981881.665:208): prog-id=88 op=LOAD
[  432.796970] audit: type=1130 audit(1696981881.862:209): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  432.819919] audit: type=1334 audit(1696981881.885:210): prog-id=88 op=UNLOAD
[  442.852802] audit: type=1334 audit(1696981891.912:211): prog-id=89 op=LOAD
[  443.060313] audit: type=1130 audit(1696981892.125:212): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  443.083173] audit: type=1334 audit(1696981892.149:213): prog-id=89 op=UNLOAD
[  453.103698] audit: type=1334 audit(1696981902.165:214): prog-id=90 op=LOAD
[  453.283688] audit: type=1130 audit(1696981902.349:215): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  453.306577] audit: type=1334 audit(1696981902.372:216): prog-id=90 op=UNLOAD
[  463.352753] audit: type=1334 audit(1696981912.412:217): prog-id=91 op=LOAD
[  463.557009] audit: type=1130 audit(1696981912.622:218): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  463.579859] audit: type=1334 audit(1696981912.645:219): prog-id=91 op=UNLOAD
[  473.602782] audit: type=1334 audit(1696981922.662:220): prog-id=92 op=LOAD
[  473.780330] audit: type=1130 audit(1696981922.845:221): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  473.803087] audit: type=1334 audit(1696981922.869:222): prog-id=92 op=UNLOAD
[  483.853678] audit: type=1334 audit(1696981932.915:223): prog-id=93 op=LOAD
[  484.053691] audit: type=1130 audit(1696981933.119:224): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  484.073250] audit: type=1334 audit(1696981933.139:225): prog-id=93 op=UNLOAD
[  494.103103] audit: type=1334 audit(1696981943.165:226): prog-id=94 op=LOAD
[  494.317036] audit: type=1130 audit(1696981943.382:227): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  494.339883] audit: type=1334 audit(1696981943.405:228): prog-id=94 op=UNLOAD
[  504.354214] audit: type=1334 audit(1696981953.415:229): prog-id=95 op=LOAD
[  504.618319] audit: type=1130 audit(1696981953.682:230): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  504.633223] audit: type=1334 audit(1696981953.699:231): prog-id=95 op=UNLOAD
[  514.602776] audit: type=1334 audit(1696981963.662:232): prog-id=96 op=LOAD
[  514.780250] audit: type=1130 audit(1696981963.845:233): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  514.803254] audit: type=1334 audit(1696981963.869:234): prog-id=96 op=UNLOAD
[  524.852677] audit: type=1334 audit(1696981973.912:235): prog-id=97 op=LOAD
[  525.040255] audit: type=1130 audit(1696981974.105:236): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  525.076575] audit: type=1334 audit(1696981974.142:237): prog-id=97 op=UNLOAD
[  535.103505] audit: type=1334 audit(1696981984.165:238): prog-id=98 op=LOAD
[  535.310283] audit: type=1130 audit(1696981984.375:239): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  535.333186] audit: type=1334 audit(1696981984.399:240): prog-id=98 op=UNLOAD
[  545.353070] audit: type=1334 audit(1696981994.415:241): prog-id=99 op=LOAD
[  545.543661] audit: type=1130 audit(1696981994.609:242): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  545.566582] audit: type=1334 audit(1696981994.632:243): prog-id=99 op=UNLOAD
[  555.603728] audit: type=1334 audit(1696982004.665:244): prog-id=100 op=LOAD
[  555.780325] audit: type=1130 audit(1696982004.845:245): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  555.799880] audit: type=1334 audit(1696982004.865:246): prog-id=100 op=UNLOAD
[  565.853061] audit: type=1334 audit(1696982014.915:247): prog-id=101 op=LOAD
[  566.036943] audit: type=1130 audit(1696982015.102:248): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  566.059893] audit: type=1334 audit(1696982015.125:249): prog-id=101 op=UNLOAD
[  576.103731] audit: type=1334 audit(1696982025.165:250): prog-id=102 op=LOAD
[  576.283632] audit: type=1130 audit(1696982025.349:251): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  576.306516] audit: type=1334 audit(1696982025.372:252): prog-id=102 op=UNLOAD
[  586.352746] audit: type=1334 audit(1696982035.412:253): prog-id=103 op=LOAD
[  586.540316] audit: type=1130 audit(1696982035.605:254): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  586.559879] audit: type=1334 audit(1696982035.625:255): prog-id=103 op=UNLOAD
[  596.602717] audit: type=1334 audit(1696982045.662:256): prog-id=104 op=LOAD
[  596.816962] audit: type=1130 audit(1696982045.882:257): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=failed'
[  596.839807] audit: type=1334 audit(1696982045.905:258): prog-id=104 op=UNLOAD
[  599.399828] wlan0: authenticate with fc:34:97:22:75:74
[  599.413973] wlan0: send auth to fc:34:97:22:75:74 (try 1/3)
[  599.497174] wlan0: authenticate with fc:34:97:22:75:74
[  599.497181] wlan0: send auth to fc:34:97:22:75:74 (try 1/3)
[  599.525280] wlan0: authenticated
[  599.526237] wlan0: associate with fc:34:97:22:75:74 (try 1/3)
[  599.527596] wlan0: RX AssocResp from fc:34:97:22:75:74 (capab=0x1011 status=0 aid=27)
[  599.531720] wlan0: associated
[  599.591019] wlan0: Limiting TX power to 30 (30 - 0) dBm as advertised by fc:34:97:22:75:74
[  599.647398] IPv6: ADDRCONF(NETDEV_CHANGE): wlan0: link becomes ready
[  602.987607] audit: type=1334 audit(1696982052.049:259): prog-id=105 op=LOAD
[  602.987731] audit: type=1334 audit(1696982052.049:260): prog-id=106 op=LOAD
[  602.987820] audit: type=1334 audit(1696982052.049:261): prog-id=107 op=LOAD
[  603.083261] audit: type=1130 audit(1696982052.145:262): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=systemd-hostnamed comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=success'
[  606.852714] audit: type=1334 audit(1696982055.912:263): prog-id=108 op=LOAD
[  633.163460] audit: type=1131 audit(1696982082.225:264): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=systemd-hostnamed comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=success'
[  633.226300] audit: type=1334 audit(1696982082.289:265): prog-id=107 op=UNLOAD
[  633.226322] audit: type=1334 audit(1696982082.289:266): prog-id=106 op=UNLOAD
[  633.226333] audit: type=1334 audit(1696982082.289:267): prog-id=105 op=UNLOAD
[  633.254868] systemd-journald[405]: Time jumped backwards, rotating.
[  633.293356] audit: type=1130 audit(1696982056.410:268): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=systemd-time-wait-sync comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=success'
[  648.987011] audit: type=1130 audit(1696982072.104:269): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=pacman-init comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=success'
[  670.137215] audit: type=1130 audit(1696982093.253:270): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=success'
[  670.137228] audit: type=1131 audit(1696982093.253:271): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=reflector comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=success'
[  670.159970] audit: type=1334 audit(1696982093.277:272): prog-id=108 op=UNLOAD
[  909.489580] audit: type=1130 audit(1696982332.608:273): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=systemd-tmpfiles-clean comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=success'
[  909.489590] audit: type=1131 audit(1696982332.608:274): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=systemd-tmpfiles-clean comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=success'
[  989.351812] audit: type=1334 audit(1696982412.468:275): prog-id=109 op=LOAD
[  989.352259] audit: type=1334 audit(1696982412.471:276): prog-id=110 op=LOAD
[  989.352388] audit: type=1334 audit(1696982412.471:277): prog-id=111 op=LOAD
[  989.373466] audit: type=1130 audit(1696982412.491:278): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=shadow comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=success'
[  989.492449] audit: type=1131 audit(1696982412.611:279): pid=1 uid=0 auid=4294967295 ses=4294967295 msg='unit=shadow comm="systemd" exe="/usr/lib/systemd/systemd" hostname=? addr=? terminal=? res=success'
[  989.552201] audit: type=1334 audit(1696982412.671:280): prog-id=109 op=UNLOAD
[ 2999.905128] usb 1-9: USB disconnect, device number 9
[ 3001.030652] usb usb1-port9: Cannot enable. Maybe the USB cable is bad?
[ 3001.153984] usb 1-9: new high-speed USB device number 11 using xhci_hcd
[ 3001.337047] usb 1-9: New USB device found, idVendor=0bda, idProduct=58c8, bcdDevice=67.15
[ 3001.337062] usb 1-9: New USB device strings: Mfr=3, Product=1, SerialNumber=2
[ 3001.337068] usb 1-9: Product: Integrated_Webcam_HD
[ 3001.337073] usb 1-9: Manufacturer: CN05DX887248775I0396A00
[ 3001.337077] usb 1-9: SerialNumber: 200901010001
[ 3001.342065] usb 1-9: Found UVC 1.00 device Integrated_Webcam_HD (0bda:58c8)
[ 3001.350845] usb 1-9: Found UVC 1.00 device Integrated_Webcam_HD (0bda:58c8)
[ 6867.004116] usb 1-9: reset high-speed USB device number 11 using xhci_hcd
[ 6867.622135] usb 1-9: USB disconnect, device number 11
[ 6868.750471] usb usb1-port9: Cannot enable. Maybe the USB cable is bad?
[ 6869.710480] usb usb1-port9: Cannot enable. Maybe the USB cable is bad?
[ 6869.711994] usb usb1-port9: attempt power cycle
[ 6870.744500] usb usb1-port9: Cannot enable. Maybe the USB cable is bad?
[ 6871.704553] usb usb1-port9: Cannot enable. Maybe the USB cable is bad?
[ 6871.706412] usb usb1-port9: unable to enumerate USB device
[ 6942.431231] usb usb1-port9: Cannot enable. Maybe the USB cable is bad?
[ 6943.391244] usb usb1-port9: Cannot enable. Maybe the USB cable is bad?
[ 6943.392864] usb usb1-port9: attempt power cycle
[ 6944.424581] usb usb1-port9: Cannot enable. Maybe the USB cable is bad?
[ 6945.384558] usb usb1-port9: Cannot enable. Maybe the USB cable is bad?
[ 6945.386661] usb usb1-port9: unable to enumerate USB device
