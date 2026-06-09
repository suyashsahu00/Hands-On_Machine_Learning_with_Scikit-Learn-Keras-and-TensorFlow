# Chapter 1 Exercises

**1. How would you define Machine Learning?**
**Machine Learning** is the science and art of programming computers so they can learn directly from data.

**2. Can you name four types of problems where it shines?**
It shines in problems requiring **long lists of hand-tuned rules**, **complex problems** with no good traditional solution, **fluctuating environments**, and extracting **insights from large amounts of data**.

**3. What is a labeled training set?**
A **labeled training set** is training data fed to the algorithm that includes the desired solutions or targets.

**4. What are the two most common supervised tasks?**
The two most common supervised tasks are **classification** and **regression**.

**5. Can you name four common unsupervised tasks?**
Four common unsupervised tasks are **clustering**, **visualization**, **dimensionality reduction**, and **anomaly detection** (or association rule learning).

**6. What type of Machine Learning algorithm would you use to allow a robot to walk in various unknown terrains?**
**Reinforcement Learning** is the algorithm used to train a robot to walk.

**7. What type of algorithm would you use to segment your customers into multiple groups?**
A **clustering algorithm** (which is a form of unsupervised learning) would be used to segment customers.

**8. Would you frame the problem of spam detection as a supervised learning problem or an unsupervised learning problem?**
Spam detection is a **supervised learning problem**, specifically a classification task.

**9. What is an online learning system?**
An **online learning system** is capable of learning incrementally on the fly by processing data instances sequentially.

**10. What is out-of-core learning?**
**Out-of-core learning** is a technique used to train models on huge datasets that cannot fit into a single machine's main memory, typically by processing data in chunks.

**11. What type of learning algorithm relies on a similarity measure to make predictions?**
**Instance-based learning** algorithms rely on a similarity measure to compare new cases to learned examples.

**12. What is the difference between a model parameter and a learning algorithm’s hyperparameter?**
A **model parameter** is adjusted by the model itself during training to fit the data, whereas a **hyperparameter** is a setting of the learning algorithm that is set before training and remains constant.

**13. What do model-based learning algorithms search for? What is the most common strategy they use to succeed? How do they make predictions?**
Model-based algorithms search for **optimal parameter values** to fit the data. They succeed by optimizing a **performance measure** (like minimizing a cost function). They make predictions by applying the resulting model to new cases.

**14. Can you name four of the main challenges in Machine Learning?**
Four main challenges include **insufficient training data**, **nonrepresentative data**, **poor-quality data**, and **irrelevant features** (along with overfitting and underfitting).

**15. If your model performs great on the training data but generalizes poorly to new instances, what is happening? Can you name three possible solutions?**
This is called **overfitting**. Three solutions are: **simplifying the model** (e.g., using regularization), gathering **more training data**, and **reducing noise/outliers** in the data.

**16. What is a test set and why would you want to use it?**
A **test set** is a separate portion of data used specifically to estimate the model's generalization error on instances it has never seen.

**17. What is the purpose of a validation set?**
A **validation set** is a held-out set used to evaluate multiple candidate models, allowing you to safely tune hyperparameters and select the best model.

**18. What can go wrong if you tune hyperparameters using the test set?**
If you tune hyperparameters using the test set, you adapt the model to that specific data, meaning it will likely **generalize poorly** to actual new data.

**19. What is repeated cross-validation and why would you prefer it to using a single validation set?**
**Repeated cross-validation** uses many small validation sets and averages the results; it is preferred because relying on a single validation set risks it being too small (causing imprecise evaluations) or too large (taking away too much data from the training set).
