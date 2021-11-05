# This code is deprecated, please use [AccordDATools](https://github.com/Hirlam/AccordDaTools) instead

# Plot-jbdiag

Tools to prepare and plot JB diagnostics

## Prepare data

Compile the code to create diagnostics files for plotting using gfortran or similar

```
cd src
gfortran -o jbdiagnose.x jbdiagnose.f90 -fconvert=big-endian
```

Edit scr/jbdiagnose.bash to fit your needs



## Plotting
### Python dependencies for the plotting
sys,matplotlib,argparse

### Usage

Run the plot programs under src to get info about arguments

