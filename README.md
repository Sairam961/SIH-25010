# Smart India Hackathon Workshop
# Date: 25-09-2025
## Register Number: 25000694
## Name: R.Sairam
## Problem Title
SIH 25010: Smart Crop Advisory System for Small and Marginal Farmers
## Problem Description
A majority of small and marginal farmers in India rely on traditional knowledge, local shopkeepers, or guesswork for crop selection, pest control, and fertilizer use. They lack access to personalized, real-time advisory services that account for soil type, weather conditions, and crop history. This often leads to poor yield, excessive input costs, and environmental degradation due to overuse of chemicals. Language barriers, low digital literacy, and absence of localized tools further limit their access to modern agri-tech resources.

Impact / Why this problem needs to be solved

Helping small farmers make informed decisions can significantly increase productivity, reduce costs, and improve livelihoods. It also contributes to sustainable farming practices, food security, and environmental conservation. A smart advisory solution can empower farmers with scientific insights in their native language and reduce dependency on unreliable third-party advice.

Expected Outcomes

• A multilingual, AI-based mobile app or chatbot that provides real-time, location-specific crop advisory.
• Soil health recommendations and fertilizer guidance.
• Weather-based alerts and predictive insights.
• Pest/disease detection via image uploads.
• Market price tracking.
• Voice support for low-literate users.
• Feedback and usage data collection for continuous improvement.

Relevant Stakeholders / Beneficiaries

• Small and marginal farmers
• Agricultural extension officers
• Government agriculture departments
• NGOs and cooperatives
• Agri-tech startups

Supporting Data

• 86% of Indian farmers are small or marginal (NABARD Report, 2022).
• Studies show ICT-based advisories can increase crop yield by 20–30%.

## Problem Creater's Organization
Government of Punjab

## Theme
Agriculture, FoodTech & Rural Development

## Proposed Solution
A advisory platform that runs on an AI algorithim, available via an smartphone app, SMS or in voice calls in a variety of regional languages. The system will:

Keep feeding live, local weather data, satellite images and the history of crop performance to the system 24/7.

Process soil-test reports and user-uploaded field images with machine learning models to identify any deficiencies in crops and early signs of pest/disease.

Customised advisories on choice of crops, timing of sowing, irrigation scheduling, fertiliser use and pest management.

It also supplies market-price alarms and demand predictions to help in the best time of harvest and crop type selection,while also offering a voice based interactive session during which low-literate users can be assisted with alerts and prompts.

This solution provides agronomic knowledge to small-scale farmers, gives out scientific recommendations and  are presented in an understandable manner.

## Technical Approach
Python's machine learning capabilities and Django's ecosystem are used in the Smart Crop Advisory System's Django-centric architecture.

The system incorporates TensorFlow for AI-powered crop advisory services, Django Channels for real-time features and the Django's framework (REST) for the API development.

So the technologies used are:

Python 3.9+,

Django 5.0+

Django REST framework (DRF) 3.14+

Django Channels

TensorFlow 2.x (open source Machine Learning platform)

Scikit-learn, NumPy/Pandas (for Machine Learning algorithims)

PostgreSQL (for database operations)



## Feasibility and Viability
Quick prototype development is made possible by established machine learning frameworks and publicly available datasets (soil maps, weather archives).  Infrastructure overhead is decreased by cloud platforms such as AWS that support IoT and have serverless features.

Field deployment and training are guaranteed through collaboration with regional extension services and cooperatives, distributing soil testing kits by utilising government infrastructure.

For economic feasability,subscription-based model can be employed for NGOs and cooperatives, free basic advisory model for farmers through which farmers can save 15–20% on input costs by using less fertiliser and pesticide, which will offset any small service fees.

## Impact and Benefits
Implementing this model can potentially:

Increase crop yeilds by around 20-30%.

Reduce input costs by around 15-20%

Enhance small farming incomes by around 20-25% annually via the suggestions provided by the model.

Promote sustainable practises while empowering low literate farmers and regional farmers with the help of virtual guidance available in multiple regional languages.

## Research and References
AI – DRIVEN CROP ADVISORY SYSTEM, https://ijnrd.org/viewpaperforall.php?paper=IJNRD2503437

A comprehensive analysis of the advances in Indian Digital Agricultural architecture,   https://www.sciencedirect.com/science/article/pii/S2772375523001478

Django's Framework, https://www.bairesdev.com/blog/diving-into-django-rest-framework/

Django ORM, https://www.geeksforgeeks.org/python/django-orm-inserting-updating-deleting-data/

TensorFlow, https://en.wikipedia.org/wiki/TensorFlow
