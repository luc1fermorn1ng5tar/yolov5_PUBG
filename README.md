#### 功能
该项目可在游戏中识别到人物后进行自动瞄准
#### 缺陷
1. 抓取画面帧数的效率太低以至于等识别到人早死了，有人通过C++重写yolo识别可以达到每秒一百多帧
2. 本项目未写鼠标的平滑过渡，以至于识别到人后画面抖动厉害，这样yolo识别更跟不上画面抖动了
#### 更新
更新应该是没有了，因本人不再从事神经网络方面的工作开发，也对此不感兴趣

#### 设备需求
一定要使用罗技的鼠标，因为驱动用的是罗技的

#### 训练
yolo的训练本人当时使用的是笔记本的显卡型号为1070，一共训练了5小时，训练集3000张左右，素材来源于各个直播平台，然后用某些工具按帧自动切分后手动进行标签
