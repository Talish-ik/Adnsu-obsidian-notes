![[Laboratory Physics.docx]]
The first hw was to learn the first lab work:

# **1. DETERMINATION OF THE MOMENT OF INERTIA OF THE SOLIDS USING A TORSION PENDULUM**

<mark>Translational motion</mark> - A motion in which all points of a body move with an equal speed and with the same trajectory as the body itself.

<mark>Rotational motion</mark> - A motion in which body's components describe concentric circles at various speeds. So we need to express various dynamical values using angular velocity which is the same for every part of the body
   ![108](attachments/Pasted%20image%2020260917183045.png)or  ![148](attachments/Pasted%20image%2020260917182544.png)

$m_i$ - the mass of body's particles
$r_i$ - the distance from particle to the axis of rotation
$p$ - density
$V$- volume of the body

==Torsion pendulum== - a body hanged on a thread in a magnetic field. When rotating such a body around a fixed point torque appears and is proportional to the angular velocity. And the body begins to perform harmonic oscillations.
Apply the basic equation to the body that performs harmonic oscillations.  
$M = J\frac{d^2φ}{dt^2}$  (equation 1)
Where:
$M$ - torque relative to the rotational axis
$J$ - moment of inertia with respect to the same axis
$\frac{d^2φ}{dt^2}$ - angular acceleration

For small angles torque is proportional to $M = Gφ$. Where $G$ is module of torsion and has a constant numerical value for different threads. Using this we can write the first equation as  $J*\frac{d^2\phi}{dt^2}$  or  $\frac{d^2\phi}{dt^2} + \frac{G}{J}$ which is the differential equation of harmonic oscillations.

## **Device description.**
![](attachments/Pasted%20image%2020260917183126.png)
1. Base
2. Counters with arm
3. Collet chuck
4. Metallic suspension
5. Disc with two clamps
6. Also an etalon and the test loads
With this setting you can determine the moment of inertia of any object with mass than 5 kg located in the center.

First we need to define the moment of inertia of the device itself. For this we center the disk in vertical axis using clamps. Then by turning the disk by a small angle φ, achieve the torsional oscillations. Using a stopwatch determine the time t₀, necessary to perform n₀=20-30 oscillations while counting the period T₀=t₀/n₀. Connection between period T₀, moment of inertia J₀ and modulus of torsion G is given by $T_{0}=2\pi\sqrt{\frac{J_{0}}{G}}$. However this formula has unknown variables J₀ and G. To find them an etalon cylinder with a known moment of inertia is set to disk  $J=\frac{1}{2}mr^2$  where m - mass of the cylinder, r - radius.
If the cylinder and the device rotate parallel at distance d, then according to Steiner's theorem the moment of inertia of the cylinder:
$J_{1}=\frac{1}{2}mr^2+md^2$while the period is $T_{1}=2\pi\sqrt{\frac{J_{0}+J_{1}}{G}}$

From these two expressions we get
$J_{0}=\frac{T^2_{0}J_{1}}{T^2_{1}-T^2_{0}}$       $G=\frac{4\pi^2*J_{1}}{T^2_{1}-T^2_{0}}$

When the etalon cylinder is replaced by another load, the period will be $T=2\pi\sqrt{\frac{J_{0}+J}{G}}$
Where J is the moment of inertia of the load. Substituting values of J and G we get:
$J=\frac{T^2-T^2_{0}}{T^2_{1}-T^2_{0}}m(\frac{1}{2}r^2+d^2)$ (formula 10)

## Procedure and analysis
1. Align the installation. Turn the disc at a small angle to oscillate the system about a vertical axis. Measure time with stopwatch in which 20-30 oscillations are completed. Calculate the period of oscillation of the device. The measurements must be repeated at least three times.
2. Measure the weight of the etalon and its radius. Put the etalon on a disk of the devise, so that the etalon's symmetry axis is parallel to the axis of rotation of the device. Measure the distance between the axles.
3. Determine, as in fist step, the period of the system with the etalon load.
4. After removing the etalon from the disc , install the study load on it and determine the period of oscillation using the method stated above.
5. Substituting the values in the formula 10.
6. The measurements are repeated 3-5 times, obtained numerical values are recorded in the table; and calculate the relative measurements error.

| №   | T₀, $s$ | T₁, $s$ | T, $s$ | m, $kg$ | r, $m$ | d, $r$ | J, $kg*m^2$ |
| --- | ------- | ------- | ------ | ------- | ------ | ------ | ----------- |
| 1   |         |         |        |         |        |        |             |
| 2   |         |         |        |         |        |        |             |
| 3   |         |         |        |         |        |        |             |
