# Neural_Network_Charity_Analysis
## MODULE 19 - NEURAL NETWORKS & DEEP LEARNING MODELS

### OVERVIEW
The purpose of this module was to build on the last 2 modules material on Supervised & Unsupervised Machine Learning and take these to the next level of Neural Networks, which is a Machine Learning technique that is modeled after the inner workings of neurons in the human brain.

### RESULTS
#### DATA PROCESSING:
* WHAT VARIABLE(S) ARE CONSIDERED THE TARGET(S) FOR YOUR MODEL?
* IS_SUCCESSFUL

* WHAT VARIABLE(S) ARE CONSIDERED TO BE THE FEATURES FOR YOUR MODEL?
* APPLICATION_TYPE
* AFFILIATION
* CLASSIFICATION
* USE_CASE
* ORGANIZATION
* STATUS
* INCOME_AMT
* SPECIAL_CONSIDERATIONS
* ASK_AMT

* WHAT VARIABLE(S) ARE NEITHER TARGETS NOR FEATURES, AND SHOULD BE REMOVED FROM THE INPUT DATA?
The EIN and NAME variables were initially removed as part of the pre-processing of the data.  Later as part of the attempts to improve on the model's performance, the SPECIAL_CONSIDERATIONS variable was also removed.

#### COMPILE, TRAIN & EVALUATE THE MODEL:
* HOW MANY NEURONS, LAYERS AND ACTIVATION FUNCTIONS DID YOU SELECT FOR YOUR NEURAL NETWORK MODEL, AND WHY?
* ATTEMPT 1: TWO LAYERS
![MOD19 CHALLENGE DEL I ATTEMPT 1](https://user-images.githubusercontent.com/99851509/181381912-143ef2fe-82a7-4f91-835c-fef410792b9e.png)

* ATTEMPT 2: INCREASED TO THREE LAYERS
![MOD19 CHALLENGE DEL III ATTEMPT 2](https://user-images.githubusercontent.com/99851509/181381950-212e9ceb-ccd1-4fe5-9d69-51430400c929.png)

* ATTEMPT 3: INCREASED THE NUMBER OF NEURONS PER LAYER
![MOD19 CHALLENGE DEL III ATTEMPT 3](https://user-images.githubusercontent.com/99851509/181381977-d37e7a39-a3d8-4434-92c7-0718d273cb8f.png)

* ATTEMPT 4: DECREASED THE NUMBER OF NEURONS PER LAYER
![MOD19 CHALLENGE DEL III ATTEMPT 4](https://user-images.githubusercontent.com/99851509/181381999-7c00dbef-9886-46d3-a538-18092ee33919.png)

* WERE YOU ABLE TO ACHIEVE THE TARGET MODEL PERFORMANCE?
All attempts to improve on the performance of the model failed.  There was no significant increase in the accuracy levels; in fact, they decreased with each subsequent attempt.  The highest accuracy actually came with the initial attempt at 72.9% (73%).

* WHAT STEPS DID YOU TAKE TO TRY AND INCREASE MODEL PERFORMANCE?
As outlined in the PNGs above, the second attempt increased a layer and the number of neurons.  The third attempt further increased the number of neurons per level substantially.  For the fourth attempt we went in the opposite direction and reduced the number of neurons per level.  This again did not yield any significant increase in performance.

### SUMMARY
* SUMMARIZE OVERALL RESULTS
* FIRST ATTEMPT RESULT: 72.94% (73%)
* SECOND ATTEMPT RESUTL: 72.69% (73%)
* THIRD ATTEMPT RESULT: 72.68% (73%)
* FOURTH ATTEMPT RESULT: 72.66% (73%)
Looking at the performance accuracy levels side-by-side, we see that the levels actually decrease with each attempt at optimization, but in each attempt they yielded roughly the same percentage (rounded up) at 73%.  Increasing the number of layers as well as increasing and decreasing the number of neurons did not change the performance accuracy with any significance.

* RECOMMENDATION & EXPLANATION FOR A DIFFERENT MODEL
Attempts to get to the goal of 75% by increasing the original dataset may yield some results.  The attempts made for this challenge portion did not yield any significant results so further attempts would most likely prove fruitless.  This in itself would prove the necessity for a different model altogether.
Personal Challenges: This module's concepts were quite hard to grasp as we only received a basic understanding of Supervised & Unsupervised Machine Learning and its models.  While not grasping all of the coding and the ever important "why" we do it, it gave me a basic understanding of some of the concepts related to neural networks.  The layers and how they are modeled after the human brain seems, again simple in concept.  The actual application of which is where I still need help to understand.  With more intensive reading hopefully I will get to that level.
