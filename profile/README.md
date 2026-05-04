# AMPAV: Automated Metadata Pipeline for Audio/Video

## Overview
**AMPAV** (Automated Metadata Pipeline for Audio/Video) is an open-source initiative designed to provide archivists and collection managers with efficient, AI-assisted tools for generating metadata from audio and moving image collections. It is the next evolution of the **Audiovisual Metadata Platform (AMP)**.

While the original AMP project utilized a graphical workflow interface (Galaxy), **AMPAV shifts toward a pipeline-based approach**. This transition allows for greater flexibility, easier integration of rapidly evolving AI/ML tools, and lower overhead by focusing on **data processing** rather than data management.

## Key Features
*   **AI-Assisted Processing:** Pipelines for **speech-to-text, segmentation, named entity recognition (NER), and summarization**.
*   **Flexible Execution:** Can be run locally on workstations, within **High-Performance Computing (HPC)** environments, or via **REST APIs** for integration with other library applications.
*   **Integration-Ready:** Designed to interface with systems like **Avalon** and **Media Collections Online (MCO)**.
*   **Data Agnostic:** Leverages third-party storage (such as **Amazon S3**) for inputs and outputs, serving as a standalone metadata generation service.

## Core Repositories
The AMPAV ecosystem is organized into several specialized repositories:
*   **[ampav-core](https://github.com/AMPAV/ampav-core):** Foundational libraries, schemas, and utilities.
*   **[ampav-whisper](https://github.com/AMPAV/ampav-whisper):** Tools for Automatic Speech Recognition (ASR) using the **OpenAI Whisper** model.
*   **[ampav-parakeet](https://github.com/AMPAV/ampav-parakeet):** Tools for ASR utilizing **NVIDIA NeMo Parakeet**.
*   **[transcription-notebooks](https://github.com/AMPAV/transcription-notebooks):** A collection of **Jupyter Notebooks** for specific transcription tasks and proof-of-concept pipelines.

## Getting Started
Development is currently centered on **Python 3.12**. For developers setting up a local environment, please refer to our documentation on **[Setting up a development environment (Linux)](https://github.com/AMPAV/.github/wiki/Setting-up-a-development-environment-(Linux))**.

## Background
The original AMP project was supported by the **Mellon Foundation** (2017-2023) and developed collaboratively by Indiana University Libraries, AVP, University of Texas at Austin, and the New York Public Library. AMPAV continues this mission by modernizing the toolset for current AI/ML workflows.

---
*For more information, visit the [AMPAV Wiki](https://github.com/AMPAV/.github/wiki).*
This updated version reflects the project's current focus on Jupyter notebooks and Python scripts for tasks like transcription and segmentation
. It also correctly identifies the primary repositories and the role of the Mellon Foundation in the project's history
.
