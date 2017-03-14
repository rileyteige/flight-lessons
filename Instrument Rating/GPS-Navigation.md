# GPS Navigation

## Objective
To teach the student about the Global Positioning System, and train the student in GPS navigation.

## Elements
- RNAV background
- GPS/GNSS background
- Common GPS functions and benefits
- RAIM
- IFR GPS Requirements
- WAAS
- GPS Approaches
- Using GPS on non-GPS approaches
- Review GPS pre-flight actions

## Schedule

| Task | ETE |
| ---- | --- |
| Pre-flight Instruction | 0:45 |
| Instructor Demo | 0:10 |
| Student Practice | 1:00 |
| Post-flight Instruction | 0:20 |
| **Total** | **2:15** |

## Equipment
- Aircraft equipped for IFR with GPS
- View-limiting device
- IFR En-Route Low Altitude Charts
- Example GPS Approach Plates
    - LP
    - LPV
    - LNAV+V
    - LNAV/VNAV
    - RNP

## Instructor Actions

Explain RNAV background and capabilities (direct-to), and legacy VOR/DME RNAV receivers.

Explain T-airways, find using IFR En-Route Low Altitude Charts.

Explain GNSS (Global Navigation Satellite System) / GPS (Global Positioning System) concepts.
- GPS (USA), Russian GNSS (GLONASS), Galileo (EU)
- Satellite-based, worldwide in scope, operated by Department of Defense, 24 satellites
- In the sky, at least 4 (usually 6-8) satellites in view.
- Receivers are listen-only, triangulating own position, velocity & time.
- Straight-line distances

Explain typical benefits and functions of a modern IFR-capable GPS receiver.
- Enhanced Situational Awareness (location, airspace, weather/traffic in advanced displays)
- Name-based waypoint input via navigation databases for fixes, airports, IAPs, STARs, SIDs
- Moving map
- DTK vs Track
- Distance
- ETE & ETA
- Flight-Plan Entry
- Nearest Field, FSS, ATC, VOR
- Auxiliary info: Winds Aloft, Density Altitude computation

Explain common "gotcha" with GPS: Each model can vary greatly (unlike ILS/VOR).

Explain Receiver Autonomous Integrity Monitoring (RAIM).
- Verifies enough GPS satellites in view, detects position error to identify corrupt satellites.
- Required for IFR, many VFR-only GPS receivers not equipped with RAIM alerting capability.
- Need _n+1_ satellites for _n_-dimensional triangulation.
- For RAIM, need _n+2_ to identify bad satellite, or barometric altimeter "baro-aid" to detect integrity anomaly.
- To be able to safely isolate a bad satellite and keep RAIM, need _n+3_ so one can be removed.
- Two ways to lose RAIM: not enough satellites, or potential accuracy error detection.

Explain requirements for a GPS receiver to be usable for IFR navigation:
- Must be installed on the aircraft, hand-held is prohibited and usable for SA only.
- Must meet Technical Standard Order (TSO) C-129 (or equivalent).
- Must be "approved" for IFR operation.
- Must be operated in accordance with POH/AFM or AFM Supplement.
- Must have RAIM alerting capability
- Current navigation database (expires every **28** days)

Explain (Wide-Area Augmentation System) WAAS. (IFH 9-32)

<img src="images/waas-ifh-9-29.png" width="400" />

- Measures changes in variables to provide satellite positioning corrections.
- Implementation of ICAO-standardized Satellite-Based Augmentation System.
<div style="clear: both;" />

Explain GPS CDI Sensitivity:
| Location | Sensitivity |
| -------- | ----------- |
| En-Route | ±5 NM |
| Terminal (within 30 NM) | ±1 NM |
| Approach | ±1 NM to ±0.3 NM at FAF |

Explain GPS approaches: LNAV, LNAV/VNAV, LNAV+V, LP, LPV, RNP requirements

Explain GPS pre-flight requirements:
- Check GPS NOTAMs, if not WAAS-equipped must do RAIM check (FSS w/ ETA, or on-board).
    - If using GPS SID without WAAS, also request RAIM for departure airport if using FSS.

## Student Actions

## Evaluation

## Common Errors

## References
[Pilot's Handbook of Aeronautical Knowledge Chapter 16 p.35](https://www.faa.gov/regulations_policies/handbooks_manuals/aviation/phak/media/18_phak_ch16.pdf)

[Instrument Flying Handbook Chapter 9 p.22-33, 44](https://www.faa.gov/regulations_policies/handbooks_manuals/aviation/media/FAA-H-8083-15B.pdf)

FAR/AIM