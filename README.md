###bower
先全局安装bower
```javascript
npm install -g bower
```

使用以下命令来测试安装是否成功以及学习bower的相关命令
```javascript
bower help
```

默认用bower下载库会安装到当前目录下的bower_components文件下
若想指定下载到文件位置，则在当前名录下建立.bowerrc文件(注意：若无法直接新建此文件，可用命令 type nul>.bowerrc )
然后配置路径
```javascript
{
  "directory" : "public/components"
}
```
