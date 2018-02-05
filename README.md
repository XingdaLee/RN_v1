# RN_v1

## 错误信息

``
Showing Recent Messages

Connection to localhost port 8081 [tcp/sunproxyadmin] succeeded!

Port 8081 already in use, packager is either not running or not running correctly

Command /bin/sh failed with exit code 2

``

解决方法： 

1、把Xcode中所有的8081修改为8899

2、把/node_modules/react-native/React/React.xcodeproj/project.pbxproj 8081改为8899


