<br>

# Matplotlib Challenge
<br>

Analysis of four drug compounds effects on tumor size by using pandas dataframes and the matplotlib graphing library.  Results showed that Capomulin and Ramicane had a significant and greater impact on tumor size after 7 weeks relative to 8 other drug treatments brands.  
<br>  

## Methods Used  
Central Tendencies, Boxplots, Scatter Plots, Linear Regression
<br>

## Technologies
Python, PANDAS, Matplotlib
<br>

## Data Source
Data found in:
<ul>
<li>`data/Mouse_metadata.csv`"</li>
<li>`data/study_results.csv`"</li>
  </ul>
<br>
## Installation
Code was tested using Python 3.8.  The environment also needs pandas and matplotlib. The environment was setup as follows:

```bash
conda create -n envpy38 python=3.8 anaconda
source activate envpy38
jupyter notebook
```
If environment does not include pandas or matplotlib then install the following from terminal:
```bash
conda install pandas
conda install matplotlib
```  
<br>

## Analysis
An initial look at the data shows us that the mouse population is evenly divided by sex.
![mice_sex_pie](https://user-images.githubusercontent.com/66378414/161413078-989b6fdb-f5cc-465d-bb63-ff6f28bcaf4c.png)
We also see that each drug treatment had roughly the same number of treatment timepoints - we can proceed with a more in-depth analysis assuming equal data size for each drug treatments.
![num_mice_drug_bar](https://user-images.githubusercontent.com/66378414/161413074-7a329869-e949-49f6-b2ef-e30f69b4ae6c.png)

An examination of central tendencies showed that four drug treatments, Capomulin, Ramicane, Infubinol, Ceftamin, had the smallest mean tumor volume, indicating that these were the most effective of the 10 treatments.

The four above drugs were then analyzed more closely - the following boxplot shows that Capomulin and Ramicane had the smallest tumor average volume at the final timepoint.
![tumor_vol_boxplot](https://user-images.githubusercontent.com/66378414/161413077-e811fe0f-65f2-4831-82e4-ba3d51aeea4a.png)

Further analysis was conducted on Capomulin. First, a mouse was chosen as a case study - while tumor size increased for the first 20 days, it significantly decreased, below baseline, over the remaining timepoints of the study.
![tumor_time_capomulin_line](https://user-images.githubusercontent.com/66378414/161413076-00ccc108-3013-4f03-be9f-2bb3038fdf88.png)

Finally, average weight of mice treated with capomulin was plotted against overall tumor size. A pearson correlation was conducted on the data, which showed a positive correlation (r=0.84). A linear regression model was generated, showing this trend.
![corr_weight_tumor_capomulin](https://user-images.githubusercontent.com/66378414/161413067-b8f40ee6-8eeb-440d-8f77-9449c4e6133f.png)
