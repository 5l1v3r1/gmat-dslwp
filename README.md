# gmat-dslwp

This is a modified version of GMAT-R2019aBeta1 that implements delta-range
measurements for simulation and estimation of DSLWP-B VLBI observations.

This repository includes the modified GMAT-R2019aBeta1 binary and source trees
as separate git submodules, and some scripts for DSLWP-B simulation.

For a quick test, you can run

```
gmat-dslwp-binary/GMAT/R2019aBeta1/bin/GMAT-R2019aBeta1 -m -x -r scripts/test-deltarange.script 
```

and check the output file at `gmat-dslwp-binary/GMAT/R2019aBeta1/output/DSLWP-B.gmd`

