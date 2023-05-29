<!-- SHIELDS -->
<div align="left">

  ![Platform](https://img.shields.io/badge/Platform-Linux%20%7C%20macOS%20%7C%20Windows-informational)
  [![Python](https://img.shields.io/badge/Python-3.8%20%7C%203.9%20%7C%203.10%20%7C%203.11-informational)](https://www.python.org/)
  [![Qiskit Terra](https://img.shields.io/badge/Qiskit%20Terra-%E2%89%A5%200.24.0-6133BD)](https://github.com/Qiskit/qiskit-terra)
<br />
  [![Tests](https://github.com/pedrorrivero/pyproject-qiskit/actions/workflows/test.yml/badge.svg)](https://github.com/pedrorrivero/pyproject-qiskit/actions/workflows/test.yml)
  [![Coverage](https://coveralls.io/repos/github/pedrorrivero/pyproject-qiskit/badge.svg?branch=main)](https://coveralls.io/github/pedrorrivero/pyproject-qiskit?branch=main)
  [![Release](https://img.shields.io/github/release/pedrorrivero/pyproject-qiskit.svg?include_prereleases&label=Release)](https://github.com/pedrorrivero/pyproject-qiskit/releases)
  [![DOI](https://img.shields.io/badge/DOI-zz.nnnn/zenodo.ddddddd-informational)](https://zenodo.org/)
  [![License](https://img.shields.io/github/license/pedrorrivero/pyproject-qiskit?label=License)](LICENSE.txt)

</div>
<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="README.md">
    <img src="https://github.com/pedrorrivero/pyproject-qiskit/blob/main/docs/media/cover.png?raw=true" alt="Logo" width="300">
  </a>
  <h2 align="center">Pyproject Qiskit</h2>
</p>
<!-- QUICK LINKS -->
<!-- <p align="center">
  <a href="https://mybinder.org/">
    <img src="https://ibm.biz/BdPq3s" alt="Launch Demo" hspace="5" vspace="10">
  </a>
  <a href="https://www.youtube.com/c/qiskit">
    <img src="https://img.shields.io/badge/watch-video-FF0000.svg?style=for-the-badge&logo=youtube" alt="Watch Video" hspace="5" vspace="10">
  </a>
</p> -->


----------------------------------------------------------------------

### Table of contents

1. [About This Project](#about-this-project)
2. [About Prototypes](#about-prototypes)
3. [Deprecation Policy](#deprecation-policy)
4. [Using Quantum Services](#using-quantum-services)
5. [Acknowledgements](#acknowledgements)
6. [References](#references)
7. [License](#license)

#### For users
1. [Installation](https://github.com/pedrorrivero/pyproject-qiskit/blob/main/INSTALL.md)
2. [Tutorials](https://github.com/pedrorrivero/pyproject-qiskit/tree/main/docs/tutorials/)
3. [Reference Guide](https://github.com/pedrorrivero/pyproject-qiskit/blob/main/docs/reference_guide.md)
4. [How-tos](https://github.com/pedrorrivero/pyproject-qiskit/tree/main/docs/how_tos/)
5. [Explanations](https://github.com/pedrorrivero/pyproject-qiskit/tree/main/docs/explanations/)
6. [How to Give Feedback](https://github.com/pedrorrivero/pyproject-qiskit/blob/main/CONTRIBUTING.md#giving-feedback)

#### For developers
1. [Contribution Guidelines](https://github.com/pedrorrivero/pyproject-qiskit/blob/main/CONTRIBUTING.md)


----------------------------------------------------------------------

### About This Project
This template repository is a tool for creating Qiskit-based Python projects quickly by providing much of the necessary boilerplate code. The code examples in this template repository are written in accordance with pylint style checks, and the sample `pyproject_qiskit` module has an associated unit test module. We have also included examples of coverage testing, notebook tests, and notebook lint checks and wrapped all of these using [tox](https://github.com/tox-dev/tox) automated testing software. Check out the [file glossary](https://github.com/qiskit-community/quantum-prototype-template/blob/main/docs/file-map-and-description.md) for more information on each tool used in this repository.

We encourage you to use this template repository to begin your own research projects!

----------------------------------------------------------------------

### About Prototypes

Prototypes is a collaboration between developers and researchers that will give users early access to solutions from cutting-edge research in areas like error mitigation, quantum simulation, and machine learning. These software packages are built on top of, and may eventually be integrated into the Qiskit SDK. They are a contribution as part of the Qiskit community.

Check out our [landing page](https://qiskit-community.github.io/prototypes/) and [blog post](https://medium.com/qiskit/try-out-the-latest-advances-in-quantum-computing-with-ibm-quantum-prototypes-11f51124cb61) for more information!


----------------------------------------------------------------------

### Deprecation Policy

Prototypes are meant to evolve rapidly and, as such, do not follow [Qiskit's deprecation policy](https://qiskit.org/documentation/contributing_to_qiskit.html#deprecation-policy). We may occasionally make breaking changes in order to improve the user experience. When possible, we will keep old interfaces and mark them as deprecated, as long as they can co-exist with the new ones. Each substantial improvement, breaking change, or deprecation will be documented in [`CHANGELOG.md`](https://github.com/pedrorrivero/pyproject-qiskit/blob/main/CHANGELOG.md).


----------------------------------------------------------------------

### Using Quantum Services

If you are interested in using quantum services (i.e. using a real quantum computer, not a simulator) you can look at the [Qiskit Partners program](https://qiskit.org/documentation/partners/) for partner organizations that have provider packages available for their offerings.

Importantly, *[Qiskit IBM Runtime](https://qiskit.org/documentation/partners/qiskit_ibm_runtime)* is a quantum computing service and programming model that allows users to optimize workloads and efficiently execute them on quantum systems at scale; extending the existing interface in Qiskit with a set of new *primitive* programs.


----------------------------------------------------------------------

### Acknowledgements
- *Bob Alice*: for scientific insight and guidance.


----------------------------------------------------------------------

### References
[1] Diátaxis Technical Documentation Framework https://diataxis.fr/

----------------------------------------------------------------------

### License
[Apache License 2.0](https://github.com/pedrorrivero/pyproject-qiskit/blob/main/LICENSE.txt)
