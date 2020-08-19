# Multispectral Pedestrian Detection
In this repository we provide the detections that we used to generate our plots for the papers "Fully Convolutional Region Proposal Networks for Multispectral Person Detection" by König et al., IEEE CVPR Workshops 2017, and "Anchor-free Small-scale Multispectral
Pedestrian Detection" by Wolpert et al., BMVC 2020.

Here are the direct links to the papers:\
[König et al. CVPRW 2017](https://openaccess.thecvf.com/content_cvpr_2017_workshops/w3/html/Konig_Fully_Convolutional_Region_CVPR_2017_paper.html) \
[Wolpert et al. BMVC 2020](https://bmvc2020.github.io/) (link will be added soon)

All detections were generated on the KAIST Multispectral Pedestrian Benchmark test subset. The detections of our Fusion RPN+BF approach were calculated for the "Reasonable" test subset only and can be found as Matlab-file in the folder "CVPRW2017". The detections of our Fusion CSPNet approach were calculated for the "Reasonable" and the "All" test subset and can be found as txt-files (blank separated values) in the folder "BMVC2020".

## Cite us
If you use the detections or the findings of our paper, then please cite us:

@InProceedings{WolpertBMVC2020,
Title = {{Anchor-free Small-scale Multispectral Pedestrian Detection}},
Author = {Alexander Wolpert and Michael Teutsch and {M. Saquib} Sarfraz and Rainer Stiefelhagen},
Booktitle = {British Machine Vision Conference (BMVC)},
Year = {2020}
}

@InProceedings{KoenigCVPRW2017,
Title = {{Fully Convolutional Region Proposal Networks for Multispectral Person Detection}},
Author = {Daniel K{\\"o}nig and Michael Adam and Christian Jarvers and Georg Layher and Heiko Neumann and Michael Teutsch},
Booktitle = {IEEE CVPR Workshops},
Year = {2017}
}