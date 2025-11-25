# DM-VSR: Depth-Aware Diffusion Models with Adaptive Modulation for Video Super-Resolution

## Updates
- **2025.06.17**: Repo is created.
## 👀 TODO
- [x] Dependencies and installation.
- [ ] Release inference code.
- [ ] Release training code.
## 🔧 Dependencies and Installation

1. Clone repo
    ```bash
    git clone https://github.com/aigcvsr/DM-VSR.git
    cd DM-VSR
    ```

2. Install dependent packages
    ```bash
    conda create -n dmvsr python=3.8.17 -y
    conda activate dmvsr
    pip install -r requirements.txt
    ```
### Acknowledgement
This implementation largely depends on [DepthAnything](https://github.com/DepthAnything/Depth-Anything-V2), [TASR](https://github.com/SleepyLin/TASR), [ControlNetPlus](https://github.com/xinsir6/ControlNetPlus), [StableSR](https://github.com/IceClear/StableSR), and [StableVSR](https://github.com/claudiom4sir/StableVSR). The quality assessment work runs on [IQA-PyTorch](https://github.com/chaofengc/IQA-PyTorch). We thank the authors for the contribution.
