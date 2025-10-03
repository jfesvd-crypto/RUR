<p align="center">
  <img src="https://img.shields.io/badge/DOI-10.5281/zenodo.XXXXXXX-blue?style=for-the-badge" alt="DOI">
  <img src="https://img.shields.io/badge/Version-v1.0.0-green?style=for-the-badge" alt="Version">
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" alt="License">
</p>

<h1 align="center">RUR — A Fair Recruitment Framework</h1>

### [Read the full paper (PDF)](https://jfesvd-crypto.github.io/RUR/RUR_Project_Book_v1.pdf) ## Overview

**RUR (Ramy Uczciwej Rekrutacji - Fair Recruitment Framework)** is an open protocol designed to restore symmetry and fairness to the recruitment processes in the age of AI agents. It addresses the chaos of AI-driven application spam ("Bot Wars") and the inherent unfairness of traditional hiring ("Unfair Theater"). Our goal is not to eliminate performance, but to change the incentives so that **it pays to perform honesty**.

## Highlights

* **Symmetrical Disclosure**: Mandatory `Org Truth Packet` from employers and `Needs Capsule` from candidates create an informed, symmetrical starting point.
* **Fair Allocation**: A 3-lane, partially randomized shortlisting process using a Verifiable Random Function (VRF) replaces the opaque "fastest-first" model.
* **Mutual Agency**: A `Compatibility Report` and an equal, reputation-free right to `Mutual Veto` empower both parties.
* **Reflective Process**: `Rituals of Slowness` are intentionally introduced to encourage thoughtful interaction over biased, reactive decisions.
* **Auditable & Transparent**: The entire protocol is built on verifiable mechanisms, from lottery receipts to a public Falsification Protocol.

## Project Genesis

This project is the result of a unique, high-intensity collaboration between a human orchestrator and multiple advanced AI systems (including Google's Gemini and Anthropic's Claude). It is a proof of concept for a "Symphony of Agents," where human intent guides a multi-agent deliberation process to design complex socio-technical systems. The project's evolution, from a technical question to a complete philosophical and operational framework, took place over a few dozen hours of iterative dialogue. It was inspired by concepts such as Ontological Structural Realism (C0), decentralized computation (COsystem), and a critical analysis of the future of AI agents.

## Project Status

This repository contains the complete theoretical package for the RUR 1.0 protocol, including the manifesto, technical specifications, and a methodology for testing. The project is currently in the conceptual phase, ready for a pilot implementation (`Latarnia-EC01`).

## How to Cite (BibTeX)

If you use this work in your research, please cite it as follows:

```bibtex
@misc{RUR2025Framework,
  author       = {Feszter, Janusz (jfesvd-crypto)},
  title        = {RUR — A Fair Recruitment Framework: A Protocol for Restoring Symmetry in AI-Era Recruitment},
  year         = {2025},
  publisher    = {Zenodo},
  version      = {v1.0.0},
  doi          = {10.5281/zenodo.XXXXXXX},
  howpublished = {\url{[https://github.com/jfesvd-crypto/RUR](https://github.com/jfesvd-crypto/RUR)}}
}
```

## Build the PDF Yourself

To generate the complete "Project Book" PDF from the markdown files in this repository, you will need `pandoc` and a LaTeX distribution installed. Run the following command from the root of the repository:

```bash
pandoc spec/en/*.md philosophy/en/*.md -o RUR_Project_Book_v1.pdf --toc --pdf-engine=xelatex
```

## How to Contribute

This is an open project. We welcome discussion, critique, and collaboration. Please start by reading the **[Manifesto](https://github.com/jfesvd-crypto/RUR/blob/main/spec/en/01_manifest.md)** and the **[Full Protocol Specification](https://github.com/jfesvd-crypto/RUR/blob/main/spec/en/05_spec_rur_v1.md)**.