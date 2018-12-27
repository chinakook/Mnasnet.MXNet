# A MXNet/Gluon implementation of Mnasnet

This is a Gluon implementation of Mnasnet architecture as described in the paper [MnasNet: Platform-Aware Neural Architecture Search for Mobile](https://arxiv.org/pdf/1807.11626.pdf).

## Training
To train this model, you need first install the [gluon-cv](https://github.com/dmlc/gluon-cv) or download the repo beside as we do. Using ```train_imagenet.sh``` to train, you will get 0.73+ accuracy.

## Pretrained model
[A pretrained model](https://github.com/zeusees/Mnasnet-Pretrained-Model) is provided by [zuesees](https://github.com/zeusees). They've got 73.6% Top-1 score and 91.52% Top-5 score, nearly approaching official accuracy.

## TODO
After some tunes, I think you will get higher accuracy. I'm not free to do this now, so I hope someone could report to me when he/she get a better accuracy.
