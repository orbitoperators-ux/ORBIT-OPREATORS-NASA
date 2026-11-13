1. Project Summary
Dancing with the SARs – NISAR Surface Change Explorer is an interactive educational web application created by Team Orbit Operators for the NASA Space Apps Challenge 2026 challenge, “Dancing with the SARs.” The project introduces users to Synthetic Aperture Radar (SAR) and demonstrates how radar observations can help scientists understand changes taking place on Earth’s surface.
The application presents a guided exploration of the NASA–ISRO Synthetic Aperture Radar (NISAR) mission. Users can explore example locations and scenarios involving floods, ground deformation, vegetation changes, ice movement and agricultural change. Interactive visualizations, before-and-after comparisons, a time-series slider, radar product explanations and a learning hub help make complex remote-sensing concepts easier to understand.
The current version is a front-end educational prototype. Its radar-like scenes and change examples are simulated in the browser; it is not yet connected to live NISAR satellite granules or an operational data-processing pipeline. The application provides pathways to official NASA and ISRO resources so that users can learn more about the mission and its data.
2. Project Demonstration
A demonstration can be presented in the following sequence:
1.	Introduction screen: Begin with the project title, “Dancing with the SARs – NISAR Surface Change Explorer,” and briefly introduce the purpose of the application.
2.	NISAR mission overview: Explain that NISAR is a joint NASA–ISRO Earth-observation mission using two radar frequency bands to study changes on land, ice and other parts of the Earth system.
3.	Radar product selector: Show the available product categories and explain, at a high level, how radar intensity, interferometric products and pixel-offset products support different kinds of analysis.
4.	Interactive Explorer: Choose an example study area such as Maine Coast, North Dakota Farms, Wetland Delta, Volcano, Glacier or City Subsidence.
5.	Select a surface-change scenario: Demonstrate a scenario such as flooding, ground deformation, vegetation change, ice movement or agricultural change.
6.	Before-and-after comparison: Move the comparison slider to reveal the two example views and explain how visual differences can help users investigate possible surface changes.
7.	Time-series exploration: Use the timeline slider or playback control to move through the example observation sequence and discuss how repeated observations can reveal change over time.
8.	Geographic Mission Lab: Use the interactive world map to explore locations and scenario-based examples.
9.	Quality and confidence section: Show how observation intervals, surface characteristics and atmospheric or processing conditions can influence interpretation. Clarify that the displayed score is an educational heuristic, not a scientifically validated probability.
10.	Knowledge Hub and calculator: Finish by showing the learning resources and interferometric fringe calculator, then direct the audience to official NASA and ISRO mission resources.
3. Project Details
A. Detailed Description
The NISAR Surface Change Explorer is designed to make satellite radar science more accessible to students, educators and people interested in Earth observation. Instead of presenting radar remote sensing only through technical terminology, the application organizes the experience around places, surface-change scenarios and visual comparisons.
Synthetic Aperture Radar can collect information about the Earth’s surface using microwave signals. Unlike many optical satellite instruments, radar can acquire observations during both day and night and can operate through cloud cover. By comparing radar observations collected at different times, scientists can investigate changes such as flooding, ground movement, vegetation changes and ice dynamics.
The application uses interactive demonstrations to introduce these ideas. It combines a mission overview, example study areas, simulated radar-style images, time-series controls, product explanations and educational tools in one browser-based experience.
B. What Is Orbit Operators?
Orbit Operators is the team behind the project. The name reflects the team’s interest in satellites, orbital observation and the use of space-based technology to understand our planet. The team’s project focuses on turning the science and potential applications of NISAR into an approachable interactive learning experience.
C. How It Works and Key Technical Innovations
The current application is built with HTML, CSS and JavaScript. JavaScript manages the interactive controls and uses the Canvas 2D API to draw synthetic radar-like scenes. An SVG-based interactive map supports geographic exploration, while CSS animations are used for interface effects and visual presentation.
The main technical and educational elements include:
•	Synthetic radar-style visualization: Canvas 2D is used to generate illustrative radar-like scenes for the selected examples.
•	Interactive geographic exploration: an SVG map provides a visual way to explore example regions and scenarios.
•	Time-series controls: a slider and playback interaction demonstrate how repeated observations can be examined over time.
•	Before-and-after comparison: a movable divider allows users to compare two example views.
•	Radar product learning: the interface introduces different product families and explains their general purposes.
•	Quality-awareness concept: the quality section highlights factors that may affect interpretation, using a simplified educational score.
•	Interferometric learning tool: a fringe calculator helps users engage with the idea that radar phase differences can be related to surface displacement.
Important implementation note: these features currently demonstrate concepts using simulated or illustrative content. The app does not yet ingest and process actual NISAR satellite data products.
D. Use of Artificial Intelligence (AI)
The current version does not contain an implemented AI or machine-learning model. It does not automatically classify satellite imagery, detect changes in live NISAR data or generate operational alerts. The current visualizations and quality indicators are produced by front-end JavaScript logic and predefined example scenarios.
AI and machine learning are planned opportunities for future development. Possible additions include:
•	Change detection models that compare radar observations from different dates.
•	Classification of possible flood-affected, vegetated, agricultural, icy or deformed areas.
•	Anomaly detection to highlight unusual changes that may deserve further investigation.
•	AI-assisted explanations that translate technical observations into clear, accessible language.
•	A model-confidence display that communicates uncertainty and encourages users to validate results.
Any future AI output should be validated against suitable reference data and clearly communicate uncertainty. It should support expert interpretation rather than be presented as a guaranteed scientific conclusion.
E. NASA Data and the NISAR Mission
NISAR stands for NASA–ISRO Synthetic Aperture Radar. It is a joint Earth-observation mission developed by NASA and the Indian Space Research Organisation (ISRO). The mission uses two radar frequency bands, allowing scientists to study a wide range of changes on the Earth’s surface.
Mission element	Description
NASA contribution	The L-band radar system and associated mission contributions.
ISRO contribution	The S-band radar system and associated spacecraft and mission contributions.
L-band	Approximately 1.25 GHz frequency and about 24 cm wavelength; useful for observing features and structures that interact with longer-wavelength radar.
S-band	Approximately 3.2 GHz frequency and about 9.4 cm wavelength; provides complementary information at a shorter wavelength.
Orbit and coverage	The mission is designed for systematic, repeated observations of the land and ice-covered regions of Earth.
Repeat observations	A nominal 12-day repeat cycle supports monitoring changes over time.
Swath	The wide imaging swath is designed to support broad-area observations.

Mission fact-check note: commonly cited mission specifications include a launch on 30 July 2025 aboard GSLV-F16, an orbit of approximately 747 km, a swath wider than 240 km and a 12 m radar reflector. Confirm the latest official NASA and ISRO mission pages before using precise specifications in a formal presentation.
NISAR data products referred to in the project’s learning material include:
•	RSLC – Radar Single-Look Complex.
•	RIFG – Radar Interferometric product.
•	RUNW – Radar Unwrapped Interferogram.
•	GSLC – Geocoded Single-Look Complex.
•	GCOV – Geocoded Covariance product.
•	GUNW – Geocoded Unwrapped Interferogram.
•	GOFF – Geocoded Offset product.
•	SME2 – A mission product identifier used in NISAR product documentation.
Useful official and mission-related resources:
•	NASA NISAR mission: https://science.nasa.gov/mission/nisar/
•	ISRO NISAR mission: https://www.isro.gov.in/ISRO_EN/Mission_GSLVF16_NISAR_Home.html
•	Alaska Satellite Facility (ASF) search: https://search.asf.alaska.edu/
•	NASA Earthdata search for NISAR: https://search.earthdata.nasa.gov/search?q=NISAR
•	NISAR documentation: https://nisar-docs.asf.alaska.edu/
4. Ten Key Features and Additional Modules
1. Dual-band radar learning
Introduces the complementary roles of NISAR’s L-band and S-band radar systems and explains why using two wavelengths can provide richer information about the Earth’s surface.
2. Flood-monitoring demonstration
Uses an example scenario to show how radar observations can help identify changes associated with inundation. Calm open water often produces relatively low radar backscatter, although conditions such as wind, vegetation and built structures can change the response.
3. Ground-deformation exploration
Introduces the use of repeat-pass interferometry (InSAR) to investigate subtle changes in the position of the ground, such as those associated with subsidence or volcanic activity.
4. Forest and vegetation-change examples
Explains how radar observations can help study vegetation structure and changes in forested areas. Radar response depends on wavelength, vegetation structure, moisture and viewing geometry.
5. Glacier and ice-movement examples
Demonstrates how repeated radar observations can support the study of glacier movement and changes in ice-covered regions.
6. Agriculture and soil-moisture context
Uses farm-region examples to introduce how radar observations can contribute to monitoring agricultural landscapes and surface conditions. Actual soil-moisture retrieval requires appropriate data processing and validation.
7. Geographic Mission Lab
Provides an interactive map-based area for exploring example regions and connecting geographic locations with different Earth-observation scenarios.
8. Before-and-after radar comparator
Allows users to move a slider between two illustrative observations to make visual comparison easier.
9. Confidence and quality assessment
Introduces factors such as observation timing, surface characteristics, atmospheric effects and processing conditions. The current score is heuristic and educational, not a validated probability or operational quality metric.
10. Knowledge Hub and interferometric fringe calculator
Provides learning content and a simple calculator to help users understand radar interferometric fringes and the relationship between phase information and surface displacement.
5. Technology Stack and Application Architecture
Technology / component	Role in the current application
HTML	Defines the structure and content of the web application.
CSS	Controls layout, visual styling, responsive presentation and animations.
JavaScript	Handles user interactions, scenario selection, controls and application logic.
Canvas 2D API	Draws the synthetic radar-like scenes used in the educational demonstrations.
SVG	Supports the interactive map and scalable map graphics.
Browser-based front end	Allows users to access the prototype through a modern web browser without a dedicated desktop installation.

The current architecture is front-end only. A backend, live data ingestion service, geospatial processing pipeline and deployed machine-learning service are not currently implemented.
6. Problems the Project Addresses
Challenge	How the project responds
SAR concepts can be difficult for beginners.	Uses guided explanations, visual examples and interactive controls.
Radar products can feel technical and unfamiliar.	Introduces product categories and their general purposes in a learning-oriented interface.
Surface change is easier to understand visually.	Provides before-and-after and time-series demonstrations.
Earth observation covers many different environments.	Offers example scenarios involving coasts, farms, wetlands, volcanoes, glaciers and cities.
Users may overlook data quality and uncertainty.	Introduces factors that can affect interpretation through an educational quality-awareness module.
Official mission data can be difficult to discover.	Provides pathways to NASA, ISRO, NASA Earthdata and ASF resources.

7. Unique Selling Points (USPs)
•	A single interactive interface brings together NISAR mission learning, SAR concepts and Earth-surface-change examples.
•	The project uses scenario-based exploration rather than relying only on long blocks of technical explanation.
•	It introduces both radar intensity concepts and interferometric ideas.
•	The combination of a map, time-series controls and before-and-after comparison encourages active exploration.
•	It includes an explicit quality-awareness concept so users are reminded that radar interpretation depends on conditions and data quality.
•	It is designed as an accessible educational starting point that can be extended with real NISAR data in future versions.
8. Future Scope and Planned Improvements
•	Connect to official NISAR data access services and retrieve real, appropriately licensed mission products.
•	Build a backend data pipeline to search, download, preprocess and manage satellite observations.
•	Integrate geospatial processing tools and workflows, potentially including Python-based processing, ISCE3 and GIS software such as QGIS.
•	Develop validated change-detection workflows for floods, deformation, vegetation, ice and agricultural applications.
•	Add machine-learning models for classification and anomaly detection, with transparent validation and uncertainty reporting.
•	Provide downloadable maps, charts and reports for selected study areas.
•	Add user accounts or project workspaces if persistent study-area management becomes necessary.
•	Improve accessibility, mobile responsiveness and multilingual learning content.
•	Add dashboards that distinguish simulated examples from observations derived from real satellite data.
9. Expected Impact
The project aims to make NISAR and SAR remote sensing easier to explore for students, educators and the wider public. By connecting mission information with visual examples of floods, deformation, vegetation, ice and agricultural change, it can help users understand why repeated satellite observations matter.
As the application develops and integrates validated real data, it could become a useful educational and exploratory platform for learning about Earth-system monitoring. Any operational use, including hazard monitoring or decision support, would require reliable data integration, scientific validation, appropriate quality controls and expert review.
10. How the Project Stands Out
The project’s main strength is the way it combines several learning interactions in one place: mission introduction, dual-band radar concepts, map-based scenarios, simulated radar imagery, time-series exploration, before-and-after comparison, product explanations and quality awareness. Rather than claiming to be a complete scientific processing system, the current prototype focuses on helping users understand the concepts and potential applications of NISAR.
11. Conclusion
Dancing with the SARs – NISAR Surface Change Explorer, developed by Orbit Operators, is an interactive educational project that introduces the capabilities and applications of the NISAR mission. Through visual demonstrations and guided exploration, it helps users learn how Synthetic Aperture Radar can support the study of changes across the Earth’s surface.
The current prototype establishes the user experience and educational foundation. The next major step is to connect the application with real NISAR data and validated geospatial processing workflows, with AI-based analysis considered as a future enhancement rather than a feature already implemented.
12. Important Accuracy Notes for Presentation
•	Say “simulated radar visualization” when describing the current radar-style images; do not describe them as actual NISAR satellite images.
•	The current application is not connected to live NISAR granules or a live NASA/ISRO API.
•	AI/ML-based detection and classification are proposed future features; no AI model is currently implemented.
•	The confidence or quality score is a simplified educational heuristic, not a scientifically validated probability.
•	The application demonstrates flood-related concepts but does not issue operational flood alerts.
•	Use official NASA and ISRO sources to verify mission specifications and current data-access details before presenting exact figures.
•	Distinguish clearly between features available in the current prototype and improvements planned for future development.
13. Short Presentation Script
“Hello everyone. We are Team Orbit Operators, and our project is Dancing with the SARs – NISAR Surface Change Explorer. Our aim is to make Synthetic Aperture Radar and the NISAR mission easier to understand through an interactive web experience. Users can explore example locations and learn how radar observations can help scientists study flooding, ground deformation, vegetation changes, ice movement and agricultural landscapes. The application includes simulated radar-style views, a before-and-after comparator, time-series controls, an interactive map, radar product explanations and a learning hub. Our current version is an educational front-end prototype; it does not yet process live NISAR data or use an implemented AI model. Our future goal is to integrate real NISAR observations and validated analysis workflows, and later explore AI-assisted change detection. Through this project, we hope to make satellite radar science more accessible and inspire people to understand how space technology helps us study our changing planet. Thank you.”
