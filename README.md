### 背景

windows本地运行hadoop或spark程序时,如果涉及到写入新文件等操作，可能会报Hadoop相关的异常, 需要额外进行配置



### 使用

1) 使用git clone将本项目下载, 将hadoop-3.1.0 整个目录剪切到windows任意一个不含中文不含空格的路径下。假定为"D:\hadoop-3.1.0"

2) 配置环境变量HADOOP_HOME，值为"D:\hadoop-3.1.0"
3) 将其bin添加到Path环境变量中, 值为”%HADOOP_HOME%\bin", 请勿简化只配置Path, 环境变量HADOOP_HOME为必须。
4) 环境变量配置完毕后, 进入"D:\hadoop-3.1.0\bin"目录下,  双击执行其中的winutils.exe文件后关闭黑窗口即可。

