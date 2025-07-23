# EPET: A Constitutive, Emergentist-Predictive Account of Qualia - Manuscript [EN]

This repository contains the source files for the academic paper **"EPET: A Constitutive, Emergentist-Predictive Account of Qualia"**.

This paper is the first in a planned series dedicated to systematically articulating the **Emergent Predictive Experience Theory (EPET)**, a broader philosophical framework for understanding consciousness and the self. The original "treatise" version of EPET can be found for archival purposes in the [epet-theory](https://github.com/antimortine/epet-theory) repository.

## Abstract

This paper presents a constitutive, emergentist-predictive account of qualia designed to address the 'hard problem' of consciousness within a naturalistic, physicalist framework. It argues that by integrating two leading paradigms from cognitive science—Predictive Processing (PP) and Global Workspace Theory (GWT)—and grounding this synthesis in a consistent non-reductive (weak) emergentism, we can provide a coherent explanation for the phenomenal character of experience. The core thesis posits that qualia are not mysterious byproducts or illusions, but are **constituted by**, or identical to, specific intrinsic properties of the integrated, embodied predictive modeling process itself. This framework aims to dissolve the explanatory gap by reframing the question from "generation" to "realization," thereby avoiding the metaphysical extremes of both panpsychism and strong illusionism while affirming the reality of subjective experience.

## Keywords

consciousness, qualia, the hard problem, philosophy of mind, predictive processing, global workspace theory, emergentism, physicalism, cognitive science.

## Target Audience

The manuscript is primarily aimed at **philosophers of mind**, **cognitive scientists**, **neuroscientists**, and anyone interested in foundational questions about consciousness and interdisciplinary approaches to the study of mind.

## Repository Structure

*   `manuscript/`: Source files of the main manuscript in Markdown (`.md`), divided by sections.
*   `references/`: Contains the master bibliography file (e.g., `references.bib`).
*   `notes/`: Contains supplementary research notes and literature reviews relevant to this paper.
*   `assets/`: Auxiliary resources (e.g., metadata `.yaml` file, CSL citation style).
*   `scripts/`: Utility scripts (e.g., for building or checking the bibliography).
*   `output/`: Directory for generated PDF files (excluded from Git by `.gitignore`).
*   `Makefile`: Defines build commands and dependencies.
*   `README.md`: This file.
*   `.gitignore`: List of files ignored by Git.
*   `LICENSE`: License file (e.g., CC BY 4.0 International).

## Building the Document

To build the PDF document from the source files, you need:

1.  **Pandoc:** A universal document converter.
2.  **A LaTeX Distribution:** Such as TeX Live or MiKTeX (XeLaTeX engine is recommended).
3.  **Python 3:** May be required for utility scripts.
4.  **Fonts:** Ensure required fonts (e.g., a standard Serif font like Linux Libertine or Times New Roman, and a Sans-Serif font) are installed.

**Build Commands (using Make):**

(Run these commands from the root directory of the repository)

*   **Build the main PDF:**
    ```bash
    make all
    ```
    (This can be configured to build different versions, e.g., with author info or anonymous).

*   **Clean the output directory:**
    ```bash
    make clean
    ```
*   **Count words (main manuscript, excluding bibliography):**
    ```bash
    make count_words
    ```
*For detailed build targets, please refer to the `Makefile`.*

## Status

*   **Current Version:** 0.1 (Initial Draft)
*   **Goal:** Preparation of a focused academic article for submission to a peer-reviewed journal in philosophy of mind or cognitive science.

## License

The text of the manuscript and related materials is distributed under the terms of the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

This means you are free to:

*   **Share:** copy and redistribute the material in any medium or format.
*   **Adapt:** remix, transform, and build upon the material for any purpose, even commercially.

Under the following terms:

*   **Attribution:** You must give appropriate credit, provide a link to the license, and indicate if changes were made.

The full legal text of the license is available in the `LICENSE` file.