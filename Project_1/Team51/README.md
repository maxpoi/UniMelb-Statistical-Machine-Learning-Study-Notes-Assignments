"Final Approach" is the code file for our final approach.
This runs for about 24 hours.
This file also contains the process of trying out Logistic Regression and MLP as classifiers.

"Large Graph" is the code file for trying to improve "Final Approach", by simply sampling a large graph.
This runs for >24 hours, and we run out of time to test its performance.

"Naive Sampling Method" is the code file for one of our initial try-outs.
This sampling method is so naive that it is wrong so much. 
The logic behind it is completely incorrect. But it at least gives us a starting point.

*Other experiments are not included, e.g, trying a different libraries of Node2Vec, hyper-parameter tuning process, and etc.*
*Because we changed the codes directly*
*all codes mentioned above should be able to run by clicking "running all" without issues. (Hope so)*

"lightGBM-Zixin" is another approach dicussed in "Alternative Sampling Method" and first paragraph of "Alternative feature embedding - Local similarities" in our report. The approach runs as follows:
1. Build a graph with all training nodes.
2. Gathering some samples from the training nodes.
3. Feature generation based on local similarity.
4. Predict by LightGBM model.

"15thSep_Combine" is another appraoch in "Alternative Sampling Method" and second paragraph of "Alternative feature embedding - Local similarities" in our report.