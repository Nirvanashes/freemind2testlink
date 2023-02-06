# freemind2testlink

#用例编写方式
目录需要加上相关的图标： 旗帜 （对颜色无要求）【注，需要在每一级目录增加旗帜】
可直接获取xmind导出为freemind格式中已经插入的备注，也可获取到freemind中后续添加的备注；
有步骤的用例：各个步骤的描述及期望结果按父子节点编写
用例优先级需要加上相关的图标：1 2 3 --->高 中 低 (标注其他数字图标的 默认是中优先级)
#用例demo：
![image](https://user-images.githubusercontent.com/23491399/216909061-9f6419a1-be18-44d5-86d5-fb438f873cbb.png)


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
