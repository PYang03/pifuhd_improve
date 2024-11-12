## Environment
- Python 3.7.6
- CUDA 11.6
- Win 11
- ffmpeg 7.1

```
winget install ffmpeg
```
```
conda create -n "pifuhd_37" python=3.7.6
```

## Package
- pytorch 1.12.1
```
pip install torch==1.12.1+cu116 torchvision==0.13.1+cu116 torchaudio==0.12.1 --extra-index-url https://download.pytorch.org/whl/cu116
```
- Pillow
- scikit-image
- tqdm
- opencv-python
- trimesh
- PyOpenGL
```
pip install -r requirements.txt 
```

## Pre-trained model
```
sh ./scripts/download_trained_model.sh
```