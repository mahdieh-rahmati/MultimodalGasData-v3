# MultimodalGasData-v3

This repository hosts version 3 of the "MultimodalGasData: Multimodal Dataset for Gas Detection and Classification" dataset. This version includes enhancements such as deduplication of images and an improved organizational structure for better usability.

## Description

**MultimodalGasDataset-v3** is an updated and enhanced version of the original dataset described in the [MultimodalGasData: Multimodal Dataset for Gas Detection and Classification](https://www.mdpi.com/2306-5729/7/8/112) article. The original dataset is available [here](https://data.mendeley.com/datasets/zkwgkjkjn9/2).

### Key Updates in Version 3:

- **Deduplication**: Duplicate images within and across different classes have been removed.
- **Structured Organization**: Images are organized into `train`, `validation`, and `test` sets with a 70-10-20 split, ensuring uniform class distribution.
- **Updated CSV Files**: The corresponding CSV files for sensor measurements have been updated to match the deduplicated and split data.

### Folder Structure:


MultimodalGasDataset/
│
├── Gas_Sensors_Measurements/
│ ├── Gas_Sensors_Measurements_train.csv
│ ├── Gas_Sensors_Measurements_validation.csv
│ └── Gas_Sensors_Measurements_test.csv
│
└── Thermal_Camera_Images/
├── train/
│ ├── Mixture/
│ ├── NoGas/
│ ├── Perfume/
│ └── Smoke/
│
├── validation/
│ ├── Mixture/
│ ├── NoGas/
│ ├── Perfume/
│ └── Smoke/
│
└── test/
├── Mixture/
├── NoGas/
├── Perfume/
└── Smoke/


### About the Dataset

This dataset is designed for research in gas detection and classification using multimodal data, combining thermal images and gas sensor measurements. It provides a comprehensive resource for developing and testing machine learning models in this domain.

### Usage

Refer to the CSV files in the `Gas_Sensors_Measurements` directory for sensor data corresponding to the images in the `Thermal_Camera_Images` directory.

### Attribution

If you use the version 3 dataset, you must refer to this version in your work. Proper citation helps to acknowledge the effort put into the creation and maintenance of this dataset and aids in maintaining the integrity of scientific research.

## License

This dataset is licensed under the [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. This means you are free to:

- **Share**: Copy and redistribute the material in any medium or format.
- **Adapt**: Remix, transform, and build upon the material for any purpose, even commercially.

Under the following terms:

- **Attribution**: You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

## References

If you use this dataset, please cite the original article and the dataset:

1. Original Article: [MultimodalGasData: Multimodal Dataset for Gas Detection and Classification](https://www.mdpi.com/2306-5729/7/8/112)
2. Original Dataset: [Mendeley Dataset](https://data.mendeley.com/datasets/zkwgkjkjn9/2)

