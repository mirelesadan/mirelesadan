# Hi, I’m Adan Mireles 👋

I’m an **Applied Physics PhD candidate at Rice University** developing scientific software and predictive models for complex experimental data. My work spans **microscopy, computational physics, biomedical data analysis, and high-performance computing**.

I build validated, reusable workflows—from multidimensional imaging and physics-based simulations to cancer drug-response modeling and optimized native implementations.

## 🔬 Featured projects

* **[Cancer Drug Response Prediction](https://github.com/mirelesadan/Cancer-Drug-Response-Prediction)**
  A GDSC2 study of **91,229 analyzed drug–cell responses**, asking how well gene expression and molecular fingerprints predict assay response in unseen cell lines for drugs represented in training. On **120 held-out cell lines**, validation-selected per-drug Ridge reduced test RMSE **18.1% versus the per-drug training-mean baseline**; a three-seed PyTorch MLP did not outperform per-drug Ridge. The repository includes cell-line-disjoint evaluation, **2,000 paired cell-line bootstrap resamples**, drug-level error analysis, and [data provenance](https://github.com/mirelesadan/Cancer-Drug-Response-Prediction/blob/main/results/data_audit.md). A later [exploratory molecular GNN extension](https://github.com/mirelesadan/Cancer-Drug-Response-Prediction/blob/main/results/gnn_final.md) tested drug graphs on the same split and did not improve on Ridge.

* **[4Denoise](https://github.com/mirelesadan/4Denoise)**
  An open-source Python package for processing and visualizing 4D-STEM data. It supports preprocessing, Bragg-peak analysis, crystallographic tilt inference, 3D topography reconstruction, tilt-corrected strain mapping, and interactive visualization. The package supports my first-author *Science Advances* study, [“Strain Mapping of Three-Dimensionally Structured Two-Dimensional Materials”](https://doi.org/10.1126/sciadv.adz7908).

* **[Multi-view MEP](https://github.com/mirelesadan/multiview-MEP)**
  A reusable Python workflow for multi-view multislice electron ptychography, including physically calibrated 3D volumes, registration of complementary datasets, relative overlap scoring, subvoxel atom localization, and simulation-based validation with ASE and abTEM.

* **[CUDA C++ Performance Engineering](https://github.com/mirelesadan/CUDA-Cpp-Performance-Engineering)** *(in active development)*
  A correctness-first portfolio for scientific denoising with C++17, OpenMP, CUDA, and Python bindings validated against reference outputs. Benchmarks separate kernel performance from transfer-inclusive costs and document retained and rejected optimizations.

* **[Reinforcement Learning Control of a Double Pendulum](https://github.com/mirelesadan/double-pendulum-rl-control)**
  A continuous-control project built from symbolically derived nonlinear equations of motion, custom Gym environments, and Stable-Baselines3 DDPG agents trained to control a double pendulum on a cart.

## 🤖 AI-assisted development

I use Codex and GPT coding assistants to turn research goals into bounded tasks, review implementations, build tests, and improve documentation. I independently validate numerical results and remain responsible for scientific assumptions, software decisions, and reproducibility.

## ⚡ Current interests

* Scientific software, materials informatics, and biomedical data analysis
* Predictive modeling with rigorous validation
* AI-assisted software development
* C++ and CUDA performance engineering
* Computer vision and multidimensional image processing
* Correlative 3D reconstruction and inverse problems
* Physics-based machine learning
* Scientific visualization and interactive tools

## 🌎 Outside research

When I’m not working with microscopy data or debugging code, I:

* 💪 Arm wrestle
* 🪂 Skydive
* 🎹 Play piano and ukulele
* 🍽️ Enjoy exploring new restaurants

## 📫 Connect with me

* **LinkedIn:** [Adan J. Mireles](https://www.linkedin.com/in/adanjmireles)
* **Email:** [mireles@rice.edu](mailto:mireles@rice.edu)
