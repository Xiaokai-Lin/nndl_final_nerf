# Task3: NeRF 3D Reconstruction with custom dataset

## How to train?
1. **Set up environment**: Assuming Anaconda is installed, run commands in the file `environ_setup.sh` to create the virtual environment and install the required packages (always remember to activate the environment before running the following codes). 
2. Start training: Run commands in `train_eval_setup.sh` to create the dataset and train the model.

## How to evaluate?
After training session is done, run the following command to evaluate the model to get PSNR and other metrics:
```bash
ns-eval --load-config={PATH_TO_CONFIG} --output-path=output.json
```
where `{PATH_TO_CONFIG}` is the path to the config file used for training.
**To render a video**, you can create key frames in the Viewer and then find the command in the view then run it to create a video.

## How to download the dataset and the pretrained model?
The model is uploaded to the BaiduNetDisk.
