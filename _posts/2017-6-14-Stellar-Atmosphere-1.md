---
Title: 恒星大气
date: 2017-06-14
tag:
- Stellar Atmosphere
- Stellar Physics

---

## 第一章 恒星观测的基本特性

### 第一节 恒星的光度

1. **光度**$$L$$：天体每秒由其表面所辐射出的总能量。$$\left(J/s\right)$$

   $$L=4\pi R^{2}\sigma T^{4}$$

   **亮度**$$I$$：在地球上单位时间单位面积接收到的天体的辐射量。（会受星际物质的吸收和散射影响）

   $$I=\frac{L}{4\pi d^{2}}$$

2. **视星等**：天体在频率$$\nu$$处的视星等定义为

   $$m_{\nu}=-2.5\log \left(\frac{f_{\nu}}{f_{\nu}\left(Vega\right)}\right)$$

   视星等是恒星亮度的度量

   $$m^{A}_{V}-m^{B}_{V}=-2.5\log  \left(\frac{I_{A}}{I_{B}}\right)$$

   **热星等**$$m_{bol}$$：对整个波段积分总光度。

   $$m_{bol}=m_{V}+B.C.$$

   其中$$B.C.$$称为**热改正**。

3. **绝对星等**：将恒星移动到距地球$$10pc​$$处所得的亮度，表示恒星固有发光能力，与距离无关。

   $$M_{V}-m_{V}=-2.5\log \left(\frac{L/4\pi 10^{2}}{L/4\pi d^{2}}\right)=5-5\log d$$

   光度与绝对星等有关系

   $$M_{1}-M_{2}=-2.5\log\left(\frac{L_{1}}{L_{2}}\right)$$

   **绝对热星等**$$M_{bol}$$：

   $$M_{bol}=M_{V}+B.C.$$

   恒星的光度：

   $$\log \left(\frac{L}{L_{\odot}}\right)=-0.4\left(M_{bol}-M_{bol,\odot}\right)$$

4. **色指数**：两种颜色的星等差。

### 第二节 恒星的有效温度

1. **黑体辐射**：

   当一个辐射体是热辐射源时，其辐射遵循Planck黑体辐射定律

   $$B_{\nu}(T)=\frac{2h\nu^{3}}{c^{2}}\frac{1}{e^{h\nu/kT}-1}$$

   瑞利-金斯近似：当$$\frac{h\nu}{kT}\ll1$$时，$$e^{h\nu/kT}\approx1+h\nu/kT$$，因此

   $$B_{\nu}\left(T\right)=\frac{2k\nu^{2}T}{c^{2}}=\frac{2ckT}{\lambda^{4}}$$

   维恩近似：当$$\frac{h\nu}{kT}\gg1$$时，$$e^{h\nu/kT}-1\approx e^{h\nu/kT}$$，因此

   $$B_{\nu}\left(T\right)=\frac{2h\nu^{3}}{c^{2}}e^{-\frac{h\nu}{kT}}=\frac{2hc}{\lambda^{3}}e^{-\frac{hc}{\lambda kT}}$$

   **维恩定律**：

   $$\lambda_{max}T=Const.$$

2. **有效温度**：

   对Planck公式积分，有

   $$B\left(T\right)=\int^{\infty}_{0} \frac{2h\nu^{3}}{c^{2}}\left[e^{\frac{h\nu}{kT}}-1\right]^{-1}d\nu=\frac{2k^{4}T^{4}}{c^{2}h^{3}}\int^{\infty}_{0}\frac{x^{3}}{e^{x}-1}dx=\frac{2k^{4}T^{4}}{c^{2}h^{3}}\cdot \frac{\pi^{4}}{15}$$

   令$$\sigma=\frac{2\pi^{5}k^{4}}{15c^{2}h^{3}}$$，则有

   $$B\left(T\right)=\frac{\sigma}{\pi}T^{4}$$

   **温度越高的辐射源，其辐射峰值频率越高**。

   <img src="/Figures/Stellar-Atmosphere/黑体辐射.png" width="50%"/>

   将恒星的辐射等价为黑体辐射（实际并不遵守），并定义有效温度

   $$L=4\pi R^{2}\sigma T^{4}_{eff}$$

### 第三节 恒星的分类

1. 光谱分类：

   - 正常恒星光谱由**连续谱**和**吸收线**组成。连续谱来自于较热的致密的恒星内部，吸收线来自于较冷的稀薄的恒星大气。
   - 恒星光谱包含恒星性质的丰富信息，如**表面温度**、**质量**、**半径**、**光度**、**化学组成**等。
   - 光谱型：O、B、A、F、G、K、M


2. 光度型和MK分类法

### 第四节 H-R图

1. 赫罗图：将恒星光度$$L$$对其表面有效温度$$T_{eff}$$所作的图。H-R图反应了恒星光度和有效温度之间的关系，总结了恒星的许多观测性质，是研究恒星结构演化的重要方法。

   <img src="/Figures/Stellar-Atmosphere/赫罗图.png" width="70%"/>
