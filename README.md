# Master-thesis-AI4forensics
Repository with all Jupyter notebooks for the Master thesis: AI 4 Forensics: Evaluating the performance of open-source state-of-the-art speaker comparison systems.
The following datasets are required to run all code:
- UCLA variability
- Commonvoice Dutch corpus version
- FRIDA telephone
- Wyred
All datasets should be extracted in the same folder as the notebooks. 

The notebooks and their functions:
- Exploratory data analysis: code and comments generating the tables and visualizations for the EDA.
- Pairing files: Generating the speaker utterance pairs according to the pairing algorithm. Saves the pairs as csv files.
- ECAPA-TDNN: Runs the evaluation experiments on utterance pairs for the ECAPA-TDNN and ResNet models.
- wavLM: Runs the experiments on utterance pairs for the wavLM model.
- Fine-tuning resnet: Fine-tune the ResNet model on the UCLA dataset and performs Deep weight space ensemble. Then runs evaluation experiments.
