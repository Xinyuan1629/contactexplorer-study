# Further evaluation: single training seed

Evaluation seeds repeat evaluation of fixed policies; they are not independent training seeds.
Contact regions are checkpoint-specific. Counts are gated repeated contact steps; bouts are uninterrupted finger-region contacts.
Wilson intervals describe episode sampling only; they do not quantify training-seed variability.

| Job | Successes / episodes | Success rate | Mean terminal step | Contact steps / bouts |
|---|---:|---:|---:|---:|
| contactexplorer_c1250_friction_high_s10003 | 298/384 | 77.60% | 263.3 | 62891/8288 |
| contactexplorer_c1250_friction_high_s10004 | 285/384 | 74.22% | 266.6 | 64918/10550 |
| contactexplorer_c1250_friction_low_s10003 | 354/384 | 92.19% | 220.0 | 57154/5017 |
| contactexplorer_c1250_friction_low_s10004 | 359/384 | 93.49% | 220.8 | 52981/5550 |
| contactexplorer_c1250_nominal_s10003 | 377/384 | 98.18% | 215.7 | 63433/5018 |
| contactexplorer_c1250_nominal_s10004 | 368/384 | 95.83% | 215.8 | 67349/6631 |
| contactexplorer_c2000_friction_high_s10003 | 219/384 | 57.03% | 264.4 | 55524/6386 |
| contactexplorer_c2000_friction_high_s10004 | 258/384 | 67.19% | 259.8 | 56569/7055 |
| contactexplorer_c2000_friction_low_s10003 | 260/384 | 67.71% | 236.3 | 59320/4471 |
| contactexplorer_c2000_friction_low_s10004 | 307/384 | 79.95% | 227.6 | 58258/5239 |
| contactexplorer_c2000_nominal_s10003 | 282/384 | 73.44% | 235.9 | 54585/4549 |
| contactexplorer_c2000_nominal_s10004 | 338/384 | 88.02% | 225.3 | 67242/5743 |
