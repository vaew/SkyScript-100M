<h1 align="center"><img src="logo.png" width="7%">SkyScript-100M: 1,000,000,000 Pairs of Scripts and Shooting Scripts for Short Drama</h1>

<div align='center'>
    <a href='https://github.com/vaew' target='_blank'><strong>Jing Tang</strong></a><sup> 1</sup>&emsp;
  	<a href='https://www.icst.pku.edu.cn/netvideo/people/ss/240830.htm' target='_blank'><strong>Jiaquan Lu</strong></a><sup> 2</sup>&emsp;
    <a href='https://github.com/IndexFziQ' target='_blank'><strong>Yuqiang Xie</strong></a><sup> 2†</sup>&emsp;
    <a href='https://scholar.google.com/citations?user=tp2cs2IAAAAJ&hl=zh-CN' target='_blank'><strong>Zeyu Gong</strong></a><sup> 1†</sup>&emsp;
    <a href='https://scholar.google.com.tw/citations?user=RvAuMk0AAAAJ&hl=zh-CN' target='_blank'><strong>Xiang Wen</strong></a><sup> 2</sup>&emsp;
</div>

<div align='center'>
    <strong>Jiayi Zhang</strong><sup> 2</sup>&emsp;
    <strong>Yalong Guo</strong><sup> 2</sup>&emsp;
    <strong>Guibin Chen</strong><sup> 2</sup>&emsp;
  	<strong> Jiangping Yang</strong><sup> 2</sup>&emsp;
</div>

<div align='center'>
    <sup>1 </sup><a href='https://english.hust.edu.cn/' target='_blank'>Huazhong University of Science and Technology</a>&emsp; 
    <sup>2 </sup><a href='https://github.com/SkyworkAI' target='_blank'>SkyWork AI</a>&emsp; 
</div>
<div align='center'>
    <small><sup>†</sup> Corresponding author</small>
</div>

<p align="center">
  <img src="all.pdf" alt="showcase">
</p>

## Introduction 📖

Generating high-quality shooting scripts containing information such as scene and shot language is essential for short drama script generation. We collect 6,660 popular short drama episodes from the Internet, each with an average of 100 short episodes, and the total number of short episodes is about 80,000, with a total duration of about 2,000 hours and totaling 10 terabytes (TB). We perform keyframe extraction and annotation on each episode to obtain about 10,000,000 shooting scripts. We perform 100 script restorations on the extracted shooting scripts based on our self-developed large short drama generation model SkyReels. This leads to a dataset containing 1,000,000,000 pairs of scripts and shooting scripts for short dramas, called SkyScript-100M. We compare SkyScript-100M with the existing dataset in detail and demonstrate some deeper insights that can be achieved based on SkyScript-100M. Based on SkyScript-100M, researchers can achieve several deeper and more far-reaching script optimization goals, which may drive a paradigm shift in the entire field of text-to-video and significantly advance the field of short drama video generation

## Acknowledgements 💐

We would like to thank the contributors of [GroundingDINO](https://github.com/IDEA-Research/GroundingDINO), [DeepFace](https://github.com/serengil/deepface), [AlphaPose](https://github.com/MVIG-SJTU/AlphaPose) repositories, for their open research and contributions.

## Citation 💖

If you find SkyScript-100M useful for your research, welcome to 🌟 this repo and cite our work using the following BibTeX:

```bibtex
@misc{tang2024skyscript100m,
      title={SkyScript-100M: 1,000,000,000 Pairs of Scripts and Shooting Scripts for Short Drama}, 
      author={Jing Tang, Quanlu Jia, Yuqiang Xie, Zeyu Gong, Xiang Wen, Jiayi Zhang, Yalong Guo, Guibin Chen, Jiangping Yang},
      year={2024},
      eprint={2408.xxxxxx},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```

## Contact 📧

**Jing Tang (唐晶): j_tang@hust.edu.cn**
