# Cross-Attention for Improved Motion Correction in Brain PET

Zhuotong Cai, Tianyi Zeng, Eléonore V. Lieffrig, Jiazhen Zhang, Fuyao Chen, Takuya Toyonaga, Chenyu You, Jingmin Xin, Nanning Zheng, Yihuan Lu, James S. Duncan and John A. Onofrey

# Abstract
Head movement during long scan sessions degrades the quality of reconstruction in positron emission tomography (PET) and introduces artifacts, which limits clinical diagnosis and treatment. Recent deep learning-based motion correction work utilized raw PET list-mode data and hardware motion tracking (HMT) to learn head motion in a supervised manner. However, motion prediction results were not robust to testing subjects outside the training data domain. In this paper, we integrate a cross-attention mechanism into the supervised deep learning network to improve motion correction across test subjects. Specifically, cross-attention learns the spatial correspondence between the reference images and moving images to explicitly focus the model on the most correlative inherent information - the head region the motion correction. We validate our approach on brain PET data from two different scanners: HRRT without time of flight (ToF) and mCT with ToF. Compared with traditional and deep learning benchmarks, our network improved the performance of motion correction by 58% and 26% in translation and rotation, respectively, in multi-subject testing in HRRT studies. In mCT studies, our approach improved performance by 66% and 64% for translation and rotation, respectively. Our results demonstrate that cross-attention has the potential to improve the quality of brain PET image reconstruction without the dependence on HMT.

#Cite
@inproceedings{cai2023cross,
  title={Cross-Attention for Improved Motion Correction in Brain PET},
  author={Cai, Zhuotong and Zeng, Tianyi and Lieffrig, El{\'e}onore V and Zhang, Jiazhen and Chen, Fuyao and Toyonaga, Takuya and You, Chenyu and Xin, Jingmin and Zheng, Nanning and Lu, Yihuan and others},
  booktitle={International Workshop on Machine Learning in Clinical Neuroimaging},
  pages={34--45},
  year={2023},
  organization={Springer}
}
