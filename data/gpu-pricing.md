| Machine Config               | Provider | NVIDIA GPU Name | vCPUs | GPU Memory (GB) | RAM (GB) | Instance Storage (GB) | Price(USD) | INR per Hour (INR 85/USD) | INR PER HOUR PER GPU RAM |
| ---------------------------- | -------- | --------------- | ----- | --------------- | -------- | --------------------- | ---------- | ------------------------- | ------------------------ |
| 1x NVIDIA A10                | Lambda   | A10             | 30    | 24              | 200 GiB  | 1.4 TiB SSD           | 0.75       | 64                        | 2.66                     |
| 1x NVIDIA A100 PCIe          | Lambda   | A100            | 30    | 40              | 200 GiB  | 512 GiB SSD           | 1.29       | 110                       | 2.74                     |
| 1x NVIDIA A100 SXM           | Lambda   | A100            | 30    | 40              | 200 GiB  | 512 GiB SSD           | 1.29       | 110                       | 2.74                     |
| 1x NVIDIA A6000              | Lambda   | A6000           | 14    | 48              | 100 GiB  | 200 GiB SSD           | 0.8        | 68                        | 1.42                     |
| 1x NVIDIA H100 PCIe          | Lambda   | H100            | 26    | 80              | 200 GiB  | 1 TiB SSD             | 2.49       | 212                       | 2.65                     |
| 1x NVIDIA Quadro RTX 6000    | Lambda   | QuadroRTX6000   | 14    | 24              | 46 GiB   | 512 GiB SSD           | 0.5        | 43                        | 1.77                     |
| 2x NVIDIA A100 PCIe          | Lambda   | A100            | 60    | 40              | 400 GiB  | 1 TiB SSD             | 2.58       | 110                       | 2.74                     |
| 2x NVIDIA A6000              | Lambda   | A6000           | 28    | 48              | 200 GiB  | 1 TiB SSD             | 1.6        | 68                        | 1.42                     |
| 4x NVIDIA A100 PCIe          | Lambda   | A100            | 120   | 40              | 800 GiB  | 1 TiB SSD             | 5.16       | 110                       | 2.74                     |
| 4x NVIDIA A6000              | Lambda   | A6000           | 56    | 48              | 400 GiB  | 1 TiB SSD             | 4          | 68                        | 1.42                     |
| 8x NVIDIA A100 SXM           | Lambda   | A100            | 124   | 40              | 1800 GiB | 6 TiB SSD             | 10.32      | 110                       | 2.74                     |
| 8x NVIDIA A100 SXM           | Lambda   | A100            | 240   | 80              | 1800 GiB | 20 TiB SSD            | 14.32      | 152                       | 1.90                     |
| 8x NVIDIA H100 SXM New Price | Lambda   | H100            | 208   | 80              | 1800 GiB | 26 TiB SSD            | 23.92      | 254                       | 3.18                     |
| 8x NVIDIA Tesla V100         | Lambda   | TeslaV100       | 92    | 16              | 448 GiB  | 5.9 TiB SSD           | 4.4        | 47                        | 2.92                     |
| A100-40GB-NVLINK-1x          | OLA      | A100            | 24    | 40              | 96       | 512                   | 1.24       | 105                       | 2.63                     |
| A100-40GB-NVLINK-2x          | OLA      | A100            | 48    | 80              | 192      | 512                   | 2.47       | 210                       | 2.63                     |
| A100-40GB-NVLINK-4x          | OLA      | A100            | 96    | 160             | 384      | 1024                  | 3.71       | 315                       | 1.97                     |
| A100-40GB-NVLINK-8x          | OLA      | A100            | 192   | 320             | 768      | 2048                  | 9.88       | 840                       | 2.63                     |
| A100-NVLINK-Mini             | OLA      | A100            | 1     | 16              | 20       | 60                    | 0.53       | 45                        | 2.81                     |
| A100-NVLINK-Nano             | OLA      | A100            | 1     | 16              | 10       | 60                    | 0.35       | 30                        | 1.88                     |
| A100-NVLINK-Standard-1x      | OLA      | A100            | 1     | 16              | 40       | 60                    | 1.24       | 105                       | 6.56                     |
| A100-NVLINK-Standard-2x      | OLA      | A100            | 2     | 16              | 80       | 125                   | 2.47       | 210                       | 13.13                    |
| A100-NVLINK-Standard-4x      | OLA      | A100            | 4     | 128             | 160      | 250                   | 4.94       | 420                       | 3.28                     |
| A100-NVLINK-Standard-8x      | OLA      | A100            | 8     | 128             | 320      | 1000                  | 9.88       | 840                       | 6.56                     |
| A100-NVLINK-Tiny             | OLA      | A100            | 1     | 16              | 5        | 30                    | 0.18       | 15                        | 0.94                     |
| g4ad.16xlarge                | AWS      | NoData          | 4     | 256             |          | 1 x 2400 NVMe SSD     | 3.468      | 295                       | 1.15                     |
| g4ad.2xlarge                 | AWS      | NoData          | 1     | 32              |          | 1 x 300 NVMe SSD      | 0.541      | 46                        | 1.44                     |
| g4ad.4xlarge                 | AWS      | NoData          | 1     | 64              |          | 1 x 600 NVMe SSD      | 0.867      | 74                        | 1.15                     |
| g4ad.8xlarge                 | AWS      | NoData          | 2     | 128             |          | 1 x 1200 NVMe SSD     | 1.734      | 147                       | 1.15                     |
| g4ad.xlarge                  | AWS      | NoData          | 1     | 16              |          | 1 x 150 NVMe SSD      | 0.379      | 32                        | 2.01                     |
| g4dn.12xlarge                | AWS      | NoData          | 4     | 192             |          | 1 x 900 NVMe SSD      | 3.912      | 333                       | 1.73                     |
| g4dn.16xlarge                | AWS      | NoData          | 1     | 256             |          | 1 x 900 NVMe SSD      | 4.352      | 370                       | 1.45                     |
| g4dn.2xlarge                 | AWS      | NoData          | 1     | 32              |          | 1 x 225 NVMe SSD      | 0.752      | 64                        | 2.00                     |
| g4dn.4xlarge                 | AWS      | NoData          | 1     | 64              |          | 1 x 225 NVMe SSD      | 1.204      | 102                       | 1.60                     |
| g4dn.8xlarge                 | AWS      | NoData          | 1     | 128             |          | 1 x 900 NVMe SSD      | 2.176      | 185                       | 1.45                     |
| g4dn.metal                   | AWS      | NoData          | 8     | 384             |          | 2 x 900 NVMe SSD      | 7.824      | 665                       | 1.73                     |
| g4dn.xlarge                  | AWS      | NoData          | 1     | 16              |          | 1 x 125 NVMe SSD      | 0.526      | 45                        | 2.79                     |
| H100-NVLINK-1x               | OLA      | H100            | 24    | 80              | 200      | 1024                  | 3.41       | 290                       | 3.63                     |
| H100-NVLINK-2x               | OLA      | H100            | 48    | 160             | 400      | 1024                  | 6.82       | 580                       | 3.63                     |
| H100-NVLINK-4x               | OLA      | H100            | 96    | 320             | 800      | 2048                  | 13.65      | 1160                      | 3.63                     |
| H100-NVLINK-Mini             | OLA      | H100            | 1     | 16              | 40       | 60                    | 1.46       | 124                       | 7.75                     |
| H100-NVLINK-Nano             | OLA      | H100            | 1     | 16              | 20       | 60                    | 0.98       | 83                        | 5.19                     |
| H100-NVLINK-Standard-1x      | OLA      | H100            | 1     | 16              | 80       | 125                   | 3.41       | 290                       | 18.13                    |
| H100-NVLINK-Standard-2x      | OLA      | H100            | 2     | 52              | 160      | 250                   | 6.82       | 580                       | 11.15                    |
| H100-NVLINK-Standard-4x      | OLA      | H100            | 4     | 104             | 320      | 1004                  | 13.65      | 1160                      | 11.15                    |
| H100-NVLINK-Standard-8x      | OLA      | H100            | 8     | 208             | 640      | 2008                  | 27.29      | 2320                      | 11.15                    |
| H100-NVLINK-Tiny             | OLA      | H100            | 1     | 16              | 10       | 60                    | 0.48       | 41                        | 2.56                     |
| NC12                         | Azure    | K80             | 12    | 24              | 112      | \-                    | 1.8        | 153                       | 6.38                     |
| NC12s v2                     | Azure    | P100            | 12    | 32              | 224      | \-                    | 4.14       | 352                       | 11.00                    |
| NC12s v3                     | Azure    | V100            | 12    | 32              | 224      | \-                    | 6.12       | 519                       | 16.22                    |
| NC16as T4 v3                 | Azure    | T4              | 16    | 64              | 110      | \-                    | 1.204      | 102                       | 1.60                     |
| NC24                         | Azure    | K80             | 24    | 48              | 224      | \-                    | 3.6        | 306                       | 6.38                     |
| NC24r                        | Azure    | K80             | 24    | 48              | 224      | \-                    | 3.96       | 337                       | 7.01                     |
| NC24rs v2                    | Azure    | P100            | 24    | 64              | 448      | \-                    | 9.108      | 774                       | 12.10                    |
| NC24rs v3                    | Azure    | V100            | 24    | 64              | 448      | \-                    | 13.46      | 1141                      | 17.83                    |
| NC24s v2                     | Azure    | P100            | 24    | 64              | 448      | \-                    | 8.28       | 704                       | 11.00                    |
| NC24s v3                     | Azure    | V100            | 24    | 64              | 448      | \-                    | 12.24      | 1039                      | 16.24                    |
| NC4as T4 v3                  | Azure    | T4              | 4     | 16              | 28       | \-                    | 0.526      | 45                        | 2.79                     |
| NC6                          | Azure    | K80             | 6     | 12              | 56       | \-                    | 0.9        | 77                        | 6.38                     |
| NC64as T4 v3                 | Azure    | T4              | 64    | 256             | 440      | \-                    | 4.352      | 370                       | 1.45                     |
| NC6s v2                      | Azure    | P100            | 6     | 16              | 112      | \-                    | 2.07       | 176                       | 11.00                    |
| NC6s v3                      | Azure    | V100            | 6     | 16              | 112      | \-                    | 3.06       | 260                       | 16.26                    |
| NC8as T4 v3                  | Azure    | T4              | 8     | 32              | 56       | \-                    | 0.752      | 64                        | 2.00                     |
| ND12s                        | Azure    | P40             | 12    | 16              | 224      | \-                    | 4.14       | 352                       | 21.99                    |
| ND24rs                       | Azure    | P40             | 24    | 32              | 448      | \-                    | 9.108      | 774                       | 24.19                    |
| ND24s                        | Azure    | P40             | 24    | 32              | 448      | \-                    | 8.28       | 704                       | 21.99                    |
| ND40rs v2                    | Azure    | V100            | 40    | 64              | 672      | \-                    | 22.032     | 1873                      | 29.26                    |
| ND6s                         | Azure    | P40             | 6     | 8               | 112      | \-                    | 2.07       | 176                       | 22.00                    |
| ND96asr A100 v4              | Azure    | A100            | 96    | 80              | 900      | \-                    | 27.197     | 2316                      | 28.95                    |
| NV12                         | Azure    | M60             | 12    | 32              | 112      | \-                    | 2.28       | 194                       | 6.06                     |
| NV12s v3                     | Azure    | M60             | 12    | 32              | 112      | \-                    | 1.14       | 97                        | 3.03                     |
| NV24                         | Azure    | M60             | 24    | 64              | 224      | \-                    | 4.56       | 388                       | 6.06                     |
| NV24s v3                     | Azure    | M60             | 24    | 64              | 224      | \-                    | 2.28       | 194                       | 3.03                     |
| NV48s v3                     | Azure    | M60             | 48    | 128             | 448      | \-                    | 4.56       | 388                       | 3.03                     |
| NV6                          | Azure    | M60             | 6     | 16              | 56       | \-                    | 1.14       | 97                        | 6.06                     |
