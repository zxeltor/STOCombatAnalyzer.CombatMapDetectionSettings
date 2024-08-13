# Settings for STOCombatAnalyzer [![GitHub release (latest by date)](https://img.shields.io/github/v/release/zxeltor/STOCombatAnalyzer.Settings)](https://github.com/zxeltor/STOCombatAnalyzer.Settings/releases/latest)

## Revision History
* 2024-06-24 CombatMapDetectionSettings.json(1.0.0.0): Added first version of CombatMapDetectionSettings.json
* 2024-06-25 CombatMapDetectionSettings.json(1.0.1.0): Added a reference to main exceptions for Nimbus Pirate Distress Call. It was causing false positives for the Nimbus map.
* 2024-06-26 CombatMapDetectionSettings.json(1.2.0): Added new map detection logic in app. A new optional parameter has been added to the JSON to support it. Also updated the versioning to Semantic Versioning 2.0.0.
* 2024-06-29 CombatMapDetectionSettings.json(1.3.2): Add a few more maps for Red Alerts and a Borg Deep Space Encounter.
* 2024-07-02 CombatMapDetectionSettings.json(1.3.3): Removed the map for Goncra. Moved some elements around.
* 2024-08-13 CombatMapDetectionSettings.json(1.3.4): Updated the Nimbus map. It was incorrectly being detected for different space maps.

## Overview
This is a home for [STOCombatAnalyzer](https://github.com/zxeltor/STOCombatAnalyzer) settings files.

### CombatMapDetectionSettings.json
This file is used by STOCombatAnalyzer to detect Star Trek Online maps. You can manualy import this file into STOCombatAnalyzer.

**Note:** Some map/entity definitions from [STOCD/OSCR](https://github.com/STOCD/OSCR) were used in this JSON. Kudos to their contributor(s) for their hard work.
