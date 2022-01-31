# article_plot
 
 [Ex_model_comparison.ipynb](https://github.com/ziemianska/article_plot/blob/main/Ex_model_comparison.ipynb)

1. Uploaded data are loaded, modules are imported.
2. Dataframe is preprocessed (melted).
3. np.arcsinh() is applied to calculate inverse hyperbolic sine, element-wise for all arr https://www.geeksforgeeks.org/numpy-arcsinh-in-python/
4. Data types are checked.
5. Subplots are generated for the substance conditioned tested in experiments described in https://doi.org/10.1111/ejn.15144

FIGURE 7 
from the 
Jabłońska, J., Szumiec, Ł., Zieliński, P., & Rodriguez Parkitna, J. (2021). 
Time elapsed between choices in a probabilistic task correlates with repeating the same decision. 
The European journal of neuroscience, 53(8), 2639–2654. https://doi.org/10.1111/ejn.15144

As in aforementioned publication:

Figure 7 shows comparison of reinforcement learning model fits based on ΔAIC values.
 Panels correspond to: 
 (a) alcohol, 
 (b) saccharin, 
 (c) alcohol + saccharin, 
 and (d) water. 
 Each point represents an individual mouse, the boxplots show medians, 1st and 3rd quartiles. 
 Each box plot in the alcohol and saccharin groups corresponds to 28 animals, alcohol + saccharin — 13, and water — 14.
 
 AIC value ( Akaike's information criterion) was used to assess the goodness of fit.
 Overall, the models approximated the observed behavior better than a purely random choice approach for all rewards except the water control. 
 Moreover, there were larger differences in the goodness of fit for rewards that produced stronger preference (i.e., saccharin and alcohol + saccharin). 
 The best scoring models, “hybrid” and “Qd + hybrid,” shared two features: separate learning rates for positive and negative outcomes and a fictitious update of the expected value of the nonselected alternative.
