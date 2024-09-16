# Reply to Vogelsang 

## 1st reply: No evidence that late-sighted individuals rely more on color for object recognition: Reply to Vogelsang et al.

Vogelsang et al. (2024) claim that individuals treated for congenital blindness via cataract removal surgery (Prakash patients) rely more on color cues for object recognition than age-matched controls. The evidence presented for this claim is based on an inappropriate statistical analysis of proportion data in a recognition task. We show that a variety of more suitable analyses provide, if anything, slight evidence in favor of the null hypothesis that patients and controls are similarly impaired by the removal of color information in an object recognition task. 

## 2nd reply: Still no evidence that late-sighted individuals rely more on color for object recognition: Reply to Vogelsang et al.

We thank Vogelsang et al. (2024) for their reply to our critique. However, we remain unconvinced that the experimental data presented in their paper supports their claim. First, applying a non-parametric test to the differences in percent correct, as in their reply, does not solve the ceiling problem. Second, there is indeed enough data to apply more appropriate models that assume binomial rather than Gaussian errors; these models provide evidence for the null hypothesis. Third, we note a design issue that undermines the causal inferences that can be drawn from the experimental data. Based on these statistical and design considerations, we reiterate that in our view, the empirical data do not support the claim that object recognition in Prakash patients is more impaired by color removal than controls.

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
