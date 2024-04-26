# 这是一个知识库结构检查软件
由于知识库每次都搞的乱七八糟，因此写一个MFC树状图帮助快速排查


第一版功能：
首先是一个自定义创建文件夹的窗口
![image](https://github.com/WzyInCN/MFC/assets/122770024/27aa8b4b-7c79-47cd-8a73-49ef167a5f7b)
然后是一个树状图可以用来检查
![image](https://github.com/WzyInCN/MFC/assets/122770024/477d56e0-169e-4fa3-8014-0e957c7dc59d)
关于窗口还没编辑
![image](https://github.com/WzyInCN/MFC/assets/122770024/426c0c28-43e3-4d9a-a963-1f0446a949e7)

# 计划下一步添加功能
1，在初始化窗口增加记忆功能，比如我创建了一个知识库叫 云计算，那么下次启动的时候Edit控件默认值就是 云计算\n
2，在WorkDlg窗口处增加  选中树状图的某一个节点后，**新建文件夹的功能**，而且根据V20240425原则，文件夹层级不能超过2级
