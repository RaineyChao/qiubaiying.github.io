# 恒星大气
## 预备知识

1. **热辐射**：由于物质中的分子、原子受到热激发而发射电磁波的现象为热辐射。

2. **单色辐射强度**：描述物体辐射本领的物理量。
   $$
   I_{\lambda}\left(T\right)=\frac{dE_{\lambda}}{d\lambda}
   $$
   表示在一定温度$T$下，单位时间内从物体表面单位面积上波长在$\lambda$附近单位波长间隔内辐射出的能量。

3. **辐射强度**：描述物体在温度T时向外辐射本领的物理量，单色辐射强度对频率的积分。
   $$
   I\left(T\right)=\int^{\infty}_{0}I_{\lambda}\left(T\right)d\lambda
   $$
   表示在一定温度$T$下，单位时间内从物体表面单位面积上全波段范围内辐射出的能量。

4. **热平衡辐**射：物体辐射的能量等于在同一时间内所吸收的能量时，热辐射过程达到热平衡。

5. **非热平衡辐射**：不能仅用维持温度来使辐射继续下去，而且还要依靠某种激发机制来获得能量才能发生辐射。包括：

   - 电致发光
   - 光致发光
   - 化学发光
   - 热发光

   它们都有一个共同点，即都是非平衡辐射，其光谱主要是分立的线状谱或带状谱。不同的原子、离子和分子分别具有不同的标识谱线或谱带。需要强调，**热发光要加热到一定温度才会发光，如Na双黄线，而热辐射不限定于一定温度上，且形成辐射连续谱不是分立线状谱**。

6. **太阳和其他恒星的辐射是热辐射（黑体谱、连续谱）和热发光（非连续谱）的叠加。**

7. **黑体辐射**：

   - 电磁波辐射和物质的相互作用有四种方式：**发射**、**吸收**、**反射**和**透射**。一个物体发射电磁波的同时，也会吸收其他物体的电磁辐射。


   - **绝对黑体**：能够吸收外来一切电磁波辐射而毫无反射的物体。

8. **斯特藩-玻耳兹曼定律**：
   $$
   I\left(T\right)=\int^{\infty}_{0}I_{\lambda}\left(T\right)d\lambda=\sigma T^{4}
   $$

9. **维恩位移定律**：
   $$
   \lambda_{max}T=Const.
   $$

10. **瑞利-金斯公式**：
    $$
    B_{\nu}\left(T\right)=\frac{2k\nu^{2}T}{c^{2}}=\frac{2ckT}{\lambda^{4}}
    $$

11. 普朗克量子假设、黑体辐射公式：

    - 能量分离不连续

    - Planck公式
      $$
      B_{\nu}(T)=\frac{2h\nu^{3}}{c^{2}}\frac{1}{e^{h\nu/kT}-1}
      $$


## 第一章 恒星观测的基本特性

### 第一节 恒星的光度

1. **光度**$L$：天体每秒由其表面所辐射出的总能量。$\left(J/s\right)$
   $$
   L=4\pi R^{2}\sigma T^{4}
   $$
   **亮度**$I$：在地球上单位时间单位面积接收到的天体的辐射量。（会受星际物质的吸收和散射影响）
   $$
   I=\frac{L}{4\pi d^{2}}
   $$

2. **视星等**：天体在频率$\nu$处的视星等定义为
   $$
   m_{\nu}=-2.5\log \left(\frac{f_{\nu}}{f_{\nu}\left(Vega\right)}\right)
   $$
   视星等是恒星亮度的度量
   $$
   m^{A}_{V}-m^{B}_{V}=-2.5\log  \left(\frac{I_{A}}{I_{B}}\right)
   $$
   **热星等**$m_{bol}$：对整个波段积分总光度。
   $$
   m_{bol}=m_{V}+B.C.
   $$
   其中$B.C.$称为**热改正**。

3. **绝对星等**：将恒星移动到距地球$10pc$处所得的亮度，表示恒星固有发光能力，与距离无关。
   $$
   M_{V}-m_{V}=-2.5\log \left(\frac{L/4\pi 10^{2}}{L/4\pi d^{2}}\right)=5-5\log d
   $$
   光度与绝对星等有关系
   $$
   M_{1}-M_{2}=-2.5\log\left(\frac{L_{1}}{L_{2}}\right)
   $$
   **绝对热星等**$M_{bol}$：
   $$
   M_{bol}=M_{V}+B.C.
   $$
   恒星的光度：
   $$
   \log \left(\frac{L}{L_{\odot}}\right)=-0.4\left(M_{bol}-M_{bol,\odot}\right)
   $$

4. **色指数**：两种颜色的星等差。

### 第二节 恒星的有效温度

1. **黑体辐射**：

   当一个辐射体是热辐射源时，其辐射遵循Planck黑体辐射定律
   $$
   B_{\nu}(T)=\frac{2h\nu^{3}}{c^{2}}\frac{1}{e^{h\nu/kT}-1}
   $$
   瑞利-金斯近似：当$\frac{h\nu}{kT}\ll1​$时，$e^{h\nu/kT}\approx1+h\nu/kT​$，因此
   $$
   B_{\nu}\left(T\right)=\frac{2k\nu^{2}T}{c^{2}}=\frac{2ckT}{\lambda^{4}}
   $$
   维恩近似：当$\frac{h\nu}{kT}\gg1$时，$e^{h\nu/kT}-1\approx e^{h\nu/kT}$，因此
   $$
   B_{\nu}\left(T\right)=\frac{2h\nu^{3}}{c^{2}}e^{-\frac{h\nu}{kT}}=\frac{2hc}{\lambda^{3}}e^{-\frac{hc}{\lambda kT}}
   $$
   **维恩定律**：
   $$
   \lambda_{max}T=Const.
   $$

2. **有效温度**：

   对Planck公式积分，有
   $$
   B\left(T\right)=\int^{\infty}_{0} \frac{2h\nu^{3}}{c^{2}}\left[e^{\frac{h\nu}{kT}}-1\right]^{-1}d\nu=\frac{2k^{4}T^{4}}{c^{2}h^{3}}\int^{\infty}_{0}\frac{x^{3}}{e^{x}-1}dx=\frac{2k^{4}T^{4}}{c^{2}h^{3}}\cdot \frac{\pi^{4}}{15}
   $$
   令$\sigma=\frac{2\pi^{5}k^{4}}{15c^{2}h^{3}}$，则有
   $$
   B\left(T\right)=\frac{\sigma}{\pi}T^{4}
   $$
   ​

   **温度越高的辐射源，其辐射峰值频率越高**。

   <div align=center>

   <img src="./Figures/黑体辐射.png" width="50%"/>

   </div>

   将恒星的辐射等价为黑体辐射（实际并不遵守），并定义有效温度
   $$
   L=4\pi R^{2}\sigma T^{4}_{eff}
   $$


### 第三节 恒星的分类

1. 光谱分类：

   - 正常恒星光谱由**连续谱**和**吸收线**组成。连续谱来自于较热的致密的恒星内部，吸收线来自于较冷的稀薄的恒星大气。


   - 恒星光谱包含恒星性质的丰富信息，如**表面温度**、**质量**、**半径**、**光度**、**化学组成**等。
   - 光谱型：O、B、A、F、G、K、M

2. 光度型和MK分类法

### 第四节 H-R图

1. 赫罗图：将恒星光度$L$对其表面有效温度$T_{eff}$所作的图。H-R图反应了恒星光度和有效温度之间的关系，总结了恒星的许多观测性质，是研究恒星结构演化的重要方法。

   <div align=center>

   <img src="./Figures/赫罗图.png" width="70%"/>

   </div>

## 第二章 辐射转移理论基础



## 第三章 物质函数



## 第四章 恒星大气的基本方程组

### 第一节 统计平衡方程组

1. 单位体积内原子在各个能级上的占据数为常量，即
   $$
   \frac{d}{dt}n^{\alpha\beta}_{i}=0
   $$
   即跃入等于跃出。

2. 讨论$\alpha$类原子处于$\beta$电离度时
   $$
   n_{i}\Sigma^{k}_{j\neq i}P_{ij}=\Sigma^{k}_{j\neq i}n_{j}P_{ji}
   $$
   式中$P_{ij}$表示单位时间内原子由$i$能级跃迁到$j$能级的跃迁几率 ，$k$代表连续谱。

3. 讨论$P_{ij}$

   - 与辐射场有关

   - 由辐射部分和碰撞部分组成
     $$
     P_{ij}=R_{ij}+C_{ij}
     $$
     其中$R_{ij}$为辐射跃迁速率，$C_{ij}$为碰撞跃迁速率。

   - 辐射跃迁速率$R_{ij}$

   - 碰撞跃迁速率$C_{ij}$

### 第二节 粒子数守恒和电荷数守恒方程

1. 总粒子数守恒方程
   $$
   n=n_{e}+\Sigma_{\alpha}\Sigma_{\beta}\Sigma_{i}n^{\alpha\beta}_{i}
   $$

2. 元素$\alpha$的粒子数守恒方程
   $$
   nX_{\alpha}=\Sigma_{\beta}\Sigma_{i}n^{\alpha\beta}_{i}
   $$

3. 电荷数守恒方程
   $$
   n_{e}=\Sigma_{\alpha}\Sigma_{\beta}\beta\Sigma_{i}n^{\alpha\beta}_{i}
   $$


### 第三节 流体静力学平衡方程

1. 由流体静力学平衡条件
   $$
   \frac{dP}{dr}=-g\rho
   $$
   平面平行情况：
   $$
   dp_{g}+dp_{R}=-g\rho dz
   $$


### 第四节 辐射转移方程

1. 辐射穿越一介质层$ds$后，产生辐射强度变化$dI_{\nu}$的原因：

   - 吸收作用：
     $$
     dI_{\nu}=-\kappa_{\nu}I_{\nu}ds
     $$

   - 发射作用：
     $$
     dI_{\nu}=\eta_{\nu}ds
     $$


   总辐射变化$dI_{\nu}$为
   $$
   \mu\frac{dI_{\nu}}{dz}=-\kappa_{\nu}I_{\nu}+\eta_{\nu}\\
   \mu\frac{dI_{\nu}}{d\tau_{\nu}}=I_{\nu}-\frac{\eta_{\nu}}{\kappa_{\nu}}
   $$
   其中$d\tau_{\nu}=-\kappa_{\nu}dz​$。定义源函数$S_{\nu}=\frac{\eta_{\nu}}{\kappa_{\nu}}​$，因此
   $$
   \mu\frac{dI_{\nu}}{d\tau_{\nu}}=I_{\nu}-S_{\nu}
   $$

2. 对辐射转移方程两边乘以积分因子$e^{-\tau_{\nu}/\mu}$再积分，有辐射转移方程通解
   $$
   I_{\nu}\left(0\right)=I_{\nu}\left(\tau_{\nu}\right)e^{-\tau_{\nu}/\mu}+\int^{\tau_{\nu}}_{0}S_{\nu}e^{-t_{\nu}/\mu}\frac{dt_{\nu}}{\mu}
   $$
   右边第一项代表入射辐射的贡献，第二项代表介质层的贡献。

### 第五节 能量平衡方程与能量定理

1. 能量平衡方程：

   恒星大气温度较低，没有热核反应，只有能量输运。有两种方式：

   - 辐射转移（表面$\rightarrow$内部$\tau=1$的范围，辐射平衡区）
   - 对流转移（晚于F5的恒星在$\tau=1$以下的区域内，H、He部分电离区，对流平衡区）

   当恒星大气处于辐射平衡时，任意体元$dV$每秒吸收的能量应该与辐射出去的能量相等，即
   $$
   \int_{\nu}\int_{\omega}\left[\kappa_{\nu}I_{\nu}\left(\tau_{nu},\mu\right)+\eta_{\nu}\left(\tau_{\nu}\right)\right]\frac{d\omega}{4\pi}d\nu=0
   $$
   该式称为能量平衡方程。

2. 能量定理：

   将辐射转移方程左侧对频率$\nu$和空间角$\omega$积分
   $$
   \int_{\nu}\int_{\omega}\mu\frac{dI_{\nu}}{dz}d\nu d\omega=\frac{d}{dz}\int_{\nu}\int_{\omega}\mu I_{\nu}d\nu d\omega=\int_{\nu}\int_{\omega}\left(-\kappa_{\nu}I_{\nu}+\eta_{\nu}\right)d\nu d\omega=0
   $$
   又$\pi F=\int^{\infty}_{0}\pi F_{\nu}d\nu=\int_{\nu}\int_{\omega}\mu I_{\nu}d\nu d\omega$，因此
   $$
   \frac{d\pi F}{dz}=0
   $$
   该式称为能量定理，仅对总辐射流成立。又$\pi F$表示恒星向外的净辐射流，因此
   $$
   \pi F=\frac{L}{4\pi R^{2}}=\sigma T^{4}_{eff}=Const.
   $$
   恒星大气处于辐射平衡时，总辐射流应该是由辐射方式和对流方式传递的能量流之和，即
   $$
   \pi F=\pi F_{rad}+\pi F_{conv}=\sigma T^{4}_{eff}=Const.
   $$


### 第六节 对流

1. 史瓦西条件推导：

   考虑流体元因浮力作用上浮一段距离$dr$，其内部密度与环境密度的差为
   $$
   \Delta\rho\left(r+dr\right)=\Delta\rho\left(r\right)+dr\cdot\frac{d}{dr}\left(\Delta\rho\right)
   $$
   其中$\Delta\rho\left(r\right)<0$，$dr>0$。当$\frac{d}{dr}\left(\Delta\rho\right)\le0$时，$\Delta\rho\left(r+dr\right)<0$，即流体密度仍低于环境密度，流体可以继续上浮。因此，对流非稳定性条件为
   $$
   \frac{d}{dr}\left(\Delta\rho\right)\le0
   $$
   考虑化学组分均匀的区域，有物态方程
   $$
   \rho=\rho\left(P,T\right)
   $$
   写出了$\ln P$的全微分
   $$
   d\ln P=\left(\frac{\partial\ln \rho}{\partial\ln P}\right)_{T}d\ln P+\left(\frac{\partial\ln \rho}{\partial\ln T}\right)_{P}d\ln T
   $$
   应用于流体元内部有
   $$
   \frac{d\ln \rho_{e}}{dr}=\left(\frac{\partial\ln \rho}{\partial\ln P}\right)_{T}\frac{d\ln P_{e}}{dr}+\left(\frac{\partial\ln \rho}{\partial\ln T}\right)_{P}\frac{d\ln T_{e}}{dr}
   $$
   应用于流体元环境有
   $$
   \frac{d\ln \rho_{R}}{dr}=\left(\frac{\partial\ln \rho}{\partial\ln P}\right)_{T}\frac{d\ln P_{R}}{dr}+\left(\frac{\partial\ln \rho}{\partial\ln T}\right)_{P}\frac{d\ln T_{R}}{dr}
   $$
   两式相减得
   $$
   \frac{d}{dr}\left(\Delta\ln \rho\right)=\frac{d\ln \rho_{e}}{dr}-\frac{d\ln \rho_{R}}{dr}=\left(\frac{\partial\ln \rho}{\partial\ln P}\right)_{T}\left(\frac{d\ln P_{e}}{dr}-\frac{d\ln P_{R}}{dr}\right)+\left(\frac{\partial\ln \rho}{\partial\ln T}\right)_{P}\left(\frac{d\ln T_{e}}{dr}-\frac{d\ln T_{R}}{dr}\right)
   $$
   又$\Delta P=P_{e}-P_{R}=0$，因此
   $$
   \frac{d}{dr}\left(\Delta\ln \rho\right)=-\left(\frac{\partial\ln \rho}{\partial\ln T}\right)_{P}\left(\frac{d\ln T_{R}}{dr}-\frac{d\ln T_{e}}{dr}\right)
   $$
   由对流非稳定性条件$\frac{d}{dr}\left(\Delta\rho\right)\le0$，有
   $$
   \frac{d\ln T_{R}}{dr}\le\frac{d\ln T_{e}}{dr}
   $$
   引入压强标高
   $$
   H_{P}\equiv-\frac{dr}{d\ln P}=-P\frac{dr}{dP}
   $$
   当$P$随$r$增大而减小时，$H_{P}>0$。因此，两侧同乘$H_{P}$
   $$
   \left(\frac{d\ln T}{d\ln P}\right)_{R}\ge \left(\frac{d\ln T}{d\ln P}\right)_{e}
   $$
   定义$\nabla_{R}\equiv\left(\frac{d\ln T}{d\ln P}\right)_{R}$，$\nabla_{e}\equiv\left(\frac{d\ln T}{d\ln P}\right)_{e}$,有
   $$
   \nabla_{R}\ge \nabla_{e}
   $$
   因假设对流流体元来不及与环境温度交换，即绝热，有$\nabla_{e}=\nabla_{ad}$，因此，
   $$
   \nabla_{R}\ge \nabla_{ad}
   $$


## 第五章 恒星大气模型

### 第一节 基本假设

### 第二节 灰大气模型

1. **基本假设：**

   - 不透明度与频率无关，即
     $$
     \kappa_{\nu}=\bar{\kappa}
     $$

   - 恒星大气处于热动平衡状态，满足
     $$
     \left\{
     \begin{aligned}
     &\frac{\eta_{\nu}}{\kappa_{\nu}}=B_{\nu}\left(T\right)\\
     &S_{\nu}(\tau)=B_{\nu}(T(\tau))\\
     &B_{\nu}(T)=\frac{2h\nu^{3}}{c^{2}}\frac{1}{e^{h\nu/kT}-1}
     \end{aligned}
     \right.
     $$





2. **模型优点：**
   - 基本方程组之间的相关性被忽略
   - 方程可单独求解，计算简单


3. **辐射转移方程通解：**

    已知辐射转移方程

$$
\mu\frac{dI_{\nu}}{d\tau_{\nu}}=I_{\nu}-S_{\nu}
$$
​	由于在灰大气近似下不透明度与频率无关，即有
$$
\mu\frac{dI}{d\tau}-I=-S
$$
​	其中$I=\int^{\infty}_{0}I_{\nu}d\nu$，$S=\int^{\infty}_{0}S_{\nu}d\nu$。两侧同乘积分因子$e^{-\tau/\mu}$
$$
\frac{d}{d\tau}\left(Ie^{-\tau/\mu}\right)=-\frac{1}{\mu}Se^{-\tau/\mu}
$$
​	积分可得
$$
Ie^{-\tau/\mu}\Bigg|^{\tau_{2}}_{\tau_{1}}=-\int^{\tau_{2}}_{\tau_{1}}S\left(t\right)e^{-\tau/\mu}\frac{dt}{\mu}
$$
​	即
$$
I\left(\tau_{1},\mu\right)=I\left(\tau_{2},\mu\right)e^{-\frac{\tau_{2}-\tau_{1}}{\mu}}+\int^{\tau_{2}}_{\tau_{1}}S\left(t\right)e^{-\frac{t-\tau_{1}}{\mu}}\frac{dt}{\mu}
$$
​	该式为辐射转移方程通解。

4. 平均辐射强度、辐射流和K-积分的表达式
   - ​
5.  

### 第二节 局部热动平衡（LTE）大气模型

## 第六章 谱线理论

### 第一节 谱线基本知识

1. **发射光谱：**炽热气体的光谱，是由连续分布的一切波长的光组成的，这种光谱叫做连续光谱。

   - **连续光谱**：炽热气体的光谱，是由连续分布的一切波长的光组成的，这种光谱叫做连续光谱。恒星连续谱可以用黑体辐射解释，满足维恩位移定律，即
     $$
     \lambda_{max}T=Const.
     $$

   - **辐射能量流**$F$：单位时间通过单位面积向一侧辐射的总辐射能量，有：
     $$
     F=\sigma T^{4}
     $$

   - **明线光谱**：由游离状态的原子发射的，也叫原子光谱。（ex. 稀薄气体发射的光谱是明线光谱。


2. **吸收光谱**：高温气体发出的白光（其中包含连续分布的一切波长的光），通过介质时，某些波长的光被物质吸收后产生的光谱，叫做吸收光谱。

3. **恒星光谱中的谱线**：
   - 发射线、吸收线
   - 允许线、禁线
   - 星际吸收线、大气吸收线
   - 根据恒星光谱特点给恒星分类

4. **氢原子光谱及线系**：

   - 发射线、吸收线和电离

     <div align=center>

     <img src="./Figures/跃迁.png" width="50%">

     </div>

   - 能级分裂

   - 跃迁定则

     - 允许线
     - 禁戒线

5. **观测量：**

   - 谱线敏感于$T_{eff}$，$\log g$，$\xi_{t}$，$[X/H]$

   - 光谱方法：

     - 高分辨率观测（$R=\lambda/\Delta\lambda>20000$）；
     - 谱线证认；
     - 定量分析谱线；

   - 谱线轮廓和等值宽度

     - 吸收线形成：与连续谱相反, 谱线的辐射来自比较大的光深范围, 它们的**线翼**（Line wings）来自**恒星大气的内部**，而**线心**（Line core）来自**恒星大气的高层**。

     - **谱线轮廓**：改正了仪器的影响后的谱线的真实形状，是**谱线强度按频率的分布**，定义为
       $$
       A_{\nu}\equiv\frac{F_{\nu}}{F_{c}}
       $$


       其中$F_{\nu}$表示恒星表面频率为ν的辐射流，$F_{c}$表示恒星表面连续谱的辐射流。

     - **谱线深度**：$R_{\nu}\equiv(F_{c}-F_{\nu})/F_{c}=1-A_{\nu}$

     - **等值宽度**：以连续光谱背景的强度为单位，取长为一个单位强度的矩形，令其面积等于谱线所占的面积，则矩形的宽就是等值宽度（以波长标度表示）。谱线所占的面积
       $$
       W=\int \left(\frac{F_{c}-F_{\lambda}}{F_{c}}\right)d\lambda=\int^{\lambda_{2}}_{\lambda_{1}}1d\lambda
       $$
       <div align=center>

       <img src="./Figures/等值宽度.png" width="50%">

       </div>

     - **半峰宽度**：谱线轮廓的半高（深）所对应的轮廓宽度。

       - 发射线：用峰高$I_{0}$和半峰宽$\Delta\nu$来表示谱线轮廓；

         <div align=center>

         <img src="./Figures/发射线半宽.png" width="50%">

         </div>

       - 吸收线：吸收线经常用不透明度$\kappa_{\nu}$来描述，频率为$\nu$强度为$I_{0}$的光通过光程为s后，光强为$I_{υ}$，有
         $$
         I_{\nu}=I_{0}e^{-\kappa_{\nu}s}
         $$
         吸收峰$K_{0}$的一半处（$K_{0}/2$）所对应的频率$\Delta\nu$即为吸收线的“半宽度”。

         <div align=center>

         <img src="./Figures/吸收线半宽.png" height="180px" width="70%">

         </div>

6. 谱线致宽

   {0}. **辐射阻尼轮廓**：能级寿命有限

      由海森堡不确定关系
      $$
      \Delta E\cdot\tau=\hbar
      $$
      其中$\tau$为能级寿命。因此，**寿命越短，谱线越宽；寿命越长，谱线越窄**。这种自然宽度又称为**洛伦兹轮廓**
      $$
      \phi_{\nu}=\frac{\gamma/4\pi^{2}}{\left(\nu_{0}-\nu\right)^{2}+\left(\gamma/4\pi\right)^{2}}
      $$
      其中$\gamma=\frac{8\pi^{2}e^{2}\nu_{0}^{2}}{3m_{e}c^{2}}$。

   {0}. **多普勒致宽**：原子在空间作热运动所引起的，原子热运动速度分布满足**麦克斯韦分布**。

      * **多普勒宽度**：
        $$
        \Delta\nu_{D}=\nu_{0}v_{0}/c
        $$
        **高斯轮廓**：

      $$
      \phi_{\nu}=\frac{1}{\Delta\nu_{D}\sqrt{\pi}}e^{-\frac{\left(\nu-\nu_{0}\right)^{2}}{\Delta\nu_{D}^{2}}}
      $$

      * Lorentzian和Gaussian轮廓结合就是大多数恒星的真实谱线轮廓， 叫Voigt轮廓。

      <div align=center>

      <img src="./Figures/Voigt.png" width="50%">

      </div>

   {0}. **压力致宽**：

      {0}. 碰撞（与原子／离子／电子／分子）引起能级变化
      {0}. 速率与压强有关
      {0}. 影响谱线: 展宽，位移，不对称
      {0}. Stark效应：有电场存在时退简并

   {0}. **总吸收轮廓**：Voigt轮廓

   {0}. **外部致宽机制**：

      {0}. 恒星自转
      {0}. 宏观湍流：恒星光球中的气体运动。只是平移而不改变谱线吸收强度。
      {0}. 仪器轮廓致宽

      ​

      ​