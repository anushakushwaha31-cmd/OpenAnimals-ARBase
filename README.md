## OpenAnimals-ARBase: Animal Re-Identification

Reproduction and evaluation of the ARBase approach for animal re-identification using the OpenAnimals framework during a research internship at IIT (BHU), Varanasi.

## Objectives
- Reproduce the animal re-identification pipeline.
- Evaluate performance across wildlife datasets.
- Compare experimental results with the original paper.

## Tech Stack
- Python, PyTorch, Deep Learning
- Computer Vision, CUDA
- OpenAnimals framework

## Datasets Evaluated
- HyenaID2022
- LeopardID2022
- SeaTurtleIDHeads
- WhaleSharkID

## Limitations
The reproduced results were lower than those reported in the original paper. Dataset splits, preprocessing, configuration differences, and training randomness are possible reasons that require further investigation.

## Conclusion
This project provided practical experience in deep learning, animal re-identification, model evaluation, and research reproducibility.

## References
- Hou et al. (2025), *OpenAnimals: Revisiting Person Re-Identification for Animals Towards Better Generalization*, ICCV.
- He et al. (2023), *FastReID: A PyTorch Toolbox for General Instance Re-Identification*, ACM Multimedia.
- Čermák et al. (2024), *WildlifeDatasets: An Open-Source Toolkit for Animal Re-Identification*, WACV.


**OpenAnimals** is a flexible repository that aims to help researchers get started on **Animal Re-Identificatoin** quickly. 
This repository is built upon [FastReID](https://github.com/JDAI-CV/fast-reid) and [WildlifeDatasets](https://github.com/WildlifeDatasets/wildlife-datasets).

## Installation

Please refer to [INSTALL.md](INSTALL.md).

## Usage

1. Please refer to [README.md](datasets/README.md) for preparing the datasets.
2. Please refer to [run_animals.sh](run_animals.sh) for training and validation.

## Citation

If you use OpenAnimals in your research, please use the following BibTeX entry for [FastReID](https://github.com/JDAI-CV/fast-reid) and [WildlifeDatasets](https://github.com/WildlifeDatasets/wildlife-datasets).

```BibTeX
@inproceedings{he2023fastreid,
  title={Fastreid: A pytorch toolbox for general instance re-identification},
  author={He, Lingxiao and Liao, Xingyu and Liu, Wu and Liu, Xinchen and Cheng, Peng and Mei, Tao},
  booktitle={Proceedings of the 31st ACM International Conference on Multimedia},
  pages={9664--9667},
  year={2023}
}

@inproceedings{vcermak2024wildlifedatasets,
  title={WildlifeDatasets: An open-source toolkit for animal re-identification},
  author={{\v{C}}erm{\'a}k, Vojt{\v{e}}ch and Picek, Lukas and Adam, Luk{\'a}{\v{s}} and Papafitsoros, Kostas},
  booktitle={Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision},
  pages={5953--5963},
  year={2024}
}

@inproceedings{hou2025openanimals,
  title={Openanimals: Revisiting person re-identification for animals towards better generalization},
  author={Hou, Saihui and Huang, Panjian and Wang, Zengbin and Liu, Yuan and Li, Zeyu and Zhang, Man and Huang, Yongzhen},
  booktitle={Proceedings of the IEEE/CVF International Conference on Computer Vision},
  pages={14369--14379},
  year={2025}
}
```
=======
# OpenAnimals-ARBase
Reproduction and evaluation of ARBase for animal re-identification using the OpenAnimals framework

