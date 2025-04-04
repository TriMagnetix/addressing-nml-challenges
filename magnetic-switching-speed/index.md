# Magnetic Switching Speed

## Issues

A core concern with nanomagnetic logic devices is whether or not its performance can match semiconductor logic devices. Many NML systems rely on a clocked external field applied to a region of the device, and this can negatively impact the system's speed in ways that seem to substantiate these concerns. [1][1] Another type of NML device utilizes an inverter chain that requires system magnetization to be switched between clock cycles, which further degrades the overall data throughput. [2][2] Using these methods at larger scales degrades performance proportional to the size of the system, although component size reduction and localized electrically-induced switching can greatly mitigate such issues. [3][3]

## Solutions

Contemporary nanomagnetic dot and inverter chain-based architectures certainly are subject to the challenges described above, but switching speed has been shown to increase in structures with multiple axes of magnetization. [3][3] [4][4] Magnetic vortices in particular have been used to achieve picosecond switching speeds that are on-par with competing semiconductor technology. [5][5] Furthermore, nanomagnetic logic units of all morphologies see their switching speeds and energies decrease as their physical size decreases. [3][3] Since multi-axial structures can remain stable at nanometer scales, unlike semiconductors, they can further benefit from increased locality and a comparatively lower need for redundancy. [4][4] These factors together mean that a system of nanomagnetic triangles at such a scale would require fewer components, and the holistic system switching speed would become even more favorable compared to semiconductor counterparts.

## Roadmap

To ensure switching speeds that are on-part or better than semiconductor switching speeds, we plan to:

1. Use multi-axial magnetic structures, such as nanomagnetic triangles, to facilitate quick switching speeds.
2. Target a nanometer-scale feature size to lessen switching energy and time.
3. Take advantage of the unique switching mechanics of multiaxial geometry to produce more complicated gates with fewer computational units.
4. Track the current state of the system so that magnetization does not need to be switched between clock cycles.

## References

1. M. Becherer, J. Kiermaier, S. Breitkreutz, I. Eichwald, G. Csaba†, D. Schmitt-Landsiedel, "Nanomagnetic Logic Clocked in the MHz Regime", [ESSDERC][1], **276** (2013)
2. I. Eichwald, A. Bartel, J. Kiermaier, S. Breitkreutz, G. Csaba, D. Schmitt-Landsiedel, M. Becherer, "Nanomagnetic Logic: Error-Free, Directed Signal Transmission by an Inverter Chain", [IEEE Transactions on Magnetics][2], **4332**, 48, (2012)
3. T. Devolder, A. Le Goff, V. Nikitin, "Size-dependence of nanosecond-scale spin-torque switching in perpendicular magnetized tunnel junctions", [Physical Review B][3], **224432**, 93 (2016)
4. K. Nanayakkara, I. Vasil’evskii, I. Eremin, O. Kolentsova, N. Kargin, A. Anferov, A. Kozhanov, "Tunable configurational anisotropy of concave triangular nanomagnets", [Journal of Applied Physics][4], **233906**, 119 (2016)
5. R. Hertel, S. Gliga, M. Fähnle, C. Schneider, "Ultrafast Nanomagnetic Toggle Switching of Vortex Cores", [Physical Review Letters][5], **117201**, 98 (2007)


[1]: nml-clocked-in-mhz.pdf
[2]: inverter-chain.pdf
[3]: size-dependence-of-switching.pdf
[4]: tunable-concave-triangles.pdf
[5]: vortex-core-switching.pdf
