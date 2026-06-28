# KQL Detection Rules

Custom KQL detection queries for identifying high-priority threat patterns in enterprise environments. Designed for Microsoft Sentinel (Log Analytics) and adaptable to Defender XDR.

## Detections Included

| Rule | MITRE ATT&CK | Severity |
|------|-------------|----------|
| MFA Bypass Attempts | T1556.006 | High |
| Impossible Travel | T1078 | High |
| Lateral Movement (Pass-the-Hash / Token Abuse) | T1550 | Critical |

## Usage
Each `.kql` file can be imported directly into Sentinel as an Analytics Rule or run ad-hoc in Log Analytics workspace.
