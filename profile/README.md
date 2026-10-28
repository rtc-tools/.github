<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/rtc-tools/rtc-tools/master/doc/images/rtc-tools-horizontal-white.svg">
    <img src="https://raw.githubusercontent.com/rtc-tools/rtc-tools/master/doc/images/rtc-tools-horizontal-color.svg" alt="RTC-Tools logo" width="50%">
  </picture>
</p>

RTC-Tools is an open-source, domain-agnostic Python framework for modeling,
simulating, and optimizing dynamic systems. Its modular and extensible design
makes it well suited for the operational optimization and control of networked
systems, from canals, reservoirs, and pumps in water management to hydropower,
batteries, and heat networks in energy.

Models can be written in Python or Modelica, and the framework handles both
linear and nonlinear optimization problems with continuous or discrete
decisions. Built on top of [CasADi](https://web.casadi.org/), RTC-Tools also
supports multi-objective optimization and optimization under uncertainty. It
works with open-source solvers such as [HiGHS](https://highs.dev/),
[IPOPT](https://coin-or.github.io/Ipopt/), and [Bonmin](https://github.com/coin-or/Bonmin),
as well as commercial solvers such as [Gurobi](https://www.gurobi.com/),
[CPLEX](https://www.ibm.com/products/ilog-cplex-optimization-studio),
[Xpress](https://www.fico.com/en/products/fico-xpress-optimization), and
[Knitro](https://www.artelys.com/solvers/knitro/).

Originally developed by [Deltares](https://www.deltares.nl/), RTC-Tools is now
an [LF Energy](https://lfenergy.org/projects/rtc-tools/) project under the Linux
Foundation. It is maintained by Deltares in collaboration with [PortfolioEnergy](https://portfolioenergy.com/) and a growing
community of external contributors.

## Get started

```bash
pip install rtc-tools
```

- [Documentation](https://rtc-tools.readthedocs.io/)
- [Package on PyPI](https://pypi.org/project/rtc-tools/)
- [LF Energy project page](https://lfenergy.org/projects/rtc-tools/)

## Repositories

| Repository | Description |
|---|---|
| [rtc-tools](https://github.com/rtc-tools/rtc-tools) | The RTC-Tools framework |
| [rtc-tools-standard-library](https://github.com/rtc-tools/rtc-tools-standard-library) | Subset of the Modelica Standard Library for RTC-Tools |
| [rtc-tools-casadi-plugins](https://github.com/rtc-tools/rtc-tools-casadi-plugins) | CasADi solver plugin binaries and Python wheels for RTC-Tools |

## Community

- [Contributing](https://github.com/rtc-tools/rtc-tools/blob/master/CONTRIBUTING.md)
- [Governance](https://github.com/rtc-tools/rtc-tools/blob/master/GOVERNANCE.md)
- [Code of Conduct](https://github.com/rtc-tools/rtc-tools/blob/master/CODE_OF_CONDUCT.md)
- [Discussions](https://github.com/rtc-tools/rtc-tools/discussions) and [issues](https://github.com/rtc-tools/rtc-tools/issues)

RTC-Tools is licensed under the [LGPL-3.0](https://github.com/rtc-tools/rtc-tools/blob/master/COPYING.LESSER).
