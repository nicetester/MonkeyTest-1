2013-09-08 v0.8 What's new:
==============================
1.新增log分析功能，可以自动统计Crash数量。
2.更新adb检测方式，使用adb get-serialno检查设备是否存在，并返回设备号。
3.更新测试结果输出保存路径，方便区分每次测试结果，注意Report不在此路径下。
4.将log分析和adb检查两个功能封装成模块，方便调试和调用。

2013-08-13 v0.7 What's new:
==============================
1.加入logging模块，所有输出都以Log形式，方便查看日志


2013-08-08 v0.6 What's new:
==============================
1. 更改默认的测试结果保存路径
2. 增加结果输出到文件
3. 增加设备连接检查
4. 修改部分注释
5. 优化条件判断
6. 将测试完成的结果输出封装成函数，方便多次调用

2013-07-09 What's new:
==============================
优化代码：使用a + = 1形式代替a = a + 1形式，提高运行速度

MonkeyTest
==========
Android Monkey test.