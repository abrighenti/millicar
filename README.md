# Millicar - An ns-3 Module for MmWave NR V2X Networks #

This is an [ns-3](https://www.nsnam.org "ns-3 Website") module for the simulation
of Vehicle-to-Vehicle networks operating at mmWaves.

This module currently includes features such as:
- support to the latest 3GPP channel model for V2X networks, for frequency spectrum above 6 GHz;
- custom PHY and MAC classes, supporting the NR frame structure specified by 3GPP;
- full-stack operations including those from RLC and PDCP layers, thanks to the integration with the LTE module of ns-3;
- helpers and examples to guide users that want to interact with the module
- support for CSMA scheme in scenarios with two platoons of [2, 10] vehicles each, in which there is one receiver per platoon

If you use this module in your research, please cite:
M. Drago, T. Zugno, M. Polese, M. Giordani, M. Zorzi, _"Millicar - An ns-3 Module for MmWave NR V2X Networks,"_ Proc. of the Workshop on ns-3 (WNS3), 2020.

## Getting Started ##

To use this module, you need to install [ns3-mmwave]("https://github.com/nyuwireless-unipd/ns3-mmwave.git") and clone this repository inside the `src` folder:

```bash
git clone https://github.com/nyuwireless-unipd/ns3-mmwave.git
git clone https://github.com/abrighenti/millicar.git ns3-mmwave/src/millicar
cd ns3-mmwave/src/millicar
git checkout develop
```

## About ##

This module is being developed by 
- [SIGNET Lab](http://mmwave.dei.unipd.it/), [University of Padova](https://www.unipd.it)
- Alessandro Brighenti, University of Trento

## License ##

This software is licensed under the terms of the GNU GPLv2, as like as ns-3. See the LICENSE file for more details.
