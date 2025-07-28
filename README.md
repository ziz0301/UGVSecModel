# AVHARM
AVHARM is a graphical modelling tool developed as part of the research presented in our paper "Graphical security modelling for Autonomous Vehicles: A novel approach to threat analysis and defence evaluation", published in Computers & Security. It enables in-depth threat analysis and defence evaluation of Autonomous Vehicle (AV) systems by combining attack graphs, attack trees, and countermeasure trees with formal security metrics.




## Overview
AVHARM is built to support AV security researchers and developers by offering:
1. Web-based visualisation of AV network attack paths.
2. Automatic calculation of multi-level security metrics.
3. Analysis of the impact and probability of attacks.
4. Support for modelling real-world AV architectures.

## To use AVHARM: 
1. Go to the AVHARM Web Tool: https://ziz0301.github.io/AVHARM/index.html.
2. Prepare vehicle network architecture in JSON format (see sample files in the `/ScenarioData` folder used in the paper).
3. Copy the JSON content and paste it into the input field.
4. Click the `Process Data` button to generate the attack graphs and calculate security metrics automatically.

## Citation
If you use AVHARM in your research, please cite our paper:
<pre>
@article{NGUYEN2025104229,
title = {Graphical security modelling for Autonomous Vehicles: A novel approach to threat analysis and defence evaluation},
journal = {Computers & Security},
volume = {150},
pages = {104229},
year = {2025},
issn = {0167-4048},
doi = {https://doi.org/10.1016/j.cose.2024.104229},
url = {https://www.sciencedirect.com/science/article/pii/S0167404824005352},
author = {Nhung H. Nguyen and Mengmeng Ge and Jin-Hee Cho and Terrence J. Moore and Seunghyun Yoon and Hyuk Lim and Frederica Nelson and Guangdong Bai and Dan Dongseong Kim},
keywords = {Attack graphs, Autonomous Vehicle, Security Analysis, Security modelling, Graphical security modelling, Attack countermeasure tree},
}
</pre>
