# IP_Pool
- 构建一个爬虫代理的ip池
- 基于python 3.7
- 思路
1.找到一个免费的ip 网站
2. 爬取ip(常规爬取request+ Beautifulsoup)
3.验证ip 的有效性,携带ip 去访问指定网站,并查看返回状态码
4.记录ip