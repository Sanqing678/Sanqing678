<div align="center">

# 三青

**Hackintosh / OpenCore EFI / macOS hardware adaptation**

把不同平台的黑苹果 EFI、驱动方案和安装经验整理成可检索、可复用的资料库。

<p>
  <a href="https://github.com/Sanqing678?tab=repositories">
    <img src="https://img.shields.io/badge/Repositories-30-111827?style=for-the-badge&logo=github&logoColor=white" alt="Repositories" />
  </a>
  <a href="https://github.com/Sanqing678/Hackintosh-Installation-Guide">
    <img src="https://img.shields.io/badge/OpenCore-Guide-0A84FF?style=for-the-badge&logo=apple&logoColor=white" alt="OpenCore Guide" />
  </a>
  <a href="https://github.com/Sanqing678?tab=followers">
    <img src="https://img.shields.io/github/followers/Sanqing678?style=for-the-badge&label=Follow&color=16A34A" alt="GitHub followers" />
  </a>
</p>

<p>
  <a href="#精选项目">精选项目</a> ·
  <a href="#efi-索引">EFI 索引</a> ·
  <a href="#适配范围">适配范围</a> ·
  <a href="#使用建议">使用建议</a>
</p>

</div>

---

## 关于

我主要维护 Hackintosh / OpenCore 相关项目，覆盖台式机、迷你主机、笔记本、工作站和部分特殊硬件平台。

每个仓库尽量围绕一台具体设备整理：硬件配置、macOS 版本、OpenCore 版本、驱动状态、已知问题和排错思路。这里不是单个 EFI 的堆放区，而是一个持续整理的黑苹果适配索引。

---

## 精选项目

<table>
  <tr>
    <td width="50%">
      <h3><a href="https://github.com/Sanqing678/Hackintosh-Installation-Guide">OpenCore 安装指南</a></h3>
      <p>硬件兼容、EFI 制作、BIOS 设置、安装流程、排错和后期优化。</p>
      <p><code>Guide</code> <code>OpenCore</code> <code>Intel / AMD</code></p>
    </td>
    <td width="50%">
      <h3><a href="https://github.com/Sanqing678/Introduction-to-SSDT">SSDT 入门</a></h3>
      <p>ACPI / SSDT 基础、常用表、制作工具和黑苹果常见补丁思路。</p>
      <p><code>ACPI</code> <code>SSDT</code> <code>Patch</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3><a href="https://github.com/Sanqing678/CPUFriend-Usage-Tutorial">CPUFriend 教程</a></h3>
      <p>CPU 电源管理优化，生成并使用 CPUFriendDataProvider.kext。</p>
      <p><code>Power Management</code> <code>Kext</code></p>
    </td>
    <td width="50%">
      <h3><a href="https://github.com/Sanqing678/RX6950XT-RX6650XT-Black-Apple-video-card-driver-tutorial-and-method">AMD 显卡驱动方案</a></h3>
      <p>RX 6950 XT / RX 6650 XT 通过 SSDT 仿冒方式适配 macOS。</p>
      <p><code>GPU</code> <code>SSDT Spoof</code> <code>AMD</code></p>
    </td>
  </tr>
</table>

---

## EFI 索引

<details open>
<summary><strong>近期维护</strong></summary>

| 设备 | 关键信息 | 仓库 |
| --- | --- | --- |
| ASUS TUF Gaming FX504GE | i7-8750H / UHD 630 / Sonoma | [ASUS-TUF-FX504GE-Hackintosh](https://github.com/Sanqing678/ASUS-TUF-FX504GE-Hackintosh) |
| Panasonic Let note CFLV8 | i5-8365U / Whiskey Lake / Ventura | [PANASONIC-CFLV8-1T-Hackintosh](https://github.com/Sanqing678/PANASONIC-CFLV8-1T-Hackintosh) |
| MSI B650M GAMING PLUS WIFI | Ryzen 7 7800X3D / RX 580 | [MSI-B650M-GAMING-PLUS-WIFI-Hackintosh](https://github.com/Sanqing678/MSI-B650M-GAMING-PLUS-WIFI-Hackintosh) |
| ASUS PRIME Z890M-PLUS WIFI | Core Ultra 7 265K | [EFI-ASUS-PRIME-Z890M-PLUS-WIFI-CORE-ULTRA-7-265K-open-core1.04](https://github.com/Sanqing678/EFI-ASUS-PRIME-Z890M-PLUS-WIFI-CORE-ULTRA-7-265K-open-core1.04) |

</details>

<details>
<summary><strong>台式机 / 工作站 / 迷你主机</strong></summary>

| 设备 | 平台 | 仓库 |
| --- | --- | --- |
| MSI Creator TRX40 | Threadripper 3960X + RX 6950 XT | [EFI-MSI-Creator-TRX40-Ryzen-Threadripper-3960X-OpenCore1.07](https://github.com/Sanqing678/EFI-MSI-Creator-TRX40-Ryzen-Threadripper-3960X-OpenCore1.07) |
| MSI MAG B460M MORTAR | Intel B460 | [MSI-MAG-B460M-MORTAR-Hackintosh](https://github.com/Sanqing678/MSI-MAG-B460M-MORTAR-Hackintosh) |
| Colorful B860M | Arrow Lake | [Colorful-B860M-Arrow-Lake-Hackintosh](https://github.com/Sanqing678/Colorful-B860M-Arrow-Lake-Hackintosh) |
| AIGO X99M D3 MAX | X99 | [AIGO-X99M-D3-MAX-Hackintosh](https://github.com/Sanqing678/AIGO-X99M-D3-MAX-Hackintosh) |
| OEM HN B85 | B85 | [OEM-HN-B85-Hackintosh](https://github.com/Sanqing678/OEM-HN-B85-Hackintosh) |
| Huawei MateStation B520 | i7-10700 / Comet Lake-S | [Huawei-MateStation-B520-Hackintosh](https://github.com/Sanqing678/Huawei-MateStation-B520-Hackintosh) |
| DELL OptiPlex 7070 | i7-9700T / UHD 630 | [DELL-OptiPlex-7070-OpenCore1.0](https://github.com/Sanqing678/DELL-OptiPlex-7070-OpenCore1.0) |
| DELL OptiPlex 7060 Micro | i5-8500T | [DELL-Optiplex-7060-OpenCore1.0](https://github.com/Sanqing678/DELL-Optiplex-7060-OpenCore1.0) |
| DELL OptiPlex 3040 | i5-6600T / Skylake | [DELL-Optiplex-3040-Hackintosh](https://github.com/Sanqing678/DELL-Optiplex-3040-Hackintosh) |
| Lenovo ThinkCentre M920 | ThinkCentre | [Lenovo-ThinkCentre-M920-Hackintosh](https://github.com/Sanqing678/Lenovo-ThinkCentre-M920-Hackintosh) |
| Lenovo ThinkCentre M6600q-N000 | i3-6100 | [Lenovo-ThinkCentre-M6600q-N000-Open-Core1.0](https://github.com/Sanqing678/Lenovo-ThinkCentre-M6600q-N000-Open-Core1.0) |
| HP ProDesk 400 G5 SFF | HP ProDesk | [HP-ProDesk-400-G5-SFF-Hackintosh](https://github.com/Sanqing678/HP-ProDesk-400-G5-SFF-Hackintosh) |
| Intel NUC5i7RY | Intel NUC | [Intel-NUC5i7RY-Hackintosh](https://github.com/Sanqing678/Intel-NUC5i7RY-Hackintosh) |
| Mini PC i7-8565U | UHD 620 | [Mini-PC-i7-8565U-OpenCore](https://github.com/Sanqing678/Mini-PC-i7-8565U-OpenCore) |

</details>

<details>
<summary><strong>笔记本 / 移动设备</strong></summary>

| 设备 | 平台 | 仓库 |
| --- | --- | --- |
| RedmiBook Pro 14S | Ryzen 7 5700U | [TIMI-RedmiBook-Pro-14S-open-core-1.06](https://github.com/Sanqing678/TIMI-RedmiBook-Pro-14S-open-core-1.06) |
| 机械革命 S1 Pro | i5-8265U | [MMECHREVO-S1-Pro-OpenCore1.0](https://github.com/Sanqing678/MMECHREVO-S1-Pro-OpenCore1.0) |
| HP EliteBook 840 G3 | i5-6300U | [EFI-HP-EliteBook-840-G3-Hackintosh](https://github.com/Sanqing678/EFI-HP-EliteBook-840-G3-Hackintosh) |
| HP Elite X2 1012 G2 | i5-7200U | [HP-Elite-X2-1012-G2-Hackintosh](https://github.com/Sanqing678/HP-Elite-X2-1012-G2-Hackintosh) |
| Lenovo ThinkPad X280 | ThinkPad X280 | [Lenovo-ThinkPad-X280-Hackintosh](https://github.com/Sanqing678/Lenovo-ThinkPad-X280-Hackintosh) |
| TIMI TM1707 | i5-8250U / Kaby Lake-R | [TIMI-TM1707-Hackintosh](https://github.com/Sanqing678/TIMI-TM1707-Hackintosh) |
| AIERXUAN Z-2 | i7-8750H / Coffee Lake-H | [AIERXUAN-Z2-Hackintosh](https://github.com/Sanqing678/AIERXUAN-Z2-Hackintosh) |

</details>

---

## 适配范围

<p>
  <img src="https://img.shields.io/badge/OpenCore-EFI-111827?style=flat-square" alt="OpenCore EFI" />
  <img src="https://img.shields.io/badge/ACPI-SSDT-2563EB?style=flat-square" alt="ACPI SSDT" />
  <img src="https://img.shields.io/badge/macOS-Monterey%20%7C%20Ventura%20%7C%20Sonoma%20%7C%20Sequoia-0F766E?style=flat-square" alt="macOS versions" />
  <img src="https://img.shields.io/badge/Platform-Intel%20%7C%20AMD-7C3AED?style=flat-square" alt="Platforms" />
</p>

| 模块 | 内容 |
| --- | --- |
| 启动 | OpenCore 配置、启动项、机型定制、升级记录 |
| ACPI | EC、USBX、PLUG、PNLF、显卡仿冒等常用 SSDT |
| 驱动 | 显卡、声卡、网卡、蓝牙、触控板、电池、USB、睡眠 |
| 平台 | Intel / AMD，台式机 / 迷你主机 / 笔记本 / 工作站 |

---

## GitHub 数据

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Sanqing678&show_icons=true&theme=transparent&hide_border=true&hide_title=true" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sanqing678&layout=compact&theme=transparent&hide_border=true" alt="Top languages" />

</div>

---

## 使用建议

EFI 与硬件批次、BIOS 版本、外设组合关系很大。使用前请先核对自己的硬件配置，替换 EFI 前备份原文件，并准备可恢复的启动盘。

如果仓库帮到了你，欢迎 Star；如果遇到兼容性问题，建议在 Issue 里补充设备型号、CPU、显卡、网卡、macOS 版本、OpenCore 版本和具体报错。

