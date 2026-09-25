# Hi, I'm Grzegorz 👋

Lead AI & Software Architect working on cybersecurity and regulatory
compliance (NIS2, DORA) by day — builder of small, sharp-edged tools
on the side.

## 🔐 Engineering & Security
- **[Sentin-NPU](https://github.com/GrzegorzOle/Sentin-NPU)** — on-device privacy gateway for AI traffic: checksum-verified IDs (PESEL, IBAN, payment cards) and NER catch sensitive data before a prompt leaves the laptop, with inference running on the machine's otherwise idle Intel NPU (OpenVINO). Measured, not assumed: 2× less energy than the iGPU at realistic load; audit events carry metadata, never content. [The write-up](https://medium.com/@goleksy.go/your-laptops-npu-is-bored-europe-can-always-use-another-employee-with-nothing-to-do-6779d22e9f24).
- **[Sentin-Harden](https://github.com/GrzegorzOle/Sentin-Harden)** — desktop tool that audits Windows and Linux against CIS Benchmarks and answers the question the benchmark leaves vague: what exactly stops working once a rule is applied. Each of 2,400+ rules carries two extra ratings, attacker gain and operational disruption, so the queue sorts into quick wins and conscious decisions instead of benchmark order. Read-only audit first; fixes run one at a time, backup before, re-audit after, and anything without a rollback path can be copied but never run. No bulk mode, by design. Ships as MSI/AppImage; independent project, not affiliated with CIS.
- **[behavioral-auth](https://github.com/GrzegorzOle/behavioral-auth)** — local-only behavioral biometrics for Linux: continuous identity verification via keystroke/mouse dynamics, fused with face recognition. No cloud, alert-only by design.
- **[Pick_Route_Optimizer](https://github.com/GrzegorzOle/Pick_Route_Optimizer)** — warehouse picking route optimization on Google OR-Tools, with a map editor that catches broken layouts before they break a shift.

## ♿ Accessibility
- **[DepthForge](https://github.com/GrzegorzOle/DepthForge)** — turns paintings into 3D-printable tactile reliefs for blind and visually impaired people, using AI depth estimation (Intel OpenVINO).
- **[GazeCtrl](https://github.com/GrzegorzOle/GazeCtrl)** — webcam-only eye-gaze tracking, no IR hardware, built as an input layer for AAC applications.

Two threads, one habit: get the boring infrastructure right, then let
it disappear into the background for the people who actually need it.

📝 [Blog](https://cdest.eu/blog/) · 💼 [LinkedIn](https://www.linkedin.com/in/grzegorz-oleksy-63062179/)
