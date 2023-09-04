# Kaggle-RSNA-ATD-Competition

This is a repo containing my work for the [2023 RSNA-ATD kaggle competition](https://www.kaggle.com/competitions/rsna-2023-abdominal-trauma-detection/overview), where the task is to detect abdominal trauma in CT scans. 

Here are some features of my notebook:
- Custom Data class that reads data
- Dataloader functionality that incorporates data augmentation techniques
- Custom function to perform stratified k fold validation
- Configurations to organize notebook
- Weights & Biases integration for experiment tracking
- Abstract MultiHeadedModel class that subclasses from pl.LightningModule (i.e. PyTorch Lightning)
- 3 example models: CNN (implemented by scratch), ResNet (pretrained), EfficientNet (pretrained)
