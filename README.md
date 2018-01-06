# From junior to senior

<img src="https://cdn.rawgit.com/KolesnichenkoDS/from-junior-to-senior/master/sicp.jpg"
     width="350" />

My study plan for going from junior to senior software developer (i. e. from level 1 to level 3 of the
[Programmer Competency Matrix](http://sijinjoseph.com/programmer-competency-matrix)). Inspired by
[Google Interview University](https://github.com/jwasham/google-interview-university).

This study plan attempts to cover a lot of topics related to math and theoretical computer science, but
it can miss some applied topics, like mobile or frontend development. Also this plan doesn't (and never
will) include something related to SEO, advertising, marketing etc.

## Usage

1. Fork this repo
2. Mark all items as undone
3. Add missing topics (optional)
4. Study!

## Table of contents

- [Calculus](#calculus)
- [Functional Analysis](#functional-analysis)
- [Geometry](#geometry)
  - [Analytic Geometry](#analytic-geometry)
- [Linear Algebra](#linear-algebra)
- [Mathematical Logic](#mathematical-logic)
- [Abstract Algebra](#abstract-algebra)
- [Category Theory](#category-theory)
- [Combinatorics and Probability](#combinatorics-and-probability)
- [Discrete Mathematics](#discrete-mathematics)
  - [Graph Theory](#graph-theory)
- [Type Theory](#type-theory)
- [Lambda Calculus](#lambda-calculus)
- [Pi Calculus](#pi-calculus)
- [Data Structures](#data-structures)
- [Algorithms](#algorithms)
  - [Basic Algorithms](#basic-algorithms)
    - [Sorting](#sorting)
  - [Complexity](#complexity)
- [Programming Languages](#programming-languages)
  - [Assembly](#assembly)
  - [C/C++](#cc)
  - [Haskell](#haskell)
  - [Rust](#rust)
- [Programming Paradigms](#programming-paradigms)
  - [Object-Oriented Programming](#object-oriented-programming)
  - [Functional Programming](#functional-programming)
  - [Logic Programming](#logic-programming)
  - [Actor Model](#actor-model)
- [Design Patterns](#design-patterns)
- [Domain-Driven Design](#domain-driven-design)
- [Computer Architecture](#computer-architecture)
- [Systems Programming](#systems-programming)
  - [Operating Systems](#operating-systems)
    - [Linux](#linux)
    - [Windows](#windows)
  - [Embedded Programming](#embedded-programming)
  - [Compilers and Interpreters](#compilers-and-interpreters)
    - [Compilers](#compilers)
    - [Interpreters](#interpreters)
    - [Garbage Collectors](#garbage-collectors)
- [Networks](#networks)
- [Web Development](#web-development)
  - [Server-side](#server-side)
  - [Client-side](#client-side)
- [Databases](#databases)
  - [SQL Databases](#sql-databases)
    - [SQL](#sql)
  - [NoSQL Databases](#nosql-databases)
- [Concurrent Programming](#concurrent-programming)
  - [POSIX Threads](#posix-threads)
  - [Green Threads](#green-threads)
  - [Coroutines](#coroutines)
  - [SIMD](#simd)
- [Security](#security)
  - [Cryptography](#cryptography)
  - [Web Applications Security](#web-applications-security)
- [Blockchain](#blockchain)
- [Testing](#testing)
  - [TDD](#tdd)
  - [BDD](#bdd)
- [Source Code Version Control](#source-code-version-control)
  - [Git](#git)
  - [Mercurial](#mercurial)
- [Build Automation](#build-automation)
- [See also](#see-also)
- [Resources](#resources)
- [Online Tools](#online-tools)

## Calculus

- :pencil: **Articles**
  - [x] [An Intuitive Introduction to Limits](https://betterexplained.com/articles/an-intuitive-introduction-to-limits) by Better Explained
- :book: **Books**
  - [ ] :ru: [Курс дифференциального и интегрального исчисления в 3 томах. Том 1](http://www.ozon.ru/context/detail/id/4577306/) by Grigorii Fichtenholz
  - [ ] :ru: [Курс дифференциального и интегрального исчисления в 3 томах. Том 2](http://www.ozon.ru/context/detail/id/4577307/) by Grigorii Fichtenholz
  - [ ] :ru: [Курс дифференциального и интегрального исчисления в 3 томах. Том 3](http://www.ozon.ru/context/detail/id/4577308/) by Grigorii Fichtenholz
  - [x] :ru: [Краткий курс Математического анализа](http://nuclphys.sinp.msu.ru/mathan/) by Lev Kudryavtsev
- :mortar_board: **Courses**
  - [Khan Academy](https://www.khanacademy.org/math/calculus-home)
    - [x] [Limits and Continuity](https://www.khanacademy.org/math/calculus-home/limits-and-continuity-calc)
    - [x] [Taking Derivatives](https://www.khanacademy.org/math/calculus-home/taking-derivatives-calc)
    - [x] [Derivative Applications](https://www.khanacademy.org/math/calculus-home/derivative-applications-calc)
    - [x] [Integration](https://www.khanacademy.org/math/calculus-home/integration-calc)
    - [x] [Integration Techniques](https://www.khanacademy.org/math/calculus-home/integration-techniques-calc)
    - [x] [Integration Applications](https://www.khanacademy.org/math/calculus-home/integration-applications-calc)
    
## Functional Analysis

- :pencil: **Articles**
  - [ ] [An Interactive Guide to the Fourier Transform](https://betterexplained.com/articles/an-interactive-guide-to-the-fourier-transform) by Better Explained
- :book: **Books**
  
## Geometry

### Analytic Geometry

- :mortar_board: **Courses**
  - [x] [Analytic Geometry](https://www.khanacademy.org/math/geometry-home/analytic-geometry-topic) by Khan Academy

## Linear Algebra

- :mortar_board: **Courses**
  - [Khan Academy](https://www.khanacademy.org/math/linear-algebra)
    - [x] [Vector and Spaces](https://www.khanacademy.org/math/linear-algebra/vectors-and-spaces)
    - [x] [Matrix Transformations](https://www.khanacademy.org/math/linear-algebra/matrix-transformations)
    - [x] [Alternate Coordinate Systems](https://www.khanacademy.org/math/linear-algebra/alternate-bases)

## Mathematical Logic

- :pencil: **Articles**
  - [x] [Sequent Calculus](https://ncatlab.org/nlab/show/sequent+calculus) by nLab
  - [x] [Linear Logic](https://ncatlab.org/nlab/show/linear+logic) by nLab
  - [ ] :ru: [Линейная логика (реферат по истории математики)](https://www.docme.ru/doc/925474/linejnaya-logika) by Alexandr Kharitonov
- :book: **Books**
  - [ ] [Linear Logic](http://www.cs.cmu.edu/~fp/courses/linear/handouts/linear.pdf) by Frank Pfenning
- :movie_camera: **Videos**
  - [ ] [Linear Logic is Broken](https://youtu.be/ljYX46pp7hw) by Cassandra Sparks

## Abstract Algebra

- :book: **Books**
  - [ ] [Algebra: Chapter 0](https://www.amazon.com/Algebra-Chapter-Graduate-Studies-Mathematics/dp/0821847813) by Paolo Aluffi

## Category Theory

- :book: **Books**
  - [ ] [Basic Category Theory for Computer Scientists](https://www.amazon.com/Category-Computer-Scientists-Foundations-Computing/dp/0262660717) by Benjamin C. Pierce
  - [ ] [Category Theory for Programmers](https://bartoszmilewski.com/2014/10/28/category-theory-for-programmers-the-preface/) by Bartosz Milewski

## Combinatorics and Probability

- :mortar_board: **Courses**
  - [ ] [Basic Theoretical Probability](https://www.khanacademy.org/math/statistics-probability/probability-library) by Khan Academy

## Discrete Mathematics

### Graph Theory

- :mortar_board: **Courses**
  - [ ] [Graph Theory](https://www.tutorialspoint.com/graph_theory/) by Tutorialspoint

## Type Theory

- :pencil: **Articles**
  - [ ] [On Regions and Linear Types](https://www.cs.princeton.edu/~dpw/papers/space.pdf) by David Walker and Kevin Watkins
  - [ ] [Linear Regions Are All You Need](http://www.ccs.neu.edu/home/amal/papers/linrgn.pdf) by Matthew Fluet, Greg Morrisett and Amal Ahmed
  - [ ] [Enriching an Effect Calculus with Linear Types](http://www.itu.dk/people/mogel/papers/ems.pdf) by Jeff Egger, Rasmus Ejlers Møgelberg and Alex Simpson
  - [ ] [Dependent Type Theory of Stateful Higher-Order Functions](http://ynot.cs.harvard.edu/papers/depstate.pdf) by Aleksandar Nanevski and Greg Morrisett
  - [ ] [The Pain Of Real Linear Types in Rust](https://gankro.github.io/blah/linear-rust/) by Alexis Beingessner
  - [ ] [Fundamentals of Session Types](https://www.di.fc.ul.pt/~vv/papers/vasconcelos_fundamental-sessions.pdf) by Vasco T. Vasconcelos
  - [ ] [A Gentle Introduction to Multiparty Asynchronous Session Types](http://mrg.doc.ic.ac.uk/publications/a-gentle-introduction-to-multiparty-asynchronous-session-types/paper.pdf) by Mario Coppo, Mariangiola Dezani-Ciancaglini, Luca Padovani and Nobuko Yoshida
- :book: **Books**
  - [ ] [Homotopy Type Theory](https://homotopytypetheory.org) by Vladimir Voevodsky
  - [ ] [Types and Programming Languages](https://www.amazon.com/Types-Programming-Languages-MIT-Press/dp/0262162091) by Benjamin C. Pierce
- :movie_camera: **Videos**
  - [x] [Linear and Dependent Types 1](https://youtu.be/5i3YDgQyIwE) by Neel Krishnaswami
  - [ ] [Linear and Dependent Types 2](https://youtu.be/2lPebyKMOug) by Neel Krishnaswami
  - [ ] [Linear and Dependent Types 3](https://youtu.be/e46nF6FJmtI) by Neel Krishnaswami
  - [ ] [Linear and Dependent Types 4](https://youtu.be/XWTqeVQJ91E) by Neel Krishnaswami
  - [ ] [Substructural Type Systems and Concurrent Programming 1](https://youtu.be/ZW-VWWa1o9g) by Frank Pfenning
  - [ ] [Substructural Type Systems and Concurrent Programming 2](https://youtu.be/kiQ5e1rhr9w) by Frank Pfenning
  - [ ] [Substructural Type Systems and Concurrent Programming 3](https://youtu.be/RytTifwjBiM) by Frank Pfenning
  - [ ] [Substructural Type Systems and Concurrent Programming 4](https://youtu.be/KY5aYhqGKdw) by Frank Pfenning
  - [ ] [Substructural Type Systems and Concurrent Programming 5](https://youtu.be/lJhixRjDiNE) by Frank Pfenning
  - [ ] [Linear Logic, Session Types and Deadlock-Freedom](https://youtu.be/R7pJDDNy--k) by Simon Gay
  
## Lambda Calculus
- :movie_camera: **Videos**
  - [x] :ru: [Лямбда-исчисление](https://youtu.be/7BPQ-gpXKt4) by Денис Москвин
  - [x] :ru: [Рекурсия и редукция](https://youtu.be/nyulPOcDLGM) by Денис Москвин
  - [x] :ru: [Просто типизированное лямбда-исчисление](https://youtu.be/S-mqZrmUUqU) by Денис Москвин

## Pi Calculus
- :pencil: **Articles**
  - [ ] [A compositional semantics for the reversible pi-calculus](https://hal-univ-diderot.archives-ouvertes.fr/hal-00840156/document) by Ioana Domnina Cristescu, Jean Krivine and Daniele Varacca
  - [ ] [Reversible Structures](http://www.cs.unibo.it/~laneve/papers/ReversibleStructures.pdf) by Luca Cardelli and Cosimo Laneve

## Data Structures

- :pencil: **Articles**
  - [ ] [Data Structures Basics](http://algosaur.us/data-structures-basics) by Algosaurus
  - [x] :ru: [Что такое хеш-таблицы и как они работают](https://ruhighload.com/post/%D0%A7%D1%82%D0%BE+%D1%82%D0%B0%D0%BA%D0%BE%D0%B5+%D1%85%D0%B5%D1%88-%D1%82%D0%B0%D0%B1%D0%BB%D0%B8%D1%86%D1%8B+%D0%B8+%D0%BA%D0%B0%D0%BA+%D0%BE%D0%BD%D0%B8+%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%D1%8E%D1%82) by RuHighload
- :mortar_board: **Courses**
  - [ ] [Data Structures](https://www.coursera.org/learn/data-structures) by UC San Diego and HSE

## Algorithms

- :book: **Books**
  - [ ] [The Art of Computer Programming](https://www.amazon.com/Computer-Programming-Volumes-1-4A-Boxed/dp/0321751043) by Donald E. Knuth
  - [ ] [Structure and Interpretation of Computer Programs](https://www.amazon.com/Structure-Interpretation-Computer-Programs-Engineering/dp/0262510871/ref=pd_sim_14_3?_encoding=UTF8&psc=1&refRID=261YMEZJ1FKVM8BHZZFH) by Harold Abelson, Gerald Jay Sussman and Julie Sussman

### Basic algorithms

#### Sorting

- :paperclip: **Cheat Sheets**
  - [Sorting Algorithms Animations](https://www.toptal.com/developers/sorting-algorithms) by Toptal
- :pencil: **Articles**
  - [ ] [Sorting Algorithms](https://betterexplained.com/articles/sorting-algorithms) by Better Explained

### Complexity

- :paperclip: **Cheat Sheets**
  - [Big-O Algorithm Complexity Cheat Sheet](http://bigocheatsheet.com/)
- :pencil: **Articles**
  - [ ] [Algorithmic Complexity](http://algosaur.us/algorithmic-complexity) by Algosaurus
  
## Programming Languages

- :zap: **Practice**
  - [Exercism](http://exercism.io)
  - [Codewars](https://codewars.com)

### Assembly

- :paperclip: **Cheat Sheets**
  - [armasm Reference Guide](http://infocenter.arm.com/help/topic/com.arm.doc.dui0802b/ARMCT_armasm_reference_guide_v6_01_DUI0802B_en.pdf)
  - [Intel and AT&T Syntax Comparison](http://www.imada.sdu.dk/Courses/DM18/Litteratur/IntelnATT.htm)
- :book: **Books**
  - [x] :ru: [Ассемблер в Linux для программистов C](https://ru.wikibooks.org/wiki/%D0%90%D1%81%D1%81%D0%B5%D0%BC%D0%B1%D0%BB%D0%B5%D1%80_%D0%B2_Linux_%D0%B4%D0%BB%D1%8F_%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%81%D1%82%D0%BE%D0%B2_C) by Wikibooks

### C/C++

- :paperclip: **Cheat Sheets**
  - ANSI C Standard
    ([C99](http://www.open-std.org/jtc1/sc22/wg14/www/docs/n1256.pdf),
     [C11](http://www.open-std.org/jtc1/sc22/wg14/www/docs/n1570.pdf))
- :pencil: **Articles**
  - [ ] [What Every C Programmer Should Know About Undefined Behaviour](http://blog.llvm.org/2011/05/what-every-c-programmer-should-know.html) by Chris Lattner
- :book: **Books**
  - [ ] [The C Programming Language](https://www.amazon.com/Programming-Language-Brian-W-Kernighan/dp/0131103628) by Brian W. Kernighan and Dennis M. Ritchie
  - [ ] [C Primer Plus](https://www.amazon.com/C-Primer-Plus-Developers-Library-ebook/dp/B00GWLPX76) by Stephen Prata
  - [ ] [C Programming Absolute Beginner's Guide](https://www.amazon.com/Programming-Absolute-Beginners-Guide-3rd/dp/0789751984) by Greg Perry and Dean Miller
  - [ ] [Object-Oriented C](https://www.cs.rit.edu/~ats/books/ooc.pdf)
  - [ ] [The C++ Programming Language](https://www.amazon.com/C-Programming-Language-4th/dp/0321563840) by Bjarne Stroustrup
  - [ ] [C++ Primer Plus](https://www.amazon.com/Primer-Plus-6th-Developers-Library/dp/0321776402asv) by Stephen Prata
- :movie_camera: **Videos**
  - [ ] :ru: [Использование C++ для низкоуровневой платформозависимой разработки](https://youtu.be/0K0I5uiX_Uk) by Kirill Lashkevich
  - [ ] :ru: [Модель памяти C++](https://youtu.be/SIZmLPtcZiE) by Andrey Yankovsky

### Java

- :paperclip: **Cheat Sheets**
  - [JVM Anatomy Park](https://shipilev.net/jvm-anatomy-park/) by Alexey Shipilev

### Haskell

- :book: **Books**
  - [ ] :ru: [Haskell Book](https://anton-k.github.io/ru-haskell-book/book/home.html) by Anton Kholomiov
  
### Rust

- :pencil: **Articles**
  - [ ] [Wrapper Types in Rust: Choosing Your Guarantees](https://manishearth.github.io/blog/2015/05/27/wrapper-types-in-rust-choosing-your-guarantees/) by Manish Goregaokar
- :book: **Books**
  - [ ] [The Rustonomicon](https://doc.rust-lang.org/nomicon/)

## Programming Paradigms

### Object-Oriented Programming

- :pencil: **Articles**
  - [ ] [Retracing Original Object-Oriented Programming](https://medium.com/skyfishtech/retracing-original-object-oriented-programming-f8b689c4ce50) by A. T. Herlangga
- :book: **Books**
  - [ ] [A Theory of Objects](https://www.amazon.com/Theory-Objects-Monographs-Computer-Science/dp/0387947752) by M. Abadi, L. Cardelli
- :book: **Books**
  - [ ] [Object Thinking](https://www.amazon.com/Object-Thinking-Developer-Reference-David/dp/0735619654) by David West

### Functional Programming

- :pencil: **Articles**
  - [x] [Transducers in Clojure](https://clojure.org/reference/transducers)
  - [ ] [The ReaderT Design Pattern](https://www.fpcomplete.com/blog/2017/06/readert-design-pattern) by FP Complete
  - [ ] [The RIO Monad](https://www.fpcomplete.com/blog/2017/07/the-rio-monad) by FP Complete
- :movie_camera: **Videos**
  - [x] [Immutable data structures for functional JS](https://youtu.be/Wo0qiGPSV-s) by Anjana Vakil
  
### Actor Model

- :pencil: **Articles**
  - [ ] [Why has the actor model not succeeded?](http://www.doc.ic.ac.uk/~nd/surprise_97/journal/vol2/pjm2/) by P. Mackay
- :book: **Books**
  - [ ] [Reactive Messaging Patterns with the Actor Model: Applications and Integration in Scala and Akka](https://www.amazon.com/Reactive-Messaging-Patterns-Actor-Model/dp/0133846830) by Vaughn Vernon

## Domain-Driven Design

- :book: **Books**
  - [ ] [Domain-Driven Design: Tackling the Complexity at the Heart of Software](https://www.amazon.com/dp/0321125215/ref=cm_sw_su_dp) by Eric Evans
  - [ ] [Implementing Domain-Driven Design](https://vaughnvernon.co/?page_id=168#iddd) by Vaughn Vernon
  - [ ] [Domain-Driven Design Reference](http://domainlanguage.com/wp-content/uploads/2016/05/DDD_Reference_2015-03.pdf) by Eric Evans

## Computer Architecture

- :paperclip: **Cheat Sheets**
  - [Intel Architecture Instruction Set Extensions Programming Reference](https://software.intel.com/sites/default/files/managed/c5/15/architecture-instruction-set-extensions-programming-reference.pdf)
  - [Intel 64 and IA-32 Architectures Optimization Reference Manual](https://www-ssl.intel.com/content/dam/www/public/us/en/documents/manuals/64-ia-32-architectures-optimization-manual.pdf)
- :pencil: **Articles**
  - [ ] [What Every Programmer Should Know About Memory](https://www.akkadia.org/drepper/cpumemory.pdf) by Ulrich Drepper
- :mortar_board: **Courses**
  - [ ] [Computer Architecture](https://www.coursera.org/learn/comparch) by Princeton University

## Systems Programming

### Operating Systems

- :pencil: **Articles**
  - [ ] [Writing an OS in Rust](http://os.phil-opp.com/) by Philipp Oppermann
- :book: **Books**
  - [ ] [Modern Operating Systems](https://www.amazon.com/Modern-Operating-Systems-Andrew-Tanenbaum/dp/013359162X) by Andrew S. Tanenbaum
  - [ ] [IntermezzOS](https://intermezzos.github.io/book/)
  - [ ] [The little book about OS development](https://littleosbook.github.io/) by Erik Helin and Adam Renberg
  
#### Linux

- :pencil: **Articles**
  - [ ] [Writing Device Drivers in Linux: A Brief Tutorial](http://freesoftwaremagazine.com/articles/drivers_linux/) by Free Software Magazine
  
- :book: **Books**
  - [ ] [Linux From Scratch](http://www.linuxfromscratch.org/) by Gerard Beekmans
  - [ ] [The Linux Kernel Module Programming Guide](https://www.amazon.com/Linux-Kernel-Module-Programming-Guide/dp/1441418865) by Peter Jay Salzman

### Embedded Programming

- :pencil: **Articles**
  - [ ] [Rust your ARM microcontroller!](http://blog.japaric.io/quickstart/) by Jorge Aparicio
  - [ ] [Fearless concurrency in your microcontroller](http://blog.japaric.io/fearless-concurrency/) by Jorge Aparicio
  - [ ] [Understanding the STM32F0's GPIO part 1](http://hertaville.com/stm32f0-gpio-tutorial-part-1.html) by Hertaville.com
  - [ ] [Understanding the STM32F0's GPIO part 2](http://hertaville.com/stm32f0-gpio-tutorial-part-2.html) by Hertaville.com

- :book: **Books**
  - [ ] [Discover the world of microcontrollers through Rust!](https://github.com/japaric/discovery) by Jorge Aparicio

### Compilers and Interpreters

#### Compilers

- :book: **Books**
  - [ ] [Write You a Haskell](http://dev.stephendiehl.com/fun/) by Stephen Diehl

#### Interpreters

- :book: **Books**
  - [ ] [Crafting Interpreters](http://www.craftinginterpreters.com/) by Bob Nystorm
  - [ ] [Beautiful Racket](http://beautifulracket.com/) by Matthew Butterick
  - [ ] [Write Yourself a Scheme in 48 Hours](https://en.wikibooks.org/wiki/Write_Yourself_a_Scheme_in_48_Hours) by Jonathan Tang

#### Garbage Collectors

- :pencil: **Articles**
  - [ ] [Garbage Collection with LLVM](http://llvm.org/docs/GarbageCollection.html)
  - [ ] [JVM Anatony Park: GC Design and Pauses](https://shipilev.net/jvm-anatomy-park/3-gc-design-and-pauses/) by Alexey Shipilev
  - [ ] [Immix: A Mark-Region Garbage Collector with Space Efficiency, Fast Collection, and Mutator Performance](http://users.cecs.anu.edu.au/~steveb/pubs/papers/immix-pldi-2008.pdf) by Stephen M. Blackburn and Kathryn S. McKinley
  - [ ] [Rust as a Language for High Performance GC Implementation](http://ts.data61.csiro.au/publications/nictaabstracts/9260.pdf)
  - [ ] [Designing a GC in Rust](https://manishearth.github.io/blog/2015/09/01/designing-a-gc-in-rust/) by Manish Goregaokar
- :book: **Books**
  - [ ] [The Garbage Collection Handbook](http://gchandbook.org/)

## Networks

- :book: **Books**
  - [ ] [Computer Networks](https://www.amazon.com/Computer-Networks-Tanenbaum-International-Economy/dp/9332518742) by Andrew S. Tanenbaum

## Web Development

### Server-side

- :mortar_board: **Courses**
  - [Codecademy](https://www.codecademy.com)
    - [ ] [Learn Rails](https://www.codecademy.com/courses/learn-rails)
    - [ ] [Ruby on Rails Authentification](https://www.codecademy.com/courses/rails-auth)

### Client-side

- :pencil: **Articles**
  - 
- :mortar_board: **Courses**
  - [Codecademy](https://www.codecademy.com)
    - [x] [Learn AngularJS](https://www.codecademy.com/courses/learn-angularjs)
    - [x] [Learn ReactJS: Part I](https://www.codecademy.com/courses/react-101)
    - [x] [Learn ReactJS: Part II](https://www.codecademy.com/courses/react-102)

## Databases

### SQL Databases

- :mortar_board: **Courses**
  - [Codecademy](https://www.codecademy.com)
    - [ ] [Learn SQL](https://www.codecademy.com/courses/learn-sql)
    - [ ] [SQL: Table Transformation](https://www.codecademy.com/courses/sql-table-transformation)
    - [ ] [SQL: Analyzing Business Metrics](https://www.codecademy.com/courses/sql-analyzing-business-metrics)

## Concurrent Programming

### POSIX Threads

- :book: **Books**
  - [ ] [Programming with POSIX Threads](https://www.amazon.com/Programming-POSIX-Threads-David-Butenhof/dp/0201633922) by David R. Butenhof
  
### SIMD

- :paperclip: **Cheat Sheets**
  - [Intel Intrinsics Guide](https://software.intel.com/sites/landingpage/IntrinsicsGuide/)

## Security

### Cryptography

- :pencil: **Articles**
  - [ ] [Cryptographic Hashing in Haskell](https://www.fpcomplete.com/blog/2017/09/cryptographic-hashing-haskell) by FP Complete
- :mortar_board: **Courses**
  - [ ] [Journey Into Cryptography](https://www.khanacademy.org/computing/computer-science/cryptography) by Khan Academy

### Web Applications Security

- :mortar_board: **Courses**
  - [ ] [Web Application Exploits and Defenses](https://google-gruyere.appspot.com/)
  - [ ] [Hacksplaining](https://www.hacksplaining.com/)
  - [ ] [XSS Game](https://xss-game.appspot.com/)
  

## Blockchain

- :paperclip: **Cheat Sheets**
  - [Exonum Documentation](https://exonum.com/doc/)

## See also
- [Teach Yourself Programming in Ten Years](http://norvig.com/21-days.html)
- [Teach Yourself Computer Science](https://teachyourselfcs.com/)
- [Become a Programmer, Motherfucker](http://programming-motherfucker.com/become.html)
- [Project Based Learning](https://github.com/tuvttran/project-based-learning)
- [Open Source Society University](https://github.com/open-source-society/computer-science)
- [Free Programming Books](https://github.com/vhf/free-programming-books)
- [Google Interview University](https://github.com/jwasham/google-interview-university)
- [Machine Learning for Software Engineers](https://github.com/ZuzooVn/machine-learning-for-software-engineers)
- [Awesome Compilers](http://aalhour.com/awesome-compilers)
- [What happens when...](https://github.com/alex/what-happens-when)

## Resources

You can find more courses, articles, videos etc here:

- [Coursera](https://www.coursera.org)
- [Khan Academy](https://www.khanacademy.org)
- [Codecademy](https://www.codecademy.com)
- [Better Explained](https://betterexplained.com)
- [Learn X in Y minutes](https://learnxinyminutes.com)
- :ru: [Викиконспекты ИТМО](http://neerc.ifmo.ru/wiki)

Online documentation:

- [StackOverflow Documentation](http://stackoverflow.com/documentation)
- [DevDocs](http://devdocs.io)

[Wikimedia Foundation](https://www.wikimedia.org/) projects:

- [Wikipedia](https://www.wikipedia.org)
- [Wikibooks](https://www.wikibooks.org)
- [Wikiversity](https://www.wikiversity.org)

Forums, Q&A:

- [StackOverflow](http://stackoverflow.com)
- :ru: [Toster](https://toster.ru)
- :ru: [dxdy](http://dxdy.ru)

## Online Tools

- Math
  - [Wolfram Alpha](http://www.wolframalpha.com/) — a computational knowledge engine
  - [Symbolab](https://www.symbolab.com/) — a step by step calculator
- Coding
  - [Cloud9](https://c9.io/) — a development environment in the cloud
  - [Codepen](http://codepen.io/) — a playground for the front end side of the web
  - [Compiler Explorer](https://godbolt.org) — an interactive online C, C++, D, Rust and Go compiler
  - [Ideone](http://ideone.com/) — a free online IDE, compiler and debugging tool
  - [Repl.It](https://repl.it/) — a REPL, compiler & IDE
  - [RunKit](https://runkit.com/) — a Node prototyping tool
  - [Reepl](http://jaredforsyth.com/reepl/) — an online ClojureScript REPL
