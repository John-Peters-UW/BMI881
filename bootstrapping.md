#  Bootstrapping

### John Peters

### 12/26/24

## Review 

In this paper, the authors use the bootstrap technique to show how the estimated standard deviation on linear models for datasets that contain certain types of finite-sample problems. 

The main example of this paper was a model that was created and run by the department of energy which estimated the fuel requirements of various regions for the subsequent year. A contribution of the paper was using this bootstrapping technique across time-series data, as well. While using bootstrapping to help understand how linear models were behaving on this data, the authors found that nominal standard errors were a very optimistic perspective on how the model was fitting the data to a three fold extent in the worse cases.

I find that this paper was okay. I couldn't really follow, with the time I allocated to reading and responding to this paper, all of the reasoning (not having read the original bootstrapping paper made it hard). I think the authors did a good job I think of separating the possible ways that the standard error could be so optimistic in the nominal case, and proving it was because of the method and not some other intrinsic part of the data. I think the authors could have done a better job of showing the 

## Discussion Questions:
- What's the difference between the jackknife, that this method was compared to?
- Why are bootstrap techniques only used on relatively simplistic models? I don't recall seeing this happen for models more significant than trees.