# README

## 2021.12.12修改

- 修改了Armor类，加入储存灯条四角点的数组，并修改SLOVE类中设置二维坐标的函数，及绘画装甲板的函数,微小改动了部分上层类中使用到装甲部的成员函数。

- 修改了部分接受的通信数据，加入MODE ，COLOR ，MODE 分为打符和正常攻击，更改了时间接受逻辑，用3个uin8_t类型储存世时间ms，使用一个u8 接受包括弹道速度，MODE ，COLOR等数据，具体增加的数据参考Serial.h,解算的数据方法查看imageprocess.cpp.
