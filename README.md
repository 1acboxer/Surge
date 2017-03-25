# Surge.conf / Shadowrocket.conf

* 自动代理 / 全局代理
* 解决本地 DNS 可能带来的干扰
* 可突破部分内网限制（公司、学校）
* 拦截常用应用程序的行为分析
* 拦截常用应用程序的数据统计
* 拦截常用应用程序的隐私跟踪
* 拦截各大购物网站的运营商劫持
* 屏蔽部分应用程序的启动广告
* 屏蔽部分运营商劫持网页弹出的流量统计
* 屏蔽部分运营商劫持网页弹出的漂浮球广告
* 屏蔽常用视频广告
* 屏蔽常用网站广告、其他流媒体网站广告
* 所有国内网站直线连接
* Apple 服务加速（App Store、Apple Music、Apple流媒体、iCloud备份、iCloud Drive、iTunes 等）
* 国外常用网站加速（Google/Youtube/Twitter/Facebook/instagram/wikipedia/Github 等）

♻️ Download

    Surge：https://raw.githubusercontent.com/lhie1/Surge/master/Surge.conf
    
    Shadowrocket：https://raw.githubusercontent.com/lhie1/Surge/master/Shadowrocket.conf

    Hosts：https://async.be/Rule/Basic/Hosts.php
    （免服务器 / 自动更新 ／ 支持 google、instagram、twitter 等主流外网）

    Telegram：https://telegram.me/surgenews
    （新内容发布 ／ 更方便快捷获取更新内容）
    
    更新日志：https://raw.githubusercontent.com/lhie1/Surge/master/more/New

🈲️ 浏览器广告

    全平台：Adguard - https://adguard.com/en/welcome.html

    Safari for macOS：JS Blocker - https://safari-extensions.apple.com/details/?id=com.toggleable.JavaScriptBlocker5-6S8J5HV3H4
    

🆙 一键生成 / 更新（Workflow）

    https://workflow.is/workflows/8e57208a2ef3443292af96cbfe73fd04

    单节点版（特）：https://workflow.is/workflows/83007c0c0e62458daaee3564d6bffab2 （不再更新）


🆙 自动更新（示范）

    单节点：https://async.be/Rule/Advanced/Surge?List=https://raw.githubusercontent.com/lhie1/CloudGate-List/master/Rule/&AutoGroup=false&Rule=false&Apple=false&IPV6=false&Group=1&SERVER1=ServerName,custom,127.0.0.1,80,rc4-md5,Password&DNS=false&AGENT=false

    多节点：https://async.be/Rule/Advanced/Surge?List=https://raw.githubusercontent.com/lhie1/CloudGate-List/master/Rule/&AutoGroup=false&Rule=false&Apple=false&IPV6=false&Group=2&SERVER1=ServerName,custom,127.0.0.1,80,rc4-md5,Password&SERVER2=ServerName,custom,127.0.0.1,80,rc4-md5,Password&DNS=false&AGENT=false
    
    参数详解：https://manual.async.be/AdvancedRule.html


# more

🔰 客户端（有“R”标示表示支持 SSR）：

    * iOS
    
        Surge：https://appsto.re/cn/D0Q_9.i
        
        Shadowrocket (R)：https://appsto.re/cn/UDjM3.i
        
        Wingy (R)：https://appsto.re/cn/19xBeb.i
        
        Potatso (R)：https://appsto.re/cn/OIk1_.i
        
    * Android
    
        ShadowsocksR (R)：https://github.com/shadowsocksr/shadowsocksr-android/releases
        
        Postern (R)：http://www.tunnel-workshop.com
        
    * macOS
    
        ShadowsocksX：https://github.com/shadowsocks/shadowsocks-iOS/releases

        ShadowsocksX-R (R)：https://github.com/yichengchen/ShadowsocksX-R/releases

        ShadowsocksX-NG (R)：https://github.com/qinyuhang/ShadowsocksX-NG/releases
        
        Flora：https://github.com/huacnlee/flora-kit

        Specht Lite：https://github.com/zhuhaow/SpechtLite/releases
        
        Surge：http://nssurge.com
        
    * Windows
    
        ShadowsocksR (R)：https://github.com/shadowsocksr/shadowsocksr-csharp/releases
        

📋 教程 / 说明：

        Surge for iOS：https://medium.com/@scomper/surge-配置文件-a1533c10e80b#.9fpdjn34f
    
        Surge for macOS：https://medium.com/@scomper/surge-for-mac-简明指南-f6f357b8f09c#.n55zdnvnd
    
        Shadowrocket for iOS：http://matrix.sspai.com/p/c113cba0
    
        SSR for Windows：https://ocvpn.wordpress.com/2016/10/15/shadowsocksr-for-windows设置教程
    
        SSR for Android：https://yhyy135.github.io/how-to-use-ssr-android/
    
        Specht Lite for macOS：https://github.com/zhuhaow/SpechtLite/wiki/如何配置Specht-Lite
    

# line

*** | Raw |
---------|:---------:
LHIE1| [翻墙服务](https://item.taobao.com/item.htm?spm=686.1000925.0.0.nxFmSh&id=524385498809)
ss.lhie1| [翻墙服务](https://ss.lhie1.com)
新浪微博 | [ @lhie1](http://www.weibo.com/1748625493)
Telegram | https://telegram.me/lhie1x


# Q&A

### ☁️ Proxy & 🔰 Proxy

    ☁️ Proxy ： 直连 / 代理服务器(选择 [🌍 Direct] 为 直连，选择 [其他] 则通过 代理服务器 访问)

    🔰 Proxy ： 自动代理 / 全局代理(选择 [🌍 Direct] 为 智能分流 (Pac) ，选择 [☁️ Proxy] 即为 全局代理 )

    如果 ： [☁️ Proxy] 、 [🔰 Proxy] 都选择 代理服务器 ，则为全局代理。

    建议 ： ☁️ Proxy - 代理服务器 、🔰 Proxy - 🌍 Direct 



#### 🚀 SSR 混淆模式 https://github.com/breakwa11/shadowsocks-rss/blob/master/ssr.md

    理论上开启混淆模式的时候可以利用混淆做到乱序大小的发送和接收，至少可以在某种程度上可以避开GFW的探测，那就应当会获得更好的速度、稳定性以及安全性。



#### 🔋 Surge for iOS 耗电

    Surge 会接管全局的（几乎）所有通信，所以所有的网络方面电量消耗都会被算在 Surge 头上，实际使用中不会感到 Surge 对电量有明显影响。



#### ☑️ Set as System Proxy

    启用 Surge for Mac 后勾选下拉菜单中的 Set as System Proxy 即可自动向系统网络设置添加必要的参数，因为需要修改系统网络设置，首次勾选时需要输入管理员密码进行确认，去掉 Set as System Proxy 的勾选，会清除网络设置中的代理相关设置。



#### 📶 Surge for iOS 开启共享模式 https://medium.com/@scomper/局域网其他设备共享上网-dd29e18853da#.6w19tdsh9

    Surge 在增加了代理共享模式，只需要开启就能让 Wi-Fi 网络中的其他设备通过这台 iPhone 代理访问网络。
    到高级设置中开启 Allow Wi-Fi Access ，或者直接修改配置文件，添加一行参数 allow-wifi-access = true。

    其他 Wi-Fi 网络环境下的设备可以输入已经开启共享代理的 Surge 设备的 IP 地址和端口号，（技巧：Surge Log 中能看到开启后本机的 IP 地址和监听端口）将 IP 地址填写到需要共享设备的 Wi-Fi 信息的 HTTP 代理里即可。



#### 🏃 Auto / Benchmarik

    测试结果仅供参考，无法检测出 VPS 的带宽

    请不要使用 google.com 作为测试目标，有可能导致 proxy 服务器 ip 被加入黑名单，导致各种操作需要输入验证码。
    目标 URL 对所有的 policy 是基本公平的，所以请选择像 gstatic.com 这样的在全球都有节点的 URL 作为测试目标。
    作者建议：http://www.gstatic.com/generate_204



#### 🍎 Apple DNS （Apple 服务加速） http://t.cn/RcgOudi

    Apple DNS 通过收集 Apple 在全中国几乎所有省级行政区的 CDN IP 列表，解决 App Store / Mac App Store / iTunes Store / Apple Music / iBooks / TestFlight 在中国部分地区速度缓慢的问题。

    ChinaNet：电信宽带专用
    ChinaUnicom：联通宽带专用
    auto(原 CMCC)：电信、联通、移动 三网通用

    电信、联通宽带用户可以自行按照教程生成最适合自身网络环境的 CDN IP 列表，移动宽带用户或嫌麻烦的用户使用 auto 列表即可。

    Apple DNS参考：

    [Host]
    // Apple DNS

    // China Net (中国电信)
    # API-1-ChinaNetCenter [ChinaNet] (Avg RTT: 9.772ms)
    se.itunes.apple.com = 222.211.64.122
    su.itunes.apple.com = 222.211.64.122
    upp.itunes.apple.com = 222.211.64.122
    play.itunes.apple.com = 222.211.64.122
    client-api.itunes.apple.com = 222.211.64.122
    # API-2-ChinaCache [ChinaNet] (Avg RTT: 15.339ms)
    itunes.apple.com = 125.65.247.14
    init.itunes.apple.com = 125.65.247.14
    # API-HK-Akamai-1 [HongKong0] (Avg RTT: 52.706ms)
    search.itunes.apple.com = 184.87.97.50
    # API-HK-Akamai-2-AMRadio [HongKong1] (Avg RTT: 58.221ms)
    radio.itunes.apple.com = 184.87.100.246
    radio-activity.itunes.apple.com = 184.87.100.246
    radio-services.itunes.apple.com = 184.87.100.246
    # Apple Music Streaming [ChinaNet-ChinaCache] (Avg RTT: 10.465ms)
    aod.itunes.apple.com = 139.206.198.9
    mvod.itunes.apple.com = 139.206.198.9
    streamingaudio.itunes.apple.com = 139.206.198.9
    # Beats 1 Radio (Not Available in Mainland China) [Malaysia] (Avg RTT: 90.211ms)
    itsliveradio.apple.com = 202.76.239.11

    // China Unicom （中国联通）
    apps.itunes.apple.com = 60.213.22.72
    beta.itunes.apple.com = 23.42.189.88
    client-api.itunes.apple.com = 60.213.22.72
    init.itunes.apple.com = 111.161.121.26
    itunes.apple.com = 111.161.121.26
    itunesconnect.apple.com = 111.161.121.26
    play.itunes.apple.com = 60.213.22.72
    radio.itunes.apple.com = 104.115.242.174
    radio-activity.itunes.apple.com = 104.115.242.174
    radio-services.itunes.apple.com = 104.115.242.174
    s.mzstatic.com = 111.161.121.26
    se.itunes.apple.com = 60.213.22.72
    search.itunes.apple.com = 111.161.121.26
    su.itunes.apple.com = 60.213.22.72
    upp.itunes.apple.com = 60.213.22.72

    // CMCC （中国移动）
    apps.itunes.apple.com = 111.62.245.9
    beta.itunes.apple.com = 23.198.133.66
    client-api.itunes.apple.com = 111.62.245.9
    init.itunes.apple.com = 183.222.99.115
    itunes.apple.com = 183.222.99.115
    itunesconnect.apple.com = 183.222.99.115
    play.itunes.apple.com = 111.62.245.9
    radio.itunes.apple.com = 23.50.28.36
    radio-activity.itunes.apple.com = 23.50.28.36
    radio-services.itunes.apple.com = 23.50.28.36
    s.mzstatic.com = 183.222.99.115
    se.itunes.apple.com = 111.62.245.9
    search.itunes.apple.com = 183.222.99.115
    su.itunes.apple.com = 111.62.245.9
    upp.itunes.apple.com = 111.62.245.9


# License

* 可以拷贝、转发，但是必须提供原作者信息，同时也不能将本项目用于商业用途。
