Sources:
https://www.storagereview.com/news/tegile-launches-t4000-series-of-all-flash-hybrid-arrays
more... lots of googling and datasheets.


Key specifications:

 ### All-Flash Models: T4500 | T4600 | T4700 | T4800

Form Factor: 2U

CPU: 4 x E5-2640 v3 | 4 x E5-2680 v3 | 4 x E5-2680 v3 | 4 x E5-2680 v3

Controllers: Dual-Active Controller Architecture

Memory: 240GB | 464GB | 464GB | 464GB

 #### Storage

- Capacity: 6TB | 12TB | 24TB | 46TB
- Effective Capacity: 22 – 1093TB | 44 – 1116TB | 88 – 1160TB | 170 -1241TB

 #### Network Connectivity

- Lights-out Management Ports: 2 x 1Gbps KVM over IP
- Storage Connectivity: 16 & 8Gbps Fibre Channel, 10GE Copper/Fibre & 1 Gbps Ethernet


Power: 439W | 495W | 495W | 495W

Weight: 80 lbs

 ### Hybrid Models: T4100 | T4200 | T4530 | T4630 | T4730 | T4760 | T4860

Form Factor: 3U | 3U | 5U | 5U | 8U | 5U | 5U

CPU: 4 x E5-2620 v3 | 4 x E5-2640 v3 | 4 x E5-2640 v3 | 4 x E5-2680 v3 | 4 x E5-2680 v3 | 4 x E5-2680 v3 | 4 x E5-2680 v3

Controllers: Dual-Active Controller Architecture

Memory: 256GB | 464GB | 240GB | 464GB | 464GB | 464GB | 464GB

 #### Storage

- Flash Capacity: 1.5TB | 5.8TB | 7.5TB | 17.8TB | 35.6TB | 25.5TB | 51.8TB
- Disk Capacity:  26TB | 52TB | 26TB | 52TB | 104TB | 26TB | 52TB
- Effective Flash Capacity: N/A | N/A | 22-917TB | 44-939TB | 88-804TB | 88-983TB | 170-1065TB
- Effective Hybrid Capacity: 60-780TB | 120-840TB | 60-660TB | 120-720TB | 240-720TB | 60-660TB | 120-720TB


 #### Network Connectivity
- Lights-out Management Ports: 2 x 1Gbps KVM over IP
- Storage Connectivity: 16 & 8Gbps Fibre Channel, 10GE Copper/Fibre & 1 Gbps Ethernet


Power: 423W | 441W | 635W | 691W | 887W | 691W | 691W

Weight: 105lbs | 105lbs | 185lbs | 185lbs | 290lbs | 185lbs | 185lbs



### Example Layout for 3.5" System:

T4200: 13x4TB Disk, 3x 1.92TB SSD




## Virtualization:

Running virtualized is an unknown field, there are some references for ESXi.
QEMU should be able to emulate the WHOLE platform (IPMI, UEFI, PCIe Switch)
Advice: Don't go down this road if you don't have a few days to investigate.
