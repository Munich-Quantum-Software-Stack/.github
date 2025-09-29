<p align="center">
  <a href="https://mqt.readthedocs.io">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="figures/logo-mqss-dark.svg" width="60%">
      <img src="figures/logo-mqss-light.svg" width="60%" alt="MQSS Logo">
    </picture>
  </a>
</p>

# The Munich Quantum Software Stack (MQSS)

The **Munich Quantum Software Stack (MQSS)** is a modular, community-driven software ecosystem for hybrid quantum-classical computing, developed under the Munich Quantum Valley (MQV) initiative. It aims to provide a unified, extensible, and efficient interface from high-level quantum applications down to diverse quantum hardware, tightly integrated with classical HPC environments.

---

## Vision & Mission

- Lower the entry barrier to quantum computing by providing **high-level abstractions** and tools.
- Support **heterogeneous quantum hardware** (different technologies, vendors) under a unified interface.
- Enable **tight integration with HPC systems**, treating quantum processors as accelerators in classical workloads.
- Be **modular, extensible, and community-governed**, so that new backends, frontends, or optimizations can be plugged in.

---

## Core Components & Architecture

While work is ongoing, some of the key building blocks in MQSS include:

- **QDMI** ([Quantum Device Management Interface](https://munich-quantum-software-stack.github.io/QDMI/)): A low-level interface defining how software tools interact with quantum devices (job submission, constraints, telemetry).
- **Programming Interfaces** ([MQSS *Adapters* Suite](https://munich-quantum-software-stack.github.io/MQSS-Interfaces/): Bridges to frameworks like Qiskit, PennyLane, and others, allowing users to express quantum algorithms in familiar APIs.  
- **Compiler / optimization layers** ([MQSS *Passes* Suite](https://munich-quantum-software-stack.github.io/MQSS-Passes-Documentation/mlir/)): Multi-stage compilation pipelines, pass transformations, hardware-specific lowering, and optimizations.  
- **Device backends / plugins** ([MQSS *QDMI Devices* Suite](https://munich-quantum-software-stack.github.io/MQSS-QDMI-Devices-Suite/)): Modules to integrate particular quantum hardware (superconducting, ion traps, neutral atoms, etc.).

---

## Getting Started

1. Explore the individual repositories under this organization (e.g. `QDMI`, `MQSS-Passes-Suite`, etc.), many are already public and many more are to come.
2. Read the documentation and design rationale in each repo (look for `README.md`, `docs/`, etc).  
3. To contribute: fork a repo, follow its contributing guidelines (e.g. coding style, tests, documentation).  
4. Use issues / PRs for discussion, design proposals, bug reports, and feature requests.  
5. Engage with the community: review others' contributions, propose new modules, open design discussions.

---

## Contributing & Governance

- Contributions are welcome, whether code, documentation, tests, benchmarks, or design proposals.  
- Please follow repository-level **CONTRIBUTING.md** and **CODE_OF_CONDUCT** guidelines (if present).  
- Use issue templates and pull request templates where available.  
- Design and architecture discussions can be held in issues or dedicated "discussion" threads before coding.  
- Maintain backwards compatibility, clear API versioning, and ensure tests / CI pass before merge.

---

## License & Citation

All components in the MQSS are open-source under permissive licenses (e.g., Apache 2.0 with LLVM Exceptions).
If you use the MQSS or parts thereof in research or production, please cite the MQSS overview paper:

> Burgholzer, Echavarria, et al. [*"The Munich Quantum Software Stack: Connecting End Users, Integrating Diverse Quantum Technologies, Accelerating HPC"*](https://arxiv.org/abs/2509.02674) (2025).

Some repositories may contain more fine-grained license or citation files (e.g. `LICENSE`, `CITATION.cff`).

---

## Community & Contact

- Feel free to open issues or PRs in any public repo. 
- The development of this project is led by [Laura Schulz](mailto:laura.schulz@lrz.de) (LRZ), [Martin Schulz](mailto:martin.w.j.schulz@tum.de) (TUM CAPS), and [Robert Wille](mailto:robert.wille@tum.de) (TUM CDA) on the management side and [Lukas Burgholzer](mailto:lukas.burgholzer@tum.de) (TUM CDA) as well as [Jorge Echavarria](mailto:jorge.echavarria@lrz.de) (LRZ) from the technical side.
- If you want to contribute to private or in-development parts, feel free to contact the Architecture Review Board (ARB) of the MQSS using this email: [MQSS at Munich-Quantum-Valley.de](mailto:mqss@munich-quantum-valley-de).  
- Stay tuned for announcements, workshops, or developer calls via MQV / Munich Quantum Valley channels.  
- Visit [MQV's *Munich Quantum Software Stack* Official Webpage](https://www.munich-quantum-valley.de/research/research-areas/mqss).

---
