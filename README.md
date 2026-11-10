FRVT Quality (Quality-SIDD) submission

Implemented quality measures:
TotalFacesPresent, SubjectPoseYaw/Pitch/Roll, InterEyeDistance,
EyesOpen/EyesOpen2, MouthOpen/MouthOpen2, Resolution,
CompressionArtifacts, FaceOcclusion/FaceOcclusion2, BackgroundUniformity,
PixelsFromEyeToLeftEdge/RightEdge/Top/Bottom,
Overexposure/Underexposure, UnifiedQualityScore,
EyeGlassesPresent/SunGlassesPresent

Validation:
- Platform: Ubuntu 24.04.3 LTS
- run_validate_quality.sh completed with [SUCCESS]
- 663 input images; 659 returned Success (0)
- 4 stress/invalid images returned 8 (FaceDetectionError):
  white.ppm, black.ppm, 8bit.pgm, small.ppm

 
