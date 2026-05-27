# HAMMER Software Ecosystem

HAMMER's software ecosystem spans computational modeling, in-situ manufacturing monitoring, uncertainty quantification, digital twins, physics-informed machine learning, and open-source manufacturing hardware.

This catalog is an integration map, not a fork list. Active development remains in the original upstream repositories maintained by the researchers and collaborating labs who created the work.

## Featured Projects

<table>
  <thead>
    <tr>
      <th align="left">Area</th>
      <th align="left">Project</th>
      <th align="left">Repository / Site</th>
      <th align="left">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Computational mechanics</td>
      <td><strong>JAX-FEM</strong></td>
      <td><a href="https://github.com/deepmodeling/jax-fem">deepmodeling/jax-fem</a></td>
      <td>Differentiable finite element package based on JAX.</td>
    </tr>
    <tr>
      <td>Computational mechanics</td>
      <td><strong>JAX-CPFEM</strong></td>
      <td><a href="https://github.com/SuperkakaSCU/JAX-CPFEM">SuperkakaSCU/JAX-CPFEM</a></td>
      <td>GPU-computing simulation for differentiable crystal plasticity finite element modeling.</td>
    </tr>
    <tr>
      <td>Computational mechanics</td>
      <td><strong>JAX-PF</strong></td>
      <td><a href="https://github.com/SuperkakaSCU/JAX-PF">SuperkakaSCU/JAX-PF</a></td>
      <td>GPU-computing simulation platform for differentiable phase-field modeling.</td>
    </tr>
    <tr>
      <td>In-situ monitoring and vision</td>
      <td><strong>SMAXI</strong></td>
      <td><a href="https://github.com/dukyong414/SMAXI">dukyong414/SMAXI</a></td>
      <td>X-ray image analysis project repository.</td>
    </tr>
    <tr>
      <td>In-situ monitoring and vision</td>
      <td><strong>Confidence-Aware Photometric Stereo</strong></td>
      <td><a href="https://github.com/aiml-nu/Confidence-Aware-PS">aiml-nu/Confidence-Aware-PS</a></td>
      <td>Code for confidence-aware photometric stereo networks for normal and depth estimation in smart metrology.</td>
    </tr>
    <tr>
      <td>Uncertainty quantification</td>
      <td><strong>Deep-UQ</strong></td>
      <td><a href="https://github.com/Vispikarkaria/Deep-UQ">Vispikarkaria/Deep-UQ</a><br><a href="https://vispikarkaria.github.io/Deep-UQ/">Documentation site</a></td>
      <td>Unified PyTorch toolkit for deep learning uncertainty quantification.</td>
    </tr>
    <tr>
      <td>Uncertainty quantification</td>
      <td><strong>ASNO</strong></td>
      <td><a href="https://github.com/Vispikarkaria/ASNO">Vispikarkaria/ASNO</a></td>
      <td>Attention-based spatio-temporal neural operator for evolving physics.</td>
    </tr>
    <tr>
      <td>Uncertainty quantification</td>
      <td><strong>UQ Model Discrepancy</strong></td>
      <td><a href="https://github.com/mesoOSU/UQ_Model_Discrepancy">mesoOSU/UQ_Model_Discrepancy</a></td>
      <td>Bayesian uncertainty framework for model discrepancy in a random effects framework.</td>
    </tr>
    <tr>
      <td>Digital twins</td>
      <td><strong>DED Digital Twin</strong></td>
      <td><a href="https://github.com/yiping514/DED_DT">yiping514/DED_DT</a></td>
      <td>Directed energy deposition digital twin project repository.</td>
    </tr>
    <tr>
      <td>Generative modeling</td>
      <td><strong>PB-GAN</strong></td>
      <td><a href="https://github.com/mesoOSU/PB-GAN">mesoOSU/PB-GAN</a></td>
      <td>Physics-based regularization using generative adversarial networks.</td>
    </tr>
    <tr>
      <td>Open hardware</td>
      <td><strong>Dauber</strong></td>
      <td><a href="https://github.com/aiml-nu/Dauber">aiml-nu/Dauber</a></td>
      <td>Low-cost additive friction stir deposition with small-scale continuous wire feed enabled by orbital motion.</td>
    </tr>
  <tr>
    <td>Open hardware</td>
    <td><strong>LC-CNC</strong></td>
    <td><a href="https://github.com/t-w00d/LC-CNC">t-w00d/LC-CNC</a></td>
    <td>Low-cost desktop CNC milling machine design and curriculum.</td>
  </tr>
  <tr>
    <td>Open hardware</td>
    <td><strong>arcResearch</strong></td>
    <td><a href="https://github.com/vishnu-ramasamy/arcResearch.git">vishnu-ramasamy/arcResearch</a></td>
    <td>Open-source Wire Arc Additive Manufacturing (WAAM) platform.</td>
  </tr>
  <tr>
  <td>Open hardware</td>
  <td><strong>Automated Forging Clay</strong></td>
  <td><a href="https://github.com/Amumu-ze1ast/ncat_automated_forging_clay">Amumu-ze1ast/ncat_automated_forging_clay</a></td>
  <td>Automated forging clay project repository.</td>
  </tr>
  </tbody>
</table>

## Computational Mechanics and Physics-Based Modeling

| Project | Repository | Details |
| --- | --- | --- |
| JAX-FEM | <https://github.com/deepmodeling/jax-fem> | Differentiable finite element method package based on JAX, with support for finite-element simulation and differentiable programming workflows. |
| JAX-CPFEM | <https://github.com/SuperkakaSCU/JAX-CPFEM> | Differentiable crystal plasticity finite element modeling built around JAX-FEM and JAX, with emphasis on GPU acceleration, calibration, sensitivity analysis, and inverse design workflows. |
| JAX-PF | <https://github.com/SuperkakaSCU/JAX-PF> | Differentiable phase-field modeling platform built on JAX-FEM and JAX for GPU-computing simulation. |

## In-Situ Monitoring and Computer Vision

| Project | Repository | Details |
| --- | --- | --- |
| SMAXI | <https://github.com/dukyong414/SMAXI> | X-ray image analysis repository included in the HAMMER software map. |
| Confidence-Aware Photometric Stereo | <https://github.com/aiml-nu/Confidence-Aware-PS> | Implementation for confidence-aware photometric stereo networks for end-to-end normal and depth estimation in smart metrology. |

## Uncertainty Quantification and Optimization

| Project | Repository / Site | Details |
| --- | --- | --- |
| Deep-UQ | <https://github.com/Vispikarkaria/Deep-UQ> | Unified deep learning UQ toolkit in PyTorch. The project documents multiple UQ method families, including variational inference, Laplace approximation, MCMC/SGLD, MC Dropout, and Gaussian processes. |
| Deep-UQ documentation | <https://vispikarkaria.github.io/Deep-UQ/> | Documentation site for the Deep-UQ package. |
| ASNO | <https://github.com/Vispikarkaria/ASNO> | Attention-based Spatio-Temporal Neural Operator implementation for evolving physics, including physics-oriented benchmarks and additive manufacturing data workflows. |
| UQ for Model Discrepancy | <https://github.com/mesoOSU/UQ_Model_Discrepancy> | Bayesian uncertainty framework for accounting for model discrepancy within a random effects Bayesian framework. |

## Digital Twins and Generative Models

| Project | Repository | Details |
| --- | --- | --- |
| DED Digital Twin | <https://github.com/yiping514/DED_DT> | Directed energy deposition digital twin repository included in the HAMMER software map. |
| PB-GAN | <https://github.com/mesoOSU/PB-GAN> | Physics-based regularization using generative adversarial networks, with regularization terms related to stress equilibrium. |

## Open-Source Manufacturing Hardware

| Project | Repository | Details |
| --- | --- | --- |
| Dauber | <https://github.com/aiml-nu/Dauber> | Low-cost additive friction stir deposition with small-scale continuous wire feed enabled by orbital motion. |
| LC-CNC | <https://github.com/t-w00d/LC-CNC> | Low-cost desktop CNC milling machine design and curriculum, including design files, instructions, and software resources. |
| arcResearch | <https://github.com/vishnu-ramasamy/arcResearch.git> | Open-source Wire Arc Additive Manufacturing (WAAM) platform. |
| Automated Forging Clay | <https://github.com/Amumu-ze1ast/ncat_automated_forging_clay> | Automated forging clay project repository. |

## Stewardship Model

Most repositories listed here are upstream projects owned by individual researchers, partner institutions, or collaborating labs.

- The upstream repository remains the source of truth.
- Issues and pull requests should be opened upstream unless the issue concerns HAMMER-level integration.
- HAMMER uses this catalog to provide visibility, coordination, and cross-project context.
- Repository ownership should move into the HAMMER organization only when HAMMER becomes the long-term maintainer.
