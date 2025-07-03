# PROJECT-1
OVERVIEW

The Project focuses on the Aviation Industry with the main aim being to 
review the Aviation dataset and come up with an understanding of how the aviation Industry 
is. The dataset simply highlights all the accidents that have happened in the Aviation 
Industry and the Aircrafts involved.

Business Understanding

The company which I work for aims at venturing into the aviation industry. They intend to purchase and operate 
 airplanes for commercial and private enterprises. They intend on knowing:
 - The most common aircrafts for both commercial and private enterprises.
 - The risks associated with operating aircrafts.
 - The Survival rates in case of a crash
 - Aircrafts levels of damage in case of a crash.
 - The trend in aircrafts crashes to date.


Data Understanding and Analysis

The dataset being used for the analysis is from the National Transportation Safety Board 
and it includes aviation accidents data from 1962 to 2023. The dataset is available for 
download from the kaggle website.

Initially the dataset contained 88,889 rows and 31 columns before cleaning. After going through the dataset
some columns were dropped as there were not very essential for our analysis. However some columns
were not dropped for this reason i.e the 'Aircraft.Category' column. This column was dropped because 
it contained many missing values ,about 70%. Being a categorical type of data there was options of
filling it with the mode but the data could have been biased. Columns with numerical data like 
the injuries column contained null values so the best step was to assume that in that particular entry there 
was no acitivity so it was filled with zero.
- make(categorical) - this is a column that contains the name of the aircraft in question.

- Aircraft Damage(categorical) - This column contains the level of damage suffered by an aircraft
after a crash.

- Broad Phase of Flight( categorical)- This contains the phases in which most of the crashes occured.

Conclusions
- According to the analysis the findings are that the total number of injuries be it minor or major have reduced meaning over the recent past crashes have been minimal.
- After accidents the damage levels of most aircrafts is substantial(76%).
- It is recommended that the company purchases aircrafts from 2000 henceforth but those with the lowest risk rate. As many accidents have happened during the climb and landing Phase it is recommended that as preparation for purchase is done maybe more training could help deal with this.
The link to my tableau story is https://public.tableau.com/app/profile/samuel.njogu2458/viz/AviationProject_/Dashboard1?publish=yes
