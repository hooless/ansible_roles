### bind 集群

![bind](http://ot7vbu52o.bkt.clouddn.com/20170717150026667512670.jpg?imageslim)

满足需求：
1. 自建高可用内部 dns，配置内部域名 ， 记录存储在 mysql 中，实现高可用 (bind 支持 mysql ，需要手动编译对应的模块 --with-dlz-mysql)
2. 配置两台普通 dns ，用来做转发，实现内外网域名的解析分离。
