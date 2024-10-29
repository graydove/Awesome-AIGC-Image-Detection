# AIGCDetectBenchmark++
There is a new AIGC detection benchmark,  including six benchmarks. All results are obtained by running their official codes; more details will be coming soon.
,

## AIGCDetectBenchmark

|           | Time      | ProGAN         | StyleGAN      | BigGAN        | CycleGAN       | StarGAN        | GauGAN         | StyleGAN2     | WFIR          | ADM           | Glide         | Midjourney    | SD v1.4       | SD v1.5       | VQDM          | Wukong        | DALLE2        | Mean              |
|:---------:|:---------:|:--------------:|:-------------:|:-------------:|:--------------:|:--------------:|:--------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-----------------:|
| CNNSpot   | CVPR2020  | 100.0, 100.0  | 90.17, 99.83 | 71.17, 85.99 | 87.59, 94.93  | 94.60, 99.04  | 81.44, 90.80  | 86.91, 99.48 | 95.10, 99.91 | 60.38, 75.70 | 58.03, 72.29 | 51.40, 66.25 | 50.58, 61.18 | 50.52, 61.53 | 56.45, 68.83 | 51.03, 57.33 | 51.25, 54.53 | 71.04, 80.48     |
| FreDetect | ICML2020  | 99.36, 99.99  | 78.02, 88.98 | 81.97, 93.62 | 78.77, 84.78  | 94.62, 99.49  | 80.57, 82.86  | 66.17, 82.53 | 46.45, 44.46 | 64.67, 63.73 | 55.43, 54.73 | 46.89, 47.25 | 40.02, 38.51 | 40.39, 38.42 | 78.95, 86.02 | 41.54, 40.44 | 34.65, 38.20 | 64.28, 67.75     |
| UnivFD    | CVPR2023  | 99.81, 100.00 | 84.93, 97.56 | 95.08, 99.27 | 98.33, 99.80  | 95.75, 99.37  | 99.47, 99.98  | 74.96, 97.90 | 87.20, 97.27 | 66.94, 87.13 | 62.53, 84.26 | 56.24, 74.61 | 63.75, 86.56 | 63.57, 86.19 | 85.42, 96.65 | 71.06, 91.34 | 50.75, 63.04 | 78.49, 91.31     |
| LGrad     | CVPR2023  | 99.86, 100.00 | 89.72, 98.01 | 84.58, 91.58 | 87.81, 95.11  | 99.30, 100.00 | 82.26, 93.88  | 85.30, 98.30 | 52.95, 55.92 | 64.12, 70.38 | 70.30, 82.83 | 67.09, 73.34 | 63.78, 64.89 | 65.08, 65.29 | 72.62, 76.93 | 60.14, 63.24 | 68.55, 84.09 | 75.84, 82.11     |
| NPR       | CVPR2024  | 99.79, 99.99 | 97.71, 99.78 | 84.35, 87.80 | 96.10, 98.45 | 99.35, 99.94 | 82.50, 85.49 | 98.39, 99.94 | 65.75, 65.32 | 69.72, 74.64 | 78.35, 85.72 | 77.83, 85.36 | 78.62, 84.03 | 78.88, 84.59 | 78.13, 81.19 | 76.10, 80.47 | 64.90, 76.69 | 82.90, 86.84     |
| FreqNet   | AAAI2024  | 99.58, 100.00 | 90.24, 99.71 | 90.45, 96.05 | 95.84, 99.63 | 85.69, 99.80 | 93.41, 98.63 | 87.95, 99.49 | 49.20, 51.07 | 83.27, 91.44 | 81.66, 88.86 | 69.83, 78.89 | 64.22, 74.33 | 64.91, 75.62 | 81.65, 89.59 | 57.72, 66.96 | 55.30, 54.62 | 78.18, 85.29     |
| FatFormer | CVPR2024  | 99.89, 100.00 | 97.13, 99.75 | 99.50, 99.98 | 99.36, 100.00 | 99.75, 100.00 | 99.43, 100.00 | 98.80, 99.92 | 88.16, 98.48 | 78.44, 91.73 | 88.03, 95.99 | 56.08, 62.76 | 67.83, 81.12 | 68.06, 81.09 | 86.87, 96.99 | 73.06, 85.86 | 69.67, 81.83 | 85.63, 92.22     |
| SSP       | arXiv2024 | 84.01, 91.66  | 83.14, 97.07 | 74.35, 97.06 | 65.37, 93.90  | 89.59, 96.29  | 58.82, 96.08  | 86.23, 96.19 | 70.30, 96.73 | 93.15, 97.28 | 98.77, 97.11 | 84.21, 97.63 | 99.17, 97.89 | 99.08, 97.76 | 96.09, 96.23 | 98.55, 97.28 | 96.30, 96.36 | 88.97, 96.08     |
| C2L-CLIP  | arXiv2024 | 99.98, 100.00 | 96.44, 99.50 | 99.12, 99.96 | 97.31, 100.00 | 99.60, 100.00 | 99.17, 100.00 | 95.59, 99.86 | 94.80, 99.54 | 77.12, 95.74 | 88.48, 98.76 | 59.12, 83.04 | 82.76, 97.26 | 82.73, 97.23 | 87.16, 98.40 | 80.12, 95.45 | 65.10, 92.84 | 87.79, **97.35** |
| SAFE      | arXiv2024 | 99.86, 100.00 | 98.04, 99.93 | 89.72, 95.89 | 98.87, 99.77  | 99.90, 100.00 | 91.52, 97.20  | 98.57, 99.99 | 51.95, 51.65 | 82.05, 96.66 | 96.29, 99.27 | 95.27, 99.53 | 99.41, 99.95 | 99.27, 99.92 | 96.29, 99.56 | 98.21, 99.79 | 95.30, 99.52 | **93.16**, 96.16 |

&nbsp;

## ForenSynths

|           | Time      | ProGAN         | StyleGAN      | StyleGAN2     | BigGAN        | CycleGAN       | StarGAN        | GauGAN         | Deepfake      | SITD          | SAN           | CRN           | IMLE          | WFIR          | Mean              |
|:---------:|:---------:|:--------------:|:-------------:|:-------------:|:-------------:|:--------------:|:--------------:|:--------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-----------------:|
| CNNSpot   | CVPR2020  | 100.0, 100.0  | 90.17, 99.83 | 86.91, 99.48 | 71.17, 85.99 | 87.59, 94.93  | 94.60, 99.04  | 81.44, 90.80  | 50.71, 84.47 | 98.06, 99.81 | 50.00, 68.56 | 86.34, 99.84 | 86.34, 99.84 | 95.10, 99.91 | 77.76, 92.07     |
| FreDetect | ICML2020  | 99.36, 99.99  | 78.02, 88.98 | 66.17, 82.53 | 81.97, 93.62 | 78.77, 84.78  | 94.62, 99.49  | 80.57, 82.86  | 63.29, 70.77 | 33.33, 35.76 | 50.00, 49.50 | 60.04, 82.27 | 60.13, 69.78 | 46.45, 44.46 | 68.67, 75.75     |
| UnivFD    | CVPR2023  | 99.81, 100.00 | 84.93, 97.56 | 74.96, 97.90 | 95.08, 99.27 | 98.33, 99.80  | 95.75, 99.37  | 99.47, 99.98  | 68.57, 81.76 | 62.22, 63.84 | 56.62, 78.81 | 56.59, 96.59 | 69.11, 98.61 | 87.20, 97.27 | 80.66, 93.14     |
| LGrad     | CVPR2023  | 99.86, 100.00 | 89.72, 98.01 | 85.30, 98.30 | 84.58, 91.58 | 87.81, 95.11  | 99.30, 100.00 | 82.26, 93.88  | 51.17, 64.13 | 48.06, 41.65 | 41.55, 44.42 | 51.51, 63.52 | 51.54, 77.00 | 52.95, 55.92 | 75.05, 78.73     |
| NPR       | CVPR2024  | 99.79, 99.99 | 97.71, 99.78 | 98.39, 99.94 | 84.35, 87.80 | 96.10, 98.45 | 99.35, 99.94 | 82.50, 85.49 | 80.22, 82.40 | 62.50, 60.89 | 69.18, 71.57 | 50.00, 50.00 | 50.00, 50.00 | 65.75, 65.32 | 79.68, 80.89     |
| FreqNet   | AAAI2024  | 99.58, 100.00 | 90.24, 99.71 | 87.95, 99.49 | 90.45, 96.05 | 95.84, 99.63 | 85.69, 99.80 | 93.41, 98.63 | 88.92, 94.42 | 65.56, 62.34 | 71.92, 80.10 | 59.03, 74.59 | 59.05, 77.78 | 49.20, 51.07 | 79.76, 87.20     |
| FatFormer | CVPR2024  | 99.89, 100.00 | 97.13, 99.75 | 98.80, 99.92 | 99.50, 99.98 | 99.36, 100.00 | 99.75, 100.00 | 99.43, 100.00 | 93.27, 97.99 | 81.39, 97.93 | 68.04, 81.23 | 69.46, 99.84 | 69.46, 99.93 | 88.11, 98.48 | 89.51, 98.08     |
| SSP       | arXiv2024 | 83.70, 92.91  | 83.11, 93.36 | 86.37, 94.58 | 73.12, 77.30 | 65.40, 80.39  | 90.22, 93.65  | 59.32, 83.61  | 67.51, 81.24 | 77.50, 93.49 | 78.77, 93.16 | 52.19, 77.10 | 51.69, 85.51 | 69.10, 88.08 | 70.36, 77.30     |
| C2P-CLIP  | arXiv2024 | 99.98, 100.00 | 96.44, 99.50 | 95.59, 99.86 | 99.12, 99.96 | 97.31, 100.00 | 99.60, 100.00 | 99.17, 100.00 | 93.77, 98.59 | 95.56, 98.92 | 64.38, 84.56 | 93.29, 99.86 | 93.29, 99.95 | 94.80, 99.54 | **94.02, 98.52** |
| SAFE      | arXiv2024 | 99.86, 100.00 | 98.04, 99.93 | 98.57, 99.99 | 89.72, 95.89 | 98.87, 99.77  | 99.90, 100.00 | 91.52, 97.20  | 93.10, 97.44 | 85.56, 85.07 | 95.91, 99.27 | 50.10, 41.33 | 50.10, 47.25 | 51.95, 51.65 | 84.86, 85.75     |

&nbsp;

## Self-Synthesis (GAN Based)

|           | Time      | AttGAN        | BEGAN          | CramerGAN      | InfoMaxGAN    | MMDGAN         | RelGAN         | S3GAN         | SNGAN         | STGAN          | Mean              |
|:---------:|:---------:|:-------------:|:--------------:|:--------------:|:-------------:|:--------------:|:--------------:|:-------------:|:-------------:|:--------------:|:-----------------:|
| CNNSpot   | CVPR2020  | 67.55, 94.07 | 84.03, 93.04  | 94.75, 98.88  | 75.35, 88.45 | 94.05, 98.49  | 91.10, 99.51  | 71.33, 83.34 | 76.50, 89.56 | 82.42, 97.60  | 81.90, 93.66     |
| FreDetect | ICML2020  | 28.57, 35.29 | 58.27, 94.77  | 46.17, 50.45  | 41.40, 39.01 | 48.27, 52.23  | 66.62, 53.95  | 91.05, 98.52 | 57.25, 61.66 | 50.00, 46.64  | 54.18, 59.17     |
| UnivFD    | CVPR2023  | 90.80, 96.99 | 89.35, 96.34  | 90.70, 99.29  | 88.48, 96.90 | 90.62, 99.18  | 93.38, 98.00  | 94.12, 98.82 | 88.65, 96.81 | 82.75, 91.64  | 89.87, 97.11     |
| LGrad     | CVPR2023  | 56.15, 85.47 | 50.02, 58.30  | 50.60, 70.07  | 53.20, 89.16 | 50.95, 79.71  | 78.38, 97.08  | 82.33, 90.80 | 52.12, 88.29 | 50.25, 93.27  | 58.22, 83.57     |
| NPR       | CVPR2024  | 82.97, 96.17 | 98.98, 99.75 | 98.65, 99.00 | 94.45, 98.29 | 98.55, 98.96 | 99.62, 100.00 | 79.00, 80.04 | 88.83, 97.39 | 97.97, 100.00 | 93.23, 96.62     |
| FreqNet   | AAAI2024  | 89.78, 98.78 | 52.45, 78.97 | 55.35, 65.70 | 58.63, 73.04 | 58.50, 78.86 | 99.98, 100.00 | 88.35, 94.29 | 58.67, 81.92 | 64.70, 81.60 | 69.60, 83.69     |
| FatFormer | CVPR2024  | 99.33, 99.99 | 99.88, 100.00 | 98.35, 100.00 | 98.35, 99.98 | 98.35, 100.00 | 99.45, 100.00 | 99.00, 99.95 | 98.28, 99.91 | 98.78, 99.78  | 98.86, **99.96** |
| SSP       | arXiv2024 | 89.30, 89.55 | 91.27, 87.39  | 68.30, 83.19  | 75.45, 85.76 | 72.20, 84.23  | 76.90, 84.27  | 46.25, 75.23 | 65.88, 83.63 | 74.38, 84.14  | 73.32, 75.23     |
| C2P-CLIP  | arXiv2024 | 90.42, 99.83 | 94.85, 100.00 | 98.40, 99.97  | 98.40, 99.97 | 98.40, 99.97  | 91.97, 99.81  | 98.98, 99.95 | 98.38, 99.91 | 97.58, 99.64  | 96.38, 99.90     |
| SAFE      | arXiv2024 | 99.38, 99.99 | 99.80, 100.00 | 99.73, 100.00 | 99.55, 99.99 | 99.73, 100.00 | 99.55, 100.00 | 94.48, 98.71 | 98.80, 99.95 | 99.90, 100.00 | **98.99**, 99.85 |

&nbsp;

## Ojha (DM Based)

|           | Time      | DALLE         | Glide_100_10  | Glide_100_27  | Glide_50_27   | ADM           | LDM_100       | LDM_200       | LDM_200_cfg   | Mean                  |
|:---------:|:---------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:---------------------:|
| CNNSpot   | CVPR2020  | 57.65, 72.97 | 62.35, 82.56 | 61.30, 80.23 | 64.50, 84.78 | 62.45, 78.21 | 54.85, 71.65 | 54.75, 70.41 | 55.95, 73.70 | 59.23, 76.81         |
| FreDetect | ICML2020  | 91.00, 97.84 | 59.15, 66.98 | 61.60, 68.56 | 62.80, 70.02 | 60.40, 60.80 | 88.75, 96.59 | 88.45, 96.35 | 86.15, 94.88 | 74.79, 81.50         |
| UnivFD    | CVPR2023  | 87.45, 97.73 | 78.05, 95.48 | 78.65, 95.79 | 79.20, 96.03 | 70.00, 88.27 | 95.15, 99.35 | 94.55, 99.40 | 74.15, 93.22 | 82.15, 95.66         |
| LGrad     | CVPR2023  | 84.65, 92.72 | 84.80, 94.24 | 82.55, 91.57 | 85.10, 94.03 | 69.30, 75.43 | 85.00, 93.09 | 84.10, 92.75 | 86.00, 94.35 | 82.69, 91.02         |
| NPR       | CVPR2024  | 93.85, 98.96 | 97.60, 99.63 | 97.10, 99.55 | 97.55, 99.61 | 75.15, 80.29 | 98.65, 99.80 | 98.45, 99.76 | 98.30, 99.73 | 94.58, 97.17         |
| FreqNet   | AAAI2024  | 97.25, 99.74 | 87.95, 96.03 | 84.40, 95.57 | 86.55, 95.84 | 67.25, 75.43 | 97.75, 99.93 | 97.40, 99.89 | 97.20, 99.92 | 89.47, 95.29     |
| FatFormer | CVPR2024  | 98.70, 99.84 | 94.15, 99.33 | 94.30, 99.27 | 94.60, 99.50 | 76.01, 91.90 | 98.60, 99.89 | 98.55, 99.83 | 94.85, 99.22 | 93.72, 98.60         |
| SSP       | arXiv2024 | 97.85, 99.32 | 97.95, 99.73 | 97.60, 99.01 | 98.45, 99.27 | 89.05, 98.93 | 98.15, 99.22 | 97.95, 99.13 | 98.45, 99.80 | **96.93**, **99.32** |
| C2P-CLIP  | arXiv2024 | 98.55, 99.91 | 96.10, 99.83 | 95.25, 99.72 | 95.25, 99.79 | 69.10, 94.13 | 99.30, 99.98 | 99.25, 99.99 | 97.25, 99.83 | 93.76, 99.15         |
| SAFE      | arXiv2024 | 97.50, 99.67 | 97.25, 99.36 | 95.75, 98.93 | 96.60, 99.21 | 82.36, 95.81 | 98.80, 99.96 | 98.80, 99.96 | 98.65, 99.92 | 95.71, 99.10         |

&nbsp;

## GenImage

|           | Time      | Midjourney    | SDv1.4        | SDv1.5        | ADM           | Glide         | Wukong        | VQDM          | BigGAN        | Mean              |
|:---------:|:---------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-----------------:|
| CNNSpot   | CVPR2020  | 51.40, 66.25 | 50.58, 61.18 | 50.52, 61.53 | 60.38, 75.70 | 58.03, 72.29 | 51.03, 57.33 | 56.45, 68.83 | 72.92, 86.94 | 56.41, 68.76     |
| FreDetect | ICML2020  | 46.89, 47.25 | 40.02, 38.51 | 40.39, 38.42 | 64.67, 63.73 | 55.43, 54.73 | 41.54, 40.44 | 78.95, 86.02 | 40.23, 47.79 | 51.02, 52.11     |
| UnivFD    | CVPR2023  | 56.24, 74.61 | 63.75, 86.56 | 63.57, 86.19 | 66.94, 87.13 | 62.53, 84.26 | 71.06, 91.34 | 85.42, 96.65 | 90.18, 98.21 | 69.96, 88.12     |
| LGrad     | CVPR2023  | 67.09, 73.34 | 63.78, 64.89 | 65.08, 65.29 | 64.12, 70.38 | 70.30, 82.83 | 60.14, 63.24 | 72.62, 76.93 | 52.91, 52.92 | 64.50, 68.73     |
| NPR       | CVPR2024  | 77.83, 85.36 | 78.62, 84.03 | 78.88, 84.59 | 69.72, 74.64 | 78.35, 85.72 | 76.10, 80.47 | 78.13, 81.19 | 80.08, 88.20 | 77.21, 83.02     |
| FreqNet   | AAAI2024  | 69.83, 78.89 | 64.22, 74.33 | 64.91, 75.62 | 83.27, 91.44 | 81.66, 88.86 | 57.72, 66.96 | 81.65, 89.59 | 90.57, 94.92 | 74.23, 82.57     |
| FatFormer | CVPR2024  | 56.08, 62.76 | 67.83, 81.12 | 68.06, 81.09 | 78.44, 91.73 | 88.03, 95.99 | 73.06, 85.86 | 86.87, 96.99 | 96.80, 99.55 | 76.90, 86.89     |
| SSP*      | arXiv2024 | 84.38, 99.04 | 99.09, 99.96 | 99.03, 99.37 | 93.21, 99.05 | 98.78, 99.78 | 98.45, 99.26 | 95.74, 99.76 | 78.06, 99.11 | 93.57, 99.05     |
| C2P-CLIP  | arXiv2024 | 59.12, 83.04 | 82.76, 97.26 | 82.73, 97.23 | 77.12, 95.74 | 88.48, 98.76 | 80.12, 95.45 | 87.16, 98.40 | 97.94, 99.90 | 81.93, 95.72     |
| SAFE      | arXiv2024 | 95.27, 99.53 | 99.41, 99.95 | 99.27, 99.92 | 82.05, 96.66 | 96.29, 99.27 | 98.21, 99.79 | 96.29, 99.56 | 97.84, 99.82 | **95.58, 99.31** |

*SSP trained on SDv1.4 training set from GenImage.

&nbsp;

## DRCT-2M

|           | Time      | LDM           | SDv1.4        | SDv1.5        | SDv2          | SDXL          | SDXL-Refiner  | SD-Turbo      | SDXL-Turbo    | LCM-SDv1.5    | LCM-SDXL      | SDv1-Ctrl     | SDv2-Ctrl     | SDXL-Ctrl     | SDv1-DR       | SDv2-DR       | SDXL-DR       | Mean              |
|:---------:|:---------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|:-----------------:|
| CNNSpot   | CVPR2020  | 48.89, 48.06 | 48.74, 55.06 | 48.77, 54.55 | 49.16, 54.79 | 48.90, 65.43 | 48.80, 62.32 | 48.74, 53.48 | 48.73, 65.43 | 48.74, 60.19 | 49.10, 80.85 | 48.75, 53.34 | 48.74, 47.31 | 48.73, 50.15 | 51.15, 59.70 | 49.16, 46.14 | 48.88, 40.42 | 49.07, 56.45     |
| FreDetect | ICML2020  | 88.75, 96.59 | 40.17, 41.35 | 40.27, 41.12 | 41.79, 42.35 | 62.16, 64.35 | 62.16, 64.35 | 61.03, 61.13 | 69.46, 72.47 | 46.20, 45.31 | 57.18, 55.28 | 33.43, 41.77 | 29.76, 35.68 | 34.62, 38.11 | 42.64, 43.16 | 41.79, 42.35 | 43.51, 44.40 | 44.77, 46.71     |
| UnivFD    | CVPR2023  | 85.38, 98.27 | 56.84, 84.04 | 56.41, 83.61 | 58.17, 86.24 | 63.24, 89.49 | 55.04, 79.00 | 56.46, 82.70 | 52.98, 75.47 | 54.49, 79.40 | 65.86, 91.51 | 75.85, 94.11 | 65.42, 90.99 | 61.80, 85.75 | 64.60, 89.49 | 56.15, 79.81 | 53.90, 75.57 | **61.80, 85.75** |
| LGrad     | CVPR2023  | 34.77, 35.81 | 31.09, 32.22 | 31.09, 32.20 | 31.66, 33.39 | 31.57, 32.42 | 31.08, 31.76 | 31.18, 32.03 | 31.06, 31.60 | 31.22, 32.34 | 31.28, 32.45 | 31.23, 32.53 | 31.11, 32.28 | 31.77, 33.43 | 55.07, 55.53 | 52.06, 52.97 | 31.28, 32.45 | 37.93, 37.36     |
| NPR       | CVPR2024  | 31.23, 32.27 | 32.67, 33.66 | 32.65, 33.68 | 35.19, 34.68 | 31.53, 32.36 | 32.10, 33.88 | 32.17, 33.47 | 32.92, 32.87 | 33.55, 33.66 | 30.86, 32.51 | 30.63, 32.16 | 30.69, 32.10 | 35.40, 34.42 | 71.07, 74.34 | 70.55, 72.29 | 68.63, 68.83 | 39.49, 40.45     |
| FreqNet   | AAAI2024  | 42.31, 37.50 | 41.35, 31.77 | 41.35, 31.76 | 41.03, 32.37 | 41.38, 34.23 | 41.46, 34.43 | 41.35, 32.06 | 41.35, 32.37 | 41.36, 32.23 | 41.37, 34.11 | 41.35, 31.77 | 41.37, 34.48 | 41.38, 35.51 | 57.31, 62.32 | 51.03, 53.17 | 56.41, 60.88 | 43.97, 38.30     |
| FatFormer | CVPR2024  | 98.60, 99.89 | 48.54, 33.28 | 48.55, 33.14 | 48.57, 32.94 | 48.55, 33.03 | 48.61, 38.36 | 48.59, 32.51 | 48.54, 32.10 | 48.63, 33.75 | 50.09, 40.36 | 61.09, 72.05 | 50.11, 42.39 | 54.17, 62.27 | 49.91, 38.81 | 59.56, 71.86 | 64.45, 78.27 | 51.95, 46.49     |
| SSP       | arXiv2024 | 51.73, 54.24 | 50.47, 55.16 | 50.51, 57.33 | 49.96, 59.96 | 49.93, 68.41 | 49.93, 68.41 | 49.85, 56.60 | 49.91, 58.70 | 50.67, 53.30 | 49.79, 53.53 | 50.09, 55.04 | 50.16, 54.18 | 50.67, 53.07 | 98.64, 59.61 | 84.92, 63.10 | 82.43, 61.57 | 57.47, 53.07     |
| C2L-CLIP  | arXiv2024 | 83.02, 98.11 | 51.96, 55.20 | 51.94, 54.42 | 52.92, 57.49 | 51.94, 55.61 | 64.60, 90.62 | 51.72, 60.30 | 50.62, 45.95 | 52.03, 59.65 | 66.05, 82.45 | 56.86, 68.13 | 54.69, 69.18 | 77.77, 91.26 | 67.24, 89.33 | 57.14, 77.44 | 56.72, 76.50 | 59.20, 70.73     |
| SAFE      | arXiv2024 | 50.28, 52.93 | 50.05, 46.75 | 50.00, 46.26 | 49.98, 42.82 | 49.92, 47.09 | 50.14, 50.33 | 49.96, 40.17 | 49.95, 49.77 | 50.13, 50.74 | 49.95, 49.06 | 49.94, 38.73 | 50.00, 43.74 | 54.74, 64.28 | 98.18, 99.91 | 98.47, 99.96 | 97.26, 99.87 | 59.31, 57.65     |

DRCT-2M looks like a robustness dataset other than an AIGC Detection dataset. The JPEG format of the real images can let many detection methods disabled.
