# 视频小程序
“小程序”这个是由微信最早提出的，国内的其他互联网巨头也相继推出了自己的小程序。小程序是一种新的开放能力，开发者可以快速地开发一个小程序，它可以被便捷地获取和传播，同时具有出色的用户体验。
“视频小程序”也继承了上述小程序的优势，但是不局限于特定的APP，它运行在客户自己的APP视频播放器之上。目前我们已经适配了市面上占有率较高的几款播放器：阿里云播放器、七牛云播放器、ijkplayer等。
视频小程序是基于<a href="http://docs.videojj.com/docs/videoos-lua-app" target="_blank">OS Lua</a>方案，一个简单的小程序，由一个几百行的lua脚本加一个几十行的 json 配置文件组成。

完成以下两步即可投放一个小程序到你的APP
## 创建投放素材
点击左侧导航“投放管理”=>“投放素材管理”，选择需要投放的小程序，进入“创建素材”设置页面，素材配置由第三步上传的json配置文件决定，根据实际情况填写

## 创建投放计划
点击左侧导航“投放管理”=>“投放计划管理”=>“新增投放计划”，选择需要投放的小程序，进入“新增投放计划”设置页面  

* 投放名称：根据实际情况填写，限制30个字符长度
* 投放素材：这里的下拉框选项就是第六步创建的素材，根据实际情况选择
* 视频/直播间的ID/URL：根据实际情况填写，视频/直播间的唯一值，如需填写多个ID/URL，请用英文的“,”分隔即可
* 投放时间类型：即可（直播）、视频时间（点播）、北京时间（直播）
