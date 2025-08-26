---
permalink: /portfolio/publications/
title: "Publications"
toc: true
toc_sticky: true
toc_label: "Publications"
toc_icon:  "book"

header:
  show_overlay_excerpt: false
  overlay_image: /assets/images/header_papers.jpg
  caption: "Photo credit: [**Unsplash**](https://unsplash.com/photos/white-printer-paper-lot-5cFwQ-WMcJU)"
  overlay_filter: 0.5
---

## Conference Proceedings

### QR-Map: A Map-Based Approach to Quantum Circuit Abstraction for Qubit Reuse Optimization <a href="https://doi.org/10.1145/3695053.3731020" target="_blank"><i class="fa fa-book" title="Reference"></i></a>

<div style="display: flex; align-items: center;">
  <div style="width: 80%; padding-right: 10px;">
    <i>ISCA '25: Proceedings of the 52nd Annual International Symposium on Computer Architecture</i>
    <br>20 Jun. 2025
  </div>
  <div style="width: 20%;">
    <img src="/assets/images/logo_isca2025.png" alt="ISCA 2025" width="100" height="100"/>
  </div>
</div>

<div style="text-align: center; font-size: 0.85em;">
<b>Hyungseok Kim</b><sup>1</sup>, Enhyeok Jang<sup>1</sup>, Seungwoo Choi<sup>1</sup>, Youngmin Kim<sup>1</sup>, and Won Woo Ro<sup>1</sup>
<br><sup>1</sup>Yonsei University, Republic of Korea
<br><br>
</div>

<div style="text-align: center;">
  <a class="btn btn--info" onclick="toggleContent(this)">
      <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>Abstract
  </a>
</div>
<div class="abstract" style="display: none;">
  Recent advances in quantum computing introduce the ability to reuse qubits through mid-circuit measurements, thereby enhancing the efficiency of quantum devices with limited computational resources.
  However, identifying optimal reuse opportunities in quantum circuits remains challenging due to the intricate dependencies between quantum gates. 
  Existing frameworks address this by either directly searching for reuse opportunities or converting circuits into directed acyclic graphs (DAGs).
  Unfortunately, these frameworks may require exponential search complexity or may not always ensure optimal results due to their non-deterministic property.
  To overcome these challenges, we propose <i>QR-Map</i> (<u>Q</u>ubit <u>R</u>euse <u>Map</u>), a map-based framework that abstracts computational dependencies for efficient qubit reuse. 
  By extracting and aligning two-qubit gates, QR-Map facilitates dependency detection and ensures qubit savings without incurring excessive idle time. 
  This approach achieves an optimal balance between gate serialization depth and crosstalk reduction.
  Evaluations with various quantum circuit benchmarks demonstrate that quantum circuits optimized with QR-Map achieve average reductions of 20% in qubit usage, 25% in circuit depth, and 22% in SWAP insertions compared to those optimized with the state-of-the-art framework.
</div>



### Qubit Movement-Optimized Program Generation on Zoned Neutral Atom Processors <a href="https://doi.org/10.1145/3696443.3708937" target="_blank"><i class="fa fa-book" title="Reference"></i></a>

<div style="display: flex; align-items: center;">
  <div style="width: 80%; padding-right: 10px;">
    <i>CGO '25: Proceedings of the 23rd ACM/IEEE International Symposium on Code Generation and Optimization</i>
    <br>01 Mar. 2025
  </div>
  <div style="width: 20%;">
    <img src="/assets/images/logo_cgo.jpg" alt="CGO 2025" width="100" height="100"/>
  </div>
</div>

<div style="text-align: center; font-size: 0.85em;">
Enhyeok Jang<sup>1</sup>, Youngmin Kim<sup>1</sup>, <b>Hyungseok Kim</b><sup>1</sup>, Seungwoo Choi<sup>1</sup>, Yipeng Huang<sup>2</sup>, and Won Woo Ro<sup>1</sup>
<br><sup>1</sup>Yonsei University, Republic of Korea, <sup>2</sup>Rutgers University, New Jersey, USA
<br><br>
</div>

<div style="text-align: center;">
  <a class="btn btn--info" onclick="toggleContent(this)">
      <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>Abstract
  </a>
</div>
<div class="abstract" style="display: none;">
  A zoned neutral atom architecture achieves exceptional fidelity by segregating the execution spaces of 1- and 2-qubit gates, being a promising candidate for high-accuracy quantum systems. 
  Unfortunately, naïvely applying programs designed for static qubit topologies to zoned architectures may result in most execution time being consumed by intra-zone travels of atoms. 
  To address this, we introduce <i>Mantra</i> (Minimizing trAp movemeNts for aTom aRray Architectures), which rewrites quantum programs to reduce the interleaving of single- and two-qubit gates. 
  <i>Mantra</i> incorporates three strategies: (i) a fountain-shaped controlled-Z (CZ) chain, (ii) ZZ-interaction protocol without a 1-qubit gate, and (iii) preemptive gate scheduling. 
  <i>Mantra</i> reduces inter-zone movements by 68%, physical gate counts by 35%, and improves circuit fidelities by 17% compared to the standard executions.
</div>



### Recompiling QAOA Circuits on Various Rotational Directions <a href="https://doi.org/10.1145/3656019.3676899" target="_blank"><i class="fa fa-book" title="Reference"></i></a>

<div style="display: flex; align-items: center;">
  <div style="width: 80%; padding-right: 10px;">
    <i>PACT '24: Proceedings of the 2024 International Conference on Parallel Architectures and Compilation Techniques</i>
    <br>13 Oct. 2024
  </div>
  <div style="width: 20%;">
    <img src="/assets/images/logo_pact.gif" alt="PACT 2024" width="100" height="100"/>
  </div>
</div>

<div style="text-align: center; font-size: 0.85em;">
Enhyeok Jang<sup>1</sup>, Dongho Ha<sup>2</sup>, Seungwoo Choi<sup>1</sup>, Youngmin Kim<sup>1</sup>, Jaewon Kwon<sup>1</sup>, Yongju Lee<sup>1</sup>, Sungwoo Ahn<sup>1</sup>, <b>Hyungseok Kim</b><sup>1</sup>, and Won Woo Ro<sup>1</sup>
<br><sup>1</sup>Yonsei University, Republic of Korea, <sup>2</sup>MangoBoost, Washington, USA
<br><br>
</div>

<div style="text-align: center;">
  <a class="btn btn--info" onclick="toggleContent(this)">
      <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>Abstract
  </a>
</div>
<div class="abstract" style="display: none;">
  The quantum approximate optimization algorithm (QAOA) is introduced to efficiently solve combinatorial optimization problems. 
  Despite the promise of QAOA, the cost of executing QAOA circuits at scale for quantum advantage may still be excessive for the near-future quantum device. 
  We observe the increasing overhead of QAOA circuit execution in the native gate translation. 
  To execute QAOA circuits on a real quantum computing device, Hamiltonians composed of predefined specific rotations (e.g., ZZ and X) should be decomposed into finite native gates. 
  By adopting rotational combinations that utilize native gates more directly than the standard QAOA circuit model, the execution cost on real quantum devices can be reduced. 
  In this study, we propose <i>Racoon</i> (<u>R</u>ot<u>a</u>tional Spa<u>c</u>e Virtualizati<u>o</u>n for QA<u>O</u>A A<u>n</u>satz), an algorithm-hardware co-design approach that revisits the synthesis conditions of QAOA circuits and selects alternative candidates with different rotational combinations. 
  Our analysis of six commercial quantum processors demonstrates that applying <i>Racoon</i> to QAOA circuits for the 4-node Sherrington-Kirkpatrick model reduces the number of native gates by an average of 23% and up to 79%. 
  Consequently, using <i>Racoon</i> results in 43% fewer training epochs, 41% lower training energy consumption, and a 6% improvement in inference on average compared to standard QAOA. 
  <i>Racoon</i> consistently reduces circuit depth as the number of qubits and layers increases, achieving 123 × more circuit depth reduction compared to the recently proposed Depth First Search (DFS)-based method. 
  Furthermore, we confirm that <i>Racoon</i>'s method can be extended to State-of-The-Art QAOAs with modified ansätze and to the variational quantum eigensolver (VQE).
</div>



## Workshops and Tutorials

### Native Gate-Aware QAOA Ansatz

<div style="display: flex; align-items: center;">
  <div style="width: 80%; padding-right: 10px;">
    <i>QDML '25: The 1st International Workshop on Quantum Data and Machine Learning: Systems, Theory and Hardware<br>In conjunction with ICDE '25</i>
    <br>19 May 2025
  </div>
  <div style="width: 20%;">
    <img src="/assets/images/logo_qdml.png" alt="QDML 2025" width="100" height="100"/>
  </div>
</div>

<div style="text-align: center; font-size: 0.85em;">
<b>Hyungseok Kim</b><sup>1</sup>, Enhyeok Jang<sup>1</sup>, Youngmin Kim<sup>1</sup>, and Won Woo Ro<sup>1</sup>
<br><sup>1</sup>Yonsei University, Republic of Korea
<br><br>
</div>

<div style="text-align: center;">
  <a class="btn btn--info" onclick="toggleContent(this)">
      <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>Abstract
  </a>
</div>
<div class="abstract" style="display: none;">
  The quantum approximate optimization algorithm (QAOA) is introduced to solve combinatorial optimization problems efficiently. 
  Despite the computational benefit of the QAOA, the cost of executing QAOA programs at scale to demonstrate quantum advantage is still expensive for the near-future quantum computing system.
  We observe that real quantum computing devices represent and execute QAOA circuits through their finite set of native gates.
  In general, the cost and mixer Hamiltonian are realized with ZZ and X-direction rotations of qubits, respectively.
  However, the rotation direction of the qubit for QAOA circuit training does not necessarily have to be configured only with the combination described above, nor is this combination of rotation always optimal for all quantum processors.
  By adopting rotational combinations that utilize native gates more directly than the standard QAOA circuit model, the execution cost on real quantum devices can be reduced.
  In this study, we propose <i>Racoon</i> (<u>R</u>ot<u>a</u>tional Spa<u>c</u>e Virtualizati<u>o</u>n for QA<u>O</u>A A<u>n</u>satz), an algorithm-hardware co-design approach that revisits the synthesis conditions of QAOA circuits and selects alternative candidates with different rotational combinations. 
  Our analysis of six commercial quantum processors demonstrates that applying <i>Racoon</i> to QAOA circuits for the 4-node Sherrington-Kirkpatrick model reduces the number of native gates by an average of 23% and up to 79%.
  Consequently, using <i>Racoon</i> results in 43% fewer training epochs, 41% lower training energy consumption, and a 6% improvement in inference on average compared to standard QAOA.
  <i>Racoon</i> consistently reduces circuit depth as the number of qubits and layers increases, achieving 123× more circuit depth reduction compared to the recently proposed Depth First Search (DFS)-based method.
  Furthermore, we confirm that <i>Racoon</i> method can be extended to state-of-the-art QAOAs with modified ansatz and to variational quantum eigensolvers (VQEs).
</div>



### A Dead Gate Elimination for Quantum Programs

<div style="display: flex; align-items: center;">
  <div style="width: 80%; padding-right: 10px;">
    <i>HAIQ '25: The 1st HPC/AI Integration with Quantum Computing Workshop<br>In conjunction with HPCA '25</i>
    <br>01 Mar. 2025
  </div>
  <div style="width: 20%;">
    <img src="/assets/images/logo_haiq.jpg" alt="HAIQ 2025" width="100" height="100"/>
  </div>
</div>

<div style="text-align: center; font-size: 0.85em;">
Enhyeok Jang<sup>1</sup>, Youngmin Kim<sup>1</sup>, <b>Hyungseok Kim</b><sup>1</sup>, Dongho Ha<sup>2</sup>, Yongju Lee<sup>1</sup>, Jaewon Kwon<sup>1</sup>, Jun Woo You<sup>1</sup>, Jiho Park<sup>1</sup>, and Won Woo Ro<sup>1</sup>
<br><sup>1</sup>Yonsei University, Republic of Korea, <sup>2</sup>MangoBoost, Washington, USA
<br><br>
</div>

<div style="text-align: center;">
  <a class="btn btn--info" onclick="toggleContent(this)">
      <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle;"></i>Abstract
  </a>
</div>
<div class="abstract" style="display: none;">
  The computational complexity of quantum programs is influenced by the limitations of the native gate set and the constraints imposed by qubit topology. 
  These factors necessitate advanced compilation techniques for efficient execution. 
  Our experimental data reveal that approximately 23.1% of gates in quantum programs are <i>dead gates</i>, which do not contribute to any meaningful alteration in the quantum state. 
  Removing these dead gates would provide the potential opportunity to reduce the size and improve the accuracy of the quantum program. 
  However, we observe that existing methods, including those integrated into Qiskit Transpiler, cannot adequately remove these unnecessary gates. 
  In this work, we introduce Dementor (<u>De</u>ad Quantu<u>m</u> Gat<u>e</u> Elimi<u>n</u>a<u>tor</u>), which efficiently detects and removes dead gates by considering a range of redundancy patterns. 
  To evaluate the efficacy of Dementor, we conducted experiments on IBM quantum processors, which have two distinct native gate sets: Echoed Cross-Resonance (ECR)-based and Controlled-X (CX)-based. 
  Our experiments show that Dementor achieves a reduction in the number of decomposed gates by an average of 46.4% on ECR-based systems and by an average of 60.6% on CX-based systems compared to Qiskit Transpiler with optimization level 3.
</div>



## Oral and Poster Presentations

### How Basis Choice Shapes Performance in Quantum Optimal Control Framework

<div style="display: flex; align-items: center;">
  <div style="width: 80%; padding-right: 10px;">
    <i>Summer Annual Conference of the Institute of Electronics and Information Engineers (IEIE), 2025</i>
    <br>27 Jun. 2025
  </div>
  <div style="width: 20%;">
    <img src="/assets/images/logo_ieie.jpg" alt="IEIE" width="100" height="100"/>
  </div>
</div>

<div style="text-align: center; font-size: 0.85em;">
Changheon Lee<sup>1</sup>, Youngmin Kim<sup>1</sup>, <b>Hyungseok Kim</b><sup>1</sup>, and Won Woo Ro<sup>1</sup>
<br><sup>1</sup>Yonsei University, Republic of Korea
<br><br>
</div>

<div style="text-align: center;">
  <a class="btn btn--info" onclick="toggleContent(this)">
      <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle;"></i>Abstract
  </a>
</div>
<div class="abstract" style="display: none;">
  Quantum optimal control (QOC) is essential for extracting the most algorithmic depth from today’s NISQ processors, yet its practical impact is limited by two factors: (i) the analytic basis used to parameterize each control pulse and (ii) the compilation latency required to generate highfidelity waveforms. 
  We find that ① Fourier envelopes outperforms Gaussian shapes by 1.24× on average, in terms of fidelity. 
  ② The Gaussian basis reduces gate length by 5% relative to the Fourier basis. 
  ③ The Gaussian envelope shave 11% from compilation latency compared to the Fourier basis. 
  ④ Sinc functions, although attractive in theory for their perfect rectangular spectra, underperform on fidelity.
</div>



## Journal Articles

### Research Trends and Prospects of Hybrid Computing-Based Variational Quantum Algorithms (VQA)

<div style="display: flex; align-items: center;">
  <div style="width: 80%; padding-right: 10px;">
    <i>The Magazine of the Institute of Electronics and Information Engineers (IEIE)</i>
    <br>2025
  </div>
  <div style="width: 20%;">
    <img src="/assets/images/logo_ieie.jpg" alt="IEIE" width="100" height="100"/>
  </div>
</div>

<div style="text-align: center; font-size: 0.85em;">
Youngmin Kim<sup>1</sup>, Changheon Lee<sup>1</sup>, <b>Hyungseok Kim</b><sup>1</sup>, and Won Woo Ro<sup>1</sup>
<br><sup>1</sup>Yonsei University, Republic of Korea
<br><br>
</div>



## Preprints

### Mantra: Rewriting Quantum Programs to Minimize Trap-Movements for Zoned Rydberg Atom Arrays <a href="https://doi.org/10.48550/arXiv.2503.02272" target="_blank"><i class="fa fa-book" title="Reference"></i></a>

<div style="display: flex; align-items: center;">
  <div style="width: 80%; padding-right: 10px;">
    <i>arXiv preprint</i>
    <br>04 Mar. 2025
  </div>
  <div style="width: 20%;">
    <img src="/assets/images/logo_arxiv.png" alt="arXiv" width="100" height="100"/>
  </div>
</div>

<div style="text-align: center; font-size: 0.85em;">
Enhyeok Jang<sup>1</sup>, Youngmin Kim<sup>1</sup>, <b>Hyungseok Kim</b><sup>1</sup>, Seungwoo Choi<sup>1</sup>, Yipeng Huang<sup>2</sup>, and Won Woo Ro<sup>1</sup>
<br><sup>1</sup>Yonsei University, Republic of Korea, <sup>2</sup>Rutgers University, New Jersey, USA
<br><br>
</div>

<div style="text-align: center;">
  <a class="btn btn--info" onclick="toggleContent(this)">
      <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle;"></i>Abstract
  </a>
</div>
<div class="abstract" style="display: none;">
  A zoned neutral atom architecture achieves exceptional fidelity by segregating the execution spaces of 1- and 2-qubit gates, being a promising candidate for high-accuracy quantum systems. 
  Unfortunately, naively applying programs designed for static qubit topologies to zoned architectures may result in most execution time being consumed by inter-zone travels of atoms. 
  To address this, we introduce <i>Mantra</i> (Minimizing trAp movemeNts for aTom aRray Architectures), which rewrites quantum programs to reduce the interleaving of single- and two-qubit gates. 
  <i>Mantra</i> incorporates three strategies: (i) a fountain-shaped controlled-Z (CZ) chain, (ii) ZZ-interaction protocol without a 1-qubit gate, and (iii) preemptive gate scheduling. 
  <i>Mantra</i> reduces inter-zone movements by 68%, physical gate counts by 35%, and improves circuit fidelities by 17% compared to the standard executions.
</div>



### Distribution-Adaptive Dynamic Shot Optimization for Variational Quantum Algorithms <a href="https://doi.org/10.48550/arXiv.2412.17485" target="_blank"><i class="fa fa-book" title="Reference"></i></a>

<div style="display: flex; align-items: center;">
  <div style="width: 80%; padding-right: 10px;">
    <i>arXiv preprint</i>
    <br>23 Dec. 2024
  </div>
  <div style="width: 20%;">
    <img src="/assets/images/logo_arxiv.png" alt="arXiv" width="100" height="100"/>
  </div>
</div>

<div style="text-align: center; font-size: 0.85em;">
Youngmin Kim<sup>1</sup>, Enhyeok Jang<sup>1</sup>, <b>Hyungseok Kim</b><sup>1</sup>, Seungwoo Choi<sup>1</sup>, Changhun Lee<sup>1</sup>, Donghwi Kim<sup>2</sup>, Woomin Kyoung<sup>2</sup>, Kyujin Shin<sup>2</sup>, and Won Woo Ro<sup>1</sup>
<br><sup>1</sup>Yonsei University, Republic of Korea, <sup>2</sup>Hyundai Motor Company, Republic of Korea
<br><br>
</div>

<div style="text-align: center;">
  <a class="btn btn--info" onclick="toggleContent(this)">
      <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle;"></i>Abstract
  </a>
</div>
<div class="abstract" style="display: none;">
  Variational quantum algorithms (VQAs) have attracted remarkable interest over the past few years because of their potential computational advantages on near-term quantum devices. 
  They leverage a hybrid approach that integrates classical and quantum computing resources to solve high dimensional problems that are challenging for classical approaches alone. 
  In the training process ofvariational circuits, constructing an accurate probability distribution for each epoch is not always necessary, creating opportunities to reduce computational costs through shot reduction. 
  However, existing shot-allocation methods that capitalize on this potential often lack adaptive feedback or aretied to specific classical optimizers, which limits their applicability to common VQAs and broader optimization techniques. 
  Our observations indicate that the information entropy of a quantum circuit's output distribution exhibits an approximately exponential relationship with the numberof shots needed to achieve a target Hellinger distance. 
  In this work, we propose a distribution-adaptive dynamic shot (DDS) framework that efficiently adjusts the number of shots per iterationin VQAs using the entropy distribution from the prior training epoch. 
  Our results demonstrate that the DDS framework sustains inference accuracy while achieving a ~50% reduction in average shotcount compared to fixed-shot training, and ~60% higher accuracy than recently proposed tiered shot allocation methods. 
  Furthermore, in noisy simulations that reflect the error rates of actual IBM quantum systems, DDS achieves approximately a ~30% reduction in the total number of shots compared to the fixed-shot method with minimal degradation in accuracy, and offers about ~70% higher computational accuracy than tiered shot allocation methods.
</div>