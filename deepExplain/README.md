# deepexplain

Welcome to the GitHub repository of our tutorial on explainability in machine learning!

#####
Write an introduction on why explainability is important for deep learning here
#####

This readme is intended to help navigate the tutorial that is organized in a modular manner.



+ First, we will look at models that are interpretable by design: training a simple model where the weights can be interpreted by a human ! [here](01_intro_interpretability_by_design.ipynb)

+ The method after that aims at hiding pieces of the input and looking at the changes that it implies in the output. Combined with deconvolutions (the reverse operation of the convolution), it is a cool method for looking at a popular image analysis model : the CNN. The notebook for these methods can be found [here](02_deconv_occ_final.ipynb)


+ Then, we will dig deeper into more sophisticated methods for explaining deep learning models, [shapley values](03_Explainable_AI_With_SHAP.ipynb) and [CAM-based Methods](04_CAM_based_Methods.ipynb).



+ Finally, another method is [finding similar inputs](05_similar_inputs.ipynb). If the network makes a mistake on a test input, we can see which training inputs are similar from network's point of view. The results can show us what features the network does not use in classification.  
