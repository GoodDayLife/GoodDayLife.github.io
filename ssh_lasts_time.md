# Linux VPS 连接时间长度设置

	* vim /etc/ssh/sshd\_config
	* /ClientAliveCountMax
	* 删除前面的注释,修改其时间值.
	* :wq
	* /etc/rc.d/init.d/sshd restart

OK.

