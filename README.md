<div align="center">
<img src="portfolio-assets/cover.svg" width="100%" alt="Wireless Button Monitor project cover">

# Wireless Button Monitor

**Monitor four inputs and battery state, with a serial interface for a radio module.**

ATmega328P · Embedded C · UART · Battery sensing

[Overview](#overview) · [Design](portfolio/DESIGN.md) · [Setup](portfolio/SETUP.md) · [Validation](portfolio/VALIDATION.md) · [Evidence](portfolio/EVIDENCE.md)
</div>

## Overview

| Item | Record |
| :-- | :-- |
| Project type | Circuit and firmware |
| Field | Engineering |
| Material in this package | Documentation package; original source not included |
| Documentation review | 17 November 2026 |

## Scope

Monitor four inputs and battery state, with a serial interface for a radio module. The documentation separates the stated project scope, inspected artifacts and future work. A listed feature is not a new test result.

### Main elements

- Four inputs
- Input handling
- Battery indication
- Serial radio interface

## Start here

1. Read the [design record](portfolio/DESIGN.md) for the system elements and boundaries.
2. Follow the [setup record](portfolio/SETUP.md) for available entry points.
3. Use the [validation plan](portfolio/VALIDATION.md) to record reproducible results.
4. Check the [evidence register](portfolio/EVIDENCE.md) before reusing claims.

## Source status

This package contains project documentation and visual assets. Original code, CAD, data and test records have not been added. The setup record lists the files needed for a reproducible release.

## Next work

- [ ] Radio module and protocol
- [ ] Schematic and PCB
- [ ] Debounce logic
- [ ] Battery thresholds and current draw

## Credits and reuse

Project record: Mehdi Moallemkolaei. Specific third-party and course contributions must retain their original notices.

Existing license terms remain in effect. This package does not grant a new license over source code, course material, models or datasets. See [reuse and contribution notes](portfolio/CONTRIBUTIONS.md).
