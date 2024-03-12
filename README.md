# Pattern matching/recognition in DWS graphs
<div align=center>
  <image src=/.github/g2_norm.png width=40%></image>
  <image src=/.github/peak.png width=31%></image>  
</div>

Dynamic Light Scattering (DLS) is a technique used to determine size distributions of small particles in suspension or polymers in solution. $^{[1]}$ Fluctuations in time are analyzed using the intensity or photon autocorrelation function (ACF) $^{[2]}$ which usually decays from zero delay time, and faster dynamics due to smaller particles lead to faster decorrelation of scattered intensity trace. __Diffusing-Wave Spectroscopy (DWS)__ is a technique deriving from DLS which studies  the dynamics of scattered light limited to multiple scattering. In this variation, both transmission (FW) and backscatter (BS) are measured and the seperate correlation functions analyzed to characterize emulsions in motion.

## Signal analysis using ACF
In our case, the auto-correlation function is of the following form

$$g_2(t)=\frac{\langle I(t_0;\mathtt{pixel}) \cdot I(t_0+t;\mathtt{pixel}) \rangle _{\mathtt{pixel}}}{\langle I(t _{\mathtt{age}};\mathtt{pixel}) \rangle \langle I(t _{\mathtt{age}}+t;\mathtt{pixel}) \rangle _{\mathtt{pixel}}}$$

where $I$ represents the intensity function of two factors, $t_0$ the time starting the measurement, $t$ the delayed time, $t _{\mathtt{age}}$ the $k$-th element from $t _{\mathtt{age}}$ and $\mathtt{pixel}$ the particular pixel intensity.

---
$[1]$ Dynamic Ligh Scattering, with applications to Chemistry, Biology, and Physics (Bruce J. Berne, Robert Pecora)</br>
$[2]$ Probability and random processes for electrical and computer engineers (Pg.392) (John A. Gubner)
