# System requirement
Tensorflow 2.12.0 and Keras 2.12.0 packages with python 3.10.12 are used on google colab platform to consruct the CNN model.

# Installation guide
The above mention packages can be installed in a windows 10 operating system computer following standard installation procedure. The installations will take about few minutes.

# Demo
The final CNN model along with the model architecture code is given in the ERE_Code.zip file. The required input files mentioned in the final version of the codes is made available in the "Testing_dataset" folder of the ERE_CODE.zip file itself. The expected output of the code is the forecast of normalized extrme rainfall events (ERE) frequency or extreme rainfall activity (ERA) anomaly between 1992 to 2022 at 1-month lead time. The forecast between 1992 and 2022 is generated using D20 anomaly ORAS5 dataset. The expected run time of the CNN model in both google colab and windows 10 desktop is around few minutes.

# Instruction for use
Stepwise instruction at appropriate locations are given in the model's scipts. The datasets and codes are arranged in a systematic order inside the ERE_CODE.zip file for user convenience.

To run the codes, all the required input files (input and output dataset), weight parameters (ERE_freq_Model_*.hdf5 or ERA_Model_*.hdf5), and model script should be placed in the same folder.

# Note
The ERE_CODE.zip file can be downloaded by clicking on "View raw".
