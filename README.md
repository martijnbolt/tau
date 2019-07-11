# Tau Chain explainer
This document is the result of a little documentation project in an attempt to describe and explain [Tau Chain](https://github.com/IDNI/) for the masses. Eventually this resource could help with the communication about Tau Chain or even might help writing a scientific whitepaper about Tau Chain.
## Approach
Read the first 3 official blogs on idni.org (in reverse order, see [sources](#sources) below) and explain Tau in the [content](#content) of this document in such a way every (educated) person can understand and validate the information without deep understanding of mathematics, computer science, compiler design, etc. In the future in-depth knowledge could be added.
## Status
This is a ongoing endeavor. Current status is collecting and reading up on existing resources found on [bitcointalk](https://bitcointalk.org/index.php?topic=950309.0), in the Tau Chain [IRC chat](https://webchat.freenode.net/?channels=##idni), on [telegram](https://t.me/tauchain), blogs, steemit and elsewhere online. Found resources are listed in this file under [sources](#sources) and, after inspection, archived in the [archive](#archive) or integrated with the [content](#content) section.
## 3 step collaboration process
**1) Add URL's to resources** in the relevant category (or in [unsorted](#unsorted)) under [sources](#sources) below, preferably with a comment about it's contents. After reading, **2a) Remove and archive** irrelevant content (move URL from sources to the [archive](#archive) section, with a comment why), or **2b) Describe or explain** relevant content in a comprehensible manner in [content](#content). If the resource contains additional useful content afterwards, please **3a) add a comment** alongside the URL in the sources section. **3b) Remove and archive** the URL - again preferably with a comment - once all *relevant* content is documented and properly attributed.
## Join us
You're welcome to join, discuss or help along. Our 1000+ community can be found [here](https://t.me/tauchain).

# Content
## Abstract
* Tau Chain basics
## what problems it solves, the purpose for which Tau Chain was invented
* the Halting Problem or more generally Rice’s theorem, which demonstrate that reasoning over computer programs is mathematically impossible in most cases
## What is Tau Chain?
1. History
   * Ohad Asor
   * Zennet
1. [Features](https://thecreativecrypto.com/the-first-million-person-conversation-interview-ohad-asor-of-tau-chain/)
   * Knowledge market
   * Computational resources market
   * Advanced currency
## Technical functions
1. Data storage
   * Decentralize information storage and use while keeping it secure yet widely accessible
1. TML
   * TML is intended to be a compiler-compiler
   * there can not be a single universal language as no one language is optimal or adequate for all needs.
   * nobody knows how machines can use human languages, therefore tau can't use natural languages but machine comprehensible languages
   * machines need to understand the meaning of what we say, but computers expect operational information, while humans use declarative language. In Tau people focus on the "know-what" and machines figure out the "know-how". Tau uses formal logic as it is natural to humans and something machines can work with (cf. "Knowledge Representation and Classical Logic" by Lifschitz et al)
   * there are many formalisms of natural language that are close to natural language and comfortable for humans to work with (what we refer to "simple enough English that machines can understand")
   * a meta-language that can define new languages and is able to redefine itself and change, a self-amending language
   * users define new languages by specifying logical formulas to describe what it means for two documents in different languages to have the same meaning. To define a new language, one needs to define how it translates into an existing language while preserving semantics.
1. Futamura projections
   * Tau uses Partial Evaluation to prevent considering the logic of the language(s) again and again with every compilation of documents written in it. This adds desirable features for a compiler-compiler, in the form of Futamura projections.
1. the Internet of Languages
   * Infrastructure
   * users define languages over the internet of languages. Users can express knowledge and opinions in these languages in order to communicate.
   * With Tau users express themselves in decidable machine-comprehensible languages. This facilitates Human-Machine-Human communication where Tau organizes what we say and is able to do so since we encode our information in a way accessible to it.
   * Semantics in Tau is ontological (objects and relations), not operational as in programming languages, to get an internet of knowledge representation languages. A document in one language can be routed (using TML programs) into other languages
   * language translation by synthesizing code from specifications using synthesis capabilities from the MSO+λY world
1. Agoras
* [named](https://github.com/naturalog/Bitagoras) after the Ancient Agora of Athens)
   1. knowledge market
   1. computational resources market
   1. derivatives market (newly designed economy offering features like risk free interest without printing new money)
   * advanced monetary system
1. Self-defining scalable system
   * gather knowledge and agree or disagree over it, and perform automated actions arising from the discussion
   * a decentralized program that everyone writes, a program that is waiting for its users to tell it what to do. That program can be the rules of the blockchain itself, effectively [democratizing the rules of governance](https://thecreativecrypto.com/the-first-million-person-conversation-interview-ohad-asor-of-tau-chain/) at the most fundamental level allowing all users equal rights
   * Tau Chain allows users to change the choice mechanism of itself by having clear rules of changing the rules, to change Tau's code with time
    recursion in order to deal with rules of changing the rules. This is an important aspect involved in the choice of fixed-point logic for TML, and λY calculus on the Beta (apropos, Bauer showed in "On Self-Interpreters For System-T and Other Typed λ-Calculi" that a language can self-interpret only if it has fixed point, which rules out total programming languages)
1. Self-defining deterministic logic
   * Tau doesn't guess the people's opinion. that's the main reason we use logic, not ML for example
   * Why the logic was chosen with regard to partial fixed point
   * Tau uses PFP logic known from Finite Model Theory with PSPACE-complete expressiveness, decidability and self-defining properties (Imhof, 1999 "Logics that define their own semantics")
1. Tau
   * choices collaboratively be made over the system, are about the system itself. Tau, is a discussion about Tau.
   * a collaboratively self-amending program that can be anything or many programs at once
   * Over Tau many drafts that propose Tau's next full code can be submitted by users. Using the logical formalism of these documents Tau can calculate the precise core that everyone agrees on, and list the points to be resolved. Users discuss the future Tau and the opinions map arises from the conversation, determining the next Tau.
## Business/use cases
Tau can be anything that its users want it to be, as they ultimately collaboratively determine the very code of the network. Examples:
1. [large scale discussions](https://thecreativecrypto.com/the-first-million-person-conversation-interview-ohad-asor-of-tau-chain/)
* we cannot ever vote on whether something should be voted on in the first place
* theoretical inability to comprehend the consequences of proposals which could compromise the security of the system
*  a [social choice](http://www.idni.org/blog/the-new-tau) mechanism where small or very large group of people repeatedly reach and follow agreements.
   * language
   transmitting one idea between two people - formalized in a machine comprehensible language - allows for easy explaining, easy understanding, and produces formalized knowledge.
   * knowledge
   limits that affect flow and processing of information
   collaborative theory formation
   Ideas that are formalized in a machine comprehensible language allows users to translate it to other knowledge representation languages, to reorganize it or to compare it to other formalized ideas. From this Tau gains the ability to answer questions about an idea in a decidable manner, without the need to refer the question to the original idea's author
   * discussion
   collaborative decision making
   methods of discussions so far suffer from very poor scaling
   voters go over equally-weighted one million proposals daily
   * collaboration
      * Scaling limits
      * discuss, share and organize knowledge, detect consensus and disagreements, and coordinate actions in forms of programs
      * automatically detect repeated argument by same person
      * collecting what each person said during the discussion
      * map all the agreement and disagreement points
      * list all opinions and then who agrees with them rather (speakers per opinion rather opinions per speaker)
      * organize the information put on the discussion in more organized and readable forms like a wiki
      * comment automatically and automatically express your opinion, based on the information you provided in the past, and relative to the post you're autocommenting to.
      * calculate the set of statements agreed by everyone, network wide, per team, per profiles connected to the users profile, per discussion, and so on.
   * choice about choice
      * opinions flow through certain pipes and reach the voting stage almost empty from the vast information gathered in the process
      * everyone has an equal right to propose what to vote over
      * If rules can change themselves, they inevitably contradict themselves as they try to say something else. This is formalized in a paradox-free manner using recursion.
2. Wolfram alpha
* see video
## Roadmap
1. TML and the internet of languages
1. discussions of any scale (alpha)
* identities dealing with e certain subject are grouped in teams
* teach the network a lot of knowledge, intentionally or as a byproduct of discussions
1. collaboratively following processes (not just defining them) (beta)
* discuss programs, and then run them
* A special team called Tau is formed, whenever this group accepts a new decision, Tau's code is automatically modified
* development of language transformers for language translation over the internet of languages by synthesizing code from specifications
1. Tau, decentralized self-amending social choice platform
1. agoras
## Technical details
* Integrate .pdf's and discussion from IRC + bitcointalk

# Sources
Below is a (growing) list of URL's to resources that need to be inspected and curated in order to reflect the new tau, following the [process](#process) mentioned above.
## Official blog
Read this first, in this order:
* http://www.idni.org/blog/the-new-tau
* http://www.idni.org/blog/agoras-to-tml
* http://www.idni.org/blog/art-of-self-ref
* http://www.idni.org/blog/tau-and-the-crisis-of-truth (optional/later read)
## General
* https://steemit.com/blockchain/@kevinwong/what-is-tauchain-and-why-it-could-be-one-of-the-greatest-inventions-of-all-time-part-1
* https://steemit.com/tauchain/@rok-sivante/tauchain-101-essential-reading-on-one-of-the-most-revolutionary-blockchain-project-under-the-radar
* https://steemit.com/tauchain/@dana-edwards/tauchain-is-not-easy-to-understand-but-here-are-some-concepts-to-know-to-track-ohad-s-progress
* https://steemit.com/tau-chain/@flis/the-vision-of-tau-chain-a-blockchain-based-self-amending-program-designed-to-scale-human-collaboration-and-knowledge-building
* https://steemit.com/tauchain/@dana-edwards/can-we-use-tauchain-eos-tezos-ethereum-to-bring-about-a-new-age-of-enlightenment
* https://steemit.com/tauchain/@rok-sivante/tauchain-strap-in
* https://steemit.com/tauchain/@rok-sivante/simplifying-tauchain-what-you-need-to-know-about-one-of-the-most-fascinating-significant-projects-on-the-block-chain
* https://medium.com/@RokSivante/simplifying-tauchain-what-you-need-to-know-about-one-of-the-most-fascinating-significant-projects-60b1d99bc88
* https://github.com/naturalog/Bitagoras (up to now: only used the agoras name reference)
* https://steemit.com/tauchain/@flis/tau-is-a-discussion-about-tau
* https://steemit.com/cryptocurrency/@trafalgar/what-is-tau-my-only-other-crypto-investment
* https://steemit.com/eos/@rok-sivante/eos-vs-tezos-vs-tauchain-the-dummies-simplification-of-possibly-the-biggest-blockchain-launches-of-2017
## TML
* https://steemit.com/crypto-news/@dana-edwards/the-first-instance-of-tau-metalanguage-tml-has-appeared-on-github
* https://steemit.com/tauchain/@dana-edwards/tau-the-programming-language-and-context-free-grammar
* https://steemit.com/tauchain/@dana-edwards/using-controlled-english-as-a-knowledge-representation-language
## Agoras
* https://steemit.com/agoras/@flis/the-future-split-of-agoras-tokens
## Internet of languages
* https://steemit.com/tauchain/@dana-edwards/tauchain-the-internet-of-languages-and-precise-communication-ambiguity-minimized
## Why the logic was chosen
* https://steemit.com/tauchain/@dana-edwards/tauchain-advanced-concepts
## Partial fixed point
* https://steemit.com/tauchain/@dana-edwards/tau-meta-language-and-the-notion-of-fixed-point
* https://steemit.com/tauchain/@dana-edwards/tauchain-tml-partial-fixed-point-logic-and-it-s-unique-benefits
## Linear independent hashing algorithm
* https://steemit.com/tauchain/@dana-edwards/tml-development-introduction-of-a-linear-independent-hashing-algorithm
## Turing
* https://steemit.com/computation/@dana-edwards/real-computers-vs-turing-machines
## Binary decision diagrams
* https://steemit.com/tauchain/@dana-edwards/programming-useful-data-structures-binary-decision-diagrams
* https://steemit.com/tauchain/@dana-edwards/tauchain-update-significant-code-changes-in-github-and-discussion-of-progress
## Subsumption optimization vs magic sets
* https://steemit.com/tauchain/@dana-edwards/tauchain-r-and-d-analysis-and-discussion-subsumptive-tabling-beats-magic-sets
## Automated reasoning
## Context free grammar / parsing
* https://steemit.com/tauchain/@dana-edwards/a-great-video-on-parsing-for-all-studying-tauchain
* https://steemit.com/programming/@dana-edwards/what-are-context-free-grammars-cgfs
## Compilers/partial evaluation
* https://steemit.com/tauchain/@dana-edwards/for-all-who-are-researching-tauchain-tml-to-understand-how-it-works-a-nice-video
## Futamura projection
* https://steemit.com/tauchain/@dana-edwards/tauchain-and-the-mysterious-futamura-projections
## TML with negation and optimization
* https://steemit.com/tauchain/@dana-edwards/understanding-tml-prolog-datalog-tau
## Forward chaining
* https://steemit.com/crypto-news/@dana-edwards/should-agoras-token-become-an-erc20-token-until-the-release-of-the-alpha
## Self defining/self amending blockchain
* https://steemit.com/life/@dana-edwards/self-replication-dna-and-tauchain
* https://steemit.com/crypto-news/@dana-edwards/tauchain-and-tezos-why-adaptability-is-the-key-to-surving-in-a-fast-changing-environment
## Social/metrics/consensus/morality/voting/regret/collaboration
* https://thecreativecrypto.com/the-first-million-person-conversation-interview-ohad-asor-of-tau-chain/ (interview Ohad, basics and large scale conversations usecase) [@martijnbolt ]
* https://steemit.com/tauchain/@ponpase/tau-chain-and-agoras-the-only-dynamic-decentralized-social-network
* https://steemit.com/technology/@dana-edwards/thinking-outside-the-brain-why-we-need-to-build-a-decentralized-exocortex-part-2
* https://steemit.com/tauchain/@dana-edwards/the-wide-world-of-scores-and-tau
* https://steemit.com/tauchain/@dana-edwards/tauchain-the-social-dispersed-computer-introduced-as-a-social-network
* https://steemit.com/tauchain/@dana-edwards/truth-vs-consensus-which-is-more-important
* https://steemit.com/crypto-news/@dana-edwards/consensus-morality-and-tauchain-or-consensus-gentium
* https://steemit.com/tauchain/@dana-edwards/how-tauchain-can-empower-africa-from-the-start
* https://steemit.com/tauchain/@trafalgar/the-power-of-tau-scaling-the-creation-of-knowledge
* https://steemit.com/tauchain/@dana-edwards/how-can-we-minimize-regret-can-tauchain-help-us
* https://steemit.com/tauchain/@dana-edwards/ohad-asor-the-lead-developer-and-founder-of-tauchain-releases-first-new-blog-post-in-over-a-year
* https://steemit.com/tauchain/@dana-edwards/artificial-morality-moral-agents-and-tauchain
* https://steemit.com/tauchain/@rok-sivante/why-tauchain-connecting-the-dots-from-personal-vision-to-collective-innovation-part-one
* https://steemit.com/tauchain/@rok-sivante/why-tauchain-connecting-the-dots-from-personal-vision-to-collective-innovation-part-two
## Business/usecases
* https://steemit.com/tauchain/@dana-edwards/how-to-make-tau-agoras-good-for-business
* https://steemit.com/tauchain/@dana-edwards/let-s-use-tauchain-to-save-our-own-lives-and-the-lives-of-others-the-life-saving-potential-of-tauchain
* https://docs.google.com/document/d/1zYNNbSLTT4uCq3tNTzhc4a_mICoEI2aT8eYVrFwP8oA/edit
* https://steemit.com/tauchain/@dana-edwards/why-tauchain-needs-to-exist-collaborative-healthcare-and-decentralized-gene-therapy-research
* https://steemit.com/tauchain/@dana-edwards/what-tauchain-can-do-for-us-collaborative-serious-alternate-reality-games
* https://steemit.com/tauchain/@dana-edwards/what-tauchain-can-do-for-us-finding-the-world-s-biggest-problems
* https://steemit.com/tauchain/@dana-edwards/what-tauchain-can-do-for-us-effective-altruism-tauchain
* https://steemit.com/tauchain/@dana-edwards/monitoring-and-adapting-to-the-winds-of-change
* https://steemit.com/tau-chain/@flis/how-tau-chain-can-be-implemented-in-practice
* https://steemit.com/tauchain/@karov/tutor-ex-machina
* https://cointelegraph.com/news/tau-chain-a-decentralized-app-store-with-greater-flexibility-than-ethereum
## Privacy
* https://steemit.com/tauchain/@dana-edwards/tauchain-and-the-privacy-question-benefits-of-secret-contracts-and-private-knowledge
* https://steemit.com/tauchain/@dana-edwards/how-to-prevent-tauchain-from-becoming-skynet
## Smart constitution
* https://steemit.com/tauchain/@dana-edwards/tauchain-may-allow-for-the-development-of-the-first-smart-constitution
## Self religion
* https://steemit.com/tauchain/@dana-edwards/will-tauchain-allow-for-augmented-self-religions
## Marketing
* https://steemit.com/tauchain/@dana-edwards/tauchain-passion-addressing-the-need-for-a-marketing-strategy
* https://steemit.com/tauchain/@capitanart/improving-tauchain-and-agoras-branding
## People/team
* https://steemit.com/cryptocurrency/@kevinwong/is-tauchain-agoras-in-good-hands
## Tauchain videos
* https://steemit.com/tauchain/@dana-edwards/interview-about-tauchain-and-agoras-with-ohad-asor-2016
* https://steemit.com/tauchain/@dana-edwards/new-coininterview-with-ohad-asor-on-tauchain
* https://www.youtube.com/watch?v=zFmaX-oumNw
* https://www.youtube.com/watch?v=Utggm7cuGbo
* https://youtu.be/1SXfYgQxsOA
* https://youtu.be/3ORpi2MMJrA
* https://youtu.be/TKhzo_60f6Y
* https://youtu.be/Zfx8xqP0XGI
* https://youtu.be/lxrofNHiq9Y
* https://youtu.be/6G8mTCtv8d8
* https://youtu.be/MTARBWPRmxk
## Unsorted
* https://steemit.com/tauchain/@dana-edwards/tauchain-the-automated-webslueth-the-sherlock-holmes-bot-concept-for-discussion
* https://docs.google.com/document/d/1zYNNbSLTT4uCq3tNTzhc4a_mICoEI2aT8eYVrFwP8oA/edit (previous whitepaper attempt by Dana, still partially relevant)
* http://zennet.sc/about/index.html (original decentralised supercomputer idea)
* http://www.idni.org/blog/generalized-blockchain
## Meta/other
* https://steemit.com/writing/@dana-edwards/how-to-write-a-good-thesis-paper
* https://guides.github.com/features/mastering-markdown/
## Related projects
* https://www.legalrobot.com/
    Centralised platform that helps to transform legal documents into human readable form
* http://www.estrellaproject.org/
    Open projec focused on data formalisation in area of legal afairs
* https://www.focafet.org/
    1language initiative focused on transaction standardisation
* https://www.northchain.tech/en/how-ole-works/
    OLE, project of prof. Herman Balsters, executable and 100% error-free blockchain code
# Archive
* https://bravenewcoin.com/insights/tau-chain-a-programmers-perspective (irrelevant @martijnbolt)
