# Formal-Verification-RTL-Bug-Repair-using-SymbiYosys

Overview

This project demonstrates formal verification and automated RTL bug detection/repair using Verilog/SystemVerilog, Yosys, SymbiYosys, SMTBMC and Z3.

The project intentionally introduces RTL defects into common digital designs and uses formal properties to identify functional violations. Counterexample traces are analyzed to determine the root cause, followed by RTL repair and formal re-verification.

Objectives

- Detect RTL functional bugs using formal verification
- Develop assertion-based verification properties
- Use SymbiYosys for bounded and unbounded verification
- Generate and analyze counterexample traces
- Debug and repair defective RTL
- Re-run formal verification after RTL repair
- Assign binary verification rewards based on PASS/FAIL results

Designs Verified

1. 4-bit Counter


Tools & Technologies

- Verilog
- SystemVerilog
- Assertions
- Yosys
- SymbiYosys
- SMTBMC
- Z3
- GTKWave
- Python
- Git/GitHub

Verification Flow

Buggy RTL
→ Formal Properties
→ SymbiYosys
→ SMTBMC/Z3
→ Counterexample
→ RTL Debug
→ RTL Repair
→ Formal Re-verification
→ PASS/FAIL Reward

Verification Techniques

- Bounded Model Checking
- Unbounded Formal Proof
- Assertion-based Verification
- Assumption-based Verification
- Cover Property Analysis
- Counterexample Analysis
- RTL Bug Localization
- RTL Bug Repair

Binary Reward

Each verification task receives:

- Reward = 1 → Formal verification PASS
- Reward = 0 → Formal verification FAIL

Overall verification score:

Reward Score = Passed Tasks / Total Tasks × 100

Example

For four successfully verified designs:

Verification Success = 100%

Project Outcome

The project demonstrates the complete RTL verification lifecycle from defective RTL identification to formal proof of the repaired implementation.

Author

Rohit Mohitkar

Target Role

VLSI RTL Verification Engineer / Formal Verification Engineer
