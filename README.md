#### 功能
该项目可在游戏中识别到人物后进行自动瞄准
#### 缺陷
1. 抓取画面帧数的效率太低以至于等识别到人早死了，有人通过C++重写yolo识别可以达到每秒一百多帧
2. 本项目未写鼠标的平滑过渡，以至于识别到人后画面抖动厉害，这样yolo识别更跟不上画面抖动了
