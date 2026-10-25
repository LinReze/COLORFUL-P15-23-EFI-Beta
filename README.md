<h1>COLORFUL-P15-23-EFI</h1>

<p>基于七彩虹隐星 p15 23 的黑苹果 EFI</p>

<div class="warning">
  <p><strong>注意注意⚠️</strong></p>
  <p>此 EFI 并未给其他人测试，属于小白个人使用 + AI 协作钻研，不保证 100% 开机。</p>
  <p><strong>⚠️⚠️⚠️</strong></p>
  <p>如果有其他更好的方案愿意分享的话也可以推送到这里，非常感谢。</p>
</div>

<p>使用 1401 创建 EFI，后续和 DS 老师沟通寻找驱动和修复方案（操作都是我手操，D 老师告诉我怎么做）。</p>

<h2>笔记本配置</h2>
<p>笔记本配置如下：</p>
<img
  src="https://github.com/user-attachments/assets/5aa89956-860e-4d5f-a8aa-9fc1f81e62b5"
  alt="无标题"
  width="1165"
  height="799"
>

<p>非同机型同 CPU + GPU 可以试试。我是在 1401 的网站上看到了华硕同显 U 成功开机了，觉得这个有戏才做的尝试。因为这个型号太冷门了（之前要个原厂镜像都要不到）。</p>

<p>同系列机型非同 CPU、GPU 需要修改部分内容，要改啥不确定。因为有个 P1523，但是是 i5 + 4050 的盆友用我的 EFI 就开不了机。</p>

<h2>开机效果</h2>
<img
  src="https://github.com/user-attachments/assets/067f50ab-4b63-4110-920b-6259e1bb3018"
  alt="f28f0b54df3afe6acdc4109db256e731"
  width="1181"
  height="717"
>

<h2>可用</h2>
<ul>
  <li>GPU</li>

  <li>蓝牙（蓝牙音频可用，解码协议未知，懂得不多）</li>
  <li>
    <img
      src="https://github.com/user-attachments/assets/5e7da711-b57a-4df6-8d63-44c8a65ec3ee"
      alt="截屏2026-10-25 19 33 14"
      width="508"
      height="638"
    >
  </li>

  <li>Wi‑Fi（因特尔网卡不太兼容，在开机后需要用 OCLP-MOD 给驱动打补丁，还需要先伪装后安装，Wi‑Fi 6 正常使用）</li>
  <li>
    <img width="335" height="214" alt="截屏2026-10-25 19 56 26" src="https://github.com/user-attachments/assets/081988e5-1529-4a84-9f84-dee6c0175d17" />

  </li>

  <li>隔空传送（单向只能发不能收，原因同英特尔）</li>
  <li>
    <img
      src="https://github.com/user-attachments/assets/bd8eb8b1-19e9-4856-9173-f9e2cb4ba380"
      alt="截屏2026-10-25 19 36 11"
      width="368"
      height="270"
    >
  </li>

  <li>键盘 / 触控板 / USB / 摄像头 / 麦克风 / 扬声器（内置和外接）</li>
</ul>

<h2>不可用（我修不好的）</h2>
<ul>
  <li>屏幕镜像</li>
  <li>隔空传送半残，不完整体验</li>
  <li>🔋（脱电使用会减电量，但是要时间刷新，并且充电时无法识别到在充电）</li>
  <li>风扇控制、显示器亮度调节</li>
  <li>核显：听说已经有相关驱动了，不过因为刚出可能问题比较多就没整</li>
</ul>

<p>使用一段时间后“关于本机”打不开，看起来无伤大雅，但是不太懂怎么回事。重启后正常。</p>
<img
  src="https://github.com/user-attachments/assets/2d497205-5fbc-4871-a871-51d5cca6f8d1"
  alt="截屏2026-10-25 19 44 25"
  width="730"
  height="635"
>

<h2>另外需要注意⚠️</h2>
<p>七彩虹这个型号的笔记本 BIOS 大概率是阉割版的，可能需要破解。我当时因为有个开关需要开，但是 BIOS 没有设置才去刷 BIOS。</p>
<p><strong>此操作有风险。</strong>如果能够接受，可以去 B 站找教程。</p>

<p>谢谢各路大佬开源，让我也第一次用上 macOS 🙏</p>
