﻿# World Data League 2023

## Team Name

JKL & Frank

## 👥 Authors

* Joydeep Chatterjee
* Kate Crawford
* Lara Strachan
* Frank Novak

## ✨ Introduction (250 words max)

We aim to develop a predictive model that provides insights into the ecological factors that impact the density of flora, sessile fauna and mobile fauna in the Marine Protected Area (MPA) of Avencas, near Lisbon. 

A short-term evaluation (starting in 2010) resulted in the reduction of anthropogenic stress through data collection, fishing community input, and visitor education. For long-term efforts, researchers strongly advised the establishment of a monitoring program, involving monthly surveys conducted by two experienced observers, for a minimum duration of 10 years. 

Our model aims to support these efforts, providing insights on ecological factors related to species abundance. Understanding the key influencing factors is essential for effective coastal zone management in response to climate change.

## 🔢 Data (250 words max)

Our model utilizes climatological covariates based on almost a decade of observations, providing sufficient data for estimating the long-term condition of the MPA. The analysis relied on comparing historical observations over the years to serve as absence data, aiding in interpreting changes in abundance measurements.

While acknowledging the limitations of current sampling methods and the potential biases in our models and predictions, we were informed by the initial analysis conducted by the researchers who provided the dataset. They observed a decrease in densities of mobile species between 2013 and 2015, potentially influenced by the Hercules storm of 2014.

## 🧮 Methods and Techniques (250 words max)

Our primary objective was to prepare the data for forecasting regressors that could offer valuable insights into feature importances. To achieve this, we initially focused on ecological factors and removed individual species occurrences, as models with high dimensions are challenging to analyze effectively. 

We manually partitioned the data into training and validation sets to specify a cutoff date (Timestamp('2016-05-23 00:00:00')) that allows for an evaluation of recovery after the Hercules storm. This date was chosen as a stamp for when the pier was re-established in the Summer of 2016.

A pipeline for preprocessing and modeling was then constructed for reproducability. We evaluated two classifiers, namely a linear regressor and a random forest regressor. The latter generated a tree structure, enabling the calculation of feature importances and identifying the key factors that influence the abundance of mobile species.



## 💡 Main Insights (300 words max)
One significant finding pertained to Cladophora sp., an invasive species known for its aggressive behavior and high mortality impact on rival organisms. What stood out was its ability to generate elevated concentrations of dissolved phosphorus, a vital nutrient for algae growth.

Further research highlighted the potential implications of Cladophora sp.'s invasion. Its dominance in aquatic ecosystems can disrupt the balance of nutrient availability, potentially leading to harmful algal blooms and the decline of native species. Understanding the mechanisms driving Cladophora sp.'s invasiveness and its ecological impacts will be crucial for effective management and conservation efforts in affected areas.

Secondly, we examined the effects of extreme weather events, specifically the impact of storms like Hercules in 2014, on a Marine Protected Area (MPA). This investigation revealed compelling evidence of how such storms can significantly influence the environment and species within the MPA. Seen in the data, it required almost 6 months after the storm passed for the abudence levels to reach levels once had before.

## 🛠️ Product

In this section you should define the product that can be created by using the model developed. Make sure that the product solves the problem in a holistic way, takes into account the constraints of the topic entities (specifically mention these constraints).

### Definition

Define in **one sentence** what product(s) could be built out of the code you produced.
Example: A dashboard that assists in traffic control

realtime data

### Users

Describe who would be the users of your product and for what purpose would they use it.
Example: Traffic controllers use the dashboard during their work to better plan where to dispatch resources

### Activities

* Predicts the most likely ecological factors for mobile species abundance.
* Suggests the how storms, like Hercules in 2014, impacted the environment and species in the MPA.

### Output

Describe what the product outputs to the users and how it does that. You can add mockups and/or visualisations.

Example: Location of the accident on a map and suggest the fastest route from the dispatch centre.

### Scalability

Discuss the scalability and the ease of implementation of your solution in the scope of the topic entity. Feel free to mention any road blocks you see and how they could be solved.

## 🌍 Social Impact Measurement


### Outcome

If the outputs are your immediate results, describe your long-term results. What do you want your product to achieve? What ''good'' are you creating?
Example: To decrease response time from dispatchers so that people in urgent need receive help faster.

### Impact Metrics

From the outcome, define **2 to 4 metrics** that measure, whether you are achieving that outcome or not.
Example:

* Average Dispatch Time
* Average Distance from Accident Location and Dispatch Center

### Impact Measurement

Since you cannot wait to see the impact of your product, estimate it. You can do that by either using the estimations/predictions of your model, market research, products from proxy industries and/or similar locations, etc.


Example:
* *Based on model predictions*: Our model estimates a decrease of 6 minutes of the average dispatch time and a decrease of the average distance of 200 metres
* *Based on proxy products*: Similar studies in other cities show that the dispatch time can be decreased by as much as 13 minutes, depending on the traffic intensity of that city.

### Citations

Cuddington, K., M.-J. Fortin, L. R. Gerber, A. Hastings, A. Liebhold, M. O'Connor, and C. Ray. 2013. Process-based models are required to manage ecological systems in a changing world. Ecosphere 4(2):20. http://dx.doi.org/10.1890/ES12-00178.1

Ferreira, A, Alves, AS, Marques, JC, Seixas, S. Ecosystem response to different management options in Marine Protected Areas (MPA): A case study of intertidal rocky shore communities, Ecological Indicators, Volume 81, 2017, Pages 471-480, ISSN 1470-160X, https://doi.org/10.1016/j.ecolind.2017.06.028.

Mannocci, L, Boustany, AM, Roberts, JJ, et al. Temporal resolutions in species distribution models of highly mobile marine animals: Recommendations for ecologists and managers. Diversity Distrib. 2017; 23: 1098– 1109. https://doi.org/10.1111/ddi.12609
