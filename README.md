# Glass Identification

The aim of this project is to correctly classify classes based on their oxide content. The dataset for this project was sourced from the [UCI Machine Learning Repository.](https://archive.ics.uci.edu/dataset/42/glass+identification)

The dataset contains the following data (description taken from the docs):
   1. Id number: 1 to 214  
   2. RI: refractive index  
   3. Na: Sodium (unit measurement: weight percent in corresponding oxide, as 
                  are attributes 4-10)  
   4. Mg: Magnesium  
   5. Al: Aluminum  
   6. Si: Silicon  
   7. K: Potassium  
   8. Ca: Calcium  
   9. Ba: Barium  
  10. Fe: Iron  
  11. Type of glass: (class attribute)  
      - 1 building_windows_float_processed  
      - 2 building_windows_non_float_processed  
      - 3 vehicle_windows_float_processed  
      - 4 vehicle_windows_non_float_processed (none in this database)  
      - 5 containers  
      - 6 tableware  
      - 7 headlamps
---
The notebook contains the whole process including basic EDA up to model creation.

A pipeline was used to streamline the process, then went through hyper-parameter tuning to select the best algorithm for the model, and finally more hyper-parameter tuning to select the best parameters for said model.

After using cross-validation to judge the accuracy of the model, the final average test score was 81.89%.