---

Title: 恒星大气

Date: 2017-6-17

Tag:

- Stellar Atmosphere
- Stellar Physics

---

## 第三章 物质函数

### 第一节 大气物质的不透明度

1. **化学元素丰度**：通常指在同一体积内某种元素的原子数目与氢原子数目之比。

2. **重元素**：天文上习惯把氢和氦以外的所有元素统称为重元素。

3. 恒星大气的不透明度

   - 束缚-束缚跃迁
   - 束缚-自由跃迁
   - 自由-自由跃迁
   - 散射过程产生的吸收

4. 热动平衡条件下，各能级间的跃迁和复合应该是处于平衡状态的，称为**细致平衡原理**。因此，

   $$N_{k}B_{ki}I_{\nu}=N_{i}\left(A_{ik}+B_{ik}I_{\nu}\right)$$

   各能级上的粒子占据数服从玻尔兹曼分布

   $$\frac{N_{i}}{N_{k}}=\frac{g_{i}}{g_{k}}e^{-h\nu/kT}$$

   辐射强度满足普朗克函数

   $$B_{\nu}(T)=\frac{2h\nu^{3}}{c^{2}}\frac{1}{e^{h\nu/kT}-1}$$

   比较可得爱因斯坦关系

   $$g_{k}B_{ki}=g_{i}B_{ik}$$

   $$A_{ik}=\frac{2h\nu^{3}_{ik}}{c^{2}}B_{ik}$$

5. 束缚-束缚跃迁过程

6. 束缚-自由跃迁过程

7. 自由-自由跃迁过程

8. 散射过程

   - 汤姆逊散射
   - 康普顿散射
   - 瑞利散射

9. 平均不透明度近似公式

   定义与频率无关的**光学厚度**

   $$d\tau=-\rho\kappa_{P}dz$$

### 第二节 LTE物态方程

1. 物态方程：

   $$\rho=\rho\left(P,T,X_{i}\right)$$

   总压强：

   $$P=P_{g}+P_{R}$$

2. 辐射压强的推导：

   考虑一个各向同性的均匀辐射场$$P_{R}=\frac{1}{3}u$$，熵函数为

   $$dS=\frac{dQ}{T}=\frac{1}{T}\left(dU+P_{R}dV\right)=\frac{1}{T}\left[d\left(V\cdot u\right)+\frac{1}{3}udV\right]$$

   由于熵是全微分，可以得到

   $$\frac{1}{T}\frac{du}{dT}=\frac{4}{3}\left(\frac{du}{dT}\cdot \frac{1}{T}-\frac{u}{T^{2}}\right)$$

   化简可得

   $$u=aT^{4}$$

   又$$I=\frac{c}{4\pi}u=\frac{ac}{4\pi}T^{4}$$，$$F_{R}=\sigma T^{4}$$，因此

   $$a=\frac{4\sigma}{c}$$

3. 气体压强：

   - 大气由原子、离子和电子组成

     $$P_{g}=P_{\alpha}+P_{e}=\left(n_{\alpha}+n_{e}\right)kT$$

     其中$$n_{\alpha}$$为单位体积中原子和离子的总数，$$n_{e}$$是单位体积中电子的总数。

     - 电离物质的平均分子量

       X表示氢的质量丰度，Y表示氦的质量丰度，Z表示重元素的质量丰度，显然$$X+Y+Z=1$$

     - 完全电离状态下的物态方程

       $$P_{g}=nkT=\frac{R}{\mu}\rho T=\frac{R}{\mu_{I}}\rho T + \frac{R}{\mu_{e}}\rho T$$

       $$P=P_{g}+P_{R}=\frac{R}{\mu}\rho T+\frac{1}{3}aT^{4}$$

     - 完全电离情况下的热力学量

       压缩系数：$$\alpha=\left(\frac{\partial\ln\rho}{\partial\ln P}\right)_{T}$$

       膨胀系数：$$\delta=-\left(\frac{\partial\ln\rho}{\partial\ln T}\right)_{P}$$

       引入$$\beta=\frac{P_{g}}{P}$$，有

       $$\alpha=\frac{1}{\beta}$$，$$\delta=\frac{4-3\beta}{\beta}$$

       对于一个完全电离理想气体，单位质量的内能为

       $$u=\frac{3R}{2\mu}T+\frac{aT^{4}}{\rho}$$

     - 部分电离状态下的物态方程

     - 部分电离情况下的热力学量


   - 大气由原子、离子和分子态氢组成

4. Non-LTE物态方程