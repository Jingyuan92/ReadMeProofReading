<div id="top"></div>
<!--
*** README template used
*** https://github.com/othneildrew/Best-README-Template
-->

<!-- PROJECT SHIELDS -->
<!--
*** Markdown "reference style" is used links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->


<!-- PROJECT -->
# biomassChemistryFoam



<!-- PROJECT LOGO -->
The biomassChemistryFoam is an extended solver based on the official "coalChemistryFoam" solver. Instead of using the coalCombustion lib, a new biomassCombustion lib is built. The layer-based thermally thick particle model is implemented to calculate the thermal conversion of the biomass particle.
<br />
<br />

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![License: GPL v3][license-shield]][license-url]

<div align="center">
  <p align="center">
    <a href="https://github.com/Jingyuan92/ReadMeProofReading/issues">Report Bug</a>
    ·
    <a href="https://github.com/Jingyuan92/ReadMeProofReading/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">Features</a>
      <ul>
        <li><a href="#IBM-model">IBM model</a></li>
      </ul>
      <ul>
        <li><a href="#New-library">New library</a></li>
      </ul>
      <ul>
        <li><a href="#Solver">Solver</a></li>
      </ul>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#Contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#Publications">Publications</a></li>
    <ul>
        <li><a href="#Publications using this repo">Publications using this repo</a></li>
      </ul>
      <ul>
        <li><a href="#Other-references">Other-references</a></li>
      </ul>
  </ol>
</details>



<!-- Features -->
## Features

### IBM model

This section should list any major frameworks/libraries used to bootstrap your project. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.

* [ ]()
* [ ]()


<p align="right">(<a href="#top">back to top</a>)</p>

### New library

The new lib has two new templates which are inheritaged from the official Lagrangian lib. 


### Solver



<!-- ROADMAP -->
## Roadmap

- [x] Add Changelog
- [x] Add back to top links
- [] Add Additional Templates w/ Examples
- [] Add "components" document to easily copy & paste sections of the readme
- [] Multi-language Support
    - [] Chinese
    - [] Spanish

See the [open issues](https://github.com/othneildrew/biomassChemistryFoam/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- Contributing -->

## Contributing
Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the [GPLv3 License](https://www.gnu.org/licenses/gpl-3.0.en.html). ([OpenFOAM license control](https://openfoam.org/licence/))

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Jingyuan Zhang - jingyuan.zhang@ntnu.no

Research group: [ComKin group at NTNU](https://www.ntnu.edu/comkin/)

 


<p align="right">(<a href="#top">back to top</a>)</p>

<!-- Publications -->
## Publications

If you use biomassChemistryFoam, you may want to cite the following papers:

### Publications using this repo
* <a id="1">[1]</a>[Zhang J, Li T, Ström H, et al. Grid-independent Eulerian-Lagrangian approaches for simulations of solid fuel particle combustion[J]. Chemical Engineering Journal, 2020, 387: 123964.](https://www.sciencedirect.com/science/article/pii/S1385894719333790)

### Other references
* <a id="2">[2]</a>[Ström H, Thunman H. CFD simulations of biofuel bed conversion: A submodel for the drying and devolatilization of thermally thick wood particles[J]. Combustion and Flame, 2013, 160(2): 417-431.](https://www.sciencedirect.com/science/article/pii/S0010218012002933)
* <a id="3">[3]</a>[Thunman H, Leckner B, Niklasson F, et al. Combustion of wood particles—a particle model for Eulerian calculations[J]. Combustion and Flame, 2002, 129(1-2): 30-46.](https://www.sciencedirect.com/science/article/pii/S0010218001003716)
 
<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/Jingyuan92/ReadMeProofReading.svg?style=flat
[contributors-url]: https://github.com/Jingyuan92/ReadMeProofReading/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Jingyuan92/ReadMeProofReading.svg?style=flat
[forks-url]: https://github.com/Jingyuan92/ReadMeProofReading/network/members
[stars-shield]: https://img.shields.io/github/stars/Jingyuan92/ReadMeProofReading.svg?style=flat
[stars-url]: https://github.com/Jingyuan92/ReadMeProofReading/stargazers
[issues-shield]: https://img.shields.io/github/issues/Jingyuan92/ReadMeProofReading.svg?style=flat
[issues-url]: https://github.com/Jingyuan92/ReadMeProofReading/issues
[license-shield]: https://img.shields.io/badge/License-GPLv3-blue.svg
[license-url]: https://www.gnu.org/licenses/gpl-3.0

