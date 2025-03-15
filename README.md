# GAN_LAB_3_DCGAN_065

## Dataset Preprocessing

1. Uses the **CELEBA** dataset (or another dataset if specified in the notebook).  
2. Applies the following transformations using `torchvision.transforms`:  
   - Resizing images.  
   - Normalizing pixel values.  
   - Converting images to tensors.  
3. Data is loaded using `torch.utils.data.DataLoader` for efficient batching.

## Expected Output

The model generates realistic images after several epochs of training.
Early training outputs may appear noisy, but they improve over time.
