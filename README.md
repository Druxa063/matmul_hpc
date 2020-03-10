#How to execute

Before start the app please follow this [guide](https://docs.nvidia.com/cuda/cuda-installation-guide-microsoft-windows/index.html)

---
Note: you need to have compatible GPU, [list](https://developer.nvidia.com/cuda-gpus) of allowed GPUs
---

# Results

The results were tested on GeForce 840M.

| Matrix size   | CPU, ms       | GPU, ms|
| ------------- |:-------------:| -----: |
| 320x320       | 260           | 100.555|
| 640x640       | 3775          | 122.939|
| 1600x1600     | -----         | 150.549|