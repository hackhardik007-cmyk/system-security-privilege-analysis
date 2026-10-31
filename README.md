# CEH Module 6: System Hacking — Lab Risk and Defensive Analysis

> Coursework project | CEH v12 curriculum | Intellipaat

## Overview

This coursework report studied system-hacking concepts in a host-only Kali Linux and Windows 10 virtual lab. Topics included credential exposure, reverse-connection payload concepts, password auditing, steganography, and anti-forensic behavior. This public project summary emphasizes defensive lessons and deliberately excludes operational payload instructions, recovered credentials, and sensitive lab values.

## Objectives

- Document the methodology and observations from the course lab.
- Explain security implications in clear, defensible terms.
- Connect observations to practical defensive recommendations.
- Keep public documentation sanitized and reproducible at a high level.

## Lab and Tools

- Kali Linux
- Responder
- Metasploit Framework
- L0phtCrack
- Steghide
- Privacy Eraser
- Windows 10 VM

## Methodology

1. Studied how insecure local name-resolution protocols can expose authentication material in a lab scenario.
2. Reviewed the risk represented by reverse-connection payload execution and the importance of endpoint controls.
3. Performed password-auditing exercises against lab-owned accounts; no recovered password or hash is published here.
4. Examined steganography as a data-concealment concept and considered how defenders can investigate suspicious files.
5. Reviewed anti-forensic behavior and documented the importance of preserving logs and evidence during incident response.

## Key Findings

- Legacy name-resolution protocols and weak passwords can increase credential-compromise risk.
- Application control, endpoint detection, network monitoring, and least privilege help reduce the impact of unauthorized execution.
- Evidence preservation and documented handling are important when investigating suspected anti-forensic activity.
- Testing must remain limited to systems and accounts explicitly owned or authorized for the exercise.

## Defensive Recommendations

- Apply least privilege and remove or restrict services that are not required.
- Keep operating systems, applications, and security tools updated.
- Use strong unique passwords and multifactor authentication where available.
- Centralize and review relevant endpoint, authentication, and network logs.
- Validate scanner or tool output before treating it as a confirmed vulnerability.
- Preserve evidence and document scope during incident investigation.

## Scope and Limitations

This is an educational lab summary, not a real-world penetration test. The repository intentionally excludes payload binaries, exploit execution steps, captured hashes/passwords, target IPs, and raw logs. Do not upload the original report unchanged.

## Ethics and Safety

All hands-on activity described here was coursework conducted in a lab context. Only assess systems for which you have explicit authorization. This repository contains documentation only; it does not distribute payloads, credentials, malware, or raw target scan data.

## Repository Structure

- `docs/methodology.md` — concise workflow and tool purpose.
- `docs/findings-summary.md` — summarized observations, implications, and limitations.
- `evidence/README.md` — guidance for adding sanitized screenshots, if permitted.
- `.gitignore` — excludes common temporary and sensitive files.

## Coursework Disclaimer

This project documents learning exercises from the CEH v12 curriculum. It is not evidence of a commercial security engagement or a certification exam pass.
