#  Deep Learning and Skin Cancer

### John Peters

### 10/22/24

## Review 

The authors of the paper we read this time, wrote about formulating electronic health records (EHR) data relating to skin cancer into an image-like format such that a CNN could be applied. Their CNN worked well, with at best an AUROC of ~89%. The authors of this paper wanted to predict risk of non-melanoma skin cancer NMSC. The dataset was from the Taiwan National Health Insurance Research Database and was used in a deidentified and anonymized manner. Patients which had 3 years or more of health records were used in their study. Patients aged 20-90 years of age were used in this study, and information about interventions related to skin cancer and medications used were features for this CNN. These features were extended across the time dimension, to create a 3 year (x incrementing by weekly) overview of medical events of interest that could be convolved into a prediction. The CNN used, compressed each row into a 4 dimensional vector which was then pooled across the features and passed into a MLP. 

From an ML perspective, we commonly see ablation studies. We saw a bit of this with them training new CNNs for each of the subsets of features and then all of them, but I would have like to see more. There are a lot of questions I have about the size of the network, and its capacity here to fulfil its role. I would have loved some analysis on what groups the model predicted poorly against, well against and so on. The approach was interesting and not something I would've thought of a CNN for.

## Discussion Questions:

- Was the CNN they chose a good architecture or should they have modified the kernels, their shapes, the time-series length and so on?
- Did they do enough in the paper to show understanding on what the CNN was learning? Or is there a lot of interpretability issues with the way they presented this model?