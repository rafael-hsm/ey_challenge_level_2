# Overview

- Be part of a movement to make science more accessible. Join this challenge to help create open-source solutions to address the UN Sustainable Develpment Goal 2: Zero Hunger.
- More than 800 million people regularly go to bed hungry.
- Climate change is one of the main causes of hunger.
- Better understanding crop yields and how to maximize efficiency of crops is an urgent need.
- Though the scale of the problem is global, we must start by understanding a single crop at a single location.
- You will use radar and optical satellite data from Microsoft's Planetary Computer to build a toool to identify rice crops in Vietnam.

# Goal

- The goal of Level 1 is to predict the presence of rice crops at a given location using satellite data. By the time you complete this level, you will have developed a rice crop classification model, which can distinguish between rice and non-rice fields.

# Why rice production in Vietnam?

- In two words: applicability and imperative.
- Vietnam is among the world's leading rice producers and the Vietnamese obtain more than half their total calories from rice.
- Also, Vietnam is among the most vulnerable to climate change, losing an estimated U$ 10bi in 2020 to climate change according to the World Bank.
- More broadly, rice is a staple food for more than four billion people and the livelihood for a fifth of the world's population. But both the amount of land available for rice and the yield growth rates are in decline with irrigated rice yields in developing countries forecast to decrease by 15% due to climate change.
- Simply put, solutions focused on this staple are scalable and could transform global rice production.

# Completing the challenge

- The time required to complete this level is approximately 30 hours.
- This challenge is to predict the presence of rice crop at 250 geo locations (latitude and longitude) in the An Giang province of Vietnam using satellite data.
- You will be given an example Jupyter notebook with a preliminary F1 score of 0.55. The notebook connects to public facing data sources on Microsoft's Planetary Computer. The output of the notebook is a .csv file that can be uploaded to the challenge platform, which you can improve over the course of the challenge.
- Watch this video to learn [how to get started and make a submission](https://challenge.ey.com/getting-started-2023/help) and claim your spot on the EY Open Science Data Challenge ranking board.
- Watch this video for some tipos on [how to improve your model performance.](https://challenge.ey.com/challenge-2023-level-2/help).
- Opportunities for improvement include but are not limited to; explore other bands from Sentinel-1-RTC, use combinations of many bands from the Sentinel-1-RTC, generate various vegetation indices to be used as features, extract VV and VH band values for an entire year and summarize using time-series metrics, explore the approach of building a bounding box around the given latitude and longitude positions, try other classification algorithms, and hypeparameter tuning.
- The output will be a rice crop classification model that can distinguish between a rice and non-rice field.
- Identifying areas where rice is growing is important for prioritizing actions intended to esure food security.