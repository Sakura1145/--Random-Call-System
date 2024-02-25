随机点名系统v0.1.1操作说明书

一、	说明
本系统为github开源项目，使用者可在https://github.com/Sakura1145/--Random-Call-System 下载最新版或提出改进意见。
本系统每次使用时需上传学生姓名，暂时仅支持双班级无缓存点名，后续将完善。

二、	操作指引

1、	导入学生姓名

方法一（不推荐）：
使用者可在界面中分班级输入姓名，但需要注意的是添加学生时应单次仅输入一个姓名，否则会导致系统将多个名字识别为单个学生的名字。注意：本方法暂不支持修改学生姓名，且本方法操作后需点击保存至Excel，否则将不会保存所填姓名！

方法二：
使用者可以将本地Excel文档中的姓名上传至系统，但需注意系统只能识别第一列单元格中靠左对齐的姓名，且第一列中只能保留学生姓名，不能添加其他内容，否则会将该内容识别为姓名。
进行多班级导入姓名时，仅需将文档的Sheet1与Sheet2分别更名为A班与B班，并删除Sheet3（后续会完善）后按上述格式导入即可。

2、	修改班名
需要修改班名的使用者可将下载的代码后缀改为.txt，然后将该文档中所有的A班、B班改为目标班名，再将后缀改为.html即可。
