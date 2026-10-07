# RTC-Tools

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
Foundation. It is maintained by Deltares in collaboration with Portfolio Energy and a growing
community of external contributors.

To learn more, visit the [RTC-Tools repository](https://github.com/rtc-tools/rtc-tools)
or read the [documentation](https://rtc-tools.readthedocs.io/).
