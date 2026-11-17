# 3CX SmoothOperator - Malware Analysis
Static and behavioral analysis of the 3CX Desktop App supply chain compromise (Lazarus Group), prepared for the *Foundation in Cybersecurity* course (Università di Pavia).

## Analysis Breakdown
1. **[01 - In-Memory Staging & VirtualProtect](./01-virtualprotect-staging.md)**: Memory permission transition (`RW` $\rightarrow$ `RWX`) and fileless execution handoff to `d3dcompiler_47.dll`.
2. **02 - Dynamic API Resolution: PEB Walking** *(WIP)*
3. **03 - Dynamic API Resolution: API Hashing (`ROR`)** *(WIP)*
4. **04 - Anti-Analysis & Sandbox Evasion** *(WIP)*
5. **05 - Steganographic C2 Fetch via GitHub** *(WIP)*