# KPS Loss: Key Point Sensitive Loss for Long-tailed Visual Recognition
This is the source code for our TPAMI paper: Key Point Sensitive Loss for Long-tailed Visual Recognition.  
This version is a demo of how to use KPS loss. The version that supports more datasets is in the works and is coming soon.

## CIFAR10
```bash
$ python cifar_train_backbone.py --arch resnet32 /
                                 --dataset cifar10 --data_path './dataset/data_img'/
                                 --loss_type 'KPS' --train_rule 'GA'/
                                 --imb_factor 0.01/ 
                                 --batch_size 64 --learning_rate 0.1 
```

## To do list:
- [x] Support Cifar10/100-LT dataset
- [ ] Support imageNet-LT
- [ ] Support iNaturalist2018
- [ ] More loss functions
- [ ] Separate configuration files for easier execution
- [ ] Some other minor performance improvements


## Citation
```
@article{Li2022Long,
  author    = {Mengke Li, Yiu{-}ming Cheung, Zhikai Hu},
  title     = {Key Point Sensitive Loss for Long-tailed Visual Recognition},
  journal   = {{IEEE} Transactions on Pattern Analysis and Machine Intelligence},
  volume    = {45},
  number    = {4},
  pages     = {4812 - 4825},
  publisher = {IEEE},
  year      = {2023},
  doi       = {10.1109/TPAMI.2022.3196044},
}
```

### You May Find Our Additional Works of Interest

* [CVPR'22] Long-tailed visual recognition via Gaussian clouded logit adjustment [[paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Li_Long-Tailed_Visual_Recognition_via_Gaussian_Clouded_Logit_Adjustment_CVPR_2022_paper.pdf)] [[code](https://github.com/Keke921/GCLLoss)]

* [CVPR'23] Long-Tailed Visual Recognition via Self-heterogeneous Integration with Knowledge Excavation [[paper](https://arxiv.org/pdf/2304.01279)] [[code](https://github.com/jinyan-06/SHIKE)]

* [AAAI'24] Feature Fusion from Head to Tail for Long-Tailed Visual Recognition [[paper](https://arxiv.org/pdf/2306.06963)] [[code](https://github.com/Keke921/H2T)]

* [NeurIPS'24] Improving Visual Prompt Tuning by Gaussian Neighborhood Minimization for Long-Tailed Visual Recognition [[paper](https://arxiv.org/pdf/2410.21042)] [[code](https://github.com/Keke921/GNM-PT)]

* [TAI'24] Adjusting logit in Gaussian form for long-tailed visual recognition [[paper](https://arxiv.org/pdf/2305.10648)] [[code](https://github.com/Keke921/GCLLoss)]



## Other Resources of long-tailed visual recognition

* [Awesome-LongTailed-Learning](https://github.com/Vanint/Awesome-LongTailed-Learning)

* [Awesome-of-Long-Tailed-Recognition](https://github.com/zwzhang121/Awesome-of-Long-Tailed-Recognition)

* [Long-Tailed-Classification-Leaderboard](https://github.com/yanyanSann/Long-Tailed-Classification-Leaderboard)

* [BagofTricks-LT](https://github.com/zhangyongshun/BagofTricks-LT)

## Connection
If you have any questions, please send the email to Mengke Li at: csmkli@comp.hkbu.edu.hk.

