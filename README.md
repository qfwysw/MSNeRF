# Project README

## Environment Setup

Please follow these steps to set up the required environment:

1. **Install according to the Nerfstudio installation guide.**
   - Refer to the [Nerfstudio Installation Documentation] for detailed installation steps.

## Data Preparation

Our dataset is located at:

```
sparse_rice_single
```

Make sure this dataset is extracted and located in the correct directory.

## Model weight

```
https://drive.google.com/drive/folders/1baXTfo5wFH_QcUKcFx9UnOLTLutZ3u4u?usp=sharing
```

## Training Steps

To start training, execute the following script:

```bash
mytools/train_rice_single_sparse.sh
```

## Results Output

After training is complete, the results will be saved in the following path:

```
render_sparse_rice_single_womask_10
```

Please check this directory for the rendered results from the training.

## Notes

- Ensure all dependencies are correctly installed.
- If you encounter any issues during training, please check the log files for detailed information.
