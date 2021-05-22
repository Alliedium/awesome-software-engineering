# Awesome Software Engineering
A curated list of awesome software engineering resources.



## Quick links to sections in this page

| | | |
|-|-|-|
|[🔍 Fundamentals](#fundamentals) |[🌀 Common Mistakes](#common-mistakes) | [🎁 Code Review](#code-review)|
|[⚔  Data Structures and Algos](#data-structures-and-algos) |[💰 Common principles](#common-principles) | [:loop: Design Patterns](#design-patterns)|
|[:bath:  Clean Code](#clean-code) |[:flashlight: Clean Architecture](#clean-architecture) | [:wrench: Refactoring](#refactoring)|
|[🔏 UML & noUML](#uml--nouml) | [📜 Software Development Methodologies](#software-development-methodologies)|[:mortar_board:OOP](#oop)|
|[🏁 Debugging](#debugging)|[💪 Testing](#testing)|[🤖 IDEs](#ides)|
| [🧵 Security](#security) | [🏷️ Programming Languages](#programming-languages) |[🗞️ Databases](#databases) |
| [📡 Java](#java)| [🗺️ Python](#python) | [📥 JavaScript](#javascript) |
| [:snail: Rust](#rust)| [:microscope: Julia](#julia) |  |

| | |
|-|-|
|[:red_circle: REST API](#rest-api)  | 🧩 [GraphQL](#graphql)|

| | | |
|-|-|-|
| [📓 Linux](#linux) | [:grey_question: Windows](#windows) | [:sparkles: Proxmox](#proxmox) |
| [📊 SSH](#ssh) | [:bookmark: Git](#git) |[:fax: Vim](#vim) |
| [:violin: LibreOffice](#libreoffice) | [:gem: Kdenlive](#kdenlive) |[ :black_nib:GIMP](#gimp) |
| [:books: ZFS](#zfs) | [:golf: LVM](#lvm) | [:musical_keyboard: tmux](#tmux) |
| [🧮 Ansible](#ansible)| [ [:leaves: Docker](#docker) | [:milky_way: Kubernetes](#kubernetes)|

| | |
|-|-|
|[🔐 KeePassXC](#KeePassXC)  |  [🗿 iptables](#iptables)|



## Fundamentals

### OOP
1. [:film_strip: \[rus\] What is OOP by FoxMinded](https://www.youtube.com/watch?v=M58eiYbM6AE)
2. [:film_strip: \[rus\] OOP: Incapsulation explained by FoxMinded](https://www.youtube.com/watch?v=EvGi6XDgV7wф)
3. [:film_strip: \[rus\] OOP: Inheritance explained by FoxMinded](https://www.youtube.com/watch?v=eI0XzQw3V0Q)
4. [:film_strip: \[rus\] OOP: Polymorphism by explained by FoxMinded](https://www.youtube.com/watch?v=Ay_GwOQWPs8)
5. [:film_strip: \[eng\] OOP explained by Mosh](https://www.youtube.com/watch?v=pTB0EiLXUC8)
6. [:scroll: \[eng\] Why OOP is not a silver bullet](https://medium.com/@cscalfani/goodbye-object-oriented-programming-a59cda4c0e53)
7. [:scroll: \[eng\] Inheritance vs Composition. Which should you use?](https://medium.com/better-programming/inheritance-vs-composition-2fa0cdd2f939) 

### Common mistakes
1. [:film_strip: \[rus\] 7 Common mistakes of Junior developers](https://www.youtube.com/watch?v=oH2RJNILkLs)
2. [:film_strip: \[eng\] 5 Programming Anti-patterns for Beginners](https://www.youtube.com/watch?v=lQ_rGCL17EE)
3. [:scroll: \[eng\] Anti-patterns and Code Smells](https://itnext.io/anti-patterns-and-code-smells-46ba1bbdef6d)
4. [:film_strip: \[rus\] Why it is bad to return NULL in Java](https://www.youtube.com/watch?v=QwycPnpp6uQ)
5. [:scroll: \[eng\] The Anti Pattern of Getters And Setters by Ajeng Sugiarti](https://medium.com/@ajengs/the-anti-pattern-of-getters-and-setters-22011e0123e9)
6. [:scroll: \[eng\] Avoid getters and setters whenever possible by scottshipp](https://dev.to/scottshipp/avoid-getters-and-setters-whenever-possible-c8m)
7. [:scroll: \[eng\] Software Engineering Anti-patterns catalogue in Wikipedia](https://en.wikipedia.org/wiki/Anti-pattern#Software_engineering)

### Code Review
1. [:film_strip: \[eng\] How to Review Someone Else's Code by Codecademy](https://www.youtube.com/watch?v=TlXy_i27N3w)
2. [:film_strip: \[eng\] Code Review Best Practices by JetBrains](https://www.youtube.com/watch?v=a9_0UUUNt-Y)

### Code Style 
1. [:scroll: \[rus\] Code style as a standard of software development](https://habr.com/ru/company/manychat/blog/468953/)

### Data Structures and Algos
1. [:film_strip: \[eng\] Data Structures and Algorithms by Mosh](https://www.youtube.com/watch?v=BBpAmxU_NQo)

### Common principles
1. [:film_strip: \[rus\] Problem Domain Decomposition by FoxMinded](https://www.youtube.com/watch?v=Qku0VoaZ-gE)
2. [:film_strip: \[rus\] DRY principle](https://www.youtube.com/watch?v=NWemqNMCesQ)
3. [:film_strip: \[rus\] DRY, KISS, YAGNI](https://www.youtube.com/watch?v=dz6ZsIcxoo0)
4. [:film_strip: \[rus\] SOLID principles](https://www.youtube.com/playlist?list=PLmqFxxywkatQNWLG1IZYUhKoQrnuZHqaK)
5. [:film_strip: \[rus\] SOLID principles & Architecture: a lecture from FPMI](https://www.youtube.com/watch?v=XjGbg-N4sQc)
6. [:film_strip: \[eng\] Frameworks & Inversion of Control](https://www.youtube.com/watch?v=vFzP2SaMyA0)
7. [:film_strip: \[eng\] Dependency Injection & Inversion of Control](https://www.youtube.com/watch?v=EPv9-cHEmQw)
8. [:scroll: \[eng\] Dependency Injection vs Inversion of Control](https://levelup.gitconnected.com/dependency-injection-vs-inversion-of-control-e8a9fcc7d9f7)
9. [:scroll: \[rus\] Low Coupling & High Cohesion by German Gorelkin](https://medium.com/german-gorelkin/low-coupling-high-cohesion-d36369fb1be9)
10. [:scroll: \[eng\] Low Coupling & High Cohesion by Ammar Verbi Merakli](https://medium.com/the-innovation/pure-functions-high-cohesion-low-coupling-174b0a47ef24)
11. [:scroll: \[eng\] Demeter's Law: Don't talk to strangers by Carlos Caballero](https://medium.com/better-programming/demeters-law-don-t-talk-to-strangers-87bb4af11694)
12. [:scroll: \[eng\] GRASP Design Principles by Krzysztof Kwieciński](https://medium.com/@k.d.kwiecinski/grasp-design-principles-de98cae2196c)
13. [:scroll: \[eng\] What are General Responsibility Assignment Software Patterns? by Jakub Kapuscik](https://levelup.gitconnected.com/what-are-general-responsibility-assignment-software-patterns-6ad9635a44da)
14. [:scroll: \[eng\] Object-oriented design: GRASP patterns by J.Serrat](http://www.cvc.uab.es/shared/teach/a21291/temes/object_oriented_design/slides/handouts/GRASP_patterns.pdf)
15. [:scroll: \[eng\] ADVANCED SOFTWARE DESIGN: GRASP, SOLID, YAGNI, DRY, KISS, OTHER PRINCIPLES BY Dave Clarke](http://www.it.uu.se/edu/course/homepage/asd/ht14/Lecture%204.pdf)


### Design Patterns
1. [:film_strip: \[eng\] Design Patterns by Mosh](https://www.youtube.com/watch?v=NU_1StN5Tkk)
2. :book: Design Patterns: Elements of Reusable Object-Oriented Software, Erich Gamma, Richard Helm, Ralph Johnson, John Vlissides
3. [:film_strip: \[rus\] Design patterns (brief)](https://www.youtube.com/playlist?list=PLmqFxxywkatSzlcVEJTsMqZ1ObLO6vqCe)
4. [:film_strip: \[rus\] Design patterns (full)](https://www.youtube.com/playlist?list=PLmqFxxywkatStbd9hdzVOS1hZa9dc56k4)
5. [:scroll: \[eng\] Java Design Patterns - online catalog](https://java-design-patterns.com/patterns/observer/)
6. [:scroll: \[eng\] The Builder pattern vs Java syntax](https://bsideup.github.io/posts/builders_vs_java/)

### Clean Architecture
1. :book: Clean Architecture, A Craftsman's Guide to Software Structure And Design, Robert C. Martin
2. [:film_strip: \[rus\] SOLID principles & Architecture: a lecture from FPMI](https://www.youtube.com/watch?v=XjGbg-N4sQc)

### Clean Code
1. [:film_strip: \[rus\] Clean Code lecture by FoxMinded](https://www.youtube.com/playlist?list=PLmqFxxywkatSQoLnnkh7-XjIcGdmo28aJ)
2. :book: Clean Code: A Handbook of Agile Software Craftsmanship,Robert C. Martin

### Refactoring
1. :book: Refactoring: Improving the Design of Existing Code, Martin Fowler, Kent Beck, 2st edition
2. [:film_strip: \[rus\] Refactoring lectures by FoxMinded](https://www.youtube.com/playlist?list=PLmqFxxywkatR5zj5M4WdUyyKyLoJSZZrQ)
3. [:scroll: \[eng\] The Art of Refactoring: 5 Tips to Write Better Code](https://medium.com/better-programming/the-art-of-refactoring-5-tips-to-write-better-code-3bc1f6f7689)
4. [:scroll: \[eng\] Code Refactoring Best Practices: When (and When Not) to Do It](https://www.altexsoft.com/blog/engineering/code-refactoring-best-practices-when-and-when-not-to-do-it/)

## UML & noUML

1. [:film_strip: \[eng\] A brief UML tutorial by Lucidchart](https://www.youtube.com/playlist?list=PLUoebdZqEHTxNC7hWPPwLsBmWI0KEhZOd)
2. [:film_strip: \[eng\] A detailed UML tutorial by Derek Banas](https://www.youtube.com/playlist?list=PLGLfVvz_LVvQ5G-LdJ8RLqe-ndo7QITYc)
3. [:scroll: \[eng\] noUML explained, UML criticism by Vladimir Frolov, part1](https://medium.com/@volodymyrfrolov/nouml-afbb7f07f369)
4. [:scroll: \[eng\] noUML explained by Vladimir Frolov, part2](https://medium.com/@volodymyrfrolov/nouml-2-9734a2746258)

## Software Development Methodologies
1. [:film_strip: \[rus\] Who is who in Software Development: Developer, QA, BA, PM - who are those people? by FoxMinded](https://www.youtube.com/watch?v=OHPPpRkryfU)
2. [:film_strip: \[rus\] Phases](https://www.youtube.com/watch?v=ktBw6RZhji0)
3. [:film_strip: \[rus\] Methodologies](https://www.youtube.com/watch?v=xmJINdHGucw)

## Debugging
1. [:film_strip: \[rus\] Debugging, lecture from FPMI, part1](https://www.youtube.com/watch?v=BnTUDLRdjmM&list=PL4_hYwCyhAvaTVSzXsvFQlb-FmNqUNkPT)
2. [:film_strip: \[rus\] Debugging, lecture from FPMI, part2](https://www.youtube.com/watch?v=YNEdqUwtS4s&list=PL4_hYwCyhAvaTVSzXsvFQlb-FmNqUNkPT)
3. [:scroll: \[eng\] Debugging tips](https://jonskeet.uk/csharp/debugging.html)
4. [:scroll: \[eng\] 10 Debugging Tips for Beginners: How to Troubleshoot and Fix Your Code Without Pulling Your Hair Out By Hartley Brody](https://blog.hartleybrody.com/debugging-code-beginner/)

## Testing
1. [:film_strip: \[rus\] Unit Testing in Software Development](https://www.youtube.com/watch?v=KAny2OSYY3Y&list=PLmqFxxywkatQzkUy9qSpY2aaWaY6kZbD4)
2. [:film_strip: \[eng\] TTD vs BDD 1](https://www.youtube.com/watch?v=4QFYTQy47yA)
3. [:film_strip: \[eng\] TTD vs BDD 2](https://www.youtube.com/watch?v=fsSMuqIpu_c)
4. [:scroll: \[eng\] Unit Tests vs Functional Tests](https://medium.com/javascript-scene/behavior-driven-development-bdd-and-functional-testing-62084ad7f1f2)
5. [:film_strip: \[eng\] TTD crash course](https://www.youtube.com/watch?v=z6gOPonp2t0)
6. [:film_strip: \[eng\] BDD](https://www.youtube.com/watch?v=o4Y--AOoh9k)

### TTD in Java
1. Go to "TestNG" and "Mockito" subsections below under "Java Frameworks" section.

### BDD in Java
1. Go to "Serenity BDD" subsection below under "Java Frameworks" section.

### TTD in JavaScript
1. Go to "Jest" subsection below under "Java Script Frameworks" section.
2. [:film_strip: \[eng\] React Unit Testing](https://www.youtube.com/watch?v=3e1GHCA3GP0)

# IDEs
## IntelliJ Idea
1. [:film_strip: \[eng\] IntelliJ Idea Full Course by Amigoscode](https://www.youtube.com/watch?v=yefmcX57Eyg)

## Linux

1. [:film_strip: \[eng\] 6 Things to Know When Switching to Linux from Windows by Chris Titus](https://www.youtube.com/watch?v=wcdquhB6hT8)
2. [:film_strip: \[eng\] 6 Mistakes New Linux Users Make by Chris Titus](https://www.youtube.com/watch?v=mkrN4uAcDGk)
3. [:film_strip: \[rus\] Unix philosophy by unixway](https://www.youtube.com/watch?v=ExmBIpgM0kI)
4. [:film_strip: \[eng\] 5 Things I Hate About Linux by Chris Titus](https://www.youtube.com/watch?v=rb46F24HJM4)

### Linux Distributions
1. [:film_strip: \[eng\] Which Linux Distribution? | Understanding Linux Distros by Chris Titus](https://www.youtube.com/watch?v=DKFnqAtEOvc)
2. [:film_strip: \[eng\] How to Choose a Linux Distribution by Chris Titus](https://www.youtube.com/watch?v=iox7fr7p5Hc)
3. [:film_strip: \[eng\] Debian vs Arch by Chris Titus](https://www.youtube.com/watch?v=gtdYBc3p5Kw)
4. [:film_strip: \[eng\] Why Ubuntu is the Devil and Why So Many No Longer Use It by Chris Titus](https://www.youtube.com/watch?v=L7uL50zVZJA)

### Command line
1. [:film_strip: \[eng\] 15 Useful Linux Commands Every Linux User Needs | Learning Terminal Part 1](https://www.youtube.com/watch?v=XK81cfvrElg)
2. [:film_strip: \[eng\] 15 Useful Linux Commands Every Linux User Needs | Learning Terminal Part 2](https://www.youtube.com/watch?v=kVlkgiwiY6w)
3. [:film_strip: \[eng\] Bash tutorial](https://www.youtube.com/watch?v=oxuRxtrO2Ag)
4. [:scroll: \[eng\] zsh+OhMyZsh+fzf+powerlevel10k: Your terminal can be much, MUCH more productive by Ivan](https://medium.com/@ivanaugustobd/your-terminal-can-be-much-much-more-productive-5256424658e8)
5. [:scroll: \[eng\] fzf: Why you should be using fzf, the command line fuzzy finder by Alexey Samoshkin](https://medium.com/free-code-camp/fzf-a-command-line-fuzzy-finder-missing-demo-a7de312403ff)

### Tips & Tricks
1. [:scroll: \[eng\] Awesome Linux Configuration Scripts by Alliedium](https://github.com/Alliedium/awesome-linux-config)
2. [:film_strip: \[eng\] Git Bare Repository - A Better Way To Manage Dotfiles by DistroTube](https://www.youtube.com/watch?v=tBoLDpTWVOM) 

### Linux Utilities
1. [:film_strip: \[eng\] Linux Apps I Use Daily by Chris Titus](https://www.youtube.com/watch?v=4R0uqG4NXPA)
2. [:film_strip: \[eng\] Linux Apps I Use At Work by Chris Titus](https://www.youtube.com/watch?v=_XYSyKI3cr0)
   
#### tmux
1. [:film_strip: \[rus\] Console Utility tmux by unixway](https://www.youtube.com/watch?v=J67U2NKfszM)

### Arch Linux, Manjaro

1. [:film_strip: \[rus\] Arch Linux basics](https://www.youtube.com/watch?v=KTSlwGlviBE)
2. [:film_strip: \[rus\] Arch Linux pacman](https://www.youtube.com/watch?v=qSdu6Mqgur4)
3. [:film_strip: \[rus\] Arch Linux AUR](https://www.youtube.com/watch?v=kT1NCH45XdI)
4. [:film_strip: \[rus\] Arch Linux vs Manjaro](https://www.youtube.com/watch?v=8pGmUMZs_Do)

### Proxmox
1. [:film_strip: \[eng\] Virtualize Everything! - Proxmox Install Tutorial by Craft Computing](https://www.youtube.com/watch?v=azORbxrItOo)
2. [:film_strip: \[eng\] Proxmox VE 6.0 Beginner Tutorial - Installing Proxmox & Creating a virtual machine by Proxmox HHS](https://www.youtube.com/watch?v=I-e1_CTa4s0)
3. [:film_strip: \[eng\] Virtualize Windows 10 with Proxmox VE by Techno Tim](https://www.youtube.com/watch?v=6c-6xBkD2J4)
4. [:film_strip: \[rus\] Proxmox tutorial by realmanual](https://www.youtube.com/playlist?list=PLEFo-qGWcO2bIGEy7HbLX2nWfhVj3prmL)

### LVM
1. [:film_strip: \[rus\] LVM: Theory and practice by unixway](https://www.youtube.com/watch?v=QgUZrLcmJT8)

### SSH 
1. [:film_strip: \[rus\] OpenSSH basics](https://www.youtube.com/watch?v=ZzIF43ZeQrc)
2. [:film_strip: \[eng\] SSH config basics](https://www.youtube.com/watch?v=gZx9yCbQg50)

### Linux Filesystems
1. [:film_strip: \[eng\] File Systems | Which One is the Best? ZFS, BTRFS, or EXT4 by Chris Titus](https://www.youtube.com/watch?v=HdEozE2gN9I)

#### ZFS
1. [:film_strip: \[eng\] What Is ZFS?: A Brief Primer by Level1Linux](https://www.youtube.com/watch?v=lsFDp-W1Ks0)
2. [:film_strip: \[rus\] ZFS filesystem by unixway](https://www.youtube.com/playlist?list=PLsMIccp52YRvsLuZ6ed-Ytjv1HfpEC30k)
   

### Desktop Environments
#### KDE
1. [:film_strip: \[eng\] How to Customize KDE | KDE Customization by Chris Titus](https://www.youtube.com/watch?v=nRtyFtpf5yU)
2. [:film_strip: \[eng\] KDE is Slow !?! | Disable Baloo File Indexer by Chris Titus](https://www.youtube.com/watch?v=B42AmZlfDt8)

### Image Editing
#### GIMP
1. [:film_strip: \[eng\] GIMP vs Photoshop | How to Optimize Your Workflow by Chris Titus](https://www.youtube.com/watch?v=X4ZRJnAhmeU)

### Video Editing
#### Kdenlive
1. [:film_strip: \[eng\] Kdenlive Tutorial 2019 - Beginner Basics by Victoriano de Jesus](https://www.youtube.com/watch?v=7N3rXT_5f_I)
2. [:film_strip: \[eng\] 2020 Kdenlive Video Tutorials by Victoriano de Jesus](https://www.youtube.com/watch?v=nqifJqeiXu0&list=PLnJFu6D59R6L18UGQG4VNE_VIi40v9-Qt)
3. [:film_strip: \[eng\] Kdenlive Cinematic Title Animation by makinars](https://www.youtube.com/watch?v=wYlGOKXvuco)

### Text Editing
#### Vim
1. [:film_strip: \[eng\] Vim Basics in 8 Minutes by tutorialLinux](https://www.youtube.com/watch?v=ggSyF1SVFr4)

### LibreOffice
1. [:film_strip: \[eng\] Microsoft Office vs LibreOffice | How to Make the Change by Chris Titus](https://www.youtube.com/watch?v=I0jeYe8iNWo)

## Windows
1. [:film_strip: \[eng\] 17 Reasons Why I Do Not Use Windows 10 by Chris Titus](https://www.youtube.com/watch?v=TMeeryVlGAY)
2. [:film_strip: \[eng\] Speed Up Windows 10 in 2020 by Chris Titus](https://www.youtube.com/watch?v=8E6OT_QcHaU)


## Source Control  

### Git

1. [:film_strip: \[eng\] Git Tutorial - Learn Git in 1 Hour by Mosh](https://www.youtube.com/watch?v=8JJ101D3knE)
2. [:film_strip: \[rus\] Git Basic Training](https://www.youtube.com/playlist?list=PLsMIccp52YRtH-uTcqPf5H1RtNN_swNc8)
3. [:scroll: \[eng\] Awesome Git Exerises by Alliedium](awesome-git-exercises.md)
4. [:scroll: \[eng\] Git exercies online by fracz](https://gitexercises.fracz.com)

## Security
### KeePassXC
1. [:film_strip: \[eng\] Introduction to KeePassXC](https://www.youtube.com/watch?v=_qRLJyhMNpw)

### iptables
1. [:film_strip: \[eng\] iptables: getting started](https://www.youtube.com/watch?v=qPEA6J9pjG8)
2. [:film_strip: \[rus\] Iptables detailed tutorial](https://www.youtube.com/playlist?list=PLsMIccp52YRsuYa7QOZIy7OsnaIyQZB7_)

## Databases
### SQL
1. [:film_strip: \[eng\] SQL Tutorial | PostgreSQL | Full Course by Amigoscode](https://www.youtube.com/watch?v=7S_tz1z_5bA)

### Apache Ignite
1. [:film_strip: \[eng\] \[eng\] Getting started with Apache Ignite part 1](https://www.youtube.com/watch?v=3dpHqlRhELI)
2. [:film_strip: \[eng\] Getting started with Apache Ignite part 2](https://www.youtube.com/watch?v=my7gwssh2cA)
3. [:film_strip: \[eng\] Getting started with Apache Ignite part 3](https://www.youtube.com/watch?v=EFy-nwYOQrc)
4. [:film_strip: \[eng\] Getting started with Apache Ignite part 4](https://www.youtube.com/watch?v=cVqnNa192NY)
5. [:film_strip: \[eng\] Moving Apache Ignite into Production: Best Practices for Distributed Transactions](https://www.youtube.com/watch?v=yvMWK-4grYo)
6. [:scroll: \[eng\] Boosting Jira Cloud App Development with Apache Ignite and Spring Boot](https://medium.com/alliedium/boosting-jira-cloud-app-development-with-apache-ignite-7eebc7bb3d48)
7. :book: High Performance in-memory computing with Apache Ignite: Building low latency, near real time application, Shamim Ahmed Bhuiyan, Michael Zheludkov and Timur Isachenko

## Programming Languages
### Java
1. [:film_strip: \[rus\] Java Overview by FoxMinded](https://www.youtube.com/watch?v=w2Vb-VSUPBA)
2. [:film_strip: \[rus\] Java Application Development: the first steps by FoxMinded](https://www.youtube.com/watch?v=Qku0VoaZ-gE)
3. [:scroll: \[eng\] AWESOME JAVA: A curated list of awesome frameworks, libraries and software for the Java programming language. ](https://github.com/akullpp/awesome-java)
4. [:film_strip: \[rus\] What is a Java server, comparison of Java Servers: Tomcat, Jetty, Wildfly, Glassfish, IBM WebSphere, Oracle WebLogic](https://www.youtube.com/watch?v=fCjJgA2ila4)
5. [:film_strip: \[eng\] Java Tutorial for Beginners by Mosh](https://www.youtube.com/watch?v=eIrMbAQSU34)
6. [:film_strip: \[rus\] \[rus\] \[rus\] Java For Beginners by FoxMinded](https://www.youtube.com/playlist?list=PLmqFxxywkatR3qNmxqcFIHF9MN2-_eteU)
7. [:film_strip: \[rus\] \[rus\] Why it is bad to return NULL in Java](https://www.youtube.com/watch?v=QwycPnpp6uQ)
8. [:film_strip: \[rus\] Never ever use Lombok! Why this library is bad by FoxMinded](https://www.youtube.com/watch?v=tkoFx3fDwz8)
9. :book: Thinking in Java, Bruce Eckel, 4th edition
10. [:scroll: \[eng\] Java Tutorials by JournalDev](https://www.journaldev.com/java-tutorial-java-ee-tutorials)

#### Code Style
1. [:scroll: \[eng\] Checkstyle is a tool for enforcing a Code Standard in Java](https://github.com/checkstyle/checkstyle)
2. [:scroll: \[eng\] Jenkins Warnings Next Generation Plugin](https://github.com/jenkinsci/warnings-ng-plugin)
3. [:scroll: \[eng\] How to Centralize your Checkstyle Configuration with Maven](https://codeburst.io/how-to-centralize-your-checkstyle-configuration-with-maven-7575eacd7295)

#### Build Tools
##### Maven
1. [:film_strip: \[eng\] Simple Explanation of Maven and pom.xml](https://www.youtube.com/watch?v=KNGQ9JBQWhQ)
2. [:scroll: \[eng\] Maven Tutorial](https://medium.com/edureka/maven-tutorial-2e87a4669faf)
3. [:scroll: \[eng\] Multi-Module Maven Project by Baeldung](https://www.baeldung.com/maven-multi-module)

#### Java Frameworks

1. [:film_strip: \[rus\] Which Java Frameworks you should know by FoxMinded](https://www.youtube.com/watch?v=GbALlmGg0vc)

##### Java Collections Framework
1. [:scroll: \[eng\] Java Collections Framework official documentation](https://docs.oracle.com/javase/8/docs/technotes/guides/collections/overview.html)

##### ExecutorService
1. [:scroll: \[eng\] ExecutorService - 10 tips and tricks](https://www.nurkiewicz.com/2014/11/executorservice-10-tips-and-tricks.html)
2. [:scroll: \[eng\] InterruptedException and interrupting threads explained](https://www.nurkiewicz.com/2014/05/interruptedexception-and-interrupting.html)

##### TestNG
1. [:scroll: \[eng\] Introduction to TestNG](https://medium.com/gradeup/introduction-to-testng-7f401811f48c)
2. [:scroll: \[eng\] Why TestNG is better than JUnit](https://medium.com/@kavinduvsomadasa/test-automation-with-testng-using-page-object-modeling-b0d8dc272438)
3. [:film_strip: \[eng\] Java Unit Testing with TestNG and Mockito](https://www.youtube.com/watch?v=4d8D47cMvZo)
4. :book: Practical Unit Testing with TestNG and Mockito, Tomek Kaczanowski

##### Mockito
1. [:scroll: \[eng\] Unit Tests with Mockito: Tutorial](https://www.vogella.com/tutorials/Mockito/article.html)
2. [:scroll: \[eng\] Mockito in six easy examples](https://gojko.net/2009/10/23/mockito-in-six-easy-examples/)
3. [:scroll: \[ru\] A sip of Mockito](https://habr.com/ru/post/72617/)
4. [:scroll: \[eng\] Mockito - Quick Guide](https://www.tutorialspoint.com/mockito/mockito_quick_guide.htm)
5. [:scroll: \[eng\] Mockito When/Then Cookbook](https://www.baeldung.com/mockito-behavior)
6. [:scroll: \[eng\] Usage of Mockito](https://medium.com/art-of-coding/usage-of-mockito-674db441a334)
7. [:scroll: \[eng\] Mocking with Mockito: advanced techniques](https://medium.com/trabe/mocking-with-mockito-advanced-techniques-3a4e5143c2ba)
8. :book: Practical Unit Testing with JUnit and Mockito, Tomek Kaczanowski

##### Serenity BDD
1. [:scroll: \[eng\] How to implement test automation using Serenity](https://medium.com/@pratikbarjatya/how-i-implemented-test-automation-using-serenity-22a734bae78e)
2. [:scroll: \[eng\] Serenity BDD official documentation](http://serenity-bdd.info/docs/serenity/)
3. [:scroll: \[eng\] JBehave vs Cucumber JVM comparison](https://medium.com/agile-vision/jbehave-vs-cucumber-jvm-comparison-and-experience-sharing-439dfdf5922d)

##### Hibernate
1. [:film_strip: \[rus\] What is JDBC? What is ORM, Hibernate & JPA? by FoxMinded](https://www.youtube.com/watch?v=vAv0zaXGbFo)
2. [:film_strip: \[eng\] Getting started with Hibernate](https://www.youtube.com/watch?v=6TPDK6MOkz4)
3. [:film_strip: \[rus\] Spring Boot JPA(Hibernate): let's add a database to our Java-based website by letsCode](https://www.youtube.com/watch?v=nyFLX3q3poY&list=PLU2ftbIeotGpAYRP9Iv2KLIwK36-o_qYk&index=4)
4. [:film_strip: \[eng\] Hibernate Tutorial, Full Course](https://www.youtube.com/watch?v=JR7-EdxDSf0)

##### Spring Boot
1. [:film_strip: \[eng\] Spring Boot Tutorial for Beginners by freeCodeCamp.org](https://www.youtube.com/watch?v=vtPkZShrvXQ)
2. [:film_strip: \[rus\] Comparing Spring and JavaEE by FoxMinded](https://www.youtube.com/watch?v=HMT6jgZ5Pls)
3. [:film_strip: \[rus\] Spring Boot 2: let us build a simple website together! by letsCode](https://www.youtube.com/playlist?list=PLU2ftbIeotGpAYRP9Iv2KLIwK36-o_qYk)
4. [:scroll: \[eng\] Boosting Jira Cloud App Development with Apache Ignite and Spring Boot](https://medium.com/alliedium/boosting-jira-cloud-app-development-with-apache-ignite-7eebc7bb3d48)

##### Spring Boot Dev Tools
1. [:scroll: \[eng\] Faster Development with Spring Boot DevTools](https://www.vojtechruzicka.com/spring-boot-devtools/)
2. [:scroll: \[eng\] Optimize Your Dev Loop with Spring Boot Dev Tools](https://reflectoring.io/spring-boot-dev-tools/)

### JavaScript
1. [:film_strip: \[eng\] Java Script Tutorials by Mosh](https://www.youtube.com/playlist?list=PLTjRvDozrdlxEIuOBZkMAK5uiqp8rHUax)
2. [:scroll: \[eng\] AWESOME JAVASCRIPT:  A collection of awesome browser-side JavaScript libraries, resources and shiny things](https://github.com/sorrycc/awesome-javascript)

#### JavaScript frameworks, Tools and Runtimes
##### Node.js
1. [:film_strip: \[eng\] Node.js Tutorial for Beginners: Learn Node in 1 Hour by Mosh](https://www.youtube.com/watch?v=TlB_eWDSMt4)
2. [:scroll: \[eng\] AWESOME NODEJS: Delightful Node.js packages and resources](https://github.com/sindresorhus/awesome-nodejs)

##### Babel
1. [:film_strip: \[eng\] What is Babel and why you need it? Introduction to Babel](https://www.youtube.com/watch?v=yLrNwo4wXOs)

##### Jest
1. [:film_strip: \[rus\] Jest: Unit Testing in Java Script](https://www.youtube.com/watch?v=IEDe8jl5efU)

##### React
1. [:film_strip: \[eng\] React Tutorial for Beginners [React js]](https://www.youtube.com/watch?v=Ke90Tje7VS0)
2. [:scroll: \[eng\] AWESOME REACT: A collection of awesome things regarding React ecosystem ](https://github.com/enaqx/awesome-react)
3. [:film_strip: \[eng\] React in 30 minutes](https://www.youtube.com/watch?v=hQAHSlTtcmY)
4. [:film_strip: \[eng\] Learn useState In 15 Minutes - React Hooks Explained](https://www.youtube.com/watch?v=O6P86uwfdR0&list=PLZlA0Gpn_vH8EtggFGERCwMY5u5hOjf-h)
5. [:film_strip: \[eng\] Learn useEffect In 13 Minutes](https://www.youtube.com/watch?v=0ZJgIjIuY7U)
6. [:film_strip: \[eng\] Redux Tutorial - Learn Redux from Scratch](https://www.youtube.com/watch?v=poQXNp9ItL4)
7. [:film_strip: \[eng\] React Unit Testing](https://www.youtube.com/watch?v=3e1GHCA3GP0)

### Python
1. [:film_strip: \[eng\] Python Tutorial - Python for Beginners [2020]](https://www.youtube.com/watch?v=f79MRyMsjrQ&list=RDCMUCWv7vMbMWH4-V0ZXdmDpPBA)
2. [:scroll: \[eng\] AWESOME PYTHON: A curated list of awesome Python frameworks, libraries, software and resources](https://github.com/vinta/awesome-python)


### Rust
#### Rust Tutorial
- [Considering Rust by Jon Gjengset](https://www.youtube.com/watch?v=DnT-LUQgc7s)
- [Rust Crash Course by  Traversy Media](https://www.youtube.com/watch?v=zF34dRivLOw)
- [Rust Linz, August 2020 - Ryan Levick - Why should I care about Rust?](https://www.youtube.com/watch?v=OhCjnyBc448)
- [Introduction to Rust Part 1 by Ryan Levick](https://www.youtube.com/watch?v=WnWGO-tLtLA)
- [Introduction to Rust Part 2 by Ryan Levick](https://www.youtube.com/watch?v=lLWchWTUFOQ)
- [Understanding Rust Lifetimes by Ryan Levick](https://www.youtube.com/watch?v=MSi3E5Z8oRw)
- [Crust of Rust by  Jon Gjengset](https://www.youtube.com/watch?v=rAl-9HwD858&list=PLqbS7AVVErFiWDOAVrPt7aYmnuuOLYvOa)

##### Rust at Microsoft
- [R-Evolution: A Story of Rust Adoption at Microsoft - Ryan Levick](https://www.youtube.com/watch?v=qCB19DRw_60)
##### Rust at AWS
- [AWS re:Invent 2020: Next-gen networking infrastructure with Rust and Tokio](https://www.youtube.com/watch?v=MZyleK8elPk)


### Julia

#### Criticism of Julia
- [Julia: a post-mortem](https://chrisvoncsefalvay.com/2021/03/07/julia-a-post-mortem/)
- [Julia: a post-mortem: discussion on Julia's discourse](https://discourse.julialang.org/t/julia-a-post-mortem/56809)
- [Julia: a post-mortem: discussion on ycombinator](https://news.ycombinator.com/item?id=26384133)
- [Julia from the perspective of a pythonista](https://discourse.julialang.org/t/julia-from-the-perspective-of-a-pythonista/55956)
- [What's bad about Julia by Jeff Bezenson](https://www.youtube.com/watch?v=TPuJsgyu87U)

#### Getting started with Julia
 - [Julia motivation: why weren’t Numpy, Scipy, Numba, good enough?](https://discourse.julialang.org/t/julia-motivation-why-werent-numpy-scipy-numba-good-enough/2236)
 - [JuliaCon 2019 | The Unreasonable Effectiveness of Multiple Dispatch | Stefan Karpinski](https://www.youtube.com/watch?v=kc9HwsxE1OY) 
 - [Julia Academy](https://juliaacademy.com/courses)
 - [Getting started with Julia](https://geekmonkey.org/getting-started-with-julia-lang/)
 - [9 Cool Julia tricks](https://towardsdatascience.com/9-cool-julia-tricks-in-4-minutes-47a3a4496054)
 - [Julia blogs aggregator](https://julialang.org/blog/)
 - [Julia 1.6 highlights](https://julialang.org/blog/2021/03/julia-1.6-highlights/)
 
#### Julia adoption
- [Julia is production-ready](https://bkamins.github.io/julialang/2020/08/07/production-ready.html)
- [JuliaCon 2020 | The ups and downs of convincing to switch to Julia in a company | Jorge Alberto](https://www.youtube.com/watch?v=IdhnP00Y1Ks)
- [JuliaCon 2020 | State of Julia | Jeff Bezanson & Stefan Karpinski](https://www.youtube.com/watch?v=xKrIp4ZVOrg)

#### Julia co-creators talks
- [Interview with Julia Language Co-founders](https://www.youtube.com/watch?v=VgZm53qgj9Q)

#### Julia performance
 - [Julia performance tips](https://docs.julialang.org/en/v1/manual/performance-tips/)
 - [Julia performance: benchmarking via BenchmarkTools.jl](https://github.com/JuliaCI/BenchmarkTools.jl/blob/master/doc/manual.md#defining-and-executing-benchmarks)
 - [How to benchmark like a pro in Julia | Tom Kwong](https://www.youtube.com/watch?v=9C7MAAsMMBc)
 - [JuliaCon 2020 | Adventures in Avoiding Allocations | Brian Jackson](https://www.youtube.com/watch?v=o8qTJGcPWkE)

#### Julia vs C++
- [How hard would it be to implement Numpy.jl, i.e. Numpy in Julia? Point 1](https://discourse.julialang.org/t/how-hard-would-it-be-to-implement-numpy-jl-i-e-numpy-in-julia/22080/71)
- [How hard would it be to implement Numpy.jl, i.e. Numpy in Julia? Point 2](https://discourse.julialang.org/t/how-hard-would-it-be-to-implement-numpy-jl-i-e-numpy-in-julia/22080/73)


#### Contributing to Julia ecosystem
- [How to submit a PR on GitHub](https://discourse.julialang.org/t/develop-a-local-version-of-a-registered-package-and-submit-changes-as-a-pull-request/24868)

#### Language basics
- [Working with and emulating references in Julia](https://erik-engheim.medium.com/working-with-and-emulating-references-in-julia-e02c1cae5826)
- [Is Julia Dynamically Typed?](https://stackoverflow.com/questions/28078089/is-julia-dynamically-typed)
- [Julia type system](https://docs.julialang.org/en/v1/manual/types/)
- [Libraries & parameterized types | MIT Computational Thinking Spring 2021 | Lecture 18](https://www.youtube.com/watch?v=S71YIZ8e7MQ)

#### Finding Julia packages
- [juliaobserver.com](https://juliaobserver.com/packages)
- [juliapackages.com](https://juliapackages.com/)

#### DataFrames
##### DataFrames.jl
- [DataFrames.jl performance benchmark](https://h2oai.github.io/db-benchmark/)
- [DataFrames minilanguage explained](https://www.juliabloggers.com/dataframes-jl-minilanguage-explained/)
- [Welcome to DataFrames.jl with Bogumił Kamiński](https://github.com/JuliaAcademy/DataFrames)
- [Release announcements for DataFrames.jl](https://discourse.julialang.org/t/release-announcements-for-dataframes-jl/18258/1)
- [DataFrames.jl: comparison with Pandas](https://dataframes.juliadata.org/latest/man/comparisons/)
- [DataFrames.jl cheatsheet](https://ahsmart.com/assets/pages/data-wrangling-with-data-frames-jl-cheat-sheet/DataFramesCheatSheet_v0.22_rev1.pdf)

#### ML
- [JuliaCon 2020 | Doing Scientific Machine Learning (SciML) With Julia](https://www.youtube.com/watch?v=QwVO0Xh2Hbg)
- [MIT Course 18.337 - Parallel Computing and Scientific Machine Learning GitHub Repo](https://github.com/mitmath/18337)
- [MIT Course 18.337 - Parallel Computing and Scientific Machine Learning YouTube Channel](https://www.youtube.com/playlist?list=PLCAl7tjCwWyGjdzOOnlbGnVNZk0kB8VSa)


#### Parallel Computing
- [https://julialang.org/blog/2019/07/multithreading/#task_scheduling_and_synchronization]
- [MIT Course 18.337 - Parallel Computing and Scientific Machine Learning GitHub Repo](https://github.com/mitmath/18337)
- [MIT Course 18.337 - Parallel Computing and Scientific Machine Learning YouTube Channel](https://www.youtube.com/playlist?list=PLCAl7tjCwWyGjdzOOnlbGnVNZk0kB8VSa)

#### IDE
 - [VSCode Plugin](https://www.youtube.com/watch?v=IdhnP00Y1Ks)

#### Notebooks
##### Jupyter 
- [JuliaCon 2020 | Dependency-Aware Jupyter Notebooks | Arnav Sood](https://www.youtube.com/watch?v=LYVdRTuxS_c)

##### Pluto.jl
- [JuliaCon 2020 | Interactive notebooks ~ Pluto.jl | Fons van der Plas](https://www.youtube.com/watch?v=IAF8DjrQSSk)
- [Pluto.jl Notebooks and PlutoUI Tutorial (Julia Programming)](https://www.youtube.com/watch?v=C4QhZcX34mI)
- [How to disable authentication](https://github.com/fonsp/Pluto.jl/issues/1083)
- [How to increase notebook width](https://github.com/fonsp/Pluto.jl/issues/748)
- [Table of contents](https://github.com/fonsp/PlutoUI.jl/pull/30#issuecomment-819287500)
- [Dark mode](https://github.com/Pocket-titan/DarkMode)

#### Jilia in production
##### Microservices
- [JuliaCon 2020 | Building Microservices and Applications in Julia](https://www.youtube.com/watch?v=uLhXgt_gKJc)
##### Deployment
###### Sysimage
- [Custom sysimages: official documentation](https://julialang.github.io/PackageCompiler.jl/dev/sysimages/)
###### Docker
- [SimpleContainerGenerator](https://github.com/JuliaContainerization/SimpleContainerGenerator.jl)
- [Running AWS Lambda functions with Julia | Tom Kwong](https://www.youtube.com/watch?v=6DvpneWRb_w)

#### Differential equations
##### DifferentialEquations.jl
- [Libraries & parameterized types | MIT Computational Thinking Spring 2021 | Lecture 18](https://www.youtube.com/watch?v=S71YIZ8e7MQ)

#### OOP in Julia
- [Goodbye OOP](https://medium.com/@cscalfani/goodbye-object-oriented-programming-a59cda4c0e53)
- [Type-Dispatch Design: Post Object-Oriented Programming for Julia](http://www.stochasticlifestyle.com/type-dispatch-design-post-object-oriented-programming-julia/)
- [WhereTraits.jl](https://github.com/schlichtanders/WhereTraits.jl)
- [BinaryTraits.jl](https://github.com/tk3369/BinaryTraits.jl)
- [Julia: how multiple dispatch works](https://discourse.julialang.org/t/julia-isnt-multiple-dispatch-but-overloading/42370/13)
- [JuliaCon 2020 | Lessons learned on trait-based descriptions of graphs | Mathieu Besancon](https://www.youtube.com/watch?v=qhAe1PuWjRQ)

#### Integration with other languages
##### Python
- [JuliaPy](https://github.com/JuliaPy)

#### Basics of hardware architecture 
- http://ithare.com/infographics-operation-costs-in-cpu-clock-cycles/


## DevOps
1. [:film_strip: \[eng\] DevOps explained by IBM](https://www.youtube.com/playlist?list=PLOspHqNVtKAAm1dmyiR9WMmw1UBoOwZVj)
2. [:scroll: \[eng\] What is DevOps, DevOps lifecycle](https://medium.com/edureka/devops-lifecycle-8412a213a654)
3. [:scroll: \[eng\] Continuous Delivery vs Continuous Deployment](https://medium.com/edureka/continuous-delivery-vs-continuous-deployment-5375642865a)
4. [:scroll: \[eng\] DevOps exercies by Bregman Arie](https://github.com/bregman-arie/devops-exercises)

### Containers and Container Orchestration
#### Docker
1. [:film_strip: \[rus\] Docker basics](https://www.youtube.com/watch?v=yrmty10Q7NQ)
2. [:scroll: \[eng\] Docker Interview Questions](https://medium.com/edureka/docker-interview-questions-da0010bedb75)
3. [:scroll: \[eng\] Docker Compose Tutorial](https://medium.com/edureka/docker-compose-containerizing-mean-stack-application-e4516a3c8c89)
4. [:scroll: \[eng\] Docker Exercises by Bregman Arie](https://github.com/bregman-arie/devops-exercises#docker)
5. [:film_strip: \[eng\] Portainer - Lightweight Management UI for Docker](https://www.youtube.com/watch?v=8q9k1qzXRk4) 

#### Ansible
1. [:film_strip: \[eng\] What Is Ansible? | How Ansible Works? | Ansible Tutorial For Beginners by Simplilearn](https://www.youtube.com/watch?v=wgQ3rHFTM4E)
2. [:film_strip: \[eng\] You need to learn Ansible RIGHT NOW!! (Linux Automation) by NetworkChuck](https://www.youtube.com/watch?v=5hycyr-8EKs)

#### Kubernetes 
1. [:film_strip: \[eng\] Minikube Basics and How to Get Started with Kubernetes by Peter Jausovec](https://www.youtube.com/watch?v=FacPam4bwRk)
2. [:film_strip: \[rus\] Kubernetes video tutorial](https://www.youtube.com/playlist?list=PLsMIccp52YRtEr4EallcVRlCaEt61oRzl)
3. [:scroll: \[eng\] Setting up a Kubernetes cluster with Kubespray](https://medium.com/@leonardo.bueno/setting-up-a-kubernetes-cluster-with-kubespray-1bf4ce8ccd73)
4. [:scroll: \[eng\] Kubernetes exercies by Bregman Arie](https://github.com/bregman-arie/devops-exercises#kubernetes)

### Jenkins
1. [:scroll: \[eng\] Jenkins Pipeline Tutorial](https://medium.com/edureka/jenkins-pipeline-tutorial-continuous-delivery-75a86936bc92)
2. [:scroll: \[eng\] Continuous Integration with Jenkins](https://medium.com/edureka/continuous-integration-615325cfeeac)
3. [:film_strip: \[rus\] Jenkins Video Course in Russian](https://www.youtube.com/playlist?list=PLmxB7JSpraiew9igtD89o33AaniUrmUzm)
4. [:scroll: \[eng\] Jenkins CheatSheet](https://medium.com/edureka/jenkins-cheat-sheet-e0f7e25558a3)
5. [:scroll: \[eng\] Jenkins Interview Questions](https://medium.com/edureka/jenkins-interview-questions-7bb54bc8c679)

## Networks
### REST API
1. [:film_strip: \[eng\] REST API explained by Mosh](https://www.youtube.com/watch?v=SLwpqD8n3d0)
2. [:film_strip: \[eng\] Autogenerating Swagger Documentation with Node & Express](https://www.youtube.com/watch?v=apouPYPh_as)
3. [:film_strip: \[rus\] REST API testing via Postman](https://www.youtube.com/watch?v=ZpxjS8ZB0MA)

### GraphQL
1. [:scroll: \[eng\] Introduction to GraphQL by Udara Bibile](https://medium.com/@chathuranga94/introduction-to-graphql-3e0142879aba)
2. [:scroll: \[eng\] GraphQL With Python Flask by Manish Jain](https://medium.com/@hatemtayeb2/hello-graphql-a-practical-guide-a2f7f9f70ab4)
3. [:scroll: \[eng\] Schema-First GraphQL: The Road Less Travelled by Jakub Draganek](https://blog.mirumee.com/schema-first-graphql-the-road-less-travelled-cf0e50d5ccff)

