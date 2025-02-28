<div align="center">

<h3 align="center">YOLOv10 - Document Layout Analysis</h3>
</div>

<p align="center">
  <a href="https://huggingface.co/spaces/omoured/YOLOv10-Document-Layout-Analysis">
    <img src="https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Models-blue"/>
  </a>
  &nbsp;
  <a href="https://colab.research.google.com/github/moured/YOLOv10-Document-Layout-Analysis/blob/main/demo.ipynb">
    <img src="https://colab.research.google.com/assets/colab-badge.svg"/>
  </a>
</p>

<!--
<p align="center">
  For further assistance or adaptation in your project, feel free to get in touch: <a href="mailto:moured.omar@gmail.com">moured.omar@gmail.com</a>.
</p>
-->

<h3 align="center">🚀 <b>Check Out Our Recent Trained Model:</b> <a href="https://github.com/moured/YOLOv11-Document-Layout-Analysis/">Yolov11</a>, is now available with live demo! 🎉</h3>




<!--
  <p align="center">
    Trained on DocLayNet dataset
    <br />
    <a href="https://huggingface.co/spaces/linhdo/document-layout-analysis">Live HuggingFace Demo</a>
    ·
    <a href="https://github.com/THU-MIG/yolov10">Visit YOLOv10</a>
    ·
    <a href="https://github.com/LynnHaDo/Document-Layout-Analysis/issues">Request Feature or Report Problem</a>
  </p>
</div>
-->

## Updates 🔥

I have trained YOLOv10 on the DocLayNet dataset for this project. Below is the results table. Feel free to use our fine-tuned models, and please remember to cite YOLOv10, DocLayNet, and our repository. If you find this repository useful, don't forget to give it a 🌟!

- **01/11/2024**: Yolov11 trained models with better performance - [https://github.com/moured/YOLOv11-Document-Layout-Analysis/](https://github.com/moured/YOLOv11-Document-Layout-Analysis/).
- **03/06/2024**: Uploaded Fine-tuned (check the table below).
- **02/06/2024**: 🤗 HuggingFace demo is live with YOLOv10-x fine-tuned weights.
  
<!-- ABOUT THE PROJECT -->
## About 📋

The models were fine-tuned using 4xA100 GPUs on the Doclaynet-base dataset, which consists of 69103 training images, 6480 validation images, and 4994 test images.

<p align="center">
  <img src="images/samples.gif" height="640"/>
</p>

## Results 📊
| Model   | mAP50 | mAP50-95 | Model Weights |
|---------|-------|----------|---------------|
| YOLOv11-x | 0.924 | 0.755 | [Repo](https://github.com/moured/YOLOv11-Document-Layout-Analysis) |
| YOLOv10-x | 0.924 | 0.740 | [Download](https://github.com/moured/YOLOv10-Document-Layout-Analysis/releases/download/doclaynet_weights/yolov10x_best.pt) |
| YOLOv10-b | 0.922 | 0.732 | [Download](https://github.com/moured/YOLOv10-Document-Layout-Analysis/releases/download/doclaynet_weights/yolov10b_best.pt) |
| YOLOv10-l | 0.921 | 0.732 | [Download](https://github.com/moured/YOLOv10-Document-Layout-Analysis/releases/download/doclaynet_weights/yolov10l_best.pt) | 
| YOLOv10-m | 0.917 | 0.737 | [Download](https://github.com/moured/YOLOv10-Document-Layout-Analysis/releases/download/doclaynet_weights/yolov10m_best.pt) | 
| YOLOv10-s | 0.905 | 0.713 | [Download](https://github.com/moured/YOLOv10-Document-Layout-Analysis/releases/download/doclaynet_weights/yolov10s_best.pt) | 
| YOLOv10-n | 0.892 | 0.685 | [Download](https://github.com/moured/YOLOv10-Document-Layout-Analysis/releases/download/doclaynet_weights/yolov10n_best.pt) |

### Installation 💻
```
conda create -n yolov10 python=3.9
conda activate yolov10
git clone https://github.com/THU-MIG/yolov10.git
cd yolov10
pip install -r requirements.txt
pip install -e .
```

## References 📝

1. YOLOv10
```
BibTeX
@article{wang2024yolov10,
  title={YOLOv10: Real-Time End-to-End Object Detection},
  author={Wang, Ao and Chen, Hui and Liu, Lihao and Chen, Kai and Lin, Zijia and Han, Jungong and Ding, Guiguang},
  journal={arXiv preprint arXiv:2405.14458},
  year={2024}
}
```

   
2. DocLayNet
```
@article{doclaynet2022,
  title = {DocLayNet: A Large Human-Annotated Dataset for Document-Layout Analysis},  
  doi = {10.1145/3534678.353904},
  url = {https://arxiv.org/abs/2206.01062},
  author = {Pfitzmann, Birgit and Auer, Christoph and Dolfi, Michele and Nassar, Ahmed S and Staar, Peter W J},
  year = {2022}
}
```

## Contact
LinkedIn: [https://www.linkedin.com/in/omar-moured/](https://www.linkedin.com/in/omar-moured/)
