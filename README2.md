
The dataset that I have selected for this project contains information on every known satellite orbitting the Earth. 

This is a database compiled by the Union of Concerned Scientists. It contains information on more than 2000 live satellites. The dataset is updated "roughly quarterly." The following information is available in the dataset:

* Name of Satellite
* Country of origin
* Country of operator
* Operating organization
* Users
* Purpose
* Orbit type
* Orbit class
* Information about orbit (eccentricity, inclination etc)
* Date of Launch + Other launch details (location, launch vehicle etc.)
* Expected lifetime
* Contractor (with country)

Some interesting things that I noticed while exploring the data was the breakup of satellites by country, and purpose. Each satellite has numerous associated variables related to its own features or that of its orbit. In this project, I will try and determine the variables controlling the purpose that the satellite is being used for. Features will be engineered to allow use of orbital information in combination with any other information about the satellite available to create a predictive model that determines the purpose of a satellite based on these variables. 

Motivating question(s): 1) Predict the purpose of a satellite based on other information provided regarding Orbital information and other associated information. 

The features that you will be engineering in this project are perigee_type() and dayoflaunch(). Please look at notebooks 30-feature-engineering and 40-modeling to complete this task. Make sure to verify and assert that the functions work correctly based on issues #1 and #2 in the repository for this project. 