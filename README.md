# 3119005387
软件工程第一次个人项目作业
## 开发日志
在网上查阅资料，发现大部分的思路
- 把文本变成字符串
- 然后进行分词操作
- 并计算词频
- 利用余弦相似性计算出两者的相似度

所以我打算先按照这样的思路去实现。
初步实现了大概的逻辑，但是还没有测试和做异常处理。



学习使用Jprofile 性能测试工具
安装idea jprofiler插件和安装window版



添加测试用例

最后的jar包在resource目录下

### 运行方法
java -jar main.jar [原文文件] [抄袭版论文的文件] [答案文件]

运行环境
jdk 11.0.2
windows环境下运行jar包请检查 
java -version和javac -version 的是否一样
