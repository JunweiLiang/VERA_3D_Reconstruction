# VERA - 3D Event Reconstruction

This repository contains the code and models for the following paper:


**[Technical Report of the Video Event Reconstruction and Analysis (VERA) System - Shooter Localization, Models, Interface, and Beyond](https://arxiv.org/abs/1905.13313)** \
[Junwei Liang](https://www.cs.cmu.edu/~junweil/),
[Jay D. Aronson](https://www.cmu.edu/dietrich/history/people/faculty/aronson.html),
[Alexander Hauptmann](https://www.cs.cmu.edu/~alex/)

You can check find more information and try out the live 3D event reconstruction demo at our [Project Page](https://vera.cs.cmu.edu/VERA_3D_Reconstruction).

Also, try out our [shooter localization system](https://vera.cs.cmu.edu/).



## Introduction
We introduce the Video Event Reconstruction and Analysis (VERA) system, enabled by established machine learning techniques and physics models, that can show synchronized videos from social media that capture an event in 3D space.


<div align="center">
  <div style="">
      <img src="img/3D_Reconstruction.gif" height="200px" />
      <img src="img/Video_In_3D.gif" height="200px" />
  </div>
  <p style="font-weight:bold;font-size:1.2em;">
  	<a href="https://vera.cs.cmu.edu/VERA_3D_Reconstruction/3D_Reconstruction_1.html" target="_blank">Live Demo 1</a> &nbsp; &nbsp;
    <a href="https://vera.cs.cmu.edu/VERA_3D_Reconstruction/3D_Reconstruction_2.html" target="_blank">Live Demo 2</a>
  </p>
</div>

If you find this system/code useful in your research/report then please cite

```
@article{liang2019vera,
    title={Technical Report of the Video Event Reconstruction and Analysis (VERA) System - Shooter Localization, Models, Interface, and Beyond},
    author={Liang, Junwei and Aronson, Jay D. and Hauptmann, Alexander},
    journal={arXiv preprint arXiv:1905.13313},
    year={2019}
}
@inproceedings{liang2017synchronization,
  title={Synchronization for multi-perspective videos in the wild},
  author={Liang, Junwei and Huang, Poyao and Chen, Jia and Hauptmann, Alexander},
  booktitle={2017 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)},
  pages={1592--1596},
  year={2017},
  organization={IEEE}
}
@inproceedings{liang2017event,
  title={An event reconstruction tool for conflict monitoring using social media},
  author={Liang, Junwei and Fan, Desai and Lu, Han and Huang, Poyao and Chen, Jia and Jiang, Lu and Hauptmann, Alexander},
  booktitle={Thirty-First AAAI Conference on Artificial Intelligence},
  year={2017}
}
```

You can check find more information and try out the live 3D event reconstruction demo at our [Project Page](https://vera.cs.cmu.edu/VERA_3D_Reconstruction).

## Installation
You will need to have a running server for the demo to run properly. You cannot just directly open the html file in Chrome according to [this](https://github.com/mrdoob/three.js/wiki/How-to-run-things-locally).

## Code Overview
Currently we have released the source code for the web interface.

