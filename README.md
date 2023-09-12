<p align="center">
    <img src="./figs/fig_3in1.jpg" width="65%"/> <br />
    <em>
    </em>
</p>

# <p align=center>`Awesome quantum computer vision (Q-CV)`

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](https://opensource.org/licenses/MIT) 
[![Forks](https://img.shields.io/github/forks/Jun-Pu/Awesome-quantum-computer-vision.svg?style=for-the-badge)](https://github.com/Jun-Pu/Awesome-quantum-computer-vision/network/members)
[![Stargazers](https://img.shields.io/github/stars/Jun-Pu/Awesome-quantum-computer-vision.svg?style=for-the-badge)](https://github.com/Jun-Pu/Awesome-quantum-computer-vision/stargazers)
[![Issues](https://img.shields.io/github/issues/Jun-Pu/Awesome-quantum-computer-vision.svg?style=for-the-badge)](https://github.com/Jun-Pu/Awesome-quantum-computer-vision/issues)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555)](https://www.linkedin.com/in/Jun-Pu/)
   

<p align="center">
 The list will be continually updated. Stay tuned!

< **Last updated: Aug/21/2023** >
        

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#Methodologies">Methodologies</a>
      <ul>
        <li><a href="#Year 2023">Year 2023</a></li>
        <li><a href="#Year 2022">Year 2022</a></li>
        <li><a href="#Year 2021">Year 2021</a></li>
        <li><a href="#Year 2020">Year 2020</a></li>
      </ul>
    </li>
    <li><a href="#Contact">Contact</a></li>
  </ol>
</details>


## Methodologies

### Year 2023

**Year** | **Publication** | **Title** | **Preprint** | **Project Page** | **Key Concepts**
:-: | :-:| :- | :-: |  :-: |  :-: 
**2023** | **ICLR** | [QuAnt: Quantum Annealing with Learnt Couplings](https://openreview.net/pdf?id=isiQ5KIXbjj) <br><sub> **QuAnt:** Proposing to learn quadratic unconstrained binary optimization (QUBO) forms from data through gradient back-propagation instead of deriving them. Demonstrating the advantages of learned  QUBOs on the diverse problem types of graph matching, 2D point cloud alignment and 3D rotation estimation. </sub>  | [arXiv](https://arxiv.org/pdf/2210.08114.pdf) | [Link](https://4dqv.mpi-inf.mpg.de/QuAnt/)
**2023** | **CVPR** | [CCuantuMM: Cycle-Consistent Quantum-Hybrid Matching of Multiple Shapes](https://openaccess.thecvf.com/content/CVPR2023/papers/Bhatia_CCuantuMM_Cycle-Consistent_Quantum-Hybrid_Matching_of_Multiple_Shapes_CVPR_2023_paper.pdf) <br><sub> **CCuantuMM:** Introducing the first quantum-hybrid cycle-consistent approach for 3D shape multi-matching. Significantly outperforming extensions to multi-shape matching of a previous quantum-hybrid two-shape matching method and is on-par with classical multi-matching methods. </sub> | [arXiv](https://arxiv.org/pdf/2303.16202.pdf) | [Link](https://4dqv.mpi-inf.mpg.de/CCuantuMM/)
**2023** | **CVPR** | [Quantum Multi Model Fitting](https://openaccess.thecvf.com/content/CVPR2023/papers/Farina_Quantum_Multi-Model_Fitting_CVPR_2023_paper.pdf) <br><sub> **QMMF:** Formulating multi-model fitting as a problem that can be efficiently sampled by modern adiabatic quantum computers without the relaxation of the objective function. Supporting real-world-sized problems. </sub> | [arXiv](https://arxiv.org/pdf/2303.15444.pdf) | [Link](https://github.com/FarinaMatteo/qmmf)
**2023** | **ICML** | [A Hybrid Quantum-Classical Approach based on the Hadamard Transform for the Convolutional Layer](https://proceedings.mlr.press/v202/pan23d/pan23d.pdf) <br><sub> **HQC-WHT:** Proposing a novel Hadamard Transform (HT)-based neural network layer for hybrid quantum-classical computing. </sub> | [arXiv](https://arxiv.org/pdf/2305.17510.pdf) | [Link](https://github.com/phy710/icml2023-ht)

### Year 2022
    
**Year** | **Publication** | **Title** | **Preprint** | **Project Page** | **Key Concepts**
:-: | :-:| :- | :-: |  :-: |  :-: 
**2022** | **CVPR** | [An Iterative Quantum Approach for Transformation Estimation from Point Sets](https://openaccess.thecvf.com/content/CVPR2022/papers/Meli_An_Iterative_Quantum_Approach_for_Transformation_Estimation_From_Point_Sets_CVPR_2022_paper.pdf) <br><sub> **Q-TE:** Proposing an iterative method for estimating rigid transformations from point sets using adiabatic quantum computation. </sub> | | | Transformation Estimation from Point Sets
**2022** | **CVPR** | [Adiabatic Quantum Computing for Multi Object Tracking](https://openaccess.thecvf.com/content/CVPR2022/papers/Zaech_Adiabatic_Quantum_Computing_for_Multi_Object_Tracking_CVPR_2022_paper.pdf) <br><sub> **AQC-MOT:** Proposing the first multi-object tracking formulation designed to be solved with adiabatic quantum computing. </sub> | [arXiv](https://arxiv.org/pdf/2202.08837.pdf)
**2022** | **CVPR** | [A Hybrid Quantum-Classical Algorithm for Robust Fitting](https://openaccess.thecvf.com/content/CVPR2022/papers/Doan_A_Hybrid_Quantum-Classical_Algorithm_for_Robust_Fitting_CVPR_2022_paper.pdf) <br><sub> **HQC-RF:** Novel robust fitting formulation that solves a sequence of integer programs and terminates with a global solution or an error bound. </sub> | [arXiv](https://arxiv.org/pdf/2201.10110.pdf)
**2022** | **ECCV** | [Q-FW: A Hybrid Classical-Quantum Frank-Wolfe for Quadratic Binary Optimization](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136830341.pdf) <br><sub> **Q-FW:** A hybrid classical-quantum framework based on the Frank-Wolfe algorithm, namely Q-FW, for solving quadratic, linearly-constrained, binary optimization problems on quantum annealers. </sub> | [arXiv](https://arxiv.org/pdf/2203.12633.pdf)
**2022** | **ECCV** | [Quantum Motion Segmentation](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136890497.pdf) <br><sub> **Q-MS:** The first algorithm for motion segmentation that relies on adiabatic quantum optimization of the objective function. </sub> | [arXiv](https://arxiv.org/pdf/2203.13185.pdf) | [Link](https://4dqv.mpi-inf.mpg.de/QuMoSeg/)

### Year 2021
    
**Year** | **Publication** | **Title** | **Preprint** | **Project Page** | **Key Concepts**
:-: | :-:| :- | :-: |  :-: |  :-: 
**2021** | **CVPR** | [Quantum Permutation Synchronization](https://openaccess.thecvf.com/content/CVPR2021/papers/Birdal_Quantum_Permutation_Synchronization_CVPR_2021_paper.pdf) <br><sub> **QuantumSync:** The first quantum algorithm for solving a synchronization problem in the context of computer vision. </sub> | [arXiv](https://arxiv.org/pdf/2101.07755.pdf) | [Link](https://vcai.mpi-inf.mpg.de/projects/QUANTUMSYNC/)
**2021** | **ICCV** | [Q-Match: Iterative Shape Matching via Quantum Annealing](https://openaccess.thecvf.com/content/ICCV2021/papers/Benkner_Q-Match_Iterative_Shape_Matching_via_Quantum_Annealing_ICCV_2021_paper.pdf) <br><sub> **Q-Match:** A new iterative quantum method for quadratic assignment problems inspired by the α-expansion algorithm, which allows solving problems of an order of magnitude larger than current quantum methods. </sub> | [arXiv](https://arxiv.org/pdf/2105.02878.pdf) | [Link](https://4dqv.mpi-inf.mpg.de/QMATCH/)

### Year 2020
    
**Year** | **Publication** | **Title** | **Preprint** | **Project Page** | **Key Concepts**
:-: | :-:| :- | :-: |  :-: |  :-: 
**2020** | **NeurIPS** | [Recurrent Quantum Neural Networks](https://proceedings.neurips.cc/paper/2020/file/0ec96be397dd6d3cf2fecb4a2d627c1c-Paper.pdf) <br><sub> **QRNN:** Constructing a quantum recurrent neural network (QRNN) with demonstrable performance on non-trivial tasks such as sequence learning and integer digit classification. </sub> | [arXiv](https://arxiv.org/pdf/2006.14619.pdf) | | Recurrent Neural Networks
**2020** | **3DV** | [Adiabatic Quantum Graph Matching with Permutation Matrix Constraints](https://vcai.mpi-inf.mpg.de/projects/QGM/data/SeelbachBenkner_etal.pdf) <br><sub> **QGM:** Proposing several reformulations of quadratic assignment problems as unconstrained problems suitable for efficient execution on quantum hardware. </sub> | [arXiv](https://arxiv.org/pdf/2107.04032.pdf) | [Link](https://vcai.mpi-inf.mpg.de/projects/QGM/)
**2020** | **ECCV** | [Quantum-soft QUBO Suppression for Accurate Object Detection](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123740154.pdf) <br><sub> **QSQS:** Mapping the task of removing redundant detections into Quadratic Unconstrained Binary Optimization (QUBO) framework that consists of detection score from each bounding box and overlap ratio between pair of bounding boxes. Solve the QUBO problem using the proposed Quantum-soft QUBO Suppression (QSQS) algorithm for fast and accurate detection by exploiting quantum computing advantages. </sub> | [arXiv](https://arxiv.org/pdf/2007.13992.pdf) 

### Year 2019
    
**Year** | **Publication** | **Title** | **Preprint** | **Project Page** | **Key Concepts**
:-: | :-:| :- | :-: |  :-: |  :-: 

### Year 2011
    
**Year** | **Publication** | **Title** | **Preprint** | **Project Page** | **Key Concepts**
:-: | :-:| :- | :-: |  :-: |  :-: 


## Contact
    
Feel free to drop an e-mail to junpuzhang.2022@gmail.com.
