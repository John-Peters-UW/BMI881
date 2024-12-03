# Gene Enrichment papers

### John Peters

### 12/2/24

## Review 

We read two papers this week. The first paper, was a 2003 paper that pursued a thought about how to increase statistical power in identifying the expression of a set of genes responsible for some phenotype by using a prior defining that expression is modulated in groups (pathways) of genes, and those group expression can be combined in order to detect gene expression. The authors were able to use this type of analysis of pathways, with close examination of homologs in mice, to identify new pathways that were significantly downregulated in coordination in diabetic muscle. Testing without grouping by known pathways, showed no significance in genes and their expression levels by tissue type.

The other paper we read, seemed to be of the same technique. This paper however, used this technique with cancer related data (of leukemia, lung cancer and some others). This paper cites the first approach, and improves upon it. It uses techniques we talked about previously, with controlling for false positives with FDR in order to add robustness.  

I'm not quite sure what to think of these papers. A lesson I learned, and continue to learn, is that priors are worth a lot. Being able to use knowledge from a domain in order to add power to any sort of experiment is a common theme, and I think one that these papers highlight well. 

## Discussion Questions:

- Could this style of test produce invalid/misleading information, depending on if the priors weren't perfectly correct?

- Following up on my first question, how wrong could your priors be, and with a coincidence that they are all somewhat correlated, make you produce unknowingly off results that seem to have a good p value?
