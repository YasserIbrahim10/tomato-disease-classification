## Tomato Disease Classification Dataset

### Dataset Sources

- [PlantVillage Dataset](https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset)
- [Tomato Leaves Dataset](https://www.kaggle.com/datasets/ashishmotwani/tomato)

### Data Preparation

- Selected tomato leaf images from both sources.
- Checked image readability and removed exact duplicate images using SHA-256 hashes.
- Excluded three image hashes associated with conflicting labels.
- Created stratified train, validation, and test splits.

### Dataset Split

| Split | Images |
|---|---:|
| Train | 24,049 |
| Validation | 5,153 |
| Test | 5,154 |
| **Total** | **34,356** |

### Split Manifest

The file `tomato_dataset_split.csv` contains image paths, source information, class labels, split assignments, and SHA-256 hashes.

**Important:** The CSV is a manifest, not the image files themselves. The original datasets must be obtained from their respective sources, and their licensing terms must be followed before images are redistributed or shared.

The dataset was prepared for a tomato disease classification graduation project.
