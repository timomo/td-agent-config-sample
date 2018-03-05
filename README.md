# td-agent-config-sample

## apache.error
```
2018-03-05 21:39:07.514212000 +0900 td.apache.error.error.error: {"level":":error","pid":"2501","client":"113.148.185.134:50337","message":"PHP Fatal error:  Uncaught Exception: here in /var/www/html/error.php:3\\nStack trace:\\n#0 {main}\\n  thrown in /var/www/html/error.php on line 3","tag":"td.apache.error"}
```

## apache.access
```
2018-03-05 21:39:07.000000000 +0900 td.apache.access.Mozilla.access: {"host":"113.148.185.134","user":null,"method":"GET","path":"/error.php","code":500,"size":null,"referer":null,"agent":"Mozilla/5.0 (Macintosh; Intel Mac OS X 10_13_3) AppleWebKit/604.5.6 (KHTML, like Gecko) Version/11.0.3 Safari/604.5.6","tag":"td.apache.access"}
```
