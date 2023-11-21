# MOTION LATENT DIFFUSION FOR STOCHASTIC TRAJECTORY PREDICTION

The official repository of the paper:

MOTION LATENT DIFFUSION FOR STOCHASTIC TRAJECTORY PREDICTION

Weishang Wu, Xiaoheng Deng*

![image](https://github.com/SyKszzzzz/MLD/assets/48318221/2f85ef4b-402c-468e-ac48-1c1d850b8d0b)

Please be patient 😁, further clarification and implementation will be released soon 🥰.

# Abstract
The indeterminacy of human motion poses challenges for pedestrian trajectory prediction. Consequently, existing methods adopt multimodal strategy to model pedestrians future trajectories. A significant advancement in this regard is the growing prominence of the diffusion model. However, the two-dimensional inputs for trajectory prediction not provide sufficient contextual information for the diffusion model. Furthermore, the diffusion model suffers from substantial inference time. To address these conundrums, we propose a trajectory prediction method based on the diffusion model, named as Motion Latent Diffusion (MLD). The core of MLD is the Conditional Variational Autoencoder (CVAE) to transform the original low-dimensional inputs into a higher-dimensional latent space, expanding the receptive field to yield more comprehensive and intricate representations. Simultaneously, during the inferential stage of the diffusion model, we adopt a leapfrogging inference strategy, which facilitates a faster sampling process. Experiments conducted on the ETH/UCY and Stanford Drone datasets (SDD) corroborate the superiority of our method.
