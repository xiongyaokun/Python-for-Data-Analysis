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

设置共享文件：vagrant默认是与Vagrantfile文件所在目录为共享目录，可以把需要与虚拟机共享的文件直接放在此目录下，可以新建一个共享文件夹

<pre>
$ sudo bash Anaconada3-5.1.0-Linux-x86\_64.sh
</pre>

安装完成后，打开新的terminal
<pre>
$ anaconda -V
$ conda -h
</pre>
