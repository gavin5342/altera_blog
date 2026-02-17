# Agilex 5 packaging

Agilex 5 devices use two types of package 

- VPBGA packages = 0.65mm partially depopulated array
- MBGA packages = 0.5mm full array

The MBGA package allows greatest pin density but requires a HDI process for Type IV vias.  The [routing guidelines](https://docs.altera.com/r/docs/821801/current/pcb-design-guidelines-hssi-emif-mipi-true-differential-pdn-user-guide-agilextm-5-fpgas-and-socs/typical-design-rules-for-type-iv-hdi-in-a-0.5-mm-mbga) have a useful table to compare with your fabricator's capabilities.

The VPBGA package allows for high pin density while *not* requiring HDI.  The [Agilex 5 PCB guidelines](https://docs.altera.com/r/docs/821801/current/pcb-design-guidelines-hssi-emif-mipi-true-differential-pdn-user-guide-agilextm-5-fpgas-and-socs/) say that design rules are similar top those for 0.8mm BGAs on a Type III with standard PTH vias.

Avoiding the need for HDI and fine features is a benefit for fabrication time, cost and availability.

The VPBGA package 

[Agilex 5 board design](https://www.altera.com/design/agilex-5/design-hub/board)