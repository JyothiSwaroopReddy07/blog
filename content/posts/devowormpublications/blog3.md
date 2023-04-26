+++
title =  "Google Summer of Code 2022 in the OpenWorm Community (DevoWorm)"
tags = ["DevoWorm", "Bradly Alicea"]
date = "2022-06-15"
+++




<p align="center">
<img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgjwFZTC2F-CChOitsBm60l_v1EfWll4tMznDyypeaq74WKTguxCkAWyutJ9hOmK9hCHmzrmP4Ll2hVQZvq_pN__d-7-4pZHweWEv34rjoieAGFtBR2VLuoEx19CPddW3IuIPgCmINADwyfA6UV-Mip9WLD7XYxSqvuUA_wXyIzFar4CIY07NChMb0C/s1600/GSoC-icon-192.png" alt='Darwin Image'/>
</p>

Welcome to Google Summer of Code 2022! I am pleased to announce that this year, we have two funded projects: D-GNNs and Digital Microspheres! These projects will both take place in conjunction with the DevoWorm part of the OpenWorm community. [DevoWorm](https://devoworm.weebly.com/) is an interdisciplinary group engaged in both computational and biological data analysis. We have [weekly meetings on Jit.si](https://meet.jit.si/DevoWorm), and are a part of the [OpenWorm Foundation](https://openworm.org/). 
This year, we were able to fund two students per project. They will be working on complementary solutions to each problem, and we will see how far they get by the end of the Summer. 

## D-GNNs (Developmental Graph Neural Networks)

The description for this project is as follows:

Biological development features many different types of networks: neural connectomes, gene regulatory networks, interactome networks, and anatomical networks. Using cell tracking and high-resolution microscopy, we can reconstruct the origins of these networks in the early embryo. Building on our group's past work in deep learning and pre-trained models, we look to apply graph neural networks (GNNs) to developmental biological analysis.

The contributor will create graph embeddings that resemble actual biological networks found throughout development. Potential activities include growing graph embeddings using biological rules, differentiation of nodes in the network, and GNNs that generate different types of movement output based on movement seen in microscopy movies. The goal is to create a library of GNNs that can simulate developmental processes by analyzing time-series microscopy data.

When completed, D-GNNs will become part of the [DevoWorm AI](https://devoworm.github.io/DevoWormAi/) library. Ultimately, we will be integrating the GNN work with the DevoLearn (open-source pre-trained deep learning) software. 

<p align="center">
  <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhupq99DK8UHCusm7zXMmQjfmIImIo8Jv1Z8fBCJmI1G4zc5WNsp30fCy3WRE-bdOAmBkz6FTyiq-XItvWhncD3vTzkL7rd4FFhA323GYH0bkqVMPX20E92wTFyZikngbW5MMG-sVUABUVkc20YNath3TAU5TnGaRMgd_NXrINEvT9XMNv8ocak9mv1/w200-h184/jiahang.png" alt="Sublime's custom image"/>
</p>

<p align="center">
    Jiahang Li
</p>

Jiahang Li is a first year MPhil candidate in Computing Department at [Hong Kong Polytechnic University](https://www.polyu.edu.hk/). His research interests cover graph representation learning and its applications. Jiahang's approach to the project is to provide a pipeline that converts microscopic video data of C. elegans and other organisms into graph structures, on which advanced network analysis techniques and graph neural networks will be employed to obtain high-level representation of embryogenesis and to solve applied problems.

<p align="center">
  <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEit5v0EWr3qZQmlQNSytPLl0BMT__F1lvg6pzCVQEIps2ImXaWwiuTMVIxKuCE-Db1ZcAv419rglHRmqhP_Sn0Hzf_RBrLTsZ6GqHg3nWlOjQYZMPfqETBRt-DbWkJMYdwjF0CUjGWKE2cUgEycWoFwALbLAwR16bRIqtp3BoZog1eWrOe-0VEsK5_U/w217-h158/wataru.png" alt="Sublime's custom image"/>
</p>

<p align="center">
    Wataru Kawakami
</p>

Wataru is a student at [Kyoto University](https://www.kyoto-u.ac.jp/en) with interests in Machine Learning (in particular Graph Neural Networks) and Neuroimaging.


### Digital Microspheres

The description for this problem is as follows: 

This project will build upon the specialized microscopy techniques to develop a shell composed of projected microscopy images, arranged to represent the full external surface of a sphere. This will allow us to create an atlas of the embryo’s outer surface, which in some species (e.g. Axolotl) enables us to have a novel perspective on neural development.

The contributor will build a computational tool that allows us to visualize 4D data derived from the surface of an Axolotl embryo. The spatial model and animation (4th dimension) of microscopy image data can be created in a 3-D modeling software of your choice.

This project is based on previous research by DevoWorm contributors Richard Gordon and Susan Crawford-Young. The flipping and ball microscopy research involve the design and fabrication of specialized microscopes to image embryos in a 4-D context (3 dimensions of space plus time).

### Spherical Embryo Maps: 
Gordon, R. (2009). [Google Embryo for Building Quantitative Understanding of an Embryo As It Builds Itself](https://link.springer.com/article/10.1162/BIOT_a_00010). II. Progress Toward an Embryo Surface Microscope. Biological Theory, 4, 396–412.

### Flipping Microscopy: 
Crawford-Young, S., Dittapongpitch, S., Gordon, R., and Harrington, K. (2018). [Acquisition and reconstruction of 4D surfaces of axolotl embryos with the flipping stage robotic microscope](https://www.sciencedirect.com/science/article/abs/pii/S0303264718302995). Biosystems, 173, 214-220.

### Ball Microscopy: 
Crawford-Young, S.J. and Young Williment, J.L. (2021). [A ball microscope for viewing the entire surface of amphibian embryos](https://www.sciencedirect.com/science/article/abs/pii/S0303264721001453). Biosystems, 208, 104498.


<p align="center">
  <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjuix_4PEn2YFMnCcpL-ueqgR_84lJ0EtUy5ndS1QWf6UaJJMqDlbEQDmcNemc3ExFGgiFaE2vqjQAzl8iDnSS2_6yjuLKnO3Ztx70NF20QwaJ7fVjJ5QJ-PqgY-2Oet6mlQZ4W3_TxklomdHNSu_5mzhq5i66E4W0AJ_srEowLRuEB4pVpUXOeqwj7/w200-h180/karan.png" alt="Sublime's custom image"/>
</p>

<p align="center">
    Karan Lohaan
</p>

Karan is a student at [Amrita Vishwa Vidyapeetham University](https://www.amrita.edu/), and is a member of the AMFoss program there. He is interested in Machine Learning and Image Processing. 

<p align="center">
  <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhU5TbIvkJA1jgkXEljBQhnmVRT0zB3U6Wb1UANNXzhG2Ug_jy2BgNg00RY4BIQ6M-SgsAxjl0ZvrePey7D0MXMINsWpuMNsXcxiwVyl8yONKqJFr3NRAXAo30kaRk1ViuoCekMsLgNyku2rKU8Av0LyyMvjbOQFySySewfdP29ek1M3ol5knCqVTyy/w200-h196/harikrishna.png" alt="Sublime's custom image"/>
</p>

<p align="center">
    Harikrishna Pillai
</p>

I am Harikrishna pursuing my B.Tech in Computer Science and Artificial Intelligence from [Amrita Vishwa Vidyapeetham University](https://www.amrita.edu/). I completed my schooling in Mumbai. I started with python as my first language and eventually developed interest for AI. Due to my interest in Android apps, I have done Android development in Kotlin. Also, I have been interested in open source for some time now and therefore, I wanted to start my open source journey with GSoC.

We also have two GSoC mentors for these projects: Bradly Alicea is a mentor for D-GNNs and Digital Microspheres, and Jesse Parent is a mentor for D-GNNs. Richard Gordon and Susan Crawford-Young are serving as collaborators for the Digital Microspheres project.

If you would like to check on their progress, please check out our weekly meetings available on our [YouTube channel](https://www.youtube.com/channel/UChGTq41_rJwmZ1I4j7SezWQ).



Posted by [Bradly Alicea](https://www.linkedin.com/in/bradlyalicea/) 
