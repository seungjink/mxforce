# mx mft

Test calculation for mft with local spin perturbaiton.

## Installation

Copy files to openmx source folder and reinstall

## Usage

```bash
scf.restart.filename             YOUR_SYSTEM_NAME
scf.restart                      c2n # Fixed
scf.restart.spin.mixing          full | atom | average | onside

scf.Restart.Spin.Angle.Theta     0.0
scf.Restart.Spin.Angle.Phi       0.0
scf.restart.read.atom.charge on 
<SCF.Restart.Spin.Angles
...
SCF.Restart.Spin.Angles>
```

