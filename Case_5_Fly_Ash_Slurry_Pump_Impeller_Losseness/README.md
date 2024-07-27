# Conversation link:

[case-5](https://aws3.link/FaFpHy)

**Root Cause:** Crack formation in the impeller of a Fly Ash Slurry Pump

Observations from Different Positions of the Motor and Pump

1. **Pump NDE (Non-Drive End) Bearing:**
    - **Horizontal and Vertical Directions:**
        - Dominant 2x rpm component observed.
        - Presence of high-frequency harmonic components and random vibrations.
2. **Pump DE (Drive End) Bearing:**
    - **Axial Direction:**
        - Significant axial vibration (more than 50% of radial component).
        - Dominated by the 4x rpm component.
        - Excessive axial vibration with 23 mm/sec peak.
        - Axial displacement of 260 microns p-p.
    - **Radial Directions (Horizontal and Vertical):**
        - Significant 2x and higher harmonics observed.
        - 2x rpm component was the most dominant (18 mm/sec peak).
3. **Motor DE (Drive End) Bearing:**
    - **Axial Direction:**
        - Minor axial vibration (9 mm/sec peak velocity).
        - Axial displacement of 46 microns p-p.

**Diagnosis Explanation:**

1. **Vibration Signatures:**
    - **NDE Bearing Spectra:** The vibration spectra recorded in both horizontal and vertical directions of the NDE bearing exhibited a dominant 2x rpm component. This indicates an issue related to the rotational speed of the pump, often linked to mechanical looseness or imbalance.
    - **High-Frequency Harmonics:** The presence of high-frequency harmonic components and random vibrations suggests complex fault conditions that could be due to structural issues or resonance.
    - **Axial Vibration:** The significant axial vibration (more than 50% of the radial component) dominated by the 4x rpm component is indicative of severe mechanical looseness and potential flow disturbances from the impeller vanes.
    - **DE Bearing Vibration:** The DE bearing showed excessive axial vibration (23 mm/sec peak) and a dominant 2x rpm component (18 mm/sec peak), confirming heavy axial thrust, typically caused by looseness.
2. **Potential Causes:**
    - **Misalignment:** Misalignment was ruled out as the motor did not exhibit severe axial vibration (only 46 microns p-p displacement and 9 mm/sec peak velocity at the motor DE axial compared to 260 microns and 22 mm/sec at the pump DE axial).
    - **Mechanical Looseness:** The combination of the dominant 2x rpm component and the high axial thrust at the DE bearing pointed towards mechanical looseness. Given the overhung impeller design, axial thrust due to looseness was more pronounced.
    - **Flow Disturbances:** The 4x rpm component was associated with flow disturbances from the impeller vanes, as the number of impeller vanes was four, matching the vane-passing frequency (4x rpm).
3. **Inspection Findings:**
    - **Thrust Bearing Analysis:** The high 2x rpm vibration at the DE bearing indicated heavy axial thrust due to looseness. This axial thrust, combined with the observed vibration patterns, confirmed mechanical looseness.
    - **Impeller Inspection:** Physical inspection revealed a circumferential crack near the hub of the impeller, causing a condition mimicking mechanical looseness. The crack was due to material failure.
4. **Conclusion:**
    - The circumferential crack in the impeller hub resulted in a looseness-like condition, causing the observed vibration patterns. Post-replacement of the impeller, vibration levels significantly decreased, validating the diagnosis.

**What is the Best Possible Help:**

To further confirm the diagnosis and ensure accurate fault detection, the following steps are recommended:

- **Detailed Inspection:** Perform a thorough visual and non-destructive inspection of the impeller to identify any cracks or material failures.
- **Vibration Analysis:** Conduct additional vibration analysis post-replacement to ensure normalized vibration levels.
- **Preventive Maintenance:** Implement regular vibration monitoring and maintenance schedules to detect early signs of similar faults and prevent recurrence.
- **Material Quality Review:** Assess the material quality and operating conditions of the impeller to address potential causes of material failure and enhance durability.

By following these steps, the diagnosis can be confirmed, and measures can be taken to ensure the longevity and efficient operation of the pump."

# Facts:


Misalignment:

1. Angular Misalignment:
   - Characterized by high axial vibration, 180° out-of-phase across the coupling.
   - Typically has high vibration at both 1X and 2X RPM.
   - Can excite many 1X RPM harmonics when severe.

2. Parallel Misalignment:
   - Shows high radial vibration, 180° out-of-phase across coupling.
   - 2X RPM often larger than 1X RPM.
   - When severe, can generate high amplitude peaks at higher harmonics (4X-8X).

3. General Misalignment:
   - Can generate either high amplitude peaks at much higher harmonics (4X-8X) or a series of high frequency harmonics when severe.
   - Coupling type and material can greatly influence the entire spectrum.
   - Does not typically have a raised noise floor.

Bearing Issues:

1. Rolling Element Bearing Failure Stages:
   - Stage 1: Earliest indications appear in ultrasonic frequencies (250,000 - 350,000 Hz).
   - Stage 2: Excitation of bearing component natural frequencies (30K - 120K CPM range).
   - Stage 3: Bearing defect frequencies and harmonics appear with sidebands.
   - Stage 4: Amplitude of 1X RPM is affected, discrete frequencies disappear, replaced by random broadband high frequency noise floor.

Cavitation or Hydraulic Related Issues:

1. Cavitation:
   - Generates random, higher frequency broadband energy.
   - Sometimes superimposed with blade pass frequency harmonics.
   - Indicates insufficient suction pressure (starvation).
   - Can be quite destructive to pump internals if left uncorrected.
   - Often sounds as if "gravel" is passing through pump.

2. Flow Turbulence:
   - Occurs due to variations in pressure or velocity of the fluid.
   - Generates random, low frequency vibration, typically in the range of 50 to 2000 CPM.
   - If surging occurs within a compressor, random broadband high frequency vibration can occur.

Vane Passing Frequency for a Pump:

1. Blade Pass Frequency (BPF) = Number of Blades (or Vanes) X RPM.
2. Large amplitude BPF (and harmonics) can be generated if gap between rotating vanes and stationary diffusers is not equal all the way around.
3. BPF (or harmonic) can sometimes coincide with a system natural frequency causing high vibration.
4. High BPF can be generated if:
   - Impeller wear ring seizes on shaft
   - Welds fastening diffuser vanes fail
   - Abrupt bends in pipe (or duct) are present
   - Obstructions disturb flow
   - Damper settings are incorrect
   - Pump or fan rotor is positioned eccentrically within housing
