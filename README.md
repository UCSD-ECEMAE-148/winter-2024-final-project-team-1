<div id="top"></div>

<h1 align="center">Autonomous Drifting </h1>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/UCSD-ECEMAE-148/winter-2024-final-project-team-1/tree/main">
    <img src="https://github.com/UCSD-ECEMAE-148/winter-2024-final-project-team-1/blob/main/images/UCSDLogo_JSOE_BlueGold_0_0.png" alt="Logo" width="400" height="100">
  </a>
<h3>MAE-ECE 148 Final Project</h3>
<p>
Team 1 Winter 2024
</p>
</div>




<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#team-members">Team Members</a>
    </li>
    <li><a href="#final-project">Final Project</a></li>
      <ul>
        <li><a href="#final-project-documentation">Final Project Documentation</a></li>
        <li><a href="#autonomous-drifting:">Autonomous Drifting: (Insert Video)</a></li>
      </ul>
    <li><a href="#robot-design">Robot Design</a></li>
      <ul>
        <li><a href="#mechanical-design">Mechanical Design</a></li>
        <li><a href="#electronic-hardware">Electronic Hardware</a></li>
      </ul>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>


<!-- TEAM MEMBERS -->
## Team Members



<h4>Team Member Major and Class </h4>
<ul>
  <li>Seth Durbin - MAE Ctrls & Robotics (MC34) - Class of 2025</li>
  <li>Justin Kwak - MAE Ctrls & Robotics (MC34) - Class of 2025</li>
  <li>John Liu - Electrical Engineering (EC27) - Class of 2024</li>
  <li>Patrick Choe - Extension - Class of (unknown)</li>
</ul>

<!-- Final Project -->
## Final Project

The goal of our final project was to train our car to autonomously drift.  In addition to using the OAKD Lite Camera, we aimed to integrate a Razor IMU into the DonkeyCar framework to train our car.

### Primary Goals:
1) Modify car for drifting: rear wheel drive, upgrade suspension system, change out wheels
2) Integrating an IMU into the DonkeyCar framework to read data from the sensor in order to train a model 

#### Autonomous Drifting: (Insert Video)



#### Final Project Documentation

* [Final Project Proposal](https://drive.google.com/file/d/1oSwgIkiHx3t4BQ_cxLm2ZbBmvrU56_2j/view?usp=sharing)
* [Final Project Update 3/7](https://docs.google.com/presentation/d/1isKjaOL28nRso7TQlT29QjokpVWHbEqB3DTJVeYga64/edit?usp=sharing)
* [Final Project Update 3/14](https://docs.google.com/presentation/d/1QSHOZ-a3gA7jtG-dcgdHc4KCrVCbHbBCUfhCX-5B-9E/edit?usp=sharing)

<!-- Robot Design -->
## Robot Design

#### Mechanical Design

| Part | CAD Model | Designer |
|------|--------------|------------|
| Adjustable Camera Mount | <img src="https://github.com/UCSD-ECEMAE-148/winter-2024-final-project-team-1/blob/main/images/CameraMount.png" width="300" height="300" /> | Seth
| GPS Mount | <img src="https://github.com/UCSD-ECEMAE-148/winter-2024-final-project-team-1/blob/main/images/GPSMount.png" width="370" height="400" /> | Seth
| Adaptors For Wheels | <img src="https://github.com/UCSD-ECEMAE-148/winter-2024-final-project-team-1/blob/main/images/WheelAdapters.png" width="400" height="250" /> | Seth
| Tires For Wheels | <img src="https://github.com/UCSD-ECEMAE-148/winter-2024-final-project-team-1/blob/main/images/Tires.png" width="380" height="300" /> | Seth
| Acrylic Base | <img src="https://github.com/UCSD-ECEMAE-148/winter-2024-final-project-team-1/blob/main/images/AcrylicBase.png" width="400" height="210" /> | Justin




#### Electronic Hardware
Our team used only the electronic components given to us. In particular, we focused primarily on the OAK-D camera, Jetson NANO and the GNSS board (only used for the 3 GPS Autonomous Laps). When assembling the circuit, we used the following circuit diagram (given by the TAs of the class):
<div align="center">
    <img src="https://github.com/UCSD-ECEMAE-148/winter-2024-final-project-team-1/blob/main/images/MAE_148_Circuit_Diagram.png">
</div>


<!-- ACKNOWLEDGMENTS -->
## Acknowledgments
* [Nikita's Razor IMU Code](https://github.com/NikitaB04/razorIMU_9dof/blob/main/imu.py)

Special thanks to Professor Jack Silberman, and our TA Arjun Naageshwaran, and to all our amazing classmates of Winter 2024

<!-- CONTACT -->
## Contact

* Seth Durbin - sdurbin@ucsd.edu
* Justin Kwaak - jukwak@ucsd.edu
* John Liu - jol037@ucsd.edu
* Patrick Choe - Patrickychoe@gmail.com


<!-- MARKDOWN TEMPLATE INFORMATION -->
<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo_name/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo_name/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo_name/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo_name/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo_name/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: images/screenshot.png
