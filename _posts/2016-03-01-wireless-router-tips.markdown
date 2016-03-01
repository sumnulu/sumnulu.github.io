---
layout: post
title:  "ADSL Router ipucları"
date:   2016-03-01 19:28:59 +0200
categories: tips wireless router
---
Adsl router'ların web parolasını öğrenmek veya değiştirmek için ssh veya telnet ile router'a bağlandıktan sonra:

- Parolayı görmek için `nvram get http_passwd`
- Parolayı değiştirmek için `nvram set http_passwd=ç0kg1zl1p4r0l4`


{% highlight bash %}
admin@(none):/tmp/home/root# nvram get http_passwd
 cok_gizli_parola
 admin@(none):/tmp/home/root#
{% endhighlight %}

PS: İleriki zamanlarda bu postu güncelleyeceğim.
