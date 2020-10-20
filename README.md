# Final Project
Solo team

Order of operations for using the jupyter notebooks:
- First, I used the "compiling" notebook to import all of the 2010-2019 data. This notebook no longer needs to be referenced as new data becomes available.
- Second, I used the "updating" notebook to append the 2020 data, and I continue to update/run this notebook each week.
- Third, I used the "modeling" notebook to scale and encode the data, and then run the built-in machine learning models. These turned out to be relatively inaccurate, so I no longer run this notebook.
- Lastly, I use the "analyzing" notebook to determine weekly predictions and update accuracy figures. 


## Update for Segment 3:
- Presentation on Google Slides has been updated to reflect the new model accuracy numbers and updated visualizations based on an adjustment in the code.
- There is now a secondary model that can be used to find weaknesses/blindspots in the primary model. The secondary model identifies if there are any teams that are consistently over- or underestimated by the primary model. I used this secondary model to override my primary model's prediction that the Bengals would beat the Colts this week. The secondary model indicated that the Bengals have been overestimated by the model and the Colts have been underestimated, so I overrode the prediction and, as anticipated, the Colts won.
- I now have a second repo for the website aspect of this project. I have purposefully separated these repos because I do not want people to have access to the code, in the event that I plan to commodify my algorithm, and gitpages requires me to keep the published repo "public." As soon as this course is over, I am going to make this repo private and use it only to log the code while the product of this code is visualized in the other repo.
- Link to other repo: https://github.com/amnichols93/PickSys
- Link to gitpage: https://amnichols93.github.io/PickSys/

## Update for Segment 2:
Presentation Slides: https://docs.google.com/presentation/d/1BMbp83ryxox5Rm0n8Au2fhnJJwBQ1P3ISek7oBGqSko/edit?usp=sharing
This presentation offers an update on the project so far. Some slides only include key words, since I don't plan on presenting with a lot of text on the screen.

## Preliminary README.md for Segment 1:

The goal of this final project is to predict the weekly outcomes of NFL games for the remainder of the season with at least 82% accuracy (14 out of 17 games), and to present these weekly predictions on a website via gitpages.

The reason I chose 14/17 as the target accuracy is because I am currently in a weekly pool for straight wins and the highest weekly score so far was 14 wins in week 2. The typical winning number is approximately 12, but I don't want to take any chances.

### Steps to complete this project:
- Download weekly data for the last ten years of each franchise (from Pro Football Reference, cited in each team's section of the "Compiling" notebook)
- Edit those Excel files so they are compatible with csv format
- Load the csv files into a jupyter notebook
- Add coaching staff (from Pro Football Reference) and starting quarterback data (from Wikipedia) to each franchise's dataframe
- Create master dataframe from each franchise's individual database
- Refine the values as needed (some columns may prove to be useless or a hinderance on the machine learning model)
- Run the data through the machine learning model using different models and encoding techniques to achieve the highest accuracy rate
- Create the html file and display the data/predictions by week (this will be where the visualizations are displayed)

### Current Status
As of the Segment 1 submission, I have the code written for compiling the franchise data and for processing the master dataframe through some machine learning models, however I still need to download/reformat the csv files for 6 out of 32 teams so I can actually save the master dataframe.
