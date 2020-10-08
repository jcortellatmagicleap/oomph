# oomph
The EclipseSource Oomph Profile...modified to use 2020-03 instead of 2020-06 or later.

2020-06 has the 4.16 platform. That's problematic for anyone on Ubuntu 16.04.
The SWT in Eclispe 4.16 depends on GTK 3.20, and Ubuntu 16.04 has GTK 3.18. In
fact, Eclipse says on their website that 4.16 has been tested and validated with
Ubuntu 20.04 only. It also says there that SWT requires GTK 3.20 or newer.

See https://www.eclipse.org/projects/project-plan.php?planurl=http://www.eclipse.org/eclipse/development/plans/eclipse_project_plan_4_16.xml

With GTK 3.18 (Ubuntu 16.04), warnings are generated to stdout/stderr, and more
importantly, certain functionality doesn't work (e.g., you can't open file chooser).


