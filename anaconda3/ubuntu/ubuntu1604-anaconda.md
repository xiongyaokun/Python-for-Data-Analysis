## Install Anaconda3 in virtualbox Ubuntu16.04

默认安装的是python2.7和python3.5，
从python3.5升级到python3.6

<pre>
$ sudo add-apt-repository ppa:jonathonf/python-3.6
$ sudo apt update
$ sudo apt install python3.6
</pre>

删除python3.5
<pre>
$ sudo apt autoremove python3.5
</pre>


### 开始安装anacoda3

需要切换到root身份运行，如果以vagrant身份会出现protocol error

<pre>
$ su  # 切换成root身份
$ bash Anaconada3-5.1.0-Linux-x86\_64.sh
</pre>
