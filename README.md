# Anaconda多环境多版本python配置指导 (https://www.jianshu.com/p/d2e15200ee9b)
$ conda create -n py2 python=2 # 安装python2到环境py2中
$ conda create -n py3 python=3 # 安装python3到环境py3中
$ conda info --envs # 列出已安装环境
$ source activate py2 # 打开环境py2，以使用python2
$ source deactivate py2 # 关闭环境
$ source activate py3 # 打开环境py3，以使用python3
$ source deactivate py3 # 关闭环境
