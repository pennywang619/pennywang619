# OpenTraffic Delivery Repositories

Traffic-vision delivery repositories for Linux shared-library integration, validation artifacts, and task-level deployment bundles.

## Current Repositories

- [OpenTraffic-IQC](https://github.com/pennywang619/OpenTraffic-IQC)
  Image quality classification delivery bundle.

- [OpenTraffic-Water](https://github.com/pennywang619/OpenTraffic-Water)
  Water detection delivery bundle.

- [OpenTraffic-Occluded](https://github.com/pennywang619/OpenTraffic-Occluded)
  Occlusion detection delivery bundle.

- [OpenTraffic-Snow](https://github.com/pennywang619/OpenTraffic-Snow)
  Snow detection delivery bundle.

- [OpenTraffic-RLV](https://github.com/pennywang619/OpenTraffic-RLV)
  Red-light violation detection delivery bundle.

- [OpenTraffic-Cars](https://github.com/pennywang619/OpenTraffic-Cars)
  Cars detection delivery bundle.

- [OpenTraffic-NMV](https://github.com/pennywang619/OpenTraffic-NMV)
  Non-motor vehicle detection delivery bundle.

- [OpenTraffic-TLTV-YOLO](https://github.com/pennywang619/OpenTraffic-TLTV-YOLO)
  YOLO-based traffic-light timing validation delivery bundle.

- [OpenTraffic-vehicle-flow-detection](https://github.com/pennywang619/OpenTraffic-vehicle-flow-detection)
  Vehicle-flow detection delivery bundle with released submodules:
  `02_vehicle_motion_state`
  `04_area_vehicle_counting`
  `05_lane_turning_flow_rebuild`
  `06_lane_queue_length_detection`
  `07_overflow_detection`
  `08_lane_line_detection`

- [OpenTraffic-vision](https://github.com/pennywang619/OpenTraffic-vision)
  Aggregate entry repository with cross-repo index and module-level bundle map.

## Delivery Style

These repositories focus on public delivery artifacts instead of full internal source release.

Current public bundles mainly include:

- Linux `.so` shared libraries
- validation summaries
- output examples
- public manifests
- task-level bundle indexes

## Recommended Entry

If you want a single overview first, start here:

- [OpenTraffic-vision](https://github.com/pennywang619/OpenTraffic-vision)

If you want task-specific bundles directly, open the target repository from the list above.

## Notes

- Public repositories are organized for delivery, validation, and integration review.
- Internal training code, internal paths, and non-public deployment details are not included in the public bundles.
