# PatientPose 3D v2.1 — Chest PA Live Assessment

Browser-based educational prototype for radiographic positioning training.

## Chest PA live checks
- Torso centering against a visual midline
- Shoulder leveling
- 2D/landmark-depth torso symmetry proxy
- Hip/postural symmetry
- Short hold-still readiness check
- Real-time corrective guidance
- Privacy mode: pose processing occurs in-browser; no application-level video upload

## Important limitation
This prototype only evaluates externally visible pose features available from a consumer RGB camera. It does not verify detector contact, source-to-image distance (SID), respiration, scapular displacement, internal anatomy, exposure factors, or diagnostic image quality. Final positioning remains subject to qualified radiographer review. The score is a prototype training metric and is not clinically validated.

## Run
Deploy over HTTPS (for example GitHub Pages) or use localhost. Open index.html and grant camera permission.
