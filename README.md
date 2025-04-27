Project Title:
Automated Coastline Extraction for Erosion Modeling in Alaska
Project Goals:
•	Develop an algorithm to automatically extract coastlines from satellite images.
•	Integrate this system into existing erosion modeling software.
•	Validate the tool using Alaska’s coastal data, providing real-world application examples.
•	Enable a platform for continuous tracking of coastline changes over time.

SYNOPSIS OF THE PROJECT

•	Summary:

This project aims to create an automated system to extract coastlines from satellite imagery to model and monitor coastal erosion along Alaska’s coastlines. With the accelerating effects of climate change, Alaska's coastal communities are at significant risk due to increasing erosion. Current tools lack the automation needed for efficient tracking, and this project will fill that gap by developing a machine learning and image processing tool for real-time coastline tracking.

•	Problem Statement:

The manual processes used to monitor the changes in the shorelines simply can't keep up with the rapid and relentless force of nature reshaping the coast. The urgency is clear, Alaska’s coastline is rapidly changing, and time is running out to act. By embracing satellite-based erosion monitoring, we can turn the tide. This is more than just data, it’s a lifeline for communities that deserve a future, a way to safeguard the places they call home and the ecosystems that sustain them.

•	Solution Alignment:

The solution aligns with the goals of the University of Alaska Anchorage's research in environmental studies and remote sensing. It will support ongoing erosion modeling projects and enhance the accuracy of predictions using real-time satellite data, providing decision-makers with valuable insights.

Timeline
Phases:
•	Community Bonding Period:
o	Introduction to the UAA research team and familiarization with the existing codebase.
o	Discuss project requirements and feedback from mentors.
•	Coding Phase 1 (Weeks 1-3):
o	Finalize project requirements and complete a design document.
o	Initial work on satellite image preprocessing for coastline extraction.
o	Research and select appropriate machine learning models for coastline detection.
o	Set up initial data pipeline for testing.
•	Coding Phase 2 (Weeks 4-6):
o	Implement coastline extraction algorithm using satellite imagery.
o	Begin integrating the model into a working prototype.
o	Start testing with available datasets from Alaska's coastal regions.
•	Coding Phase 3 (Weeks 7-9):
o	Improve the accuracy of the coastline extraction algorithm.
o	Begin full-scale testing with real-world datasets.
o	Develop data visualization tools to present coastline change over time.
•	Final Evaluation (Weeks 10-12):
o	Complete the final version of the tool and ensure full functionality.
o	Write documentation for users and developers.
o	Submit the tool for mentor review and perform final testing.
o	Prepare a final report and presentation summarizing the project.
Motivation: I have a deep interest in polar science especially the north pole open-source software development. This project presents an exciting opportunity to apply my skills in python and scientific disciplines, fieldwork expertise, and soft skills like communication and collaboration, essential for understanding and addressing global environmental challenges in the polar regions to contribute to real-world solutions for the urgent issue of coastal erosion in Alaska, aligning with my academic and professional goals.
________________________________________

Benefits to the Community

Helping the Open-Source Organization:
The project will contribute to the broader open-source community by providing an automated tool that can be adapted for use in other regions beyond Alaska, aiding in global coastal erosion monitoring. By integrating machine learning with satellite data, it can attract attention from other environmental research communities and open-source developers.
Usefulness Beyond GSoC:
Beyond GSoC, the tool can be extended to include additional features, such as incorporating more data sources or refining the algorithm to improve accuracy. It could also serve as the foundation for further projects aimed at addressing climate change and environmental conservation, which are critical topics worldwide.
________________________________________
Technical Details & Approach

Implementation:
•	Image Preprocessing: Use open-source tools like OpenCV or Scikit-image to clean and process satellite images.
•	Coastline Detection: Implement a machine learning model (like U-Net or other image segmentation networks) for coastline detection.
•	Model Training: Use a pre-labeled dataset of coastal imagery from Alaska to train the model.
•	Data Integration: Integrate with GIS platforms for real-time tracking of coastal changes.
•	Validation: Compare model results with ground truth data to measure accuracy.
Technologies & Libraries:
•	Python (for processing and machine learning)
•	TensorFlow/Keras or PyTorch (for deep learning models)
•	OpenCV (image processing)
•	QGIS or GeoPandas (for geographic data handling)
•	Docker (for environment setup)

Challenges:

•	Data Quality: Inconsistent satellite image quality could make coastline detection difficult. Solution: Preprocess images to reduce noise and improve consistency.
•	Model Accuracy: Deep learning models may require fine-tuning to perform optimally. Solution: Regular validation with ground truth data and model adjustments.

________________________________________
11) Skill Set
    
•	Python: Extensive experience with Python, including data analysis and machine learning tasks.
•	Geospatial Data Processing: Familiar with libraries like geopandas, rasterio, and shapely for handling satellite imagery and geospatial data.
•	Machine Learning: Experience working with machine learning models, particularly for image segmentation tasks (e.g., CNNs), and using frameworks such as tensorflow and keras.
•	Satellite Imagery Processing: Worked with multi-band satellite data (e.g., Landsat, Sentinel, and PlanetLabs imagery) to extract meaningful environmental data.

