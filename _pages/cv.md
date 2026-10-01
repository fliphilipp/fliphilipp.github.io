---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

You can download the full CV as a PDF file [here](/files/Philipp_S_Arndt_CV_2026_09.pdf) (last updated September 2026).

Research Profile
=====
Earth scientist and machine-learning researcher who builds automated, scalable methods that turn large volumes of satellite data into reliable, openly available information. At Global Fishing Watch, I develop AI models that detect, classify, and identify vessels in optical and radar satellite imagery to support transparent monitoring of fishing and other human activity at sea. As a NASA FINESST Future Investigator at Scripps Institution of Oceanography, I created algorithms that automatically detect meltwater lakes and measure their depths in NASA ICESat-2 laser-altimetry photon data across the Greenland and Antarctic ice sheets.

Skills
=====
**Methods:** Machine learning and computer vision for satellite imagery ∣ Sensor processing and data fusion (optical, SAR, lidar altimetry, AIS) ∣ Satellite remote sensing ∣ Large-scale geospatial data analysis ∣ Distributed high-throughput computing ∣ Training-data design and annotation management ∣ Statistical learning and econometrics ∣ Data visualization ∣ Scientific writing and communication

**Computing:** Python ∣ SQL (Google BigQuery, PostgreSQL/PostGIS) ∣ PyTorch ∣ scikit-learn ∣ Jupyter ∣ Git/GitHub ∣ bash ∣ Google Cloud Platform & AWS ∣ Google Earth Engine ∣ HTCondor ∣ Singularity/Docker ∣ Spark ∣ MATLAB ∣ R ∣ C ∣ Java ∣ JavaScript ∣ Stata ∣ Mathematica ∣ QGIS & ArcGIS ∣ $$\LaTeX$$ ∣ AI coding assistants (Claude Code, Gemini CLI)

**Languages:** German (native) ∣ English (fluent) ∣ French (conversational) ∣ Portuguese (conversational)

Education
=====
* Ph.D. in Earth Sciences, Scripps Institution of Oceanography, UC San Diego, 2024
  * Dissertation: [Using High-Resolution Satellite Observations to Better Understand Surface Melt Processes on the Greenland and Antarctic Ice Sheets](https://escholarship.org/uc/item/7hk6f0dr) (advisor: Helen A. Fricker)
* M.Sc. in Earth Sciences, Scripps Institution of Oceanography, UC San Diego, 2020
* M.Sc. in Engineering Physics (Complex Adaptive Systems), Chalmers University of Technology, 2018
  * Thesis: [Detection of Multi-Level Hierarchies in Multi-View Cancer Networks, with Applications to Glioblastoma Multiforme](/publication/2018-mastersthesis)
* B.A. in Economics & Mathematics, Yale University, 2016
* International Summer School in Glaciology, University of Alaska Fairbanks, McCarthy, AK, 2022

Research & Professional Experience
=====

* Jan 2025 - present: Data Scientist, Satellite Imagery & Data Fusion (Research & Innovation Team)
  * [Global Fishing Watch](https://globalfishingwatch.org/), remote (based in San Diego, CA, USA)
  * Building machine-learning systems that detect vessels in optical (Sentinel-2, PlanetScope) and radar (Sentinel-1, NISAR) satellite imagery and determine their type, activity, and identity, in close collaboration with SkyTruth and the Allen Institute for AI (Ai2)
  * Global Sentinel-2 vessel detections (released July 2025): rebuilt the database of environmental and contextual features (e.g., bathymetry, seabed type, ocean and weather conditions, distance to shore and port, AIS vessel density, socioeconomic indicators) that the vessel-classification models combine with image embeddings. The open dataset captures about three times more vessels than radar, including some under 10 m, across all coastal waters.
  * PlanetScope vessel detections: helping develop vessel-classification models for detections in Planet's 3 m imagery, which brings small coastal vessels (down to ~5 m) into view; managing image annotation for training data (labeling tools, training and managing an external labeling contractor) and building BigQuery feature pipelines across hundreds of millions of detections
  * Dark vessels and new activity types: supporting work on retrieving the identities of large vessels that do not broadcast AIS; sand-dredging classification in Sentinel-2 and PlanetScope imagery with collaborators from UC Santa Barbara's emLab
  * Bottom trawling in Australia: co-led a project for the Minderoo Foundation mapping bottom trawling across Australia's Exclusive Economic Zone by combining AIS data with Sentinel-2 detections, including how much occurs inside versus outside Fisheries Restricted Areas

* Sep 2018 - Dec 2024: Graduate Researcher & NASA FINESST Future Investigator
  * [Scripps Polar Center](https://polar.ucsd.edu/), Scripps Institution of Oceanography, UC San Diego, La Jolla, CA, USA
  * Developed [FLUID-SuRRF](/publication/2024-FLUIDSuRRF), a fully automated framework that detects meltwater lakes in ICESat-2 photon data and measures their depths (mean absolute error < 0.27 m). Scaled it with distributed high-throughput computing on the NSF-supported Open Science Pool to process 138 TB of data (~765 billion photons) from five melt seasons on both ice sheets, yielding 10,954 lake-depth segments up to 33 m deep.
  * Trained a random-forest model on the Greenland ICESat-2 depths to estimate lake depth and volume from Sentinel-2 imagery; it reaches ~0.5 m depth accuracy against in situ sonar, cuts volume errors by over 60% compared with traditional radiative-transfer methods, and generalizes to Antarctica (manuscript in preparation)
  * Wrote the open-source ICESat-2 depth-retrieval code for [Fricker et al. (2021)](/publication/2021-meltwater-depths-amery), since used by independent research groups; contributed analysis, code, and the widely republished water-volume graphic to [Warner et al. (2021)](/publication/2021-doline-amery); compiled an inventory of through-ice-shelf lake drainages across Antarctica
  * Designed and led a [ski-based campaign](/fieldwork/) to ground-validate ICESat-2 snow depths in the San Bernardino Mountains (2023); mentored three undergraduate research projects and was a teaching assistant for two courses
  * Advisor: Helen A. Fricker

* Jan 2017 - Dec 2017: Contracted Student Researcher
  * Fraunhofer-Chalmers Centre for Industrial Mathematics, Gothenburg, Sweden
  * I analyzed GPS tracking data for a large truck producer to gain insights into their customers' mobility patterns. This involved a global clustering of points where trucks stopped for extended periods of time, cross-referencing the resulting "hubs" with infrastructure data from open-source mapping platforms, and training a classifier to categorize unlabeled locations.
  * Supervisor: Mats Jirstrand

* Jun 2017 - Aug 2017: Visiting Assistant in Research
  * Yale Graduate School of Arts & Sciences, New Haven, CT, USA
  * I worked on an interdisciplinary project applying econometric methods to global weather station data to robustly estimate Earth's transient climate sensitivity from in-situ observational data (co-author of [Storelvmo et al., 2018](/publication/2018-aerosols)). I also used machine learning algorithms for spatio-temporal interpolation of weather station records based on global reanalysis data.
  * Supervisors: Trude Storelvmo & Peter C. B. Phillips
 
* May 2015 - Aug 2015: COPAN Guest Researcher
  * Potsdam Institute for Climate Impact Research, Potsdam, Germany
  * I carried out statistical data analyses focusing on the 'Great Acceleration' time series and related data sets. I found that many of these time series exhibit statistically significant break points around the 1950s. This means that it is possible to define the Anthropocene as a geological epoch with a stratigraphic marker that coincides with the "bomb spike" while also being rooted in a robust statistical analysis that takes into account the socioeconomic drivers characterizing the Anthropocene.
  * Supervisor: Jobst Heitzig

* May 2014 – Jul 2014: Client Management and Underwriting Intern
  * Munich Re, Munich, Germany
  * Risk modeling, XL treaty pricing, solvency analysis, business strategy for the Indian and Japanese markets
 
* Aug 2013 – May 2015: Social Media and Photography Intern
  * Yale Office of Public Affairs & Communications, New Haven, CT, USA
  * Photography, outreach strategy & official representation of Yale University on social media

Publications
======
Google Scholar (September 2026): 175 citations, h-index 4 ∣ [profile](https://scholar.google.com/citations?user=NORXhMcAAAAJ)

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Research Grants & Fellowships
=====
* Future Investigators in NASA Earth and Space Science and Technology (FINESST), NASA Earth Science Division, research award (USD 135,000 ∣ 2020-24, grant 80NSSC20K1666). Project: "Exploitation of ICESat-2's Unique Capabilities and Machine Learning for Improved Understanding of Mass Balance Processes Across all Antarctic Ice Shelves" (Future Investigator; PI: H. A. Fricker)
* Wyer Family Endowed Fellowship, for PhD stipend supplement (2020-23)
* Katzin Fellowship, for PhD program tuition supplement (2020-23)
* Scripps Fellowship, for outstanding incoming graduate students (2018-19)
* Richter Fellowship, for climate research in Germany (2015)
* e-fellows.net Scholarship, awarded for academic merit (2015)
* Larry Coben Fellowship, for academic work and volunteer teaching in Brazil (2013)

Honors & Travel Awards
=====
* Early-Career Researcher Travel Grant, WAIS Workshop, Cloquet, MN (2023)
* Selected speaker, Graduate Student Spotlight, NASA ICESat-2 Science Symposium & Science Team Meeting, Austin, TX (2022)
* Early-Career Researcher Travel Grant, WAIS Workshop, Estes Park, CO (2022)
* WSL Early-Career Researcher Travel Grant, The Cryosphere in a Changing Climate, Davos, Switzerland (2022)
* Scripps Departmental Travel Grant, AGU Fall Meeting, New Orleans, LA (2021)
* Early-Career Researcher Travel Grant, WAIS Workshop, Sterling, VA (2021)
* Antarctica Service Medal, U.S. Department of Defense (2019)
* Scholar-Athlete Award, National Association of Intercollegiate Gymnastics Clubs (2019)
* Academic Excellence Award, UC San Diego Club Sports (2019)

Open Data Products & Software
=====
* Arndt, P. S. & Fricker, H. A. (2024). Source code for FLUID-SuRRF, automated supraglacial lake detection and depth retrieval in ICESat-2 photon data (incl. a Singularity container for distributed high-throughput computing). Zenodo. [doi:10.5281/zenodo.10905941](https://doi.org/10.5281/zenodo.10905941)
* Arndt, P. S. & Fricker, H. A. (2024). Data for "A framework for automated supraglacial lake detection and depth retrieval in ICESat-2 photon data across the Greenland and Antarctic ice sheets". Zenodo. [doi:10.5281/zenodo.10901737](https://doi.org/10.5281/zenodo.10901737)
* Arndt, P. (2024). Data and code for figure reproduction for the same paper (FLUIDSuRRF-figures). Zenodo. [doi:10.5281/zenodo.10901826](https://doi.org/10.5281/zenodo.10901826)
* Arndt, P. (2025). ICESat2Sentinel2 (v0.1.0): open-source code for pairing ICESat-2 data with Sentinel-2 imagery. Zenodo. [doi:10.5281/zenodo.14722234](https://doi.org/10.5281/zenodo.14722234)
* Arndt, P., Warner, R., Fricker, H. A., Adusumilli, S., Kingslake, J., & Spergel, J. (2021). Data and code for "Rapid Formation of an Ice Doline on Amery Ice Shelf, East Antarctica." Zenodo. [doi:10.5281/zenodo.4747428](https://doi.org/10.5281/zenodo.4747428)
* Arndt, P. (2020). Code for ICESat-2 melt-lake depth retrieval comparisons on Amery Ice Shelf, for Fricker et al. (2021) (ameryMeltLakesICESat2, v1.0.0). Zenodo. [doi:10.5281/zenodo.4299237](https://doi.org/10.5281/zenodo.4299237)
* Arndt, P. pondpicking: interactive Jupyter tool for ICESat-2 lake-depth retrieval, used in Lutz et al. (2024, The Cryosphere). [GitHub](https://github.com/fliphilipp/pondpicking)
* Arndt, P. & Roberts, C. (2026). Interactive Visualization with OpenAltimetry and Google Earth Engine. Chapter in ICESat-2 Cookbook (v1.0.0), Project Pythia. [doi:10.5281/zenodo.21298648](https://doi.org/10.5281/zenodo.21298648)
* ICESat-2 Hackweek 2022 and 2023 websites and tutorials (co-author), eScience Institute, University of Washington. [doi:10.5281/zenodo.6462479](https://doi.org/10.5281/zenodo.6462479); [doi:10.5281/zenodo.10519966](https://doi.org/10.5281/zenodo.10519966)
* Contributor (team product): Global Fishing Watch Sentinel-2 vessel detections, a global, openly available dataset (GFW map, data portal, and monthly Zenodo releases), 2025-present

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Media Coverage
=====
Coverage of [Warner et al. (2021)](/publication/2021-doline-amery) unless noted; many of these articles feature my graphic of the lost water volume.

* UC San Diego Today / Scripps Institution of Oceanography News (23 June 2021): [Scientists Track Sudden Disappearance of Antarctic Ice Shelf Lake](https://today.ucsd.edu/story/scientists-track-sudden-disappearance-of-antarctic-ice-shelf-lake)
* State of the Planet, Columbia Climate School (24 June 2021): [Scientists Track the Sudden Disappearance of an Antarctic Ice-Shelf Lake](https://news.climate.columbia.edu/2021/06/24/scientists-track-sudden-disappearance-of-an-antarctic-ice-shelf-lake)
* EarthSky (28 June 2021): [An Antarctic lake suddenly disappears](https://earthsky.org/earth/antarctic-lake-suddenly-disappears-doline/)
* ScienceAlert (28 June 2021): [Gigantic Antarctic Lake Suddenly Disappears in Monumental Vanishing Act](https://www.sciencealert.com/gigantic-antarctic-lake-suddenly-disappears-in-monumental-vanishing-act)
* SciTechDaily (29 June 2021): [Sudden Disappearance of Giant Antarctic Lake Leaves Massive Crater – 200 Billion Gallons of Water Gone](https://scitechdaily.com/sudden-disappearance-of-giant-antarctic-lake-leaves-massive-crater-200-billion-gallons-of-water-gone/)
* The Weather Network (4 July 2021): [Disappearing lake in Antarctica leaves scientists puzzled](https://www.theweathernetwork.com/us/news/article/disappearing-lake-in-antarctica-leaves-scientists-puzzled)
* UC San Diego Graduate Division: [Graduate Student Spotlight: Philipp Arndt](https://grad.ucsd.edu/student-life/student-spotlights/alumni/philipp-arndt.html) (profile of my doctoral research and the NASA FINESST award)

Field Experience
=====
* Field Team and Project Lead
  * Independent Research with the UC San Diego Alpine Club  ∣  April 2023, San Bernardino National Forest, CA, USA
  * Ski-Based ICESat-2 Ground-Validation Campaign for Snow Depth Measurements on San Gorgonio Mountain
 
* Field Assistant
  * University of Alaska Fairbanks & National Science Foundation  ∣  May 2022 - Jun 2022, McCarthy, AK, USA
  * Anticipating Rates of Deglaciation in Alaska: Controls on The Mass Loss and Morphology of The Debris Covered Terminus of Kennicott Glacier, Wrangell - St. Elias National Park (NSF Award ID 1917536)
 
* Field Researcher (Grantee)
  * United States Antarctic Program & National Science Foundation ∣ Oct 2019 - Dec 2019, McMurdo Station / Siple Dome, Antarctica
  * Subglacial Antarctic Lakes Scientific Access (SALSA) project, Geophysics Team (event number C-533): two-month deep-field deployment living in tents on the ice, including recovery of GPS instruments by small aircraft

* Glacier Field Course
  * Bavarian Academy of Sciences, Commission for Geodesy & Glaciology ∣ Jul 2010, Vernagtferner Glacier, Ötztal Alps, Austria

Teaching & Mentorship
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Professional Service, Leadership & Community Engagement
======
* Peer reviewer, The Cryosphere, 2021; public community comments in The Cryosphere's open peer-review discussions of later manuscripts
* Organizer and tutorial lead, ICESat-2 Hackweeks, University of Washington eScience Institute, 2022 & 2023
* Board Member of the Allied Climbers of San Diego, 2024-present
* Founding member and instruction/outreach with the UC San Diego Alpine Club, 2022-present
* Chalmers Environmental Unit Sustainability Ambassador, 2017-18
* Student Representative, MSc Complex Adaptive Systems Program at Chalmers University of Technology and Gothenburg University, 2017-18
* Artistic Gymnastics Coach (kids and adults) and Judge with Göteborgs Turnförening, 2016-18
* Co-Founder of the Yale Gymnastics Club, President (2013-15) and Coach (2013-16)
* German Society at Yale University, President (2014-15), Events Coordinator (2013-16)
* Co-founder of the Yale Photography Society, President (2012-13)
* Provided free or heavily discounted photoshoots for small community organizations while doing paid freelance projects and work for Yale University (2013-16)
* Artistic Gymnastics Coach (kids) and Judge with Turn- und Sportverein Fürstenfeldbruck (2007-11)

Certifications and Licenses
=====
* Wilderness First Responder, Wilderness Medical Associates (2022-28)
* Single Pitch Instructor, American Mountain Guides Association (2024-27)
* PADI Open Water Diver
* Driver's Licenses: California and Germany

Coursework
=====
Algebraic Topology and Knot Theory  ∣  Artificial Neural Networks  ∣  Big Data and Statistical Learning  ∣  Climate Dynamics and Climate Change  ∣  Combinatorics and Graph Theory  ∣  Computational Biology  ∣  Computational Physics  ∣  Conservation Biology  ∣  Data Science for Engineers and Scientists  ∣  Dynamic Meteorology  ∣  Dynamical Systems  ∣  Earth Surface Processes  ∣  Econometrics  ∣  Environmental Risk Assessment  ∣  Ethical and Professional Science  ∣  Fluid Mechanics  ∣  General Equilibrium Theory  ∣  Geophysical Fluid Dynamics  ∣  Global Environmental Governance  ∣  Global Tectonics  ∣  Ice Sheet-Ocean Interactions  ∣  Ice and the Climate System  ∣  Independent Research in Earth Science  ∣  Information Theory  ∣  International Summer School in Glaciology  ∣  Leadership for Sustainability Transitions  ∣  Linear Algebra and Differential Calculus of Several Variables  ∣  Linear Algebra and Matrix Theory  ∣  Macroeconomics  ∣  Marine Chemistry  ∣  Master's Thesis in Mathematics  ∣  Mathematical Game Theory  ∣  Microeconomics  ∣  Natural Disasters  ∣  Observational Methods in Physical Oceanography  ∣  Organic Chemistry (Structure and Reactivity)  ∣  Paleoclimatology  ∣  Physical Oceanographic Data Analysis  ∣  Physical Oceanography  ∣  Probability Theory and Statistics  ∣  Real Analysis  ∣  Satellite Remote Sensing  ∣  Science Writing  ∣  Seismology  ∣  Simulation of Complex Systems  ∣  Stochastic Optimization Algorithms  ∣  Systems Biology  ∣  Thermodynamics of the Atmosphere  ∣  Vector Analysis and Differential Geometry  ∣  World Finance
