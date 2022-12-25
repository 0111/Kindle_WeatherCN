# Kindle_WeatherCN
Kindle WeatherCN，中文台历系统
原理：内置浏览器 访问H5页面

![Image text](https://raw.githubusercontent.com/0111/Kindle_WeatherCN/main/00-JustSoso.jpg)

# 重要的第一步：关闭屏幕休眠模式
点击，放大镜，搜索框中输入： ～ds 回车

操作参考：https://bookfere.com/post/150.html

## 测试站点
测试站点：https://0111.github.io/Kindle_WeatherCN

测试站点：https://0111.github.io/Kindle_WeatherCN/config.html 

可以复制这个短网址到kindle浏览器测试： https://dwz.win/a2Cy

Chrome模拟600*700的显示屏效果（Kindle 7th大体一致）

![Image text](https://raw.githubusercontent.com/0111/Kindle_WeatherCN/main/05-Chome_WebView.png)


# 操作方法一（无需越狱）
## 第一步：下载解压Kindle_WeatherCN脚本

## 第二步：将www目录发布到web站点

## 第三步：原生浏览器中访问 http://website 即可
![Image text](https://raw.githubusercontent.com/0111/Kindle_WeatherCN/main/03-WebVist_127-0-0-2.png)

## 第四步：自定义设置所在城市 
访问页面 http://website/config.html 


![Image text](https://raw.githubusercontent.com/0111/Kindle_WeatherCN/main/04-Setting_City.png)

正确配置后，选择“应用配置”

在新页面加载后，保存该书签即可。



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
```
Kindle磁盘
└── extensions
    └─── KindleWeatherCN
        ├── bin
        └── www
```        
## 第五步：在KUAL中运行 “Kindle_WeatherCN”
### 运行KUAL工具

![Image text](https://raw.githubusercontent.com/0111/Kindle_WeatherCN/main/01-Run_KUAL-Plugin.png)

### 启动 Kindle_WeatherCN服务

![Image text](https://raw.githubusercontent.com/0111/Kindle_WeatherCN/main/02-Start_KWService.png)


## 第六步：原生浏览器中访问 http://127.0.0.2 即可
![Image text](https://raw.githubusercontent.com/0111/Kindle_WeatherCN/main/03-WebVist_127-0-0-2.png)

## 第七步：自定义设置所在城市 
访问 http://127.0.0.2/config.html 

![Image text](https://raw.githubusercontent.com/0111/Kindle_WeatherCN/main/04-Setting_City.png)

正确配置后，选择“应用配置”

在新页面加载后，保存该书签即可。
