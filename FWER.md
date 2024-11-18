#  Propensity

### John Peters

### 11/19/24

## Review 

The paper we read this time was on controlling for the false discovery rate (FDR) during multiple significance testing. The standard way to do this during the time of the paper, somewhat confusingly, was to control another metric called the familywise error rate (FWER). Controlling the FWER also controlled the FDR, in that if the FWER was lowered, then so was the FDR (to a similar degree, I think). The author's suggested that instead of controlling the FWER, the FDR could be directly controlled. By doing this, the FWER is also controlled, but to a much less strict manner than the converse relationship. Controlling the FDR also has other benefits like it being less costly to do so, which was a main complaint during the paper: The current FWER standard was complex and even though standard many did not follow it because of its complexity.

I think the paper is an okay paper that's presenting mechanisms to deal with issues we have during multiple statistical testing. I do not have any perspective on the difficulty of implementing these methods, and if this paper was responsible for a paradigm shift in the ...*insert subfield of statistics here*... variant of statistics. I'm also uncertain what is meant about statistical power here, and the specifics to why the more strict method FWER would have less power under some scenarios where FDR controlling is just better. 

## Discussion Questions 

- Have we moved onto a different metric in even more recent times (re: the thursday paper may answer this)?

- Is there minimum number of tests that should be considered before any controlling is necessary? Or that maybe moving from FDR to FWER is advised?