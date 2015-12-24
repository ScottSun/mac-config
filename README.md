# mac-config

* mac最大文件描述符修改 (不重启系统)
<p>sudo sysctl -w kern.maxfilesperproc=65536
sudo sysctl -w kern.maxfiles=65536</p>
