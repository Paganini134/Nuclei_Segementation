# Nuclei Segmentation Using UNets

This repository contains an implementation of nuclei segmentation using UNet architectures. The code demonstrates how to preprocess microscopy images, train a UNet model, and perform segmentation on nuclei images. The project is implemented in a Jupyter Notebook to facilitate easy experimentation and visualization.

## Overview

Nuclei segmentation is a crucial step in various biomedical image analysis pipelines. This project leverages a UNet model to accurately segment nuclei from microscopy images. The UNet architecture, known for its encoder-decoder structure and skip connections, provides high-resolution segmentation maps while efficiently capturing spatial context.

## Features

- **Data Preprocessing:** Functions for loading and augmenting microscopy images.
- **UNet Model Implementation:** A full implementation of the UNet architecture tailored for segmentation tasks.
- **Training Pipeline:** End-to-end training loop including loss calculation, optimization, and evaluation.
- **Visualization:** Tools to visualize training progress and segmentation results.

## Requirements

Ensure you have the following dependencies installed:

```bash
pip install torch torchvision numpy matplotlib scikit-image tqdm
```

## Usage

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Paganini134/nuclei-unet-segmentation.git
   cd nuclei-unet-segmentation
   ```

2. **Launch Jupyter Notebook:**

   ```bash
   jupyter notebook Unet_Segmentation.ipynb
   ```

3. **Follow the notebook instructions:**

   The notebook is organized into several sections including data preprocessing, model definition, training, and evaluation. Execute each cell sequentially to run the complete segmentation pipeline.

## Results

The notebook includes example visualizations of the segmented nuclei overlaid on the original images. These results showcase the effectiveness of the UNet architecture in capturing the shape and boundaries of nuclei.

## Acknowledgments

This project is inspired by various works on biomedical image segmentation, including the original UNet paper by Ronneberger et al. (2015). Special thanks to the community for providing valuable datasets and open-source implementations.

## License

This project is open-source and available under the [MIT License](LICENSE).

