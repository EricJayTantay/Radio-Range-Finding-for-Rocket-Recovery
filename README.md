# Radio-Range-Finding
Radio Range Finding PCB for use in triangulating and recovering a rocket after launch

Summary: 
  This project involves designing a custom hardware system for tracking and recovering high-powered rockets using LoRa-based time-of-flight ranging with the SX1280 transceiver. The system consists of one onboard radio node and two or more ground-based receivers, enabling  precise distance measurements without relying on GPS.

Motivation:
  Previous recovery efforts using GPS faced limitations; GPS modules can lose fix under high acceleration or altitude (due to ITAR/COCOM restrictions);
  Rockets often land out of visual or audible range, making recovery difficult;
  GPS updates can be delayed or noisy, especially in descent;

By using 2.4 GHz LoRa with integrated ranging, we can:
  Get low-latency distance measurements;
  Avoid legal and hardware limitations of GPS;
  Add potential for triangulation with multiple base stations;
  Build a lightweight, low-power, and cost-effective recovery system;
