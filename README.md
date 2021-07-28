# Skeletal-GNN
Code for "Learning Skeletal Graph Neural Networks for Hard 3D Pose Estimation" ICCV'21

Various deep learning techniques have been proposed to solve the single-view 2D-to-3D pose estimation problem. While the average prediction accuracy has been improved
significantly over the years, the performance on hard poses with depth ambiguity, self-occlusion, and complex or rare poses is still far from satisfactory.
![Situation](img/situation.png)

In this work, we target these hard poses and present a novel skeletal GNN learning solution. To be specific, we propose a hop-aware hierarchical channel-squeezing fusion
layer to effectively extract relevant information from neighboring nodes while suppressing undesired noises in GNN learning. In addition, we propose a temporal-aware dynamic
graph construction procedure that is robust and effective for **3D pose estimation**. Last, we further apply the proposed technique on the **skeleton-based action recognition** task and also achieve state-of-the-art performance.

![framework](img/D-HCSF.png)


Code will be coming soon!
