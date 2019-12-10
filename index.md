---
layout: default
---

# Hello world

Steven Pestana is a PhD student in the [Mountain Hydrology Research Group](https://depts.washington.edu/mtnhydr/) at the [University of Washington, Department of Civil and Environmental Engineering](https://www.ce.washington.edu/). His research interests include applying the unique perspective provided by remote sensing (whether from [small UAS](#small-uas), [aircraft](), or [satellites]()) to improve our understanding of mountain hydrology, seasonal snow, their patterns, and how they're changing. 

Where else to find Steven on the internet:

 * Twitter: [@stevenpest](https://twitter.com/stevenpest)
 * LinkedIn: [spestana](https://www.linkedin.com/in/spestana/)
 * GitHub: [spestana](https://github.com/spestana/)
 * [Mountain Hydrology Research Group](https://depts.washington.edu/mtnhydr/)
 * [UW CEE](https://www.ce.washington.edu/)


* * *

# AGU 2019 Poster
*Dec. 2019*

**Multi-scale Comparison of Wintertime Mountain Surface Temperatures from GOES ABI, MODIS, ASTER, and Airborne Thermal Infrared Observations**

Session: Remote Sensing of Land, Ocean, and Atmosphere from the New Generation of Geostationary Satellites III Posters

[Click here to download a PDF copy of the poster](/assets/images/agu2019poster.pdf)

![AGU2019](/assets/images/agu2019poster_small.jpg)



![GOESviewAnimation](/assets/images/goes_view_animation.gif)

Download, print, and fold these pages to see mountain sites from the perspective of the GOES-East and GOES-West satellites:

 * ![goes_tuolumne](/assets/images/goes_tuolumne_small.jpg)[GOES-East/West views of the upper Tuolumne River Basin, California](/assets/images/goes_tuolumne.pdf)
 * ![dem_tuolumne](/assets/images/dem_tuolumne_small.jpg)[Digital elevation model of the upper Tuolumne River Basin, California](/assets/images/dem_tuolumne.pdf)
 * ![goes_grandmesa](/assets/images/goes_grandmesa_small.jpg)[GOES-East/West views of Grand Mesa, Colorado](/assets/images/goes_grandmesa.pdf)


* * *

# Small UAS
### "drones"

## Structure from Motion Drone Survey of Easton Glacier
*Oct. 2018*

Thank you to [David Shean](https://dshean.github.io/) and his lab group for inviting me to help with this work!

[Easton Glacier](https://en.wikipedia.org/wiki/Easton_Glacier), Mount Baker (Kulshan), WA

![EastonVideo](/assets/images/easton_video.gif)

UAS used for the survey:

* DJI Phantom 4 (pictured below)
* senseFly eBee
* DJI Mavic

![EastonPhantom](/assets/images/easton_phantom.jpg)


Setting up GNSS base station and rover stations:

![EastonGNSS](/assets/images/easton_gnss.jpg)

## Structure from Motion Survey of a River Channel
*May 2018*

<img src="noocksack_survey.jpg" alt="noocksack_survey" width="200"/>

River systems in the Pacific Northwest, like much of western North America, underwent drastic changes starting in the 19th century with the settlement of the region by European Americans. Including bank reinforcement, the cutback of riparian vegetation, removal of debris and dredging, and even [re-routing river flows](https://web.archive.org/web/20110621220131/http://www.historylink.org/index.cfm?DisplayPage=output.cfm&File_Id=2624).

> “For 500 generations they flourished until newcomers came… much was lost; much was devalued, but much was also hidden away in the hearts of the dispossessed…” [Native Americans of the Pacific Northwest: An Introduction by David M. Buerge](https://content.lib.washington.edu/aipnw/index.html)

Only much more recently have the calls for restoration and rehabilitation of the regions waterways been met with action, perhaps most notably with the [Elwha River dam removals and ongoing river restoration in the Olympic Mountains](https://www.nps.gov/olym/learn/nature/elwha-ecosystem-restoration.htm).

The Nooksack river drains the western slopes of the Cascade Range in northern Washington, including Kulshan, Mount Baker, an active stratovolcano. Its south fork meanders through a valley gridded by agricultural fields before the confluence with the main stem of the river near the [Nooksack Indian Reservation](https://nooksacktribe.org/).

<img src="noocksack_map.png" alt="noocksack_map" width="200"/>

The south fork’s meanders have become relatively fixed between farm plots, held in place by bank reinforcement that in turn can increase flow velocities. The clearing of vegetation from its banks as well as its own tributaries in the logged foothills have also limited the amount of “woody debris” that the river carries downstream. These two factors (among many others) are detrimental to the local salmon population that return to the river from the Pacific Ocean to spawn. Low flow velocities through the meanders allow the fish to make their way further upstream against the current. Woody debris within the stream channel can slow flow velocities so that sand and gravel become deposited on the riverbed, creating braided channels and salmon spawning habitat.

A project to re-introduce the function of woody debris and gravel bars has been enacted on the south fork of the Nooksack river. These “engineered logjams” (ELJs) consist of tree trunks driven into the soil and tied together within the river channel. It is hoped that these will help catch what natural woody debris comes down the stream, and germinate the structures required to slow flow velocity and form gravel and sand bars.

<img src="noocksack_elj.png" alt="noocksack_elj" width="200"/>

To assess the performance of the ELJs, surveys were performed to map the shape of the river bed. Lidar surveys (light detection and ranging) from a prior year could be compared against a new survey to determine how the land surface may have changed with the introduction of these structures . Acoustic Doppler Current Profiler (ADCP) provided bathymetric measurements below the current water level, but instead of using lidar again to map the above-water river bed surfaces (at low flows, much of the river channel is exposed above water), structure from motion (SfM) using images from a small drone were used.

<img src="unavco_sfm.png" alt="unavco_sfm" width="200"/>

Lidar surveys are typically conducted from a single (or series of) fixed locaitons with a tripod-mounted “terrestrial lidar system” (TLS, as opposed to an airborne or spaceborne lidar system). To conduct a survey of the ELJ study site along the Nooksack, multiple TLS scan positions would be needed to provide views of all the river bed surfaces of interest, which takes a lot of time and effort to relocate and set up equipment multiple times. Using a small drone to capture aerial images for a SfM survey allows us to survey a similarly sized area from a single launch/landing position.

Structure from motion methods are a leap forward from traditional stereo photogrammetry which had previously supplied the data for creating topographic maps across the United States. Unlike stereo photogrammetry which provides two images analogous to perceiving depth by viewing a scene with two eyes, structure from motion can utilize 100s and 1000s of “eyes” to view an object or scene from all angles.

<img src="nooksack_gnss.png" alt="nooksack_gnss" width="200"/>

Before the drone could be launched to capture its images across the survey site, ground control points needed to be placed and their locations logged using high-precision GNSS (Global Navigation Satellite Systems, the generic term for constellations of navigational satellites, which includes the American GPS system among others). A GNSS base station was first set up to provide a long-term log of geolocation information at a fixed central location for the duration of the survey. This allows high accuracy to be established on a fixed site. The base station communicates error correction information to a “rover” GNSS unit that is taken to each ground control point to log its position. High-contrast black and white tarps served as ground control point targets since these are easily visible in the imagery taken high above the ground.

Following the logging of all ground control point locations, the drone could finally be launched to perform its survey. Multiple flights (using up all the batteries brought along in the field) helped cover different reaches of the site at a range of altitudes (which will translate to a range of image resolutions) and view angles.

<img src="nooksack_drone.png" alt="nooksack_drone" width="200"/>

Processing the resulting imagery (which itself has some geolocation information from the drone’s GNSS) together with the ground control point locations provides a digital elevation model (DEM) over which the visible imagery can be draped, creating an orthorectified image mosaic. The resulting DEM can now be used to compare against previous surveys to look for changes in the topography, perhaps due to the influence that the ELJs have on the river’s flow.

<img src="nooksack_ortho.png" alt="nooksack_ortho" width="400"/>

Thanks to the folks who invited me out to help with this project!

<img src="nooksack_group_photo.png" alt="nooksack_group_photo" width="200"/>


Seen from the drone’s point of view: [Annie Ockelford](https://research.brighton.ac.uk/en/persons/annie-ockelford) and her student Chloe, Joanna Curran, Jacob Morgan, and myself.

## Structure From Motion With A Toy Drone
*Jan. 2018*
	
![toydronevideo](/assets/images/toydrone_video.gif)

Drone: UDI R/C U845 Voyager and [Android app]()

SfM Software used: [VisualSFM]()

Sample Images:

![toydrone1](/assets/images/toydrone1.jpg)
![toydrone2](/assets/images/toydrone2.jpg)
![toydrone2](/assets/images/toydrone2.jpg)


* * *






