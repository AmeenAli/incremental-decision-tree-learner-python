# incremental-decision-tree-learner

Definition from wikipedia: https://en.wikipedia.org/wiki/Incremental_decision_tree

"An incremental decision tree algorithm is an online machine learning algorithm that outputs a decision tree. Many decision tree methods, such as C4.5, construct a tree using a complete (static) dataset. Incremental decision tree methods allow an existing tree to be updated using only new data instances, without having to re-process past instances. This may be useful in situations where the entire dataset is not available when the tree is updated (i.e. the data was not stored), the original data set is too large to process or the characteristics of the data change over time (concept drift)."

This implementation is based on the Hoeffding Tree i.e. very fast decision tree (VFDT) which is describe by the paper "Mining High-Speed Data Streams" (Domingos &amp; Hulten, 2000). 

This is the first version of my python implementation of VFDT. I will try to improve on it. The code is tested on dataset bank.csv which is downloaded from UCI data base.

Another newly published paper extends this model： "Extremely Fast Decision Tree" by Manapragada, Webb & Salehi 2018. After I'm satisified with VFDT, I will modify it to get this EFDT. 
