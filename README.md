# Nixie_Tester_IN-1_IN-12A

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/NA-varez/Nixie_Tester_IN-1_IN-12A/">
    <img src="images/1.png" alt="1" width="100" height="100">
  </a>

  <p align="center">
    A Nixie tube tester that counts from 0 to 9! (CONSTRUCTION AND TESTING IN PROGRESS)
    <br />
  </p>
</div>


<!-- ABOUT THE PROJECT -->
## About The Project

<div align="center">
  <a href="https://github.com/NA-varez/Nixie_Tester_IN-1_IN-12A/">
    <img src="images/2.png" alt="2" width="600" height="300">
  </a>
</div>

External HV supply required.


## Notes

A board outline only needs to be created when you want the shape of the board to be different than the basic rectangle that is automatically created as a gerber .GM file.
If you want rounded edges or something, then a board outline is required to define that. The reason I am explaining this is when I sent this board to fab, 
JLC pcb contacted me wondering if I wanted the board outline to be defined by the .GKO or .GM gerber. Turns out 

In the future I will look at the gerber files and NC drill files more closely with Gerber Viewer 7.0 to understand each layer's existence and purpose.
In a future commit I will remove the outline from the keepout layer (.GKO to prevent any confusion or delay when getting board fabbed.

<!-- USAGE EXAMPLES -->
## How it Works

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- ROADMAP -->
## Roadmap

- [X] Figure out how to bias the cathode and what components to use for cycling through cathodes
- [x] Create footprints for edge connections
- [X] Order board (Used JLC PCB)
- [ ] Remove gerber .GKO Keepout layer outline. Not needed. The .GM layer already takes care of the board outline
- [ ] Assemble and test the board
- [ ] Make any fixes to the board (especially Nixie tube footprints) for it to be a reliable design for others
- [ ] Design a simple DC-DC Boost Converter Supply 12V input to max output of 200V (This will be linked to a separate repo eventually)


<!-- CONTACT -->
## Contact

Nicolas Alvarez - nalvar95@outlook.com - www.linkedin.com/in/nicolas-alvarez-69061b1b6
Douglas Liu - https://www.linkedin.com/in/liudouglas/


<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

[Threeneuron](https://threeneurons.wordpress.com/nixie-power-supply/)

:smile:

<p align="right">(<a href="#readme-top">back to top</a>)</p>

