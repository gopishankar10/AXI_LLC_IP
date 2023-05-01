# axi_llc_ip
Original axi_llc files as a standalone IP (for trace tests)

# For Utilisation/Comparision Analysis of IP on VIVADO, we have to force all SRAMs to BRAMs. Follow the steps below to achieve this

- include the "tc_sram_xilinx.sv" file from the following repository (https://github.com/pulp-platform/tech_cells_generic.git) into the source folder
- change the file name to "tc_sram" 
