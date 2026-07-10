# Georgios Kiritsis

- Second Lieutenant | Computer Science Officer & Researcher @ Hellenic National Meteorological Service (EMY) · Hellenic Air Force
- BSc Computer Science, Hellenic Air Force Academy '26


I am a Computer Science Officer at the **Hellenic National Meteorological Service** (EMY),
working on machine learning and big-data analysis of operational meteorological and
satellite data. My work sits at the intersection of
**software engineering**, **computer graphics**, **embedded systems**, **aerospace ML**,
and **real-time analytics for pilot training**. My undergraduate research at the 360
Training Squadron of the Hellenic Air Force produced an operationally deployed end-to-end
flight-data acquisition and debriefing system, from the custom STM32 hardware up to a 3D
replay engine with inline anomaly detection.

## Research interests

- Phase-conditional unsupervised anomaly detection on non-stationary time series
- Synthetic-to-real transfer when training data are unavoidably simulated
- Embedded ML on cockpit-class hardware (Cortex-M, sub-MB memory)
- Data-driven post-flight analytics for pilot training and aviation safety
- Reproducible benchmarks and tooling for aerospace ML
- Multi-aircraft generalization in synthetic flight benchmarks
- Edge computing and embedded ML for robotic applications
- Meteorological and satellite data analytics

## Writing

Long-form technical deep-dives at **[georgekiritsis.com/writing](https://georgekiritsis.com/writing/)**:

- 🌲 &nbsp;**[Phase-Aware Anomaly Detection on Flight Time Series](https://georgekiritsis.com/writing/phase-aware-anomaly-detection.html)** &ndash; why flight telemetry defeats a single global model, and how a phase-conditional Isolation Forest scores each frame in under 0.1 ms.
- 🎮 &nbsp;**[Architecture of Skyris: a Real-Time Flight Replay Engine](https://georgekiritsis.com/writing/skyris-engine.html)** &ndash; ECS, a platform abstraction layer, PBR, quadtree LOD terrain, and deterministic replay with quaternion interpolation.
- 🛠 &nbsp;**[Designing Ikaros: a Cockpit-Class Flight Data Recorder](https://georgekiritsis.com/writing/ikaros-flight-computer.html)** &ndash; custom STM32F405 hardware, sensor fusion with Mahony AHRS, and a CSV format designed as an interface contract.

## Selected publications

- 📕 &nbsp;**The Use of Artificial Intelligence in Military Simulation Training** &ndash;
  Springer book chapter (2026, in press), with P. Karampelas.
  _Survey of AI techniques for military simulation training, with an aviation case study
  built on the Ikaros / Skyris system._
- 📄 &nbsp;**From Generic Simulator to Mission Debriefing: A 3D Visualization Engine for Drone SAR Training Analysis** &ndash;
  IEEE Computer Graphics & Applications (under review), with F. Vakrakos, D. Lappas, G. Pappas & P. Karampelas.
- 📄 &nbsp;**Skyris: A Deterministic-Replay Engine for Real-Time Aircraft Flight-Training Debriefing** &ndash;
  target IEEE Transactions on Visualization and Computer Graphics (in preparation), with P. Karampelas.
- 📄 &nbsp;**Drone Pilot Self-Training, Debriefing, and Assessment: Bridging Training Gaps Through an Aviation-Inspired Framework** &ndash;
  in preparation, with D. Lappas, G. Pappas & P. Karampelas.
- 📊 &nbsp;**FLARES: A Synthetic-to-Real Validated Benchmark for Anomaly Detection in General-Aviation Flight Training** &ndash;
  in preparation, with P. Karampelas.

## Selected work

- 🛠 &nbsp;**[Ikaros Flight Computer](https://georgekiritsis.com/writing/ikaros-flight-computer.html)** &ndash; Custom flight-data recorder firmware for the
  Tecnam P2002-JF trainer aircraft. STM32F405, BMI088 IMU, LIS2MDL magnetometer, BMP280 barometer, NEO-6M GPS,
  microSD logging. Mahony AHRS at 400 Hz, CSV telemetry at 100 Hz. _[Deep-dive](https://georgekiritsis.com/writing/ikaros-flight-computer.html) · Code coming soon._
- 🎮 &nbsp;**[Skyris Engine](https://georgekiritsis.com/writing/skyris-engine.html)** &ndash; Custom C++20/OpenGL engine for 3D flight replay & visualization,
  with EnTT ECS architecture, PBR rendering, quadtree LOD terrain, OSM/SRTM geographic context,
  and inline phase-aware Isolation-Forest anomaly detection at 60 Hz. _[Deep-dive](https://georgekiritsis.com/writing/skyris-engine.html) · Code coming soon._
- 🌲 &nbsp;**[Phase-Aware Isolation Forest](https://georgekiritsis.com/writing/phase-aware-anomaly-detection.html)** &ndash; Reference implementation of the phase-aware
  Isolation-Forest pipeline, with reproducible experiments and pre-trained models. _[Deep-dive](https://georgekiritsis.com/writing/phase-aware-anomaly-detection.html) · Code coming soon._
- 📊 &nbsp;**[F.L.A.R.E.S](#)** &ndash; *Flight Logs for Anomaly Research and Evaluation Suite.*
  Open-source synthetic-to-real benchmark for general-aviation anomaly detection. JSBSim 6-DOF flight
  dynamics with five physically-grounded anomaly categories across three severity tiers, injected at the
  control or sensor layer. Synthetic-to-real validation against the NGAFID-MC real Cessna 172 dataset
  (28,935 flights, 31,177 hours), with an extensible framework for additional trainer models. _In preparation._

<sub>Diploma thesis: <i>"Design and Implementation of a Flight Data Recorder for the Tecnam P2002-JF Trainer Aircraft, with Companion Software for Post-Flight Analysis, Performance Evaluation, and Three-Dimensional Visualization"</i> &ndash; advisor Assoc. Prof. P. Karampelas, co-supervisor Sqd. Ldr. F. Vakrakos. Hellenic Air Force Academy, Department of Aeronautical Sciences, Department of Computer Science. Grade 100/100, Best Thesis of Class 2026.</sub>
