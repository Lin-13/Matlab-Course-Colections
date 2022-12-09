# 介绍

该仓库为《工程测试技术基础》课程中的课程作业的Matlab代码实现。

代码可能存在部分Bug。

由于Matlab特性，该代码需使用Matlab打开。

如有代码整体复制等操作请注明出处。

## Ch1 函数生成器

fcn_gen

## Ch2 Media

media.mlapp 第一版，使用sound，功能较少。

media_player 第二版，用过更复杂的函数实现更复杂的功能。

## Ch3 Histogram & Corr

hist,波形数据直方图分析

wave_corr,波形自相关和互相关分析，支持两个通道波形函数生成和分析。

## Ch4 Filter & STFT

通过MATLAB实现均衡器和短视傅里叶变换的可视化。

## Ch5 IMU

通过串口读取并可视化传感器数据。

**传感器有一个IMU和一个超声波传感器。**

串口通讯文本如下：

'''

 acc: -0.501 -0.208 0.838 gyro: 0.0 0.0 0.0 angle: -13.892 30.146 153.732 mag: 272 -243 -242 dist: 2.41

'''
