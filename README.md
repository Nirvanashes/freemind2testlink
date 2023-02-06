# freemind2testlink
# 项目源码：
1. 修改自：https://github.com/pengchenglin/freemind2testlink.git ，针对自己的使用习惯做了部分修改

# 用例编写方式
1. 目录需要加上相关的图标： 旗帜 （对颜色无要求）【注，需要在每一级目录增加旗帜】；
2. 可直接获取xmind导出为freemind格式中已经插入的备注，也可获取到freemind中后续添加的备注；
3. 支持预期结果换行展示；
4. 有步骤的用例：各个步骤的描述及期望结果按父子节点编写；
5. 用例优先级需要加上相关的图标：1 2 3 --->高 中 低 (标注其他数字图标的 默认是中优先级)；

# 用例demo：
![image](https://user-images.githubusercontent.com/23491399/216909061-9f6419a1-be18-44d5-86d5-fb438f873cbb.png)

# xml中testlink相关名词解释:
1. testsuite：用例目录
2. testcase：用例标题
3. summary：摘要（默认与用例标题相同）
4. preconditions：前提（对应思维导图中的备注）
5. step_number：步骤次序
6. actions：用例步骤
7. expectedresults：预期结果

# 项目打包：
1. 生成exe文件：使用Pyinstaller进行打包，pip install pyinstaller安装好之后，到该文件夹下，执行pyinstaller -F Freemind2Testlink.py，在dist文件夹下就会生成一个独立的exe文件了。
2. 生成macOS执行文件：用户可自行打包
