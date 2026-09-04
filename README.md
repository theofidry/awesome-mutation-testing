# Awesome Mutation Testing [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

Mutation testing evaluates a test suite by introducing small changes—called mutants—into a program and checking whether the tests detect them.

This repository catalogues mutation-testing tools, publications, talks, tutorials, and other resources. Projects are included for their practical, educational, research or historical value. Inclusion does not imply that a project is actively maintained.

[Discord Invite](https://discord.com/invite/k5JBWU2)


## Contents

- [Tools](#tools)
- [Archived tools](archived.md#archived-tools)
- [Visualisation tools](#visualisation-tools)
- [Publications](#publications)
- [Blogs/Posts](#blogsposts)
- [Videos](#videos)
- [Conference presentations](#conference-presentations)
- [Conferences](#conferences)
- [Examples and practical resources](#examples-and-practical-resources)
- [Tutorials](#tutorials)

## Tools

* Alloy
  * [MuAlloy](https://github.com/kaiyuanw/MuAlloy)
    * [MuAlloy papers](https://github.com/kaiyuanw/MuAlloy#publications)
* C/C++
  * [llvm-mutate](https://eschulte.github.io/llvm-mutate/) - An LLVM-based mutation tool for C and C++.
  * [Frama-C Mutation](https://github.com/gpetiot/Frama-C-Mutation/) - A Frama-C plug-in for generating mutant C programs.
  * [Mull](https://github.com/mull-project/mull) - An LLVM-based mutation-testing and fault-injection tool for C and C++.
  * [Mutate++](https://github.com/nlohmann/mutate_cpp)
  * [MuCPP](https://neptuno.uca.es/redmine/projects/mucpp-mutation-tool/wiki) - A mutation system for applying class-level operators to C++ programs.
    * [Assessment of Class Mutation Operators for C++ with the MuCPP Mutation System](https://pdfs.semanticscholar.org/05d5/2ba68ed4ba8505cc92e4f27ad68c1b944842.pdf)
  * [AccMut](https://github.com/wangbo15/accmut) - An LLVM IR-based framework for accelerating mutation testing.
    * [Faster mutation analysis via equivalence modulo states](http://sei.pku.edu.cn/%7Exiongyf04/papers/ISSTA17.pdf)
  * [MUSIC](https://github.com/swtv-kaist/MUSIC) - A configurable and extensible mutation-analysis tool for C programs.
    * [MUSIC: Mutation Analysis Tool with High Configurability and Extensibility](http://swtv.kaist.ac.kr/publications/music-mutation18.pdf)
  * [Dextool Mutate](https://github.com/joakim-brannstrom/dextool/tree/master/plugin/mutate) - A mutation-testing plug-in in the LLVM- and Clang-based Dextool suite.
  * [SRCIROR](https://github.com/TestingResearchIllinois/srciror) - A mutation tool for C source code and LLVM IR.
    * [SRCIROR: A Toolset for Mutation Testing of C Source Code and LLVM Intermediate Representation](http://mir.cs.illinois.edu/farah/publications/ase18_srciror.pdf)
  * [MART](https://github.com/thierry-tct/mart) - A configurable mutation-testing framework based on LLVM.
* C#
  * [Stryker.NET](https://github.com/stryker-mutator/stryker-net) - A mutation-testing tool for .NET Framework and .NET.
  * [Fettle](https://github.com/ComparetheMarket/fettle) - An experimental mutation-testing tool for C#.
  * [Testura.Mutation](https://github.com/Testura/Testura.Mutation)
  * [Faultify](https://github.com/Faultify/Faultify) - A bytecode-level mutation-testing tool for .NET.
* Clojure
  * [mutant](https://github.com/jstepien/mutant)
* Crystal
  * [crytic](https://github.com/hanneskaeufler/crytic)
* Elixir
  * [Mutation](https://github.com/JordiPolo/mutation)
* Erlang
  * [Muterl](https://github.com/parsifal-47/muterl)
* Go
  * [go-mutesting](https://github.com/jonbaldie/go-mutesting)
  * [Ooze](https://github.com/gtramontina/ooze)
  * [Gremlins](https://github.com/go-gremlins/gremlins)
* Haskell
  * [MuCheck](https://hackage.haskell.org/package/MuCheck)
  * [FitSpec](https://github.com/rudymatela/fitspec) - A tool that uses mutations to refine properties for testing Haskell programs.
* Java/JVM
  * [PIT](https://github.com/hcoles/pitest) - A bytecode-level mutation-testing system for the JVM.
    * [PIT: A Practical Mutation Testing Tool for Java (Demo)](https://dl.acm.org/citation.cfm?id=2948707)
    * [An Experimental Evaluation of PIT’s Mutation Operators](http://www.diva-portal.org/smash/get/diva2:1161760/FULLTEXT01.pdf)
    * [Introduction to Mutation Testing](https://blog.frankel.ch/introduction-to-mutation-testing/)
    * [Faster Mutation Testing (in Java)](https://blog.frankel.ch/faster-mutation-testing/)
  * [LittleDarwin](https://github.com/aliparsai/LittleDarwin) - A Java mutation-testing framework implemented in Python.
    * [LittleDarwin: a Feature-Rich and Extensible Mutation Testing Framework for Large and Complex Java Systems](https://www.parsai.net/files/research/LittleDarwin%20a%20Feature-Rich%20and%20Extensible%20Mutation%20Testing%20Framework%20for%20Large%20and%20Complex%20Java%20Systems%20(pre-print).pdf)
  * [metamutator](https://github.com/SpoonLabs/metamutator) - A Java mutation engine based on mutant schemata and metaprogramming.
  * [Major](http://mutation-testing.org) - A compiler-integrated mutation-testing system for Java.
    * [Publications related to the Major mutation framework](http://mutation-testing.org/publ/)
* JavaScript
  * [StrykerJS](https://github.com/stryker-mutator/stryker) - A mutation-testing framework for JavaScript and TypeScript.
  * [testtruth](https://github.com/T4LEL/testtruth) - A tool that compares mutation results before and after a Git diff to detect weakened JavaScript and TypeScript tests.
* Kotlin
  * [Mutant Kraken](https://github.com/JosueMolinaMorales/mutant-kraken)
  * [mutflow](https://github.com/anschnapp/mutflow) - A Kotlin library that performs mutation testing within the test suite after a single compilation.
* PHP
  * [Infection](https://github.com/infection)
  * [Pest PHP](https://pestphp.com/docs/mutation-testing) - Mutation testing integrated into the Pest PHP testing framework.
* Python
  * [Cosmic Ray](https://github.com/sixty-north/cosmic-ray)
  * [mutmut](https://github.com/boxed/mutmut)
* R
  * [mutator](https://github.com/PRL-PRG/mutator)
  * [muttest](https://github.com/jakubsob/muttest) - A mutation-testing tool for assessing test assertions in R.
* Ruby
  * [Mutant](https://github.com/mbj/mutant)
    * [Kill all the mutants - a deep dive into mutation testing and how the Mutant gem works](https://troessner.svbtle.com/kill-all-the-mutants-a-deep-dive-into-mutation-testing-and-how-the-mutant-gem-works)
  * [mutest](https://github.com/backus/mutest) - A fork of Mutant with additional mutations and inline disable comments.
* Rust
  * [cargo-mutants](https://github.com/sourcefrog/cargo-mutants) - A Cargo-based mutation-testing tool for Rust.
  * [mutagen](https://github.com/llogiq/mutagen) - A mutation-testing plug-in for Rust.
* Scala
  * [Scalamu](https://github.com/sugakandrey/scalamu)
  * [Stryker4s](https://stryker-mutator.io/stryker4s/)
* Smalltalk
  * [MuTalk](https://github.com/pavel-krivanek/mutalk) - A mutation-testing tool for Pharo Smalltalk.
* Simulink
  * [MUT4SLX](https://github.com/haliliceylan/MUT4SLX) - A model-based mutation-testing framework for Simulink and Stateflow models in MATLAB.
    * [Reproduction Package](https://github.com/haliliceylan/MUT4SLX/blob/main/Reproduction-Package-ASE-2023.md)
    * [MUT4SLX: Fast mutant generation for Simulink](https://ieeexplore.ieee.org/abstract/document/10298490)
    * [MUT4SLX: Extensions for Mutation Testing of Stateflow Models](https://ieeexplore.ieee.org/abstract/document/10621727)
* Solidity / Smart Contracts
  * [Gambit](https://github.com/Certora/gambit) - A mutation generator for improving specifications and test suites for Solidity contracts.
  * [vertigo-rs](https://github.com/RareSkills/vertigo-rs) - A mutation-testing tool for Ethereum smart contracts using Foundry.
  * [vertigo](https://github.com/JoranHonig/vertigo)
* Swift
  * [Muter](https://github.com/muter-mutation-testing/muter)
* OCaml
  * [Mutaml](https://github.com/jmid/mutaml)
* Lean
  * [Mutate.lean](https://github.com/jubnzv/Mutate.lean)
* Other
  * [Universal Mutator](https://github.com/agroce/universalmutator) - A regular-expression-based mutation tool for source code in multiple languages.
  * [boggart](https://github.com/squaresLab/boggart) - A lightweight, extensible, language-independent mutation-testing framework.
  * [Mutahunter](https://github.com/codeintegrity-ai/mutahunter) - An open-source, language-agnostic mutation-testing tool.
  * [Bough](https://github.com/CodeEnPlace/bough) - A polyglot incremental mutation-testing tool.

## Visualisation tools

* [VisMAn](https://github.com/sqrlab/VisMAn)


## Publications

Publication titles retain their original spelling. Entries link to DOI or publisher pages or to locally archived copies when redistribution is permitted.

### Papers

> **Local PDF** links to a file stored in this repository. **External** links to another website.

* **External:** [Mario Rosano Barroso (2026) _Aplicación de modelos de aprendizaje profundo al Predictive Mutation Testing_](http://hdl.handle.net/10498/39116)
* **Local PDF:** [Hervé Robert, Shubho Sengupta (2025) _Mutation-Guided LLM-based Test Generation at Meta_](documents/Mutation-Guided%20LLM-based%20Test%20Generation%20at%20Meta%20(2025).pdf)
* **Local PDF:** [Jeongju Sohn, Ezekiel Soremekun, Michail Papadakis (2025) _Latent Mutants: A large-scale study on the Interplay between mutation testing and software evolution_](documents/Latent%20Mutants%20A%20large%20scale%20study%20on%20the%20Interplay%20between%20mutation%20testing%20and%20software%20evolution%20(2025).pdf)
* **External:** [Deniz Eren, Gabriele Taentzer, Sascha Lehmann, Freya Dorn, Daniel Neufeld, Christoph Bockisch (2025) _Advanced Mutation Testing of Java Bytecode Using Model Transformation_](https://doi.org/10.18420/se2025-11)
* **External:** [Bekzat Skakov (2025) _LLM-DRIVEN MUTATION TESTING IN MICROARCHITECTURE VERIFICATION_](https://nur.nu.edu.kz/handle/123456789/8509)
* **Local PDF:** [Marcela G. dos Santos, Sylvain Hallé, Fábio Petrillo (2025) _Mutation Testing for Industrial Robotic Systems_](documents/Mutation%20Testing%20for%20Industrial%20Robotic%20Systems%20(2025).pdf) — [DOI](https://doi.org/10.4204/eptcs.436.5)
* **External:** [Pablo Gómez‐Abajo, Esther Guerra, Juan de Lara (2025) _Wodel-Test: A model-based framework for engineering language-specific mutation testing tools_](https://doi.org/10.1016/j.softx.2025.102195)
* **Local PDF:** [Dolores Miao, Ignacio Laguna, Giorgis Georgakoudis, Konstantinos Parasyris, Cindy Rubio-González (2024) _An automated OpenMP mutation testing framework for performance optimization_](documents/An%20automated%20OpenMP%20mutation%20testing%20framework%20for%20performance%20optimization%20(2024).pdf) — [DOI](https://doi.org/10.1016/j.parco.2024.103097)
* **Local PDF:** [Enzo Nicourt, Benjamin Kushigian, Chandrakana Nandi, Yliès Falcone (2024) _Using Mutation Testing To Improve and Minimize Test Suites for Smart Contracts_](documents/Using%20Mutation%20Testing%20To%20Improve%20and%20Minimize%20Test%20Suites%20for%20Smart%20Contracts.pdf)
* **External:** [Kadiatou Diallo, Zizhao Chen, W. E. Wong, Shou-Yu Lee (2024) _An Analysis and Comparison of Mutation Testing Tools for Python_](https://doi.org/10.1109/dsa63982.2024.00030)
* **Local PDF:** [Zhifei Chen, Yang Hao, Qichao Liu, Yuyong Liu, Mingyang Zhu, Liang Xiao (2024) _Deep Learning for Hyperspectral Image Classification: A Critical Evaluation via Mutation Testing_](documents/Deep%20Learning%20for%20Hyperspectral%20Image%20Classification%20A%20Critical%20Evaluation%20via%20Mutation%20Testing%20(2024).pdf) — [DOI](https://doi.org/10.3390/rs16244695)
* **External:** [Serhat Uzunbayir, Kaan Kurtel (2024) _Leveraging Genetic Algorithms for Efficient Search-Based Higher Order Mutation Testing_](https://doi.org/10.31577/cai_2024_3_709)
* **External:** [Erasmo Junkes (2024) _Mutant Codebraker: A game to assist in teaching mutation testing_](http://repositorio.utfpr.edu.br/jspui/handle/1/36188)
* **External:** [Yichun Wang, Zhiyi Zhang, Yongming Yao, Zhiqiu Huang (2023) _A Fine-Grained Evaluation of Mutation Operators for Deep Learning Systems: A Selective Mutation Approach_](https://doi.org/10.1145/3609437.3609453)
* **External:** [Sergen Aşik, Uğur Yayan (2023) _Generating Python Mutants From Bug Fixes Using Neural Machine Translation_](https://doi.org/10.1109/access.2023.3302695)
* **External:** [Miloš Ojdanić, Ahmed Khanfir, Aayush Garg, R. Degiovanni, Mike Papadakis, Yves Le Traon (2023) _On Comparing Mutation Testing Tools through Learning-based Mutant Selection_](https://doi.org/10.1109/ast58925.2023.00008)
* **External:** [Ezio Bartocci, Leonardo Mariani, Dejan Ničković, Drishti Yadav (2023) _Property-Based Mutation Testing_](https://doi.org/10.1109/icst57152.2023.00029)
* **Local PDF:** [Pedro Delgado-Pérez, Ana B. Sánchez, Sergio Segura, Inmaculada Medina-Bulo (2022) _Mutation testing in the wild: findings from GitHub_](documents/Mutation%20testing%20in%20the%20wild:%20findings%20from%20GitHub%20(2022).pdf) — [DOI](https://doi.org/10.1007/s10664-022-10177-8)
* **Local PDF:** [Giovani Guizzo, Federica Sarro, Jens Krinke, Silvia Regina Vergilio (2022) _Sentinel: A Hyper-Heuristic for the Generation of Mutant Reduction Strategies_](documents/Sentinel:%20A%20Hyper-Heuristic%20for%20the%20Generation%20of%20Mutant%20Reduction%20Strategies%20(2021).pdf) — [DOI](https://doi.org/10.1109/TSE.2020.3002496)
* **Local PDF:** [Deepti Mishra, Biswaranjan Acharya, Dharashree Rath, Vassilis C. Gerogiannis, Andreas Kanavos (2022) _A Novel Real Coded Genetic Algorithm for Software Mutation Testing_](documents/A%20Novel%20Real%20Coded%20Genetic%20Algorithm%20for%20Software%20Mutation%20Testing%20(2022).pdf) — [DOI](https://doi.org/10.3390/sym14081525)
* **External:** [Nishtha Jatana, Bharti Suri (2022) _Application of Nature Inspired Algorithms to Test Data Generation/Selection/Minimization using Mutation Testing_](https://doi.org/10.2174/9789815036091122010016)
* **External:** [Miloš Ojdanić (2022) _Change-aware mutation testing for evolving systems_](https://doi.org/10.1145/3540250.3558911)
* **External:** [Matheus Yudi Fujiike Ferreira (2022) _Generation test data for weak mutation testing using search-based techniques_](http://repositorio.utfpr.edu.br/jspui/handle/1/33093)
* **External:** [Sara Tarek ElSayed Abbas, Rohayanti Hassan, Shahliza Abd Halim, Shahreen Kasim, Rohaizan Ramlan (2022) _Investigation on Java Mutation Testing Tools_](https://doi.org/10.30630/joiv.6.2-2.1090)
* **External:** [Li-Chao Feng, Xing-Ya Wang, Shi-Yu Zhang, Rui-Zhi Gao, Zhi-Hong Zhao (2022) _Mutation Operator Reduction for Cost-effective Deep Learning Software Testing via Decision Boundary Change Measurement_](https://doi.org/10.53106/160792642022052303018)
* **Local PDF:** [Miloš Ojdanić, Ezekiel Soremekun, Renzo Degiovanni, Mike Papadakis, Yves Le Traon (2022) _Mutation Testing in Evolving Systems: Studying the Relevance of Mutants to Code Evolution_](documents/Mutation%20Testing%20in%20Evolving%20Systems%20(2022).pdf) — [DOI](https://doi.org/10.1145/3530786)
* **External:** [Daniel Fortunato, José Campos, Rui Abreu (2022) _Mutation Testing of Quantum Programs: A Case Study With Qiskit_](https://doi.org/10.1109/tqe.2022.3195061)
* **External:** [Xinyi Wang, Tongxuan Yu, Paolo Arcaini, Tao Yue, Shaukat Ali (2022) _Mutation-based test generation for quantum programs with multi-objective search_](https://doi.org/10.1145/3512290.3528869)
* **External:** [Daniel Fortunato, José Campos, Rui Abreu (2022) _QMutPy: a mutation testing tool for Quantum algorithms and applications in Qiskit_](https://doi.org/10.1145/3533767.3543296)
* **External:** [Morena Barboni, Francesco Casoni, Andrea Morichetta, Andrea Polini (2022) _ReSuMo: Regression Mutation Testing for Solidity Smart Contracts_](https://doi.org/10.1007/978-3-031-14179-9_5)
* **External:** [Van-Nho Do, Quang-Vu Nguyen, Thanh-Binh Nguyen (2022) _Toward Improving the Quality of Mutation Operator and Test Case Effectiveness in Higher-Order Mutation Testing_](https://doi.org/10.1142/s2196888822500282)
* **Local PDF:** [Goran Petrović, Marko Ivanković, Gordon Fraser, René Just (2021) _Practical Mutation Testing at Scale: A view from Google_](documents/Practical%20Mutation%20Testing%20at%20Scale%20A%20view%20from%20Google%20(2021).pdf) — [DOI](https://doi.org/10.1109/TSE.2021.3107634)
* **Local PDF:** [Goran Petrović, Marko Ivanković, Gordon Fraser, René Just (2021) _Does mutation testing improve testing practices?_](documents/Does%20mutation%20testing%20improve%20testing%20practices%3F%20(2021).pdf) — [DOI](https://doi.org/10.1109/ICSE43902.2021.00087)
* **External:** [Zhenpeng Liu, Xianwei Yang, Yi Liu, Yonggang Zhao, Xiaofei Li (2021) _ImReMuDF: Redundant Mutants Identification Method Based on Definition and Reference of Variables_](https://doi.org/10.1155/2021/7543896)
* **External:** [Jinlei Sun, Song Huang, Changyou Zheng, Tingyong Wang, Cheng Zong, Zhanwei Hui (2021) _Mutation testing for integer overflow in ethereum smart contracts_](https://doi.org/10.26599/tst.2020.9010036)
* **External:** [Galina Cherneva, Pavlо Khalimov (2021) _MUTATION TESTING OF ACCESS CONTROL POLICIES_](https://doi.org/10.20998/2522-9052.2021.1.17)
* **External:** [Changqing Wei, Xiangjuan Yao, Dunwei Gong, Huai Liu (2021) _Spectral clustering based mutant reduction for mutation testing_](https://doi.org/10.1016/j.infsof.2020.106502)
* **Local PDF:** [Y. Ivanova, A. Khritankov (2020) _RegularMutator: A Mutation Testing Tool for Solidity Smart Contracts_](documents/RegularMutator:%20A%20Mutation%20Testing%20Tool%20for%20Solidity%20Smart%20Contracts%20(2020).pdf) — [DOI](https://doi.org/10.1016/j.procs.2020.11.009)
* **Local PDF:** [Pedro Delgado-Pérez, Ana Belén Sánchez, Sergio Segura, Inmaculada Medina-Bulo (2020) _Performance mutation testing_](documents/Performance%20Mutation%20Testing%20(2010).pdf) — [DOI](https://doi.org/10.1002/stvr.1728)
* **External:** [Beatriz Souza, Rohit Gheyi (2020) _A Lightweight Technique to Identify Equivalent Mutants_](https://doi.org/10.5753/cbsoft_estendido.2020.14630)
* **Local PDF:** [Alessandro Viola Pizzoleto, Fabiano Cutigi Ferrari, Jeff Offutt, Leo Fernandes, Márcio Ribeiro (2019) _A Systematic Literature Review of Techniques and Metrics to Reduce the Cost of Mutation Testing_](documents/A%20Systematic%20Literature%20Review%20of%20Techniques%20and%20Metrics%20to%20Reduce%20the%20Cost%20of%20Mutation%20Testing%20(2019).pdf) — [DOI](https://doi.org/10.1016/j.jss.2019.07.100)
* **Local PDF:** [August Shi, Jonathan Bell, Darko Marinov (2019) _Mitigating the Effects of Flaky Tests on Mutation Testing_](documents/Mitigating%20the%20Effects%20of%20Flaky%20Tests%20on%20Mutation%20Testing%20(2019).pdf) — [DOI](https://doi.org/10.1145/3293882.3330568)
* **Local PDF:** [Esther Guerra, Jesús Sánchez Cuadrado, Juan de Lara (2019) _Towards effective mutation testing for ATL_](documents/Towards%20effective%20mutation%20testing%20for%20ATL%20(2019).pdf)
* **Local PDF:** [Mike Papadakis, Marinos Kintis, Jie Zhang, Yue Jia, Yves Le Traon, Mark Harman (2019) _Mutation Testing Advances: An Analysis and Survey_](documents/Mutation%20Testing%20Advances:%20An%20Analysis%20and%20Survey%20(2017).pdf) — [DOI](https://doi.org/10.1016/bs.adcom.2018.03.015)
* **External:** [Jackson Antonio do Prado Lima, Silvia Regina Vergilio (2019) _A systematic mapping study on higher order mutation testing_](https://doi.org/10.1016/j.jss.2019.04.031)
* **External:** [Serhat Uzunbayir, Kaan Kurtel (2019) _An Analysis on Mutation Testing Tools For C# Programming Language_](https://doi.org/10.1109/ubmk.2019.8907222)
* **External:** [Muhammad Bilal Bashir, Aamer Nadeem (2019) _An Evolutionary Mutation Testing System for Java Programs: eMuJava_](https://doi.org/10.1007/978-3-030-22868-2_58)
* **External:** [Qiang Hu, Lei Ma, Xiaofei Xie, Bing Yu, Yang Liu, Jianjun Zhao (2019) _DeepMutation++: A Mutation Testing Framework for Deep Learning Systems_](https://doi.org/10.1109/ase.2019.00126)
* **External:** [Patrick Chapman, Dianxiang Xu, Lin Deng, Yin Xiong (2019) _Deviant: A Mutation Testing Tool for Solidity Smart Contracts_](https://doi.org/10.1109/blockchain.2019.00050)
* **External:** [Alex Alberto (2019) _Formal mutation testing in Circus process algebra_](https://doi.org/10.11606/t.55.2019.tde-04012019-112931)
* **Local PDF:** [Yoo-Min Choi, Dong-Jin Lim (2019) _Model-Based Test Suite Generation Using Mutation Analysis for Fault Localization_](documents/Model-Based%20Test%20Suite%20Generation%20Using%20Mutation%20Analysis%20for%20Fault%20Localization%20(2019).pdf) — [DOI](https://doi.org/10.3390/app9173492)
* **External:** [Andreas Fellner, Willibald Krenn, Rupert Schlick, Thorsten Tarrach, Georg Weissenbacher (2019) _Model-based, Mutation-driven Test-case Generation Via Heuristic-guided Branching Search_](https://doi.org/10.1145/3289256)
* **External:** [Tomasz Lewowski, Lech Madeyski (2019) _Mutants as Patches: Towards a formal approach to Mutation Testing_](https://doi.org/10.2478/fcds-2019-0019)
* **External:** [Nishtha Jatana, Bharti Suri (2019) _Particle Swarm and Genetic Algorithm applied to mutation testing for test data generation: A comparative evaluation_](https://doi.org/10.1016/j.jksuci.2019.05.004)
* **External:** [Thomas Laurent, Anthony Ventresque (2019) _PIT-HOM: an Extension of Pitest for Higher Order Mutation Analysis_](https://doi.org/10.1109/icstw.2019.00036)
* **External:** [Muhammad Rashid Naeem, Tao Lin, Hamad Naeem, Farhan Ullah, Saqib Saeed (2019) _Scalable Mutation Testing Using Predictive Analysis of Deep Learning Model_](https://doi.org/10.1109/access.2019.2950171)
* **Local PDF:** [Lin Deng, Jeff Offutt (2018) _Reducing the Cost of Android Mutation Testing_](documents/Reducing%20the%20Cost%20of%20Android%20Mutation%20Testing%20(2018).pdf)
* **Local PDF:** [Goran Petrović, Marko Ivanković (2018) _State of Mutation Testing at Google_](documents/State%20of%20Mutation%20Testing%20at%20Google%20(2018).pdf) — [DOI](https://doi.org/10.1145/3183519.3183521)
* **Local PDF:** [Goran Petrović, Marko Ivanković, Bob Kurtz, Paul Ammann, René Just (2018) _An Industrial Application of Mutation Testing: Lessons, Challenges, and Research Directions_](documents/An%20Industrial%20Application%20of%20Mutation%20Testing%20Lessons,%20Challenges,%20and%20Research%20Directions%20(2018).pdf) — [DOI](https://doi.org/10.1109/ICSTW.2018.00027)
* **Local PDF:** [Sten Vercammen, Mohammad Ghafari, Serge Demeyer, Markus Borg (2018) _Goal-Oriented Mutation Testing with Focal Methods_](documents/Goal-Oriented%20Mutation%20Testing%20with%20Focal%20Methods%20(2018).pdf) — [DOI](https://doi.org/10.1145/3278186.3278190)
* **Local PDF:** [Qianqian Zhu, Annibale Panichella, Andy Zaidman (2018) _A Systematic Literature Review of How Mutation Testing Supports Quality Assurance Processes_](documents/A%20Systematic%20Literature%20Review%20of%20How%20Mutation%20Testing%20Supports%20Quality%20Assurance%20Processes%20(2018).pdf) — [DOI](https://doi.org/10.1002/stvr.1675)
* **Local PDF:** [Lingchao Chen, Lingming Zhang (2018) _Speeding up Mutation Testing via Regression Test Selection: An Extensive Study_](documents/Speeding%20up%20Mutation%20Testing%20via%20Regression%20Test%20Selection:%20An%20Extensive%20Study%20(2018).pdf)
* **External:** [Qianqian Zhu, Annibale Panichella, Andy Zaidman (2018) _An Investigation of Compression Techniques to Speed up Mutation Testing_](https://doi.org/10.1109/icst.2018.00035)
* **External:** [Lei Ma, Fuyuan Zhang, Jiyuan Sun, Minhui Xue, Bo Li, Felix Juefei-Xu, Chao Xie, Li Li, Yang Liu, Jianjun Zhao, Yadong Wang (2018) _DeepMutation: Mutation Testing of Deep Learning Systems_](https://doi.org/10.1109/issre.2018.00021)
* **External:** [S. Rani, Bharti Suri (2018) _Equivalent Mutant Problem and its Problem-Solving Techniques: A Retrospective View_](https://doi.org/10.1109/confluence.2018.8442785)
* **External:** [Farah Hariri (2018) _Exploring design decisions for mutation testing_](http://hdl.handle.net/2142/101008)
* **External:** [Paolo Arcaini, Angelo Gargantini, Elvinia Riccobene (2018) _Fault‐based test generation for regular expressions by mutation_](https://doi.org/10.1002/stvr.1664)
* **External:** [Diego Rodríguez-Baquero, Mario Linares‐Vásquez (2018) _Mutode: generic JavaScript and Node.js mutation testing tool_](https://doi.org/10.1145/3213846.3229504)
* **External:** [Rodolfo Adamshuk Silva (2018) _Search based software testing for the generation of synchronization sequences for mutation testing of concurrent programs_](https://doi.org/10.11606/t.55.2018.tde-10102018-141934)
* **External:** [Jorge López, Natalia Kushik, Nina Yevtushenko (2018) _Source code optimization using equivalent mutants_](https://doi.org/10.1016/j.infsof.2018.06.013)
* **Local PDF:** [Pablo C. Cañizares, Alberto Núñez, Juan de Lara (2017) _OUTRIDER: Optimizing the mUtation Testing pRocess In Distributed EnviRonments_](documents/OUTRIDER:%20Optimizing%20the%20mUtation%20Testing%20pRocess%20In%20Distributed%20EnviRonments%20(2017).pdf)
* **Local PDF:** [Qianqian Zhu, Annibale Panichella, Andy Zaidman (2017) _Speeding-Up Mutation Testing via Data Compression and State Infection_](documents/Speeding-Up%20Mutation%20Testing%20via%20Data%20Compression%20and%20State%20Infection%20(2017).pdf)
* **External:** [Allison Sullivan, Kaiyuan Wang, Razieh Nokhbeh Zaeem, S. Khurshid (2017) _Automated Test Generation and Mutation Testing for Alloy_](https://doi.org/10.1109/icst.2017.31)
* **External:** [Leontiuc, Ioana (2017) _Continuous Mutation Testing in Modern Software Development_](http://resolver.tudelft.nl/uuid:ce135a31-972f-4f96-bfbb-28b813045e1b)
* **Local PDF:** [Anna Derezińska, Marcin Rudnik (2017) _Evaluation of Mutant Sampling Criteria in Object-Oriented Mutation Testing_](documents/Evaluation%20of%20Mutant%20Sampling%20Criteria%20in%20Object-Oriented%20Mutation%20Testing%20(2017).pdf) — [DOI](https://doi.org/10.15439/2017f375)
* **External:** [Mayank Singh, Viranjay M. Srivastava (2017) _Extended firm mutation testing: A cost reduction technique for mutation testing_](https://doi.org/10.1109/iciip.2017.8313788)
* **External:** [Ahmed S. Ghiduk, M. Girgis, Marwa H. Shehata (2017) _Higher order mutation testing: A Systematic Literature Review_](https://doi.org/10.1016/j.cosrev.2017.06.001)
* **External:** [Marinos Kintis, Mike Papadakis, Andreas Papadopoulos, Evangelos Valvis, Nicos Malevris, Yves Le Traon (2017) _How effective are mutation testing tools? An empirical analysis of Java mutation testing tools with manual analysis and real faults_](https://doi.org/10.1007/s10664-017-9582-5)
* **External:** [Fan Wu, Jay Nanavati, Mark Harman, Yue Jia, Jens Krinke (2017) _Memory mutation testing_](https://doi.org/10.1016/j.infsof.2016.03.002)
* **External:** [Dunwei Gong, Gongjie Zhang, Xiangjuan Yao, Fanlin Meng (2017) _Mutant reduction based on dominance relation for weak mutation testing_](https://doi.org/10.1016/j.infsof.2016.05.001)
* **External:** [Phra Pridsadi Tadeesom, Taratip Suwannasart (2017) _Mutation Operators in BPMN Model_](https://doi.org/10.1145/3178264.3178286)
* **External:** [Le Thi My Hanh, Nguyen Thanh Binh, Khuat Thanh Tung (2017) _Parallel Mutant Execution Techniques in Mutation Testing Process for Simulink Models_](https://doi.org/10.26636/jtit.2017.113617)
* **External:** [Nishtha Jatana, Bharti Suri, Rani Shweta (2017) _Systematic Literature Review on Search Based Mutation Testing_](https://doi.org/10.5277/e-inf170103)
* **Local PDF:** [Joanna Strug, Barbara Strug (2017) _Using Classification for Cost Reduction of Applying Mutation Testing_](documents/Using%20Classification%20for%20Cost%20Reduction%20of%20Applying%20Mutation%20Testing%20(2017).pdf) — [DOI](https://doi.org/10.15439/2017f215)
* **Local PDF:** [Jie Zhang, Ziyi Wang, Lingming Zhang, Dan Hao, Lei Zang, Shiyang Cheng, Lu Zhang (2016) _Predictive Mutation Testing_](documents/Predictive%20Mutation%20Testing%20(2016).pdf) — [DOI](https://doi.org/10.1145/2931037.2931038)
* **Local PDF:** [Marinos Kintis (2016) _Effective Methods to Tackle the Equivalent Mutant Problem when Testing Software with Mutation_](documents/Effective%20Methods%20to%20Tackle%20the%20Equivalent%20Mutant%20Problem%20when%20Testing%20Software%20with%20Mutation%20(2016).pdf)
* **External:** [Zhu, Qianqian, Panichella, Annibale, Zaidman, Andy (2016) _A systematic literature review of how mutation testing supports test activities_](https://doi.org/10.7287/peerj.preprints.2483v1)
* **External:** [Marinos Kintis, Mike Papadakis, Andreas Papadopoulos, Evangelos Valvis, Nicos Malevris (2016) _Analysing and Comparing the Effectiveness of Mutation Testing Tools: A Manual Study_](https://doi.org/10.1109/scam.2016.28)
* **Local PDF:** [Joanna Strug (2016) _Applying Mutation Testing for Assessing Test Suites Quality at Model Level_](documents/Applying%20Mutation%20Testing%20for%20Assessing%20Test%20Suites%20Quality%20at%20Model%20Level%20(2016).pdf) — [DOI](https://doi.org/10.15439/2016f82)
* **External:** [Thomas Laurent, Anthony Ventresque, Mike Papadakis, Christopher Henard, Y. Traon (2016) _Assessing and Improving the Mutation Testing Practice of PIT_](https://doi.org/10.1109/icst.2017.47)
* **External:** [Joanna Strug (2016) _Mutation Testing Approach to Negative Testing_](https://doi.org/10.1155/2016/6589140)
* **External:** [Eduard P. Enoiu, Daniel Sundmark, Adnan Čaušević, Robert Feldt, Paul Pettersson (2016) _Mutation-Based Test Generation for PLC Embedded Software Using Model Checking_](https://doi.org/10.1007/978-3-319-47443-4_10)
* **External:** [Henry Coles, Thomas Laurent, Christopher Henard, Mike Papadakis, Anthony Ventresque (2016) _PIT: a practical mutation testing tool for Java (demo)_](https://doi.org/10.1145/2931037.2948707)
* **External:** [Mehrnoosh Ebrahimipour (2016) _Undefined Behaviour in Mutation Testing_](http://summit.sfu.ca/item/16790)
* **External:** [Nan Li, Michael West, Anthony Escalona, Vinicius H. S. Durelli (2015) _Mutation testing in practice using Ruby_](https://doi.org/10.1109/icstw.2015.7107453)
* **External:** [Yiling Lou, Dan Hao, Lu Zhang (2015) _Mutation-based test-case prioritization in software evolution_](https://doi.org/10.1109/issre.2015.7381798)
* **External:** [Mike Papadakis, Yue Jia, M. Harman, Yves Le Traon (2015) _Trivial Compiler Equivalence: A Large Scale Empirical Study of a Simple, Fast and Effective Equivalent Mutant Detection Technique_](https://doi.org/10.5555/2818754.2818867)
* **Local PDF:** [René Just, Darioush Jalali, Laura Inozemtseva, Michael D. Ernst, Reid Holmes, Gordon Fraser (2014) _Are Mutants a Valid Substitute for Real Faults in Software Testing?_](documents/Are%20Mutants%20a%20Valid%20Substitute%20for%20Real%20Faults%20in%20Software%20Testing%3F%20(2014).pdf) — [DOI](https://doi.org/10.1145/2635868.2635929)
* **Local PDF:** [Lorena Gutiérrez-Madroñal, J. Domínguez-Jiménez, I. Medina-Bulo (2014) _Mutation Testing: Guideline and Mutation Operator Classification_](documents/Mutation%20Testing%20Guideline%20and%20Mutation%20Operator%20Classification%20(2014).pdf)
* **Local PDF:** [L. Madeyski, W. Orzeszyna, R. Torkar, M. Józala (2014) _Overcoming the Equivalent Mutant Problem: A Systematic Literature Review and a Comparative Experiment of Second Order Mutation_](documents/Overcoming%20the%20Equivalent%20Mutant%20Problem%20A%20Systematic%20Literature%20Review%20and%20a%20Comparative%20Experiment%20of%20Second%20Order%20Mutation%20(2014).pdf)
* **External:** [Srinivas Prasad (2014) _A Novel Approach of Mutation Testing of Object-Oriented Programs_](https://doi.org/10.15866/irecos.v9i11.4542)
* **External:** [LEONARDO DA SILVA SOUSA (2014) _A service-based infrastructure for evolution of mutation testing_](http://repositorio.bc.ufg.br/tede/handle/tede/4647)
* **External:** [Gordon Fraser, Andrea Arcuri (2014) _Achieving scalable mutation-based generation of whole test suites_](https://doi.org/10.1007/s10664-013-9299-z)
* **External:** [Jie Zhang, Muyao Zhu, Dan Hao, Lu Zhang (2014) _An Empirical Study on the Scalability of Selective Mutation Testing_](https://doi.org/10.1109/issre.2014.27)
* **External:** [Mike Papadakis, Y. Traon (2014) _Effective fault localization via mutation analysis: a selective mutation approach_](https://doi.org/10.1145/2554850.2554978)
* **External:** [Marinos Kintis, Mike Papadakis, Nicos Malevris (2014) _Employing second‐order mutation for isolating first‐order equivalent mutants_](https://doi.org/10.1002/stvr.1529)
* **External:** [Mike Papadakis, Marcio Delamaro, Yves Le Traon (2014) _Mitigating the effects of equivalent mutants with mutant classification strategies_](https://doi.org/10.1016/j.scico.2014.05.012)
* **External:** [Pedro Reales, Macario Polo, José Luis Fernández-Alemán, Ambrosio Toval, Mario Piattini (2014) _Mutation Testing_](https://doi.org/10.1109/ms.2014.68)
* **External:** [Francisco Carlos, M Souza, Mike Papadakis, Vinícius H. S. Durelli, Delamaro, Marcio Eduardo (2014) _Test Data Generation Techniques for Mutation Testing: A Systematic Mapping_](https://doi.org/10.13140/rg.2.1.3699.9209)
* **External:** [Lingming Zhang (2014) _Unifying regression testing with mutation testing_](http://hdl.handle.net/2152/25055)
* **Local PDF:** [Lingming Zhang, Darko Marinov, Sarfraz Khurshid (2013) _Faster Mutation Testing Inspired by Test Prioritization and Reduction_](documents/Faster%20Mutation%20Testing%20Inspired%20by%20Test%20Prioritization%20and%20Reduction%20(2013).pdf) — [DOI](https://doi.org/10.1145/2483760.2483782)
* **Local PDF:** [Bouchaib Falah, Bouriat Salwa (2013) _Effectiveness of Mutation Testing Techniques: Reducing Mutation Cost_](documents/Effectiveness%20of%20Mutation%20Testing%20Techniques%20Reducing%20Mutation%20Cost%20(2013).pdf)
* **Local PDF:** [Quang Vu Nguyen, Lech Madeyski (2013) _Problems of Mutation Testing and Higher Order Mutation Testing_](documents/Problems%20of%20Mutation%20Testing%20and%20Higher%20Order%20Mutation%20Testing%20(2013).pdf)
* **Local PDF:** [Lingming Zhang, Milos Gligoric, Darko Marinov, Sarfraz Khurshid (2013) _Operator-Based and Random Mutant Selection: Better Together_](documents/Operator-Based%20and%20Random%20Mutant%20Selection%20Better%20Together%20(2013).pdf)
* **External:** [D. Singh, B. Suri (2013) _Mutation testing tools- an empirical study_](https://doi.org/10.1049/cp.2013.2596)
* **Local PDF:** [Kevin Jalbert, Jeremy S. Bradbury (2012) _Predicting Mutation Scores using Source Code and Test Suite Metrics_](documents/Predicting%20Mutation%20Score%20Using%20Source%20Code%20and%20Test%20Suite%20Metrics%20(2012).pdf)
* **External:** [David Schuler, Andreas Zeller (2012) _Covering and Uncovering Equivalent Mutants_](https://doi.org/10.1002/stvr.1473)
* **External:** [Mike Papadakis, Nicos Malevris (2012) _Mutation based test case generation via a path selection strategy_](https://doi.org/10.1016/j.infsof.2012.02.004)
* **External:** [René Just (2012) _On effective and efficient mutation analysis for unit and integration testing_](https://doi.org/10.18725/oparu-2474)
* **External:** [Pedro Reales Mateo, Macario Polo Usaola (2012) _Parallel mutation testing_](https://doi.org/10.1002/stvr.1471)
* **External:** [Lingming Zhang, Darko Marinov, Lu Zhang, Sarfraz Khurshid (2012) _Regression mutation testing_](https://doi.org/10.1145/2338965.2336793)
* **External:** [Eric Schulte, Zachary P. Fry, Ethan Fast, Westley Weimer, Stephanie Forrest (2012) _Software Mutational Robustness_](https://doi.org/10.48550/arxiv.1204.4224)
* **External:** [Bernhard K. Aichernig, Elisabeth Jöbstl (2012) _Towards Symbolic Model-Based Mutation Testing: Combining Reachability and Refinement Checking_](https://doi.org/10.4204/eptcs.80.7)
* **External:** [Simona Nica, F. Wotawa (2012) _Using Constraints for Equivalent Mutant Detection_](https://doi.org/10.4204/eptcs.86.1)
* **Local PDF:** [David Schuler (2011) _Assessing Test Quality_](documents/Assessing%20Test%20Quality%20(2011).pdf)
* **Local PDF:** [John A. Clark, Haitao Dan, Robert M. Hierons (2011) _Semantic Mutation Testing_](documents/Semantic%20mutation%20testing%20(2011).pdf) — [DOI](https://doi.org/10.1016/j.scico.2011.03.011)
* **External:** [J.J. Domínguez-Jiménez, A. Estero-Botaro, A. García-Domínguez, I. Medina-Bulo (2011) _Evolutionary mutation testing_](https://doi.org/10.1016/j.infsof.2011.03.008)
* **External:** [Sergio Segura, Segura, S, Benavides, D, Antonio Ruiz-Cortés, Ruiz Cortés, Antonio, Segura Rueda, Sergio, Robert M. Hierons, Benavides Cuevas, David Felipe, Hierons, Robert M., David Benavides, Hierons, RM, Ruiz-Cortes, A (2011) _Mutation testing on an object-oriented framework: An experience report_](https://doi.org/10.1016/j.infsof.2011.03.006)
* **External:** [Z. Ivanković, D. Radosav, B. Markoski (2011) _Mutation Testing: Object-Oriented Mutation and Testing Tools_](https://doi.org/10.7251/jit1102105i)
* **External:** [Frédéric Dadeau, Pierre-Cyrille Héam, Rafik Kheddam (2011) _Mutation-Based Test Generation from Security Protocols in HLPSL_](https://doi.org/10.1109/icst.2011.42)
* **External:** [Sam Ratcliff, David R. White, John A. Clark (2011) _Searching for invariants using genetic programming and mutation testing_](https://doi.org/10.1145/2001576.2001832)
* **External:** [Mark Harman, Yue Jia, William B. Langdon (2011) _Strong higher order mutation-based test data generation_](https://doi.org/10.1145/2025113.2025144)
* **External:** [Ronny Mandal (2011) _Towards Safe Mutation Testing in a Sandbox Environment_](http://hdl.handle.net/10852/8888)
* **Local PDF:** [Yue Jia, Mark Harman (2010) _An Analysis and Survey of the Development of Mutation Testing_](documents/An%20Analysis%20and%20Survey%20of%20the%20Development%20of%20Mutation%20Testing%20(2010).pdf) — [DOI](https://doi.org/10.1109/TSE.2010.62)
* **External:** [M. Harman, Yue Jia, W. Langdon (2010) _A Manifesto for Higher Order Mutation Testing_](https://doi.org/10.1109/icstw.2010.13)
* **External:** [William B. Langdon, Mark Harman, Yue Jia (2010) _Efficient multi-objective higher order mutation testing with genetic programming_](https://doi.org/10.1016/j.jss.2010.07.027)
* **External:** [Lu Zhang, Shan-Shan Hou, Jun-Jue Hu, Tao Xie, Hong Mei (2010) _Is operator-based mutant selection superior to random mutant selection?_](https://doi.org/10.1145/1806799.1806863)
* **External:** [L. Madeyski, N. Radyk (2010) _Judy – a mutation testing tool for Java_](https://doi.org/10.1049/iet-sen.2008.0038)
* **External:** [Yue Jia, Mark Harman (2009) _Higher Order Mutation Testing_](https://doi.org/10.1016/j.infsof.2008.09.016)
* **Local PDF:** [Macario Polo, Mario Piattini (2009) _Mutation testing: practical aspects and cost analysis_](documents/Mutation%20testing%20practical%20aspects%20and%20cost%20analysis%20(2009).pdf)
* **External:** [W. Langdon, M. Harman, Yue Jia (2009) _Multi Objective Higher Order Mutation Testing with Genetic Programming_](https://doi.org/10.1109/taicpart.2009.18)
* **External:** [Robert M. Hierons, Mercedes G. Merayo (2009) _Mutation testing from probabilistic and stochastic finite state machines_](https://doi.org/10.1016/j.jss.2009.06.030)
* **External:** [Yue Jia, Mark Harman (2008) _Constructing Subtle Faults Using Higher Order Mutation Testing_](https://doi.org/10.1109/scam.2008.36)
* **External:** [Yue Jia, Mark Harman (2008) _MILU: A Customizable, Runtime-Optimized Higher Order Mutation Testing Tool for the Full C Language_](https://doi.org/10.1109/taic-part.2008.18)
* **External:** [Robert M. Hierons, Mercedes G. Merayo (2007) _Mutation testing from probabilistic finite state machines_](https://doi.org/10.1109/taic.part.2007.20)
* **Local PDF:** [Jeff Offutt, Paul Ammann, Lisa (Ling) Liu (2006) _Mutation Testing implements Grammar-Based Testing_](documents/Mutation%20Testing%20implements%20Grammar-Based%20Testing%20(2006).pdf)
* **External:** [Auri Marcelo Rizzo Vincenzi, Adenilso Simão, Márcio Eduardo Delamaro, J. C. Maldonado (2006) _Muta-Pro: Towards the definition of a mutation testing process_](https://doi.org/10.1007/bf03192394)
* **External:** [Ying Jiang, Shan-Shan Hou, Jinhui Shan, Lu Zhang, Bing Xie (2005) _Contract-based mutation for testing components_](https://doi.org/10.1109/icsm.2005.36)
* **External:** [A.J. Offutt, Jie Pan (2002) _Detecting equivalent mutants and the feasible path problem_](https://doi.org/10.1109/cmpass.1996.507890)
* **External:** [Auri Marcelo Rizzo Vincenzi, José Carlos Maldonado, Ellen Francine Barbosa, Márcio Eduardo Delamaro (2001) _Unit and integration testing strategies for C programs using mutation_](https://doi.org/10.1002/stvr.242)
* **External:** [Auri Marcelo Rizzo Vincenzi, José Carlos Maldonado, Ellen Francine Barbosa, Márcio Eduardo Delamaro (2001) _Unit and Integration Testing Strategies for C Programs Using Mutation-Based Criteria_](https://doi.org/10.1007/978-1-4757-5939-6_8)
* **External:** [Phyllis G. Frankl, Stewart N. Weiss, Cang Hu (1997) _All-uses vs mutation testing: An experimental comparison of effectiveness_](https://doi.org/10.1016/s0164-1212(96)00154-9)
* **External:** [A. Jefferson Offutt, Jie Pan (1997) _Automatically detecting equivalent mutants and infeasible paths_](https://doi.org/10.1002/(sici)1099-1689(199709)7:3<165::aid-stvr143>3.0.co;2-u)
* **External:** [A. Jefferson Offutt, Ammei Lee, Gregg Rothermel, Roland H. Untch, Christian Zapf (1996) _An Experimental Determination of Sufficient Mutant Operators_](https://doi.org/10.1145/227607.227610)
* **External:** [W.Eric Wong, Aditya P. Mathur (1995) _Reducing the cost of mutation testing: An empirical study_](https://doi.org/10.1016/0164-1212(94)00098-0)
* **External:** [A. Jefferson Offutt, Stephen D. Lee (1994) _An empirical evaluation of weak mutation_](https://doi.org/10.1109/32.286422)
* **External:** [A. Jefferson Offutt, W. Michael Craft (1994) _Using compiler optimization techniques to detect equivalent mutants_](https://doi.org/10.1002/stvr.4370040303)
* **External:** [Roland H. Untch, A. Jefferson Offutt, Mary Jean Harrold (1993) _Mutation Analysis Using Mutant Schemata_](https://doi.org/10.1145/154183.154265)
* **External:** [Martin R. Woodward (1993) _Errors in algebraic specifications and an experimental mutation testing tool_](https://doi.org/10.1049/sej.1993.0027)
* **External:** [A. Jefferson Offutt (1992) _Investigations of the Software Testing Coupling Effect_](https://doi.org/10.1145/146637.146610)
* **Local PDF:** [Robert Geist, Jeff Offutt (1992) _Estimation and Enhancement of Real-Time Software Reliability through Mutation Analysis_](documents/Estimation%20and%20Enhancement%20of%20Real-Time%20Software%20Reliability%20through%20Mutation%20Analysis%20(1992).pdf)
* **External:** [I. M. M. Duncan, D. J. Robson (1990) _Ordered mutation testing_](https://doi.org/10.1145/382296.382699)
* **External:** [W.E. Howden (1982) _Weak Mutation Testing and Completeness of Test Sets_](https://doi.org/10.1109/tse.1982.235571)
* **External:** [Timothy A. Budd, Richard A. DeMillo, Richard J. Lipton, Frederick G. Sayward (1980) _Theoretical and Empirical Studies on Using Program Mutation to Test the Functional Correctness of Programs_](https://doi.org/10.1145/567446.567468)
* **External:** [Richard A. DeMillo, Richard J. Lipton, Frederick G. Sayward (1978) _Hints on Test Data Selection: Help for the Practicing Programmer_](https://doi.org/10.1109/C-M.1978.218136)

### Course material

* [Gordon Fraser (2010) _Mutation Testing_ — university course slides](documents/Mutation%20Testing%20(2010).pdf)

## Blogs/Posts

* [Who Mutates the Mutator? (2026) • Aleksei Gagarin (Testo)](https://php-testo.github.io/blog/self-mutation)
* [Infection + Testo (2026) • Aleksei Gagarin (Testo)](https://php-testo.github.io/blog/infection-debut)
* [Mutation Testing (2026) • Aleksei Gagarin (Testo)](https://php-testo.github.io/docs/theory/mutation-testing)
* [Path Coverage or Mutation Testing? (2025) • Sebastian Bergmann](https://phpunit.expert/articles/path-coverage-or-mutation-testing.html)
* [LLMs Are the Key to Mutation Testing and Better Compliance (2025) • Mark Harman (Meta)](https://engineering.fb.com/2025/09/30/security/llms-are-the-key-to-mutation-testing-and-better-compliance/)
* [Revolutionizing software testing: Introducing LLM-powered bug catchers (2025) • Christopher Foster, Abhishek Gulati, Mark Harman, Inna Harper, Ke Mao, Jillian Ritchey, Hervé Robert, Shubho Sengupta (Meta)](https://engineering.fb.com/2025/02/05/security/revolutionizing-software-testing-llm-powered-bug-catchers-meta-ach/)
* [The Power of Mutation Testing (2024) • The Green Report](https://www.thegreenreport.blog/articles/the-power-of-mutation-testing/the-power-of-mutation-testing.html)
* [Enhancing Test Effectiveness with Mutation Testing (2024) • João Coelho](https://medium.com/@joaovitorcoelho10/enhancing-test-effectiveness-with-mutation-testing-6a714c1dfd01)
* [Solidity Mutation Testing (2023) • RareSkills](https://rareskills.io/post/solidity-mutation-testing)
* [Mutation Testing Google Blog Entry (2021) • Goran Petrovic (Google)](https://testing.googleblog.com/2021/04/mutation-testing.html)
* [Test Your Tests Are Testing (2018) • Gert de Pagter](https://backendtea.com/post/test-your-tests-are-testing/)
* [A note on Mutation Operators (2017) • Markus Schirp](https://gist.github.com/AlexDenisov/feb0b5ab7c0648441b492a462b0f307f)
* [Relevant mutants (2024) • Manuel Rivero](https://codesai.com/posts/2024/07/relevant-mutants)
* [I built a single-compile mutation testing lib for Kotlin which runs inside your normal test suite (2026) • Andreas Schnapp](https://dev.to/5n4p_/i-built-a-single-compile-mutation-testing-lib-for-kotlin-which-runs-inside-your-normal-test-suite-4253)

## Videos

* [Rider Webinar 2023: How To Test C# Unit Tests With Mutation Testing • Stefan Pölz](https://www.youtube.com/watch?v=9BoKyeZapLs)
* [GOTO 2019 • Making Mutants Work for You • Henry Coles](https://www.youtube.com/watch?v=LoFJajoJQ2g&feature=youtu.be)
* [Test Automation Research for Industry 2019: Mutation Testing, Opportunities and Pitfalls • Ali Parsai](https://www.youtube.com/watch?v=oebxX3COmtg)
* [PHPDeveloperDay 2018: Mutation Testing • Théo Fidry](https://www.youtube.com/watch?v=dlVASJ-MbUE&list=PLW4GAs3yDy3IqKoRGGLJY5gG74SnLOQRH)
* [RailsConf 2017: How to Write Better Code Using Mutation Testing • John Backus](https://www.youtube.com/watch?v=uB7m9T7ymn8)
* [FOSDEM 2017: Mutation Testing: Leaving the Stone Age • Alex Denisov](https://www.youtube.com/watch?v=YEgiyiICkpQ)
* [Voxxed Athens 2017: Mutation Testing to the Rescue of Your Tests • Nicolas Fränkel](https://www.youtube.com/watch?v=E4UuxVWYCVQ)
* [Jfokus 2016: From JUnit to Mutation Testing • Sven Ruppert](https://www.youtube.com/watch?v=9yG1c9Crnbk)
* [GOTO 2015: Mutation Testing in Python • Austin Bingham](https://www.youtube.com/watch?v=jwB3Nn4hR1o)

## Conference presentations

* [Speaker Deck 2026: Would Your Tests Catch This Bug? A Mutation Testing Story • Szymon Fiedler](https://speakerdeck.com/szymonfiedler/would-your-tests-catch-this-bug-a-mutation-testing-story)
* [RubyConf 2024: The Mutation Game — Cracking the Enigma of Mutation Testing • Tyler Lemburg](https://www.youtube.com/watch?v=WqrL5w0WP0o)
* [NDC TechTown 2024: Mutation Testing in Python with Cosmic Ray • Austin Bingham](https://www.youtube.com/watch?v=HBqhjLaZejA)
* [PHP UK Conference 2024: The Absolute Beginner’s Guide to Mutation Testing • Neal Brooks](https://www.youtube.com/watch?v=h1fIXGb06h8)
* [ICCQ 2023: Mutant Selection Strategies in Mutation Testing • Rowland Pitts](https://www.youtube.com/watch?v=86TPTFavdFU)
* [Build Stuff 2023: Kill All Mutants! Intro to Mutation Testing • Dave Aronson](https://www.youtube.com/watch?v=pJyuQXo5Uyo)
* [ACCU 2022: Kill All Mutants! Intro to Mutation Testing • Dave Aronson](https://www.youtube.com/watch?v=u78zWfkCZ1Q)
* [Code BEAM Europe 2022: Kill All Mutants! Intro to Mutation Testing • Dave Aronson](https://www.youtube.com/watch?v=30ydZKPtVn4)
* [ICCQ 2022: Quasi-Dominators and Random Selection in Mutation Testing • Rowland Pitts](https://www.youtube.com/watch?v=XDXKAs6s8Eo)
* [Devoxx Poland 2021: Mutation Testing — Too Good to Be True? • Piotr Kubowicz](https://www.youtube.com/watch?v=hxFMqyn4U5A)
* [Laracon EU 2021: Mutation Testing with PHP • Jeroen Groenendijk](https://www.youtube.com/watch?v=OukNLda4TxA)
* [PHPKonf 2021: Mutation Testing in PHP • Maks Rafałko](https://www.youtube.com/watch?v=aDdXTY372Vo)
* [JSConf Hawaii 2020: Kill All Mutants! Introduction to Mutation Testing • Dave Aronson](https://www.youtube.com/watch?v=yNMBOj7JUPs)
* [LLVM Developers’ Meeting 2020: LLVM-Based Mutation Testing for C and C++ • Alex Denisov](https://www.youtube.com/watch?v=DfoS9kdTWmI)
* [MSR 2020: Mutation Testing Meets Software Analytics — A Hands-On Tutorial](https://www.youtube.com/watch?v=QY6T6znfm9Y)
* [NDC 2020: Testing the Tests — Mutation Testing for C++ • Seph De Busser](https://www.youtube.com/watch?v=M-5_M8qZXaE)
* [PHP Barcelona 2020: Mutation Testing — Better Code by Making Bugs • Théo Fidry](https://www.youtube.com/watch?v=GRB0sTweUVY)
* [PHP North East 2020: Mutation Testing with Infection](https://www.youtube.com/watch?v=E1xQXaXTjpQ)
* [Speaker Deck 2020: Getting Started with Mutation Testing • Denis Brumann](https://speakerdeck.com/dbrumann/getting-started-with-mutation-testing)
* [Symfony User Group 2020: What’s New in Symfony 5.1 and Getting Started with Mutation Testing](https://www.youtube.com/watch?v=lFY1td8kzEw)
* [DevConf Johannesburg 2019: Testing Your Tests’ Quality — Introduction to Mutation Testing • Felix Wu](https://www.youtube.com/watch?v=WTR8k6oPTyY)
* [fwdays 2019: Mutation Testing in PHP • Maks Rafałko](https://www.youtube.com/watch?v=8t-gCS3wbEE)
* [RubyConf 2019: Kill All Mutants! Intro to Mutation Testing • Dave Aronson](https://www.youtube.com/watch?v=9GId6mFL0_c)
* [Speaker Deck 2019: Mutation Testing at Pixels Camp • Pedro Rijo](https://speakerdeck.com/pedrorijo91/mutation-testing-pixels-camp-2019)
* [Speaker Deck 2019: Mutation Testing in Elixir • Daniel Serrano](https://speakerdeck.com/dnlserrano/mutation-testing-in-elixir)
* [Speaker Deck 2019: Mutation Testing with Infection • DragonBe](https://speakerdeck.com/dragonbe/mutation-testing-with-infection)
* [Speaker Deck 2018: Mutation Testing at PHPDeveloperDay • Théo Fidry](https://speakerdeck.com/theofidry/mutation-testing-phpdeveloperday)
* [Symfony User Group Osnabrück: Mutation Testing with Symfony](https://www.youtube.com/watch?v=CUzjQ-BOd6w)
* [Speaker Deck 2014: Mutation Testing with Mutant • Erik Berlin](https://speakerdeck.com/sferik/mutation-testing-with-mutant)

## Conferences

* International Workshop on Mutation Analysis
  * [MUTATION 2018, The 13th International Workshop on Mutation Analysis](https://mutation-workshop.github.io)

## Examples and practical resources

* [atodorov/mutation-testing-in-patterns](https://github.com/atodorov/mutation-testing-in-patterns)
    * Practical examples of software and testing patterns related to mutation testing [Mutation Testing in Patterns](http://mutation-testing-patterns.rtfd.io)

## Tutorials

* [Introduction to Mutation Testing with PIT (Java)](https://github.com/sualeh/introduction-to-mutation-testing)
