# tensorflow-g6
Tensorflow build for HP Pavilion g6 Notebook PC (B1R15EA#ABZ)

To install:

```bash
pip install tensorflow-<version-tags>.whl
```

lshw output

```bash
sudo lshw | grep product
```

```
    product: HP Pavilion g6 Notebook PC (B1R15EA#ABZ)
       product: 3567
             product: AD73I1C1674EV
             product: HMT325S6CFR8C-PB
          product: AMD A4-3305M APU with Radeon(tm) HD Graphics
          product: Family 12h Processor Root Complex
             product: Sumo [Radeon HD 6480G]
             product: BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]
             product: Family 12h Processor Root Port
                product: Seymour [Radeon HD 6400M/7400M Series]
             product: Family 12h Processor Root Port
                product: RTL8188CE 802.11b/g/n WiFi Adapter
             product: Family 12h Processor Root Port
                product: RTL810xE PCI Express Fast Ethernet controller
             product: Family 12h Processor Root Port
                product: RTS5209 PCI Express Card Reader
             product: FCH SATA Controller [AHCI mode]
             product: FCH USB OHCI Controller
                product: OHCI PCI host controller
                   product: USB Optical Mouse
             product: FCH USB EHCI Controller
                product: EHCI Host Controller
                   product: HP Webcam-101
             product: FCH USB OHCI Controller
                product: OHCI PCI host controller
             product: FCH USB EHCI Controller
                product: EHCI Host Controller
             product: FCH SMBus Controller
             product: FCH Azalia Controller
             product: FCH LPC Bridge
             product: FCH PCI Bridge
             product: FCH USB OHCI Controller
                product: OHCI PCI host controller
             product: FCH USB EHCI Controller
                product: EHCI Host Controller
          product: Family 12h/14h Processor Function 0
          product: Family 12h/14h Processor Function 1
          product: Family 12h/14h Processor Function 2
          product: Family 12h/14h Processor Function 3
          product: Family 12h/14h Processor Function 4
          product: Family 12h/14h Processor Function 6
          product: Family 12h/14h Processor Function 5
          product: Family 12h/14h Processor Function 7
             product: SanDisk SSD PLUS
             product: CDDVDW SN-208BB
       product: MU06047

```
