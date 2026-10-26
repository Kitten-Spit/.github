# Kitten Spit Labs

An experimental robotics and materials lab, and an [xoxd.ai](https://xoxd.ai) company.

We build instruments and tooling for work that does not fit on a catalogue shelf:

- **Ultrasonics:** power ultrasonics, resonator design and drive electronics
- **Automation:** industrial and biotech fluid handling, open-hardware motion platforms
- **Materials:** polymer processing and metamaterials research
- **Measurement:** interferometry, optics and calibrated sensing

## How we work

- **Specifications as code.** Designs are parameterised in [Dhall](https://dhall-lang.org), a typed configuration language. One source of truth drives CAD, simulation and documentation.
- **Numerical work in [Futhark](https://futhark-lang.org).** A purely functional, data-parallel language that compiles to GPU and multicore code. Our public building blocks include [futhark-bessel](https://github.com/Kitten-Spit/futhark-bessel), provenance-clean Bessel functions for Futhark.
- **Verified before built.** Geometry is checked numerically, parts are proven with finite element analysis, circuits are simulated, and every fit is tested with a coupon print before the real part is made.
- **Open where we can.** Tooling and libraries are published when they are useful to others.

The lab grew out of the original Kitten Spit proof of concept; those repositories are archived here for history.
