Caffe Implementation (v1) for 

# [Pyramid Dilated Deeper ConvLSTM for Video Salient Object Detection, ECCV, 2018](https://www.researchgate.net/publication/328116556_Pyramid_Dilated_Deeper_ConvLSTM_for_Video_Salient_Object_Detection_15th_European_Conference_Munich_Germany_September_8-14_2018_Proceedings_Part_XI)

By Hongmei Song and Wenguan Wang and Sanyuan Zhao and Jianbing Shen and Kin-Man Lam

========================================================================

Please install our modified caffe first. Download our model (https://drive.google.com/open?id=1vsGV31gfYA48j8usoRjTtfn-IpBosGFH) and put it in 'model' folder.

Then edit paths in 'test_davis.py'.

Finally, run 'test_davis.py'.

========================================================================

The saliency and segmentation results (on the test sets of DAVIS16 and FBMS) can also be found at https://drive.google.com/open?id=1oOeoDAkxInOL_lKvgaSlnjO_6OLhL2Ew

The IOU score of the FBMS-test set should be changed as: 72.3. 

========================================================================
If you find our method useful in your research,please consider citing the following papers:

1) H. Song, W. Wang, J. Shen, S. Zhao, and K. M. Lam, Pyramid Dilated Deeper ConvLSTM for Video Salient Object Detection, European Conference on Computer Vision, 2018

2) W. Wang, J. Shen, and L. Shao,Video salient object detection via fully convolutional networks,IEEE Trans. on Image Processing, 27(1):38-49, 2018

3) W. Wang, J. Shen, R. Yang, and F. Porikli, Saliency-aware video object segmentation,IEEE Trans. on Pattern Analysis and Machine Intelligence, 40(1):20-33, 2018

========================================================================
Other related projects:

[(CVPR19)](https://github.com/wenguanwang/AGS) Learning Unsupervised Video Object Segmentation through Visual Attention

[(CVPR19 Oral)](https://github.com/wenguanwang/DAVSOD) Shifting More Attention to Video Salient Object Detection

[(CVPR19)](https://github.com/carrierlxk/COSNet) See More, Know More: Unsupervised Video Object Segmentation With Co-Attention Siamese Networks

Any comments, please email:songhongmei@bit.edu.cn, wenguanwang.china@gmail.com
