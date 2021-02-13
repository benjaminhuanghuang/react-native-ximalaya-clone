
## 第5章 项目初始化
本章才算是正式开始应用的开发了。还有我在工作中用到的两个非常好的第三方项目，可以做到多环境设置和绝对路径的设置，能帮助我们减少一些繁琐枯燥又容易出错的工作。

共 3 节 (27分钟) 收起列表

## 5-1 项目初始化 (05:48)
 ```
  npx react-native init ximalaya --template react-native-template-typescript
```

Install dependencies manually
```
  npm install -D typescript @types/jest @types/react @types/react-native @types/react-test-renderer
```


## 5-2 多环境 (07:43)
```
  npm i react-native-config

  cd ios
  pod install
```
Code
```
  import Config from "react-native-config"
```
## 5-3 绝对路径 (13:26)

