

<strong>About Me<strong>  

I am a geospatial analyst and programmer with 5 years of experience working with GIS and remote sensing tools. Please see <a href="/assets/images/KestingResume.pdf" class="image fit"><img target="_blank">my resume</a> or scroll down for examples of my work.  

<strong>Booststraping and Numerical Solution Analysis<strong>   

  Evapotranspiration (ET) is the flux of water from the surface to the atmosphere. It includes evaporation as well as transpiration, which is water that is taken up by plants and then lost through leaf surfaces. ET affects water availability and can be an indicator of vegetation health. For this analysis, we focused on the seasonal sourcing of ET from precipitation that falls during summer (May - September) versus winter (October - April). Specifically, we asked how annual fluxes of water from summer and winter precipitation to ET vary depending on summer and winter precipitation amounts. Using isotopes of hydrogen and oxygen, we conducted end-member splitting analysis (Kirchner and Allen, 2020). However, this method relies on several assumptions that make it unsuitable for analyzing data at the annual timescale.  
  To solve this problem, we developed a bootstrapping numerical solution analysis. To find a numerical solution, we replaced every variable in the end-member splitting equations with the linear regression equation of that variable against the x-axis (either summer of winter precipitation). We conducted bootstrapping by repeating this process with a random sample of the data. We conducted 3000 bootstrapping iterations and used the percentiles from those iterations to create the figure below. 
![Bootstrapping numerical solution figures to show precipitation partitioning](/assets/images/ETpartitioning.svg)

![Map of ozone concentrations](/assets/images/CourseraOzone.svg)
![Roads decommissioning project](/assets/images/SequoiaRoadsDecom_CVD.svg)
