# Methodology

## Project

CEH Module 6: System Hacking — Lab Risk and Defensive Analysis

## Environment and Scope

This coursework report studied system-hacking concepts in a host-only Kali Linux and Windows 10 virtual lab. Topics included credential exposure, reverse-connection payload concepts, password auditing, steganography, and anti-forensic behavior. This public project summary emphasizes defensive lessons and deliberately excludes operational payload instructions, recovered credentials, and sensitive lab values.

## Tools and Their Purpose

- Kali Linux
- Responder
- Metasploit Framework
- L0phtCrack
- Steghide
- Privacy Eraser
- Windows 10 VM

## Workflow

1. Studied how insecure local name-resolution protocols can expose authentication material in a lab scenario.
2. Reviewed the risk represented by reverse-connection payload execution and the importance of endpoint controls.
3. Performed password-auditing exercises against lab-owned accounts; no recovered password or hash is published here.
4. Examined steganography as a data-concealment concept and considered how defenders can investigate suspicious files.
5. Reviewed anti-forensic behavior and documented the importance of preserving logs and evidence during incident response.

## Validation and Safety

- Treat tool output as an observation that may require manual validation.
- Avoid publishing secrets, account details, private IPs, full scan outputs, or unredacted screenshots.
- Keep any follow-up testing inside an explicitly authorized lab.
- Do not infer that a system is secure solely because a scan did not report a critical finding.
