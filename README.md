# Five-in-a-row
 JavaScript写的五子棋游戏，分单机人人对战->单机人机对战->联网人人对战三个版本
 ***
 2018.12.13更新：提交了单机人人对战的版本

2018.12.14更新：
1. 更改了单机人人对战版本的文件名称
2. 增加了单机人机对战版本文件
3. 将单机人人对战版本中开状态数组过大的问题解决，新的数组开法写在了单机人机对战版本中
4. 人机对战单机版，已添加部分功能，AI可进攻，但尚不会防守

2018.12.14更新：
人机对战单机版，AI可根据下一点的黑白权值选择进攻或者防守。
经测试，多数情况下的AI落子是合理的，但是对于活三/冲四的选择尚不佳（面对活三和冲四或者死四同时存在的情况，还是会选择防守四而不是防守活三，这不正确）
