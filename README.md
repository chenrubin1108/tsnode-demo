# tsnode-demo
1. 
npm install typescript@2.9.2 -g
npm install ts-node@7.0.0 -g

2. 安装完相应的依赖包后,在.vscode/launch.json 文件更改为你自己的安装路径(全局安装ts-node会有个路径)即可
```json
// 更改为自己电脑上的路径
"program": "C:/Users/HP/AppData/Roaming/npm/node_modules/ts-node/dist/bin.js",
```
3.  vscode 点击运行和调试 选择ts-node 控制台输出为1 就是成功了
![avatar](https://github.com/chenrubin1108/tsnode-demo/blob/master/success.jpg)