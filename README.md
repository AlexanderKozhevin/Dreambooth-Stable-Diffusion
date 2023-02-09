#!rm /content/Dreambooth-Stable-Diffusion/outputs/txt2img-samples/*
!python worker8.py \
 --ddim_eta 0.0 \
 --n_samples 1 \
 --email "ealhdo@gmail.com" \
 --gender "man" \
 --hash "dc9678a273b8645448bb0d2230ad35a6" \
 --outdir "/workspace/Dreambooth-Stable-Diffusion/output" \
 --n_iter 4 \
 --skip_grid \
 --scale 7.0 \
 --ddim_steps 50 \
 --ckpt "/workspace/dc9678a273b8645448bb0d2230ad35a6.ckpt" \
 





!pip install google-cloud-storage
!pip install protobuf==3.20.*


!pip install torch==1.12.1+cu113 torchvision==0.13.1+cu113 torchaudio==0.12.1 --extra-index-url https://download.pytorch.org/whl/cu113
