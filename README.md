DSI-2022
Africa DSI-2022
Module 3 Twist - NLP

Topic: Analysing crisis events in West Africa - 2021

1. Introduction

This project is my submission for the DSI Module 3 Twist Challenge on Natural Language Processing (NLP). For this project, I used open-source data from the Armed Conflict Location & Event Data Project (ACLED.

Armed Conflict Location & Event Data Project (ACLED) is a disaggregated conflict collection, analysis and crisis mapping project. ACLED’s aim is to capture the forms, actors, dates and locations of political violence and protest as it occurs across states. The ACLED team conducts analysis to describe, explore and test conflict scenarios, and makes both data and analysis open to freely use by the public.

The project focuses on West Africa for the year 2021. West Africa has 16 countries, 10 of which are French speaking.

2. Objectives

The objectives of the project are:

- Analysis of the crisis events in W/A for 2021 with particular emphasis on event types and fatalities in this notebook (using plotly)
- Translation of notes coulumn from English to French using huggingface translation transformers. For each event, there is a notes column which has a summary of the details of the event in English. The translation is mainly to aid people in French-speaking West Africa to understand the circumstances of these events.
- Further analysis of data in Tableau which is flexible for dashboards and deployment. Output from the translation is used for a French labelled dashboard

3. Data

All data for this project has been downloaded from the ACLED website using their export tool - https://acleddata.com/data-export-tool/. Data downloaded covered all event variables for Western Africa (West Africa) for the year 2021. 

- The downloaded data has been saved in the data folder as acled21_westafrica.csv
- The initial translated French results has been saved in the data folder as acled21_fr.csv
- The final file with french translations appended with column name 'notes_fr' is saved as acled21_westafrica_final.csv. This file is extracted to tableau for analysis.

4. Deliverables

The deliverables for this project are:
- Python notebook: Detailed analysis of events and translation of english notes to french. Some plotly charts are not showing in github. Kindly follow the colab link to see all plots until I am able to sort out the issue - https://colab.research.google.com/drive/1FrDHoBPRLcRg-ZsnNGCcth-gpk0_Ytfs?usp=sharing
- PowerPoint presentation - https://1drv.ms/p/s!AtTvaR5DUZm4vAX2GHxoUz5GIvAo?e=IeIa5X
- Tableau: Further analysis of events using Tableau dashboard. The dashboard has been deployed at the following link https://public.tableau.com/app/profile/douglas.obeng4472/viz/ACLED-2021-West-Africa/Dashboard1?publish=yes. Switch between English and French and hover over maps to see labels in selected languages.

All deliverables have been saved in the github repository https://github.com/obengdouglas/DSI-2022/tree/main/module3-nlp-twist. Data used for this project is also saved in the same github repo
