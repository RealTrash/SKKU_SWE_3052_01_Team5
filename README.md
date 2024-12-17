# SKKU_SWE_3052_01_Team5

## 코드 분류

### Baseline
[Baseline]CAFE.ipynb
[Baseline]EAC.ipynb
[Baseline]MobileNet.ipynb
[Baseline, Ours]Latent-OFER.ipynb
[Baseline]KTN.ipynb
[Baseline]FERVT.ipynb
[Baseline]ViT.ipynb

### Ours
[Ours]Depth_CAFE.ipynb
[Ours]CLIP_FER.ipynb
[Baseline, Ours]Latent-OFER.ipynb
[Ours]FERVT-MS.ipynb
[Ours]DynamicEAC.ipynb
[Ours]AdaptiveFeatureFusion.ipynb

## 모델 성능 비교

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

## 팀원 역할 분담

| 팀원     | 역할                                  |
|----------|---------------------------------------|
| 김도훈   | CAFE 구현, Depth Augmented CAFE 연구   |
| 김병혁   | FER-VT 구현, FERVT-MS (Multi-Scale) 연구 |
| 신준규   | KTN 구현, Adaptive Feature Fusion 연구 |
| 정연후   | EAC 구현, Dynamic EAC 연구             |
| 정윤호   | Latent-OFER, ViT-Base, MobileNet구현, Dlib Latent-OFER, Self-Attention CLIP 연구 |




