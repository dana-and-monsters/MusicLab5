# MusicLab5 <br/>
The 5th edition of MusicLab was an algorave (algorithmic rave) featuring Renick Bell based in Japan, Khoparzi based in India, and researchers in Norway. Renick Bell and Khoparzi live-streamed improvised live-coded music on their computers while the audience danced at home. We measured audience members' movement using our new MusicLab mobile application that uses smartphones' accelerometers and gyroscopes. We also asked questions about the experience of the concert.

Learn more from the [webpage](https://www.uio.no/ritmo/english/news-and-events/events/musiclab/2020/musiclab-5---lockdown-rave/index.html).
The video of the concert, panel discussion, and data jockeying can be viewed [here](https://youtu.be/hJ73IGYawuM). Raw data can be downloaded [here](https://www.uio.no/ritmo/english/news-and-events/events/musiclab/2020/lockdown-rave/data/).

This repository contains the data jockeying notebook by Cagri Erdem and building on Cagri's work, Dana Swarbrick conducted the data analysis on the MusicLab IMU data for [RPPW2021](https://www.uio.no/ritmo/english/news-and-events/events/conferences/2021/RPPW/).

* MusicLab5_DJ.ipynb - Cagri's data jockeying notebook  
* MusicLab5_DataAnalysis_20210610.ipynb - built on Cagri's notebook but to enable looping through the motion files of each participant.  
* MusicLab5_DataAnalysis_ExtractPerformances_20210611.ipynb - script to identify the start of the performances in the motion data.  
* MusicLab5_DataAnalysis_Animations_20210614.ipynb - script to create animations from the motion data.  
* MusicLab5_DataAnalysis_Filtering_20210617.ipynb - script to conduct filtering.
* MusicLab5_DataAnalysis_Geolocation_20210707.ipynb - script to analyze, anonymize, and visualize geolocation.
