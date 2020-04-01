# AMC FMC Carrier (AFC)

## Project description

The AMC FMC carrier is partially based on SPEC (supply, WR clocks)
design. It was primarily specified by the Brazilian Synchrotron Light
Laboratory ([LNLS](www.lnls.br)) and designed by Warsaw University of
Technology (WUT) to support quad 16-bit ADC FMC boards for Sirius BPM
electronics. Among many features, the card has very flexible clock
circuit that enables any clock source to be connected to any clock
input, including telecom clock, FMC clocks and
FPGA.

-----

![Top
view](https://www.ohwr.org/project/afc/uploads/28ef8b39ac0952926931bef84a25d8d5/AFC_TOP_v3_1.JPG)

![Bottom
view](https://www.ohwr.org/project/afc/uploads/5372faa7cec5cbc101eb8f5c0f0cfa8a/AFC_BOT_V3_1.JPG))

-----

## Functional specifications

  - Xilinx Artix-7 200T FFG1156 FPGA (XC7A200T-3FFG1156E)
  - 2 GB DDR3 SDRAM (32-bit interface)
  - 2 high pin count (HPC) slots for 2 single width mezzanines or 1
    double width mezzanine
  - SPI Flash for FPGA configuration
  - SPI Flash for user data storage
  - JTAG multiplexer (SCANSTA) for FMC access
  - Power supply for FPGA, memory, FMCs - programmable VADJ 1.8-3.3V
  - Clock distribution circuit compatible with WR
  - Temperature, voltage and current monitoring for critical power buses
  - Stand-alone power connector
  - Mini-USB connected to the IPMI processor
  - SATA connector for Port2, Port3 with possibility of switching to
    FPGA MGT
  - MGT connected to FMC1, FMC2, Fat Pipe 1, Fat Pipe 2 (optional),
    Port0, Port1, Port2 (optional), Port3 (optional), RTM (optional)
  - EEPROM with MAC and unique ID
  - RTM connector with 8 GTP routed to it. Compatible with rtm-sfp8
    module.

<!-- end list -->

  - [Users](Users)
  - [CERN-ACC-2014-0357](https://cds.cern.ch/record/1977919/files/CERN-ACC-2014-0357.pdf)

-----

## Contacts

### Commercial producers

  - [AMC FMC Carrier – AFC](http://creotech.pl/product-scientific/amc-fmc-carrier-afc) - [Creotech](http://creotech.pl), Poland

### General question about project

  - [Daniel Tavares (LNLS)](mailto:daniel.tavares@lnls.br)
  - [Filip Świtakowski (Creotech)](mailto:filip.switakowski@creotech.pl)

-----