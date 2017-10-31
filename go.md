# 测试代码路径 :
/gopath1/src/restful-json/tns-restful-json-api-master/myRestFul-v3-token


GOPATH 值:

echo $GOPATH
/gopath1/src

export  GOPATH=/gopath1/src

测试url  :

172.16.10.18/myweb/Home.html


后台url  :

http://172.16.10.18/index.html


数据库管理员 账号:root 密码webdemo

mysql -uroot -h172.16.10.18 -p'webdemo'









mysql -hlocalhost -p


password

webdemo



grant  all privileges  on  *.* to 'root'@'172.16.10.18'  identified  by 'webdemo';


Received #1045 error from MySQL server: "Access denied for user 'root'@'172.16.10.18' (using password: NO)"
