# jiasule
#最新破解工商信息公示网加速乐加密cookies

本项目为学习破解Js加密而立，请勿用于违法用途，用于违法用途产生的后果与本人无关，本版本仅供学习参考所用，所有下载者应于24小时内学习完毕后删除。

#使用方法

按照environment和requirements.txt配置好环境后，运行crack.py，获得jsl_clearance与jsluid。
在请求的header中的cookies添加即可正常访问。

如发现bug或不能使用请在lssues中告知。

#调用思路


1.无cookies请求页面获得jsluid与返回的js代码。
2.运行得到的js代码。（经多次测试得出返回的js代码是相同的，只是每次的x值与y值是不同的，所以本项目在本地构建了一个js项目，每次调用传入x，y）
3.第二步运行后会得到一个解密后的js代码段（其中会返回多个版本），去除其中的本地运行会出错的代码，运行会得到会jsl_clearance。
4带上jsl_clearance与jsluid就可以愉快的访问了



#可用网站

国家企业信用信息公示系统

中华人民共和国公安部

中国医采网

