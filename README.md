# 新型冠状病毒疫情实时动态省市地图

> 武汉加油，众志成城，共抗疫情

这是fork自[shfshanyue/2019-ncov](https://github.com/shfshanyue/2019-ncov)的项目，主要修复了丁香园页面参数修改后原代码运行报错的问题。


## 快速开始

``` bash
# 获取数据
node scripts/build-origin.js
```

执行以上命令后，`src/data`中就会生成数据文件。

## 数据来源

数据爬自丁香园，使用脚本 `build-origin.js` 获取数据。数据每半个小时爬取一次，直接注入到前端，因此对丁香园造成的压力很小。

另外，如果你需要更详细的数据，可以参考项目 [BlankerL/DXY-2019-nCoV-Crawler](https://github.com/BlankerL/DXY-2019-nCoV-Crawler)。

