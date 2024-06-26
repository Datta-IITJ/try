# MIDL CODE

## Anomaly-focused Single Image Super-resolution with Artifact Removal for Chest X-rays using Distribution-aware Diffusion Model

### Abstract

Single image super-resolution (SISR) is a crucial task in the field of medical imaging. It transforms low-resolution images into high-resolution counterparts, enhancing image quality and aiding better diagnosis, particularly in chest X-ray images. However, these images often contain artifacts that can obscure important information. In this work, we propose an anomaly-guided SISR process that utilizes the denoising mechanism of the diffusion model to iteratively remove noise and restore the original image. By training the model to learn the data distribution, we enable it to effectively eliminate artifacts within the images. Additionally, we prioritize the reconstruction of disease regions to ensure their accurate representation. Our experiments over publicly available datasets reveal that existing SISR methods struggle to learn and remove artificially added artifacts. In contrast, our proposed model not only prioritizes superior image reconstruction but also effectively removes artifacts, outperforming existing methods.

### Contributions

In this work, our major contributions are:

- We introduce a SISR method for chest x-rays using a diffusion probabilistic model that can remove artifacts during super-resolution.
- The proposed model utilizes information about abnormalities that may be present in the chest x-rays. The resultant SR image is likely to contain richer information about the abnormalities.
- Our model captures the distribution of data using a variational autoencoding mechanism to facilitate super-resolution.
- Experiments on publicly available datasets show the potential of generalizability of the proposed method.

