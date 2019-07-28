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
    * [SRCIROR: A Toolset for Mutation Testing of C Source Code and
LLVM Intermediate Representation](http://mir.cs.illinois.edu/farah/publications/ase18_srciror.pdf)
  * [MART](https://github.com/thierry-tct/mart)
* C#
  * [stryker-mutator/stryker-net](https://github.com/stryker-mutator/stryker-net)
  * [ComparetheMarket/fettle](https://github.com/ComparetheMarket/fettle)
  * [Unima](https://github.com/MilleBo/Unima)
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
    * [Introduction to Mutation Testing](https://blog.frankel.ch/introduction-to-mutation-testing/)
    * [Faster Mutation Testing (in Java)](https://blog.frankel.ch/faster-mutation-testing/)
  	* [Voxxed Athens 2017 :: Mutation Testing to the rescue of your Tests • Nicolas Fränkel](https://www.youtube.com/watch?v=E4UuxVWYCVQ)
  * [aliparsai/LittleDarwin](https://github.com/aliparsai/LittleDarwin)
    * [LittleDarwin: a Feature-Rich and ExtensibleMutation Testing Framework forLarge and Complex Java Systems](https://www.researchgate.net/publication/318223563_LittleDarwin_a_Feature-Rich_and_Extensible_Mutation_Testing_Framework_for_Large_and_Complex_Java_Systems)
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

* [An Analysis and Survey of the Development of Mutation Testing](http://www0.cs.ucl.ac.uk/staff/mharman/tse-mutation-survey.pdf)
* [Mutation Testing Advances: An Analysis and Survey](https://mutationtesting.uni.lu/survey.pdf)
* [Are Mutants a Valid Substitute for Real Faults in Software Testing?](https://homes.cs.washington.edu/~mernst/pubs/mutation-effectiveness-fse2014.pdf)
* [Predicting Mutation Scores using Source Code and Test Suite Metrics](https://github.com/kevinjalbert/master-thesis)
* [CrestWeb](http://crestweb.cs.ucl.ac.uk/resources/mutation_testing_repository)
* [Mutation Testing Repository at LU](https://mutationtesting.uni.lu/)

* [PropEr Testing](http://propertesting.com/)

### Blogs/Posts/Videos

* [Mutant Musings](https://github.com/tjchambers/mutant-musings)
* [RailsConf 2017: How to Write Better Code Using Mutation Testing • John Backus](https://www.youtube.com/watch?v=uB7m9T7ymn8)
* [FOSDEM 2017: Mutation Testing: Leaving the Stone Age • 
Alex Denisov
](https://www.youtube.com/watch?v=YEgiyiICkpQ)
* [GOTO 2015: Mutation Testing in Python • Austin Bingham](https://www.youtube.com/watch?v=jwB3Nn4hR1o)
* [Jfokus 2016: From jUnit to Mutation-Testing • Sven Ruppert](https://www.youtube.com/watch?v=9yG1c9Crnbk)
* [PHPDeveloperDay 2018: Mutation Testing • Theo Fidry](https://www.youtube.com/watch?v=dlVASJ-MbUE&list=PLW4GAs3yDy3IqKoRGGLJY5gG74SnLOQRH)

### Conferences

- International Workshop on Mutation Analysis
  - [MUTATION 2018, The 13th International Workshop on Mutation Analysis](https://mutation-workshop.github.io)

### Friendly resources

- [atodorov/mutation-testing-in-patterns](https://github.com/atodorov/mutation-testing-in-patterns)

> Practical examples of software and testing patterns related to mutation testing http://mutation-testing-patterns.rtfd.io
