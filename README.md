# Final Project
Solo team

## Preliminary README.md for Segment 1:

The goal of this final project is to predict the weekly outcomes of NFL games for the remainder of the season with at least 82% accuracy (14 out of 17 games), and to present these weekly predictions on a website via gitpages.

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
As of the Segment 1 submission, I have the code written for compiling the franchise data and for processing the master dataframe through some machine learning models, however I still need to download/reformat the csv files for 7 out of 32 teams so I can actually save the master dataframe.
