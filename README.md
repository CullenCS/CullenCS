# Cullen McFlynn

Detection engineer. I build production-style detection rules — mapped to
MITRE ATT&CK, validated against real attack telemetry, and documented well
enough to hand straight to a SOC.

I care about detections that hold up under scrutiny: clear logic, honest
false-positive analysis, and evidence they actually fire on the technique
they claim to cover — not just a regex that looks right.

### Featured

**[detections](https://github.com/CullenCS/detections)** — Windows (Sigma)
and cloud (KQL) detection rules, each with a full writeup: threat research,
detection logic, validation against
[EVTX-ATTACK-SAMPLES](https://github.com/sbousseaden/EVTX-ATTACK-SAMPLES) /
[OTRF Security-Datasets](https://github.com/OTRF/Security-Datasets), and
known gaps. CI enforces structure and runs the official Sigma validator on
every push.

[![validate-detections](https://github.com/CullenCS/detections/actions/workflows/ci.yml/badge.svg)](https://github.com/CullenCS/detections/actions/workflows/ci.yml)

### Currently working on

- Expanding cloud detection coverage (Entra ID, AWS) with the same
  validation rigor as the Windows rules
- Building out a small detection-as-code pipeline (CI validation, rule
  testing, structured writeups)

### Toolbox

Sigma · KQL · MITRE ATT&CK · Chainsaw · Windows event logs · Azure Data
Explorer · AWS CloudTrail

---

Always glad to talk detection engineering, threat hunting, or SOC tooling —
reach me at **culmcflynn@gmail.com**.
