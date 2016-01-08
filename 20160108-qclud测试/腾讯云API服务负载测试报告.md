# 腾讯云API服务负载测试报告
##测试项
###1、单线程测试上行API
执行500次（平均每次请求内容为100~500K）
###2、多线程测试上行API
5个线程同时上传API执行500\*5次（平均每次请求内容为100~500K）
###3、多线程测试上行和下行API
5个线程同时上传API执行500\*5次（平均每次请求内容为100~500K）
5个线程同时下行API执行20000\*5次（每次响应内容为500~1000K)
###4、多线程测试上行和下行API
5个线程同时上传API执行500\*5次（平均每次请求内容为100~500K）
10个线程同时下行API执行20000\*5次（每次响应内容为500~1000K)
###5、多线程测试上行和下行API
5个线程同时上传API执行500\*5次（平均每次请求内容为100~500K）
10个线程同时下行API执行20000\*5次（每次响应内容为500~1000K)

##测试监控
###全盘扫描数监控
![](https://raw.githubusercontent.com/yuezaixz/wDModle/master/%E5%85%A8%E7%9B%98%E6%89%AB%E6%8F%8F%E6%95%B0%E7%9B%91%E6%8E%A7.png)
###当前连接数监控
![](https://github.com/yuezaixz/wDModle/blob/master/%E5%BD%93%E5%89%8D%E8%BF%9E%E6%8E%A5%E6%95%B0%E7%9B%91%E6%8E%A7.png?raw=true)
###查询数监控
![](https://github.com/yuezaixz/wDModle/blob/master/%E6%9F%A5%E8%AF%A2%E6%95%B0%E7%9B%91%E6%8E%A7.png?raw=true)
###插入数监控
![](https://github.com/yuezaixz/wDModle/blob/master/%E6%8F%92%E5%85%A5%E6%95%B0%E7%9B%91%E6%8E%A7.png?raw=true)
###查询使用率监控
![](https://github.com/yuezaixz/wDModle/blob/master/%E6%9F%A5%E8%AF%A2%E4%BD%BF%E7%94%A8%E7%8E%87%E7%9B%91%E6%8E%A7.png?raw=true)
###磁盘占用空间监控
![](https://github.com/yuezaixz/wDModle/blob/master/%E7%A3%81%E7%9B%98%E5%8D%A0%E7%94%A8%E7%A9%BA%E9%97%B4%E7%9B%91%E6%8E%A7.png?raw=true)
###容量使用率监控
![](https://github.com/yuezaixz/wDModle/blob/master/%E5%AE%B9%E9%87%8F%E4%BD%BF%E7%94%A8%E7%8E%87%E7%9B%91%E6%8E%A7.png?raw=true)
###内存利用率监控
![](https://github.com/yuezaixz/wDModle/blob/master/fds_%E5%86%85%E5%AD%98%E5%88%A9%E7%94%A8%E7%8E%87%E7%9B%91%E6%8E%A7.png?raw=true)
###CPU利用率监控
![](https://github.com/yuezaixz/wDModle/blob/master/fds_CPU%E5%88%A9%E7%94%A8%E7%8E%87%E7%9B%91%E6%8E%A7.png?raw=true)



