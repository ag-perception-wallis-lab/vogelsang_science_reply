# Vogelsang et al. reply

Vogelsang et al. (2024) claim that individuals treated for congenital blindness via cataract removal surgery (Prakash patients) rely more on color cues for object recognition than age-matched controls.  The evidence presented for this claim is based on an inappropriate statistical analysis of proportion data in a recognition task. We show that a variety of more suitable analyses provide, if anything, slight evidence in favor of the null hypothesis that patients and controls are similarly impaired by the removal of color information in an object recognition task. 

## Directory structure and usage

The code underlying our data analysis can be found in the scripts directory. This consists of two main parts: (1) a transformation plus t-test approach (carried out in a jupyter notebook), and (2) a mixed effects logistic regression (carried out in an R notebook). The raw and processed data files can be found in the data directory and a descriptive report of our analyses and findings can be found under publications. 

```shell
./vogelsang_science_reply
├── README.md
├───data
│   └───processed_data
├───figures
├───publications
└───scripts
```