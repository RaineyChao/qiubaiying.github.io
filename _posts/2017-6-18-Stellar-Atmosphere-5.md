---

Title: 恒星大气

Date: 2017-6-18

Tag:

- Stellar Atmosphere
- Stellar Physics

---

## 第五章 恒星大气模型

### 第一节 基本假设

1. 恒星大气层为平面平行层，在每一层内一切物理和化学性质都是均匀的。
2. 恒星大气处于稳定状态，不随时间变化。
3. 大气层处于流体静力学平衡状态，作用在大气层内任意流体元上的力只有引力和辐射压力，忽略磁场、转动和潮汐力的影响。
4. 恒星大气层是辐射平衡的，没有能量产生，满足能量定律。
5. 大气由氢和氦组成。

### 第二节 灰大气模型

1. **基本假设：**

   - 不透明度与频率无关，即

     $$\kappa_{\nu}=\bar{\kappa}$$

   - 恒星大气处于热动平衡状态，满足

     $$\left\{\begin{aligned}&\frac{\eta_{\nu}}{\kappa_{\nu}}=B_{\nu}\left(T\right)\\&S_{\nu}(\tau)=B_{\nu}(T(\tau))\\&B_{\nu}(T)=\frac{2h\nu^{3}}{c^{2}}\frac{1}{e^{h\nu/kT}-1}\end{aligned}\right.$$

2. **模型优点：**

   {0}. 基本方程组之间的相关性被忽略
   {0}. 方程可单独求解，计算简单


1. **辐射转移方程通解：**

    已知辐射转移方程

    $$\mu\frac{dI_{\nu}}{d\tau_{\nu}}=I_{\nu}-S_{\nu}$$

    由于在灰大气近似下不透明度与频率无关，即有

    $$\mu\frac{dI}{d\tau}-I=-S$$

    其中$$I=\int^{\infty}_{0}I_{\nu}d\nu$$，$$S=\int^{\infty}_{0}S_{\nu}d\nu$$。两侧同乘积分因子$$e^{-\tau/\mu}$$

    $$\frac{d}{d\tau}\left(Ie^{-\tau/\mu}\right)=-\frac{1}{\mu}Se^{-\tau/\mu}$$

    积分可得

    $$Ie^{-\tau/\mu}\Bigg|^{\tau_{2}}_{\tau_{1}}=-\int^{\tau_{2}}_{\tau_{1}}S\left(t\right)e^{-\tau/\mu}\frac{dt}{\mu}$$

    即

    $$I\left(\tau_{1},\mu\right)=I\left(\tau_{2},\mu\right)e^{-\frac{\tau_{2}-\tau_{1}}{\mu}}+\int^{\tau_{2}}_{\tau_{1}}S\left(t\right)e^{-\frac{t-\tau_{1}}{\mu}}\frac{dt}{\mu}$$

    该式为辐射转移方程通解。

    <img src="/Figures/Stellar-Atmosphere/大气辐射.png" width="50%">

    当$$\mu\ge0$$时，

    $$I\left(\tau,\mu\right)=lim_{\tau_{2}\rightarrow\infty}I\left(\tau_{2},\mu\right)e^{-\frac{\tau_{2}-\tau}{\mu}}+\int^{\infty}_{\tau}S\left(t\right)e^{-\frac{t-\tau}{\mu}}\frac{dt}{\mu}$$

    利用边界条件$$lim_{\tau_{2}\rightarrow\infty}I\left(\tau_{2},\mu\right)=0,0\le\mu\le1$$

    $$I\left(\tau,\mu\right)=\int^{\infty}_{\tau}S\left(t\right)e^{-\frac{t-\tau}{\mu}}\frac{dt}{\mu},0\le\mu\le1$$	

    当$$\mu\le0$$时，

    $$I\left(\tau,\mu\right)=I\left(0,\mu\right)e^{-\frac{\tau}{\mu}}+\int^{0}_{\tau}S\left(t\right)e^{-\frac{t-\tau}{\mu}}\frac{dt}{\mu}$$	

    利用边界条件$$\tau=0,I\left(0,\mu\right)=0,-1\le\mu\le0$$

    $$I\left(\tau,\mu\right)=-\int^{\tau}_{0}S\left(t\right)e^{-\frac{t-\tau}{\mu}}\frac{dt}{\mu},-1\le\mu\le0$$	

    在恒星表面只考虑向外辐射$$\tau=\tau_{1}=0,\mu\ge0$$

    $$I\left(0,\mu\right)=\int^{\infty}_{\tau}S\left(t\right)e^{-\frac{t}{\mu}}\frac{dt}{\mu}$$


1. **平均辐射强度、辐射流和K-积分的表达式**

   - 辐射强度：$$I_{\nu}=I_{\nu}\left(\tau_{\nu},\mu\right)$$

   - 平均辐射强度：$$J_{\nu}=\frac{1}{2}\int^{+1}_{-1}I_{\nu}d\mu$$

   - 辐射流：$$F_{\nu}=\frac{1}{\pi}\int I_{\nu}\cos\theta d\omega$$

   - K-积分：

     引入辐射场矩的一般形式：$$\frac{1}{2}\int^{+1}_{-1}I_{\nu}\mu^{n}d\mu$$

     零阶辐射场矩：$$J_{\nu}=\frac{1}{2}\int^{+1}_{-1}I_{\nu}d\mu$$

     一阶辐射场矩：$$H_{\nu}=\frac{1}{2}\int^{+1}_{-1}I_{\nu}\mu d\mu\equiv\frac{1}{4}F_{\nu}$$（爱丁顿辐射流）

     二阶辐射场矩：$$K_{\nu}=\frac{1}{2}\int^{+1}_{-1}I_{\nu}\mu^{2} d\mu$$（K-积分）

2. $$\tau\gg1$$**辐射转移方程的渐进式**

   当$$\tau\gg1$$时，即由恒星大气深入到恒星内部，物理状态接近热动平衡，根据克希霍夫定律有$$S_{\nu}=B_{\nu}$$，并且辐射各向均匀。

   将某一光深处的$$I_{\nu}$$展开成$$\mu$$的级数

   $$I_{\nu}\left(\mu\right)=I_{\nu0}+I_{\nu1}\mu+I_{\nu2}\mu^{2}+\cdots$$

   代入辐射转移方程

   $$\Sigma^{\infty}_{n=0}\mu^{n+1}\frac{dI_{\nu n}}{d\tau_{\nu}}=\Sigma^{\infty}_{n=0}I_{\nu n}\mu^{n}-B_{\nu}\left(\tau_{\nu}\right)$$

   根据$$\mu$$的任意性，对应项系数相等

   $$I_{\nu0}=B_{\nu}\\I_{\nu1}=\frac{dI_{\nu0}}{d\tau_{\nu}}=\frac{dB_{\nu}}{d\tau_{\nu}}\\\vdots\\I_{\nu n}=\frac{d^{n}B_{\nu}}{d\tau_{\nu}^{n}}$$

   由此可得

   $$I_{\nu}\left(\mu\right)=B_{\nu}+\mu\frac{dB_{\nu}}{d\tau_{\nu}}+\mu^{2}\frac{d^{2}B_{\nu}}{d\tau_{\nu}^{2}}+\cdots=\Sigma^{\infty}_{n=0}\mu^{n}\frac{d^{n}B_{\nu}}{d\tau_{\nu}^{n}}$$

   代入$$J_{\nu}$$、$$H_{\nu}$$、$$K_{\nu}$$表达式，并忽略高阶项

   $$\left\{\begin{align}&J_{\nu}\approx B_{\nu}\left(\tau_{\nu}\right)\\&H_{\nu}\approx \frac{1}{3}\frac{dB_{\nu}}{d\tau_{\nu}}\\&K_{\nu}\approx \frac{1}{3}B_{\nu}\left(\tau_{\nu}\right)\end{align}\right.$$

   又$$H_{\nu}=\frac{1}{4}F_{\nu}$$，$$\frac{d}{d\tau_{\nu}}=-\frac{1}{\kappa_{\nu}}\frac{d}{dz}$$，

   $$F_{\nu}\left(\tau_{\nu}\right)=-\frac{4}{3}\frac{1}{\kappa_{\nu}}\frac{dB_{\nu}}{dT}\frac{dT}{dz}$$

3. **灰大气情况**

   以灰大气条件代入能量平衡方程，可得

   $$J=S$$

   即有

   $$\mu\frac{dI}{d\tau}=I-\frac{1}{2}\int^{+1}_{-1}Id\mu$$

   称为灰大气总辐射强度的微分-积分方程，有边界条件：$$\tau=0$$时，$$I\left(0,\tau\right)=0,-1\le\mu\le1$$

   两边对所有角度积分可得

   $$\frac{dF/4}{d\tau}=J-J=0$$

   即

   $$F/4=H=Const.$$

   两边同乘$$\mu$$并积分

   $$\frac{dK}{d\tau}=\frac{F}{4}-J\int^{1}_{-1}\mu d\mu=F/4$$

   因此

   $$K=\frac{1}{4}F\tau+Const.$$

   又$$\tau\gg1$$，且$$K=1/3J$$可得渐近解

   $$J=\frac{3}{4}F\cdot\tau$$

   灰大气温度分布：$$T^{4}\left(\tau\right)=\frac{\pi}{\sigma}J\left(\tau\right)=\frac{\pi}{\sigma}\frac{3}{4}F\cdot\tau$$

4. **灰大气的近似解**

   精确解为$$J=\frac{3}{4}F\left(\tau+q\left(\tau\right)\right)$$

   其中$$q\left(\tau\right)$$称为Hopf函数，表示精确解与近似解的差。

   爱丁顿假设$$q\left(\tau\right)=C$$，代入辐射转移方程通解并由边界条件可解得

   $$C=2/3$$

   即

   $$J=\frac{3}{4}F\left(\tau+\frac{2}{3}\right)$$

   该式称为爱丁顿的灰大气近似解。

5. **灰大气下得温度分布**

   由上可得

   $$T^{4}\left(\tau\right)=\frac{\pi}{\sigma}J\left(\tau\right)=\frac{\pi}{\sigma}\frac{3}{4}F\cdot\left(\tau+2/3\right)$$

   又$$\pi F=\sigma T_{eff}^{4}$$

   $$T^{4}\left(\tau\right)=\frac{3}{4}T_{eff}^{4}\left(\tau+2/3\right)$$

6. **临边昏暗现象**

   由爱丁顿近似解

   $$I\left(0,\mu\right)=\frac{3}{4}F\left(\mu+2/3\right)$$

   因此

   $$\frac{I\left(0,\mu\right)}{I\left(0,1\right)}=\frac{2}{5}\left(1+\frac{3}{2}\mu\right)$$

7. **罗色兰平均值**

   非灰大气$$\kappa_{\nu}$$与频率有关，采用平均值$$\bar\kappa$$。罗色兰提出采用$$\tau\gg1$$时的$$F_{\nu}$$作为权重计算$$\bar\kappa$$，即

   $$\frac{1}{\bar\kappa_{R}}=\frac{\int^{\infty}_{0}\frac{1}{\kappa_{\nu}}\frac{\partial B_{\nu}}{\partial T}d\nu}{\int^{\infty}_{0}\frac{\partial B_{\nu}}{\partial T}d\nu}$$

### 第二节 局部热动平衡（LTE）大气模型