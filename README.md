# CT5129- Artificial Intelligence Project 
## Topic: ClearFlow: An Enhanced Image Dehazing Workflow Using Model Ensembling and CNN Postprocessing 📸 🌫
### Name: Hemanth Harikrishnan
### ID: 23105030

The method uses deep convolutional networks with Channel and Pixel Attention to perform dehazing process. The tracking of the model was done on Weights and biases and the logging can be found here: 
<br><br>
[<img src="https://raw.githubusercontent.com/wandb/assets/main/wandb-github-badge-28.svg" alt="Weights & Biases" width="150"/>](https://wandb.ai/hemanthh17/CT5129-Image%20Dehazing?nw=nwuserhemanthh17)
      
#### Dataset 🖥
The datasets used are: 
- RESIDE (ITS and SOTS)
- I-Haze (NTIRE-2018)
- O-Haze (NTIRE-2018)
- Dense-Haze (NTIRE-2019)
- NH-Haze (NTIRE-2020)

The datasets can be found on Kaggle:
<br><br>
[![Kaggle](https://img.shields.io/badge/Kaggle-blue)](https://www.kaggle.com/datasets/hemanthhari/dehazing-dataset-thesis)

#### Training the model 
The following steps needs to be done to train the model.
- Make sure the requirements are satisfied. <br>
  ```sh
  pip install -r requirements.txt
  ```
- Download the Dataset from the URL mentioned.
- Check for presence of GPU  <br>
  ```sh
   nvidia-smi
  ```
- Train the model using the DWT+DehazerNet-MSE-Perceptual Training Script.ipynb and DWT+DehazerNet-MSE-Perceptual Training Script.ipynb notebooks
- Save the model
#### Testing the model
The model can be tested using the inference-script.ipynb. The results will be saved in a separate folder. The process can be easily run on a CPU.

#### Note 📝
<b>The paths are supposed to be changed according to where your corresponding dataset is present. The paths in the code are according to the Kaggle dataset strucutre.</b>
