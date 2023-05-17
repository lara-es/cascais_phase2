# World Data League 2023


## Executive Summary Template
This executive summary is one of the mandatory deliverables when you submit your solution. Its structure follows the WDL evaluation criteria and it has dedicated sections where you should add information. Make sure your executive summary covers all the sections since it will be an integral part of the Insights Report and your evaluation. Make sure your content is relevant and straight to the point.
**There is no need to reach the maximum number of words.**


Instructions:


1. 🧱 Create a separate copy of this template and do not change the predefined structure
2. 👥 Fill in the Authors section with the names of allteam members
3. ✏️ Write your executive summary - make sure you write for a non-technical audience. 
4. 📄 Fill in all the text sections
5. 🗑️ Remove this section (‘Executive Summary Template’) and any instructions inside other sections
6. ⬆️ Upload the .md file to the submission platform.


## 🎯 Challenge
*Insert challenge name here*


## Team Name
(Insert Team Name Here)


## 👥 Authors
Include all the authors that have worked on this submission. It is not obligatory to include all the team members if not everyone has worked on it. This will not impact the evaluation in any way.
* Person 1
* Person 2
* Person 3


## ✨ Introduction (250 words max)
Provide a contextualization of the problem, together with an estimation of its size using real numbers and references. In this section you should demonstrate your understanding of the problem.

As marine ecosystems undergo global climate change, there is an increasing need to incorporate potential shifts in the distribution of marine taxa into management plans

We propose that the best models—those that effectively describe or predict marine animal distribution patterns at a desired temporal scale without utilizing unnecessarily high-resolution data—are obtained when the temporal characteristics of the animals’ distribution and environmental data sufficiently match the scale of the ecological question and the variability of the ecosystem


## 🔢 Data (250 words max)

Special attention should be put on any scaling mismatches, meaning cases where the spatial (or temporal) grain or extent doe not match between biodiversity and environmental data or within environmental data. In these cases, we need to make decisions about adequate **upscaling and downscaling strategies.**

**absence data** are rarely available. In such cases, adequate background data or pseudo-absence data needs to be selected.

for later model assessment we may wish to partition the data into training data and validation data (Hastie, Tibshirani, and Friedman 2009)

*Climatological datasets* divide the calendar year into shorter time slices such as days, weeks, months or seasons, and for each slice, apply a summary statistic (e.g., mean, variance, frequency or probability) to many (often at least 10) years of observations made during that slice to estimate the long-term state

Are contemporaneous covariates are necessary or climatological covariates are sufficient to model these associations?

we acknowledge that current sampling abilities and requirements lead to imperfect models and potentially biased predictions and practical recommendations are critically needed for ecologists and managers.

SDMs developed from climatological covariates are relevant for static management and used to predict important species habitats with a high potential for delineation of marine-protected areas and implementation of mitigation measures

[Source](https://onlinelibrary.wiley.com/doi/full/10.1111/ddi.12609)

## 🧮 Methods and Techniques (250 words max)
Tell us what methods and algorithms you used and the results you obtained.

Process-based modeling
Global change includes changes in climate, habitat connectivity and nutrient dynamics at various spatial and temporal scales.

the model should allow an exploration of how these changes affect outcomes. 

Changing the scale of a process can alter the relative importance of key drivers, or disrupt the process altogether.

Complex simulation models can be process-based, but a highly dimensional model will be difficult to analyze. As the number of estimated parameters increases, the size of the parameter space (i.e., the number of possible combinations of parameter values) increase

[Source](https://esajournals.onlinelibrary.wiley.com/doi/10.1890/ES12-00178.1)


## 💡 Main Insights (300 words max)
Explain what you discovered from addressing this problem, such as interesting facts or statistics.
*Write here*


## 🛠️ Product
In this section you should define the product that can be created by using the model developed. Make sure that the product solves the problem in a holistic way, takes into account the constraints of the topic entities (specifically mention these constraints).
### Definition
Define in **one sentence** what product(s) could be built out of the code you produced.
Example: A dashboard that assists in traffic control


### Users
Describe who would be the users of your product and for what purpose would they use it.
Example: Traffic controllers use the dashboard during their work to better plan where to dispatch resources


### Activities
Describe what features your product has.
Example:
* Predicts the most likely locations for traffic accidents
* Suggests the fastest route from dispatch centres


### Output
Describe what the product outputs to the users and how it does that. You can add mockups and/or visualisations.
Example: Location of the accident on a map and suggest the fastest route from the dispatch centre.

Torres et al. (2013) modelled the seasonal distribution of southern right whales (Eubalaena australis) by comparing the predicted habitat suitability maps with maps of shipping traffic to identify areas of increased risk of collision where mitigation measures could be implemented.

[Source](https://onlinelibrary.wiley.com/doi/full/10.1111/ddi.12609)
### Scalability
Discuss the scalability and the ease of implementation of your solution in the scope of the topic entity. Feel free to mention any road blocks you see and how they could be solved.
Macroscale (Figure 4)
animal distribution: Fisheries, historical catches, species coverage
enviro data: sum of in situ databases, climatological oceanographic covariates
temporal resolution: climatological 

[Source](https://onlinelibrary.wiley.com/doi/full/10.1111/ddi.12609)

## 🌍 Social Impact Measurement
This section will help to guide you on how to measure the impact of your product. Make sure that measurement is thoroughly quantitative, even if you need to estimate some of the numbers.

The protection and restoration of coastal wetlands can be more cost effective than barrier construction as a means to reduce storm damage (Halpern et al. 2007, Costanza et al. 2008, although see Francis et al. 2011).

[Source](https://esajournals.onlinelibrary.wiley.com/doi/10.1890/ES12-00178.1)
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