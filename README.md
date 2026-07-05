```text
-------------------------------------------------------------------------------
                              COMPUTER SCIENCE
-------------------------------------------------------------------------------

  Repository : computer-science
  Owner      : Pedro Neiva | preis-ne (@neivaeu)
  Website    : https://www.neiva.pt
  GitHub     : https://github.com/neivaeu
  LinkedIn   : https://linkedin.com/in/neivaeu
  Updated    : June 2026
  Copyright  : (c) 2026 Pedro Neiva. All rights reserved.

-------------------------------------------------------------------------------
                                 PHILOSOPHY
-------------------------------------------------------------------------------

  This repository is more than a portfolio. It is a living knowledge base,
  a software engineering laboratory, and the exhaustive documentation of a
  deep journey through Computer Science. Strongly anchored in the demanding
  curriculum of 42 School, this repository is structured across 19
  technological domains and demonstrates the deconstruction of technology
  from bare-metal to the cloud.

  The core philosophy: build without shortcuts. Prove the ability to deeply
  master the internal mechanics of systems through complete, standalone
  implementations built from scratch.

  Content includes:

    - 42 School curriculum projects
    - MIT OpenCourseWare challenge solutions
    - Harvard CS50x, CS50w, CS50ai, CS50c solutions
    - Stanford, Princeton, Berkeley, CMU, Oxford, ETH Zurich, EPFL coursework
    - HackTheBox machine write-ups and CTF solutions
    - HackerOne and Bugcrowd vulnerability research and PoCs
    - PortSwigger Web Security Academy lab solutions
    - OverTheWire, pwn.college, CryptoHack, and other wargame solutions
    - LeetCode, Codeforces, AtCoder, and Advent of Code solutions
    - Personal concept laboratories and independent research
    - Security certification preparation (OSCP, OSWE, GIAC, etc.)
    - Professional portfolio and curriculum materials

-------------------------------------------------------------------------------
                            STRUCTURE — 19 DOMAINS
-------------------------------------------------------------------------------
meu-repositorio/
├── .editorconfig
├── .github/
├── .gitignore_old
├── .lycheeignore
├── .markdownlint.json
├── 00-dotfiles/
├── 99-curriculum/
├── CHANGELOG.md
├── CITATION.cff
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── GOVERNANCE.md
├── LICENSE
├── README.md
├── SECURITY.md
├── SUPPORT.md
│
└── XX-domain-name/
    ├── README.md
    ├── GLOSSARY.md
    ├── RESOURCES.md
    │
    ├── 01-foundations/
    │   ├── README.md
    │   ├── 00-mathematics/
    │   │   ├── README.md
    │   │   └── ...
    │   ├── 01-theory-and-models/
    │   │   ├── README.md
    │   │   └── ...
    │   ├── 02-core-algorithms/
    │   │   ├── README.md
    │   │   └── ...
    │   ├── 03-data-structures/
    │   │   ├── README.md
    │   │   └── ...
    │   ├── 04-paradigms-and-patterns/
    │   │   ├── README.md
    │   │   └── ...
    │   └── 05-protocols-and-standards/
    │       ├── README.md
    │       └── ...
    │
    ├── 02-knowledge-base/
    │   ├── README.md
    │   ├── 01-architectures-and-diagrams/
    │   │   ├── README.md
    │   │   └── diagrams/
    │   ├── 02-core-logic-and-snippets/
    │   │   ├── README.md
    │   │   └── snippets/
    │   ├── 03-post-mortems/
    │   │   ├── README.md
    │   │   └── template-post-mortem.md
    │   └── 04-defense-and-evaluation/
    │       ├── README.md
    │       └── evaluation-criteria.md
    │
    ├── 03-projects/
    │   ├── README.md
    │   ├── 01-from-scratch/
    │   │   ├── README.md
    │   │   └── ...
    │   ├── 02-framework-based/
    │   │   ├── README.md
    │   │   └── ...
    │   ├── 03-cli-and-micro-tools/
    │   │   ├── README.md
    │   │   └── ...
    │   └── 04-large-scale-systems/
    │       ├── README.md
    │       └── ...
    │
    ├── 04-laboratory/
    │   ├── README.md
    │   ├── 01-benchmarks/
    │   │   ├── README.md
    │   │   └── ...
    │   ├── 02-vulnerability-and-stress/
    │   │   ├── README.md
    │   │   └── ...
    │   ├── 03-edge-cases/
    │   │   ├── README.md
    │   │   └── ...
    │   └── 04-reverse-engineering/
    │       ├── README.md
    │       └── ...
    │
    ├── 05-toolchain/
    │   ├── README.md
    │   ├── 01-build-and-compile/
    │   │   ├── README.md
    │   │   └── ...
    │   ├── 02-debug-and-profile/
    │   │   ├── README.md
    │   │   └── ...
    │   ├── 03-analysis-and-quality/
    │   │   ├── README.md
    │   │   └── ...
    │   ├── 04-deployment/
    │   │   ├── README.md
    │   │   └── ...
    │   └── 05-domain-specific-tools/
    │       ├── README.md
    │       └── ...
    │
    ├── 06-challenges/
    │   ├── README.md
    │   ├── 01-algorithmic-platforms/
    │   │   ├── README.md
    │   │   └── ...
    │   ├── 02-ctf-and-wargames/
    │   │   ├── README.md
    │   │   └── ...
    │   ├── 03-academic-assignments/
    │   │   ├── README.md
    │   │   └── poc/
    │   │       ├── README.md
    │   │       ├── 42/
    │   │       │   ├── README.md
    │   │       │   └── <project-name>/
    │   │       │       ├── README.md
    │   │       │       ├── EVALUATION.md
    │   │       │       ├── POST-MORTEM.md
    │   │       │       ├── src/
    │   │       │       ├── docs/
    │   │       │       └── tests/
    │   │       ├── harvard/
    │   │       │   └── README.md
    │   │       ├── mit/
    │   │       │   └── README.md
    │   │       └── stanford/
    │   │           └── README.md
    │   └── 04-system-design-katas/
    │       ├── README.md
    │       └── ...
    │
    ├── 07-chaos/
    │   ├── README.md
    │   ├── template.md
    │   └── <exploration-name>/
    │       └── ...
    │
    ├── 08-experiments/
    │   ├── README.md
    │   ├── template.md
    │   └── <experiment-name>/
    │       ├── README.md
    │       ├── src/
    │       └── results/
    │
    └── 09-graveyard/
        ├── README.md
        ├── template.md
        └── <dead-project>/
            ├── README.md
            └── src/

-------------------------------------------------------------------------------
                              IMPORTANT NOTICE
-------------------------------------------------------------------------------

  42 SCHOOL STUDENTS
    Copying any part of this code is a violation of the 42 Peer-to-Peer
    integrity system and constitutes academic plagiarism. It will be
    reported immediately to campus staff with full evidence. Use this
    repository as a reference for understanding, not as a source to copy.

  INTELLECTUAL PROPERTY
    All original code and documentation in this repository are the
    exclusive intellectual property of Pedro Neiva. Unauthorized
    redistribution or commercial use is strictly prohibited.
    See LICENSE for full terms.

-------------------------------------------------------------------------------

<!--
GITHUB_SEARCH_INDEX_BOOST_START
Project_Names: "01 - Theoretical Computer Science,ready set boole,matrix,
computorv1,computorv2,ft_turing,n-puzzle,krpsim,Abstract_data,
02 - Algorithms & Data Structures,push_swap,lem_in,ft_ls,nm,malloc,corewar,
A-Maze-ing,03 - Programming Languages,CPP Module 00,CPP Module 01,
CPP Module 02,CPP Module 03,CPP Module 04,CPP Module 05,CPP Module 06,
CPP Module 07,CPP Module 08,CPP Module 09,
OCAML - Basic syntax and semantics - 0,
OCAML - Recursion and higher-order functions - 0,
OCAML - Pattern Matching and Data Types - 0,
OCAML  - OCaml's modules language - 1,OCAML - Imperative features - 1,
OCAML - Functor - 1,OCAML - Object Oriented Programming -  1,
OCAML - Object Oriented Programming - 2,OCAML - Monoids and Monads - 3,
Python Module 00,Python Module 01,Python Module 02,Python Module 03,
Python Module 04,Python Module 05,Python Module 06,Python Module 07,
Python Module 08,Python Module 09,Python Module 10,avaj-launcher,swingy,
fix-me,04 - Compilers & Interpreters,dr-quine,ft_ssl_md5,ft_ssl_rsa,
ft_ssl_des,ft_lex,ft_yacc,RoR - 0 - Initiation,RoR - 0 - Starting,
RoR - 0 - Oob,RoR - 1 - Gems,RoR - 1 - Base Rails,RoR - 2 - SQL,
RoR - 3 - Sessions,RoR - 3 - Advanced,RoR - 3 - Final,
Django - 0 - Initiation,Django - 0 - Starting,Django - 0 - Oob,
Django - 1 - Lib,Django - 1 - Base Django,Django - 2 - SQL,
Django - 3 - Sessions,Django - 3 - Advanced,Django - 3 - Final,
Symfony - 0 - Initiation,Symfony - 0 - Starting,Symfony - 0 - Oob,
Symfony - 1 - Composer,Symfony - 1 - Base Symfony,Symfony - 2 - SQL,
Symfony - 3 - Sessions,Symfony - 3 - Advanced,Symfony - 3 - Final,
05 - Computer Architecture,libasm,userspace_digressions,process-and-memory,
drivers-and-interrupts,gbmu,06 - Operating Systems,Born2beroot,ft_linux,
little-penguin-1,kfs-1,kfs-2,kfs-3,kfs-4,kfs-5,kfs-6,kfs-7,kfs-8,kfs-9,
kfs-x,filesystem,strace,taskmaster,42sh,matt-daemon,ft_shield,
tinky-winkey,xv,famine,07 - Computer Networks,ft_ping,ft_traceroute,
ft_nmap,ft_irc,webserv,ft_malcolm,minitalk,NetPractice,lem-ipc,
Bgp At Doors of Autonomous Systems is Simple,
08 - Cybersecurity & Cryptography,snow-crash,rainfall,override,boot2root,
darkly,Cybersecurity - ft_otp - OTP,Cybersecurity - ft_onion - Web,
Cybersecurity - arachnida - Web,Cybersecurity - Reverse me - Rev,
Cybersecurity - Stockholm - Malware,Cybersecurity - Inquisitor - Network,
(Optional) Cybersecurity - Iron Dome - Malware,Cybersecurity - Vaccine - Web,
woody-woodpacker,pestilence,wardeath,in-the-shadows,Cybersecurity,
09 - Software Engineering,
C Piscine|C Piscine Brussels|C Piscine Antwerp / C Piscine Shell 00,
C Piscine|C Piscine Brussels|C Piscine Antwerp / C Piscine Shell 01,
C Piscine|C Piscine Brussels|C Piscine Antwerp / C Piscine C 00,
C Piscine|C Piscine Brussels|C Piscine Antwerp / C Piscine C 01,
C Piscine|C Piscine Brussels|C Piscine Antwerp / C Piscine C 02,
C Piscine|C Piscine Brussels|C Piscine Antwerp / C Piscine C 03,
C Piscine|C Piscine Brussels|C Piscine Antwerp / C Piscine C 04,
C Piscine|C Piscine Brussels|C Piscine Antwerp / C Piscine C 05,
C Piscine|C Piscine Brussels|C Piscine Antwerp / C Piscine C 06,
C Piscine|C Piscine Brussels|C Piscine Antwerp / C Piscine C 07,
C Piscine|C Piscine Brussels|C Piscine Antwerp / C Piscine C 08,
C Piscine|C Piscine Brussels|C Piscine Antwerp / C Piscine C 09,
C Piscine|C Piscine Brussels|C Piscine Antwerp / C Piscine C 10,
C Piscine|C Piscine Brussels|C Piscine Antwerp / C Piscine C 11,
C Piscine|C Piscine Brussels|C Piscine Antwerp / C Piscine C 12,
C Piscine|C Piscine Brussels|C Piscine Antwerp / C Piscine C 13,
C Piscine|C Piscine Brussels|C Piscine Antwerp / C Piscine BSQ,
C Piscine|C Piscine Brussels|C Piscine Antwerp / C Piscine Rush 00,
C Piscine|C Piscine Brussels|C Piscine Antwerp / C Piscine Rush 01,
C Piscine|C Piscine Brussels|C Piscine Antwerp / C Piscine Rush 02,
C Piscine|C Piscine Brussels|C Piscine Antwerp / C Piscine Exam 00,
C Piscine|C Piscine Brussels|C Piscine Antwerp / C Piscine Exam 01,
C Piscine|C Piscine Brussels|C Piscine Antwerp / C Piscine Exam 02,
C Piscine|C Piscine Brussels|C Piscine Antwerp / C Piscine Final Exam,
C Piscine / C Piscine Exam Checkpoint 00.5,
C Piscine / C Piscine Exam Checkpoint 01.5,
C Piscine / C Piscine Exam Checkpoint 02.5,Libft,libftpp,ft_printf,
get_next_line,pipex,minishell,Philosophers,Exam Rank 02,Exam Rank 03,
Exam Rank 04,Exam Rank 05,Exam Rank 06,
Piscine Object - Module 00 - Encapsulation,
Piscine Object - Module 01 - Relationship,
Piscine Object - Module 02 - UML,Piscine Object - Module 03 - SOLID,
Piscine Object - Module 04 - Design Pattern,
Piscine Object - Module 05 - Practical work,Open Project,Work Experience I,
Work Experience II,Part_Time I,Startup Experience,Rushes,ActiveConnect,
ActiveDiscovery,AutomaticDirectory,AdministrativeDirectory,
AccessibleDirectory,MicroForensX,ActiveTechTales,Tokenizer,Tokenize,
Art42_Collaborative_resume,Peace_Break,Bcc1,Call Me Maybe,
RAG against the machine,The Answer Protocol,tree_nity,Agent Smith,Codexion,
Fly-in,Pac-Man,UnleashTheBox,Learn2Slither,Very_Real_Engine,
10 - Artificial Intelligence,expert-system,multilayer-perceptron,
total-perspective-vortex,ft_linear_regression,gomoku,Leaffliction,dslr,
11 - Data Science & Databases,Data Science - 0,Data Science - 1,
Data Science - 2,Data Science - 3,Data Science - 4,Python - 0 - Starting,
Python - 1 - Array,Python - 2 - DataTable,Python - 3 - OOP,Python - 4 - Dod,
12 - Computer Graphics,fract-ol,FdF,so_long,miniRT,cub3d,scop,doom-nukem,
ft_vox,shader,pixelgui,mpparticle-system,mod1,humangl,
Unity - 0 - The basics Unity tools,
Unity - 1 - 3D physics, Tags, Layers and Scene,
Unity - 2 - 2D environment, tiles and sprites,
Unity - 3 - Advanced inputs and 2D GUI,Unity - 4 - Animations and Sound,
Unity - 5 - Singleton, playerPrefs and coroutines,
Unity - 6 - Navmesh, light, sound and camera,red-tetris,rt,ft_newton,
rubik,ft_minecraft,13 - Human-Computer Interaction,camagru,matcha,
hypertube,swifty-companion,swifty-protein,ft_hangouts,nibbler,42run,
bomberman,music-room,h42n42,freddie-mercury,
Mobile - 0 - Basic of the mobile application,
Mobile - 1 - Structure and logic,Mobile - 2 - API and data,
Mobile - 3 - Design,Mobile - 4 - Auth and dataBase,
Mobile - 5 - Manage data and display,
14 - Distributed & Parallel Computing,ft_transcendence,zappy,
15 - Cloud Computing & DevOps,cloud-1,Inception,Inception-of-Things,
16 - Embedded Systems & IoT,ft_ality,
17 - Computational Science,ft_kalman,ft_newton,
18 - Quantum Computing,Ftl_quantum,
19 - Emerging Technologies,NetPractice"
GITHUB_SEARCH_INDEX_BOOST_END
-->
```
