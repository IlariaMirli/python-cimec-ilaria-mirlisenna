# Python Final Project 

Final project for the CIMEC python course 2025.

## Study Overview 

The present study investigates the assessment of others' pain. Previous research has shown that Expectancy and Uncertainty can affect the perception of one's own pain (Yoshida et al., 2013; Loued-Khenissi et al., 2025). However, it remains unclear whether and how expectancy and uncertainty affect the assesment of others' pain. 

In this study, participants watched videos of males and females actors experiencing pain. The actors could either actually experience pain or simulate it. Participants were asked to provide two types of ratings:
1. Pain Ratings - how much pain they thought the actor experienced
2. Reality Ratings - how real they perceived the pain to be
  
Before giving their ratings, participants were shown a scale displaying pain ratings from 10 pilot participants.These pilot ratings were experimentally manipulated based on the median pain value actually given by the pilots. Specifically, the displayed scores could be 10 points higher or lower than the median score, and could have either high or low standard deviation (15 or 5). 

This manipulation allowed us to experimentally control both the expected intensity of pain ('Expectancy': High vs Low) and the uncertainty about the consensus ('Uncertainty': High or Low), prior to rating the actual videos. Crucially, the videos themselves could show either real or simulated pain ('Simulation': Real vs Posed). 

## Project Overview 

In this project, we:

1. **Load the datasets**
   - 'pilot_results': results from the pilot experiment, with information on the median values of each video;
   - 'exp_results': results from the main experiment, with Pain Ratings ('PainFinal') and Real Ratings ('VerFinal');
   - 'actors_info': information about the actors and corresponding videos.
     
2. **Derive and calculate measures of interest**
   Such as the median scores per video, actors' information, and all the information needed to create a comprehensive database for the      analyses.

3. **Run statistical analyses**
   Linear mixed models to analyze Pain Ratings ('PainFinal') and Real Ratings ('VerFinal') with Expectancy, Uncertainty, Simulation and     Actor Gender as predictors.

4. **Visualize results**
   Boxplots and pointplots are used to show data distribution and significant main effects and interactions.


## How to run the project

1. **Install required packages**
   Pandas, numpy, statsmodels, matplotlib, and seaborn Python packages are required for this project.

2. **Get the datasets**
   The project expects three Excel files:
   - 'pilot_results.xlsx'
   - 'experimental_results.xlsx'
   - 'videos_info.xlsx'
   Datasets are included in the repository.

3. **Run the notebook**
   - The project is organized in a modular way. Open the notebook and run the cells in order;
   - The notebook will load the data, run the mixed models, and produce the plots automatically.



   