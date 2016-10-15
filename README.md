icourse163.org课程下载
==========

### 准备
* 测试环境：   `python 3.5、Windows7/Linux`

* 依赖包： `requests`
	pip install requests
	
* [爱课程网](http://www.icourses.cn/home/)的用户名和密码

* 需要下载的课程主页地址。e.g. http://www.icourse163.org/learn/NUDT-42001?tid=488001  
    (注：【第N次开课】--->【查看内容】---> 【地址栏】)


### 开始：
    ```python
	'''
    :param 用户名: 爱课程网用户名
    :param 密码: 爱课程网密码
    :param 课程地址: 课程主页地址
    :return: 
    '''
	python icourse163_dl.py 用户名 密码 课程地址
	```

### 下载中... 
    * 文件默认下载到 `icourse163_dl.py` 所在目录，按每一讲组织目录。  
    * 有时下载速度会很慢，这时你可以出去玩会！  
    (`Ctrl+C` 终止程序，下次不会傻不啦叽的把已下载的重下一遍)

	


