# chatgpt商业版带支付功能，会员注册（程序不断更新中），已加入AI绘画功能
#体验地址：https://pps.xxzgxq.top
#本项目主要是API调用，可部署在国内服务器上。无需CF
#环境部署：5.7SQL+7.3PHP
#项目联系Q群：219645597

V5.0.8 （6月28日）
其它细节优化
修复网站首页有时候会直接显示白屏未授权
修复前面几个版本导致的余额已到期但不自动轮询删除KEY的BUG

V5.0.7
新增Ai回答后的AD广告 后台自定义设置链接和文字
V5.0.6（6月26日）
网站后台优化
新增提问数据清理功能
其它细节优化
修复部分未知BUG

5.0.5（6月25日）
新增自定义GPT回答多少秒后超时自动重连

V5.0.4
紧急修复上一个版本导致的上下文超限提示失效BUG
新增网站公告标题自定义设置功能 后台公告设置里面修改
修复网站公告如何内容太长超出屏幕限制BUG
新增网站基本配置模块 例如首页"使用示例"板块放到数据库了 修改内容更新后不受影响
重写轮询KEY逻辑
修复轮询KEY明明没有用完余额有时候会误删的BUG
新增GPT提问若3秒没出答案则自动重连

V5.0.3 (6月24日)
修复GPT回复随机选temperature参数不生效BUG
优化log.php提问数据改回log.txt 因为PHP文件执行效率没有TXT文本快
修复log.txt数据量太大时会导致提问卡住BUG 改为6小时自动清空一次 然后数据备份到Chat目录
新增GPT3.5和GPT4.0 log.txt提问数据记录区分开来
其它代码细节优化 GPT回复更加流畅 性能大幅度提升
彻底关闭数据传输时使用Session 防止服务器卡顿

V5.0.2
新增提问超过30秒未回复自动超时刷新网页
紧急修复5.0.1导致的后台首页BUG
V5.0.1 （6月23日）
新增后台卡密列表显示卡密被哪位用户使用
新增后台用户列表显示手机号
新增绘画广场图片点击放大功能
新增绘画广场图片描述复制功能
修复未开启手机号注册时用户用手机号当用户名注册后无法登录BUG
修复第一次登录账号后需要刷新网页侧边栏的头像才会显示正常BUG

V5.0.0
新增GPT4.0不自动删KEY设置 防止用了第三方平台API误判
优化GPT回复最大超时为1200000秒 防止回复内容太长导致的超时
修复后台KEY余额查询不准确BUG
新增后台KEY余额查询错误提示
新增Prompt角色数据修改
新增订单记录显示充值类型
其它细节优化

V4.9.9
AiChat面具模式角色板块UI优化 新增动态阴影效果(白天模式下才看得到效果)
修复查询余额失效 之前的反代地址API挂了 换了一个域名
新增自定义MJ出图是否存储你自己服务器本地

V4.9.8（6月19日）
新增绘画页面图片懒加载功能 防止网页卡顿
修复手机端绘图页面翻译按钮被遮挡BUG
新增MJ绘画新通道 比之前的稳定 后台切换即可
修复部分特殊情况下邀请不返佣金BUG
优化服务器Session导致的GPT回复并发卡顿问题
修复Prompt页面退出登陆后第二次登陆提示账号被占用BUG

V5.0.1 （6月23日）
新增后台卡密列表显示卡密被哪位用户使用
新增后台用户列表显示手机号
新增绘画广场图片点击放大功能
新增绘画广场图片描述复制功能
修复未开启手机号注册时用户用手机号当用户名注册后无法登录BUG
修复第一次登录账号后需要刷新网页侧边栏的头像才会显示正常BUG

V5.0.0
新增GPT4.0不自动删KEY设置 防止用了第三方平台API误判
优化GPT回复最大超时为1200000秒 防止回复内容太长导致的超时
修复后台KEY余额查询不准确BUG
新增后台KEY余额查询错误提示
新增Prompt角色数据修改
新增订单记录显示充值类型
其它细节优化

V4.9.9
AiChat面具模式角色板块UI优化 新增动态阴影效果(白天模式下才看得到效果)
修复查询余额失效 之前的反代地址API挂了 换了一个域名
新增自定义MJ出图是否存储你自己服务器本地

V4.9.7（6月19日）
部分细节优化
新增后台自定义是否开启用户邀请分销功能
修复输入框自动执行JS代码BUG
新增Ai绘画广场 后台自行添加图片数据 需要竖屏尺寸的
其它细节优化

V4.9.6 (6月18日)
修复新弹窗邀请窗口复制邀请链接失效BUG
修复代码块无法复制BUG

V4.9.5
修复GPT4密钥失效后不自动删除的问题
修复只允许一台设配同时登录很多BUG
修复GPT4注册赠送次数不生效BUG
优化侧边栏邀请好友按钮UI样式
重写邀请好友分销页面UI样式 已改为弹窗形式的


V4.9.4（6月14日）
新增自定义GPT3/4模型名称功能 更新为最新GPT0613
优化GPT4退出登陆后不跳转GPT3.5的页面
新增卡密会员天卡套餐 可以生成1天会员的短期卡密
新增只允许一台设配同时登录使用

V4.9.3（6月12日）
修复4.9.0版导致的前台邮件注册发送不成功BUG
优化不开启网站收费的时候首页不显示开通会员按钮
新增GPT回复语速自定义配置
优化查看源代码HTML代码压缩至一行
修复后台账户密码被Log日志的TXT文档明文记录漏洞
新增绘画页面输入框内容点击按钮翻译功能 对接的国外API 国内服务器不可用

V4.9.2
新增Msql Log日志开启或关闭功能 后台配置
新增短信可自定义签名和模板内容
修复暗黑模式下Prompt页面UI颜色不兼容问题
新增写网站统计代码功能 后台配置
新增后台首页自动检测新版本功能 可自定义开关
新增更新页面自动显示新版下载链接(若有新版才会显示)

V4.9.1 （6月8日）
优化每次提问都重复查询反代链接 提高GPT一定的回复速度
修复点击中止按钮后第二次提问卡顿的BUG
大量JS细节优化 体验更加流程 提速百分之15左右
新增Prompt面具角色扮演功能 后台自定义添加 用户也可自定义添加

V4.9.0
关闭注册时的重复密码输入
新增手机验证码登录功能 后台配置AppCode密钥
优化用户名和邮箱可以通用登录
修复后台提问列表XSS漏洞

V4.8.9（6月1日）
修复手机端客服图片尺寸超出BUG
修复找回密码无法发送邮件BUG
优化联系客服弹窗UI样式
首页重新添加免责声明按钮 后台可自定义设置链接地址
新增文章资讯功能 后台发布

V4.8.8（5月31日）
新增后台自定义语音输入功能开启或者关闭
首页导航栏新增更多功能按钮
新增网站反馈建议标题提交功能 后台可查看内容

V4.8.7（5月29）
新增GPT3.5和GPT4.0连续对话区分开来设置
新增ChatGPT官网绘画 跟GPT3.5提问密钥通用的
修复代码块左右滑动导致复制按钮错位BUG
新增语音输入功能 网页必须HTTPs协议才可以使用

V4.8.6(5月27）
修复4.8.4版本造成的支付回调页面不正确BUG
修改首页ChatGPT名称为Chat机器人
优化用户列表显示GPT4和绘画的剩余次数
新增后台用户列表搜索功能
修复Ol有序列表白天模式下显示不出来
新增代码块单独复制按钮
新增用户签到功能

V4.8.4(5月23日）
优化绘画报错提醒
修复4.8.3导致的卡密充值错误BUG
新增后台可以自定义用户的GPT4.0使用次数
新增更新后自动清理静态文件缓存
新增引流卡密类型 防止一个用户使用了全部卡密

V4.8.3 (5月22日)
修复绘图套餐特殊情况下自动新增套餐数量BUG
优化意间和MJ绘图非法元素报错提醒
修复卡密页面充值不通用BUG
恢复意间绘画 可以和MJ切换使用
新增对接ChatGPT4.0 需要4.0的KEY才可以用

V4.8.1
新增ChatGPT初始预设值后台可以自定义修改和删除
新增后台可以自定义修改用户密码功能
优化网站公告内容到数据库 只需要重新修改最后一次公告 下次就不需要每次都需要了
修复4.8.0版本导致的连续对话顺序不正确BUG 重大BUG 务必更新
修复一个COOKIE BUG 数据太多网站会出现400报错
新增电脑端网站前台自定义快捷键发送切换 可以Enter直接发送了

V4.8.0（5月19日）
调整ChatGPT回复随机性为0.8参数
新增判断是否指定PHP7.3版本运行 如果不是请切换版本
新增程序在线安装功能
优化复制按钮手机端有点错位的问题
修复上下文长度超限BUG
指定一个ChatGPT3.5的初始设定

V4.7.9 (5月18日)
优化手机端提问体验
修复手机端提问字数过多遮挡按钮BUG
优化复制按钮图标上下左右不对成
优化OL有序标签显示数字序列
新增赞助功能 赞助按钮显示在Ai的答复里面 可自行开启关闭
修复一个订单提交小BUG
修复购买套餐页面不需要登陆也可以访问BUG
修复后台付费用户不正确BUG
修复前台用户开通会员后仍然显示升级会员字样BUG

V4.7.8
优化公告弹出必须点击"我记住啦"才可以关闭 防止用户误触没看到公告
优化手机端输入框有时候不下滑BUG
修复后台KEY密钥自动增加BUG
新增是否开启前台客服按钮开关
新增回答复制功能

#V4.7.7
修复少部分密码注册后无法登录的BUG
新增QQ/微信内打开跳转浏览器提示页 可自行开启关闭

V4.7.6
修复数据库用户密码明文加密后导致的修改密码失效BUG
优化代码结构 提高加载速度
新增网页加载效果
新增客服弹窗
对齐导航栏图标

V4.7.5
新增用户自助找回密码功能 需要对接邮箱
优化邮箱发送被刷风险 现已改为1分钟只允许发送一次
优化触发违禁词之后无法终止对话只能刷新的问题
新增图片点击放大功能

V4.7.4
继续优化输入框发送速度 提问更加丝滑 4.7.3版还是有点小BUG
优化用户未注册免费次数用完后按钮恢复成待发送状态

V4.7.3
紧急修复一个绘画4.7.2导致的无限提问绘画BUG
优化用户开通会员后首页显示尊贵会员
修复后台今日收入显示不正确BUG

V4.7.2
新增后台批量查KEY余额
修复邮箱可反复注册的BUG
修复每个IP注册只允许注册一次无法拦截BUG
优化前端UI手机端小BUG
修复SQL语句执行错误
修复暗黑模式下QQ打开不兼容的问题
修复邮件注册只能给QQ邮箱发送邮件的BUG
新增后台可以更改用户绘画剩余次数
修复数据库用户注册后密码明文显示BUG
优化输入框发送速度

V4.7.1
新增绘图功能
新增用户IP封禁 用来封一些白嫖党 禁止访问网站
修复邮件配置后 后台测试成功 前台发送不成功的BUG
隐藏购买套餐页面显示用户名
添加购买套餐弹出提示:虚拟商品不允许退款 防止因为有些人买了来退款
删除首页登录窗口输入用户名那的邮箱登录提示 邮箱实则不可以登录
新增API反代接口配置 配置好反代接口 国内VPS也可以搭建
新增后台可以一键查看KEY密钥剩余余额
修复暗夜模式输入框写入内容后顶部出现一个DIV挡住主页面
修复暗色模式切换BUG
修复特殊情况下用户提问不扣除次数的BUG
修复其它未知BUG

V4.7
优化系统注册登录的安全性
新增邮件发送注册
新增每个IP只能注册一次的返回提示
新增后台可以设置默认网站是白天还是暗黑模式
新增网站公告 界面UI很好看

V4.6
修复打开后台有点卡顿的问题
修复次数密钥可以无限兑换的BUG
前台对话增加头像 自动获取用户QQ头像
修复快捷键发送判断违禁词失效BUG
修复一个其它BUG
修复切换暗夜模式手机端导航不变色BUG

V4.5
优化鼠标光标网页加载卡顿一会
新增网页暗黑模式和白天模式随意更换
删除提问加载转圈圈 改为Ai正在思考中
彻底解决提问频繁问题 只要你多设置几个密钥即可 随机获取
新增卡密充值功能 后台可以设置开启和关闭 卡密在后台生成即可
新增用户邀请分销功能 分销比例后台可设置 也可以设置跳板域名 防屏蔽
新增对话保存 可以新增对话了 对话可删除修改名称
用户的到分销金额也可以设置多少可以体现 用户也可自行充值套餐
新增每个IP只能注册一次
新增违禁词 违禁词后台自己设置
优化前端界面UI细节
修复若干回调BUG
新增后台用户提问可查看

V4.4
新增注册用户赠送次数自定义
修复前端密钥明文

V4.3
优化首页加载CSS 之前加载的时候div块会往左边跑
代码安全性逻加强

V4.2:
修复41版本前端输入框换行被遮挡
优化key密钥获取机制 随机获取防止频繁

V4.0:
前端输入框重写
优化发送按钮
其它细节优化
修复部分版本的浏览器Ai回答文字显示不全
修复首页无法滑动问题

V3.9:
优化用户中心 新增用户中心footer页脚 新增用户中心右侧选项卡
新增用户中心用户可以更改密码
新增后台可以更改用户的提问次数和会员相关设置
新增后台可以更改管理员密码或账户
优化后台使其美观了一些
优化用户中心的列表显示 可以显示金额
新增用户中心可以显示用户的剩余次数和会员到期时间

V3.8:
新增后台一键自动更新
优化若干CSS
修复前端Ctrl+Cnter无视规则提交BUG

V3.2:
新增后台，所有配置都可以在后台设置
今日收入，付费用户，注册用户所有数据一目了然
新增支付配置，支付宝或微信自定义切换
新增免费试用次数自定义，默认1
新增关闭网站收费功能
新增套餐价格自定义后台修改
新增无限key轮询功能，后台自己导入
优化前端CSS，用户登陆后窗口可关闭
新增是否开启用户每日都有免费体验次数(默认关闭)
![QQ图片20230518100458](https://github.com/xt9058/chatgpt-shop/assets/117225908/990f4c63-5591-439d-bd39-5ba5fe3a2d2d)

![QQ图片20230518100517](https://github.com/xt9058/chatgpt-shop/assets/117225908/6c3c31b9-5ddf-40d1-af2e-f061425a6998)
![QQ图片20230518100453](https://github.com/xt9058/chatgpt-shop/assets/117225908/2f646ac3-472e-4394-8543-53a42f96f2a6)
