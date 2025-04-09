# Kindle_WeatherCN
Kindle WeatherCN，中文台历系统
原理：内置浏览器 访问H5页面

![Image text](https://raw.githubusercontent.com/0111/Kindle_WeatherCN/main/00-JustSoso.jpg)

# 重要的第一步：关闭屏幕休眠模式
点击，放大镜，搜索框中输入： ～ds 回车

操作参考：https://bookfere.com/post/150.html


# 方法一：访问公网站点
## 测试站点
2025年的版本修复了：kindle本地时钟不准的问题，程序每30分钟会主动从互联网同步正确时间。

直接访问=> https://kw6.netlify.app

自定义设置：点击 页面“城市”，进入自定义参数设置，点击保存后生成配置参数，保存该网址即可。

备用站点：

测试站点：https://0111.github.io/Kindle_WeatherCN

测试站点：https://0111.github.io/Kindle_WeatherCN/config.html 

Chrome模拟600*700的显示屏效果（Kindle 7th大体一致）

![Image text](https://raw.githubusercontent.com/0111/Kindle_WeatherCN/main/05-Chome_WebView.png)


# 方法二：自主搭建服务器
## 第一步：下载解压Kindle_WeatherCN脚本

## 第二步：将www目录发布到web站点

## 第三步：原生浏览器中访问 http://website 即可
![Image text](https://raw.githubusercontent.com/0111/Kindle_WeatherCN/main/03-WebVist_127-0-0-2.png)

## 第四步：自定义设置所在城市 
访问页面 http://website/config.html 


![Image text](https://raw.githubusercontent.com/0111/Kindle_WeatherCN/main/04-Setting_City.png)

正确配置后，选择“应用配置”

在新页面加载后，保存该书签即可。

