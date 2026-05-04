# AMPAV: Automated Metadata Pipeline for Audio/Video [1, 2]

## Overview
**AMPAV** (Automated Metadata Pipeline for Audio/Video) is the next evolution of the **Audiovisual Metadata Platform (AMP)** [1]. It is an open-source initiative designed to provide archivists and collection managers with efficient, AI-assisted tools for generating metadata from audio and moving image collections [1, 2].

While the original AMP project focused on a graphical workflow interface using the Galaxy platform, **AMPAV shifts toward a pipeline-based approach** [3, 4]. This transition allows for greater flexibility, easier integration of rapidly evolving AI/ML tools (such as Whisper and Parakeet), and lower overhead by focusing on **data processing** rather than data management [3-5].

## Key Features
*   **AI-Assisted Processing:** Includes pipelines for **speech-to-text, segmentation, named entity recognition (NER), and summarization** [2, 4].
*   **Flexible Execution:** Can be run locally on workstations, within **High-Performance Computing (HPC)** environments, or via **REST APIs** for integration with other library applications [2, 4].
*   **Integration-Ready:** Designed to pull and push data from Indiana University’s AV management systems, including **Avalon** and **Media Collections Online (MCO)** [2, 4].
*   **Data Agnostic:** Leverages third-party storage services (such as **Amazon S3**) for inputs and outputs, allowing it to function as a standalone metadata generation service without the burden of managing user data [4].

## Core Repositories
The AMPAV ecosystem is currently organized into several specialized repositories [6]:
*   **[ampav-core](https://github.com/AMPAV/ampav-core):** Foundational libraries, schemas, and utilities for the AMPAV environment [7, 8].
*   **[ampav-whisper](https://github.com/AMPAV/ampav-whisper):** Tools for Automatic Speech Recognition (ASR) utilizing the **OpenAI Whisper** model [9, 10].
*   **[ampav-parakeet](https://github.com/AMPAV/ampav-parakeet):** Tools for ASR utilizing **NVIDIA NeMo Parakeet** [11, 12].
*   **[transcription-notebooks](https://github.com/AMPAV/transcription-notebooks):** A proof-of-concept (POC) set of **Jupyter Notebooks** for transcription tasks, designed for experienced users to run specific AI tools in a pipeline [13, 14].

## Getting Started
The project is currently focused on **Python-based scripts and Jupyter notebooks** [2, 5]. For developers looking to set up a local development environment, please refer to our documentation on **[Setting up a development environment (Linux)](https://github.com/AMPAV/.github/wiki/Setting-up-a-development-environment-(Linux))** [15-17].

## Background
The original AMP project was supported by grants from the **Mellon Foundation** between 2017-2023 and developed collaboratively by Indiana University Libraries, AVP, University of Texas at Austin, and the New York Public Library [1, 18]. AMPAV continues this mission by modernizing the toolset for the current AI/ML landscape [2, 4].

---
*For more information, visit the [AMPAV Wiki](https://github.com/AMPAV/.github/wiki).* [6, 19]
