# es6-less-IDE
es6+less 开发、编译、输出脚手架

## 目录
- app -源代码目录 
- main.js -webpack的读取文件的主入口 
- source -存放需要webpack处理的文件和代码 
- build -webpack配置文件 
- node_modules -node模块安装目录 
- public -打包时，默认将文件生成到public目录 
- .babelrc -babel的配置文件 
- package.json -node配置文件 
- postcss.config.js -postcss兼容配置文件

## 修改
- 2018-10-8
1. 添加css压缩
2. 修正css中引用图片相对路径

## 参考
[源自](https://blog.csdn.net/qq_30100043/article/details/78564525)
- webpack_init.zip，是源码