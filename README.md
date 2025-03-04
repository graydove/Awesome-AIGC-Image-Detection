# Awesome AIGC Image Detection
This benchmark provides a comprehensive evaluation of AIGC image detection methods across six datasets. All reported results are based on official implementations with reproducible code, environment configurations, and result logs (to be released soon). If you find this resource helpful for your research, please consider giving it a ⭐!

For [SAFE](https://arxiv.org/abs/2408.06741) replication, refer to [SAFE-self](https://github.com/graydove/SAFE). We welcome community verification of our implementation.

&nbsp;

## Contents
- [Datasets](#datasets)
- [Papers](#papers)
- [Accuracy](#accuracy)

&nbsp;

## Datasets

| Dataset | Paper | Download |
|---------|-------|----------|
| [AIGCDetectBenchmark](https://github.com/Ekko-zn/AIGCDetectBenchmark) | [PatchCraft](https://arxiv.org/abs/2311.12397) | [Google Drive](https://drive.google.com/drive/folders/1p4ewuAo7d5LbNJ4cKyh10Xl9Fg2yoFOw) |
| [ForenSynths](https://github.com/peterwang512/CNNDetection) | [CNNDetection (CVPR 2020)](https://arxiv.org/abs/1912.11035) | [Hugging Face](https://huggingface.co/datasets/sywang/CNNDetection/resolve/main/CNN_synth_testset.zip) |
| [Self-Synthesis (GAN Based)](https://github.com/chuangchuangtan/FreqNet-DeepfakeDetection) | [FreqNet (AAAI 2024)](https://arxiv.org/abs/2403.07240) | [Google Drive](https://drive.google.com/drive/folders/11E0Knf9J1qlv2UuTnJSOFUjIIi90czSj?usp=sharing) |
| [UniversalFakeDetect (DM Based)](https://github.com/Yuheng-Li/UniversalFakeDetect) | [UnivFD (CVPR 2023)](https://arxiv.org/abs/2302.10174) | [Google Drive](https://drive.google.com/drive/folders/1nkCXClC7kFM01_fqmLrVNtnOYEFPtWO-?usp=sharing) |
| [GenImage](https://github.com/GenImage-Dataset/GenImage) | [GenImage (NeurIPS 2023)](https://arxiv.org/abs/2306.08571) | [Google Drive](https://drive.google.com/drive/folders/1jGt10bwTbhEZuGXLyvrCuxOI0cBqQ1FS) |
| [DRCT-2M](https://github.com/beibuwandeluori/DRCT) | [DRCT-2M (ICML 2024)](https://icml.cc/virtual/2024/poster/33086) | [ModelScope](https://modelscope.cn/datasets/BokingChen/DRCT-2M/files) |

&nbsp;

## Papers
* **CNNSpot**  
  CNN-generated images are surprisingly easy to spot... for now  *CVPR 2020*  
  [Paper](https://arxiv.org/abs/1912.11035) | [Code](https://github.com/peterwang512/CNNDetection)
  
* **FreDetect**  
  Leveraging Frequency Analysis for Deep Fake Image Recognition  *ICML 2020*  
  [Paper](https://arxiv.org/abs/2003.08685) | [Code](https://github.com/Ekko-zn/AIGCDetectBenchmark)
  
* **UnivFD**  
  Towards Universal Fake Image Detectors that Generalize Across Generative Models  *CVPR 2023*  
  [Paper](https://arxiv.org/abs/2302.10174) | [Code](https://github.com/WisconsinAIVision/UniversalFakeDetect)
  
* **LGrad**  
  Learning on Gradients: Generalized Artifacts Representation for GAN-Generated Images Detection  *CVPR 2023*  
  [Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Tan_Learning_on_Gradients_Generalized_Artifacts_Representation_for_GAN-Generated_Images_Detection_CVPR_2023_paper.pdf) | [Code](https://github.com/chuangchuangtan/LGrad)
  
* **NPR**  
  Rethinking the Up-Sampling Operations in CNN-based Generative Network for Generalizable Deepfake Detection  *CVPR 2024*  
  [Paper](https://arxiv.org/abs/2312.10461) | [Code](https://github.com/chuangchuangtan/NPR-DeepfakeDetection)
  
* **FreqNet**  
  Frequency-Aware Deepfake Detection: Improving Generalizability through Frequency Space Learning  *AAAI 2024*  
  [Paper](https://arxiv.org/abs/2403.07240) | [Code](https://github.com/chuangchuangtan/FreqNet-DeepfakeDetection)
  
* **FatFormer**  
  Forgery-aware Adaptive Transformer for Generalizable Synthetic Image Detection  *CVPR 2024*  
  [Paper](https://arxiv.org/abs/2312.16649) | [Code](https://github.com/Michel-liu/FatFormer)
  
* **SSP**  
  A Single Simple Patch is All You Need for AI-generated Image Detection  *arXiv 2024*  
  [Paper](https://arxiv.org/abs/2402.01123) | [Code](https://github.com/bcmi/SSP-AI-Generated-Image-Detection)
  
* **DRCT**  
  DRCT: Diffusion Reconstruction Contrastive Training towards Universe Detection of Diffusion Generated Images  *ICML 2024*  
  [Paper](https://raw.githubusercontent.com/mlresearch/v235/main/assets/chen24ay/chen24ay.pdf) | [Code](https://github.com/beibuwandeluori/DRCT)
  
* **C2P-CLIP**  
  C2P-CLIP: Injecting Category Common Prompt in CLIP to Enhance Generalization in Deepfake Detection *AAAI 2025*  
  [Paper](https://arxiv.org/abs/2408.09647) | [Code](https://github.com/chuangchuangtan/C2P-CLIP-DeepfakeDetection)
  
* **SAFE**  
  SAFE: Simple Preserved and Augmented FEatures  *KDD 2025*  
  [Paper](https://arxiv.org/abs/2408.06741) | [Code](https://github.com/Ouxiang-Li/SAFE)
  
* **AIDE**  
  A Sanity Check for AI-generated Image Detection  *ICLR 2025*  
  [Paper](https://arxiv.org/abs/2406.19435) | [Code](https://github.com/shilinyan99/AIDE)

&nbsp;

## Accuracy
### AIGCDetectBenchmark
|           |   Time    |  ProGAN   | StyleGAN  |  BigGAN   | CycleGAN  |  StarGAN  |  GauGAN   | StyleGAN2 |   WFIR    |    ADM    |   Glide   | Midjourney |  SD v1.4  |  SD v1.5  |   VQDM    |  Wukong   |  DALLE2   |   Mean    |
| :-------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: | :--------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: |
|   CNNSpot   | CVPR2020  | **100** |   90.17   |   71.17   |   87.59   |   94.60   |   81.44   |   86.91   | **95.10** |   60.38   |   58.03   |   51.40    |   50.58   |   50.52   |   56.45   |   51.03   |   51.25   |   71.04   |
|  FreDetect  | ICML2020  |  99.36  |   78.02   |   81.97   |   78.77   |   94.62   |   80.57   |   66.17   |   46.45   |   64.67   |   55.43   |   46.89    |   40.02   |   40.39   |   78.95   |   41.54   |   34.65   |   64.28   |
|   UnivFD    | CVPR2023  |  99.81  |   84.93   |   95.08   |   98.33   |   95.75   | **99.47** |   74.96   |   87.20   |   66.94   |   62.53   |   56.24    |   63.75   |   63.57   |   85.42   |   71.06   |   50.75   |   78.49   |
|    LGrad    | CVPR2023  |  99.86  |   89.72   |   84.58   |   87.81   |   99.30   |   82.26   |   85.30   |   52.95   |   64.12   |   70.30   |   67.09    |   63.78   |   65.08   |   72.62   |   60.14   |   68.55   |   75.84   |
|     NPR     | CVPR2024  |  99.79  |   97.71   |   84.35   |   96.10   |   99.35   |   82.50   |   98.39   |   65.75   |   69.72   |   78.35   |   77.83    |   78.62   |   78.88   |   78.13   |   76.10   |   64.90   |   82.90   |
|   FreqNet   | AAAI2024  |  99.58  |   90.24   |   90.45   |   95.84   |   85.69   |   93.41   |   87.95   |   49.20   |   83.27   |   81.66   |   69.83    |   64.22   |   64.91   |   81.65   |   57.72   |   55.30   |   78.18   |
|  FatFormer  | CVPR2024  |  99.89  |   97.13   | **99.50** | **99.36** |   99.75   |   99.43   | **98.80** |   88.16   |   78.44   |   88.03   |   56.08    |   67.83   |   68.06   |   86.87   |   73.06   |   69.67   |   85.63   |
|     SSP     | arXiv2024 |  84.01  |   83.14   |   74.35   |   65.37   |   89.59   |   58.82   |   86.23   |   70.30   |   93.15   | **98.77** |   84.21    |   99.17   |   99.08   |   96.09   |   98.55   |   96.30   |   86.07   |
| DRCT/Conv-B | ICML2024  |  54.79  |   57.09   |   55.55   |   49.89   |   51.13   |   49.13   |   52.05   |   50.05   |   61.78   |   65.92   |   94.63    | **99.88** | **99.82** |   74.88   | **99.91** |   73.20   |   68.11   |
| DRCT/UnivFD | ICML2024  |  76.85  |   71.58   |   82.67   |   94.51   |   63.08   |   78.39   |   67.73   |   63.10   |   79.43   |   89.12   |   91.51    |   95.03   |   94.40   |   90.02   |   94.65   |   92.60   |   82.79   |
|  C2P-CLIP   | AAAI2025  |  99.98  |   96.44   |   99.12   |   97.31   |   99.60   |   99.17   |   95.59   |   94.80   |   77.12   |   88.48   |   59.12    |   82.76   |   82.73   |   87.16   |   80.12   |   65.10   |   87.79   |
|    SAFE     |  KDD2025  |  99.86  |   98.04   |   89.72   |   98.87   | **99.90** |   91.52   |   98.57   |   51.95   |   82.05   |   96.29   | **95.27**  |   99.41   |   99.27   | **96.29** |   98.21   |   95.30   | **93.16** |
| AIDE_ProGAN | ICLR2025  |  99.99  | **99.65** |   83.95   |   98.49   | **99.90** |   73.24   |   98.01   |   94.20   | **93.46** |   95.10   |   77.21    |   92.99   |   92.85   |   95.16   |   93.53   | **96.60** |   92.77   |
| AIDE_SDv1.4 | ICLR2025  |  69.28  |   71.05   |   77.20   |   74.38   |   80.24   |   64.36   |   72.53   |   72.50   |   78.54   |   91.83   |   79.38    |   99.74   |   99.76   |   80.26   |   98.66   |   95.00   |   81.54   |

&nbsp;

### ForenSynths

|           |   Time    |  ProGAN   | StyleGAN  | StyleGAN2 |  BigGAN   | CycleGAN  |  StarGAN  |  GauGAN   | Deepfake  |   SITD    |    SAN    |    CRN    |   IMLE    |   WFIR    |   Mean    |
| :-------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: |
|   CNNSpot   | CVPR2020  | **100** |   90.17   |   86.91   |   71.17   |   87.59   |   94.60   |   81.44   |   50.71   | **98.06** |   50.00   |   86.34   |   86.34   | **95.10** |   82.96   |
|  FreDetect  | ICML2020  |  99.36  |   78.02   |   66.17   |   81.97   |   78.77   |   94.62   |   80.57   |   63.29   |   33.33   |   50.00   |   60.04   |   60.13   |   46.45   |   68.67   |
|   UnivFD    | CVPR2023  |  99.81  |   84.93   |   74.96   |   95.08   |   98.33   |   95.75   | **99.47** |   68.57   |   62.22   |   56.62   |   56.59   |   69.11   |   87.20   |   80.66   |
|    LGrad    | CVPR2023  |  99.86  |   89.72   |   85.30   |   84.58   |   87.81   |   99.30   |   82.26   |   51.17   |   48.06   |   41.55   |   51.51   |   51.54   |   52.95   |   71.20   |
|     NPR     | CVPR2024  |  99.79  |   97.71   |   98.39   |   84.35   |   96.10   |   99.35   |   82.50   |   80.22   |   62.50   |   69.18   |   50.00   |   50.00   |   65.75   |   79.68   |
|   FreqNet   | AAAI2024  |  99.58  |   90.24   |   87.95   |   90.45   |   95.84   |   85.69   |   93.41   |   88.92   |   65.56   |   71.92   |   59.03   |   59.05   |   49.20   |   79.76   |
|  FatFormer  | CVPR2024  |  99.89  |   97.13   | **98.80** | **99.50** | **99.36** |   99.75   |   99.43   |   93.27   |   81.39   |   68.04   |   69.46   |   69.46   |   88.11   |   89.51   |
|     SSP     | arXiv2024 |  83.70  |   83.11   |   86.37   |   73.12   |   65.40   |   90.22   |   59.32   |   67.51   |   77.50   |   78.77   |   52.19   |   51.69   |   69.10   |   72.15   |
| DRCT/Conv-B | ICML2024 |  54.79  |   57.09   |   52.05   |   55.55   |   49.89   |   51.13   |   49.13   |   73.28   |   85.56   |   85.84   |   49.19   |   49.44   |   50.05   |   58.69   |
| DRCT/UnivFD | ICML2024 |  76.85  |   71.58   |   67.73   |   82.67   |   94.51   |   63.08   |   78.39   |   57.34   |   69.17   |   78.77   |   43.90   |   50.49   |   63.10   |   69.04   |
|  C2P-CLIP   | AAAI2025  |  99.98  |   96.44   |   95.59   |   99.12   |   97.31   |   99.60   |   99.17   | **93.77** |   95.56   |   64.38   | **93.29** | **93.29** |   94.80   | **94.02** |
|    SAFE     |  KDD2025  |  99.86  |   98.04   |   98.57   |   89.72   |   98.87   | **99.90** |   91.52   |   93.10   |   85.56   | **95.91** |   50.10   |   50.10   |   51.95   |   84.86   |
| AIDE_ProGAN | ICLR2025  |  99.99  | **99.65** |   98.01   |   83.95   |   98.49   | **99.90** |   73.24   |   54.06   |   68.61   |   71.00   |   60.87   |   61.00   |   94.20   |   81.77   |
| AIDE_SDv1.4 | ICLR2025  |  69.28  |   71.05   |   72.53   |   77.20   |   74.38   |   80.24   |   64.36   |   54.25   |   69.72   |   57.53   |   49.62   |   67.66   |   72.50   |   67.72   |

*Note: ForenSynths contains <1K images in SAN/SITD categories and exhibits class imbalance*

&nbsp;

### Self-Synthesis (GAN Based)

|           |   Time    |  AttGAN   |   BEGAN   | CramerGAN | InfoMaxGAN |  MMDGAN   |  RelGAN   |   S3GAN   |   SNGAN   |   STGAN   |   Mean    |
| :-------: | :-------: | :-------: | :-------: | :-------: | :--------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: |
|   CNNSpot   | CVPR2020  |   67.55   |   84.03   |   94.75   |   75.35    |   94.05   |   91.10   |   71.33   |   76.50   |   82.42   |   81.90   |
|  FreDetect  | ICML2020  |   28.57   |   58.27   |   46.17   |   41.40    |   48.27   |   66.62   |   91.05   |   57.25   |   50.00   |   54.18   |
|   UnivFD    | CVPR2023  |   90.80   |   89.35   |   90.70   |   88.48    |   90.62   |   93.38   |   94.12   |   88.65   |   82.75   |   89.87   |
|    LGrad    | CVPR2023  |   56.15   |   50.02   |   50.60   |   53.20    |   50.95   |   78.38   |   82.33   |   52.12   |   50.25   |   58.22   |
|     NPR     | CVPR2024  |   82.97   |   98.98   |   98.65   |   94.45    |   98.55   |   99.62   |   79.00   |   88.83   |   97.97   |   93.22   |
|   FreqNet   | AAAI2024  |   89.78   |   52.45   |   55.35   |   58.63    |   58.50   | **99.98** |   88.35   |   58.67   |   64.70   |   69.60   |
|  FatFormer  | CVPR2024  |   99.33   | **99.88** |   98.35   |   98.35    |   98.35   |   99.45   | **99.00** |   98.28   |   98.78   |   98.86   |
|     SSP     | arXiv2024 |   89.30   |   91.27   |   68.30   |   75.45    |   72.20   |   76.90   |   46.25   |   65.88   |   74.38   |   73.33   |
|  C2P-CLIP   | AAAI2025  |   90.42   |   94.85   |   98.40   |   98.40    |   98.40   |   91.97   |   98.98   |   98.38   |   97.58   |   96.38   |
|    SAFE     |  KDD2025  | **99.38** |   99.80   | **99.73** | **99.55**  | **99.73** |   99.55   |   94.48   | **98.80** | **99.90** | **98.99** |
| AIDE_ProGAN | ICLR2025  |   98.05   |   94.38   |   98.05   |   97.98    |   97.93   |   98.13   |   85.93   |   95.30   |   95.93   |   95.74   |
| AIDE_SDv1.4 | ICLR2025  |   84.13   |   51.30   |   57.40   |   58.25    |   65.65   |   63.33   |   49.50   |   56.23   |   64.90   |   61.19   |

&nbsp;

### UniversalFakeDetect (DM Based)

|           |   Time    |   DALLE   | Glide_100_10 | Glide_100_27 | Glide_50_27 |    ADM    |  LDM_100  |  LDM_200  | LDM_200_cfg |   Mean    |
| :-------: | :-------: | :-------: | :----------: | :----------: | :---------: | :-------: | :-------: | :-------: | :---------: | :-------: |
|   CNNSpot   | CVPR2020  |   57.65   |    62.35     |    61.30     |    64.50    |   62.45   |   54.85   |   54.75   |    55.95    |   59.23   |
|  FreDetect  | ICML2020  |   91.00   |    59.15     |    61.60     |    62.80    |   60.40   |   88.75   |   88.45   |    86.15    |   74.79   |
|   UnivFD    | CVPR2023  |   87.45   |    78.05     |    78.65     |    79.20    |   70.00   |   95.15   |   94.55   |    74.15    |   82.15   |
|    LGrad    | CVPR2023  |   84.65   |    84.80     |    82.55     |    85.10    |   69.30   |   85.00   |   84.10   |    86.00    |   82.69   |
|     NPR     | CVPR2024  |   93.85   |    97.60     |    97.10     |    97.55    |   75.15   |   98.65   |   98.45   |    98.30    |   94.58   |
|   FreqNet   | AAAI2024  |   97.25   |    87.95     |    84.40     |    86.55    |   67.25   |   97.75   |   97.40   |    97.20    |   89.47   |
|  FatFormer  | CVPR2024  | **98.70** |    94.15     |    94.30     |    94.60    |   76.01   |   98.60   |   98.55   |    94.85    |   93.72   |
|     SSP     | arXiv2024 |   97.85   |  **97.95**   |    97.60     |  **98.45**  |   89.05   |   98.15   |   97.95   |    98.45    | **96.93** |
|  C2P-CLIP   | AAAI2025  |   98.55   |    96.10     |    95.25     |    95.25    |   69.10   | **99.30** | **99.25** |    97.25    |   93.76   |
|    SAFE     |  KDD2025  |   97.50   |    97.25     |    95.75     |    96.60    |   82.36   |   98.80   |   98.80   |  **98.65**  |   95.71   |
| AIDE_ProGAN | ICLR2025  |   97.50   |    97.85     |  **98.15**   |    98.40    | **89.30** |   98.40   |   98.20   |    97.45    |   96.91   |
| AIDE_SDv1.4 | ICLR2025  |   87.55   |    92.90     |    92.85     |    93.60    | **89.30** |   97.20   |   97.10   |    97.70    |   93.53   |

&nbsp;

### GenImage

|           |   Time    | Midjourney |  SDv1.4   |  SDv1.5   |    ADM    |   Glide   |  Wukong   |   VQDM    |  BigGAN   |   Mean    |
| :-------: | :-------: | :--------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: |
|   CNNSpot   | CVPR2020  |   51.40    |   50.58   |   50.52   |   60.38   |   58.03   |   51.03   |   56.45   |   72.92   |   56.41   |
|  FreDetect  | ICML2020  |   46.89    |   40.02   |   40.39   |   64.67   |   55.43   |   41.54   |   78.95   |   40.23   |   51.02   |
|   UnivFD    | CVPR2023  |   56.24    |   63.75   |   63.57   |   66.94   |   62.53   |   71.06   |   85.42   |   90.18   |   69.96   |
|    LGrad    | CVPR2023  |   67.09    |   63.78   |   65.08   |   64.12   |   70.30   |   60.14   |   72.62   |   52.91   |   64.51   |
|     NPR     | CVPR2024  |   77.83    |   78.62   |   78.88   |   69.72   |   78.35   |   76.10   |   78.13   |   80.08   |   77.21   |
|   FreqNet   | AAAI2024  |   69.83    |   64.22   |   64.91   |   83.27   |   81.66   |   57.72   |   81.65   |   90.57   |   74.23   |
|  FatFormer  | CVPR2024  |   56.08    |   67.83   |   68.06   |   78.44   |   88.03   |   73.06   |   86.87   |   96.80   |   76.90   |
|     SSP     | arXiv2024 |   84.38    |   99.09   |   99.03   |   93.21   | **98.78** |   98.45   |   95.74   |   78.06   |   93.34   |
| DRCT/Conv-B | ICML2024  |   94.63    |   99.88   |   99.82   |   61.78   |   65.92   |   99.91   |   74.88   |   59.81   |   82.08   |
| DRCT/UnivFD | ICML2024  |   91.51    |   95.03   |   94.40   |   79.43   |   89.12   |   94.65   |   90.02   |   81.58   |   89.47   |
|  C2P-CLIP   | AAAI2025  |   59.12    |   82.76   |   82.73   |   77.12   |   88.48   |   80.12   |   87.16   | **97.94** |   81.93   |
|    SAFE     |  KDD2025  | **95.27**  |   99.41   |   99.27   |   82.05   |   96.29   |   98.21   | **96.29** |   97.84   | **95.58** |
| AIDE_ProGAN | ICLR2025  |   77.22    |   92.99   |   92.85   | **93.47** |   95.10   |   93.53   |   95.16   |   95.19   |   91.94   |
| AIDE_SDv1.4 | ICLR2025  |   79.38    | **99.74** | **99.76** |   78.54   |   91.83   | **98.66** |   80.26   |   66.89   |   86.88   |

&nbsp;

### DRCT-2M

|           |   Time    |    LDM    |  SDv1.4   |  SDv1.5   |   SDv2    |   SDXL    | SDXL-Refiner | SD-Turbo  | SDXL-Turbo | LCM-SDv1.5 | LCM-SDXL  | SDv1-Ctrl | SDv2-Ctrl | SDXL-Ctrl |  SDv1-DR  |  SDv2-DR  |  SDXL-DR  |   Mean    |
| :-------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: | :----------: | :-------: | :--------: | :--------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: | :-------: |
|   CNNSpot    | CVPR2020  |   48.89   |   48.74   |   48.77   |   49.16   |   48.90   |    48.80     |   48.74   |   48.73    |   48.74    |   49.10   |   48.75   |   48.74   |   48.73   |   51.15   |   49.16   |   48.88   | 49.00 |
|  FreDetect   | ICML2020  |   88.75   |   40.17   |   40.27   |   41.79   |   62.16   |    62.16     | **61.03** | **69.46**  |   46.20    |   57.18   |   33.43   |   29.76   |   34.62   |   42.64   |   41.79   |   43.51   | 49.68 |
|    UnivFD    | CVPR2023  |   85.38   |   56.84   |   56.41   | **58.17** | **63.24** |    55.04     |   56.46   |   52.98    |   54.49    |   65.86   | **75.85** | **65.42** |   61.80   |   64.60   |   56.15   |   53.90   | 61.41 |
|    LGrad     | CVPR2023  |   34.77   |   31.09   |   31.09   |   31.66   |   31.57   |    31.08     |   31.18   |   31.06    |   31.22    |   31.28   |   31.23   |   31.11   |   31.77   |   55.07   |   52.06   |   31.28   | 34.28 |
|     NPR      | CVPR2024  |   31.23   |   32.67   |   32.65   |   35.19   |   31.53   |    32.10     |   32.17   |   32.92    |   33.55    |   30.86   |   30.63   |   30.69   |   35.40   |   71.07   |   70.55   |   68.63   | 39.49 |
|   FreqNet    | AAAI2024  |   42.31   |   41.35   |   41.35   |   41.03   |   41.38   |    41.46     |   41.35   |   41.35    |   41.36    |   41.37   |   41.35   |   41.37   |   41.38   |   57.31   |   51.03   |   56.41   | 43.95 |
|  FatFormer   | CVPR2024  | **98.60** |   48.54   |   48.55   |   48.57   |   48.55   |    48.61     |   48.59   |   48.54    |   48.63    |   50.09   |   61.09   |   50.11   |   54.17   |   49.91   |   59.56   |   64.45   | 54.79 |
|     SSP      | arXiv2024 |   51.73   |   50.47   |   50.51   |   49.96   |   49.93   |    49.93     |   49.85   |   49.91    |   50.67    |   49.79   |   50.09   |   50.16   |   50.67   | **98.64** |   84.92   |   82.43   | 57.48 |
|   C2P-CLIP   | AAAI2025  |   83.02   |   51.96   |   51.94   |   52.92   |   51.94   |    64.60     |   51.72   |   50.62    |   52.03    | **66.05** |   56.86   |   54.69   | **77.77** |   67.24   |   57.14   |   56.72   | 59.20 |
|     SAFE     |  KDD2025  |   50.28   |   50.05   |   50.00   |   49.98   |   49.92   |    50.14     |   49.96   |   49.95    |   50.13    |   49.95   |   49.94   |   50.00   |   54.74   |   98.18   | **98.47** | **97.26** | 59.31 |
| AIDE_ProGAN  | ICLR2025  |   71.87   |   50.83   |   50.79   |   50.21   |   49.61   |    53.54     |   49.87   |   49.81    |   50.16    |   51.26   |   53.81   |   53.71   |   65.30   |   94.92   |   90.17   |   89.13   | 60.94 |
| AIDE_SDv1.4  | ICLR2025  |   61.87   | **74.76** | **74.53** |   58.07   |   53.00   |  **66.01**   |   52.86   |   53.00    | **69.76**  |   54.05   |   64.95   |   53.1    |   53.45   |   95.33   |   73.28   |   69.47   | **64.22** |
| AIDE_ProGAN* | ICLR2025  |   78.39   |   58.23   |   57.73   |   54.5    |   48.71   |    62.51     |   52.96   |   47.07    |   55.74    |   56.36   |   68.62   |   67.01   |   72.84   |   78.88   |   78.48   |   78.37   | 63.53 |
| AIDE_SDv1.4* | ICLR2025  |   92.14   |   94.96   |   94.96   |   90.00   |   87.76   |    96.76     |   79.79   |   82.88    |   94.20    |   91.59   |   86.40   |   83.11   |   91.67   |   97.65   |   88.39   |   90.43   | 90.17 |

*Threshold set at 0.07

&nbsp;

**Key Observations:**
- DRCT-2M primarily evaluates robustness against JPEG compression artifacts
- SAFE demonstrates strong cross-domain generalization
- Task-specific methods (AIDE_ProGAN/AIDE_SDv1.4) excel on their target domains
- Detection performance varies significantly across generative architectures
