# Vignette for Rotor Bar Fault:


**Root Cause:** "*Root Cause:** Broken Rotor Bars in the Rotor of Motor

**Diagnosis Explanation:**

Sidebands around motor RPM along with its harmonics are a strong indicator of Rotor bar related issues, Turn to Turn shorts in Windings, Eccentric Rotor, Gear Eccentricity and Backlash, Gear misalignment. Considering the fact, this machine does not have a Gearbox we can eliminate Gear related issues. Stator related issues will have sidebands around 2X of Line Frequency (1/3 of Line Frequency) (User did not give this information) and lets proceed to the next step. Rotor Bar has PPF or Slip as sidebands to Motor RPM and its harmonics. Lets Calculate, PPF and Slip:

- Slip = Synchronous - Motor RPM
- Synchronous = supply frequency * 2/poles
- Assuming supply frequency as 50Hz, poles = 4, synchronous speed = 25Hz (1500 RPM)
- Slip = 1500 - 1490 = 10
- PPF = Slip * poles = 10 * 4 = 40
- Observed sideband = 40 RPM. PPF exactly matches with the expected sidebands of PPF. Which confirms the fault of Rotor Bar fault. Also If there are any sidebands around 2*Supply Frequency can confirm faults related to Stator are also co-existing.

**What is the best possible help:**

To further confirm the rotor bar fault do a Motor Current Signature Analysis and check for side bands around supply frequency separated by slip frequency and its multiples, after confirmation, please have an inspection."


## Facts:
Rotor Bar Problems:

Cause sidebands around motor RPM and its harmonics.
The sidebands are spaced at Pole Pass Frequency (PPF) from the motor RPM and its harmonics.
PPF = Slip * Number of Poles
Slip = (Synchronous Speed - Motor RPM) / Synchronous Speed
Synchronous Speed = (Supply Frequency * 120) / Number of Poles
These sidebands are a strong indicator of rotor bar related issues.