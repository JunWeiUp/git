1.你需要在gitlab或github上创建账号并下载git
2.打开git bash，输入命令ls -al ~/.ssh 

![Paste_Image.png](http://upload-images.jianshu.io/upload_images/1507947-658767c05b6991a1.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
检查是否显示有id_rsa.pub或者id_dsa.pub，如果有那么跳过下一步就可以了
3.输入ssh-keygen -t rsa -C "JunWeiUP@seeyouabroad.org" ， 账号记得改成自己的连按回车就可以啦！

![Paste_Image.png](http://upload-images.jianshu.io/upload_images/1507947-7d72845f7a7dd0ef.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

4.输入cat ~/.ssh/id_rsa.pub 就可以查看key了

![Paste_Image.png](http://upload-images.jianshu.io/upload_images/1507947-af7d06acb9069cdf.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

5.复制key添加到你的gitlab或者github上面

![Paste_Image.png](http://upload-images.jianshu.io/upload_images/1507947-d638761bd4fb01d5.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

6。这些全部操作完了就可以用了，只要管理员给你相关项目的权限就可以正常使用git了
