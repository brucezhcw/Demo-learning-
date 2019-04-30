# Demo-learning

控制motorman机器人实时跟随人体运动：

利用Kinect抓取人体骨骼点数据：肩关节、肘关节、腕关节
根据三个关节点的数据完成七自由度机械臂前四个自由度的逆运动学
根据open pose神经网络学习手部深度图像并提取指尖坐标信息
根据指尖坐标信息建立人体手臂末端姿态坐标系完成人机后三个自由度的映射
末端姿态坐标系如下图所示：

![hand.png](https://github.com/brucezhcw/Demo-learning/blob/master/hand.png)

最终完成机械臂实时跟随人臂的运动

