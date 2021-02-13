
## Create project
```
  npx react-native init ximalaya --template react-native-template-typescript
```

Install dependencies manually
```
npm install -D typescript @types/jest @types/react @types/react-native @types/react-test-renderer
```



## 多环境支持
```
  npm i react-native-config

  cd ios
  pod install
```
Code
```
  import Config from "react-native-config"
```