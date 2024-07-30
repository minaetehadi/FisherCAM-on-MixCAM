# Effective Adversarial Attacks on Images by Class Activation Mapping
Adversarial Attack using FisherCAM Heatmap



# Requirements
- Python >= 3.x
- Tensorflow => 1.12.0 
- Numpy >= 1.15.4
- Opencv >= 3.4.2
- Scipy > 1.1.0
- pandas >= 1.0.1
- imageio >= 2.6.1
- Pandas 
- Imageio
- PyTorch
- Pillow
- NumPy
- Matplotlib


  ## Fisher-CAM Heatmap generation

 Clone the repository:
   ```bash
   git clone https://github.com/minaetehadi/Adversarial-Attacks-by-Class-Activation-Mapping.git
   cd FisherCAMHeatmap
```

```bash
    python FisherCAMHeatmap.py
```

   ## Adversarial example generation

 Add your image sampe: 
```
image_path = "/content/dog1.jpg"
```
   ```bash
    python Adversarial-Example-Sample.py
```

  ## Runing adversarial attck on ILSVRC 2012 dataset 
1. [Validation data](https://github.com/minaetehadi/Adversarial-Attacks-by-Class-Activation-Mapping/blob/main/validation.csv)
2. [Pre-trained models](https://github.com/minaetehadi/Adversarial-Attacks-by-Class-Activation-Mapping/tree/main/DNNModels)
3. Clone the repository:
   ```bash
   git clone https://github.com/minaetehadi/Adversarial-Attacks-by-Class-Activation-Mapping.git
   cd Our-Attack-by-FisherCAM

   
# Acknowledge
Code refers to 
- [MixCam](https://github.com/LongTerm417/MixCam)

- [AdMix](https://github.com/JHL-HUST/Admix)

# Contact 
If you have any questions or need further assistance, please feel free to reach out to me at  (minaetehadi@eng.ui.ac.ir)


