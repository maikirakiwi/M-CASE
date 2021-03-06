# Kasei (Kiwi's Audio/Sound Engineering Project Tree)
(Named after one of my favorite company Asahi Kasei Corporation)

<!-- Directory -->
<ol>
  <li>
    <a href="#about">About</a>
    <ul>
      <li><a href="#framework">Dependencies</a></li>
    </ul>
  </li>
  <li>
    <a href="#projects">Projects</a>
    <ul>
      <li><a href="#prerequisites">Prerequisites</a></li>
      <li><a href="#kacee-ng">KACEE-NG</a></li>
      <li><a href="#kacee-depr">KACEE-Deprecated</a></li>
      <li><a href="#kacee-s">KACEE-S</a></li>
    </ul>
  </li>
  <li><a href="#roadmap">Roadmap</a></li>
  <li><a href="#contributing">Contributing</a></li>
  <li><a href="#license">License</a></li>
  <li><a href="#contact">Contact</a></li>
  <li><a href="#acknowledgements">Acknowledgements</a></li>
</ol>


<!-- ABOUT THE PROJECT -->
## About

This really started out as a project out of personal interest/hobby in Audio Processing. Now that variations of the sub-project has been licensed and commercialized. (A very extensive fork of KACEE/M-CASE specifically designed for a Chinese streaming platform) It only serves to further interest me in the field of audio with my very limited but growing programming knowledge.      

Here's why this repository is important:
* One of the few extensively detailed & documented resource for audio processing available for free of charge.
* Voluntarily bringing together the audio community into maintaining and enhancing audio processing for humankind.
* Rescue some of my really poorly recorded audio samples and apply things learned to possibly other clips.
* Showing people how far an individual can reach out of their sole interest in this particular topic.

The need for more open-sourced researches regarding Digital Signal Processing are paramount for the dying industry to be revived by the community. So, I hope this repo will serve as an inspiration to you, the person reading this! 

Academic references and rightholders are stated in acknowledgements.

## Framework
My research involved heavily in endless trials and errors of different combination of the system for each of my projects. As a result, the dependencies of each of the extension to my research are extremely hard to keep track of. For this exact purpose, the following dependencies mentioned are only the most significant/notable ones.

### KACEE-NG:
(Successor to M-CASE)
* [ATRAC9/LDAC](https://en.wikipedia.org/wiki/Adaptive_Transform_Acoustic_Coding)
* [HE-AAC/ISO 14496-3](https://en.wikipedia.org/wiki/High-Efficiency_Advanced_Audio_Coding)


### KACEE-Depr:
(Previously M-CASE)
* TBD

### KACEE-S:
(Previously M-CASE-SEC)
* Everything under KACEE-NG
* [Camellia-128-cfb](https://en.wikipedia.org/wiki/Camellia_(cipher))

<!-- GETTING STARTED -->
## Projects

Below are specific descriptions of each of the project in this branch.

### Prerequisites

* Basic knowledge in how sound works and how they are processed through digital means.
* To some extent, physics. 

### KACEE-NG
#### Kiwi's Auditory Cognitive Enhancement Engine - Next Generation
(Successor to M-CASE)
Next Generation of M-CASE, expanding the project beyond low bitrate music enhancement but to speeches as well.
There are going to be many submodules available under the KACEE-NG name in the future. Such as the planned -AM (Audio Modernization) and -LL (Low Latency).


### KACEE-Depr
#### Kiwi's Auditory Cognitive Enhancement Engine - Deprecated
(Previously M-CASE) 
Pretty much legacy experiments and structure that I would love to archive on Git just because.
Changes made to the entire thing is so significant that it deserves to be called -NG.
> TBA


### KACEE-S
#### Kiwi's Auditory Cognitive Enhancement Engine - Secured
(Previously M-CASE-SEC) 
Based on the modern audio processing KACEE-NG but the encoded streams end up encrypted with a symmetric cipher.
Camellia-128-cfb will be the default option since it is an ISO standard and patented.
> TBA


### KLLS
#### Kiwi's Lossy-but-Lossless Standardization
A new take at "Compressed Lossless" as a personal goal to shrink my Lossless library on my DAP.
Note that this is technically "Lossy" but subjectively "transparent" compared to a Lossless Stream.
(All PCM streams downsampled to 38400Hz and packaged using OGG @ Q8 Setting)
(~76.6% Space Saving compared to FLAC Source)
> TBA

<!-- ROADMAP -->
## Roadmap

### 2021
* Restructuring of my personal project and organize them under one big name. (Done)
* TBA


<!-- CONTRIBUTING -->
## Contributing

Contributions are welcomed as more brain cells help to make this project more robust over time. Please use discussion to ask questions and open new issues for any signficant flaw that need to be addressed.

<!-- LICENSE -->
## License

This repository includes modified copies of other's original work. As such, only the modifications/written code/methodology made by **myself** are licensed under the GPL-3.0 License. For details of GPL-3.0, See `LICENSE` for more information. Any modifications branched from existing copyrighted material such as music, proprietary technology and etc still retain their originally defined license. Please look those licenses up to see if you wish to republish part of this repository for your own project. 



<!-- CONTACT -->
## Contact

Maikiwi - Maikiwi#0001 (Discord) - stella@mai.kiwi (Email)

Permanent Project Link: [https://github.com/maikirakiwi/Kasei](https://github.com/maikirakiwi/Kasei)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [Etymotic Research, Inc.](https://www.etymotic.com) (The ETYMOTIC and ETY logos are trademarks of Etymotic, Inc.) [1][2]
