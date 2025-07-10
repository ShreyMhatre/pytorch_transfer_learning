# PyTorch Transfer Learning

This repository contains my implementation and experiments with **transfer learning** using PyTorch. Transfer learning leverages pretrained models to solve new tasks with fewer data and resources, making it an efficient and powerful approach in deep learning workflows.

The notebook demonstrates how to load a pretrained model from `torchvision.models`, modify the classifier head, and fine-tune it for a new classification task.

##  Contents

- `PyTorch_Transfer_Learning.ipynb`: Main Jupyter notebook showcasing the transfer learning pipeline.
- Trained model loading and evaluation examples.
- Code examples for:
  - Freezing and unfreezing model layers.
  - Using different pretrained architectures.
  - Training on a custom dataset with `ImageFolder`.
  - Tracking performance using `matplotlib` and manual accuracy/loss plots.

##  Techniques Used

- **Transfer Learning** using `torchvision.models` (e.g., ResNet).
- **Feature Extraction vs Fine-Tuning** approaches.
- **Data Preparation** using `torchvision.datasets.ImageFolder` and `torch.utils.data.DataLoader`.
- **Model Training and Evaluation** with customized classifier heads.
- **Visualization** of training and testing metrics.

##  Learnings

Through this notebook, I learned:

- How pretrained networks like ResNet can be adapted to new datasets.
- The importance of freezing vs unfreezing layers.
- Handling custom datasets and training loops manually in PyTorch.
- Visualizing performance and diagnosing underfitting/overfitting.

##  Reference

This project is heavily inspired by the **PyTorch Deep Learning series** by [Daniel Bourke](https://github.com/mrdbourke), especially the notebook:

[06_pytorch_transfer_learning.ipynb](https://github.com/mrdbourke/pytorch-deep-learning/blob/main/06_pytorch_transfer_learning.ipynb)

His tutorials provide a solid foundation and are highly recommended for beginners and intermediate learners.

##  License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
