1. Raw files with tabular entry per household with cleaned up features. These can be used for calculating PCA

Ethiopia: ethiopia_v23_normed.csv
Tanzania: tanzania_2014_v8_cleaned.csv
Uganda: uganda_2013_cleaned.csv

2. Average and std-err of features across clusters. The images and the corresponding csv files are stored in:
See plot.ipynb how these figs are created using these csv files.

Country: image folder, average stats file
Ethiopia: figs/, outputs_v23_prod7_crop_sales/crop_sales___output___ethiopia_2015_avg.csv
Tanzania: tanzania_figs/, tanzania_v6_7_crop_sales/crop_sales___output_avg.csv
Uganda: uganda_figs/, uganda_v2_crop_sales/crop_sales___output_avg.csv

3. Variations of features across clusters, for e.g: % change from cluster 1 to cluster 2.
Similar columns exist for 2-3, 3-4, and average.
I currently sort by each of these columns and pick most varying features per column.
Ethiopia: variations_ethiopia.xlsx
Tanzania: variations_tanzania.xlsx
Uganda: variations_uganda.xlsx

3. Regression coefficients with lower and upper bounds:
Ethiopia: outputs_v23_prod7_crop_sales/coef_crop_sales___output___ethiopia_2015.csv
Tanzania: tanzania_v6_7_crop_sales/coef_crop_sales___output.csv
Uganda: uganda_v2_crop_sales/coef_crop_sales___output.csv

4. The lifts of movement across clusters are plotted from threshold_lift.csv. 
Currently, this is only for Ethiopia, waiting for cleaned up versions for different years for Uganda/Tanzania.
