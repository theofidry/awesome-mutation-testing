# Awesome Mutation testing [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

Mutation testing is the practice of making better code by introducing bugs. As of now this repository is used to keep track of the current mutation testing tools developed and related resources. Its contents and purpose may however evolve depending on the community.

[Slack channel](https://mutation-testing.slack.com/)

[Slack Invite](https://mutation-testing-slack.herokuapp.com/)

### Contents

- [Existing libraries](#existing-libraries)
- [Abandoned libraries](abandoned.md)
- [Visualization Tool](#visualization-tool)
- [Papers](#papers)
- [Blogs/Posts/Videos](#blogspostsvideos)
- [Conferences](#conferences)
- [Friendly resources](#friendly-resources)
- [Tutorials](#tutorials)


### Existing libraries

* Alloy
  * [MuAlloy](https://github.com/kaiyuanw/MuAlloy)
    * [MuAlloy papers](https://github.com/kaiyuanw/MuAlloy#publications)
* C/C++
  * [llvm-mutate](https://eschulte.github.io/llvm-mutate/)
  * [Frama-C plugin](https://github.com/gpetiot/Frama-C-Mutation/)
  * [mull-project/mull](https://github.com/mull-project/mull)
  * [mutate_cpp](https://github.com/nlohmann/mutate_cpp)
  * [MuCPP](https://neptuno.uca.es/redmine/projects/mucpp-mutation-tool/wiki)
    * [Assessment of Class Mutation Operators for C++ with the MuCPP Mutation System](https://pdfs.semanticscholar.org/05d5/2ba68ed4ba8505cc92e4f27ad68c1b944842.pdf)
  * [accmut](https://github.com/wangbo15/accmut)
    * [Faster mutation analysis via equivalence modulo states](http://sei.pku.edu.cn/%7Exiongyf04/papers/ISSTA17.pdf)
  * [MUSIC](https://github.com/swtv-kaist/MUSIC)
    * [MUSIC: Mutation Analysis Tool with High Configurability and Extensibility](http://swtv.kaist.ac.kr/publications/music-mutation18.pdf)
  * [dextool](https://github.com/joakim-brannstrom/dextool)
  * [SRCIROR](https://github.com/TestingResearchIllinois/srciror) - A mutation tool for source and IR
    * [SRCIROR: A Toolset for Mutation Testing of C Source Code and LLVM Intermediate Representation](http://mir.cs.illinois.edu/farah/publications/ase18_srciror.pdf)
  * [MART](https://github.com/thierry-tct/mart)
* C#
  * [stryker-mutator/stryker-net](https://github.com/stryker-mutator/stryker-net)
  * [ComparetheMarket/fettle](https://github.com/ComparetheMarket/fettle)
  * [Testura.Mutation](https://github.com/Testura/Testura.Mutation)
* Clojure
  * [mutant](https://github.com/jstepien/mutant)
* Crystal
  * [crytic](https://github.com/hanneskaeufler/crytic)
* Elixir
  * [JordiPolo/mutation](https://github.com/JordiPolo/mutation)
* Erlang
  * [parsifal-47/muterl](https://github.com/parsifal-47/muterl)
* Go
  * [zimmski/go-mutesting](https://github.com/zimmski/go-mutesting)
* Haskell
  * [rudymatela/fitspec](https://github.com/rudymatela/fitspec)
* Java/JVM
  * [hcoles/pitest](https://github.com/hcoles/pitest)
        * [PIT : A Practical Mutation Testing Tool for Java (Demo)](https://dl.acm.org/citation.cfm?id=2948707)
        * [An Experimental Evaluation of PIT’s Mutation Operators](http://www.diva-portal.org/smash/get/diva2:1161760/FULLTEXT01.pdf)
    * [Introduction to Mutation Testing](https://blog.frankel.ch/introduction-to-mutation-testing/)
    * [Faster Mutation Testing (in Java)](https://blog.frankel.ch/faster-mutation-testing/)
        * [Voxxed Athens 2017 :: Mutation Testing to the rescue of your Tests • Nicolas Fränkel](https://www.youtube.com/watch?v=E4UuxVWYCVQ)
  * [aliparsai/LittleDarwin](https://github.com/aliparsai/LittleDarwin)
    * [LittleDarwin: a Feature-Rich and Extensible Mutation Testing Framework for Large and Complex Java Systems](https://www.parsai.net/files/research/LittleDarwin%20a%20Feature-Rich%20and%20Extensible%20Mutation%20Testing%20Framework%20for%20Large%20and%20Complex%20Java%20Systems%20(pre-print).pdf)
  * [metamutator](https://github.com/SpoonLabs/metamutator)
  * [Major](http://mutation-testing.org)
    * [Publications related to the Major mutation framework](http://mutation-testing.org/publ/)
* JavaScript
  * [stryker-mutator/stryker](https://github.com/stryker-mutator/stryker)
* PHP
  * [infection/infection](https://github.com/infection)
* Python
  * [sixty-north/cosmic-ray](https://github.com/sixty-north/cosmic-ray)
  * [boxed/mutmut](https://github.com/boxed/mutmut)
  * [xmutant.py](https://github.com/vrthra/xmutant.py)
* Ruby
  * [mbj/mutant](https://github.com/mbj/mutant)
    * [Kill all the mutants - a deep dive into mutation testing and how the Mutant gem works](https://troessner.svbtle.com/kill-all-the-mutants-a-deep-dive-into-mutation-testing-and-how-the-mutant-gem-works)
  * [backus/mutest](https://github.com/backus/mutest)
* Rust
  * [llogiq/mutagen](https://github.com/llogiq/mutagen)
* Scala
  * [sugakandrey/scalamu](https://github.com/sugakandrey/scalamu)
  * [stryker4s](https://stryker-mutator.io/stryker4s/)
* Smalltalk
  * [pavel-krivanek/mutalk](https://github.com/pavel-krivanek/mutalk) 
* Swift
  * [SeanROlszewski/muter](https://github.com/SeanROlszewski/muter) 
* Other
  * [agroce/universalmutator](https://github.com/agroce/universalmutator)
  * [boggart](https://github.com/squaresLab/boggart)

### Visualization Tool

* [sqrlab/VisMAn](https://github.com/sqrlab/VisMAn)


### Papers

* [Mutation Testing Repository](http://crestweb.cs.ucl.ac.uk/resources/mutation_testing_repository)
* [An Analysis and Survey of the Development of Mutation Testing](http://www0.cs.ucl.ac.uk/staff/mharman/tse-mutation-survey.pdf)
* [Mutation Testing Advances: An Analysis and Survey](https://mutationtesting.uni.lu/survey.pdf)
* [Are Mutants a Valid Substitute for Real Faults in Software Testing?](https://homes.cs.washington.edu/~mernst/pubs/mutation-effectiveness-fse2014.pdf)
* [Predicting Mutation Scores using Source Code and Test Suite Metrics](https://github.com/kevinjalbert/master-thesis)
* [CrestWeb](http://crestweb.cs.ucl.ac.uk/resources/mutation_testing_repository)
* [Mutation Testing Repository at LU](https://mutationtesting.uni.lu/)
* [An Industrial Application of Mutation Testing: Lessons, Challenges, and Research Direction](https://homes.cs.washington.edu/~rjust/publ/industrial_mutation_icst_2018.pdf)
* [Predictive Mutation Testing](https://personal.utdallas.edu/~lxz144130/publications/issta2016.pdf)
* [Semantic Mutation Testing](http://www-users.cs.york.ac.uk/~jac/PublishedPapers/semantic_journal4.pdf)
* [Assessing Test Quality](https://d-nb.info/1051432480/34)
* [Mutation Testing](https://www.st.cs.uni-saarland.de/edu/testingdebugging10/slides/10-MutationTesting.pdf)
* [Mutation Testing: Guideline and Mutation Operator Classification](https://pdfs.semanticscholar.org/1f0b/7edf1bdf2ccf935398bb79faab808b6e7134.pdf)
* [Faster Mutation Testing Inspired by Test Prioritization and Reduction](https://personal.utdallas.edu/~lxz144130/cs6301-readings/mutation-testing-zhang-issta13.pdf)
* [Estimation and Enhancement of Real-Time Software Reliability through Mutation Analysis](https://www.researchgate.net/publication/3042963_Estimation_and_Enhancement_of_Real-Time_Software_Reliability_through_Mutation_Analysis)
* [Problems of Mutation Testing and Higher Order Mutation Testing](http://madeyski.e-informatyka.pl/download/NguyenMadeyski14.pdf)
* [Effectiveness of Mutation Testing Techniques: Reducing Mutation Cost](https://www.researchgate.net/publication/281858788_Effectiveness_of_Mutation_Testing_Techniques_Reducing_Mutation_Cost)
* [Reducing the Cost of Android Mutation Testing](https://ksiresearchorg.ipage.com/seke/seke18paper/seke18paper_184.pdf)
* [A Systematic Literature Review of Techniques and Metrics to Reduce the Cost of Mutation Testing](https://cs.gmu.edu/~offutt/rsrch/papers/SLR-CostReductionMutation.pdf)
* [Effective Methods to Tackle the Equivalent Mutant Problem when Testing Software with Mutation](http://pages.cs.aueb.gr/~kintism/phd-thesis/Kintis-PhD-2016.pdf)
* [Goal-Oriented Mutation Testing with Focal Methods](https://arxiv.org/pdf/1807.10953.pdf)
* [OUTRIDER: Optimizing the mUtation Testing pRocess In Distributed EnviRonments](http://miso.es/pubs/iccs17.pdf)
* [Mutation testing: practical aspects and cost analysis](http://antares.sip.ucm.es/tarot09/index_files/MutationTestingTAROT09.pdf)
* [Mitigating the Effects of Flaky Tests on Mutation Testing](https://www.jonbell.net/preprint/issta19mutants.pdf)
* [Speeding-Up Mutation Testing via Data Compression and State Infection](https://peerj.com/preprints/2632.pdf)
* [State of Mutation Testing at Google](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/46584.pdf)
* [Operator-Based and Random Mutant Selection: Better Together](http://mir.cs.illinois.edu/~marinov/publications/ZhangETAL13BetterTogether.pdf)
* [Towards effective mutation testing for ATL](http://miso.es/pubs/models19.pdf)

* [PropEr Testing](http://propertesting.com/)

### Blogs/Posts/Videos

* [Mutant Musings](https://github.com/tjchambers/mutant-musings)
* [RailsConf 2017: How to Write Better Code Using Mutation Testing • John Backus](https://www.youtube.com/watch?v=uB7m9T7ymn8)
* [FOSDEM 2017: Mutation Testing: Leaving the Stone Age • Alex Denisov](https://www.youtube.com/watch?v=YEgiyiICkpQ)
* [GOTO 2015: Mutation Testing in Python • Austin Bingham](https://www.youtube.com/watch?v=jwB3Nn4hR1o)
* [GOTO 2019 • Making Mutants Work for You • Henry Coles](https://www.youtube.com/watch?v=LoFJajoJQ2g&feature=youtu.be)
* [Jfokus 2016: From jUnit to Mutation-Testing • Sven Ruppert](https://www.youtube.com/watch?v=9yG1c9Crnbk)
* [PHPDeveloperDay 2018: Mutation Testing • Theo Fidry](https://www.youtube.com/watch?v=dlVASJ-MbUE&list=PLW4GAs3yDy3IqKoRGGLJY5gG74SnLOQRH)
* [Test Automation Research for Industry 2019: Mutation Testing, Opportunities and Pitfalls • Ali Parsai](https://www.youtube.com/watch?v=oebxX3COmtg)
* [Markus Schirp On Mutation Operators](https://gist.github.com/AlexDenisov/feb0b5ab7c0648441b492a462b0f307f)

### Conferences

* International Workshop on Mutation Analysis
  * [MUTATION 2018, The 13th International Workshop on Mutation Analysis](https://mutation-workshop.github.io)

### Friendly resources

* [atodorov/mutation-testing-in-patterns](https://github.com/atodorov/mutation-testing-in-patterns)
    * Practical examples of software and testing patterns related to mutation testing [Mutation Testing in Patterns](http://mutation-testing-patterns.rtfd.io)

### Tutorials

* [Introduction to Mutation Testing with PIT (Java)](https://github.com/sualeh/introduction-to-mutation-testing)
