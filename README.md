# Metis_NLP 

**Comment on Deliverables**

I just now realized that something got messed up with dill importing, and some of the results of the codes are replaced with errors. Also realized that pyLDAvis interactive plot is not retained in the notebook. Although I can't fix this before the deadline, I will nevertheless solve these issues just in case. I apologize for any inconvenience.

**Topic Modeling of Foods Recipes**

(This is an abstracted from my writeup as a temporary description)

Sometimes it becomes a chore to decide what to eat, be it cooking or eating out. In such situation, most people start off with some general, vague idea for a food. Sometimes the idea can be main ingredients (meat, veggie, etc), or a broad categories (baked, soup, fried, etc). My aim was to collect various recipes and build a solid set of topics that can characterize such idea. With the topics at hand, I can utilize it to create a recommendation system for suggesting possible foods that matches what one might be thinking to eat.

Throughout the project I have secured a dataset of recipes for various types of foods, and then processed the dataset so it can be trained via unsupervised learning method of choice. As a result, the model yielded considerably well characterized topics for the recipes, with EDA and clustering analysis suggesting further tuning is desirable in order to gain even more distinctive topics. Although I didn’t manage to implement a recommendation model, the quality of topic models leave a good hope for one in a future works.

