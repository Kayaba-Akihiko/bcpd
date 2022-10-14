# Demo

## Surface Registration and Point set registration
MATLAB scripts under this directory will demonstrate
various examples.

- Nonrigid/Hierarchical Registration
- Nonrigid/Geodesic-Based BCPD
- Nonrigid/Geodesic-Based BCPD++
- Nonrigid/BCPD
- Nonrigid/BCPD++
- Rigid/BCPD

## Shape transfer
Bash scripts in `shapeTransfer` will demonstrate
several examples without MATLAB.  Please check
output files named `transferV[1/2]_y.interpolated.obj`
after executing a script.

## Notes
- It is possible to use BCPD without MATLAB by using
  a command-line interface. MATLAB is used only for
  visualizing registration results.
- If your OS is Windows, please install the MinGW/MSYS
  system to run Bash scripts.
- For Windows, demoPlusPlusLucy.m fails because of a
  memory allocation error originating from the
  MinGW's 32-bit compilation.
