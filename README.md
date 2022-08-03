# KPS Loss: Key Point Sensitive Loss for Long-tailed Visual Recognition
This is the [source code](https://github.com/Keke921/KPSLoss) for our TPAMI paper: Key Point Sensitive Loss for Long-tailed Visual Recognition.  
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
  volume    = {},
  number    = {},
  pages     = {},
  publisher = {IEEE},
  year      = {2022},
  doi       = {DOI: 10.1109/TPAMI.2022.3196044},
}
```

## Other Resources of long-tailed visual recognition
[Awesome-LongTailed-Learning](https://github.com/Vanint/Awesome-LongTailed-Learning)

[Awesome-of-Long-Tailed-Recognition](https://github.com/zwzhang121/Awesome-of-Long-Tailed-Recognition)

[Long-Tailed-Classification-Leaderboard](https://github.com/yanyanSann/Long-Tailed-Classification-Leaderboard)

[BagofTricks-LT](https://github.com/zhangyongshun/BagofTricks-LT)

[GCL: Long-tailed Visual Recognition via Gaussian Clouded Logit Adjustment](https://github.com/Keke921/GCLLoss) 

## Connection
If you have any questions, please send the email to Mengke Li at: csmkli@comp.hkbu.edu.hk.

