---
tags: tetons
---

Hi! 

Welcome! I'm Elizabeth. I was the Scientists-in-Parks fellow in from June - October 2021. I'm currently wrapping up a PhD in glaciology at Columbia University. I'm still (as of December 2021) dipping my toes into glaciology in the park from time to time, and am always happy to chat -- send me an email at ehc2150@columbia.edu. I'm especially useful if you want to chat about: glaciers, academia, snacks, and gear.

As others have done in the past, I hope this document can help build the foundation you'll want for an incredible summer. There's so much support and space for you to craft the projects you want to work on, as well as the time & opportunity to learn from others and join in their work. 

### Where to begin

It took me a while to get up and running. I had never worked for the government before. Here are some quick takeaways:
1. you can't check your email at home.
2. most people get in around 8 or 9; many folks are out of the office on fridays.
2. weekly meetings are for updating simeon et al. on your work, asking for questions and/or support, and sharing all the funny/cool/weird/sad things that have happened in the last week or two
3. a lot of knowledge will be assumed cause everyone has been there for a while... so swallow any shame and bury it and let that garden grown and ask as many questions as you can about what you need, where resources are, what that person's name is, where to buy food, etc etc.
			- especially relevant for GIS resources -- there are a lot! I regret not asking for a tour of it right at the beginning!
4. Read Reba McCracken's "Dear 2021 Physical Science Tech" to orient yourself! It's super comprehensive.

**List of acronyms:**
SRM - science and resource management
GYE - Greater Yellowstone ecosystem
MTG - Middle Teton glacier
GPR - ground-penetrating radar
DEM - digital elevation model

**File structure:**
Everything you need is (mostly) on the X: (GIS et al) and W: (other SRM material) drives. If you want a chill project toward the end of your position, organizing one of the main files on the W: drive would be super useful!

Here's a a list of my pinned folders (adapted from Reba McCracken):

•	X:\\ProjectData\\Natural\\Glaciers\\Data\\MiddleTeton\\Spring_survey
•	X:\\ProjectData\\Natural\\Climate\\TempSensors\\GYETempNetworkSensors\\Data\\Active Monitoring Sites
•	X:\\ProjectData\\Natural\\Hydrology\\WaterQuality\\EcoliSites
•	W:\\SRM\\Air Quality
•	W:\\SRM\\Hydrology\\MonitoringSchedules&Planning
•	W:\\SRM
•	W:\\SRM\\WaterQuality\\WaterTempMonitoring

In your first week, I'd suggest you read through the protocols the SRM team has developed to get a sense of what kind of work you'll be doing this summer. These are updated yearly, and I'm sure you'll edit and add to them at the end of the season.
- E. coli monitoring protocol
- Glacier monitoring protocol
- Hydrology/discharge measurements

Also take a gander through last year's report, which summarizes almost everything we did over the summer.
- 2021 End of Season Report

Finally if you have some downtime, skim a copy of [Vital Signs 2020](https://www.nps.gov/grte/learn/nature/vital-signs.htm) and wander through the [Greater Yellowstone Climate Assessment Report](http://www.gyclimate.org/), both of which will give you an idea of the broader ecosystem and context in which we work. 

### Very quick overview of what I worked on
My focus in 2021 was on the park's glacier monitoring program, and that's where I spent most of my field & non-field time. All? of these projects could be expanded or continued. More comprehensive notes can be found in the 2021 End of Season Report (some of this text is the same as there).

#### Fieldwork for glacier monitoring

The fieldwork is a) incredible and b) exhausting. Make sure to take care of yourself! I did the first month of fieldwork in road-running shoes and would not recommend this. I ended up picking up a pair of La Sportiva TX4s and never looked back. It made a huge difference in my safety & endurance in the field. There is group sunscreen & group electrolyte powder available; TJ Maxx sells cheap-but-quality sunscreen too (my favorite is Blue Lizard). Carry your radio with you always, even when you're on your free time. My favorite hiking snacks are bbq & salt/vinegar kettle chips and starbursts.

If you can, train a bit (e.g. hit the trails! get some elevation!) before heading up to MTG for the first time.

You will likely visit at least seven glacier site, Middle Teton, Teton, Teepe, Schoolroom, Petersen, Falling Ice, Glacier Peak, all probably more than once, to deploy timelapse cameras and temperature sensors. We don't visit any of the Triple Glaciers or Skillet Glacier. The camera at Falling Ice probably needs to be relocated soon because the terminus (end of the glacier) can no longer be seen from its current location. The camera at Peterson fell off after 12 hours, not sure why. Make sure those pitons are pounded in really well. I personally like using both pitons and cam straps where possible to better ensure the camera stays in place. 


#### Data processing & analysis

##### Ground-Penetrating Radar (GPR)

Hopefully Dan McGrath (see the People to Connect With section was able to come up for the spring survey again and take more GPR data, which can tell us about the thickness of the ice and the thickness of the snowpack.  Here are the results form last year's GPR survey:

![[Pasted image 20211129170851.png|400]]

_Figure 1. GPR from 2021 overlayed on LiDAR DEM of Middle Teton Glacier. Contours are in grey, the glacier outline from 2015 is in white, and the GPR points are colored by depth according to the colorbar on the right._

##### Ablation stake monitoring

At Middle Teton Glacier, we drill in ablation stakes every year. The full table from 2021 can be found at "…\\MiddleTeton\\GPS\\AblationStakeSurveys\\2021\\2021AccumulationSurveyAblationStakeData.xlsx". Throughout the summer, I updated the 2020 and 2019 tables whenever we were able to find those stakes. A map of the ablation stake data, with all data from all years, can be found at “… /MiddleTeton/Maps/MiddleTeton/2021/GRTE_MTG_2021_AblationStakes/GRTE_MTG_2021_AblationStakes.aprx

![[Pasted image 20211129170842.png|400]]

_Figure 2. Map of the ablation stake locations_

##### Elevation Survey

Once a year, usually in the fall when the summer melt has occurred, we take an elevation survey of Middle Teton Glacier with the help of the Jenny Lake Climbing Rangers.  We completed the fall survey in early September 2021. This data was compared to the elevation survey from fall 2020 to measure the change in ice volume. The ice thinned everywhere on the glacier, and the areas with the greatest amount of thinning (near the glacier terminus) saw up to 6.3 meters of ice loss. MTG is not long for this world... This process and updated maps were emailed to Simeon in November 2021 and hopefully added to the drive.. but if not feel free to get in touch with him or me about their location.

![[Pasted image 20211129170904.png|400]]

_Figure 3. Elevation difference between 2020 and 2021 Middle Teton Glacier elevation surfaces._

##### Simple slab model of GRTE glaciers

I do a lot of work in Matlab. If you're interested in programming or physics, it would be fun to expand this a bit. If not, don't worry about it at all. I generated a first estimate of ice thickness of GRTE glaciers and allows for comparison between the model and Dan McGrath’s GPR results. See Appendix 1 for description of and access to code. Happy to update this if there's more GPR to compare it to.

A widely used metric considers 0.1 km2 to be the minimum size of a glacier (e.g. see USGS). Schoolroom, Teepe and East Triple all fail to meet this criterion. However, it is unknown whether these glaciers are still moving -- this would be a great follow-up project.
   
![[Pasted image 20211129170918.png|400]]

_Figure 4. Plots of modeled ice thickness at all 11 glaciers in GRTE. The color represents ice thickness. Some of the thicknesses are obviously too large; more work needs to be done to determine where this model represents likely depths, and where it overestimates them._

### Projects to continue
In addition to the projects below, there's a huge project doc somewhere (I think in the teams folder?) with like 20 possible projects that relate to glaciers. Feel free to explore, steal, riff, improve any of those ideas. Here are few that seem to have garnered the most interest.

#### Cliff-mounted Cyclapse Cameras

See Appendix 2, but basically we bought some cameras from Cyclapse that we hope to mount on some cliff faces overlooking MTG so that we can get year-round timelapses of the glaciers. The work in 2022 will involve scouting locations and testing deployment.

#### Mapping the Little Ice Age in GRTE

This will be a (small) part of my PhD, but if you're interested in glacial geomorphology (the geologic evidence of past glacial activity), I'm mapping out all the moraines (rock hills at the bottom of glaciers) and trimlines (uppermost point of ice on steep faces) to get a sense of the extent of Teton glaciers during the Little Ice Age. This is a GIS project. In addition, this work will involve creating DEMs of the glaciers from past satellite and aerial imagery.

#### Mapping rock glaciers in GRTE

Rock glaciers are bodies of ice that have been covered by rocky debris. These are important refuges of cold habitat for Teton creatures, and cold meltwater for the alpine streams. In addition, melting rock glaciers on steep cliffs can pose safety hazards for visitors -- as they melt, rocks that have been frozen in place tumble down cliff and mountain faces. Rock glaciers can be identified from satellite and aerial imagery, and there's been some work done on identifying where these glaciers are. We could really use a map of all the rock glaciers in the park, along with tentative outlines. These could be confirmed in collaboration with the Teton Alpine Stream Group (see Scott Hotaling in People to Connect With)


### People to connect with outside of NPS
*==Dan McGrath==*
	Email: Daniel.McGrath@colostate.edu
	Info: Dan is a professor at Colorado State University and he has an agreement with the park to run GPR surveys on Middle Teton Glacier. He's also just all around a very smart human who knows a lot about glaciology and is always willing to chat about various projects. 

*==Scott Hotaling==*
	Email: Daniel.McGrath@colostate.edu
	Info: Scott is currently transitioning from a postdoc into a professorship so I'm not sure where he'll be in 2022. He is working with me, Simeon, and the park to set up a collaboration between the Teton Alpine Stream Research Group and 

*==Caitlyn Florentine==*
	Email: cflorentine@usgs.gov
	Info: Caitlyn is one of the principal investigators of the USGS Benchmark Glacier program. She's keen on eventually getting MTG into the program. She's really really helpful in terms of: general glacier knowledge, integration with USGS, career questions, and more. 

*==Patrick Wright==*
	Email: pwright@inversionlabs.com
	Info: Patrick helps out with the spring survey. He grew up in the Jackson Hole area and is in general super knowledgable about snow and weather. He can help you access pretty much any weather data.

### Relevant literature
You don't have to read papers, but the literature around Teton glaciology isn't super extensive and it's really helfpul for framing future projects. Some recommendations for where to start, in order of relevance:

**Fryxell F** (1935) Glaciers of the Grand Teton National Park of Wyoming. The Journal of Geology 43(4), 381–397. doi:[10/bgjksn](https://doi.org/10/bgjksn).

**Reynolds HA** (2012) Recent Glacier Fluctuations In Grand Teton National Park, Wyoming. NPS. [link](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwj-14ORx770AhUDQzABHRxSD_AQFnoECAIQAQ&url=https%3A%2F%2Fwww.nps.gov%2Fgrte%2Flearn%2Fnature%2Fupload%2FReynolds_Hazel_2011-opt-red.pdf&usg=AOvVaw2VuMkAHnhKwp2WLlD4FAdY).

**Tootle G, Kerr G and Edmunds J** (2010). [Glacial change in Grand Teton National Park](https://www.nps.gov/grte/learn/nature/upload/Kerr_Final-Teton-ReportMay26-opt.pdf)

**Love and Reed** (2007). Creation of the Teton Landscape. Grand Teton National History Association. [link](https://www.nps.gov/parkhistory/online_books/grte/grte_geology/index.htm).

**Larsen D, Finkenbinder M, Abbott M and Ofstun A** (2016) Deglaciation and postglacial environmental changes in the Teton Mountain Range recorded at Jenny Lake, Grand Teton National Park, WY. Quaternary Science Reviews. 138**, 62–75. doi:[10/f8j52s](https://doi.org/10/f8j52s).


### Appendices
#### Appendix 1: Simple Slab Matlab Code

The code can be found at [https://github.com/Elizabethcase/GRTE_iceslab](https://github.com/Elizabethcase/GRTE_iceslab). The code can be downloaded from github and includes a ReadMe. It has been tested on Matlab 2020 and 2021 on a mac. Below is the copied ReadMe text.

This code takes in glacier outlines and a DEM and generates ice thicknesses using a simple slab model. The methods are based on Florentine et al 2020.

**==Dependencies==**

-   [TopoToolBox](https://topotoolbox.wordpress.com/download/) is required to run this code

**==Data==** 
The outlines included here as "GRTE_glacier_outlines.mat" are preliminary and from multiple sources, including Dan McGrath and Reynolds et al 2011. Please contact me (ehc2150 [at] columbia [dot] edu) for the LiDAR DEM and [Dan McGrath](https://people.warnercnr.colostate.edu/?daniel.mcgrath) for the GPR data.

**==References==**

1.  Florentine C, Harper J, and Fagre, D. "Parsing complex terrain controls on mountain glacier response to climate forcing." 2020. Global and Planetary Change 191. [Link](https://doi.org/10.1016/j.gloplacha.2020.103209)
2.  Reynolds H. "Recent Glacier Fluctuations in Grand Teton National Park, Wyoming." 2012. [Link.](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwip5ca7p9fzAhWDdd8KHfpWDvAQFnoECAMQAQ&url=https%3A%2F%2Fwww.nps.gov%2Fgrte%2Flearn%2Fnature%2Fupload%2FReynolds_Hazel_2011-opt-red.pdf&usg=AOvVaw2VuMkAHnhKwp2WLlD4FAdY)

**==Code==**

**IceDepthVol_fromDEMandOutlines.m** _Calculates ice thickness from DEM, outline of glacier using a simple slab model_

-   Lines 1-10 load data.
-   Line 5 loads GRTE_glacier_outlines.mat
-   Line 9 loads the DEM derived from LiDAR (file too large for github, please contact me)
-   Lines 12-17 reduce the DEM resolution
	-   Change the value for res on line 13 to increase or decrease the resolution
-   Lines 19-40 plot the glacier outlines over the DEM
-   Lines 44-45 get the slope and aspect across the whole DEM
-   Lines 47-71 plot the slope, aspect, and glacier outlines
-   Lines 73-75 convert the slope and aspect into matrices
-   Lines 79-128 calculate the thickness at all locations
-   simple slab modeL: $d = \\frac{\\tau_b}{\\rho_I g sin(\\theta)}$
	-   where $d$ is the thickness, $\\tau_b$ is the yield strength at the base of the ice, $\\rho_I$ is the ice density, $g$ is the gravitational constant, and $\\theta$ is the slope of the ice
-   lines 80-82 set the constant values for the slab model
-   The rest of the code plots the thickness and other values

**MiddleTetonModelvsGPR.m** _Compares slab-derived thickness to GPR_

-   Lines 1-20 load the data
-   Lines 22-27 reduce the resolution of the DEM
-   Lines 29-37 extract the aspect and slope from the DEM
-   Lines 40-86 calculate thickness & volume for Middle Teton Glacier
-   Lines 89 onward overlay the GPR depths on the slab-model-derived ice thickness

#### Appendix 2: Cliff-mounted Timelapse Cameras

**==References==**

1. Liu, Edward. "Ice dynamics of the Haupapa/Tasman glacier measured at high spatial and temporal resolution, Aoraki/Mount Cook, New Zealand." Master's thesis. University of Wellington. 2016.

**==Introduction==**

The cliff-mounted cameras bought from Cyclapse/Harbortronics in September 2021 will allow us to monitor glaciers year-round. With two cameras, we will have both ongoing, continuous timelapse imagery and be able to calculate glacial velocities

Because MTG is a small, steep glacier surrounded by some of GRTE's tallest peaks, it is difficult to analyze the glacier using satellite imagery. Aerial imagery from the NAIP (National Agricultural Imagery Program) program, while high resolution, only provides snapshots every two years, which is insufficient for calculating velocities or observing change in such a dynamic and complex environment.

**==Recommended Timeline==**

1. Fall 2021
	- Wilderness permit (Simeon)
2. September 2021-June 2022
	- Between September 2021 and June 2022, cameras may be tested on the ground, first indoors, then outdoors. All aspects of the equipment should be tested, including SD cards, camera battery life, solar panel viability in all types of weather, etc.
	- Calibrate camera
3. May 2022 (or earlier)
	- observe whether any of the sites are snow filled or covered
4. June 2022
	- **Scout:** work with Lexi, GR or any of the climbing rangers. Rappel or climb to the top 1-2 locations for each camera and take photos from proposed camera locations. Ensure that a majority of the glacier is in view, and that the views from the camera location overlap the same terrain by 80 or 90%.
	- **Test:** deploy the cameras close or on the ground, preferably testing the mounting procedure & equipment (e.g. on large boulders). Systems should be deployed for around a month to pinpoint any modes of failure or difficulty with the camera, solar panel, camera battery, and/or mounting equipment.
	- In conjunction with this deployment, it may be useful to deploy theodolite reflectors (e.g. by mounting them on ablation stakes or large boulders on the ice) for testing
5. Late July or early August 2022
	- cameras should be deployed at sites identified in Step 1. This may involve: the development of a safe rappel/climbing protocol and help and coordination from/with the Jenny Lake Rangers
6. Near end of 2022 season, recover cameras, process images, and decide on long-term deployment locations and protocols

![[Pasted image 20211129162334.png]]
_Figure 5. Map of suggested camera placements_
![[Pasted image 20211129162342.png]]
_Figure 6. Annotation of potential placements for Camera 1 in talus field behind cache_