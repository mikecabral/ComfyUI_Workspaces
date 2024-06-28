#### Example of LoRA Training in ComfyUI

##### Experimental
![Workflow Example of Canny LoRA Control](https://github.com/readycade/ComfyUI/blob/master/workflows/LoRA%20Training/LoRA_Training.PNG)

### Notes:
https://github.com/LarryJane491/Lora-Training-in-Comfy

Follow the instructions but then use this to install the CORRECT pytorch

```
pip install torch==2.2.2+cu181 torchvision==0.17.2+cu121 torchaudio==2.2.2 -f https://download.pytorch.org/whl/cu121/torch_stable.html
```

#### WARNING: Use a separate ComfyUI installation, don't mess with your current one.

### Cuda Stuff
I'm still not sure which Cuda Toolkit + Cudnn flies work together for 3060TI with my current configuration.

Hopefully more information about this will be available soon.

Below are things I've been messing about with:

## Installing PyTorch for CUDA 11.8

We can now install PyTorch built for the specific CUDA version we need to support our ComfyUI requirements. Run the following commands in the same Powershell window/directory:

1. **Uninstall Current PyTorch Version**: (skip this if first time setting up virtual environment)
    
    ```
    pip uninstall torch torchvision torchaudio
    ```
    
2. **Install PyTorch for CUDA 11.8**:
    
    ```
    pip install torch==2.1.1+cu118 torchvision==0.16.1+cu118 torchaudio==2.1.1+cu118 -f https://download.pytorch.org/whl/torch_stable.html
    ```
    
3. **Verify PyTorch Installation**:
    
    ```
    python -c "import torch; print(torch.__version__); print(torch.version.cuda)"
    ```
    
    If everything worked correctly, you should see the following print in the terminal window:
    
    ```
    2.1.1+cu118
    11.8
    ```