# CVAT Image & Video Annotation Practice

**Tool:** [CVAT official repository](https://github.com/cvat-ai/cvat)  
**Experience scope:** CVAT was the primary tool practised in the bootcamp.

## Annotation types practised
- Bounding boxes — object localization.
- Polygons and masks — object boundaries and pixel-level regions.
- Polylines — linear structures such as lanes or wires.
- Points — landmarks or specific locations.
- Tags — image/frame-level classification.

## Video annotation concepts
- Track mode maintains an object's identity across frames.
- Keyframes define manual updates to object geometry.
- Interpolation fills positions between keyframes and must be reviewed.
- Occluded indicates a partially hidden object.
- Outside indicates the object is no longer visible in the frame.

## Review checklist
- Keep the same track ID for the same object.
- Fit boxes closely without unnecessary background.
- Check interpolated frames for drift.
- Distinguish occlusion from an object leaving the frame.
- Follow the task's class definitions and edge-case rules.

The JSON file in examples/ is a hand-authored learning illustration, not a native CVAT export.
