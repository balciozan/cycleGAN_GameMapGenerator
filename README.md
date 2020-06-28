*Istanbul Technical University  
MBL 549E - Special Top.in Arch.Des.Comp. <br/>
Tutor: Özgün Balaban <br/>
Final Project of Barış Terzi & Ozan Balcı* 

<br/>

<br/>

## Table of Contents  
* [Introduction](#introduction)  
* [cycleGAN_mix](#cycleGAN_mix)  
* [cycleGAN_onlyLands](#cycleGAN_onlyLands)  
* [cycleGAN_seasAndLands](#cycleGAN_seasAndLands)
* [Presentation](#presentation)
* [GIF](#gif)




<br/>

<br/>  

## Introduction  
This gitHub page is created to submit and share the final project have been done by Barış Terzi & Ozan Balcı in Machine Learning Course which is instructed by Özgün Balaban.

Purpose is to generate game maps alike map of the game 'Assassins Creed: Origin'. <br/>
Two main steps occur in the flowchart: <br/>
- Picking aerial or satellite images of the desirable location;
- Converting it into the game map.

CycleGan method is used to achieve the objective. For this purpose, open source model of Jun-Yan Zhu is used.

**[Source.](https://junyanz.github.io/CycleGAN/)**

<br/>

<br/>

## cycleGan_mix  
At this stage, the code is trained with mixed (lands and seas) map data. In training, "Bing" data is used.

**[Go to the code.](https://github.com/balciozan/cycleGAN_GameMapGenerator/tree/master/cycleGAN_mix)**

<br/>

<br/>

## cycleGAN_onlyLands  
At this stage, the code is trained partially of map data which includes images of the lands. In training, "Bing" data is used.

**[Go to the code.](https://github.com/balciozan/cycleGAN_GameMapGenerator/tree/master/cycleGAN_onlyLands/real2game)**  

<br/>

<br/>

## cycleGAN_seasAndLands  
At this stage, the code is trained partially of map data which includes images of the seas and seas with the lands. In training, "Bing" data is used.


**[Go to the code.](https://github.com/balciozan/cycleGAN_GameMapGenerator/tree/master/cycleGAN_seasAndLands/real2game)**  

<br/>

<br/>

## Presentation  
To compherend the entire process, final presentation of the project is avaible below.


**[Go to the presentation.](https://github.com/balciozan/cycleGAN_GameMapGenerator/tree/master/Presentation)** 

<br/>

<br/>

## GIF  
As an final example, historical peninsula of Istanbul is studied. Below, convertion phases of map generation can be seen.

![](historicalpeninsula_istanbul.gif)
