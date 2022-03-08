<div id="top"></div>

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Issues][issues-shield]][issues-url]
[![CC License][license-shield]][license-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/dmjimenezbravo/NetLogoExampleModification">
    <h1 aling="center">NetLogo example modification</h1>
  </a>

  <p align="center">
    A simple modification of a NetLogo model.
    <br />
    <a href="https://github.com/dmjimenezbravo/NetLogoExampleModification"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/dmjimenezbravo/NetLogoExampleModification/issues">Report Bug</a>
    ·
    <a href="https://github.com/dmjimenezbravo/NetLogoExampleModification/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#bit-information-about-netlogo">Bit information about NetLogo</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

A simple modification of a NetLogo model for the subject "Computación Social y Personalización" ("Social Computing and Personalisation") of the "Grado en Ciencia de Datos e Inteligencia Artificial" ("Degree in Data Science and Artificial Intelligence") of the Universidad Politécnica de Madrid (UPM).

<p align="right">(<a href="#top">back to top</a>)</p>

### Built With

* [NetLogo](https://ccl.northwestern.edu/netlogo/).

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- BIT INFORMATION ABOUT NETLOGO -->
## Bit information about NetLogo

It is a programmable multi-agent system modelling tool. It allows you to create interactive models and observe the life cycle of the agents based on the behaviours defined programmatically. It was created by Uri Wilensky (Northwestern University) in 1999. For more information, see [https://ccl.northwestern.edu/netlogo/](https://ccl.northwestern.edu/netlogo/).

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- GETTING STARTED -->
## Getting Started

To run the example based on the NetLogo "Paths" model, the following is needed:

Once the software has been installed, it will be possible to load the "Paths" model from the tool's installation folder (). If you have decided to use the browser tool, you can access the model via the following [link](http://www.netlogoweb.org/launch#http://ccl.northwestern.edu/netlogo/models/models/Sample%20Models/Social%20Science/Paths.nlogo).

<p align="right">(<a href="#top">back to top</a>)</p>

### Prerequisites

* NetLogo: the first step is to download the [NetLogo tool](https://ccl.northwestern.edu/netlogo/download.shtml) or access it through its [online tool](http://www.netlogoweb.org/launch). It is always recommended to use the desktop version as for some models the browser version does not work properly. On the other hand, when installing the desktop version you will have the models provided by the creators of the tool.

<p align="right">(<a href="#top">back to top</a>)</p>

### Installation

To install the desktop version of NetLogo you have to access the following [link](https://ccl.northwestern.edu/netlogo/download.shtml) and choose the corresponding version for your operating system. The software is installed in a similar way to any other software. 

It is important to pay attention to the installation folder, as it is in this folder where the models provided by the tool that we may need later will be stored.

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- USAGE EXAMPLES -->
## Usage

To use the model available in this repository [PathsModified.nlogo]() just open the tool and open the previously downloaded model on your computer.

The differences of the model in this repository in relation to the NetLogo Paths model are shown below:

1. Define a new subset of agents of type "turtle" that refers to buildings of type "skyscrapers". These agents will have a larger size than the "buildings" agents and will be coloured blue.
2.	This new agent type shall be created in the same way as the "building" type agents, i.e. by clicking on the NetLogo world. However, whenever clicked, a "skyscraper" or "building" type building can be created; this will be decided randomly but the probability of "building" type agents being created will be higher than that of the "skyscraper".
3.	When there are at least two agents of type "skyscraper" and/or "building", the mobile agents will prioritise one of these types of agents as a destination. Although they will randomly decide whether to go to a "skyscraper" or a "building", the probability of going to a "skyscraper" will always be higher.
4.	The agents of type "buiding" and "skyscraper" shall establish links between them by means of the agents of type "link". Only agents of these types that are closest to each other shall be linked.
5.	Finally, a new property is defined for the "skyscraper" and "building" agent types. This property refers to their popularity, which will progressively decrease until it reaches zero. At that point the agent will die and disappear from the NetLogo world.

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- CONTRIBUTING -->
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

Distributed under the Creative Commons Zero v1.0 Universal License. See `LICENSE` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

Diego M. Jiménez Bravo - [@dmjimenezbravo](https://twitter.com/dmjimenezbravo) - dmjimenezbravo@gmail.com

Project Link: [https://github.com/dmjimenezbravo/NetLogoExampleModification](https://github.com/dmjimenezbravo/NetLogoExampleModification)

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* Grider, R. and Wilensky, U. (2015). NetLogo Paths model. [http://ccl.northwestern.edu/netlogo/models/Paths]( http://ccl.northwestern.edu/netlogo/models/Paths). Center for Connected Learning and Computer-Based Modeling, Northwestern University, Evanston, IL.
* Wilensky, U. (1999). NetLogo. [http://ccl.northwestern.edu/netlogo/](http://ccl.northwestern.edu/netlogo/). Center for Connected Learning and Computer-Based Modeling, Northwestern University, Evanston, IL.

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/dmjimenezbravo/NetLogoExampleModification/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/dmjimenezbravo/NetLogoExampleModification/blob/main/LICENSE
