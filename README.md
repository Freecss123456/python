# python

#*****安装python3.5*****# \
sudo add-apt-repository ppa:fkrull/deadsnakes \
sudo apt-get update \
sudo apt-get install python3.5 \
卸载python3.5 \
sudo apt-get purge ......(点点为为程序名称,purge参数为彻底删除文件）, \
然后sudo apt-get autoremove,sudo apt-get clean和dpkg -l |grep ^rc|awk '{print $2}' |sudo xargs dpkg -P 两条命令来清除残余的配置文件

#*****ubuntu14.04下pycharm的安装*****# \
参考网址 http://www.cnblogs.com/cwjbest/p/5861115.html

#*****安装tensorflow*****# \
sudo pip3 install --upgrade https://storage.googleapis.com/tensorflow/linux/gpu/tensorflow-0.11.0-cp34-cp34m-linux_x86_64.whl

卸载tensorflow \
pip3 uninstall tensorflow

