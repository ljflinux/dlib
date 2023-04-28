学习python人脸识别，需要安装Dlib库，但Windows 10下安装的是Python 3.7.4，CSDN的安装dlib文档都是安装vs2015和cmake方法的各种坑，去了Google搜了也没有好的办法，都是类似的方法。

dlib官网只有Python 3.6的whl文件，没有 3.7版本的。

这个文件：dlib-19.17.0-cp37-cp37m-win_amd64.whl是针对Python 3.7版本的。

下载到d:\根目录，安装命令：

pip install d:\dlib-19.17.0-cp37-cp37m-win_amd64.whl
