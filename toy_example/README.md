## Test Environment
- NVIDIA Geforce RTX 3060 12GB
- CUDA version 12.2
- nvcc version 10.1.243
- torch==1.13.1
- triton==2.1.0
- trident==0.1.1

## Test Results
| Code  | PyTorch  | Trident |
| :---: | :------: | :-----: |
| 1_linear | 37.1 sec | 101.6 sec |
| 2_linear_gelu | 46.2 sec | 176.2 sec |
| 3_train_beast_cancer | 9.6 sec | 420.6 sec (first) -> 68.1 sec (second) |


## Example Description
