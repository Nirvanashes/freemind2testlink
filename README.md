# freemind2testlink

#xml中testlink相关名词解释:
testsuite：用例目录
testcase：用例标题
summary：摘要（默认与用例标题相同）
preconditions：前提（对应思维导图中的备注）
step_number：步骤次序
actions：用例步骤
expectedresults：预期结果


项目源码修改自：https://github.com/pengchenglin/freemind2testlink.git
针对自己使用习惯做了修改
项目打包：
1、生成exe文件：
使用Pyinstaller进行打包，pip install pyinstaller安装好之后，到该文件夹下，
执行pyinstaller -F Freemind2Testlink.py，
在生成的dist文件夹下就会生成一个独立的exe文件了。
2、生成macOS执行文件：
可参考：https://zhuanlan.zhihu.com/p/454550005
