2020.10.24 哔哩哔哩 ctf







# 第一题

​	进入页面，开始分析

![1](C:\Users\Yunoon\Pictures\哔哩哔哩 ctf\1.png)

源码

![2](C:\Users\Yunoon\Pictures\哔哩哔哩 ctf\2.png)

F12

![3](C:\Users\Yunoon\Pictures\哔哩哔哩 ctf\3.png)









# 第二题

同一个页面，直接改UA,然后用Burp Suit 发包



![4](C:\Users\Yunoon\Pictures\哔哩哔哩 ctf\4.png)





# 第三题

先访问页面

![image-20201024232502428](C:\Users\Yunoon\AppData\Roaming\Typora\typora-user-images\image-20201024232502428.png)

直接使用弱密码爆破，单纯靠猜

账号admin 密码bilibili



# 第四题



![image-20201024232738082](C:\Users\Yunoon\AppData\Roaming\Typora\typora-user-images\image-20201024232738082.png)

更改cookie中role的值为Administrator，并且md5加密

然后再发包就可以看见flag了

![7](C:\Users\Yunoon\Pictures\哔哩哔哩 ctf\7.png)



第五题

通过分析network发现有uid，然后就是python穷举

![8](C:\Users\Yunoon\Pictures\哔哩哔哩 ctf\8.png)

![image-20201024233318892](C:\Users\Yunoon\AppData\Roaming\Typora\typora-user-images\image-20201024233318892.png)
