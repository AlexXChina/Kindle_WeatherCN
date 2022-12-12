# Kindle_WeatherCN
Kindle WeatherCN，中文台历系统
原理：内置浏览器 访问H5页面

# 操作方法一（无需越狱）

# 操作方法二（越狱+python3+Kindle_WeatherCN脚本）

## 第一步：越狱
https://bookfere.com/post/970.html

## 第二步：安装 MRPI和KUAL插件
https://bookfere.com/post/311.html

## 第三步：安装 python3 插件
https://bookfere.com/post/311.html#p_8

## 第四步：拷贝Kindle_WeatherCN脚本
下载并解压 拷贝Kindle_WeatherCN脚本
拷贝到 extensions文件夹
目录结构如下

Kindle磁盘
└── extensions
    └─── KindleWeatherCN
        ├── bin
        └── www
        
## 第五步：在KUAL中运行 “Kindle_WeatherCN”
运行KUAL工具
![Image text](https://raw.githubusercontent.com/0111/Kindle_WeatherCN/main/01-RunKUAL.png)

启动 Kindle_WeatherCN服务
![Image text](https://raw.githubusercontent.com/0111/Kindle_WeatherCN/main/02-StartService.png)


## 第六步：原生浏览器中访问 http://127.0.0.2 即可
![Image text](https://raw.githubusercontent.com/0111/Kindle_WeatherCN/main/03-WebVist127-0-0-2.png)

## 第七步：自定义设置所在城市 
访问 http://127.0.0.2/config.html 
正确配置后，选择“应用配置”

在新页面加载后，保存该书签即可。
