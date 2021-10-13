## Ligand-based virtual screening work‐flow

### 1. Build a classification model using deep learning

For distinguishing active from inactive molecules. 
  - 1.1 Evaluating the training data and ensuring that the molecular weight, LogP, and charge distributions
were balanced between the active and decoy sets.
  - 1.2 Making the necessary adjustments to the chemical structures of the decoy molecules.
  - 1.3 Generating a set of chemical features for the molecules being used (we used _DeepChem GraphConv_ featurizer).
  - 1.4 Training.
  - 1.5 Evaluating.


### 2. Predict activity of a set of commercially available molecules.
  - 2.1 Filtering problematic molecules, we used a set of computational rules encoded as SMARTS patterns.
  - 2.2 With our list of desired molecules, we can predict over those molecules.
  - 2.3 Selecting the top scores of predictions.
  - 2.4 Clustering the selected molescules with higher scores.
  - 2.5 Saving a molecule from each cluster. [best_cluster_represenatives.csv](https://github.com/dbetm/DeepLearningLifeSciences/files/7341695/best_cluster_represenatives.csv)
  - 2.6 Getting the final molecules from external sources.
  - 2.7 Testing in real world (biological assays, examples: inhibiting bacterial growth to preventing the proliferation of cancer cells).


Note: A drug discovery project is far away to finish of the end of this virtual screening exercise.




