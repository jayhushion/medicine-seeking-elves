# Medicine Seeking Elves
# 基于快应用的药品查询软件

## 项目根目录结构如下
```
├── sign                      rpk包签名模块
│   └── debug                 调试环境
│       ├── certificate.pem   证书文件
│       └── private.pem       私钥文件
├── src
│   ├── About                 应用关于
│   │     └── index.ux        页面文件
│   ├── Common                公用的资源和组件文件
│   │   ├── logo.png          应用图标
│   │   ├── background2.png   背景图
│   │   ├── button.png        按钮图片
│   │   ├── js                公共js资源
│   │   └── css               公共css资源
│   ├── Catalog               药品分类页面文件
│   │   ├── arrow-right.png   箭头图标
│   │   ├── disease.js        分类药品数据
│   │   └── index.ux          页面文件
│   ├── Remind                提醒用药页面文件
│   │   └── Reminder.ux       页面文件
│   ├── Search                搜索页面文件
│   │   ├── SearchSelect.ux   页面文件及扫描搜索功能
│   │   ├── InputSearch       输入搜索页面文件
│   │   │     └── index.ux    页面文件
│   │   └── Display           搜索显示页面文件
│   │         └── index.ux    页面文件
│   ├── Demo                  主页页面文件
│   │    └── index.ux         页面文件，可自定义页面名称
│   ├── app.ux                APP文件，可引入公共脚本，暴露公共数据和方法等
│   ├── manifest.json         项目配置文件，配置应用图标、页面路由等
│   └── util.js               创建桌面图标文件
└── package.json              定义项目需要的各种模块及配置信息
```
