Q1：如何运行？
可以用java开发工具运行，或直接运行jar包即可体验游戏。
Q2：不喜欢游戏界面可否更换皮肤？
定位到src/res/layout文件夹下的main_layout.fxml布局文件。
找到文件中的mainPane的AnchorPane标签。将mainPane的stylesheets属性，从“@../css/skin2.css”修改为“@../css/skin1.css”
运行项目工程。即可体验星空皮肤。
Q3：关卡的数量是否是一定的（是否有最后一关）？
只要用户消除适当，得分足够，是可以一直玩下去的。本游戏不存在最后一关，一切取决于用户。
Q4：是否有额外奖励？如有，额外奖励分数是如何计算的？
本游戏中只有当剩余泡泡糖的数量小于等于10的时候开始有剩余奖励，剩余越少结余奖励分数就越高。

