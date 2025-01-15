DeepLearningProject_Exp1&2 - Notebook:

The notebook should be straightforward to run and work on its own. This notebook runs the experiments 1 and 2 where samples are ordered in descending and ascending order according to their learning speed. All the files should be stored directly in the working directory.
We first load the CIFAR10 dataset and split it into 5 different tasks always containing 2 classes. Afterwards we define training and test procedure as well as the number of training epochs.
The next cells run the default/baseline experiment and print the corresponding results. The stored M arrays will later be used to sort the dataset.
The following cells run experiment 1 or 2 depending on the method parameters. The previously stored M arrays are used to sort the dataset in descending or ascending order.
The learning speed results are always stored in the learning speed arrays starting with “ls..”.

Results_ordered_exps - Notebook:

This notebook prints the results (mean/std) from the report for the experiments 1 and 2. Training and test accuracy were manually extracted and are therefore stored in lists.

Results_default_exps - Notebook:

This notebook prints the results (mean/std) from the report for the default/baseline experiment.