# Page Classifier for Finding Printed Historical Tables in Digitized Library Collections

This repo contains the [training script](training_script.py) used to produce a simple ML-algorithm to find tables in large amounts of page-scans of free-of-copyright printed works from the eighteenth and nineteenth centuries. 

The training and classification model data are published on [Zenodo](https://doi.org/10.5281/zenodo.22857742). 

The training data consists of 1,384 page-scans belonging to 4 classes: `Title`, `Text`, `Table`, and `Text_and_table`. Page scans were collected from 18 sources. Bibliographic source references are given in the [sources file](SOURCES.md). 

Classification of the training data was done manually. 

1,108 files were used for training; 276 for validation during model training. 

The classification model has a preliminary character and serves as a pilot study for more comprehensive future work on an Optical Page Classifier.

The preliminary classification model documented here was used during the creation of the Bamberg 10k Printed Historical Tables Dataset, which is documented on [GitHub](https://github.com/dhofu/bamberg_10k_printed_historical_tables_dataset) and [Zenodo](https://doi.org/10.5281/zenodo.22251282).
