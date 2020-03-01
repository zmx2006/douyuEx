## DouyuEx-斗鱼直播间增强插件![](https://img.douyucdn.cn/data/yuba/weibo/2020/02/18/202002182111554630626652946.png)

### 目标
1. 旨在扩展增强原版功能，优化用户体验
2. 安全，不做用户可控范围外的功能
3. 纯粹，不过分影响本来的网页功能
4. 不污染页面的结构
5. 使用简单，架构轻量，功能实用，交互友好
6. 集合移动端、客户端、web端特色功能
7. 开发架构易扩展，易维护

### 使用说明
- 首先需要[安装油猴脚本](https://www.crx4chrome.com/crx/1429/)，选择【Download crx file from crx4chrome】，然后再安装本插件
- 安装后，在礼物栏下方/鱼丸鱼翅左方会出现一个精灵球图标，点击显示功能条
- 插件基于TamperMonkey V4.10开发，若插件有无法使用的情况，请尝试[升级油猴版本](https://www.crx4chrome.com/crx/1429/)
- 若出现提示是否允许跨域访问的页面，一律选择**允许**即可

### 声明
- 本插件是本人课余兴趣开发，代码质量请勿吐槽
- 代码可供互联网的同好们参考研究，**引用请注明出处**
- 喜欢本插件的用户不妨点一下收藏或推荐给朋友，有建议或BUG请提交在greasyfork或github
- 制作契机源于斗鱼用户@阿拆家的MilkGirl
- 本插件归属：[斗鱼直播间5189167](https://www.douyu.com/5189167)
- 作者：小淳 / QQ：189964430

### 功能
#### 弹幕自动变色循环发送 
- 自动可调速发送弹幕
- 可自动改变弹幕颜色，让弹幕不再单调

#### 一键续牌
- 给所有有粉丝牌的直播间赠送一根荧光棒

#### 查看真实人数 + 已播时长
- 数据来源：播酱
- 数据将显示在原公告栏处（弹幕框上方）
- 显示今日累计观看人数，弹幕人数，送礼人数
- 显示已播时长

#### 一键签到
- 所有已关注的直播间签到
- 所有鱼吧签到
- 车队签到(由于斗鱼本身接口问题，车队签到会自动打开新的页面，签到完毕后会自动关闭这个页面，本功能参考了@lvlanxingapp的程序，在此感谢)
- pc客户端签到

#### 一键领取鱼粮
- 自动领取pc客户端旧版鱼塘宝箱
- 自动领取web端新版鱼塘气泡
- 自动领取每日/每周任务
- 有可领取的鱼粮将自动提示

#### 一键寻宝
- 一键参与鱼塘寻宝，不再需要等转圈圈了

#### 送出指定数量的礼物
- 用于送出指定数量（无限制）的礼物
- 可用于打榜，例如一次性送出999个飞机
- 背包送礼
- 一键清空背包礼物

#### 屏蔽基础广告

#### 调节弹幕大小
- 调节的是基础弹幕的大小（不算爵位弹幕等）
- 无大小限制调节

#### 自动更新
- 插件有新版本将自动提示更新

#### 获取真实直播流地址
- 可绕过斗鱼直接在本地播放器内播放
- 可直接下载(录屏)
- 该方式播放延迟极低，速度很快

#### 同屏播放
- 可在一个直播间内同时播放多个任意直播间画面（无弹幕）
- 支持在斗鱼同时观看其他平台的直播，目前支持:斗鱼/虎牙/Bilibili
- 画面可拖动可拉伸大小
- 可选择清晰度
- 可选择线路
- 点击复制直播流地址
- 双模式选择（有弹幕/无弹幕）鼠标悬停在相应模式上可查看详细特性

#### 自动抢礼物红包
- 开启后全自动抢本房间的礼物红包
- 自动保存开关状态

#### 不绑定手机号发送弹幕
- 去除验证手机的限制
- 不绑定手机号也可以发送弹幕

--------------------------------------------------

## 更新内容

### 2020年3月1日
1. 去除代码压缩以符合gf规定

### 2020年2月28日
1. 修复部分接口偶尔无法使用的BUG
2. 优化一键鱼塘寻宝
3. 提高自动抢红包成功率

### 2020年2月27日
1. 修复因斗鱼更新，一键签到失效的BUG
2. 增加自动抢礼物红包的成功率
3. 升级鱼吧签到接口
4. 鱼吧签到无法正常使用的，请尝试[升级油猴脚本版本为4.10+](https://www.crx4chrome.com/crx/1429/)，还不行请清理cookie

### 2020年2月26日
1. 新增自动抢礼物红包（没有经过多少测试，若有BUG还请提出，在此感谢）
2. 取消屏蔽直播间推荐防止挡掉直播预告【由@伯毅。提出】
3. 优化同屏播放新增复制直播流地址功能
4. 关于默认最高画质的问题已经做成[独立的脚本](https://greasyfork.org/zh-CN/scripts/396929) 【由greasyfork@Zhang recycle提出】
5. 修复一键鱼塘寻宝失效的BUG
6. 修复一键签到失效的BUG
7. 新增不绑定手机号也可以发送弹幕的功能
8. 优化资源占用

### 2020年2月20日
1. 【重要】尝试修复斗鱼同屏播放功能无法使用的BUG。以下为说明  
-- 若出现无视频的情况，尝试点击小窗上的(无视频?)，在跳出的网址提示【是否继续访问】选择【继续访问】，然后重新载入一下同屏播放即可。  
-- 以上方法在浏览器重启之前都有效，重启浏览器后需要重新操作一遍  
-- 长久的方法可以尝试自行搜索自己的浏览器【如何关闭证书过期/不是私密链接提示】，这里举chrome和搜狗浏览器的例子：  
-- chrome: 在快捷方式启动参数加上--test-type --ignore-certificate-errors  
-- 搜狗浏览器: 升级版本(搜狗浏览器10) & 选项-安全设置-去掉HTTPS异常提示  

### 2020年2月18日
1. 新增背包送礼功能(速度并不快，送礼间隔>0.1秒)【感谢斗鱼用户@最爱骆歆小宝贝和@阿拆家的胖次提供测试】
2. 新增清空背包功能【感谢greasyfork用户@巨阳提议】
3. 修复一键寻宝偶尔会出现操作进行中的BUG

### 2020年2月11日
1. 修复引起斗鱼样式异常的BUG
2. 送礼功能新增确认信息框，以防误送【感谢斗鱼用户@扌斥女子马扁提议与测试】

### 2020年2月10日
1. 优化送礼功能消息提示
2. 修复同屏播放点击后会阻塞网页的问题，并优化显示
3. 新增同屏播放**有弹幕模式**，详细特性请**鼠标悬停**在相应模式上查看
4. 修改真实人数功能提示文字为当日累计人数

### 2020年2月6日
1. 修改插件名称为DouyuEx
2. 修复弹幕发送小助手自动变色设置后重开页面不生效的BUG

### 2020年2月3日
1. 新增屏蔽直播间推荐(直播画面上层的mask)
2. 扩展功能-赠送礼物逻辑改为循环赠送1个，以保证能正确送出与真正的无限制。详细赠送信息输出在F12控制台
3. 赠送礼物示例ID已改为当前直播间礼物数据。【感谢github@Keymorek提供的地址】

### 2020年1月26日
1. 新增点击真实人数跳转到主播数据页面，数据来源:小葫芦
2. 同屏播放新增支持bilibili和虎牙直播源，现在可以在斗鱼同时观看b站和虎牙的直播啦
3. 优化了部分代码架构

### 2020年1月20日
1. 新增获取真实直播流地址
2. 新增多屏播放，可在一直播间同时观看多个直播间画面（无弹幕）  
-- 如果无法播放，请检查浏览器是否**允许flash播放**
3. 重写优化真实人数显示，现在可以保留原来的公告，且资源占用更低
4. 修复寻宝无法一次性寻完的BUG 
5. 弹幕循环发送新增发送速度区间防止系统检测，本功能需求来源greasyfork的网友
6. 弹幕循环发送新增停止时间防止忘记关闭
7. 新增今日礼物价值，显示鱼翅礼物，鼠标悬停显示背包+总礼物价值

### 2020年1月12日
1. 重构版本发布



--------------------------------------------------

## 如何维护与编译
[项目地址](https://github.com/qianjiachun/douyuEx)
### 结构
- 本脚本将各个功能分为单独的模块，每个模块互相独立，在"编译"的时候将模块内的代码复制到main.js的相应位置即可
- 使用子模块需在父模块中注册，形式通常为`initPkg_父模块名_子模块名()`
- main.js中默认插入了一个图标，点击图标后展开功能面板。此处为底层设计好的，请慎改
- common.js为一些公共函数，是每个模块都可能会用到的。

### 维护（增加新功能）
1. 在packages内新建一个新的目录作为模块名（大驼峰）
2. 目录下新建相应的js与css文件
3. 每个模块应该有相应的入口函数（初始化函数）提供给main.js引用注册。
- 入口函数形式【initPkg_模块名】
- 每个模块向外暴露的变量需要写好注释并放在最前面
- **新增功能的icon的svg的style必须有display:block;父元素a的class要带上ex-panel__icon**
- 例如`<a class="ex-panel__icon"><svg style="display:block;"></svg></a>`或者`<a class="ex-panel__icon"><img/></a>`
- 每个模块保存的数据名字以 ExSave_ 开头 例如ExSave_BarrageLoop
4. 编写时注意不要污染其他模块或对其他模块有所影响
5. 模块中的子模块处理方式同主模块。
- **详细可参考模仿已经编写好的模块包**

### 编译
1. 将所有package的css内容依次复制到main.js的initStyle里
2. 在main.js下的initPkg函数中依次注册所有的模块，例如`initPkg_BarrageLoop();`
3. 将package下所有模块的js代码复制到main.js下
4. 全部完成后保存，复制到油猴脚本中去。
- **可以使用文件夹中自带的编译器，编译器将依据上述规则自动生成main.js**

### 更新
1. 修改头文件里的version
2. 修改Update模块包里的version
3. 编译发布