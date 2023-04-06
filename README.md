# Project 2

We're Fine-tuning the Hugging Face Vision Transformer(ViT) with Pytorch for Vehicle Type Image Classification.

The notebook explaining our process is './main.ipynb', 

the github pages link is https://aman9801.github.io/vehicle-image-classification/

and the trained models are available at https://drive.google.com/drive/folders/1YgFnsp3T7jTuxzBLXdbJx1X8uHsHqxT_?usp=share_link

In order to use those models please download them into a folder "models":<br>
- head_trained (model fine-tuned from the pretrained model 'google/vit-base-patch16-224-in21k' by freezing all layers except the head)
- last_layers_trained (further training applied to the 'head_trained' model opening up few more layers)
- full_model_trained (starting model 'last_layers_trained', trained for 10 epochs with all layers open)
- all_layers_at_once_model (model trained starting from 'google/vit-base-patch16-224-in21k' with all layers open for training)
