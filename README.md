# DDPM Implementation

Denoising diffusion models work by gradually removing noise from a noisy image to produce a clean image.

1. Training: Train a neural network to on 3 targets: a clean image,  a version of the clean image with noise added to it, and the noise level. We want the neural network to be able to determine which part of the noisy image is noise.
2. Inference: Starting from pure noise, use the trained neural network to predict the noise and remove the noise. Repeat this process many times and we will eventually generate an image.

Starting Image:

![image](https://github.com/user-attachments/assets/9382e699-1281-4a4a-a25a-066965ca2b46)


Intermediate Image:

![image](https://github.com/user-attachments/assets/428243db-4771-47e1-a176-f3815854f454)

Final Image:

![image](https://github.com/user-attachments/assets/580fc75c-bd19-4841-8c4f-a6a0a7ee2b1c)
