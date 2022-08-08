# Advanced-Physical-Design-Workshop
Using Sky130 and OpenLane

### Useful Links:

* https://vsdiat.com/
* https://www.vlsisystemdesign.com/vsd-iat/
* https://www.udemy.com/course/vsd-a-complete-guide-to-install-openlane-and-sky130nm-pdk/
* https://www.udemy.com/course/vsd-a-complete-guide-to-install-open-source-eda-tools/
* https://github.com/Geetima2021/vsdpcvrd


## Introduction

### For end-to-end ASIC development:

#### RTL Designs

Open source options:

* librecores.org
* opencores.org
* github.com
* personal RTL

#### PDK Data

The first and most popular open source option is SKY130

* Only US-owned pure-play Silicon Foundry
* Sponsored by Google
* Latest: SKY90 announced

#### EDA Tools

Open source options:

* Qflow
* OpenROAD
* OpenLANE (from efabless.com) with support for SKY130, XFAB180, GF130G.

### RTL to GDSII:

1. Synthesis (using the Standard Cell Library)
2. Floor and Power Planning
3. Placement
4. Clock Tree Synthesis
5. Routing
6. Sign-off
* Physical Verification
* Timing Verification (STA)

## Floor and Power Planning

#### It is the arrangement of IPs and pre-placed cells in a chip.

#### Utilization Factor = (Area occupied by Netlist) / (Total Area of the core)

#### Aspect Ratio = (H of core) / (W of core)

#### Core is in the Die.

#### Surround pre-placed cells with decoupling capacitors.

#### Power Planning:

Multiple Vdd and Vss in a mesh to avoid ground bounce and voltage droop.

#### Pin Placement:



## Labs
