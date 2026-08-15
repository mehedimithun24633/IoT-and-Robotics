# SmartVax Cold Chain Guard

An IoT based vaccine cold storage monitoring and control system, designed and
simulated in Cisco Packet Tracer 9.0.

Nine IoT devices, twelve automation rules, two routed subnets. The system holds a
vaccine cold room between 6.0 and 8.3 degrees Celsius with no operator action, and
alarms on heat excursion, freezing, smoke and unauthorised access.

**Course:** ICT 6217, IoT and Robotics
**Student:** Mehedi Hasan Mithun (IT-24633)

## Contents

| File | Description |
|---|---|
| `SmartVax_ColdChainGuard.pkt` | The Packet Tracer project |
| `SmartVax-Report.pdf` | Full report, 22 pa
| `brief/` | The original assignment brief |
| `SmartVax_ColdChainGuard_Video_compressed/` | The demo video |
| `Exploring Internet of Things with Cisco Packet Tracer/` | The cisco course completion report |

## Demo video

[Download the demo video](./SmartVax_ColdChainGuard_Video_compressed.mp4)
[Watch demo video in google drive](https://drive.google.com/drive/folders/1tL2tQWElQKNcWlgIGlABlVLynNunFuIg)

## Report

[Final Report](./SmartVax-Report.pdf)

## Automation rules

Twelve rules run on the IoT registration sera two
threshold controller with hysteresis: cooling starts above 8 degrees and stops
below 6, which prevents both spoilage and thingle
setpoint would cause.

Full details in section 7 of the report.
