--------------------------------------------------------------------------------
                                CONTRIBUTING
--------------------------------------------------------------------------------

  Repository : computer-science
  Owner      : Pedro Neiva | preis-ne (@neivaeu)
  Website    : https://www.neiva.pt
  GitHub     : https://github.com/neivaeu
  LinkedIn   : https://linkedin.com/in/neivaeu
  Updated    : July 2026
  Copyright  : (c) 2026 Pedro Neiva. All rights reserved.

--------------------------------------------------------------------------------
                                  OVERVIEW
--------------------------------------------------------------------------------

  This is a personal knowledge base and project archive. It is NOT a
  collaborative open-source project. This repository does not accept
  Pull Requests or forks. External contributions are not part of the
  model of this repository.

  If you find an error, a broken reference, or have a relevant suggestion,
  the correct action is to open a GitHub Issue. The owner (@neivaeu) will
  evaluate and implement any accepted change directly.

  Before interacting with this repository in any way, read:

    - LICENSE           Full ownership terms and restrictions
    - CODE_OF_CONDUCT   Behavioural expectations
    - SECURITY          Security policy and IP notice

  This is NOT exclusively a 42 School repository. It covers 42 School
  projects, MIT/Harvard/Stanford coursework, security platform research,
  competitive programming solutions, personal projects, laboratory work,
  and certification preparation across 19 technological domains. All
  content is the exclusive intellectual property of Pedro Neiva.

--------------------------------------------------------------------------------
                          WHAT YOU CAN REPORT OR SUGGEST
--------------------------------------------------------------------------------

  The following types of Issues are accepted:

  FACTUAL ERROR
    A documented fact in the repository is verifiably incorrect.
    Provide evidence: a primary source, specification, or authoritative
    reference that contradicts the current content.
    Use the Bug Report template.

  BROKEN LINK OR REFERENCE
    A URL, file path, or cross-reference no longer resolves.
    Provide the broken reference and the correct target if known.
    Use the Broken Config template or Bug Report template.

  TYPOGRAPHICAL ERROR
    A clear spelling or grammatical error in English content.
    Specify the file path and line number.
    Use the Bug Report template.

  PLAGIARISM REPORT
    Evidence that content from this repository has been copied without
    authorisation to another platform, GitHub repository, or academic
    submission.
    Use the Plagiarism Report template.

  NEW EXPERIMENT PROPOSAL
    A concrete, well-reasoned proposal for a new experiment, concept
    laboratory, or challenge solution that fits one of the 19 domains.
    The owner reserves the right to implement the idea independently
    without using any externally contributed code.
    Use the New Experiment template.

  CONDUCT VIOLATION
    A violation of the Code of Conduct by another user in this
    repository's Issues, Discussions, or linked spaces.
    Use the Conduct Report template.

  NOT ACCEPTED

    - Pull Requests of any kind
    - Forks intended for republication
    - Requests to add projects on your behalf
    - Requests to rewrite or restructure content
    - Requests to add certifications or achievements
    - General computer science questions or tutoring requests
    - Questions about 42 School subjects or requirements
    - Questions about MIT, Harvard, Stanford, or other curricula

--------------------------------------------------------------------------------
                             HOW TO OPEN AN ISSUE
--------------------------------------------------------------------------------

  1. Go to: https://github.com/neivaeu/computer-science/issues/new/choose
  2. Select the appropriate Issue template.
  3. Use a clear, specific title following the template format.
  4. Fill in every required section completely.
  5. Provide the exact file path and line number where applicable.
  6. Provide evidence, references, or primary sources where applicable.
  7. Do not leave example text from the template in your submission.
  8. Do not open duplicate Issues — search first.

  Available Issue templates:

    [BUG]           Bug found in any project implementation
    [BROKEN-CONFIG] Broken dotfile, Makefile, or configuration file
    [EXPERIMENT]    Proposal for a new experiment or concept lab
    [PLAGIARISM]    Unauthorized copy of repository content
    [CONDUCT]       Code of Conduct violation report
    [GRAVEYARD]     Archive a project or experiment (owner-initiated)

--------------------------------------------------------------------------------
                       WHY THERE ARE NO PULL REQUESTS
--------------------------------------------------------------------------------

  This repository does not accept Pull Requests. The reasons are:

  1. PERSONAL ARCHIVE
     This is a personal knowledge base. Every implementation, note, and
     architectural decision reflects the owner's individual learning
     process. External code contributions would corrupt the integrity of
     that record.

  2. ACADEMIC INTEGRITY
     Many projects here originate from academic assignments (42 School,
     MIT, Harvard, Stanford, and others). Accepting external code would
     create serious academic integrity risks.

  3. QUALITY CONTROL
     The owner maintains specific standards for code style, documentation
     depth, and implementation approach across all 19 domains. These
     standards cannot be delegated.

  4. LEGAL CLARITY
     Accepting code contributions creates copyright co-ownership
     complications. All content must remain the unambiguous intellectual
     property of Pedro Neiva.

  If you identify an error, open an Issue. The owner will fix it.
  That is the correct and only supported workflow.

--------------------------------------------------------------------------------
                             STYLE REFERENCE
--------------------------------------------------------------------------------

  This section documents the standards applied throughout the repository.

  LANGUAGE
    All content is written in English without exception.

  ENCODING AND LINE ENDINGS
    UTF-8. LF (Unix line endings).

  TRAILING WHITESPACE
    None. All files must end with exactly one newline.

  INDENTATION

  ┌────────────────────────────────────────┐
  |  Language         |   Style    | Width |
  ├────────────────────────────────────────┤
  |  C / C++          |   tabs     |   4   |
  |  Makefile         |   tabs     |   4   |
  |  Assembly         |   tabs     |   4   |
  |  Python           |   spaces   |   4   |
  |  Java             |   spaces   |   4   |
  |  JavaScript / TS  |   spaces   |   2   |
  |  Web (HTML/CSS)   |   spaces   |   2   |
  |  OCaml            |   spaces   |   2   |
  |  Shell            |   spaces   |   2   |
  |  YAML             |   spaces   |   2   |
  |  JSON             |   spaces   |   2   |
  |  Markdown         |   spaces   |   2   |
  └────────────────────────────────────────┘

  C (42 SCHOOL PROJECTS)
    Must comply with the 42 Norminette.
    https://github.com/42School/norminette

  ALL OTHER PROJECTS
    Clean code principles:
      - Meaningful variable and function names
      - Single responsibility per function
      - Proper error handling — no silent failures
      - No dead code, no commented-out blocks

  MARKDOWN FILES
    Follows .markdownlint.json rules.
    Fenced code blocks with explicit language tags.

  FILE NAMING
    Lowercase with hyphens: my-file-name.md
    No spaces in file or directory names.
    Exception: 42 School project names are preserved exactly as they
    appear in the official 42 intranet.

  COMMIT MESSAGES
    Format: <type>(<scope>): <short description>

    Types:
      feat      New project, file, or feature added
      fix       Bug fix or correction
      docs      Documentation-only change
      refactor  Code restructure, no behaviour change
      test      Test addition or update
      chore     Build, config, or tooling change
      style     Formatting, whitespace, no logic change
      perf      Performance improvement
      security  Security fix or hardening

    Examples:
      feat(09-software-engineering): add Piscine Object Module 03
      fix(12-computer-graphics): correct broken submodule URL for ft_vox
      docs(readme): update domain table with 99-curriculum entry
      chore(.gitmodules): update all submodule paths to new domain slugs

  PROJECT DIRECTORY STRUCTURE
    Every project follows the same internal layout:

      <project>/
        docs/     Documentation, notes, subject PDF, write-up
        src/      Source code
        tests/    Test cases and validation scripts

  PROJECT NAMING
    Do not suggest renaming any project, directory, or submodule.
    All names are fixed, intentional, and governed by the owner.

--------------------------------------------------------------------------------
