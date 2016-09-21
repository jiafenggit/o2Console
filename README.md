o2Console
===
### 功能

- [x] 本地开发开关
- [x] 远程调试开启

###使用
- 本地配置(已去掉，只支持URL开启
- )
```
var o2Log = new o2Log({
 debug: true
});
```
- 远程开启
```
window.location.href?debug=true
```
- 代码内打印
```
o2Console.log('o2Console');
```