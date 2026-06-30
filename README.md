# Cullen McFlynn

I'm a detection engineer. Most of what I build are detection rules — mapped
to MITRE ATT&CK, mapped against real attack telemetry, written up well
enough that I could hand them straight to a SOC and not have to explain
myself.

What I actually care about is whether a detection holds up once someone
pokes at it: does the logic make sense, is the false-positive story honest,
and is there real evidence it fires on the technique it claims to catch.
Too many rules out there are just a regex that happens to look right.

### Featured

**[detections](https://github.com/CullenCS/detections)** — Windows (Sigma)
and cloud (KQL) rules, each with a full writeup: the threat research behind
it, the detection logic, validation runs against
[EVTX-ATTACK-SAMPLES](https://github.com/sbousseaden/EVTX-ATTACK-SAMPLES) and
[OTRF Security-Datasets](https://github.com/OTRF/Security-Datasets), and
whatever gaps are still open. CI checks structure and runs the official
Sigma validator on every push, so nothing broken lands on main.

[![validate-detections](https://github.com/CullenCS/detections/actions/workflows/ci.yml/badge.svg)](https://github.com/CullenCS/detections/actions/workflows/ci.yml)

### Right now

Working through more cloud coverage (Entra ID, AWS) and trying to hold it
to the same bar as the Windows rules — same validation, same writeups, no
shortcuts. Also tinkering with a small detection-as-code pipeline around
CI checks and rule testing.

### Toolbox

Sigma, KQL, MITRE ATT&CK, Chainsaw, Windows event logs, Azure Data
Explorer, AWS CloudTrail

---

Happy to talk shop on detection engineering, threat hunting, or SOC
tooling — culmcflynn@gmail.com
