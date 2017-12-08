# pyEmail
学习使用python来发送email

加油:）

刚开始到网上搜索python发邮件的时候，资料查阅的不够全面，导致个人写出来的代码无法使用，特别是在配置邮件服务器这一块儿，没有理解。

网上搜到的链接，一般就是python smtplib为关键字

以下为参考链接

Python 3 邮件的接收（IMAP）http://blog.csdn.net/q932104843/article/details/52502447

Python实现发送邮件http://www.jianshu.com/p/96b1d1f5844a

菜鸟教程：http://www.runoob.com/python/python-email.html


可以先参看第一、二个链接，了解imap、smtp、pop3三种协议的区别。第三个写了不同需求的邮件发送，包括发送简单文本内容的邮件；发送HTML格式的邮件；发送带有福建的邮件。


之前就是混淆了imap和smtp造成了混乱。

简单邮件传输协议（Simple Mail Transfer Protocol, SMTP）

  1、SMTP是一个相对简单的基于文本的协议
  
  2、在其之上指定了一条消息的一个或多个接收者（在大多数情况下被确认是存在的），然后消息文本会被传输。
  
  3、可以通过telnet程序来测试一个SMTP服务器。
  
  4、SMTP使用TCP端口25。
  
  5、要为一个给定的域名决定一个SMTP服务器，需要使用MX (Mail eXchange) DNS。
  
  6、一句总结：它用来**发送邮件**
  
链接：https://zh.wikipedia.org/wiki/%E7%AE%80%E5%8D%95%E9%82%AE%E4%BB%B6%E4%BC%A0%E8%BE%93%E5%8D%8F%E8%AE%AE


交互式邮件存取协议（Internet Mail Access Protocol，IMAP）

  1、它是跟POP3类似邮件访问标准协议之一.
  
  2、开启了IMAP后，您在电子邮件客户端收取的邮件仍然保留在服务器上，同时在客户端上的操作都会反馈到服务器上，如：删除邮件，标记已读等，服务器上的邮件也会做相应的动作.所以无论从浏览器登录邮箱或者客户端软件登录邮箱，看到的邮件以及状态都是一致的.
  
  3、一句总结：它用来**收取邮件**
  
链接：http://www.jianshu.com/p/96b1d1f5844a


未完待续



