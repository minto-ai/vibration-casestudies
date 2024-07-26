## Link to Conversation:
[case-](https://aws3.link/XfBPJA)

**Root Cause:** High vertical vibration levels in the motor DE and NDE caused by structural or installation issues.

**Diagnosis Explanation:**

The centrifugal fan, handling cold air, is equipped with an impeller mounted directly on the motor shaft. The motor specifications are 90 KW, 2965 RPM, 415V, and 50 Hz, with SKF 6319 and NU 316 ECP bearings for the DE and NDE sides, respectively. Since commissioning, the fan exhibited slight rough vibrations, which gradually increased.

**Vibration Observations:**

- **Vibration Frequency:** The entire vibration was occurring at 1x RPM, initially suggesting unbalance. However, the vertical vibration levels at the motor bearings were significantly higher than the horizontal levels, indicating that unbalance was not the root cause.
- **Phase Analysis:** The phase difference between horizontal and vertical at the outboard bearing was 113°, while at the inboard bearing it was 180°. This directional vibration pattern would not occur in simple unbalance. Moreover, the phase difference between horizontal directions was 90°, and between vertical directions was 157°, further confirming that unbalance was not the primary cause.

The higher vertical vibrations compared to horizontal ones, combined with phase analysis showing inconsistent phase differences, suggested that simple unbalance was not the root cause. Without additional findings, the exact cause of the vertical vibration levels cannot be definitively identified. However, these observations indicated that structural or installation issues might be involved, and further investigation was needed.

**What is the best possible help:**

**Recommended Actions for Further Confirmation:**

- Perform phase analysis at the base plate to confirm the presence of any soft-foot conditions or structural issues.

By implementing these steps, the maintenance team can confirm the diagnosis, address the root cause, and prevent future occurrences with minimal effort.

**Profile Summary:**

- **Machine:** Centrifugal fan in a cold air handling application
- **Fault:** Excessive vertical vibration levels indicating potential structural or installation issues.
- **User Action:** Maintenance team should perform phase analysis at the base plate, inspect and reinforce the base frame, monitor vibration levels, and conduct regular phase analysis to ensure proper anchorage and prevent future issues.

By following these steps, the diagnosis can be investigated further, the root cause addressed, and future occurrences prevented, ensuring continued reliable operation of the seal air fan.

# Facts:

    **Looseness Type B (Lb)**
    - **FG:** **Sub-Synchronous, Synchronous & Harmonic [F_G_4]**
    - **D_D_R:** Radial (H, V)
    - **Technique:** Time Waveform
    - **Mathematical Formula Wrt to (m, n, k):** \( f = \frac{1}{n} \times \text{RPM} \) (where \( n = 1, 2, 3, \ldots \))
    - **Rules of Thumb:** N/A
    - **Phase Characteristics:** 
    - Phase readings may show two unstable reference points.
    - **Differentiator:**
    - Type B is generally caused by loose pillow block bolts, cracks in the frame structure, or bearing pedestal.
    - The spectrum shows multiple peaks at different frequencies (0.5x, 1x, 2x, 3x). The highest peak is typically at “1x” and diminishes for higher multiples.
    - Frequency spectrum includes multiple turn frequency harmonics. If the radial 2x-turn frequency amplitude exceeds 50% of the 1x-turn frequency amplitude, it indicates such a fault.
    - Vibration amplitude is somewhat unstable, increasing greatly under high load.

    **Looseness Type C (Lc)**
    - **FG:** **Sub-Synchronous, Synchronous & Harmonic [F_G_4]**
    - **D_D_R:** Radial and/or Axial (H, V, A)
    - **Technique:** Time Waveform
    - **Mathematical Formula Wrt to (m, n, k):** \( f = \frac{1}{n} \times \text{RPM} \) (where \( n = 1, 2, 3, \ldots \))
    - **Rules of Thumb:** N/A
    - **Phase Characteristics:** 
    - Phase measurements are generally unstable.
    - If the vibration becomes highly directional, the difference between horizontal and vertical directions will be close to 0° or 180°.
    - **Differentiator:**
    - Type C is often caused by a loose bearing liner in its cap, excessive clearance in either a sleeve or rolling element bearing, or a loose impeller on a shaft.
    - The spectrum includes several peaks at various frequencies, indicating a complex vibration pattern.
    - The spectrum may show subharmonic multiples at exactly 0.5x, 1.5x, 2.5x, etc.
    - Amplitude is shown at multiple harmonics of the rotational speed, indicating a complex vibration pattern with significant energy at many multiples of the fundamental frequency.
    - The vibration spectrum may display many harmonics up to 10x or even 20x the rotational frequency.
    - This type of looseness tends to produce highly directional vibration with relatively high amplitude.
    - Presence of a distinct 0.5x peak suggests a more complex loosening issue, possibly involving friction.

    **Looseness Type A (La)**
        - **FG:** **Synchronous [F_G_1]**
        - **D_D_R:** Radial (H, V)
        - **Technique:** Phase Analysis
        - **Mathematical Formula Wrt to (m, n, k):** \( f = \text{RPM} \)
        - **Rules of Thumb:** Type A mechanical looseness has a time waveform of 1 pulse per revolution.
        - **Phase Characteristics:** 
        - Soft Foot - Phase analysis shows a 180° phase shift across Base, Base Plate, and Machine foot. Phase changes if the foundation bolts are tightened.
        - Structural faults can cause a 90° to 180° phase shift.
        - **Differentiator:**
        - Type A is caused by structural looseness/weakness of machine feet, base plate, or foundation.
        - Deteriorated grouting, loose hold-down bolts, and frame or base distortion (Soft Foot).
        - Phase analysis may reveal approx. 180° phase difference between vertical measurements on the machine foot, base plate, and base itself.
        - Vibration spectrum may present with a higher noise floor due to weak structural components.