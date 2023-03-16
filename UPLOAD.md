# Gadget Works Online Ordering System  v1.0 has arbitrary file upload

BUG_Author: zhengjiasheng

Website source address:https://www.sourcecodester.com/php/13093/gadget-works-online-ordering-system-phpmysqli.html

Vulnerability url: /philosophy/admin/products/controller.php?action=add

post form-data parameter 'filename' exists arbitrary file upload

#### Steps to reproduce

1.Go to the admin Dashboard

http://localhost/philosophy/admin/login.php

System Admin Access information:

Username: janobe Password: admin

2.Click on Products and Click on + News and select Products

![image](https://github.com/zhengjiashengbaba/bug_report/blob/main/up1.png)

3.Upload the picture Trojan horse,and append the file suffix .php through BurpSuite

![image](https://github.com/zhengjiashengbaba/bug_report/blob/main/up2.png)

4.Access to upload picture Trojan links,you can execute any command.

For example,dir command.

![image](https://github.com/zhengjiashengbaba/bug_report/blob/main/up3.png)
