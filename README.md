# ML_skipception  
Experimenting with convolutional neural networks, constructing skip connections and inception layers, to classify 64x64 images across 30 and 200 classes.  
  
## datasets  
The datasets directory stores two custom ImageNet datasets used in the included notebooks.  
  
## saved_models  
The saved_models directory contains files that store model_state_dict, optimizer_state_dict, and loss history at specified epochs.  
  
## Notebooks  
This repository includes three notebooks:  
  
**CNN_building.ipynb** touches upon "single-batch training" architecture design and provides an overview on building a simple convolutional neural network.  
  
**skipception-30.ipynb** presents a model that uses a combination of skip connections and inception modules to classify images across 30 labels.  
  
**skipception-200.ipynb** is the same skipception model as in skipception-30.ipynb, but trained on a larger dataset to classify images across 200 labels.
