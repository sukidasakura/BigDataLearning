## PG
从下面的图可以看出，一个文件被切分成多个对象，映射于多个PG中。  
最终PG被映射到OSD 中，可以这样看，PG中存了很多的对象的信息  
对象通过Crush 算法映分布存储于OSD 中。  
可以看成是对象
![ceph-pg](http://my.csdn.net/uploads/201206/19/1340106194_9365.png)