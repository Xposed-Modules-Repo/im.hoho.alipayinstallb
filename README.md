# 支付宝装X模块 (Alipay install B module)

## 当前功能 (Feature)

Xposed module for Alipay App which makes your barcode payment interface same as Diamond members or customized skins.

它可以让你的支付宝付款背景为黑色钻石会员样式或自定义皮肤。

## 更新注意 (Notice)

v2.4.0-beta 仅增加自定义皮肤功能，且无界面操作，不需要该功能无需从v2.3.0更新。

## 自定义皮肤说明 (for 2.4.0 Beta version)
- 更新装X模块2.4.0版本。
- 手动下载DEMO资源包，放入SD卡根目录既可。(**[SD CARD]**\000_HOHO_ALIPAY_SKIN)

命名|所属目录|含义|是否目录|手动创建|作用后文件消失
---|---|---|---|---|---
actived|000_HOHO_ALIPAY_SKIN|开启自定义皮肤功能|随意|是|否
update|000_HOHO_ALIPAY_SKIN|触发支付宝增量自定义皮肤缓存|随意|是|是
delete|000_HOHO_ALIPAY_SKIN|触发支付宝删除自定义皮肤缓存|随意|是|是
任意名称目录|000_HOHO_ALIPAY_SKIN|自定义皮肤文件夹|是|是|否
任意名称文件|000_HOHO_ALIPAY_SKIN|无作用|否|是|否

> 通常情况下，创建 update文件 时，请同时创建 delete文件 干净清除。

> 触发仅在展示二维码时有效，使用手动触发机制非自动为避免频繁IO操作影响目标程序。

> 自定义皮肤开启后，账号皮肤数据不会被修改或影响，仅本地切换。

> 多个皮肤之间随机数切换，没有去重，看你手机心情展示。

内容|所属目录|含义
---|---|---
z01.0001|皮肤子目录|付款码背景
z02.0001|皮肤子目录|付款码卡头背景颜色
z02.0002|皮肤子目录|付款码卡头中间logo
z02.0003|皮肤子目录|付款码卡头右侧水印

***资源包已经包含3个作者画的DEMO与简单的PSD文件，请自行研究。***

<a href="https://raw.githubusercontent.com/nov30th/AlipayHighHeadsomeRichAndroid/master/images/IMG_20220107_085600.jpg"><img src="https://raw.githubusercontent.com/nov30th/AlipayHighHeadsomeRichAndroid/master/images/IMG_20220107_085600.jpg" height="600" /></a>
<a href="https://raw.githubusercontent.com/nov30th/AlipayHighHeadsomeRichAndroid/master/images/IMG_20220107_085742.jpg"><img src="https://raw.githubusercontent.com/nov30th/AlipayHighHeadsomeRichAndroid/master/images/IMG_20220107_085742.jpg" height="600" /></a>
<a href="https://raw.githubusercontent.com/nov30th/AlipayHighHeadsomeRichAndroid/master/images/IMG_20220107_085805.jpg"><img src="https://raw.githubusercontent.com/nov30th/AlipayHighHeadsomeRichAndroid/master/images/IMG_20220107_085805.jpg" height="600" /></a>
<a href="https://raw.githubusercontent.com/nov30th/AlipayHighHeadsomeRichAndroid/master/images/IMG_20220107_085719.jpg"><img src="https://raw.githubusercontent.com/nov30th/AlipayHighHeadsomeRichAndroid/master/images/IMG_20220107_085719.jpg" height="600" /></a>

【作者自用模块】
