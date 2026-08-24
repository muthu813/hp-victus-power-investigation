# Cross-GPU Analysis

## Research objective

The investigation was expanded beyond the primary Ryzen 5 5600H +
Radeon RX 6500M configuration to determine whether similar battery,
charging, telemetry, and power-management anomalies have been reported
across HP Victus systems using the same Ryzen 5 5600H processor with
different discrete GPUs.

## Configurations examined

The comparative evidence set includes reports involving:

- Radeon RX 5500M
- Radeon RX 6500M
- NVIDIA GTX 1650
- NVIDIA RTX 3050
- NVIDIA RTX 3060

## Observed symptom categories

Across the collected cases, recurring categories include:

- Rapid or unexpected battery discharge
- Battery percentage or capacity inconsistencies
- Charging interruption or abnormal charging behavior
- Battery-state changes associated with AC transitions
- ACPI or BIOS-related symptoms
- Power-state or GPU power-management behavior
- Hybrid battery discharge under high system load

## Interpretation

The recurrence of related symptom categories across different GPU
configurations makes a single-GPU-specific explanation less sufficient
as a complete explanation.

The Ryzen 5 5600H platform therefore remains a relevant common variable
for further investigation of shared battery and power-management
mechanisms.

This comparison does not establish that every Ryzen 5 5600H HP Victus
has the same defect, nor does it establish that all reported cases share
the same physical or firmware root cause.

## Primary research question

Does a shared platform-level mechanism involving the battery management
system, Embedded Controller (EC), SMBus communication, firmware, ACPI,
charging circuitry, or related power-management logic contribute to the
recurring symptoms observed across different GPU configurations?

## Evidence boundary

This document is a comparative research record. Individual external
reports vary in quality, configuration, measurement method, and outcome.

The comparison is therefore qualitative rather than a prevalence study.

Each case should be evaluated using:

1. Exact Victus model
2. Ryzen 5 5600H configuration
3. GPU configuration
4. Battery symptom
5. Charging behavior
6. BIOS/firmware information
7. Operating system
8. Diagnostic evidence
9. Reported resolution
10. Source quality

## Current conclusion

The cross-GPU evidence justifies continued investigation of shared
platform-level battery and power-management mechanisms.

The exact causal boundary remains unresolved and may involve the battery
BMS/fuel gauge, EC or firmware handling, SMBus/communication, charging
circuitry, or interactions among these components.
