# douyin_lx
根据抖音的share分享页面，字符集映射后解析用户基本信息


首先通过charles抓包。抓到了一个share_url

![在这里插入图片描述](https://img-blog.csdnimg.cn/20190617165732328.png)

![在这里插入图片描述](https://img-blog.csdnimg.cn/20190617165715413.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MzU4MjEwMQ==,size_16,color_FFFFFF,t_70)
我访问过去看了下，

https://www.iesdouyin.com/share/user/102064772608

![在这里插入图片描述](https://img-blog.csdnimg.cn/20190617165825334.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MzU4MjEwMQ==,size_16,color_FFFFFF,t_70)


   有数据的。那就拿数据。然后发现它的数字做了字符集映射。

那么我们就来查看下他的映射方式...


**更多详情请查看csdn博客**

https://blog.csdn.net/weixin_43582101/article/details/92658860


**运行结果：**   
   ![在这里插入图片描述](https://img-blog.csdnimg.cn/20190809124541951.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MzU4MjEwMQ==,size_16,color_FFFFFF,t_70)
