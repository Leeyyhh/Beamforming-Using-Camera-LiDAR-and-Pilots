# Multimodal-Learning-for-Beamforming-Using-Camera-LiDAR-and-RF-Pilots
Code and Dataset for our paper: Multimodal Learning for Beamforming Using Camera, LiDAR, and RF Pilots

## Dataset

We provide the simulation dataset used in this project through Zenodo:

[Dataset on Zenodo](https://zenodo.org/records/20147422)

The shared dataset includes the following components:

- Raw camera images
- Sampled LiDAR points
- Wireless communication channel data
- Image detection results
- 3D bounding box information

The dataset is generated in a virtual simulation environment and does not contain real-world personal data.

### Raw LiDAR Point Generation

Due to the large file size, we do not directly include the full raw LiDAR point clouds in the Zenodo dataset. Instead, we provide the files and scripts needed to generate the raw LiDAR data in this GitHub repository.

The LiDAR data generation files are located in the following directory:

```text
LiDAR_generate/

We also provide the train, validation, and test dataset lists in the `code_for_beamforming` directory to ensure reproducibility. These lists contain the fixed sample indices used in our experiments. When running the code, users only need to modify the dataset directory path according to their local file location. Users can also generate their own train/validation/test splits if needed, but the results reported in the paper are based on the provided fixed data split. We have also rerun the experiments with several versions to verify the consistency of the results.
