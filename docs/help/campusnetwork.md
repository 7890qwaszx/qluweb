<!-- markdownlint-disable MD033 -->

# 齐鲁工大校园网常见问题一览

## 新生、教职工开通校园网

齐鲁工业大学校园网由网络信息中心管理，如您需要开通校园网，请根据对应角色进行操作。

- 在校本科生

    请前往校内移动校园网服务中心获取最新套餐及资费。

- 在校研究生

    我校为在校研究生提供办公区及教学区的校园网使用权限
	
	账号为学号，初始密码为身份证号后 6 位。

- 在职教职工

    我校为在职教职工提供办公区及教学区的校园网使用权限

    账号为工号，初始密码为身份证号后 6 位。

有任何疑问，可致电网络信息中心 [0531-8963135](tel:(0531)89631358)。

---

## 连接校园网

### 选择接入方式

校园网覆盖所有校区，提供 **有线/无线** 两种接入模式，同学们可自行选择合适的方式进行接入。

- 有线接入

    该接入方式网络带宽较大、延时较为稳定，应当是您首选的接入方式。

    如选择该种接入方式，您可自行寻找楼宇内的有线网络接口或 AP(Access Point，无线接入点) 尾部的局域网络接口 (RJ45)，并使用网线连接上网设备。

    AP 设备通常布置在教室的天花板一角、宿舍门的正上方或桌子的背后。

    宿舍内的有线网络接口通常出现在下铺床底处的墙壁、柜子的背后、进门处的墙壁。

    目前我校在教学楼区域采用的 AP 设备主要是锐捷 RG-AP730-I 
	
    <center class="half">
    <img src="/img/wireless-rg-ap730-i_ad3889a4fd0b4535a126a42e41393468.webp" width=40% />
    </center>
	
    在宿舍里采用的 AP 设备主要是 RG-MAP752(G) 和 RG-AP130(L)
	
    <center class="half">
    <img src="/img/752.jpg" width=40% /><img src="/img/wireless-rg-ap130(l) v2_284ee7cc20d3407daa856663319ea6c6.webp" width=40% />
    </center>

- 无线接入

    该接入方式网络带宽较小、延时会有抖动、但连接较为方便。

    若选择该种接入方式，请使用带有 WiFI 功能的上网设备，查找名称为**QLU-2.4G**或**QLU-5.8G**的 WiFi 信号并连接。

---

### 进行上网认证

无论您选择哪种方式接入校园网，都需要进行认证才可以正常访问网络。

当您连接到校园网后，正常情况下，设备会弹出如下图所示的认证页面。
    <center class="half">
    <img src="/img/rzjm.jpg"/>
    </center>
在页面中输入您的学号（或工号）、密码（初始密码为身份证后 6 位）并选择 **互联网** 即可认证。

如果连接网络后一段时间没有弹出认证界面，请手动进入 [172.20.255.1:9090](http://172.20.255.1:9090/) 进行认证。

在登陆成功后的页面等待几分钟后刷新，可以激活免密无感认证的选项。该功能依赖设备的 MAC 地址来进行身份识别，需要关闭上网设备的 `私有局域网地址`、`随机MAC地址` 等功能才能正常使用。

若您因科研或办公需要，希望在机房、实验室、办公室等位置部署免认证接入校园网的路由器、服务器等终端设备，请拨打网络信息中心值班电话 [0531-89631358](tel:(0531)89631358)

---

## 修改校园网密码

校园网密码默认为身份证号后 6 位，如您需要修改密码，请访问 [校园网自助服务系统](http://172.17.21.111:8080) 进行修改。

---

## 绑定校园网无感认证

无感认证是指将您的上网设备与校园网账号进行绑定，无需手动进行操作即可自动认证上网。

如需开启此项服务，请在校园网登录后刷新登录页面，点击左上角的“开启本机无感认证”即可。

<center class="half">
<img src="/img/xywwg.png"/>
</center>

---

## iOS/iPadOS系统锁屏断网问题

1. 在当前连接的 WiFi 里打开“自动加入”，关闭“自动登录”。

2. 方法二：打开蜂窝网络，将 WiFi 助理关闭（若 WiFi 助理为灰色，打开数据网络即可关闭）。

3. 方法三：IOS14.01 及以上系统版本，请打开 WiFi 设置里面的“自动加入”，关闭“私有地址”和“自动登录”。

---

## 移动融合用户进行移动融合绑定时无法绑定

请前往“菁彩校园”微信公众号留言或拨打 [4007005199](tel:4007005199) 联系人工客服处理。

---

## 缴费后仍提示余额不足

移动融合用户确认是否进行移动融合绑定，未绑定的校园网用户请绑定后再用。

---

## 校园网经常掉线，需要频繁认证

- 请尝试前往 [校园网自助服务系统](http://172.17.21.111:8080) 修改校园网密码。
- 如仍未解决，请联系网络信息中心 [0531-89631358](tel:(0531)89631358)

---

## WiFi 显示感叹号，无法上网

- 请检查登录是是否选择互联网。

- 如果是没有登录页面，请使用下方手动触发登录页面的方式。

    1. 尝试在浏览器地址栏输入 [172.20.255.1:9090](http://172.20.255.1:9090/) 进行认证

    2. 尝试关机重启系统

    3. 查看网络设置中 DNS 与 IP 地址是否为自动获取，若不是，请改成自动获取。若还不弹登陆页面，检查一下浏览器是否设置拦截功能，关闭拦截重试。

如果仍未解决，请拨打网络信息中心值班电话 [0531-89631358](tel:(0531)89631358)，值班人员会尽快处理

---

## 提示账号被暂停，请先恢复

- 如您是在校内营业厅办理的校园网业务，请咨询营业厅处理；

- 如您是在菁彩校园微信公众号缴费办理的校园网业务，请拨打 [4007005199](tel:4007005199) 客服电话咨询。

- 如您是在校教职工、研究生，请拨打网络中心值班电话 [0531-89631358](tel:(0531)89631358) 值班电话咨询。

---

## 认证设备响应超时

- 请检查办理校园网手机号是否停机，如未停机请拨打运营商客服电话刷新宽带网络，账号报办理校园网的手机号即可。

---

## 提示不允许在该地区接入

- 请确认是否在菁彩校园微信公众号缴费成功。

- 如在移动营业厅办理校园网业务，请确认是否已经在菁彩校园微信公众号移动融合绑定成功，缴费或绑定成功后，登录选择互联网即可上网。

---

## 没有预留有效的手机号码或输入号码非预留号码

- 请核对在进行融合套餐绑定时的手机号码或者购买自营套餐时的手机号码和当前输入号码是否一致，学号输入是否正确。

- 如服务仍不可用，请拨打 [4007005199](tel:4007005199) 客服电话咨询。

- 如您是在校教职工、研究生，请拨打网络中心值班电话 [0531-89631358](tel:(0531)89631358) 值班电话咨询。

---

## 认证设备响应超时

- 请检查办理校园网手机号是否停机，如未停机请拨打运营商客服电话刷新宽带网络，账号报办理校园网的手机号即可。

---

## 提示不允许在该地区接入

- 请确认是否在菁彩校园微信公众号缴费成功。

- 如在移动营业厅办理校园网业务，请确认是否已经在菁彩校园微信公众号移动融合绑定成功，缴费或绑定成功后，登录选择互联网即可上网。

---

## 没有预留有效的手机号码或输入号码非预留号码

- 请核对在进行融合套餐绑定时的手机号码或者购买自营套餐时的手机号码和当前输入号码是否一致，学号输入是否正确。

- 如服务仍不可用，请拨打 [4007005199](tel:4007005199) 客服电话咨询。

- 如您是在校教职工、研究生，请拨打网络中心值班电话 [0531-89631358](tel:(0531)89631358) 值班电话咨询。

---

## 苹果手机连接不上网络，不出现 WiFi 图标

1. 还原网络，设置 - 通用 - 还原 - 还原网络设置。

2. 取消自动登录，手动打开浏览器进行重定向认证，具体操作方法百度即可。

---

## 账号被列入黑名单/代理软件

- 根据相关法律法规，校园网不允许使用路由器、信号桥、360WiFi、猎豹 WiFi、VPN、手机热点、虚拟机、手游助手、加速器、模拟器等各种代理或网络共享工具；

- 请不要开启手机上的双 WiFi 加速和 WiFi+ 功能，否则账号就会被加入黑名单，2h 后自动恢复。

- 请自觉遵守相关法律法规，文明上网
