# Write Operation Power Efficiency

## Issues

Although NML devices are often lauded for their power efficiency, there are some scenarios where their write efficiency can fall short of expectations. This can be particularly problematic in write-heavy applications. This primarily occurs when utilizing a material with low coercivity, switching magnetization against the hard-axis, or a combination of the two. If a device uses a localized magnetic field as opposed to inline spin orbit torque switching, this effect is further exacerbated. [1][1] [2][2]

## Solutions

It is important to note that each of the issues described above are situational, and they can be designed around to mitigate higher write energy costs. Tuning the permalloy ratio to have a higher coercivity or using a layered magnetic structure to induce higher spin-torque ratios can greatly decrease switching energy. [3][3] [4][4] Combining this with a design that positions ingress points so that they effect the weak axis of magnetization will bring the write energy down even lower. [5][5] Since each one of these issues has a direct solution, it would be quite realistic to design a device that does not succumb to high energy cost for write operations.

## Roadmap

To help ensure that write operations are carried out efficiently, we plan to:

1. For processing units, select a permalloy ratio with a high enough coercivity while remaining stable
2. For ingress points, utilize a layered magnetic material that increases spin torque in order to enable electrically induced magnetic switching
3. Position ingress points so they are parallel to an underlying processing unit to more efficiently impart its magnetic field.

## References

1. Y. Lee, K. Koo, K. Lee, H. Yang, "Spin–orbit torque-assisted switching in magnetic insulator thin films", [Nature Communications][1], **12688**, 7 (2016)
2. M. Li, X. Zhao, X. Zhang, L. Xu, "Spin–orbit torque in van der Waals-layered materials and devices", [Advanced Science][2], **2100847**, 8 (2021)
3. A. Yang, M. Liu, H. Wang, "Spin-orbit torque magnetization switching in MoTe₂/permalloy heterostructures", [arXiv preprint][3], arXiv:2006.16618 (2020)
4. L. Wang, Y. Bai, D. Wang, "Spin wave-assisted reduction in switching field of highly coercive FePt by exchange-coupled permalloy layer", [Nature Communications][4], **1537**, 4 (2013)
5. K. Nanayakkara, I. Vasil’evskii, I. Eremin, O. Kolentsova, N. Kargin, A. Anferov, A. Kozhanov, "Tunable configurational anisotropy of concave triangular nanomagnets", [Journal of Applied Physics][5], **233906**, 119 (2016)

[1]: spin-torque-switching.pdf
[2]: spin-torque-devices.pdf
[3]: spin-torque-in-heterostructures.pdf
[4]: reduction-in-switching-field.pdf
[5]: tunable-concave-triangles.pdf
