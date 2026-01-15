---
permalink: /portfolio/coursework/
title: "Selected Coursework"
toc: true
toc_sticky: true
toc_label: "Selected Coursework"
toc_icon:  "list-check"

header:
  show_overlay_excerpt: false
  overlay_image: /assets/images/header_books2.jpg
  caption: "Photo credit: [**Unsplash**](https://unsplash.com/photos/assorted-books-on-wooden-table-eMP4sYPJ9x0)"
  overlay_filter: 0.5
---

## Electrical and Electronic Engineering

### Quantum Computing

<a class="btn" onclick="toggleContent(this)">
    <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>
    1. <sup>BSc</sup>Quantum Computer and Simulation 1
</a>

<div class="description" style="display: none;">

<h6>Course Objective</h6>
<ul>
  <li>Understand the basic concepts of quantum computing and quantum information.</li>
  <li>Learn quantum algorithms and practice quantum coding using IBM Qiskit.</li>
  <li>Understand the physical systems that constitute qubits.</li>
  <li>Learn quantum error correction essential for NISQ devices.</li>
</ul>

<h6>Textbook</h6>
<ol>
  <li>
    Quantum Computing: A Gentle Introduction (MIT Press) by Eleanor Rieffel and Wolfgang Polak
    <a href="https://a.co/d/1odkDcg" target="_blank">
      <i class="fab fa-amazon" title="Amazon"></i>
    </a>
  </li>
</ol>

<h6>Quantum Coding Practice Materials</h6>
<ul>
  <li>
    <a href="https://github.com/qiskit-community/korean-community.git" target="_blank">
      <i class="fab fa-github" title="Github"></i>
    </a> korean-community / tutorials / 2023 Yonsei Lecture /
  </li>
</ul>

</div>

<!-- ------------------------------------ -->

<a class="btn" onclick="toggleContent(this)">
    <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>
    2. <sup>BSc</sup>Quantum Machine Learning
</a>

<div class="description" style="display: none;">

<h6>Course Objective</h6>
<ul>
  <li>Understand the basic principles of quantum information theory and its applications on quantum computing.</li>
  <li>Learn basic oracle-based quantum algorithms.</li>
  <li>Understand near-term quantum machine learning algorithms.</li>
</ul>

<h6>Textbook</h6>
<ol>
  <li>
    An Introduction to Quantum Computing (Oxford University Press) by Phillip Kaye, Raymond Laflamme, and Michele Mosca
    <a href="https://a.co/d/6FZXB1l" target="_blank">
      <i class="fab fa-amazon" title="Amazon"></i>
    </a>
  </li>
  <li>
    Quantum Computation and Quantum Information (Cambridge University Press) by Michael A. Nielsen and Isaac L. Chuang
    <a href="https://a.co/d/7eJEEGs" target="_blank">
      <i class="fab fa-amazon" title="Amazon"></i>
    </a>
  </li>
  <li>
    Machine Learning with Quantum Computers (Springer) by Maria Schuld and Francesco Petruccione
    <a href="https://a.co/d/3dj0lgZ" target="_blank">
      <i class="fab fa-amazon" title="Amazon"></i>
    </a>
  </li>
</ol>

</div>

<!-- ------------------------------------ -->

<a class="btn" onclick="toggleContent(this)">
    <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>
    3. <sup>BSc</sup>Electrical and Electronic Engineering Capstone Design
</a>

<div class="description" style="display: none;">

<h6>Course Objective</h6>
<ul>
  <li>Cultivate creative engineers with synthetic research ability.</li>
  <li>Develop an engineering program considering industry requirements.</li>
  <li>Summarize the undergraduate programs of EE.</li>
</ul>

<h6>Capstone Topic</h6>
<ul>
  <li><strong>Title</strong>: HS-Table: A Table-Based Algorithm for Optimizing Quantum Circuits through Qubit Reuse</li>
</ul>

<div style="text-align: center;">
  <a class="btn btn--info" onclick="toggleContent(this)">
      <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>Abstract
  </a>
</div>
<div class="abstract" style="display: none;">
    In the noisy intermediate-scale quantum (NISQ) era, resources to build and execute quantum computers are valuable, and saving the resources is a crucial matter. 
    Recently, mid-circuit measurement is being utilized to optimize quantum circuits. 
    Using the technique, the qubits of a quantum circuit can be reused during the execution, and it can reduce the resources and improve the fidelity of the circuit. 
    However, finding reusable qubits and transforming a circuit to an optimized form are challenging since the quantum gates in a quantum circuit are dependent each other. 
    We devised <i>HS-Table</i> (Hyungseok-Table) which represents a quantum circuit in a tabular format. 
    HS-Table shows the dependency in an orderly fashion, compared to representing a circuit as a directed acyclic graph (DAG), which has been used so far. 
    We designed a complete algorithm to optimize a quantum circuit through qubit reuse using HS-Table. 
    Using the HS-Table algorithm, the optimal form of a quantum circuit whose qubits are reused can be found. 
    The algorithm can be applied as a part of the compiler that compiles a written quantum program to an executable form. 
    By utilizing the algorithm, the following advantages can be obtained: (a) qubit usage is maximally reduced, (b) average circuit depth is decreased, and (c) SWAP gate insertion is reduced. 
    We verified the effects using practically used quantum applications and show that the qubit usage is reduced by 55%, average circuit depth is decreased by 61%, and SWAP gate insertion is reduced by 63% on regular applications. 
    For QAOA applications, we demonstrated the tradeoff between the reduction ratios and the topologies of the target graphs. 
    Using the scalable quantum applications, we showed that the algorithm is also effective to large-scale quantum circuits.
</div>

<h6>Capstone Team</h6>
<ul>
  <li><strong>Members</strong>: 1 student</li>
  <li><strong>Role</strong>: Team Leader</li>
  <li><strong>Responsibility</strong>: Every aspect of the project from planning to execution.</li>
</ul>

<h6>Research Lab</h6>
<ul>
  <li>
    <strong>Lab</strong>: Embedded Systems and Computer Architecture Lab (eSCaL)
    <a href="http://escal.yonsei.ac.kr/index.html" target="_blank">
      <i class="fa fa-house" title="Website"></i>
    </a>
  </li>
  <li>
    <strong>Advisor</strong>: 
    <a href="http://escal.yonsei.ac.kr/professor.html" target="_blank">
      Prof. Won Woo Ro
    </a>
  </li>
  <li>
    <strong>Teaching Assistant</strong>: 
    <a href="https://www.notion.so/Enhyeok-Jang-9f594ec32719477fa5ab8cf0f517a642?pvs=4" target="_blank">
      Enhyeok Jang
    </a>
  </li>
</ul>

</div>

<!-- ------------------------------------ -->

<a class="btn" onclick="toggleContent(this)">
    <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>
    4. <sup>MSc</sup>Quantum Computing
</a>

<div class="description" style="display: none;">

<h6>Course Objective</h6>
<ul>
  <li>Acquire a firm understanding of the quantum-mechanical foundations of qubit superposition, entanglement, and interference at the heart of all quantum computations.</li>
  <li>Understand the early quantum algorithms such as Deutsch’s Problem, Bernstein-Vazirani, and Quantum FFT, and be able to code and execute them on a QPU.</li>
  <li>Know recent near-term quantum algorithms like the quantum simulation of Hamiltonian dynamics.</li>
  <li>Understand and control, in principle, the quantum circuit compilation pipeline and error mitigation techniques to execute near-term quantum workloads on QPUs.</li>
</ul>

<h6>Textbook</h6>
<ol>
  <li>
    A Course in Quantum Computing (for the Community College) Volume 1 by Michael Loceff
    <a href="https://lapastillaroja.net/wp-content/uploads/2016/09/Intro_to_QC_Vol_1_Loceff.pdf" target="_blank">
      <i class="fa fa-book" title="Reference"></i>
    </a>
  </li>
  <li>
    Quantum Information Science (Oxford University Press) by Riccardo Manenti and Mario Motta
    <a href="https://a.co/d/hEAaItv" target="_blank">
      <i class="fab fa-amazon" title="Amazon"></i>
    </a>
  </li>
  <li>
    Quantum Algorithms via Linear Algebra (MIT Press) by Richard J. Lipton and Kenneth W. Regan
    <a href="https://a.co/d/hLAZzDM" target="_blank">
      <i class="fab fa-amazon" title="Amazon"></i>
    </a>
  </li>
</ol>

</div>

<!-- ------------------------------------ -->

<a class="btn" onclick="toggleContent(this)">
    <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>
    5. <sup>MSc</sup>Quantum Data Science
</a>

<div class="description" style="display: none;">

<h6>Course Objective</h6>
<ul>
  <li>Understand the fundamentals of quantum computing and why it can outperform classical computing for certain hard problems.</li>
  <li>Learn core quantum algorithms and quantum machine learning techniques relevant to modern data science tasks.</li>
  <li>Build enough theoretical background to apply quantum computing principles to real-world big data and computational challenges.</li>
</ul>

<h6>Textbook</h6>
<ol>
  <li>
    An Introduction to Quantum Computing (Oxford University Press) by Phillip Kaye, Raymond Laflamme, and Michele Mosca
    <a href="https://a.co/d/aYs6ZFv" target="_blank">
      <i class="fab fa-amazon" title="Amazon"></i>
    </a>
  </li>
  <li>
    Quantum Computation and Quantum Information (Cambridge University Press) by Michael A. Nielsen and Isaac L. Chuang
    <a href="https://a.co/d/80877IQ" target="_blank">
      <i class="fab fa-amazon" title="Amazon"></i>
    </a>
  </li>
  <li>
    Machine Learning with Quantum Computers (Springer) by Maria Schuld and Francesco Petruccione
    <a href="https://a.co/d/8PyTwqB" target="_blank">
      <i class="fab fa-amazon" title="Amazon"></i>
    </a>
  </li>
</ol>

<h6>Project (in groups of 3)</h6>
<ul>
  <li>
    Propose an original research idea that applies quantum computing techniques to a problem relevant to your domain expertise (e.g., data science, machine learning, AI, optimization, etc).
  </li>
</ul>

</div>

<!-- ------------------------------------ -->

### Computer Architecture

<a class="btn" onclick="toggleContent(this)">
    <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>
    1. <sup>BSc</sup>Digital Logic Circuits
</a>

<div class="description" style="display: none;">

<h6>Course Objective</h6>
<ul>
  <li>Understand the basic principles of digital circuits and analysing simple digital systems.</li>
  <li>Learn Boolean algebra, Karnaugh map, combinational circuit, and sequential circuit.</li>
</ul>

<h6>Textbook</h6>
<ol>
  <li>
    Contemporary Logic Design (Pearson) by Randy H. Katz and Gaetano Borriello
    <a href="https://a.co/d/dKk9GQi" target="_blank">
      <i class="fab fa-amazon" title="Amazon"></i>
    </a>
  </li>
</ol>

</div>

<!-- ------------------------------------ -->

<a class="btn" onclick="toggleContent(this)">
    <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>
    2. <sup>BSc</sup>Computer Architecture
</a>

<div class="description" style="display: none;">

<h6>Course Objective</h6>
<ul>
  <li>Understand the basic principles of computer architecture.</li>
  <li>Learn the structure of RISC CPU.</li>
  <li>Learn the CPU pipeline structure.</li>
  <li>Learn cache and memory structure.</li>
</ul>

<h6>Textbook</h6>
<ol>
  <li>
    Computer Organization and Design RISC-V Edition (Morgan Kaufmann) by David A. Patterson and John L. Hennessy
    <a href="https://a.co/d/cS3eyE1" target="_blank">
      <i class="fab fa-amazon" title="Amazon"></i>
    </a>
  </li>
</ol>

<h6>Projects</h6>
<ul>
  <li><strong>Project 1-1</strong>: Implement a simple combinational circuit using on Quartus II.</li>
  <li><strong>Project 1-2</strong>: Design an 8-bit arithmetic logic unit (ALU).</li>
  <li><strong>Project 2</strong>: Design a 64-bit single-cycle RISC-V microprocessor.</li>
  <li><strong>Project 3</strong>: Design a 64-bit pipelined RISC-V microprocessor.</li>
</ul>

<img src="/assets/images/coursework_ca.png" alt="Project 3" style="width: 80%; display: block; margin: 0 auto;">
<div style="font-size: 0.8em; text-align: center;">The block diagram of a pipelined RISC-V microprocessor.</div>

</div>

<!-- ------------------------------------ -->

<a class="btn" onclick="toggleContent(this)">
    <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>
    3. <sup>BSc</sup>Communication Networks
</a>

<div class="description" style="display: none;">

<h6>Course Objective</h6>
<ul>
  <li>Understand the basic principles of communication networks.</li>
  <li>Learn protocols of communication networks.</li>
  <li>Learn control algorithms of communication networks.</li>
</ul>

<h6>Textbook</h6>
<ol>
  <li>
    Computer Networking (Pearson) by James F. Kurose and Keith W. Ross
    <a href="https://a.co/d/iPX5Vqz" target="_blank">
      <i class="fab fa-amazon" title="Amazon"></i>
    </a>
  </li>
</ol>

<h6>Projects</h6>
<ul>
  <li><strong>Project 1</strong>: Investigate behaviors and analyze packets of HTTP, TCP, and UDP protocols using Wireshark.</li>
  <li><strong>Project 2</strong>: Investigate behaviors and analyze packets of IPv4, Ethernet, and 802.11 Wi-Fi protocols using Wireshark.</li>
</ul>

</div>

<!-- ------------------------------------ -->

<a class="btn" onclick="toggleContent(this)">
    <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>
    4. <sup>BSc</sup>Operating Systems
</a>

<div class="description" style="display: none;">

<h6>Course Objective</h6>
<ul>
  <li>Understand the basic principles of process and scheduling.</li>
  <li>Learn the basic concepts of memory virtualization, multi-threading, and file systems.</li>
  <li>Programming practice of operating systems using xv6-riscv.</li>
</ul>

<h6>Textbook</h6>
<ol>
  <li>
    Operating Systems: Three Easy Pieces by Remzi H. Arpaci-Dusseau and Andrea C. Arpaci-Dusseau
    <a href="https://pages.cs.wisc.edu/~remzi/OSTEP/" target="_blank">
      <i class="fa fa-book" title="Reference"></i>
    </a>
  </li>
</ol>

<h6>Projects</h6>
<ul>
  <li><strong>Assignment 1</strong>: Implement a simple shell in xv6-riscv.</li>
  <li><strong>Assignment 2</strong>: Add a new system call to xv6-riscv that probes processes and prints out their information, including process ID, execution state, runtime, and program name.</li>
  <li><strong>Assignment 3</strong>: Replace the round-robin process scheduler of xv6-riscv with a fair-share scheduling algorithm.</li>
  <li><strong>Assignment 4</strong>: Replace the next-fit free list management scheme of xv6-riscv's malloc library with the best-fit policy.</li>
  <li><strong>Assignment 5</strong>: Modify the paging scheme of xv6-riscv to allocate physical frames belatedly on their first write access, referred to as copy-on-write.</li>
  <li><strong>Assignment 6</strong>: Implement multi-threading features in xv6-riscv.</li>
</ul>

</div>

<!-- ------------------------------------ -->

<a class="btn" onclick="toggleContent(this)">
    <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>
    5. <sup>BSc</sup>Microprocessors
</a>

<div class="description" style="display: none;">

<h6>Course Objective</h6>
<ul>
  <li>Understand parallel architectures and major peripheral devices.</li>
  <li>Learn ARM processor and ARM assembly language for mobile SoCs.</li>
  <li>Learn the solid-state drive (SSD) architecture.</li>
</ul>

<h6>Project (in groups of 2)</h6>
<ul>
  <li>
    Design garbage collection and wear-leveling algorithm of block associative sector translation (BAST) flash translation layer (FTL) for an SSD.
  </li>
  <li>
    Team Member: 
    <a href="https://magic-lycra-8cf.notion.site/Portfolio-3e8cdf51b9da45cbbf6f071994031aa9" target="_blank">
        James Jihyun Moon
    </a>
  </li>
</ul>

</div>

<!-- ------------------------------------ -->

<a class="btn" onclick="toggleContent(this)">
    <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>
    6. <sup>BSc</sup>Multicore and GPU Programming
</a>

<div class="description" style="display: none;">

<h6>Course Objective</h6>
<ul>
  <li>Understand programming models for multi-threading (Pthread).</li>
  <li>Understand programming models for multicore CPUs (OpenMP).</li>
  <li>Understand programming models for GPUs (CUDA).</li>
</ul>

<h6>Textbook</h6>
<ol>
  <li>
    Programming Massively Parallel Processors: A Hands-on Approach (Morgan Kaufmann) by Wen-mei W. Hwu, David B. Kirk, and Izzat El Hajj
    <a href="https://a.co/d/9KFxLMG" target="_blank">
      <i class="fab fa-amazon" title="Amazon"></i>
    </a>
  </li>
  <li>
    Parallel Programming: Concepts and Practice (Morgan Kaufmann) by Bertil Schmidt, Jorge Gonzalez-Dominguez, Christian Hundt, and Moritz Schlarb
    <a href="https://a.co/d/hVPHI5c" target="_blank">
      <i class="fab fa-amazon" title="Amazon"></i>
    </a>
  </li>
  <li>
    C++ Concurrency in Action (Manning) by Anthony Williams
    <a href="https://a.co/d/hfHWZZ1" target="_blank">
      <i class="fab fa-amazon" title="Amazon"></i>
    </a>
  </li>
</ol>

<h6>Projects</h6>
<ul>
  <li><strong>Assignment 1</strong>: Implement a simple filter on 1D array using Pthread.</li>
  <li><strong>Assignment 2</strong>: Implement a hash table using open addressing method using Pthread.</li>
  <li><strong>Assignment 3</strong>: Implement a matrix multiplication kernel using OpenMP.</li>
  <li><strong>Assignment 4</strong>: Implement a matrix multiplication kernel using CUDA.</li>
  <li><strong>Assignment 5</strong>: Implement 7 versions of sum reduction kernels using CUDA.</li>
  <li><strong>Assignment 6</strong>: Implement the VGG16 DNN model using CUDA.</li>
</ul>

</div>

<!-- ------------------------------------ -->

### Machine Learning

<a class="btn" onclick="toggleContent(this)">
    <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>
    1. <sup>BSc</sup>Introduction Artificial Intelligence
</a>

<div class="description" style="display: none;">

<h6>Course Objective</h6>
<ul>
  <li>Understand the basic concepts and components of artificial intelligence (AI) and machine learning (ML).</li>
  <li>Learn to formulate and to prepare the data for learning processing.</li>
  <li>Learn to utilize and to implement programs for recognition applications and to evaluate the performance.</li>
</ul>

<h6>Textbook</h6>
<ol>
  <li>
    The Hundred-Page Machine Learning Book by Andriy Burkov
    <a href="https://a.co/d/1Klobej" target="_blank">
      <i class="fab fa-amazon" title="Amazon"></i>
    </a>
  </li>
</ol>

<h6>Projects</h6>
<ul>
  <li><strong>Project 1</strong>: Perform a linear regression for classification using the dataset <code>from sklearn.datasets import load_iris</code>.</li>
  <li><strong>Project 2</strong>: Train a decision tree regressor using the dataset <code>from sklearn.datasets import fetch_california_housing</code>.</li>
</ul>

</div>

<!-- ------------------------------------ -->

<a class="btn" onclick="toggleContent(this)">
    <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>
    2. <sup>BSc</sup>Intelligent Control
</a>

<div class="description" style="display: none;">

<h6>Course Objective</h6>
<ul>
  <li>Understand reinforcement learning through programming.</li>
  <li>Learn various reinforcement learning methods such as Markov Decision Process (MDP), Dynamic Programming (DP), Monte Carlo, Temporal-Difference (TD) learning, and Q-learning.</li>
  <li>Implement various reinforcement learning techniques through Python/PyTorch coding and compare their strengths and weaknesses.</li>
</ul>

<h6>Textbook</h6>
<ol>
  <li>
    Reinforcement Learning, second edition: An Introduction (Bradford Books) by Richard S. Sutton and Andrew G. Barto
    <a href="https://a.co/d/6XCtaII" target="_blank">
      <i class="fab fa-amazon" title="Amazon"></i>
    </a>
  </li>
</ol>

<h6>Projects</h6>
<ul>
  <li><strong>Project 1</strong>: Implement a program that solves the value function of a simple gridworld problem by matrix inversion.</li>
  <li><strong>Project 2</strong>: Implement the DP algorithm to solve a gridworld problem.</li>
  <li><strong>Project 3</strong>: Implement the Monte Carlo Control On Policy Simulation to solve a gridworld problem.</li>
  <li><strong>Project 4</strong>: Implement the Q-learning Simulation to solve a gridworld problem.</li>
</ul>

<img src="/assets/images/coursework_ic.png" alt="Gridworld" style="width: 50%; display: block; margin: 0 auto;">
<div style="font-size: 0.8em; text-align: center;">The gridworld problem.</div>

<h6>References</h6>
<ol>
  <li>
    Mnih, V., Kavukcuoglu, K., Silver, D. <em>et al.</em> Human-level control through deep reinforcement learning.
    <em>Nature</em> <strong>518</strong>, 529–533 (2015).
    <a href="https://doi.org/10.1038/nature14236" target="_blank">
      <i class="fa fa-book" title="Reference"></i>
    </a>
  </li>
</ol>

</div>

<!-- ------------------------------------ -->

<a class="btn" onclick="toggleContent(this)">
    <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>
    3. <sup>BSc</sup>Special Topics in Pattern Recognition
</a>

<div class="description" style="display: none;">

<h6>Course Objective</h6>
<ul>
  <li>Focus on a special topic about "elements of learning from data" by going through important components in the field and link among these learning elements in pattern recognition.</li>
  <li>Cover recent and advanced learning algorithms from literatures of machine learning, neural network, and pattern recognition with particular attention paying towards relationships among the learning components.</li>
</ul>

<h6>Textbook</h6>
<ol>
  <li>
    The Elements of Statistical Learning: Data Mining, Inference, and Prediction (Springer) by Trevor Hastie, Robert Tibshirani, and Jerome Friedman
    <a href="https://a.co/d/dL70zrf" target="_blank">
      <i class="fab fa-amazon" title="Amazon"></i>
    </a>
  </li>
</ol>

<h6>Projects</h6>
<ul>
  <li><strong>Project 1</strong>: Perform classification using the linear regression model and reduced multivariate (RM) model and compare the accuracies using the experimental data of Gaussian distribution.</li>
  <li><strong>Project 2</strong>: Perform a 5-fold cross validation test for the 3 data sets which are Mushroom, Iris, and Optical Recognition of Handwritten Digits, using the following algorithms: 3-layer multi-layer perceptron (MLP) at different hidden node sizes, support vector machine (SVM) using different kernels, and RM Model for orders 1 to 5.</li>
</ul>

<img src="/assets/images/coursework_pr.png" alt="Project 1" style="width: 60%; display: block; margin: 0 auto;">
<div style="font-size: 0.8em; text-align: center;">Project 1: The decision boundary line at order 5.</div>

<h6>References</h6>
<ol>
  <li>
    Kar-Ann Toh, Quoc-Long Tran and D. Srinivasan, "Benchmarking a reduced multivariate polynomial pattern classifier," in
    <em>IEEE Transactions on Pattern Analysis and Machine Intelligence</em>, vol. 26, no. 6, pp. 740–755, June 2004
    <a href="https://doi.org/10.1109/TPAMI.2004.3" target="_blank">
      <i class="fa fa-book" title="Reference"></i>
    </a>
  </li>
</ol>

</div>

<!-- ------------------------------------ -->

### Software Engineering

<a class="btn" onclick="toggleContent(this)">
    <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>
    1. <sup>BSc</sup>Engineering Information Processing
</a>

<div class="description" style="display: none;">

<h6>Course Objective</h6>
<ul>
  <li>Understand the basic concepts of programming.</li>
  <li>Learn problem solving methods using the C programming language.</li>
  <li>Improve the ability of solving some engineering-related subjects using the C programming language through various tasks.</li>
</ul>

<h6>Project (in groups of 2)</h6>
<ul>
  <li>
    Implement a household account book program with the following functions:
    print the contents of all entries, add a new entry, delete or modify an entry,
    find some item from entry, calculate the current balance, display verbal histogram,
    sort entries, display the sum of card and cash, write the contents to <code>account_book_new.txt</code> file, and quit.
  </li>
</ul>

<img src="/assets/images/coursework_eip.png" alt="Project" style="width: 50%; display: block; margin: 0 auto;">
<div style="font-size: 0.8em; text-align: center;">The initial screen of the household account book program.</div>

</div>

<!-- ------------------------------------ -->

<a class="btn" onclick="toggleContent(this)">
    <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>
    2. <sup>BSc</sup>Data Structure and Algorithms
</a>

<div class="description" style="display: none;">

<h6>Course Objective</h6>
<ul>
  <li>Understand abstract data types using the C programming language.</li>
  <li>Analyze and design basic algorithms.</li>
  <li>Introduction to the discrete mathematics system that is the basis of computer science and coding theory.</li>
</ul>

<h6>Textbook</h6>
<ol>
  <li>
    Data Structures and Algorithm Analysis in C (Pearson) by Mark Allen Weiss
    <a href="https://a.co/d/bBkDN9B" target="_blank">
      <i class="fab fa-amazon" title="Amazon"></i>
    </a>
  </li>
</ol>

</div>

<!-- ------------------------------------ -->

### Digital System Design

<a class="btn" onclick="toggleContent(this)">
    <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>
    1. <sup>BSc</sup>Introductory Digital Labs
</a>

<div class="description" style="display: none;">

<h6>Course Objective</h6>
<ul>
  <li>Learn basic digital logic design skills through laboratory experiments and projects.</li>
</ul>

<h6>Projects</h6>
<ul>
  <li>
    Implement a simple running game on a XILINX PYNQ-Z2 board.
    <ol>
      <li>
        Characters: 
        <a href="https://www.yonsei.ac.kr/en_sc/1804/subview.do" target="_blank">Yonsei University Eagle</a>,
        <a href="https://brand.mit.edu/logos-marks/tim-beaver" target="_blank">MIT Beaver</a>, and 
        <a href="https://identity.caltech.edu/officiallogomarks/athletics" target="_blank">Caltech Beaver</a>.
      </li>
      <li>
        Background music: The Skaters' Waltz from <em>Antarctic Adventure</em> (1983) by KONAMI. <a href="https://open.spotify.com/track/5XkIJ4UGZ2QvusWhFXBU5i" target="_blank"><i class="fab fa-spotify" title="Spotify"></i></a>
        Originally composed by Émile Waldteufel. <a href="https://en.wikipedia.org/wiki/%C3%89mile_Waldteufel" target="_blank"><i class="fab fa-wikipedia-w" title="Wikipedia"></i></a>
      </li>
    </ol>
  </li>
</ul>

<div style="display: flex;">
<iframe width="226" height="127" 
    src="https://www.youtube.com/embed/ziwD89N9HxE?si=DScZf7jL9Gn0Ldq6" 
    title="YouTube video player" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
    referrerpolicy="strict-origin-when-cross-origin" 
    allowfullscreen>
</iframe>
<iframe width="226" height="127" 
    src="https://www.youtube.com/embed/NHBaYf8Geag?si=jvJbs6CFz0_typpG" 
    title="YouTube video player" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
    referrerpolicy="strict-origin-when-cross-origin" 
    allowfullscreen>
</iframe>
<iframe width="226" height="127" 
    src="https://www.youtube.com/embed/LRzXyT2rxAA?si=dVvw6q3fHezhSXOH" 
    title="YouTube video player" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
    referrerpolicy="strict-origin-when-cross-origin" 
    allowfullscreen>
</iframe>
</div>

</div>

<!-- ------------------------------------ -->

<a class="btn" onclick="toggleContent(this)">
    <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>
    2. <sup>BSc</sup>Digital Microelectronics
</a>

<div class="description" style="display: none;">

<h6>Course Objective</h6>
<ul>
  <li>Understand CMOS transistors.</li>
  <li>Learn combinational and sequential VLSI circuit design.</li>
  <li>Learn subsystems of a computer such as data path, array, I/O, and clock.</li>
</ul>

<h6>Textbook</h6>
<ol>
  <li>
    Integrated Circuit Design: Global Edition (Pearson) by Neil H. E. Weste and David Money Harris
    <a href="https://a.co/d/2gf5FKv" target="_blank">
      <i class="fab fa-amazon" title="Amazon"></i>
    </a>
  </li>
</ol>

<h6>Project (in groups of 2)</h6>
<ul>
  <li>
    Design a 6-bit decoder and digitally controlled delay line (DCDL) using combinational circuit.
    <ol>
      <li>Pre-/main- decoder structural analysis and design considering metal resistance and capacitance.</li>
      <li>DCDL structural analysis and design considering uniform step-delay.</li>
    </ol>
  </li>
</ul>

<img src="/assets/images/coursework_dm.png" alt="Project" style="width: 30%; display: block; margin: 0 auto;">
<div style="font-size: 0.8em; text-align: center;">A uniform step-delay DCDL.</div>

<h6>References</h6>
<ol>
  <li>
    R. -J. Yang and S. -I. Liu, "A 40-550 MHz Harmonic-Free All-Digital Delay-Locked Loop Using a Variable SAR Algorithm," in <em>IEEE Journal of Solid-State Circuits</em>, vol. 42, no. 2, pp. 361-373, Feb. 2007 
    <a href="http://doi.org/10.1109/JSSC.2006.889381" target="_blank">
      <i class="fa fa-book" title="Reference"></i>
    </a>
  </li>
</ol>

</div>

<!-- ------------------------------------ -->

<a class="btn" onclick="toggleContent(this)">
    <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>
    3. <sup>BSc</sup>System IC Design
</a>

<div class="description" style="display: none;">

<h6>Course Objective</h6>
<ul>
  <li>Understand system IC design flow.</li>
  <li>Learn structural and behavioral modeling.</li>
  <li>Learn synthesis and verification.</li>
  <li>Learn design for testability and low power.</li>
</ul>

<h6>Project (in groups of 3)</h6>
<ul>
  <li>Design, verify, and synthesize a modified advanced encryption standard (AES) 128 decryptor.</li>
</ul>

<h6>References</h6>
<ol>
  <li>
    Explanatory material for AES by Intel.
    <a href="https://www.intel.com/content/dam/doc/white-paper/advanced-encryption-standard-new-instructions-set-paper.pdf" target="_blank">
      <i class="fa fa-book" title="Reference"></i>
    </a>
  </li>
  <li>
    AES specification by Federal Information Processing Standard (FIPS) Publication 197.
    <a href="https://nvlpubs.nist.gov/nistpubs/fips/nist.fips.197.pdf" target="_blank">
      <i class="fa fa-book" title="Reference"></i>
    </a>
  </li>
</ol>

</div>

<!-- ------------------------------------ -->

<a class="btn" onclick="toggleContent(this)">
    <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>
    4. <sup>BSc</sup>Embedded System Lab.
</a>

<div class="description" style="display: none;">

<h6>Projects</h6>
<ul>
  <li><strong>Midterm Project</strong>
    <ul>
      <li>
        Abstract: <br>
        This report introduces a methodology of designing a liquid-crystal display (LCD) controller utilizing a fieldprogrammable gate array (FPGA) board. The controller controls two LCDs: a Text-LCD and a thin-film-transistor LCD (TFT-LCD). Instead of merely displaying texts, it interlocks data of two LCDs and implements effects such as blinking and color. Effects can be controlled through external buttons. The controller is designed through Verilog hardware description language (HDL) and implemented on an FPGA board. By operating the designed LCD controller, it can be verified that LCDs display and exchange characters in the form of American standard code for information interchange (ASCII) codes.

        <img src="/assets/images/coursework_esl1.png" alt="Midterm Project" style="width: 80%; display: block; margin: 0 auto;">
        <div style="font-size: 0.8em; text-align: center;">A block diagram of the LCD controller.</div>
      </li>
    </ul>
  </li>

  <li><strong>Final Project</strong>
    <ul>
      <li>
        Abstract: <br>
        This report introduces the methodology of designing an interrupt clock using a field-programmable gate array (FPGA) board. The interrupt clock has two functions: retrieving the initial time from the real-time clock (RTC) and setting the time. The clock receives push button signals as interrupts, and these interrupts control the clock functions. The time is displayed on the 7-segment. The input/output (I/O) part is designed in Verilog hardware description language (HDL) and the firmware which handles interrupts is designed in the C programming language. By operating the designed interrupt clock, it can be verified that the clock manages interrupts using the interrupt device handler.

        <img src="/assets/images/coursework_esl2.png" alt="Final Project" style="width: 80%; display: block; margin: 0 auto;">
        <div style="font-size: 0.8em; text-align: center;">A block diagram of the interrupt clock.</div>
      </li>
    </ul>
  </li>
</ul>

</div>

<!-- ------------------------------------ -->

<a class="btn" onclick="toggleContent(this)">
    <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>
    5. <sup>MSc</sup>Semiconductor Memory Design
</a>

<div class="description" style="display: none;">

<h6>Course Objective</h6>
<ul>
  <li>Learn the relevant design and technology topics for the current and emerging semiconductor memories.</li>
  <li>Instructors from SK Hynix deliver weekly lectures on the following topics:
    <ol>
      <li>SK Hynix & Memory Tech Overview</li>
      <li>DRAM Design & Operation</li>
      <li>Computing DRAM</li>
      <li>Mobile DRAM</li>
      <li>I/O Interface</li>
      <li>HBM Technology</li>
      <li>Advanced Package Technologies</li>
      <li>NAND Flash Design & Operation</li>
      <li>Flash Solution Products</li>
      <li>Memory and Storage Solution for Generative AI</li>
      <li>CMOS Image Sensor Design</li>
      <li>Emerging Memory Design Technologies</li>
    </ol>
  </li>
</ul>

</div>

<!-- ------------------------------------ -->

### Analog System Design

<a class="btn" onclick="toggleContent(this)">
    <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>
    1. <sup>BSc</sup>Basic Circuit Theory
</a>

<div class="description" style="display: none;">

<h6>Course Objective</h6>
<ul>
  <li>Learn fundamental components comprising the analog circuits.</li>
  <li>Build the proper equations governing the circuit behaviors.</li>
  <li>Learn algebraic equations explaining the static characteristics.</li>
  <li>Learn differential equations explaining the dynamic characteristics.</li>
</ul>

<h6>Textbook</h6>
<ol>
  <li>
    Introduction to Electric Circuits (Wiley) by James A. Svoboda and Richard C. Dorf
    <a href="https://a.co/d/1bngi0l" target="_blank">
      <i class="fab fa-amazon" title="Amazon"></i>
    </a>
  </li>
</ol>

</div>

<!-- ------------------------------------ -->

<a class="btn" onclick="toggleContent(this)">
    <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>
    2. <sup>BSc</sup>Electronic Circuits
</a>

<div class="description" style="display: none;">

<h6>Course Objective</h6>
<ul>
  <li>Understand electronic circuits using Diode and Transistors.</li>
  <li>Understand the physics of semiconductor.</li>
  <li>Understand the physics of bipolar (BJT) and field effect (FET) transistors.</li>
  <li>Design BJT and FET amplifiers.</li>
  <li>Design multi-stage amplifiers.</li>
</ul>

<h6>Textbook</h6>
<ol>
  <li>
    Fundamentals of Microelectronics (Wiley) by Behzad Razavi
    <a href="https://a.co/d/0tSO6jd" target="_blank">
      <i class="fab fa-amazon" title="Amazon"></i>
    </a>
  </li>
</ol>

<h6>Projects</h6>
<ul>
  <li>
    Design a two stage amplifier based on bipolar junction transistors (BJTs).
    <ol>
      <li>Find the parameters and small signal model of BJTs.</li>
      <li>Design a common emitter amplifier with a voltage gain higher than 45 dB.</li>
      <li>Design an amplifier to drive a low impedance load.</li>
    </ol>
  </li>
</ul>

<img src="/assets/images/coursework_ec.png" alt="Project" style="width: 60%; display: block; margin: 0 auto;">
<div style="font-size: 0.8em; text-align: center;">Full circuit of the two-stage amplifier.</div>

<h6>References</h6>
<ol>
  <li>
    Modern Semiconductor Devices for Integrated Circuits (Pearson) by Chenming Hu
    <a href="https://a.co/d/gZM2V2G" target="_blank">
      <i class="fab fa-amazon" title="Amazon"></i>
    </a>
  </li>
</ol>

</div>

<!-- ------------------------------------ -->

<a class="btn" onclick="toggleContent(this)">
    <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>
    3. <sup>BSc</sup>Analog Electronics Lab.
</a>

<div class="description" style="display: none;">

<h6>Course Objective</h6>
<ul>
  <li>Verify the theoretical content of circuit theory through experiments and perform application projects.</li>
</ul>

<h6>Projects</h6>
<ul>
  <li>
    Design electrocardiogram (ECG) readout circuit.
    <ol>
      <li>Design ECG readout circuit using instrumentation amplifier (IA), notch filter, low-pass filter, and high-pass filter.</li>
      <li>Verify the design through PSpice simulation.</li>
      <li>Implement the design with breadboards and measuring ECG signals.</li>
    </ol>
  </li>
</ul>

<img src="/assets/images/coursework_ael.png" alt="Project" style="width: 30%; display: block; margin: 0 auto;">
<div style="font-size: 0.8em; text-align: center;">The ECG readout result.</div>

</div>

<!-- ------------------------------------ -->

### Telecommunications Engineering

<a class="btn" onclick="toggleContent(this)">
    <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>
    1. <sup>BSc</sup>Signal and Systems
</a>

<div class="description" style="display: none;">

<h6>Course Objective</h6>
<ul>
  <li>Learn signal and system characteristics and models.</li>
  <li>Learn time-domain analysis of continuous-time signals.</li>
  <li>Understand frequency-domain of continuous-time signals.</li>
  <li>Understand analysis of continuous-time systems using Laplace transform.</li>
  <li>Understand analysis of discrete-time systems using z-transform.</li>
</ul>

<h6>Textbook</h6>
<ol>
  <li>
    Signal and Linear System Analysis 2e (John Wiley & Sons) by Gordon E. Carlson
    <a href="https://a.co/d/iOZ2w6X" target="_blank">
      <i class="fab fa-amazon" title="Amazon"></i>
    </a>
  </li>
</ol>

<h6>MATLAB Onramp</h6>
<ul>
  <li>
    Recieved course completion certificate on 11 May 2020 from MathWorks.
    <a href="https://matlabacademy.mathworks.com/en/details/matlab-onramp/gettingstarted" title="MathWorks" target="_blank">
      <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" viewBox="0 0 32 32">
        <path fill="currentColor" d="M5.765 21.661C4.172 20.473 2.188 19.078 0 17.489l7.749-2.979l3.183 2.385c-2.385 2.781-3.973 3.776-5.167 4.771zm21.266-8.344c-.599-1.588-.995-3.181-1.593-4.771c-.593-1.792-1.187-3.38-2.183-4.771c-.4-.593-1.192-1.989-2.187-1.989c-.199 0-.396.197-.599.197c-.595.204-1.391 1.391-1.589 2.188c-.593.995-1.792 2.583-2.583 3.577c-.199.396-.6.797-.797.996c-.593.395-1.193.995-1.984 1.391c-.204 0-.401.197-.599.197c-.595 0-.996.396-1.391.593c-.595.6-1.193 1.391-1.787 1.991c0 .197-.204.395-.401.599l2.984 2.181c2.188-2.583 4.771-5.167 6.557-10.135c0 0-.593 5.369-5.364 11.131c-2.985 3.38-5.371 5.171-5.767 5.567c0 0 .792-.197 1.589.199c1.593.593 2.385 2.781 2.984 4.369c.396 1.193.989 2.188 1.391 3.38c1.589-.396 2.584-.995 3.579-1.989c.989-.989 1.984-2.183 2.979-3.177c1.792-2.187 3.975-4.968 6.756-3.577c.4.197.995.599 1.192.796c.599.396.995.792 1.593 1.391c.991.792 1.391 1.391 2.183 1.787c-1.984-3.973-3.375-7.948-4.968-12.125z"/>
      </svg>
    </a>
  </li>
</ul>

<h6>Projects</h6>
<ul>
  <li><strong>Project 1</strong>: Plot continuous-time, discrete-time, and Fourier transformed signals.</li>
  <li><strong>Project 2</strong>: Verify the Paley Wiener theory, properties of Fourier transform, and the Nyquist-Shannon sampling theorem.</li>
  <li><strong>Project 3</strong>:
    <ol>
      <li>Restore the music signal* sampled at 4000 Hz to the original signal using a low-pass filter (LPF).</li>
      <li>Remove noise from a music signal** using an LPF.</li>
    </ol>
    <p>
      &nbsp;&nbsp;&nbsp;&nbsp;*What is Love? (2018) by TWICE
      <a href="https://open.spotify.com/track/3zhbXKFjUDw40pTYyCgt1Y?si=f5416cccd7b944be&nd=1&dlsi=aefc1535489d41c1" target="_blank">
        <i class="fab fa-spotify" title="Spotify"></i>
      </a>
      &nbsp;&nbsp;&nbsp;&nbsp;**Secret Garden (2017) by IU
      <a href="https://open.spotify.com/track/5F6nAnNIsRk9QbPOx9t11B?si=cc051a133ed64a0c&nd=1&dlsi=53d104c23545482d" target="_blank">
        <i class="fab fa-spotify" title="Spotify"></i>
      </a>
    </p>
  </li>
  <li><strong>Project 4</strong>: Verify Fourier transform, Laplace transform, and z-transform on different examples.</li>
</ul>

<div style="display: flex;">
    <img src="/assets/images/coursework_ss1.png" alt="Project 3(1)" style="width: 30%; display: block; margin: 0 auto;">
    <img src="/assets/images/coursework_ss2.png" alt="Project 3(1)" style="width: 30%; display: block; margin: 0 auto;">
    <img src="/assets/images/coursework_ss3.png" alt="Project 3(1)" style="width: 30%; display: block; margin: 0 auto;">
</div>
<div style="font-size: 0.8em; text-align: center;">Project 3(1): Original signal (left), Sampled at 4000 Hz (middle), and Restored using LPF (right).</div>

<div style="text-align: center;">
    <audio controls>
        <source src="/assets/images/coursework_ss6.wav" type="audio/wav">
        Your browser does not support the audio element.
    </audio>
</div>
<div style="text-align: center;">
    <audio controls>
        <source src="/assets/images/coursework_ss7.wav" type="audio/wav">
        Your browser does not support the audio element.
    </audio>
</div>
<div style="font-size: 0.8em; text-align: center;">Project 3(1): Original signal (top) and Restored using LPF after sampled (bottom).</div>

<br>

<div style="display: flex;">
    <img src="/assets/images/coursework_ss4.png" alt="Project 3(1)" style="width: 30%; display: block; margin: 0 auto;">
    <img src="/assets/images/coursework_ss5.png" alt="Project 3(1)" style="width: 30%; display: block; margin: 0 auto;">
</div>
<div style="font-size: 0.8em; text-align: center;">Project 3(2): Noise contained (left) and Noise removed using LPF (right).</div>

<div style="text-align: center;">
    <audio controls>
        <source src="/assets/images/coursework_ss8.wav" type="audio/wav">
        Your browser does not support the audio element.
    </audio>
</div>
<div style="text-align: center;">
    <audio controls>
        <source src="/assets/images/coursework_ss9.wav" type="audio/wav">
        Your browser does not support the audio element.
    </audio>
</div>
<div style="font-size: 0.8em; text-align: center;">Project 3(2): Noise contained (top) and Noise removed using LPF (bottom).</div>

</div>

<!-- ------------------------------------ -->

<a class="btn" onclick="toggleContent(this)">
    <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>
    2. <sup>BSc</sup>Electricity & Magnetism (1)
</a>

<div class="description" style="display: none;">

<h6>Course Objective</h6>
<ul>
  <li>Learn the basic characteristics of electric and magnetic fields.</li>
  <li>Understand the meaning and phenomenon of electromagnetic waves through Maxwell's equations, which combine electric and magnetic fields in the time domain.</li>
</ul>

<h6>Textbook</h6>
<ol>
  <li>
    Field and Wave Electromagnetics: Pearson New International E (Pearson) by David K. Cheng
    <a href="https://a.co/d/iCUWvaV" target="_blank">
      <i class="fab fa-amazon" title="Amazon"></i>
    </a>
  </li>
</ol>

</div>

<!-- ------------------------------------ -->

## Economics

### Econometrics

<a class="btn" onclick="toggleContent(this)">
    <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>
    1. <sup>BA</sup>Econometrics I
</a>

<div class="description" style="display: none;">

<h6>Course Objective</h6>
<ul>
  <li>Introduction to popular skills for analysing economic data.</li>
  <li>Get familiar with the well-known economic analysis and relate this to the knowledge about the numerical outputs generated by standard statistical packages.</li>
  <li>Understand the implicit assumptions behind economic data analysis.</li>
</ul>

<h6>Textbook</h6>
<ol>
  <li>
    Introduction to Econometrics, Global Edition (Pearson) by James H. Stock and Mark W. Watson
    <a href="https://a.co/d/aG6p4qd" target="_blank">
      <i class="fab fa-amazon" title="Amazon"></i>
    </a>
  </li>
</ol>

</div>

<!-- ------------------------------------ -->

<a class="btn" onclick="toggleContent(this)">
    <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>
    2. <sup>BA</sup>Financial Econometrics
</a>

<div class="description" style="display: none;">

<h6>Course Objective</h6>
<ul>
  <li>Learn economic methods for modeling, analysing, and forecasting financial data.</li>
  <li>Understand different estimation methodologies.</li>
  <li>Critically evaluate empirical results and implications.</li>
</ul>

<h6>Textbook</h6>
<ol>
  <li>
    Introductory Econometrics for Finance (Cambridge University Press) by Chris Brooks
    <a href="https://a.co/d/gLWSj9p" target="_blank">
      <i class="fab fa-amazon" title="Amazon"></i>
    </a>
  </li>
</ol>

</div>

<!-- ------------------------------------ -->

### DSGE Modeling

<a class="btn" onclick="toggleContent(this)">
    <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>
    1. <sup>BA</sup>Dynamic Analysis of Macroeconomy
</a>

<div class="description" style="display: none;">

<h6>Course Objective</h6>
<ul>
  <li>Learn the dynamic stochastic general equilibrium (DSGE) model.</li>
  <li>Understand business cycle theory, dynamic changes in the macro labor market, and the effects of monetary policy applying DSGE.</li>
</ul>

<h6>Textbook</h6>
<ol>
  <li>
    Macroeconomics by Matthias Doepke, Andreas Lehnert, and Andrew Sellgren
    <a href="https://faculty.wcas.northwestern.edu/mdo738/book.htm" target="_blank">
      <i class="fa fa-book" title="Reference"></i>
    </a>
  </li>
  <li>
    Macroeconomics (MIT Press) by Robert J. Barro
    <a href="https://a.co/d/5WrelpZ" target="_blank">
      <i class="fab fa-amazon" title="Amazon"></i>
    </a>
  </li>
  <li>
    Advanced Macroeconomics (McGraw-Hill/Irwin) by David Romer
    <a href="https://a.co/d/62atimX" target="_blank">
      <i class="fab fa-amazon" title="Amazon"></i>
    </a>
  </li>
  <li>
    Elements of Dynamic Optimization (Waveland Pr Inc) by Alpha C. Chiang
    <a href="https://a.co/d/8DkaBQD" target="_blank">
      <i class="fab fa-amazon" title="Amazon"></i>
    </a>
  </li>
  <li>
    Fundamental Methods of Mathematical Economics (McGraw-Hill) by Alpha C. Chiang and Kevin Wainwright
    <a href="https://a.co/d/62VojZb" target="_blank">
      <i class="fab fa-amazon" title="Amazon"></i>
    </a>
  </li>
</ol>

</div>

<!-- ------------------------------------ -->

<a class="btn" onclick="toggleContent(this)">
    <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>
    2. <sup>BA</sup>Quantitative Macroeconomics
</a>

<div class="description" style="display: none;">

<h6>Course Objective</h6>
<ul>
  <li>Introduction to dynamic macroeconomic models that have been widely employed in modern macroeconomic analyses.</li>
  <li>Provide an oppertunity to learn and practice numerical techniques to implement the theories.</li>
</ul>

<h6>Projects</h6>
<ul>
  <li><strong>Coding 1</strong>: Solve a consumer's utility maximization problem.</li>
  <li><strong>Coding 2</strong>: Solve a dynamic stochastic general equilibrium model. Implement value function iteration, policy function iteration, and endogenous grid method.</li>
  <li><strong>Coding 3</strong>: Solve an income fluctuation problem where assets are stochastic and denoted as a finite Markov matrix.</li>
  <li><strong>Coding 4</strong>: Simulate a lake model of labor markets.</li>
  <li><strong>Coding 5</strong>: Solve a McCall model with separation and stochastic offers.</li>
  <li><strong>Coding 6</strong>: Solve a Lucas tree model of asset pricing with Tauchen's method.</li>
</ul>

<h6>References</h6>
<ol>
  <li>
    QuantEcon
    <a href="https://quantecon.org" target="_blank">
      <i class="fa fa-house" title="Website"></i>
    </a>
  </li>
</ol>

</div>

<!-- ------------------------------------ -->

### Financial Engineering

<a class="btn" onclick="toggleContent(this)">
    <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>
    1. <sup>BA</sup>Introduction to Financial Engineering
</a>

<div class="description" style="display: none;">

<h6>Course Objective</h6>
<ul>
  <li>Understand the types of derivatives.</li>
  <li>Learn derivatives pricing principles.</li>
  <li>Learn the risk management of derivatives.</li>
</ul>

<h6>References</h6>
<ol>
  <li>
    John C. Cox, Stephen A. Ross, and Mark Rubinstein, Option pricing: A simplified approach, <em>Journal of Financial Economics</em>, Volume 7, Issue 3, 1979, Pages 229-263, ISSN 0304-405X.
    <a href="http://doi.org/10.1016/0304-405X(79)90015-1" target="_blank">
      <i class="fa fa-book" title="Reference"></i>
    </a>
  </li>
  <li>
    Fischer Black and Myron Scholes. "The Pricing of Options and Corporate Liabilities," <em>Journal of Political Economy</em>, vol. 81, no. 3, 1973, pp. 637-54.
    <a href="https://www.jstor.org/stable/1831029" target="_blank">
      <i class="fa fa-book" title="Reference"></i>
    </a>
  </li>
  <li>
    "NOVA: Trillion Dollar Bet," <em>PBS</em>, 2000.
    <a href="https://www.imdb.com/title/tt1028385/" target="_blank">
      <i class="fab fa-imdb" title="IMDb"></i>
    </a>
  </li>
</ol>

<h6>Datacamp Accomplishments
  <a href="https://www.datacamp.com/" title="DataCamp" target="_blank">
    <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" viewBox="0 0 24 24">
      <path fill="currentColor" d="M12.946 18.151v-5.239L21.209 8.2L19.2 7.048l-6.254 3.567V5.36c0-.356-.192-.689-.5-.866L4.922.177a1.43 1.43 0 0 0-1.455.044a1.44 1.44 0 0 0-.676 1.224v14.777A1.44 1.44 0 0 0 4.92 17.49l6.032-3.44v4.683a1 1 0 0 0 .504.867l7.73 4.4l2.01-1.152zM10.953 5.938v5.814L4.785 15.27V2.4l6.168 3.539z"/>
    </svg>
  </a>
</h6>
<ol>
  <li>Introduction to Python</li>
  <li>Intermediate Python</li>
  <li>Python Data Science Toolbox (Part 1)</li>
  <li>Supervised Learning with scikit-learn</li>
  <li>Introduction to Deep Learning in Python</li>
  <li>Advanced Deep Learning with Keras</li>
</ol>

<h6>Projects</h6>
<ul>
  <li>
    Deep Hedging on Fixed Strike Asian Options
    <ul>
      <li>
        Abstract: <br>
        The Black-Scholes model is highly important and widely used strategy for the risk hedging of options. However, the Black-Scholes model has many limitations, and it is often unsuitable for application. This report introduces the method of option pricing using deep learning, which is called deep hedging, and applies the method on fixed strike Asian options.
      </li>
    </ul>
  </li>
</ul>

<img src="/assets/images/coursework_ife.png" alt="Project" style="width: 40%; display: block; margin: 0 auto;">
<div style="font-size: 0.8em; text-align: center;">Result of deep hedging on Asian option using sigmoid function.</div>

</div>

<!-- ------------------------------------ -->

<a class="btn" onclick="toggleContent(this)">
    <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>
    2. <sup>BA</sup>Coding for Economics 2
</a>

<div class="description" style="display: none;">

<h6>Course Objective</h6>
<ul>
  <li>Analyze the balance of a model economy by applying quantitative analysis algorithms to various economic theories.</li>
  <li>Perform numerical analysis of changes in balance according to changes in the economic environment.</li>
</ul>

<h6>Datacamp Accomplishments
  <a href="https://www.datacamp.com/" title="DataCamp" target="_blank">
    <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" viewBox="0 0 24 24">
      <path fill="currentColor" d="M12.946 18.151v-5.239L21.209 8.2L19.2 7.048l-6.254 3.567V5.36c0-.356-.192-.689-.5-.866L4.922.177a1.43 1.43 0 0 0-1.455.044a1.44 1.44 0 0 0-.676 1.224v14.777A1.44 1.44 0 0 0 4.92 17.49l6.032-3.44v4.683a1 1 0 0 0 .504.867l7.73 4.4l2.01-1.152zM10.953 5.938v5.814L4.785 15.27V2.4l6.168 3.539z"/>
    </svg>
  </a>
</h6>
<ol>
  <li>Manipulating Time Series Data in Python</li>
  <li>Introduction to Portfolio Analysis in Python</li>
  <li>Introduction to Portfolio Risk Management in Python</li>
  <li>Quantitative Risk Management in Python</li>
  <li>Credit Risk Modeling in Python</li>
</ol>

<h6>Projects</h6>
<ul>
  <li><strong>Coding 1</strong>: Analyze demographic data and financial data.</li>
  <li><strong>Coding 2</strong>: Dynamics of population distribution by age. Find equilibria of competitive markets.</li>
  <li><strong>Coding 3</strong>: Simulate Friedman-Hall consumption smoothing model and present value model of asset pricing theory. Find general equilibrium of an economic model with nonlinear demands and supplies using Newton's method.</li>
</ul>

</div>

<!-- ------------------------------------ -->

<a class="btn" onclick="toggleContent(this)">
    <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>
    3. <sup>BA</sup>Coding for Economics 1
</a>

<div class="description" style="display: none;">

<h6>Course Objective</h6>
<ul>
  <li>Learn basic Python programming, data analysis, and object-oriented programming.</li>
  <li>Learn the basic concepts of deep hedging.</li>
  <li>Virtual trading of financial products using the open trading API.</li>
</ul>

<h6>Datacamp Accomplishments
  <a href="https://www.datacamp.com/" title="DataCamp" target="_blank">
    <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" viewBox="0 0 24 24">
      <path fill="currentColor" d="M12.946 18.151v-5.239L21.209 8.2L19.2 7.048l-6.254 3.567V5.36c0-.356-.192-.689-.5-.866L4.922.177a1.43 1.43 0 0 0-1.455.044a1.44 1.44 0 0 0-.676 1.224v14.777A1.44 1.44 0 0 0 4.92 17.49l6.032-3.44v4.683a1 1 0 0 0 .504.867l7.73 4.4l2.01-1.152zM10.953 5.938v5.814L4.785 15.27V2.4l6.168 3.539z"/>
    </svg>
  </a>
</h6>
<ol>
  <li>Introduction to Python</li>
  <li>Intermediate Python</li>
  <li>Introduction to Functions</li>
  <li>Python Toolbox</li>
</ol>

<h6>References</h6>
<ol>
  <li>
    KIS Developers, <em>Korea Investment</em>
    <a href="https://github.com/koreainvestment/open-trading-api" target="_blank">
      <i class="fab fa-github" title="GitHub"></i>
    </a>
  </li>
  <li>
    Postman
    <a href="https://www.postman.com" target="_blank">
      <i class="fa fa-house" title="Website"></i>
    </a>
  </li>
</ol>

</div>

<!-- ------------------------------------ -->

<a class="btn" onclick="toggleContent(this)">
    <i class="toggle-icon" data-feather="chevron-right" style="vertical-align: middle; width: 1.5em; height:1.5em;"></i>
    4. <sup>BA</sup>AI Assisted Financial Engineering
</a>

<div class="description" style="display: none;">

<h6>Course Objective</h6>
<ul>
  <li>Learn the concepts of deep learning and deep hedging.</li>
  <li>Implement deep hedging on financial products using the PFHedge library.</li>
  <li>Virtual trading of financial products using the open trading API.</li>
</ul>

<h6>References</h6>
<ol>
  <li>
    PFHedge: Deep Hedging in PyTorch
    <a href="https://github.com/pfnet-research/pfhedge" target="_blank">
      <i class="fab fa-github" title="GitHub"></i>
    </a>
  </li>
  <li>
    KIS Developers, <em>Korea Investment</em>
    <a href="https://github.com/koreainvestment/open-trading-api" target="_blank">
      <i class="fab fa-github" title="GitHub"></i>
    </a>
  </li>
  <li>
    Postman
    <a href="https://www.postman.com" target="_blank">
      <i class="fa fa-house" title="Website"></i>
    </a>
  </li>
</ol>

</div>