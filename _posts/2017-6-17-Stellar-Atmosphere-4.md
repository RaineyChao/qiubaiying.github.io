---

Title: 恒星大气

Date: 2017-6-17

tag:
- Stellar Atmosphere
- Stellar Physics

---

## 第四章 恒星大气的基本方程组

### 第一节 统计平衡方程组

1. 单位体积内原子在各个能级上的占据数为常量，即

   $$\frac{d}{dt}n^{\alpha\beta}_{i}=0$$

   即跃入等于跃出。

2. 讨论$$\alpha$$类原子处于$$\beta$$电离度时

   $$n_{i}\Sigma^{k}_{j\neq i}P_{ij}=\Sigma^{k}_{j\neq i}n_{j}P_{ji}$$

   式中$$P_{ij}$$表示单位时间内原子由$$i$$能级跃迁到$$j$$能级的跃迁几率 ，$$k$$代表连续谱。

3. 讨论$$P_{ij}$$

   - 与辐射场有关

   - 由辐射部分和碰撞部分组成

     $$P_{ij}=R_{ij}+C_{ij}$$

     其中$$R_{ij}$$为辐射跃迁速率，$$C_{ij}$$为碰撞跃迁速率。

   - 辐射跃迁速率$$R_{ij}$$

   - 碰撞跃迁速率$$C_{ij}$$

### 第二节 粒子数守恒和电荷数守恒方程

1. 总粒子数守恒方程

   $$n=n_{e}+\Sigma_{\alpha}\Sigma_{\beta}\Sigma_{i}n^{\alpha\beta}_{i}$$

2. 元素$$\alpha$$的粒子数守恒方程

   $$nX_{\alpha}=\Sigma_{\beta}\Sigma_{i}n^{\alpha\beta}_{i}$$

3. 电荷数守恒方程

   $$n_{e}=\Sigma_{\alpha}\Sigma_{\beta}\beta\Sigma_{i}n^{\alpha\beta}_{i}$$

### 第三节 流体静力学平衡方程

1. 由流体静力学平衡条件

   $$\frac{dP}{dr}=-g\rho$$

   平面平行情况：

   $$dp_{g}+dp_{R}=-g\rho dz$$

### 第四节 辐射转移方程

1. 辐射穿越一介质层$$ds$$后，产生辐射强度变化$$dI_{\nu}$$的原因：

   - 吸收作用：

     $$dI_{\nu}=-\kappa_{\nu}I_{\nu}ds$$

   - 发射作用：

     $$dI_{\nu}=\eta_{\nu}ds$$

   总辐射变化$$dI_{\nu}$$为

   $$\mu\frac{dI_{\nu}}{dz}=-\kappa_{\nu}I_{\nu}+\eta_{\nu}$$

   即

   $$\mu\frac{dI_{\nu}}{d\tau_{\nu}}=I_{\nu}-\frac{\eta_{\nu}}{\kappa_{\nu}}$$

   其中$$d\tau_{\nu}=-\kappa_{\nu}dz$$。定义源函数$$S_{\nu}=\frac{\eta_{\nu}}{\kappa_{\nu}}$$，因此

   $$\mu\frac{dI_{\nu}}{d\tau_{\nu}}=I_{\nu}-S_{\nu}$$

2. 对辐射转移方程两边乘以积分因子$$e^{-\tau_{\nu}/\mu}$$再积分，有辐射转移方程通解

   $$I_{\nu}\left(0\right)=I_{\nu}\left(\tau_{\nu}\right)e^{-\tau_{\nu}/\mu}+\int^{\tau_{\nu}}_{0}S_{\nu}e^{-t_{\nu}/\mu}\frac{dt_{\nu}}{\mu}$$

   右边第一项代表入射辐射的贡献，第二项代表介质层的贡献。

### 第五节 能量平衡方程与能量定理

1. 能量平衡方程：

   恒星大气温度较低，没有热核反应，只有能量输运。有两种方式：

   - 辐射转移（表面$$\rightarrow$$内部$$\tau=1$$的范围，辐射平衡区）
   - 对流转移（晚于F5的恒星在$$\tau=1$$以下的区域内，H、He部分电离区，对流平衡区）

   当恒星大气处于辐射平衡时，任意体元$$dV$$每秒吸收的能量应该与辐射出去的能量相等，即

   $$\int_{\nu}\int_{\omega}\left[\kappa_{\nu}I_{\nu}\left(\tau_{nu},\mu\right)+\eta_{\nu}\left(\tau_{\nu}\right)\right]\frac{d\omega}{4\pi}d\nu=0$$

   该式称为能量平衡方程。

2. 能量定理：

   将辐射转移方程左侧对频率$\nu$和空间角$\omega$积分

   $$\int_{\nu}\int_{\omega}\mu\frac{dI_{\nu}}{dz}d\nu d\omega=\frac{d}{dz}\int_{\nu}\int_{\omega}\mu I_{\nu}d\nu d\omega=\int_{\nu}\int_{\omega}\left(-\kappa_{\nu}I_{\nu}+\eta_{\nu}\right)d\nu d\omega=0$$

   又$$\pi F=\int^{\infty}_{0}\pi F_{\nu}d\nu=\int_{\nu}\int_{\omega}\mu I_{\nu}d\nu d\omega$$，因此

   $$\frac{d\pi F}{dz}=0$$

   该式称为能量定理，仅对总辐射流成立。又$$\pi F$$表示恒星向外的净辐射流，因此

   $$\pi F=\frac{L}{4\pi R^{2}}=\sigma T^{4}_{eff}=Const.$$

   恒星大气处于辐射平衡时，总辐射流应该是由辐射方式和对流方式传递的能量流之和，即

   $$\pi F=\pi F_{rad}+\pi F_{conv}=\sigma T^{4}_{eff}=Const.$$

### 第六节 对流

1. 史瓦西条件推导：

   考虑流体元因浮力作用上浮一段距离$$dr$$，其内部密度与环境密度的差为

   $$\Delta\rho\left(r+dr\right)=\Delta\rho\left(r\right)+dr\cdot\frac{d}{dr}\left(\Delta\rho\right)$$

   其中$$\Delta\rho\left(r\right)<0$$，$$dr>0$$。当$$\frac{d}{dr}\left(\Delta\rho\right)\le0$$时，$$\Delta\rho\left(r+dr\right)<0$$，即流体密度仍低于环境密度，流体可以继续上浮。因此，对流非稳定性条件为

   $$\frac{d}{dr}\left(\Delta\rho\right)\le0$$

   考虑化学组分均匀的区域，有物态方程

   $$\rho=\rho\left(P,T\right)$$

   写出了$$\ln P$$的全微分

   $$d\ln P=\left(\frac{\partial\ln \rho}{\partial\ln P}\right)_{T}d\ln P+\left(\frac{\partial\ln \rho}{\partial\ln T}\right)_{P}d\ln T$$

   应用于流体元内部有

   $$\frac{d\ln \rho_{e}}{dr}=\left(\frac{\partial\ln \rho}{\partial\ln P}\right)_{T}\frac{d\ln P_{e}}{dr}+\left(\frac{\partial\ln \rho}{\partial\ln T}\right)_{P}\frac{d\ln T_{e}}{dr}$$

   应用于流体元环境有

   $$\frac{d\ln \rho_{R}}{dr}=\left(\frac{\partial\ln \rho}{\partial\ln P}\right)_{T}\frac{d\ln P_{R}}{dr}+\left(\frac{\partial\ln \rho}{\partial\ln T}\right)_{P}\frac{d\ln T_{R}}{dr}$$

   两式相减得

   $$\frac{d}{dr}\left(\Delta\ln \rho\right)=\frac{d\ln \rho_{e}}{dr}-\frac{d\ln \rho_{R}}{dr}=\left(\frac{\partial\ln \rho}{\partial\ln P}\right)_{T}\left(\frac{d\ln P_{e}}{dr}-\frac{d\ln P_{R}}{dr}\right)+\left(\frac{\partial\ln \rho}{\partial\ln T}\right)_{P}\left(\frac{d\ln T_{e}}{dr}-\frac{d\ln T_{R}}{dr}\right)$$

   又$$\Delta P=P_{e}-P_{R}=0$$，因此

   $$\frac{d}{dr}\left(\Delta\ln \rho\right)=-\left(\frac{\partial\ln \rho}{\partial\ln T}\right)_{P}\left(\frac{d\ln T_{R}}{dr}-\frac{d\ln T_{e}}{dr}\right)$$

   由对流非稳定性条件$$\frac{d}{dr}\left(\Delta\rho\right)\le0$$，有

   $$\frac{d\ln T_{R}}{dr}\le\frac{d\ln T_{e}}{dr}$$

   引入压强标高

   $$H_{P}\equiv-\frac{dr}{d\ln P}=-P\frac{dr}{dP}$$

   当$$P$$随$$r$$增大而减小时，$$H_{P}>0$$。因此，两侧同乘$$H_{P}$$

   $$\left(\frac{d\ln T}{d\ln P}\right)_{R}\ge \left(\frac{d\ln T}{d\ln P}\right)_{e}$$

   定义$$\nabla_{R}\equiv\left(\frac{d\ln T}{d\ln P}\right)_{R}$$，$$\nabla_{e}\equiv\left(\frac{d\ln T}{d\ln P}\right)_{e}$$,有

   $$\nabla_{R}\ge \nabla_{e}$$

   因假设对流流体元来不及与环境温度交换，即绝热，有$$\nabla_{e}=\nabla_{ad}$$，因此，

   $$\nabla_{R}\ge \nabla_{ad}$$
