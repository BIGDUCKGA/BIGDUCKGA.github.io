---
title: Surface Anomaly Detection 
description: Surface defect detection and identification of complex manufacturing products based on 3D point cloud data.
subtype: surface anomaly detection 
permalink: subteam/surface-anomaly-detection.html
image:
    feature: research/anomaly/points_structure.jpg
    size: 60%
excerpt_separator: <!-- More -->
---

Our goal is to catalyze tangible and substantial improvements in robot capabilities, especially in human–robot scenarios, with research at the confluence of learning, modeling, and robotics.
We accomplish this from two perspectives:

 * In the first, we leverage recent advances in learning and modeling to develop sophisticated, accessible, and generalizable robot technologies.
 Our focus here is primarily directed toward robots that operate in human environments. The ability of robots to interact or even cooperate with humans are considerations that are often neglected in the learning and modeling communities.
 * Complementarily, we draw upon our expertise in robotics and human–robot interaction to inform foundational research in artificial intelligence---particularly in natural language processing and reinforcement learning.
 Our experience with real-world robotic systems allows us to underpin our research with strong empirical motivations, an approach that is conspicuously scant in much of the existing literature.

<!-- More -->

# Contents
{:.no_toc}

* This line will be replaced by the ToC, excluding the "Contents" header
{:toc}

# 1. Projects

## 1.1. Anomaly detection for fabricated artifact by using unstructured 3D point cloud data

**Students:** Chengyu Tao

**_Publications:_**
 - Tao, Chengyu, Juan Du, and Tzyy-Shuh Chang. "Anomaly detection for fabricated artifact by using unstructured 3D point cloud data." IISE Transactions 55.11 (2023): 1174-1186.

{% include image.html url="research/anomaly/points_structure.jpg" max-width="40%" description="Illustration of (a) structured and (b) unstructured 3D point cloud data." %}

3D point cloud data has been widely used in surface quality inspection to measure fabricated artifacts, allowing the high density and precision of measurements and providing quantitative 3D geometric characteristics for anomalies. Unlike structured 3D point cloud data, unstructured 3D point cloud data can capture the surface geometry completely. However, anomaly detection by using unstructured 3D point cloud data is more challenging, due to the nonexistence of global coordinate ordering and the difficulty of mathematically modeling anomalies and discriminating outliers. To deal with these challenges, this article formulates the anomaly detection problem into a probabilistic framework. By categorizing points into three types, i.e., reference surface point, anomaly point, and outlier point, a novel Bayesian network is proposed to model the unstructured 3D point cloud data. The variational expectation-maximization algorithm is used to estimate parameters and make inference on the unknown types of points. Both simulation and real case studies demonstrate the accuracy and robustness of the proposed method.


## 1.2. Sparse learning with graph representation for anomaly detection by using unstructured 3D point cloud data 

**Students:** Chengyu Tao

**_Publications:_**
 - Tao, Chengyu, and Juan Du. "PointSGRADE: Sparse learning with graph representation for anomaly detection by using unstructured 3D point cloud data." IISE Transactions (2023): 1-14.

{% include image.html url="research/anomaly/patato_mvtec.jpg" max-width="40%" description="A real-world point cloud sample from the MVTec 3D-AD dataset with hole anomaly." %}

Surface anomaly detection by using 3D point cloud data has recently received significant attention. To completely measure the common free-form surfaces without loss of details, advanced 3D scanning technologies, such as 3D laser scanners, can be applied and will produce an unstructured point cloud. However, this irregular data structure poses challenges to anomaly detection, in that the existing methods based on regular data, e.g., 2D image, cannot be directly applied. This article proposes a sparse learning framework with a graph representation of the unstructured point cloud for anomaly detection (PointSGRADE). Specifically, the free-form surface is assumed to be smooth. Then, the associated point cloud can be represented as a graph. Subsequently, considering the sparse anomalies, we propose a sparse learning framework and formulate the anomaly detection problem as a penalized optimization problem, which is further solved by a computationally efficient majorization-minimization framework. Case studies demonstrate the accuracy and robustness of the proposed method. This article proposes a novel methodology for sparse anomaly detection on smooth free-form surfaces represented by unstructured point cloud, which is critical for quality inspection in manufacturing and other application areas.

