# XAUAT 自动评教脚本

## 项目简介
本项目是一个基于 [Tampermonkey](https://www.tampermonkey.net/) 的用户脚本，用于 **西安建筑科技大学（XAUAT）教学评价系统** 的自动评教操作。该脚本可实现 **自动打开评教页面、自动提交评教表单** 等功能，提高评教效率🤔。

## 功能特性
- 🚀 自动打开评教页面
- ✅ 自动勾选所有评分项
- 📝 自动填写评教意见
- 📤 自动提交评教表单

## 使用方法
1. 安装浏览器扩展：
   - Chrome：[Tampermonkey 扩展](https://chromewebstore.google.com/detail/%E7%AF%A1%E6%94%B9%E7%8C%B4/dhdgffkkebhmkfjojejmpbldmpobfkfo)
   - Firefox：[Tampermonkey 扩展](https://addons.mozilla.org/zh-CN/firefox/addon/tampermonkey/)
   - Edge：[Tampermonkey 扩展](https://microsoftedge.microsoft.com/addons/detail/tampermonkey/iikmkjmpaadaobahmlepeloendndfphd)
2. 安装该脚本：
   1. 打开网页 [https://greasyfork.org/zh-CN/scripts/536990-xauat-%E8%87%AA%E5%8A%A8%E8%AF%84%E6%95%99%E8%84%9A%E6%9C%AC](https://greasyfork.org/zh-CN/scripts/536990-xauat-%E8%87%AA%E5%8A%A8%E8%AF%84%E6%95%99%E8%84%9A%E6%9C%AC)，安装该脚本
   2. 打开 Tampermonkey 面板，点击 **“创建新脚本”**, 将 [xauat自动评教脚本-1.1.user.js](xauat自动评教脚本-1.1.user.js) 文件内容粘贴进去
3. 进入 `XAUAT 即时性评教系统` 页面，即可自动开始评教。
   - 即时性评教系统网址：[https://swjw.xauat.edu.cn/evaluation-student-frontend/#/timely-evaluation/myparticipate](https://swjw.xauat.edu.cn/evaluation-student-frontend/#/timely-evaluation/myparticipate)

## 版本记录
### v1.1
- 增加路由监听机制，适配不同页面行为
- 增加延迟操作以提升兼容性
- 改进错误捕获与日志输出
### v1.2
- 更新脚本命名
- 新增总结性评教功能
### v1.3
- 增加评教完成提醒并优化 UI
- 添加首页路由处理并优化代码
- 添加悬浮窗 UI 用于控制评教流程
- 优化 waitForElement 函数逻辑
- 重构代码并优化功能
### v1.4
- 尝试用自动更新 但是失败了
前三代更新全部由MrSuM更新
### v1.4.3
- 已经被guihub托管自动更新
