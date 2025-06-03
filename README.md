# Segment-Anyword: Mask Prompt Inversion for Open-Set Grounded Segmentation

This is the official implementation for our paper [Segment-Anyword: Mask Prompt Inversion for Open-Set Grounded Segmentation](https://arxiv.org/abs/2505.17994), which was accepted by ICML 2025.

## TL;DR: 

We leverage cross-attention maps from a diffusion inversion process to guide open-set grounded segmentation. This inversion helps mitigate the sensitivity to ambiguous text prompts. The resulting cross-attention based visual point prompts are further regularized using linguistic syntax and dependency information.

## Note:

Following the approach of legned textual inversion, we only update the test-time textual embeddings of the associated images. As a result, we do not have any network checkpoints. The updated textual embeddings may be released in the future, depending on usage requests.
