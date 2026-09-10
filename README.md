# ECE2112 PA 3
## Instructions
Use the same cars.csv dataset supplied for Experiment 3. Write the solutions in one Jupyter Note-
book and import Pandas as pd. The dataset contains the Model column together with the vehicle
variables used in the original experiment.

• Load the CSV file into a DataFrame named cars.

• Use Pandas subsetting, slicing, indexing, and Boolean conditions. Do not manually type any
   requested table or answer.

• Do not modify values in cars; create a new DataFrame or Series for each requested subset.

• Preserve the row order of the source dataset unless stated otherwise.

• Display every requested result in an executed notebook cell.

### --------------------------------------------------------------------------------------------------------

### A. POSITIONAL AND LABEL-BASED SLICING
<img width="1082" height="875" alt="image" src="https://github.com/user-attachments/assets/fc0cc118-e3ec-47e8-8991-31f0582f5bf0" />


### Explanation:

For a. to c., I first inspected the overall layout of my dataset by checking cars.shape to see its total dimensions and cars.column to get the list of all feature names. Next, I used iloc to extract datasets 6 through 10. I finally filter out thew newly created row subset down to only five specific columns.


### --------------------------------------------------------------------------------------------------------

### B. MODEL LOOKUP
<img width="946" height="518" alt="image" src="https://github.com/user-attachments/assets/9bc43ae3-dad3-4eaa-b0a0-60995db318c1" />


### Explanation:

For part a, this code helps me find the specific model Toyota Corolla and extract that whole row and that row only and display it. Part b works the same but only for specific columns and for a different model.


### --------------------------------------------------------------------------------------------------------

### C. MULTI-MODEL SUBSETTING
<img width="1112" height="532" alt="image" src="https://github.com/user-attachments/assets/54f230c9-a72a-46d2-8ce0-f102ea7b72c3" />


### Explanation:

I extracted multiple target models at once by matching it to Datsun 710, Lotus Europa, and Ferrari Dino. I also trimmed the results down to only five asked columns. Finally I had to verify the shape of my data frame by displaying its rows and columns.

