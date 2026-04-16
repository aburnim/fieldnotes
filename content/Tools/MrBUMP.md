---
aliases:
  - MrBUMP
tags: [tool]
---

#mx #software-dev

> [!info] Info
> Automated molecular replacement pipeline in the [[CCP4]] suite. Takes a target sequence and reflection data, searches for potential MR search models, prepares them, and passes them to [[Phaser]] or MOLREP. Developed by [[Ronan Keegan]] and [[Martyn Winn]] at [[Rutherford Appleton Laboratory|STFC Rutherford Appleton Laboratory]]. Updated to leverage AlphaFold-predicted models.

## Key Relationships
- [[Ronan Keegan]] -- primary developer
- [[Martyn Winn]] -- co-developer
- [[Phaser]] -- MrBUMP passes search models to Phaser for the MR step
- [[CCP4]] -- distributed as part of the suite
