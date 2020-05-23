
```bash
$ cd your-app
$ yarn
$ yarn start
```

#### 启动之后查看[pc 页面](http://127.0.0.1:3000/pc/demo)，[h5 页面](http://127.0.0.1:3000/pc/demo)

### 4 build

```bash
$ yarn build
```

### 5 如何增减加页面入口

#### 5.1 增加入口

只需要在 `/src/`

```bash
$ mkdir newEntry
$ cd newEntry
$ touch index.js
```

##### 然后再重新 `yarn start`, 就可以在新的页面写代码了

##

#### 5.2 减少入口

就更简单了，只要删掉一个 src 下的文件夹就可以了，文件夹的 index.js 改为其他的名字 如 a.js

### 插件

集成了 eslint prettier, 推荐使用 vscode ，安装 Prettier-code formatter 和 Formatting Toggle
, 可以根据 eslint 规则自动格式化代码
