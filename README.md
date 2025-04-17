## Inspiration
- Uber is one of the largest tech companies that revolutionized the ride-share business.
- We were curious at what motivated drivers to actually start driving for Uber and how Uber maintains their driver fleet to meet supply & demand of consumers needing to go from place A to B.

## What it does
- We explored a Stratascratch data set provided and incorporated an outside data set for fuel efficiency to train our model. We first explored data to see what features we should incorporate into our ML and then compared various ML algorithms.

## How we built it
- We built an ML algorithm to determine what influences a new Uber driver to start actually driving for Uber and helping Uber generate more revenue.
- We preprocessed data, feature engineered, data cleaning, and eventually generated different types of ML models and compared them using comparison techniques like ROC AUC.

## Challenges we ran into
- Not enough time
- Missing value (NULL) data management

## Accomplishments that we're proud of
- We made our presentation pretty :)

## What we learned
- We learned that sign-up/logistic timing is important and that how we clean and process the data prior to training the model is super important. For example, we originally had trained our model on all the data before filtering for only eligible drivers.
- We also learned how to work as a team to solve a data science problem (it was our first datathon!)

## What's next for What's driving drivers?
**Model Expansion**
- Would explore additional algorithms such as NN and comparing their performance to what we have
Try Advanced Ensemble Techniques
Better data management

**Data Imbalance Management Improvement**
- Learn how to handle the class imbalance between drivers and non-drivers better since this data set was largely dominated by non-drivers, including ones that were defaulted to non-drivers due to ineligibility
