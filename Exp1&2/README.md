# DeepLearningProject_Exp1&2 - Notebook

The notebook is designed to be straightforward to run and should work independently. This notebook conducts experiments 1 and 2, where samples are ordered in descending and ascending order according to their learning speed. Ensure all files are stored directly in the working directory.

## Steps:
1. **Dataset Loading**:  
   - Load the CIFAR10 dataset.  
   - Split it into 5 different tasks, each containing 2 classes.  

2. **Training and Testing**:  
   - Define the training and testing procedures.  
   - Specify the number of training epochs.  

3. **Baseline Experiment**:  
   - Run the default/baseline experiment.  
   - Print the corresponding results.  
   - Store the resulting M arrays for dataset sorting in later experiments.  

4. **Experiments 1 and 2**:  
   - Use the stored M arrays to sort the dataset in descending or ascending order based on learning speed.  
   - The results are stored in learning speed arrays prefixed with `ls..`.

---

# Results_ordered_exps - Notebook

This notebook presents the results (mean/std) from the report for experiments 1 and 2. Training and test accuracy were manually extracted and are stored in lists.

---

# Results_default_exps - Notebook

This notebook presents the results (mean/std) from the report for the default/baseline experiment.
