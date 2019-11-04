# Show-Attend-and-Tell-Neural-Image-Caption-Generation-with-Visual-Attention
Working repository for term project of NNFL

# Abstract: 
Inspired by recent work in machine translation and object detection, we introduce an attention based model that automatically learns to describe the content of images. We describe how we can train this model in a deterministic manner using standard backpropagation techniques and stochastically by maximizing a variational lower bound. We also show through visualization how the model is able to automatically learn to fix its gaze on salient objects while generating the corresponding words in the output sequence. We validate the use of attention with state-of-the-art performance on three benchmark datasets: Flickr8k, Flickr30k and MS COCO.

# Paper Link: 
https://arxiv.org/abs/1502.03044

# Paper ID: 
64

# Guidelines:

1. Implement the full model architecture as defined in section 3 of the paper. (edited)

2. Implement the attention mechanism as described in section 3, you can skip the attention methods described in section 4.

3. Use Flickr 8k dataset or Caltech Bird dataset (http://www.vision.caltech.edu/visipedia/CUB-200-2011.html) instead of coco since these are much smaller data sets and it will be easier to train on them.

4. For sanity check first try to train your model on 50 or 100 images only and see the if the model is able to overfit on those images. Report the results you see. (edited)

5. For CNN encoder try multiple pretrained imagenet models like VGGNet, InceptionNet, ResNet, MobileNet etc and compare the results (Use at least 2 different networks). We recommend using MobileNet, NasnetMobile if you do not have good computing power.

6. Train the model both with and without attention and compare the results.

# Reference Codes- 
1. https://github.com/sgrvinod/a-PyTorch-Tutorial-to-Image-Captioning
2. https://github.com/parksunwoo/show_attend_and_tell_pytorch
3. https://github.com/AaronCCWong/Show-Attend-and-Tell
