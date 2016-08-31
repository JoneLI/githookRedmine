# githookRedmine
集成git与redmine rest API进行控制研发流程控制。
已经实现的功能需求：
1.使用Python Redmine Web Services Library（pyredminews）URL：https://github.com/ianepperson/pyredminews 进行通过Python对于Redmine REST API进行操作。
2.控制git commit 的格式为Fix|Issue|Feature #bug id:note

#Installation
> git clone https://github.com/JoneLI/githookRedmine
> cd githookRedmine
1.拷贝pyredminews文件夹的文件与hook里面的文件到你对应的git代码库中。
2.在hook里面的对应的文件填写redmine的URL与对应的账号。

