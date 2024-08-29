### dldajlsdl;akjdl
on the first try I used lightning AI, then moved to colab. The access the colab from ![here](https://colab.research.google.com/drive/1L0DMB9CTxzYv4OeLLo5oL2w_JWOudNkT#scrollTo=0i_lAzieoj24).
### Current Status:
  Ive implemented a VAE model for image upscaling. However not trained yet. The main reason is to understand how VAE works in general.
  Oh and btw, pytorch_lightning is used for training. if you don't want this overhead you can create yours 😂

#### Current Issues:
  - Vanishing and exploding gradients. [checkout this](./vae-testing).  The gradient distribution across activations are insane. Perhaps, next time I will try SwiGLU and see how it does. 
  - As I said yesterday, After training, it resulted in a lot of deed neuron outputs
    ![download (1)](https://github.com/user-attachments/assets/76141c38-d495-486b-8aca-bf899d43ffa5)
    ![download](https://github.com/user-attachments/assets/f44a68e8-4536-4a8f-b09d-128626cfd0e4)

---

In conclusion, this model is wack! but can be used as a reference to understand how VAE works. Perhaps, by tuning the parameters or change the reparameterization to a more better one that suits your purpose! 
