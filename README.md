# Awesome Mutation testing [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

As of now this repository is used to keep track of the current mutation testing tools developed. In the future this may be extended to reference more materials such as research papers, videos & talks.

[Slack channel](https://mutation-testing.slack.com/)

[Slack Invite](https://mutation-testing-slack.herokuapp.com/)

### Contents

1. [Existing libraries](#existing-libraries)
1. [Visualization Tool](#visualization-tool)
1. [Papers](#papers)
1. [Blogs/Posts/Videos](#blogspostsvideos)
1. [Conferences](#conferences)
1. [Friendly resources](#friendly-resources)


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
  * [yuejia/Milu](https://github.com/yuejia/Milu) [abandoned]
    * [MILU: A Customizable, Runtime-Optimized Higher Order Mutation Testing Tool for the Full C Language](https://www.researchgate.net/publication/228609925_MILU_A_Customizable_Runtime-Optimized_Higher_Order_Mutation_Testing_Tool_for_the_Full_C_Language)
  * [dextool](https://github.com/joakim-brannstrom/dextool)
  * [markus-kusano/CCMutator](https://github.com/markus-kusano/CCMutator) [abandoned]
    * [CCmutator: A Mutation Generator for Concurrency Constructs in Multithreaded C/C++ Applications](http://www-bcf.usc.edu/~wang626/pubDOC/Kusano13CCmutator.pdf)
  * [SRCIROR](https://github.com/TestingResearchIllinois/srciror) - A mutation tool for source and IR
* C#
  * [infosupport/stryker-net](https://github.com/infosupport/stryker-net)
  * [ComparetheMarket/fettle](https://github.com/ComparetheMarket/fettle)
* Clojure
  * [mutant](https://github.com/jstepien/mutant)
  * [ds2643/mutcl](https://github.com/ds2643/mutcl) [abandoned]
* Crystal
  * [crytic](https://github.com/hanneskaeufler/crytic)
* Elixir
  * [JordiPolo/mutation](https://github.com/JordiPolo/mutation)
* Go
  * [zimmski/go-mutesting](https://github.com/zimmski/go-mutesting)
  * [darkhelmet/manbearpig](https://github.com/darkhelmet/manbearpig) [abandoned]
  * [kisielk/mutator](https://github.com/kisielk/mutator) [abandoned]
  * [StefanSchroeder/Golang-Mutation-testing](https://github.com/StefanSchroeder/Golang-Mutation-testing) [abandoned]
* Haskell
  * [rudymatela/fitspec](https://github.com/rudymatela/fitspec)
* Java/JVM
  * [hcoles/pitest](https://github.com/hcoles/pitest)
  * [aliparsai/LittleDarwin](https://github.com/aliparsai/LittleDarwin)
    * [LittleDarwin: a Feature-Rich and ExtensibleMutation Testing Framework forLarge and Complex Java Systems](https://www.researchgate.net/publication/318223563_LittleDarwin_a_Feature-Rich_and_Extensible_Mutation_Testing_Framework_for_Large_and_Complex_Java_Systems)
  * [metamutator](https://github.com/SpoonLabs/metamutator)
  * [Major](http://mutation-testing.org)
    * [Publications related to the Major mutation framework](http://mutation-testing.org/publ/)
  * [jeffoffutt/muJava](https://github.com/jeffoffutt/muJava) [abandoned]
  * [sqrlab/ConMAn](https://github.com/sqrlab/ConMAn) [abandoned]
  * [bulentrahimkazanci/Mutation-Testing](https://github.com/bulentrahimkazanci/Mutation-Testing) [abandoned]
* JavaScript
  * [stryker-mutator/stryker](https://github.com/stryker-mutator/stryker)
  * [lazywithclass/mutagen](https://github.com/lazywithclass/mutagen) [abandoned]
  * [bttmly/perturb](https://github.com/bttmly/perturb) [abandoned]
  * [lazywithclass/cerebro](https://github.com/lazywithclass/cerebro) [abandoned]
* PHP
  * [infection/infection](https://github.com/infection)
  * [humbug/humbug](https://github.com/humbug/humbug) [deprecated]
* Python
  * [sixty-north/cosmic-ray](https://github.com/sixty-north/cosmic-ray)
  * [boxed/mutmut](https://github.com/boxed/mutmut)
  * [xmutant.py](https://github.com/vrthra/xmutant.py)
  * [ds2643/mutpy](https://github.com/ds2643/mutpy) [abandoned]
* Ruby
  * [mbj/mutant](https://github.com/mbj/mutant)
    * [Kill all the mutants - a deep dive into mutation testing and how the Mutant gem works](https://troessner.svbtle.com/kill-all-the-mutants-a-deep-dive-into-mutation-testing-and-how-the-mutant-gem-works)
  * [backus/mutest](https://github.com/backus/mutest)
* Rust
  * [apoelstra/halfsleep](https://github.com/apoelstra/halfsleep) [abandoned]
  * [Geal/mutant](https://github.com/Geal/mutant) [abandoned]
  * [llogiq/mutagen](https://github.com/llogiq/mutagen)
* Scala
  * [sugakandrey/scalamu](https://github.com/sugakandrey/scalamu)
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


### Conferences

- International Workshop on Mutation Analysis
  - [MUTATION 2018, The 13th International Workshop on Mutation Analysis](https://mutation-workshop.github.io)

### Friendly resources

- [atodorov/mutation-testing-in-patterns](https://github.com/atodorov/mutation-testing-in-patterns)

> Practical examples of software and testing patterns related to mutation testing http://mutation-testing-patterns.rtfd.io
