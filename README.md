# enaeaHelper · 学习公社自动播放脚本

> 一个油猴（Tampermonkey）脚本，用于在学习公社（study.enaea.edu.cn）自动进入未完成的章节并连续播放课程视频。

## 功能

- 自动找到进度未达 100% 的章节并进入学习
- 播放中途暂停时，自动点击「继续学习」并处理问答弹窗
- 当前章节播放完成后，自动返回课程列表继续下一章

## 使用方法

1. 安装浏览器扩展 [Tampermonkey](https://www.tampermonkey.net/)
2. 在 Tampermonkey 中新建脚本，粘贴 [`enaeaHelper.user.js`](enaeaHelper.user.js) 的全部内容并保存
3. 登录学习公社，进入「我的课程」页面，脚本会自动开始工作

## 说明

- 脚本代码完全开源，不收集任何数据，可以放心使用
- **仅供学习交流，禁止用于商业用途**
- 欢迎提 Issue 交流问题；如果对你有帮助，请点一个 ⭐ Star 支持一下
