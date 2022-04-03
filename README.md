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
![Tumor Weight is Positively Correlated with Tumor size in mice treated with Capomulin](images/corr_weight_tumor_capomulin)

If this is a project that is a webapp then maybe include some images of what it does as a demo-preview.  
<br>

