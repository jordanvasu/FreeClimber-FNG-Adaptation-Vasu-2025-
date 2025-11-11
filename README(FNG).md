# FreeClimber–FNG Adaptation

This repository contains modifications to the [FreeClimber](https://github.com/adamspierer/FreeClimber) software (Spierer et al., 2020) to enable automated detection of failed negative geotaxis (FNG) and calculation of fall distance in *Drosophila melanogaster*.

## Original Authors
- Adam N. Spierer, Lei Zhuo, and colleagues  
- Citation: Spierer, A. N. et al. (2020). *Journal of Experimental Biology*, 223, jeb229377.

## Modifications by
- Jordan Vasu (2025)  
- Added functions for:
  - FNG detection (climb → fall events)
  - Fall distance measurement -> This function takes the difference between a fall initiating and stopping. In this way, it can be considered the time between a _Drosophila_ falling and recovering from the fall.
  

## License
The original FreeClimber is released under the MIT License.  
All modifications herein remain open-source under the same license, with attribution to the original authors.
