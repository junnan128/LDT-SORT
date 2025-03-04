# LDT-SORT
Project Overview📝 
===
`LDT-SORT` is a multi-object tracking framework that combines the `FlexDet` detector with confidence state tracking, designed to address challenges such as dense crowds, occlusion, and target similarity. It enhances the accuracy and efficiency of pedestrian multi-object tracking by integrating state-of-the-art convolutional models and similarity metrics.The code for `LDT-SORT` will be made publicly available once our paper is accepted.<br>

Highlights 🚀
==
* YOLOX support
* Linear Deformable Convolution
* high-resolution detection layer
* Confidence augmentation

Visualization results on MOT challenge test set📊
==


https://github.com/user-attachments/assets/04a10b88-b495-43bd-8c95-10e220c76322




https://github.com/user-attachments/assets/c1b86546-d6cc-41f5-b464-7fcbce4f65ec

Tracking performance
==
### Results on MOT17 challenge test set
| Tracker  | MOTA  | IDF1  | HOTA  |
|:---------:|:---------:|:---------:|:---------:|
|  LDT-SORT |  80.2   |  81.4   |  65.2   |  

Citation 🔍
==
For more details on the original dataset, refer to the paper:<br>
```markdown
@article{Milan_Leal-Taixé_Reid_Roth_Schindler_2016,
  title={MOT17: A Benchmark for Multi-Object Tracking},
  journal={Cornell University - arXiv,Cornell University - arXiv},
  author={Milan, Anton and Leal-Taixé, Laura and Reid, Ian and Roth, Stefan and Schindler, Konrad},
  year={2016},  month={Mar},  language={en-US}
}
