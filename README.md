![HackathonBanner](https://github.com/MODDSAIAccelerators/SustainableSmartBuildingsHackInBox/blob/main/Program%20Assets/HackathonBanner.PNG)
At Microsoft, we are focused on driving innovation by helping customers address today’s most pressing issues to reach their sustainability goals. One of these critical focus areas includes smart buildings and cities.
Microsoft has had several high-visibility partnerships around smart buildings, helping our customers set and attain their environmental, social, and governance (ESG) goals which expands their potential success factors. Companies with high ESG performance have 4.7X higher operating margins than those that do not.

The Sustainable Smart Buildings Hackathon helps develop the skills and fluency to build repeatable and customizable first-party solutions for environmental monitoring, energy consumption, facility operating efficiency, and energy source optimization. 

# Assets for a successful hackathon execution
You can find curated materials for you to organize and execute the sustainable smart buildings hackathon successfully. Specifically, you have access to materials for each role as listed below. 
## General Hackathon Assets can be found [here](https://github.com/MODDSAIAccelerators/SustainableSmartBuildingsHackInBox/tree/main/Program%20Assets), in this folder you can find the following:
    * Smart Buildings Hackathon-in-a-Box
    * Challenges overview
    * Branding
    * FAQs
    * Proctor & Hacker badges
## Proctor Assets can be found [here](https://github.com/MODDSAIAccelerators/SustainableSmartBuildingsHackInBox/tree/main/Proctor%20Assests), in this folder you can find the following:
    * Give and Gets
    * Recruitment email communication
    * Registration form
    * Proctor guide
    * Train the Trainer guide
    * Proctor training video
    * Proctor 3-day sample agenda
    * Post event survey
## Hacker Assets can be found [here](https://github.com/MODDSAIAccelerators/SustainableSmartBuildingsHackInBox/tree/main/Hacker%20Assests), in this folder you can find the following:
    * Gives and Gets
    * Recruitment email communication
    * Registration form
    * Hacker guide
    * Hacker preperation resources
    * Hacker 3-day sample agenda
    * Post event survey

# Hackathon Overview: Predict Shop Floor Occupancy

Contoso Corporation is a construction company building shop floors for many manufacturers across the United States. They are interested in incorporating sustainability into their shop floor design as they embark on smart building development. To support this effort, Contoso has invested in IoT technology, installing sensors on 51 of their shop floors. As a launching ground for their sustainability journey, Contoso needs to understand the data collected by their sensors and the factors influenced by the occupancy rate. Using this knowledge, they want to regulate temperature, humidity, light, and monitor CO2 levels on their shop floors.

* This hackathon enables attendees to access the IoT sensors data stored in Azure Blob that Contoso has collected to predict if a room has any occupants. The dataset contains a week’s worth of records (datetime in UNIX Epoch format) for each of the 51 shop floors. This data includes information about CO2 concentration, humidity, room temperature, and luminosity.
The dataset has been obfuscated to prevent any leak of IP or identities from prior analysis, and thus the column variables will be general in nature.

* During “hacking”, attendees will focus on understanding the data, searching for trends, exploring correlations, describing the characteristics and impact between C02, temperature, humidity, and light on occupancy rate.  Hackers will determine which of these collected features could potentially help in determining if a shop floor is occupied.  

* This hackathon enables attendees to help identify the type of features that could prove most beneficial in the development of smart buildings.

* This hackathon simulates a real-world scenario where a construction company is striving to incorporate sustainability in future shop floor designs.
By the end of the hackathon, attendees will have built a classification model to predict if a shop floor is occupied.

## Technologies
* Python
* Azure Machine Learning Studio (Auto ML, Designer can also be used for this challenge but not necessary) or Jupyter notebooks
* Azure Storage - Azure Blobs

## Prerequisites
In these challenges, you will provision an Azure Machine Learning workspace and you will then use the Compute Instance to explore data interactively.

To complete the challenges, participants will need background knowledge of the following:
* Language: Python
* Tools: Azure Machine Learning Studio (Auto ML, Designer can also be used for this challenge but not necessary); Jupyter notebooks, Azure Storage Explorer
* Basic Data Science Knowledge: Data Exploration and Classification model building 

Other basics would be:
* A web browser
* A Windows, Linux, or Mac OS X computer
* The challenge files for this course

# Hackathon Challenges
This hackathon comes with three challenges. Each of the three challenges is designed to help individuals to apply data science best paractices to build a model to predict shop floor occupancy. Each challenge comes with individual tasks that can be viewed in this [student guide](https://github.com/MODDSAIAccelerators/SustainableSmartBuildingsHackInBox/blob/main/Hacker%20Assests/StudentGuide.docx).

### Challenge 1: Load the data set to Azure Machine Learning Workspace
A sophisticated data-collection device, the sensor, is a crucial and fascinating component of the Internet of Things (IoT). The purpose of sensors is to collect analog data from the physical world and translate it into digital data assets. Sensors are measuring just about any aspect of the physical world. The calibration of sensors allows them to be tailored to application-specific functions. In this dataset, sensors have been calibrated to measure temperature, humidity, CO2 concentration, luminosity and PIR (motion detection) with accuracy. This sensor data is tasked with capturing information relevant to a shop floor design, so the data can be used to make process improvements for the purpose of increasing carbon and energy efficiency in shop floors. 

      This challenge is designed to achieve the following learning objectives:
         * How is sensor data collected in Azure Blobs?
         * How to ingest data and wrangle the data to generate insights from it?

### Challenge 2: Data exploration 
Data exploration is an approach to understand what is in a dataset and the characteristics of the data. These characteristics can include size or amount of data, completeness of the data, correctness of the data, possible relationships amongst data elements or files/tables in the data. Data Exploration is aimed at understanding the nuances of the data, and defining basic metadata (statistics, structure, relationships) for the data set that can be used in further analysis. 

      This challenge is designed to achieve the following learning objectives:
         * What are the best ways to prune the data?
         * How to visualize relevant relationships amongst features across dataset?

### Challenge 3: Build a classification model to predict shop floor occupancy
A machine learning model is a file that has been trained to recognize certain types of patterns. You train a model over a set of data, providing it an algorithm that it can use to reason over and learn from those data. Once you have trained the model, you can use it to reason over data that it hasn't seen before and make predictions about those data.

      This challenge is designed to achieve the following learning objectives:
         * What machine learning models are suitable for this and similar problem statements?
         * How to interpret the performance of a machine learning models that are tuned to predict future unseen data?

# Value Proposition
* Develop fluency in sustainability topics especially in carbon and energy space to have meaningful conversations with customers and partners
* Join the community of Microsoft Sustainability Champions and get badged

# Technical Scenarios
* Environmental Monitoring
* Energy consumption / embodied carbon monitoring and reporting
* Facilities/equipment operating efficiency optimization
* Energy source optimization

## License
Copyright (c) Microsoft Corporation

All rights reserved.

MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the ""Software""), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED AS IS, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE


## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
