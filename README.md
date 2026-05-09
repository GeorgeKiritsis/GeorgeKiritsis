# Georgios Kiritsis

Hellenic Air Force Academy '26  ·  Computer Science 
Athens, Greece

I work at the intersection of **embedded systems**, **aerospace ML**, and **real-time
analytics for pilot training**. My undergraduate research at the 360 Training Squadron
of the Hellenic Air Force produced an end-to-end flight-data acquisition and
debriefing system, from the custom STM32 hardware up to a 3D replay engine with
inline anomaly detection.

## Research interests

- Phase-conditional unsupervised anomaly detection on non-stationary time series
- Synthetic-to-real transfer when training data are unavoidably simulated
- Embedded ML on cockpit-class hardware (Cortex-M, sub-MB memory)
- Data-driven post-flight analytics for pilot training and aviation safety
- Reproducible benchmarks and tooling for aerospace ML

## Selected work

- **The Use of Artificial Intelligence in Military Simulation Training** &mdash;
  Springer book chapter (2026, in press), with P. Karampelas.
  _Survey of AI techniques for military simulation training, with an aviation case
  study built on the Ikaros / Skyris system._

- **[Ikaros Flight Computer Firmware](#)** &mdash; Custom flight-data recorder firmware for the
  Tecnam P2002-JF trainer aircraft. STM32F405, BMI088 IMU, LIS2MDL, BMP280, NEO-6M GPS,
  microSD logging. Mahony AHRS at 400 Hz, 38-channel telemetry at 100 Hz.

- **[Skyris Engine](#)** &mdash; Custom C++17/OpenGL engine for 3D flight replay,
  with ECS architecture, PBR rendering, terrain LOD, OSM/SRTM geographic context,
  and inline phase-aware Isolation-Forest anomaly detection at 60 Hz.

- **[Phase Aware Isolation Forest Algorithm](#)** &mdash; Reference implementation of the phase-aware
  Isolation-Forest pipeline, with reproducible experiments and pre-trained models.

- **[TecnamSim Dataset](#)** &mdash; Synthetic flight benchmark for pilot-training
  anomaly detection: 1,000+ nominal flights and 200+ anomalous flights with
  ground-truth labels, generated from a hardware-faithful Tecnam P2002-JF model with
  datasheet-derived sensor noise. _In preparation._

## Contact

- ✉ &nbsp;[georgekiritsis5@gmail.com]
- 🆔 &nbsp;ORCID: [0009-0001-4686-2760](https://orcid.org/0009-0001-4686-2760)
<!--- - 🎓 &nbsp;[Google Scholar](#) --->
- 💼 &nbsp;[LinkedIn](https://www.linkedin.com/in/giorgoskiritsis/)

<sub>Diploma thesis: <i>""Design and Implementation of a Flight Data Recorder for the Tecnam P2002-JF Trainer Aircraft, with Companion Software for Post-Flight Analysis, Performance Evaluation, and Three-Dimensional Visualisation""</i> &mdash; advisor Assoc. Prof. P. Karampelas, co-supervisor Sqd. Ldr. (PhD) F. Vakrakos. Hellenic Air Force Academy, Department of Aeronautical Sciences, Division of Computer Science.</sub>
