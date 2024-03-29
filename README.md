# FPGA-PCIE-Card

**Current Revision: New Version Coming soon!**

This is a base design for an Artix-7 35T based FPGA card with PCIE and USB interface. This is meant to be a learning experience for me in high speed complex FPGA design.

Consider this project in its pre-Alpha stage with **ZERO testing and verification.** 
This whole design has been based on reference designs/guidance from Diligent, Xilinx, and FTDI.

**How to open:**
Download the "Artix Express V3 - NO DDR3" rar file. Extract it and open the folder. Open the "Artix Express.DsnWrk" file in altium. All files should open with it in the project. If not, they can be found in the project folder. 

This design is fully open source and free for anyone to use, copy, or whatever else you'd like. 

**Upcoming Changes:**
1. Improve PCIE layout
2. Add length matching for USB FIFO data lines
3. Add DDR3
4. Do final impedance matching for all critical data lines
5. Add KiCad files
6. General layout improvements

**Rev3 Board Design:**
![Rev3 Board](https://i.imgur.com/xOjqv3y.png)

All Datasheets and reference info can be found below: 

FT601:

**Datasheet:**
https://www.ftdichip.com/Support/Documents/DataSheets/ICs/DS_FT600Q-FT601Q%20IC%20Datasheet.pdf

**Layout Guidelines:**
https://www.ftdichip.com/Support/Documents/AppNotes/AN_430%20FT60X%20PCB%20Layout%20Guidelines.pdf

Arty-A7 Refrence Design:

https://reference.digilentinc.com/_media/reference/programmable-logic/arty-a7/arty_a7_sch.pdf

Xilinx 7-Series Documentation:

**Pinout:**
https://www.xilinx.com/support/documentation/user_guides/ug475_7Series_Pkg_Pinout.pdf

**Chip Overview:**
https://www.xilinx.com/support/documentation/data_sheets/ds180_7Series_Overview.pdf

**PCIE Setup:**
https://www.xilinx.com/support/documentation/ip_documentation/pcie_7x/v3_0/pg054-7series-pcie.pdf

**Using trancievers:**
https://www.xilinx.com/support/documentation/user_guides/ug482_7Series_GTP_Transceivers.pdf

**Artix-7 Datasheet:**
https://www.xilinx.com/support/documentation/data_sheets/ds181_Artix_7_Data_Sheet.pdf

**DDR Layout Guidelines:**
https://www.xilinx.com/support/documentation/white_papers/wp484-a7-s7-ddr2-3-pcb.pdf

**Desigining Custom Memory interface:**
https://www.xilinx.com/support/documentation/ip_documentation/ug586_7Series_MIS.pdf

