# COLORFUL-P15-23-EFI
基于七彩虹隐星p15 23的黑苹果efi
注意注意⚠️
此efi并未给其他人测试 属于小白个人使用+ai协作钻研 不保证100%开机
⚠️⚠️⚠️
如果有其他更好的方案愿意分享的话也可以推送到这里，非常感谢

使用1401创建efi，后续和ds老师沟通寻找驱动和修复方案（操作都是我手操，d老师告诉我怎么做）
笔记本配置如下
<img width="1165" height="799" alt="无标题" src="https://github.com/user-attachments/assets/5aa89956-860e-4d5f-a8aa-9fc1f81e62b5" />
非同机型同cpu+gpu可以试试，我是在1401的网站上看到了华硕同显u成功开机了，觉得这个有戏才做的尝试。因为这个型号太冷门了
（之前要个原厂镜像都要不到）
同系列机型非同cpu，gpu需要修改部分内容，要改啥不确定。因为有个p1523，但是是i5+4050的盆友用我的efi就开不了机

开机效果
<img width="1181" height="717" alt="f28f0b54df3afe6acdc4109db256e731" src="https://github.com/user-attachments/assets/067f50ab-4b63-4110-920b-6259e1bb3018" />

可用：
gpu
蓝牙（蓝牙音频可用，解码协议未知，懂得不多）
<img width="508" height="638" alt="截屏2026-10-25 19 33 14" src="https://github.com/user-attachments/assets/5e7da711-b57a-4df6-8d63-44c8a65ec3ee" />

Wi-Fi
（因特尔网卡不太兼容，在开机后需要用OCLP-MOD给驱动打补丁 还需要先伪装后安装 wifi6正常使用）
<img width="296" height="450" alt="截屏2026-10-25 19 34 13" src="https://github.com/user-attachments/assets/31d0c28b-8219-499b-a4e3-cf9e825cb575" />

隔空传送（单向只能发不能收 原因同英特尔）
<img width="368" height="270" alt="截屏2026-10-25 19 36 11" src="https://github.com/user-attachments/assets/bd8eb8b1-19e9-4856-9173-f9e2cb4ba380" />

键盘/触控板/usb/摄像头/麦克风/扬声器（内置和外接）

不可用（我修不好的）：
屏幕镜像
隔空传送半残，不完整体验
🔋（脱电使用会减电量，但是要时间刷新，并且充电时无法识别到在充电）
风扇控制 显示器亮度调节
核显：听说已经有相关驱动了，不过因为刚出可能问题比较多就没整

使用一段时间后关于本机打不开，看起来无伤大雅。但是不太懂怎么回事。重启后正常
<img width="730" height="635" alt="截屏2026-10-25 19 44 25" src="https://github.com/user-attachments/assets/2d497205-5fbc-4871-a871-51d5cca6f8d1" />

目前暂时发现这些，更复杂的我现在也暂时没能力优化

另外需要注意⚠️
七彩虹这个型号的笔记本bios大概率是阉割版的，可能需要破解。我当时因为有个开关需要开，但是bios没有设置才去刷bios
此操作有风险。如果能够接受可以去B站找教程

谢谢各路大佬开源，让我也第一次用上macos🙏



