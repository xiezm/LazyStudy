# 关于本脚本

因原作者将脚本被删除，这里只能依靠本人能力和[ivanwhaf](https://github.com/ivanwhaf/xxqg-helper)的脚本更新  

# 软件界面
<div align="center">
<img src="https://ftp.bmp.ovh/imgs/2020/06/bfecded9b5fb510b.jpg" height="30%" width ="30%" />
<img src = 'https://ftp.bmp.ovh/imgs/2020/06/beb751a02940ceb9.jpg' height="30%" width ="30%" />
</div>

# 懒人学习

一款基于auto.js，安卓自动学习脚本，支持看文章视频、收藏分享评论、挑战答题和其他答题。

[release下载](https://github.com/lolisaikou/LazyStudy/releases/)

**环境依赖**

- 手机为安卓7.0以上版本
- 安装程序后，点击加载悬浮窗，弹出授权界面。请授权 无障碍 和 悬浮窗。

**使用说明**

- 文章和视频：点击“切到 强国”，在强国主界面点击“开始浏览”，即可自动浏览。
- 挑战答题：进入挑战答题界面，点击“挑战答题”，开始答题，答错会自动重新开始，得到6分停止。
- 每日答题：进入每日答题界面，点击"每日答题"。程序会自行进行每日答题，得到6分停止。
- 手动改题：手动查改删增，支持以题目或答案关键字查询，或列出最后十条入库记录
- 更新网络题库：从网络同步最近题库，过滤后入tikuNet表

**版本更新**
- 2020.06.19  
        完全依靠[ivanwhaf](https://github.com/ivanwhaf/xxqg-helper)的脚本，恢复了使用  
        修复了大部分功能无法使用的问题  
        <font color=red>每日答题功能不能做每周和专项答题了</font>  
        挑战答题答错会自动重新挑战，而且增加了限制，每日最多10题，达到自动停止  
        每日答题答够十题也会自动返回了  
        每日阅读的文章自动添加到数据库，重复阅读会自动返回，感谢[wanghuisenior](https://github.com/wanghuisenior)  
        更改包名为com.lazyxue（因为使用auto.js pro打包导致和之前的签名不同）  
***
        
- 2020.04.02  
        再次修复填空题获取不到题目问题  
***
- 2020.04.01  
        修复填空题获取不到题目问题  
***
- 2020.03.27  
        修复每日答题填空题获取多个空格时错误；获取正确答案由滑屏改控件滚动  
***
- 2020.03.21  
        修复获取填空题题目失败，点击评论后增加停顿  
***
- 2020.02.23  
        重制界面，新增按积分浏览，修复改题中update语句错误  
        支持按题目与答案模糊搜索，增加在线帮助与更新功能    
        挑战答题点击间隔改为随机  
***
- 2020.01.19  
        新增下载网络题库到本地，取消切换小程序方式(感谢kessil)    
        修复每日答题,错误答案入库问题    
        更新浏览文章视频部分，目前为xxqg_v3.1.0 (无 UI).js(感谢ivanwhaf)    
        新增手动查改删增题库功能    
        新增本地频道浏览    
***
- 2019.12.24  
        修复每日答题获取提示内容失败等问题    
***
- 2019.12.15  
        修复答题部分bug 取消浏览时收藏评论分享功能(避免部分手机报错)    
***
- 2019.12.13  
        重构收藏分享评论模块，修复错误    
***
- 2019.12.11  
        重构每日答题逻辑，速度更快    
***
- 2019.12.08  
        新增每日答题功能    
***
- 2019.11.21  
        发布    

<font size=5>**特别感谢**</font> <font size=1 color=gray>以下排名不分先后</font>
----

[**lgpersonal**](https://github.com/lgpersonal/)  
[**kessil**](https://github.com/kessil/AutoXue)  
[**ivanwhaf**](https://github.com/ivanwhaf/xxqg-helper)  
[**studyhelperhelper**](https://github.com/studyhelperhelper/studyhelper)  