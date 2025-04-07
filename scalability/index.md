# Scalability

## Issues

Scalability is a primary concern for any computational device, and NML based processors are no exception. Increasing unit density and decreasing size are the two primary ways of scaling integrated circuits, but decreasing the size of NML units can increase thermal sensitivity, [1][1] and increasing the density can induces interference between separate regions. [2][2] Thankfully, measures can be taken to mitigate each of these effects, some of which have been discussed in previous sections.

## Solutions

As stated previously, the primary scalability concerns with NML are centered around thermal instability and local interference at small unit sizes. Since NML units themselves don't generate enough heat to interfere with the system, it is sufficient to utilize contemporary insulation techniques can be used to prevent external heat transfer. [3][3] [4][4] As for local interference, as unit size decreases, so does the strength of its magnetic field. Furthermore, nanomagnets with strong shape anisotropy are less likely to be influenced by weak fields, which further decreases the risk of internal interference. [5][5] By employing thermal shielding and using NML units with strong shape anisotropy, scaling issues associated with size and density can be mitigated.

## Roadmap

To ensure the scalability and stability of TriMagnetix systems as small scales and high densities, we plan to:

1. Insulate the magnetic lattice againse external heat sources
2. Utilize NML units with strong shape-induced anisotropy
3. Design logic units that are resistant to weak magnetic fields

## References

1. R. Cowburn, M. Welland, "Room temperature magnetic quantum cellular automata", [Science][1], **1466**, 287 (2000)
2. A. Imre, G. Csaba, L. Ji, A. Orlov, G. Bernstein, W. Porod, "Majority logic gate for magnetic quantum-dot cellular automata" [Science][2], **205**, 311 (2006)
3. D. Nikonov, I. Young, "Overview of beyond-CMOS devices and a uniform methodology for their benchmarking", [Proceedings of the IEEE][3], **2498**, 101 (2013)
4. B. Lambson, "Energy Efficient Digital Logic Using Nanoscale Magnetic Devices," [UC Berk.][4] (2013)
5. K. Nanayakkara, I. Vasil’evskii, I. Eremin, O. Kolentsova, N. Kargin, A. Anferov, A. Kozhanov, "Tunable configurational anisotropy of concave triangular nanomagnets", [Journal of Applied Physics][5], **233906**, 119 (2016)

[1]: quantum-cellular-automata.pdf
[2]: majority-logic-for-qca.pdf
[3]: beyond-cmos-benchmarking.pdf
[4]: energy-efficient-digital-logic.pdf
[5]: tunable-concave-triangles.pdf
