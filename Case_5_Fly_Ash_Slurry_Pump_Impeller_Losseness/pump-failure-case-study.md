# Comprehensive Fly Ash Pump Failure Case Study

## Equipment Details

### Pump Specifications
- Type: Single-stage, horizontal, centrifugal, double-case pump
- Application: Pumping ash slurry in a coal-fired power plant
- Max Specific Gravity of Fluid: 1.6
- Materials: Wear-resistant alloy for flow passage parts
- Performance:
  - Head: 67 MWC
  - Discharge Capacity: 1800 m³/hr
- Impeller: 4 Vanes

### Bearings
- DE (motor end): 
  - Type: Double row spherical roller bearing
  - Model: SKF 22236 CC/W33
  - Design: Radial load bearing
- NDE (pump end): 
  - Type: Spherical roller thrust bearing
  - Model: SKF 22332 CC/W33
  - Design: Thrust load bearing

### Motor
- Rating: 825 kW
- Voltage: 6.6 kV
- Speed: 725 rpm
- Type: Three-phase, 50 Hz induction motor

## Observed Issues

### Vibration Signatures
1. Dominant 2x rpm component and high-frequency harmonics observed in both horizontal and vertical directions.
2. Pump NDE bearing: High-frequency vibrations (>50% of radial component), prominent 4x rpm component.
3. Pump DE bearing: Significant 2x and higher harmonics in Radial and Axial directions.
4. Excessive axial vibration at pump DE bearing: 23 mm/sec peak (2x rpm component: 18 mm/sec peak).
5. No data recorded at Motor DE and NDE.

### Vibration Trend Data

| POINT & DIRECTION | Overall vibrations (displacement μm p-p / Vel. mm/s pk) |
|-------------------|--------------------------------------------------------|
|                   | 2-Aug-95 (After overhaul) | 24-Aug-95 (Routing check) | 25-Aug-95 (Analysis run) |
| Pump DE Horiz     | 30/2.7                    | 90/13                     | 118/14                   |
| Pump DE Vert      | 29/2.9                    | 23/5.4                    | 32/7                     |
| Pump DE Axial     | 27/5                      | 240/22                    | 260/22                   |
| Pump NDE Horiz    | 22/4.6                    | 96/13                     | 136/13                   |
| Pump NDE Vert     | 12/4.6                    | 52/7.6                    | 48/5.6                   |
| Pump NDE Axial    | 21/3.6                    | 52/8.6                    | 50/7.6                   |

### Analysis of Vibration Trends
- Significant increase in vibrations across all measurement points between 2-Aug and 24-Aug.
- Pump DE Axial vibration shows the most dramatic increase, from 27μm/5mm/s to 240μm/22mm/s.
- Horizontal vibrations generally show larger increases than vertical.
- Both DE and NDE bearings affected, but DE bearing shows more severe changes, especially in axial direction.

## Operational Context
- Pump in continuous operation for 18 months
- Recent process changes increased ash content in slurry
- Operators reported unusual noise from pump area in the past week
- Energy consumption of the pump increased by 15% over the last month

## Maintenance History
- Last overhaul: 24 months ago
- Impeller replaced: 12 months ago
- Bearings last inspected: 6 months ago (no issues reported)
- Shaft alignment check: 3 months ago (within tolerance)

## Environmental Factors
- Ambient temperature: Consistently high (35-40°C) due to summer season
- Humidity: 80-85% (higher than usual)
- Occasional power fluctuations reported in the plant

## Inspection Findings
- Impeller: Signs of erosion on vane edges
- Shaft: Slight scoring marks observed
- Casing: Internal wear near the cutwater area
- Mechanical seal: Minor leakage detected
- Foundation bolts: 2 out of 8 bolts found loose

## Fluid Analysis Results
- Particulate content: 25% higher than design specifications
- pH: Slightly more acidic than normal (pH 5.5 vs. expected 7.0)
- Viscosity: 10% higher than usual

## Additional Measurements
- Pump inlet pressure: 5% lower than normal
- Discharge pressure: Fluctuating ±10% around setpoint
- Motor winding temperature: 15°C above typical operating temperature
- Shaft runout: 0.15 mm (specification: max 0.10 mm)

## Potential Contributing Factors
1. Mechanical looseness (evidenced by loose foundation bolts and 2x rpm vibration)
2. Impeller damage or wear (signs of erosion observed)
3. Bearing wear or damage (high vibrations, especially at DE bearing)
4. Misalignment (high axial vibration at DE bearing)
5. Cavitation (potential, given inlet pressure drop and particulate content increase)
6. Resonance issues (high-frequency vibrations)
7. Inadequate lubrication (potential factor in bearing issues)
8. Foundation issues (loose bolts observed)
9. Process fluid changes (increased particulate content, changed pH)
10. Overloading (increased energy consumption)
11. Electrical issues (motor winding temperature increase, power fluctuations)
12. Environmental stress (high ambient temperature and humidity)

## Summary of Key Observations
1. The 2x rpm component in vibration signatures indicates mechanical looseness, which is supported by the finding of loose foundation bolts.
2. The very high axial vibration at the pump DE bearing (260μm/22mm/s) suggests significant thrust issues, potentially related to impeller condition or misalignment.
3. The presence of 4x rpm vibration component could be related to the four-vane impeller, possibly indicating flow disturbances or impeller damage.
4. The rapid increase in vibrations between 2-Aug and 24-Aug suggests a sudden deterioration in the pump's condition.
5. The overhung impeller design may be contributing to the high axial vibration, especially in combination with mechanical looseness.
6. The increase in particulate content and changes in fluid properties (pH, viscosity) may be accelerating wear on pump components.
7. The combination of high ambient temperature, increased fluid temperature, and higher motor winding temperature suggests potential cooling or heat dissipation issues.

This comprehensive case study provides a complex scenario with multiple interrelated factors for the SpiderAI Copilot to analyze. The copilot can use this information to create detailed Why trees, Fishbone diagrams, and perform Five Why analyses to identify the root cause(s) of the pump failure.
