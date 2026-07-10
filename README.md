```text
--------------------------------------------------------------------------------
                              COMPUTER SCIENCE
--------------------------------------------------------------------------------

  Repository : computer-science
  Owner      : Pedro Neiva | preis-ne (@neivaeu)
  Website    : https://www.neiva.pt
  GitHub     : https://github.com/neivaeu
  LinkedIn   : https://linkedin.com/in/neivaeu
  Updated    : July 2026
  Copyright  : (c) 2026 Pedro Neiva. All rights reserved.

--------------------------------------------------------------------------------
                                 PHILOSOPHY
--------------------------------------------------------------------------------

  This repository is more than a portfolio. It is a living knowledge base,
  a software engineering laboratory, and the exhaustive documentation of a
  deep journey through Computer Science. Strongly anchored in the demanding
  curriculum of 42 School, this repository is structured across 19
  technological domains and demonstrates the deconstruction of technology.

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

--------------------------------------------------------------------------------
                               THE 19 DOMAINS
--------------------------------------------------------------------------------

  T︀h︀e︁ l︀a︀b︀o︁r︀a︀t︁o︀r︁y︁ i︀s︁ s︁y︀s︁t︁e︀m︁a︀t︀i︁c︀a︀l︀l︁y︁ c︀a︁t︀e︀g︁o︀r︀i︀z︁e︀d︀ i︀n︁t︀o︁ 19 s︀p︁e︀c︀i︀a︀l︀i︁z︁e︀d︁ d︀o︀m︁a︁i︁n︁s︁:
   ┌────────────────────────────────────────────────────────────────────── ─┐
   | 01-theoretical-computer-science  | 11-data-science-databases           |
   | 02-algorithms-data-structures    | 12-computer-graphics                |
   | 03-programming-languages         | 13-human-computer-interaction       |
   | 04-compilers-interpreters        | 14-distributed-parallel-computing   |
   | 05-computer-architecture         | 15-cloud-computing-devops           |
   | 06-operating-systems             | 16-embedded-systems-iot             |
   | 07-computer-networks             | 17-computational-science            |
   | 08-cybersecurity-cryptography    | 18-quantum-computing                |
   | 09-software-engineering          | 19-emerging-technologies            |
   | 10-artificial-intelligence       |                                     |
   └────────────────────────────────────────────────────────────────────── ─┘

--------------------------------------------------------------------------------
                            STRUCTURE — OVERVIEW
--------------------------------------------------------------------------------
computer-science/
├── .editorconfig
├── .github/
├── .gitignore
├── .lycheeignore
├── .markdownlint.json
├── CHANGELOG.md
├── CITATION.cff
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── GOVERNANCE.md
├── LICENSE
├── README.md
├── SECURITY.md
├── SUPPORT.md
├── 00-dotfiles/
├── 99-curriculum/
|
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
    │   │   ├── 42/
    │   │   │   ├── README.md
    │   │   │   └── <project-name>/
    │   │   │       ├── README.md
    │   │   │       ├── EVALUATION.md
    │   │   │       ├── POST-MORTEM.md
    │   │   │       ├── src/
    │   │   │       └── tests/
    │   │   ├── harvard/
    │   │   │   └── README.md
    │   │   ├── mit/
    │   │   │   └── README.md
    │   │   └── stanford/
    │   │       └── README.md
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

--------------------------------------------------------------------------------
                          USAGE & ACADEMIC REFERENCE
--------------------------------------------------------------------------------

  This repository is public strictly for passive educational reference and
  architectural study.

  To ensure compliance with global academic integrity systems (including 42
  School Peer-to-Peer rules, MIT, and Harvard honor codes), third-party link
  policies, and copyright laws, please consult the LICENSE file for full
  terms, permitted uses, and restrictions before interacting with this code.

--------------------------------------------------------------------------------
