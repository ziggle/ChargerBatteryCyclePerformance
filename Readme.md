# Effect of Charging Algorithm on Retained Internal Charger Battery Capacity

## Introduction

I am beginning to perform testing on various battery charging algorithm to determine their effect on the loss of battery capacity with charge cycles.

## Background

### Definitions

<dl>
<dt>Aging</dt>
<dd>When I hear the term battery aging, I assume loss of battery capacity with respect to charge cycles. Understand that batteries lose capacity while just sitting there — through corrosion. Unless you are in a backup power situation – I spent years working on telcom backup batteries for cell towers – your biggest aging issue is with cycling.</dd>
<dt>Cycle</dt>
<dd>A full-voltage range charge and discharge of the battery. The impact of cycling on capacity is a strong function of how deeply the battery is discharged and how fully charged the battery is cycled. For consistency of results, we only test over the full range.</dd>
<dt>Recovery</dt>
<dd>After being under some electrical stress (charging or discharging), the unstressed battery open-cell voltage will return to an equilibrium value. This has to do with the ions in the battery rearranging after the external stimulus is removed. This is normal and must be accounted for when setting thresholds.</dd>
<dt>Open Cell Voltage</dt>
<dd>The battery voltage with no external stimulus.</dd>
<dt>Constant Current Charging</dt>
<dd>The battery is charged with a constant current that terminates when the cell voltage reaches a defined limit ($V_\text{CV}).</dd>
<dt>Constant Voltage Charging</dt>
<dd>The battery is charged with a constant voltage that is removed when the battery current drops below a specified level ($I_\text{CV}$)</dd>
</dl>

### Charging Scenarios

#### Standard Scenario

Most battery vendors specify a 

## Analysis


## Conclusion
