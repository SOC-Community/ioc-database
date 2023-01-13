# ioc-database
Web: https://ioc.ghtk.vn/ <br/>
Now, our IoC database is more than 59,000,000++ items and update real time.<br/>
if you want to Download or get API KEY and use this free IoC database, please contact me on telegram: https://t.me/+U4v8OZYPCzU5ZTBl or email: security@ghtk.co<br/>

# IoC Sources References:
https://virusshare.com <br/>
https://malshare.com <br/>
https://urlhaus.abuse.ch <br/>
https://bazaar.abuse.ch <br/>
https://openphish.com <br/>
http://vxvault.net <br/>
https://sslbl.abuse.ch <br/>
http://cybercrime-tracker.net <br/>
https://threatfox.abuse.ch/browse/ <br/>
Our Internal Threat Hunting <br/>
SOC Community  <br/>
And More... <br/>

# IoC Patterns:<br/>
IP/Domain <br/>
Hash(md5,sha1,sha256) <br/>
Attack patterns <br/>

# Request Example:
```
GET /api/check_ioc?key=1b6e0098f67d09fdece599b84b7ccb25&token=xxxxxxxxx HTTP/1.1
Host: ioc.ghtk.vn
```

# Response Example:
```
HTTP/1.0 200 OK
Content-Type: application/json
Content-Length: 37
Server: Werkzeug/2.0.1 Python/3.8.2
Date: Thu, 12 Jan 2023 11:25:36 GMT

{
  "code": 200, 
  "result": true
}
```

# Graylog - Lookup Table Example:
![ảnh](https://user-images.githubusercontent.com/3302470/212227260-bc46aecf-5cef-45eb-a5f1-3557497b8c3a.png)
