<br>

# Matplotlib Challenge
<br>

Analysis of four drug compounds effects on tumor size by using pandas dataframes and the matplotlib graphing library.  Results showed that Capsomulin had a significant and greater impact on tumor size after 7 weeks relative to a control and competitor brands.  
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

## Additional Analysis  (or Demo-Preview)
![corr_weight_tumor_capomulin](https://user-images.githubusercontent.com/66378414/161413067-b8f40ee6-8eeb-440d-8f77-9449c4e6133f.png)
![num_mice_drug_bar](https://user-images.githubusercontent.com/66378414/161413074-7a329869-e949-49f6-b2ef-e30f69b4ae6c.png)
![tumor_time_capomulin_line](https://user-images.githubusercontent.com/66378414/161413076-00ccc108-3013-4f03-be9f-2bb3038fdf88.png)
![tumor_vol_boxplot](https://user-images.githubusercontent.com/66378414/161413077-e811fe0f-65f2-4831-82e4-ba3d51aeea4a.png)
![mice_sex_pie](https://user-images.githubusercontent.com/66378414/161413078-989b6fdb-f5cc-465d-bb63-ff6f28bcaf4c.png)

If this is a project that is a webapp then maybe include some images of what it does as a demo-preview.  
<br>

