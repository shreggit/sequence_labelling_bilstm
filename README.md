# sequence_labelling_bilstm
Performs Sequence Labelling using a BILSTM-CRF architecture.    

This repo contains a notebook (obligations_bilstm.ipynb) which contains the code to process a given annotated text dataset into a X and Y.

X - contains all the word in the given context, Y - consists of the B-I-O tags for each word. 

We use this information to build a BILSTM-CRF model.

The 8 python scripts are derived from the anago repository, and are used for model building. 

This repo also contains a notebook to augment text using back translation. (augmentation_backtrans.ipynb)

