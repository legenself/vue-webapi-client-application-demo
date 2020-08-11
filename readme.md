
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

<br />
<p align="center">
 
 <h3 align="center"></h3>
 <p align="center">
 使用asp.net core webapi + vue + webwindow 构建的独立运行客户端示例
 <br />
 
 </p>
</p>

## 概述
这个示例希望提供一个开发客户端技术栈的思路


- vue 是流行的前端框架
- webwindows 是一个能够快速在使用的webview工具
- asp.net core webapi 是流行的后端框架
- signalr 是一个常用的websocket工具



## 这个示例做了什么
- 新建了一个.net core webapi项目
- 添加了wwwroot文件，并使其始终拷贝到输出，并开启静态文件和默认文件
- 安装了如下依赖
  - webwindows 显示webview
  - NSubsys 隐藏发布后的命令行窗口
- 修改了program的IHostBuilder 为非阻塞运行
- 🍾❀ 大功告成

## 注意
- 在windows 中需要安装 edge beta版才可正常运行
- 界面与后端交互如果不太熟悉webview那一套，又有需要实时展示，推荐可以用signalr

