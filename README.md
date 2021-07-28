# Deep Learning for the Life Sciences
## Applying Deep Learning to Genomics, Microscopy, Drug Discovery & More.

Using DeepChem with TensorFlow 2.x + Keras or PyTorch 🔥, projects and exercises adapted to run on Google Colab.

[Repository of the book](https://github.com/deepchem/DeepLearningLifeSciences)

**Projects and exercises**

|       Chapter        |           Name                  |  TensorFlow | PyTorch |
|        :---:         |            :---:                |     :---:   |   :---: |
| 3 - ML with DeepChem | [Predict toxicity of molecules](03_MLDeepChem/Predict_Toxicity_of_Molecules.ipynb)   |       ✔️     |    ✖️    |
| 3 - ML with DeepChem | [Digit Recognition (MNIST)](03_MLDeepChem/MNIST_with_TensorGraph_from_DeepChem.ipynb)         |       ✔️     |    ✖️    |
| 4 - Molecules        | [Predict solubility of molecules](04_Molecules/Predict_solubility_using_GraphConvModel.ipynb)              |       ✔️     |    ✖️    |
| 4 - Molecules        | [SMARTS Strings](04_Molecules/SMARTS_Strings.ipynb)                  |       ✔️     |    ✖️    |
| 5 - Biophysics     | [Predict affinity of protein-ligands](05_Biophysics/Binding_free_energy_prediction_using_PDBBind_dataset.ipynb) |   ✔️     |    ✖️    |
| 6 - Genomics         | [Predict TF binding (JUND)](06_Genomics/Predicting_transcription_factor_binding.ipynb)       |       ✔️     |    ✖️    |
| 6 - Genomics         | [Predict TF binding with chromatin accessibility](06_Genomics/Predicting_TF_binding_chromatin_accessibility.ipynb)  |       ✔️     |    ✖️    |
| 6 - Genomics         | [Predict RNA Interference](06_Genomics/RNA_Interference.ipynb)        |       ✔️     |    ✖️    |
| 7 - Microscopy       | [Cell counting](07_Microscopy/Cell_Counting.ipynb)                   |       ✔️     |    ✖️    |
| 7 - Microscopy       | [Cell segmentation](07_Microscopy/Cell_segmentation.ipynb)             |       ✔️     |    ✖️    |
| 8 - Medicine         | [Predict diabetic retinopathy progression](08_Medicine/Diagnose_Diabetic_Retinopathy_Progression.ipynb)  |   ✔️    |    ✖️    |
| 9 - Generative models| [Generate molecules using MUV dataset](09_GenerativeModels/Generating_molecules_with_VAE.ipynb) |   ✔️    |    ✖️    |
| 10 - Interpretation|  |   -    |    -    |
| 11 - Virtual Screening|  |   -    |    -    |

**Notes**: 
1. On the Jupyter Notebooks the models don't save after/during the training.
You must set `model_dir` and call `model.restore()` for use trained models, you
can read more [here](https://deepchem.readthedocs.io/en/latest/api_reference/models.html#keras-models).
2. If you wish to run the models to train, please enable GPU on Colab (Runtime > Change runtime type > Hardware accelerator -> GPU).
3. The projects are demonstrative, you shouldn't use them in a real life application, but you can have like reference to create robust models to research, exploration and more.
