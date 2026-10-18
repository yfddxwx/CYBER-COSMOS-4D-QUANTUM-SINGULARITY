# 🌌 CYBER-COSMOS 4D QUANTUM SINGULARITY
### 赛博量子奇点与相对论时空视界实时模拟系统

[![WebGL 2.0](https://img.shields.io/badge/WebGL-2.0-00f0ff.svg?style=flat-square)](https://www.khronos.org/webgl/)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-0-00ff88.svg?style=flat-square)](https://github.com/yfddxwx/CYBER-COSMOS-4D-QUANTUM-SINGULARITY)
[![FPS](https://img.shields.io/badge/Performance-60~120%20FPS-ff0055.svg?style=flat-square)](https://github.com/yfddxwx/CYBER-COSMOS-4D-QUANTUM-SINGULARITY)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)

**CYBER-COSMOS** 是一个基于纯原生 **WebGL 2.0** 与 **GLSL 相对论测地线光线追踪（Geodesic Raymarching）** 的物理级黑洞与量子时空实时模拟引擎。

零外部库依赖、单文件自包含、全硬件加速计算，在普通 PC 和现代移动设备上皆可跑出满帧流式视觉效果。

---

## ⚡ 核心物理与视觉特性 (Key Features)

### 1. 广义相对论光线弯曲 (Relativistic Geodesic Raymarching)
- 实时求解弯曲时空中的零测地线加速度方程：
  $$\frac{d^2 x^i}{d\lambda^2} \approx -\frac{1.5 R_s \cdot h^2}{r^5} x^i$$
- 完整重现《星际穿越》（Interstellar）Gargantua 黑洞著名的**上下双弧透镜投影**（背侧吸积盘的光线受极端引力弯折跨过视界上下方进入观察者视网膜）。
- 极细的**爱因斯坦光子球层（Photon Sphere Ring，\(r = 1.5 R_s\)）** 与事件视界绝对暗区。

### 2. 相对论多普勒辐射增强 (Doppler Beaming & Gravitational Redshift)
- 吸积盘物质以接近光速的开普勒速度 \(v(r) = c \sqrt{R_s / 2r}\) 高速公转。
- 引入相对论多普勒因子 \(\delta = \frac{1}{\gamma (1 - \vec{\beta} \cdot \vec{n})}\)，盘面朝向观察者高速运动侧发生剧烈**辐射增强与蓝移（呈现炽白与天青色）**，背向侧发生强烈**红移暗化（暗红余烬）**。

### 3. 四大超维形态预设 (4 Quantum Sectors)
- 🕳️ **GARGANTUA**：电影级克尔黑洞与高能等离子湍流吸积盘。
- 🌌 **WORMHOLE**：爱因斯坦-罗森桥时空虫洞，透过通道窥见异维宇宙星空。
- 💠 **CYBER CORE**：赛博朋克量子核心与全息数字晶格时空网络。
- ⚡ **PULSAR JET**：超致密脉冲星磁层与两极超相对论性等离子体高能喷流。

### 4. 生成式宇宙声学 (Web Audio API Synthesizer)
- 纯代码实时生成的深空超低频声景（Brownian Sub-bass Drone）与动态双二阶滤波宇宙风声。
- 点击“视界跃迁”（HORIZON DIVE）触发时，同步释放模拟 LIGO 观测的**引力波啁啾声（Gravitational Wave Chirp）**。

### 5. 赛博拟态 HUD 与遥测控制台 (Cyberpunk HUD Console)
- 实时 FPS 监控、视界半径 $R_s$、自旋角动量 $a^*$、相对论时间膨胀系数 $\gamma$ 动态遥测。
- 支持时空扭曲强度、吸积流速、量子泛光实时调节。
- 支持平滑惯性阻尼旋转、超空间滚轮缩放、自动巡航轨道与一键全屏沉浸模式。

---

## 🎮 控制与交互指南 (Controls)

| 操作方式 | 功能描述 |
| :--- | :--- |
| **鼠标左键拖拽 / 单指滑动** | 3D 自由环绕视角（带物理阻尼惯性） |
| **滚轮滑动 / 双指缩放** | 超空间深度变焦（逼近事件视界） |
| **空格键 (Space)** | 触发“视界俯冲”（HORIZON DIVE）极速穿越 |
| **SECTOR 切换** | 切换 4 种黑洞/虫洞/量子核心形态 |
| **AUDIO 开关** | 开启 / 关闭 Web Audio API 宇宙深空合成音效 |
| **FULLSCREEN 按钮** | 切换 4K 全屏沉浸体验 |

---

## 🚀 极速启动 (Quick Start)

由于本项目为**零依赖单文件纯原生架构**，无需安装 Node.js、npm 或任何第三方打包工具：

1. **直接运行**：
   下载或克隆仓库后，直接双击打开 `index.html` 即可在任意现代浏览器（Chrome、Edge、Firefox、Safari）中畅玩！

2. **本地静态服务器（可选）**：
   ```bash
   # 使用 Python 快速启动本地预览
   python -m http.server 8080
   # 打开浏览器访问 http://localhost:8080
   ```

3. **在线体验 (GitHub Pages)**：
   进入仓库 Settings -> Pages -> Source 选择 `main` 分支根目录 `/` 保存，即可在 `https://<username>.github.io/CYBER-COSMOS-4D-QUANTUM-SINGULARITY/` 免安装在线畅玩！

---

## 📄 开源许可证 (License)

本项目基于 [MIT License](LICENSE) 开源。
