# FireNet-LightWeight-Network-for-Fire-Detection

更新如下 2021/07/01：

- 增加了单张图片推理测试；

- 增加了 keras 转成 tflite 模型（非量化）

- 增加了 keras 转成 tflite 模型（量化）
  - 动态量化
  - float16 量化
  - int 量化

---

原 Readme.md ：

> A Specialized Lightweight Fire & Smoke Detection Model for Real-Time IoT Applications
>
> >(Preprint of the research paper on this work is available at https://arxiv.org/abs/1905.11922v2. Please consider citing if you happen to use the codes or dataset.

### Citation
```
@article{jadon2019firenet,
  title={Firenet: A specialized lightweight fire \& smoke detection model for real-time iot applications},
  author={Jadon, Arpit and Omama, Mohd and Varshney, Akshay and Ansari, Mohammad Samar and Sharma, Rishabh},
  journal={arXiv preprint arXiv:1905.11922},
  year={2019}
}
```

In our paper we showed results on two datasets:
- A self created diverse dataset with images randomly sampled from our self-shot fire and non-fire
videos.
- Foggia's dataset (used for testing), which is available here (https://mivia.unisa.it/datasets/video-analysis-datasets/fire-detection-dataset/).

It needs to be mentioned that the data used for training is only our custom created dataset, and not Foggia's full dataset. Testing was performed on previously held-out samples from our dataset as well as on Foggia's dataset. 

The following is the link to our dataset used in the FireNet paper:
- https://drive.google.com/drive/folders/1HznoBFEd6yjaLFlSmkUGARwCUzzG4whq?usp=sharing
# -Cifar10-
