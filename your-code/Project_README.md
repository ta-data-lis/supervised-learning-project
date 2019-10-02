<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# App Store vs Google Play?
*Miguel Vian and Alona Sorochynska*

*Data Squad 21 Lisbon 20/09/19*

## Content
- [Project Description](#project-description)
- [Hypotheses / Questions](#hypotheses-/-questions)
- [Dataset](#dataset)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

<a name="project-description"></a>

## Project Description
This Prject goal is to practice what we have learned in Business Intelligence and Tableau. By making chosing Dataset(s) and making a Story through the visualizations in Tableau.

<a name="hypotheses-/-questions"></a>

## Hypotheses / Questions
How are the two shop ecosystems different?
Who spends more money? And on what? 
Who is most engarged?

<a name="dataset"></a>

## Dataset
Data sets removed from Kaggle

[Dataset Apple](https://www.kaggle.com/ramamet4/app-store-apple-data-set-10k-apps#AppleStore.csv)
[Dataset Google](https://www.kaggle.com/gauthamp10/google-playstore-apps#Google-Playstore-Full.csv)

<a name="workflow"></a>

## Workflow
Data collection --> Data cleaning --> Data visualization(Exploration phase) --> Create Dashboard --> Present Story

We decided to compare two data sets from different app stores. First we had to clean unwanted columns from both data sets. Then we cheked for duplicates in terms of App Names. Then cheked for errors in the columns like non numeric ratings and non text categories. The Category/Genre columns had different values for each store, so we made the adjustments to make them equal. After all that cleaning it was time to concatenate. But before concat we reanme the remaining columns to the same names and made a column to have an identifier for each store. A column full of "A"s to mark the apple store and one of "G"s for the google one.
Finally we concatenated and exported it as a excel to be read by Tableau. //n
Inside Tableau we tried to make every graph that could expose the differences between both stores. Manly relating things like Price, Categories and Ratings

<a name="organization"></a>

## Organization
Trello 

<a name="links"></a>

## Links
Include the links to your repository, slides and trello. Feel free to include any other links associated to your project. 

[Repository](https://github.com/naivm/Project-Week-6-Tableau)  
[Tableau Public](https://public.tableau.com/profile/miguel.vian#!/vizhome/Project6-StorevsPlay/Dashboard1)  
[Trello](https://trello.com/invite/b/ywUwW4In/4c9c5895f202192bd3cf0c2896f4817b/project-5)  
