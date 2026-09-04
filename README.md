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

* [Hervé Robert, Shubho Sengupta (2025) _Mutation-Guided LLM-based Test Generation at Meta_](documents/Mutation-Guided%20LLM-based%20Test%20Generation%20at%20Meta%20(2025).pdf)
* [Jeongju Sohn, Ezekiel Soremekun, Michail Papadakis (2025) _Latent Mutants: A large-scale study on the Interplay between mutation testing and software evolution_](documents/Latent%20Mutants%20A%20large%20scale%20study%20on%20the%20Interplay%20between%20mutation%20testing%20and%20software%20evolution%20(2025).pdf)
* [Dolores Miao, Ignacio Laguna, Giorgis Georgakoudis, Konstantinos Parasyris, Cindy Rubio-González (2024) _An automated OpenMP mutation testing framework for performance optimization_](documents/An%20automated%20OpenMP%20mutation%20testing%20framework%20for%20performance%20optimization%20(2024).pdf) — [DOI](https://doi.org/10.1016/j.parco.2024.103097)
* [Enzo Nicourt, Benjamin Kushigian, Chandrakana Nandi, Yliès Falcone (2024) _Using Mutation Testing To Improve and Minimize Test Suites for Smart Contracts_](documents/Using%20Mutation%20Testing%20To%20Improve%20and%20Minimize%20Test%20Suites%20for%20Smart%20Contracts.pdf)
* [Pedro Delgado-Pérez, Ana B. Sánchez, Sergio Segura, Inmaculada Medina-Bulo (2022) _Mutation testing in the wild: findings from GitHub_](documents/Mutation%20testing%20in%20the%20wild:%20findings%20from%20GitHub%20(2022).pdf) — [DOI](https://doi.org/10.1007/s10664-022-10177-8)
* [Giovani Guizzo, Federica Sarro, Jens Krinke, Silvia Regina Vergilio (2022) _Sentinel: A Hyper-Heuristic for the Generation of Mutant Reduction Strategies_](documents/Sentinel:%20A%20Hyper-Heuristic%20for%20the%20Generation%20of%20Mutant%20Reduction%20Strategies%20(2021).pdf) — [DOI](https://doi.org/10.1109/TSE.2020.3002496)
* [Goran Petrović, Marko Ivanković, Gordon Fraser, René Just (2021) _Practical Mutation Testing at Scale: A view from Google_](documents/Practical%20Mutation%20Testing%20at%20Scale%20A%20view%20from%20Google%20(2021).pdf) — [DOI](https://doi.org/10.1109/TSE.2021.3107634)
* [Goran Petrović, Marko Ivanković, Gordon Fraser, René Just (2021) _Does mutation testing improve testing practices?_](documents/Does%20mutation%20testing%20improve%20testing%20practices%3F%20(2021).pdf) — [DOI](https://doi.org/10.1109/ICSE43902.2021.00087)
* [Y. Ivanova, A. Khritankov (2020) _RegularMutator: A Mutation Testing Tool for Solidity Smart Contracts_](documents/RegularMutator:%20A%20Mutation%20Testing%20Tool%20for%20Solidity%20Smart%20Contracts%20(2020).pdf) — [DOI](https://doi.org/10.1016/j.procs.2020.11.009)
* [Pedro Delgado-Pérez, Ana Belén Sánchez, Sergio Segura, Inmaculada Medina-Bulo (2020) _Performance mutation testing_](documents/Performance%20Mutation%20Testing%20(2010).pdf) — [DOI](https://doi.org/10.1002/stvr.1728)
* [Alessandro Viola Pizzoleto, Fabiano Cutigi Ferrari, Jeff Offutt, Leo Fernandes, Márcio Ribeiro (2019) _A Systematic Literature Review of Techniques and Metrics to Reduce the Cost of Mutation Testing_](documents/A%20Systematic%20Literature%20Review%20of%20Techniques%20and%20Metrics%20to%20Reduce%20the%20Cost%20of%20Mutation%20Testing%20(2019).pdf) — [DOI](https://doi.org/10.1016/j.jss.2019.07.100)
* [August Shi, Jonathan Bell, Darko Marinov (2019) _Mitigating the Effects of Flaky Tests on Mutation Testing_](documents/Mitigating%20the%20Effects%20of%20Flaky%20Tests%20on%20Mutation%20Testing%20(2019).pdf) — [DOI](https://doi.org/10.1145/3293882.3330568)
* [Esther Guerra, Jesús Sánchez Cuadrado, Juan de Lara (2019) _Towards effective mutation testing for ATL_](documents/Towards%20effective%20mutation%20testing%20for%20ATL%20(2019).pdf)
* [Mike Papadakis, Marinos Kintis, Jie Zhang, Yue Jia, Yves Le Traon, Mark Harman (2019) _Mutation Testing Advances: An Analysis and Survey_](documents/Mutation%20Testing%20Advances:%20An%20Analysis%20and%20Survey%20(2017).pdf) — [DOI](https://doi.org/10.1016/bs.adcom.2018.03.015)
* [Lin Deng, Jeff Offutt (2018) _Reducing the Cost of Android Mutation Testing_](documents/Reducing%20the%20Cost%20of%20Android%20Mutation%20Testing%20(2018).pdf)
* [Goran Petrović, Marko Ivanković (2018) _State of Mutation Testing at Google_](documents/State%20of%20Mutation%20Testing%20at%20Google%20(2018).pdf) — [DOI](https://doi.org/10.1145/3183519.3183521)
* [Goran Petrović, Marko Ivanković, Bob Kurtz, Paul Ammann, René Just (2018) _An Industrial Application of Mutation Testing: Lessons, Challenges, and Research Directions_](documents/An%20Industrial%20Application%20of%20Mutation%20Testing%20Lessons,%20Challenges,%20and%20Research%20Directions%20(2018).pdf) — [DOI](https://doi.org/10.1109/ICSTW.2018.00027)
* [Sten Vercammen, Mohammad Ghafari, Serge Demeyer, Markus Borg (2018) _Goal-Oriented Mutation Testing with Focal Methods_](documents/Goal-Oriented%20Mutation%20Testing%20with%20Focal%20Methods%20(2018).pdf) — [DOI](https://doi.org/10.1145/3278186.3278190)
* [Qianqian Zhu, Annibale Panichella, Andy Zaidman (2018) _A Systematic Literature Review of How Mutation Testing Supports Quality Assurance Processes_](documents/A%20Systematic%20Literature%20Review%20of%20How%20Mutation%20Testing%20Supports%20Quality%20Assurance%20Processes%20(2018).pdf) — [DOI](https://doi.org/10.1002/stvr.1675)
* [Lingchao Chen, Lingming Zhang (2018) _Speeding up Mutation Testing via Regression Test Selection: An Extensive Study_](documents/Speeding%20up%20Mutation%20Testing%20via%20Regression%20Test%20Selection:%20An%20Extensive%20Study%20(2018).pdf)
* [Pablo C. Cañizares, Alberto Núñez, Juan de Lara (2017) _OUTRIDER: Optimizing the mUtation Testing pRocess In Distributed EnviRonments_](documents/OUTRIDER:%20Optimizing%20the%20mUtation%20Testing%20pRocess%20In%20Distributed%20EnviRonments%20(2017).pdf)
* [Qianqian Zhu, Annibale Panichella, Andy Zaidman (2017) _Speeding-Up Mutation Testing via Data Compression and State Infection_](documents/Speeding-Up%20Mutation%20Testing%20via%20Data%20Compression%20and%20State%20Infection%20(2017).pdf)
* [Jie Zhang, Ziyi Wang, Lingming Zhang, Dan Hao, Lei Zang, Shiyang Cheng, Lu Zhang (2016) _Predictive Mutation Testing_](documents/Predictive%20Mutation%20Testing%20(2016).pdf) — [DOI](https://doi.org/10.1145/2931037.2931038)
* [Marinos Kintis (2016) _Effective Methods to Tackle the Equivalent Mutant Problem when Testing Software with Mutation_](documents/Effective%20Methods%20to%20Tackle%20the%20Equivalent%20Mutant%20Problem%20when%20Testing%20Software%20with%20Mutation%20(2016).pdf)
* [René Just, Darioush Jalali, Laura Inozemtseva, Michael D. Ernst, Reid Holmes, Gordon Fraser (2014) _Are Mutants a Valid Substitute for Real Faults in Software Testing?_](documents/Are%20Mutants%20a%20Valid%20Substitute%20for%20Real%20Faults%20in%20Software%20Testing%3F%20(2014).pdf) — [DOI](https://doi.org/10.1145/2635868.2635929)
* [Lorena Gutiérrez-Madroñal, J. Domínguez-Jiménez, I. Medina-Bulo (2014) _Mutation Testing: Guideline and Mutation Operator Classification_](documents/Mutation%20Testing%20Guideline%20and%20Mutation%20Operator%20Classification%20(2014).pdf)
* [L. Madeyski, W. Orzeszyna, R. Torkar, M. Józala (2014) _Overcoming the Equivalent Mutant Problem: A Systematic Literature Review and a Comparative Experiment of Second Order Mutation_](documents/Overcoming%20the%20Equivalent%20Mutant%20Problem%20A%20Systematic%20Literature%20Review%20and%20a%20Comparative%20Experiment%20of%20Second%20Order%20Mutation%20(2014).pdf)
* [Lingming Zhang, Darko Marinov, Sarfraz Khurshid (2013) _Faster Mutation Testing Inspired by Test Prioritization and Reduction_](documents/Faster%20Mutation%20Testing%20Inspired%20by%20Test%20Prioritization%20and%20Reduction%20(2013).pdf) — [DOI](https://doi.org/10.1145/2483760.2483782)
* [Bouchaib Falah, Bouriat Salwa (2013) _Effectiveness of Mutation Testing Techniques: Reducing Mutation Cost_](documents/Effectiveness%20of%20Mutation%20Testing%20Techniques%20Reducing%20Mutation%20Cost%20(2013).pdf)
* [Quang Vu Nguyen, Lech Madeyski (2013) _Problems of Mutation Testing and Higher Order Mutation Testing_](documents/Problems%20of%20Mutation%20Testing%20and%20Higher%20Order%20Mutation%20Testing%20(2013).pdf)
* [Lingming Zhang, Milos Gligoric, Darko Marinov, Sarfraz Khurshid (2013) _Operator-Based and Random Mutant Selection: Better Together_](documents/Operator-Based%20and%20Random%20Mutant%20Selection%20Better%20Together%20(2013).pdf)
* [Kevin Jalbert, Jeremy S. Bradbury (2012) _Predicting Mutation Scores using Source Code and Test Suite Metrics_](documents/Predicting%20Mutation%20Score%20Using%20Source%20Code%20and%20Test%20Suite%20Metrics%20(2012).pdf)
* [David Schuler (2011) _Assessing Test Quality_](documents/Assessing%20Test%20Quality%20(2011).pdf)
* [John A. Clark, Haitao Dan, Robert M. Hierons (2011) _Semantic Mutation Testing_](documents/Semantic%20mutation%20testing%20(2011).pdf) — [DOI](https://doi.org/10.1016/j.scico.2011.03.011)
* [Yue Jia, Mark Harman (2010) _An Analysis and Survey of the Development of Mutation Testing_](documents/An%20Analysis%20and%20Survey%20of%20the%20Development%20of%20Mutation%20Testing%20(2010).pdf) — [DOI](https://doi.org/10.1109/TSE.2010.62)
* [Macario Polo, Mario Piattini (2009) _Mutation testing: practical aspects and cost analysis_](documents/Mutation%20testing%20practical%20aspects%20and%20cost%20analysis%20(2009).pdf)
* [Jeff Offutt, Paul Ammann, Lisa (Ling) Liu (2006) _Mutation Testing implements Grammar-Based Testing_](documents/Mutation%20Testing%20implements%20Grammar-Based%20Testing%20(2006).pdf)
* [Robert Geist, Jeff Offutt (1992) _Estimation and Enhancement of Real-Time Software Reliability through Mutation Analysis_](documents/Estimation%20and%20Enhancement%20of%20Real-Time%20Software%20Reliability%20through%20Mutation%20Analysis%20(1992).pdf)

### Course material

* [Gordon Fraser (2010) _Mutation Testing_ — university course slides](documents/Mutation%20Testing%20(2010).pdf)

## Blogs/Posts

* [LLMs Are the Key to Mutation Testing and Better Compliance (2025) • Mark Harman (Meta)](https://engineering.fb.com/2025/09/30/security/llms-are-the-key-to-mutation-testing-and-better-compliance/)
* [Revolutionizing software testing: Introducing LLM-powered bug catchers (2025) • Christopher Foster, Abhishek Gulati, Mark Harman, Inna Harper, Ke Mao, Jillian Ritchey, Hervé Robert, Shubho Sengupta (Meta)](https://engineering.fb.com/2025/02/05/security/revolutionizing-software-testing-llm-powered-bug-catchers-meta-ach/)
* [The Power of Mutation Testing (2024) • The Green Report](https://www.thegreenreport.blog/articles/the-power-of-mutation-testing/the-power-of-mutation-testing.html)
* [Enhancing Test Effectiveness with Mutation Testing (2024) • João Coelho](https://medium.com/@joaovitorcoelho10/enhancing-test-effectiveness-with-mutation-testing-6a714c1dfd01)
* [Solidity Mutation Testing (2023) • RareSkills](https://rareskills.io/post/solidity-mutation-testing)
* [Mutation Testing Google Blog Entry (2021) • Goran Petrovic (Google)](https://testing.googleblog.com/2021/04/mutation-testing.html)
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

## Conferences

* International Workshop on Mutation Analysis
  * [MUTATION 2018, The 13th International Workshop on Mutation Analysis](https://mutation-workshop.github.io)

## Examples and practical resources

* [atodorov/mutation-testing-in-patterns](https://github.com/atodorov/mutation-testing-in-patterns)
    * Practical examples of software and testing patterns related to mutation testing [Mutation Testing in Patterns](http://mutation-testing-patterns.rtfd.io)

## Tutorials

* [Introduction to Mutation Testing with PIT (Java)](https://github.com/sualeh/introduction-to-mutation-testing)
