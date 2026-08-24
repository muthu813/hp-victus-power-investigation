# Investigation Methodology

## Purpose

This repository documents a technical investigation into battery, charging,
power-management, Embedded Controller (EC), BIOS/UEFI, ACPI, and battery
telemetry behavior observed on HP Victus systems using the AMD Ryzen 5 5600H.

## Research question

Do recurring battery and power-management anomalies appear across different
HP Victus configurations using the Ryzen 5 5600H, including systems with
different discrete GPUs, suggesting a shared platform-level mechanism that
requires further engineering investigation?

## Evidence approach

The investigation distinguishes:

- Observed facts
- Derived calculations
- Engineering interpretation
- Supported hypotheses
- Unresolved causes

No hypothesis is treated as an established hardware or firmware defect unless
the available evidence directly supports that conclusion.

## Primary evidence sources

The investigation may include:

- Windows battery and power telemetry
- Linux battery and power telemetry
- HP UEFI diagnostics
- HP PC Hardware Diagnostics results
- ACPI/DSDT analysis
- Embedded Controller (EC) analysis
- BIOS/UEFI version information
- Charging and power-state observations
- Independent external cases
- Cross-GPU comparative evidence

## Read-only firmware boundary

The firmware investigation is conducted on a read-only basis.

No modified BIOS image is flashed, no undocumented EC commands are intentionally
sent, and no battery pack is opened as part of the documented investigation
phase.

## Interpretation rule

A recurring symptom across multiple systems is treated as corroborating evidence
for further investigation, not as automatic proof of a common defect.

Likewise, absence of a symptom in one configuration does not establish that the
configuration is immune.

## Limitations

The investigation does not by itself establish:

- A universal defect affecting every Ryzen 5 5600H HP Victus.
- A single failed component.
- Intentional causation by HP.
- That a particular BIOS version caused the original failure.
- Physical battery energy movement from telemetry-derived calculations alone.

Further hardware-level testing may be required to distinguish among the battery
BMS/fuel gauge, EC, SMBus/communication path, charging circuitry, firmware, and
other power-management components.
