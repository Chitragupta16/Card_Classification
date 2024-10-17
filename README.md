# Card_Classification

## My First PyTorch Model

This repository contains my first **PyTorch** model, which is a card classification model that recognizes and classifies playing cards based on the image provided. The model is designed to identify any card from a given image using deep learning techniques. This project was inspired in entirety by [Rob Mulla](https://youtube.com/@robmulla?sub_confirmation=1) and his Youtube tutorials

## Features

- **Framework**: PyTorch
- **Image Classification**: Classifies playing cards into their respective categories
- **Pretrained Models**: Utilizes models from `timm` for transfer learning
- **Custom Dataset Handling**: Loads and preprocesses images using `ImageFolder` and custom `Dataset` objects

## Libraries Used

The following libraries were used to develop and train the model:

- **PyTorch**: Core framework for building and training the model
  - `torch`
  - `torch.nn`
  - `torch.optim`
- **Torch Utilities**:
  - `torch.utils.data.Dataset`
  - `torch.utils.data.DataLoader`
- **Torchvision**:
  - `torchvision.transforms` for image preprocessing
  - `torchvision.datasets.ImageFolder` for handling the dataset structure
- **Timm**: Pretrained models for transfer learning
- **Matplotlib**: For plotting and visualization of data
- **Pandas**: For data manipulation and handling
- **Numpy**: For numerical operations and array manipulation
- **Glob**: For retrieving files from directories
- **Tqdm**: For progress bars during data loading and training

