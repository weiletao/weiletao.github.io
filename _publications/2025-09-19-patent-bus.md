---
title: "一种基于神经网络的乳腺超声图像分割方法"
collection: publications
category: patents
permalink: /publication/2025-09-19-patent-bus
excerpt: '本发明公开了一种基于神经网络的乳腺超声图像分割方法，属于图像处理技术领域，包括以下步骤：S1、采集乳腺超声图像，利用卷积层对乳腺超声图像依次进行卷积处理和展平处理；S2、进行特征提取，得到原始特征图；S3、进行重塑处理和扁平化处理，得到展平特征图；S4、将展平特征图输入至卷积特征提取模块中，得到低层特征图；S5、将低层特征图输入至卷积注意力模块中，得到加权特征图；S6、将原始特征图和加权特征图输入至交叉注意力模块中，得到最终特征图；S7、完成乳腺超声图像分割。本发明利用管道注意力与空间注意力的结合降低卷积低级特征图中的噪声干扰，避免为深层网络引入过多噪声，缓解了噪声对分割结果的影响。'
date: 2025-09-19
venue: null
paperurl: 'https://weiletao.github.io/files/一种基于神经网络的乳腺超声图像分割方法.pdf'
bibtexurl: 'https://weiletao.github.io/files/wei2025breast_ultrasound_segmentation.bib'
citation: '韦乐涛, 范嘉豪, 张帅, 余星燃, 王劲东. 一种基于神经网络的乳腺超声图像分割方法:CN202510126909.X[P]. 2025-09-19.'
---
The present invention discloses a neural network-based breast ultrasound image segmentation method, belonging to the technical field of image processing. The method comprises the following steps:

S1. Acquiring breast ultrasound images, and sequentially performing convolution processing and flattening processing on the breast ultrasound images using convolutional layers;

S2. Performing feature extraction to obtain original feature maps;

S3. Performing reshaping and flattening operations to obtain flattened feature maps;

S4. Inputting the flattened feature maps into a convolutional feature extraction module to obtain low-level feature maps;

S5. Inputting the low-level feature maps into a convolutional attention module to obtain weighted feature maps;

S6. Inputting the original feature maps and the weighted feature maps into a cross-attention module to obtain final feature maps;

S7. Completing the breast ultrasound image segmentation.

The invention reduces noise interference in low-level convolutional feature maps by combining channel attention and spatial attention, thereby avoiding the introduction of excessive noise into deep networks and alleviating the impact of noise on segmentation results.

