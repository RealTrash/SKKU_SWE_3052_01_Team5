# SKKU_SWE_3052_01_Team5

## Code Categoty

### Baseline
- [Baseline]CAFE.ipynb  
- [Baseline]EAC.ipynb  
- [Baseline]MobileNet.ipynb  
- [Baseline, Ours]Latent-OFER.ipynb  
- [Baseline]KTN.ipynb  
- [Baseline]FERVT.ipynb  
- [Baseline]ViT.ipynb  

### Ours
- [Ours]Depth_CAFE.ipynb  
- [Ours]CLIP_FER.ipynb  
- [Baseline, Ours]Latent-OFER.ipynb  
- [Ours]FERVT-MS.ipynb  
- [Ours]DynamicEAC.ipynb  
- [Ours]AdaptiveFeatureFusion.ipynb  

## Model Performance Comparison

### Baseline

| Model           | Accuracy |
|-----------------|----------|
| Latent-OFER    | 0.8788   |
| CAFE           | 0.8757   |
| ViT-Base       | 0.8728   |
| MobileNetV2    | 0.8562   |
| EAC            | 0.8270   |
| KTN            | 0.8066   |
| FER-VT         | 0.8013   |

### Ours

| Model                   | Accuracy |
|-------------------------|----------|
| Self Attention CLIP     | 0.8906   |
| Depth CAFE              | 0.8900   |
| Dlib Latent-OFER        | 0.8807   |
| Dynamic EAC             | 0.8392   |
| Adaptive Feature Fusion | 0.8290   |
| FERVT-MS                | 0.8156   |

## Team Role

| 팀원     | 역할                                  |
|----------|---------------------------------------|
| 김도훈   | CAFE 구현, Depth Augmented CAFE 연구   |
| 김병혁   | FER-VT 구현, FERVT-MS (Multi-Scale) 연구 |
| 신준규   | KTN 구현, Adaptive Feature Fusion 연구 |
| 정연후   | EAC 구현, Dynamic EAC 연구             |
| 정윤호   | Latent-OFER, ViT-Base, MobileNet구현, Dlib Latent-OFER, Self-Attention CLIP 연구 |

## Reference
[1] Li, J., Nie, J., Guo, D., Hong, R., & Wang, M. (2024). Emotion separation and recognition from a facial expression by generating the poker face with vision transformers. IEEE Transactions on Computational Social Systems.  
[2] Zhang, Y., Wang, C., Ling, X., & Deng, W. (2022, October). Learn from all: Erasing attention consistency for noisy label facial expression recognition. In European Conference on Computer Vision (pp. 418-434). Cham: Springer Nature Switzerland.  
[3] Huang, Q., Huang, C., Wang, X., & Jiang, F. (2021). Facial expression recognition with grid-wise attention and visual transformer. Information Sciences, 580, 35-54.  
[4] Li, H., Wang, N., Ding, X., Yang, X., & Gao, X. (2021). Adaptively learning facial expression representation via cf labels and distillation. IEEE Transactions on Image Processing, 30, 2016-2028.  
[5] Le Ngwe, J., Lim, K. M., Lee, C. P., Ong, T. S., & Alqahtani, A. (2024). PAtt-Lite: lightweight patch and attention MobileNet for challenging facial expression recognition. IEEE Access.  
[6] Radford, A., Kim, J. W., Hallacy, C., Ramesh, A., Goh, G., Agarwal, S., ... & Sutskever, I. (2021, July). Learning transferable visual models from natural language supervision. In International conference on machine learning (pp. 8748-8763). PMLR.  
[7] Sandler, M., Howard, A., Zhu, M., Zhmoginov, A., & Chen, L. C. (2018). Mobilenetv2: Inverted residuals and linear bottlenecks. In Proceedings of the IEEE conference on computer vision and pattern recognition (pp. 4510-4520).  




