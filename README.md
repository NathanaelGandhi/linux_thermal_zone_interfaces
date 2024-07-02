# linux_thermal_zone_interfaces
[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/NathanaelGandhi/linux_thermal_zone_interfaces/main.svg)](https://results.pre-commit.ci/latest/github/NathanaelGandhi/linux_thermal_zone_interfaces/main)
[![Publish Release](https://github.com/NathanaelGandhi/linux_thermal_zone_interfaces/actions/workflows/publish-release.yml/badge.svg?branch=release)](https://github.com/NathanaelGandhi/linux_thermal_zone_interfaces/actions/workflows/publish-release.yml)
[![Mirror release to humble](https://github.com/NathanaelGandhi/linux_thermal_zone_interfaces/actions/workflows/mirror-release-to-humble.yaml/badge.svg?branch=release)](https://github.com/NathanaelGandhi/linux_thermal_zone_interfaces/actions/workflows/mirror-release-to-humble.yaml)
[![PR Autolabeler](https://github.com/NathanaelGandhi/linux_thermal_zone_interfaces/actions/workflows/pr-autolabeler.yml/badge.svg?branch=main)](https://github.com/NathanaelGandhi/linux_thermal_zone_interfaces/actions/workflows/pr-autolabeler.yml)

ROS2 interfaces for use with the [linux_thermal_zone](https://github.com/NathanaelGandhi/linux_thermal_zone) package

## Implemented members in [ThermalZone.msg](msg/ThermalZone.msg)
- [ ] available_policies
- [ ] emul_temp
- [ ] integral_cutoff
- [ ] k_d
- [ ] k_i
- [ ] k_po
- [ ] k_pu
- [ ] mode
- [ ] offset
- [ ] policy
- [ ] power/
- [ ] slope
- [ ] subsystem/
- [ ] sustainable_power
- [x] temp
- [ ] trip_point_0_hyst
- [ ] trip_point_0_temp
- [ ] trip_point_1_hyst
- [ ] trip_point_1_temp
- [ ] trip_point_1_type
- [ ] trip_point_2_hyst
- [ ] trip_point_2_temp
- [ ] trip_point_2_type
- [x] type
- [ ] uevent
- [ ] trip_point_0_type

## [ThermalZoneNodeHk.msg](msg/ThermalZoneNodeHk.msg)
Housekeeping telemetry specific to the [ThermalZoneBaseNode](https://github.com/NathanaelGandhi/linux_thermal_zone_base/blob/main/include/linux_thermal_zone_base/linux_thermal_zone_base_node.hpp)
