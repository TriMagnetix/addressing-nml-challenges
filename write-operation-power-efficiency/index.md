# Write Operation Power Efficiency

## Issues

Although NML devices are often lauded for their power efficiency, there are some scenarios where their write efficiency can fall short of expectations. This can be particularly problematic in write-heavy applications. This primarily occurs when utilizing a material with low coercivity, switching magnetization against the hard-axis, or a combination of the two. If a device uses a localized magnetic field as opposed to inline hall-effect switching, this effect is further exacerbated.

## Solutions

It is important to note that each of the issues described above are situational, and they can be designed around to mitigate higher write energy costs. Tuning the permalloy ratio to have a higher coercivity or using a layered magnetic structure to induce higher spin-torque ratios can greatly decrease switching energy. Combining this with a design that positions ingress points so that they effect the weak axis of magnetization will bring the write energy down even lower. Since each one of these issues has a direct solution, it would be quite realistic to design a device that does not succumb to high energy cost for write operations.

## Roadmap

To help ensure that write operations are carried out efficiently, we plan to:

1. For processing units, select a permalloy ratio with a high enough coercivity while remaining stable
2. For ingress points, utilize a layered magnetic material that increases spin torque in order to enable electrically induced magnetic switching
3. Position ingress points so they are parallel to an underlying processing unit to more efficiently impart its magnetic field.

## References
