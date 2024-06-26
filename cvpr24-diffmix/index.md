---
title: 'Enhance Image Classification via Inter-Class Image Mixup with Diffusion Model'

#所有作者的列表，假设作者San Zhang是我们组的则是sanzhang，如果不是则填San Zhang
authors:
  - zhicaiwang
  - Longhui Wei
  - Tan Wang
  - Heyu Chen
  - yanbinhao
  - xiangwang
  - xiangnanhe
  - Qi Tian
# 论文接受/发表日期
date: '2023-02-27T00:00:00Z'
publishDate: '2023-02-27T00:00:00Z'

# 如果有共一则接触下面两行的注释
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

# doi号
doi: ''


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# 发表在哪个会议/期刊上
publication: In *CVPR 2024*
# <font color='red'>**Best Paper Honorable Mention**</font>
# publication_short: In *SIGIR'23* <font color='red'>**Best Paper Honorable Mention**</font>

# 论文摘要
abstract: "Text-to-image (T2I) generative models have recently emerged as a powerful tool, enabling the creation of photo- realistic images and giving rise to a multitude of appli- cations. However, the effective integration of T2I mod- els into fundamental image classification tasks remains an open question. A prevalent strategy to bolster image clas- sification performance is through augmenting the training set with synthetic images generated by T2I models. In this study, we scrutinize the shortcomings of both current gener- ative and conventional data augmentation techniques. Our analysis reveals that these methods struggle to produce im- ages that are both faithful (in terms of foreground objects) and diverse (in terms of background contexts) for domain- specific concepts. To tackle this challenge, we introduce an innovative inter-class data augmentation method known as Diff-Mix,, which enriches the dataset by performing image translations between classes. Our empirical results demon- strate that Diff-Mix achieves a better balance between faith- fulness and diversity, leading to a marked improvement in performance across diverse image classification scenarios, including few-shot, conventional, and long-tail classifica- tions for domain-specific datasets."

featured: true

links:
  # - name: Custom Link
  #   url: http://example.org
# pdf链接
url_pdf: https://arxiv.org/abs/2403.19600
# 代码链接
url_code: 'https://github.com/Zhicaiwww/Diff-Mix'

# 以下视情况填写
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# 如果需要放图，请放在同一个目录下，名字叫`featured.jpg/png` 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

projects:
  - internal-project
---

Citation:
```
@misc{wang2024enhance,
      title={Enhance Image Classification via Inter-Class Image Mixup with Diffusion Model}, 
      author={Zhicai Wang and Longhui Wei and Tan Wang and Heyu Chen and Yanbin Hao and Xiang Wang and Xiangnan He and Qi Tian},
      year={2024},
      eprint={2403.19600},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```

