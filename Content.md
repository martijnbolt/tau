# Abstract
* Tau Chain basics
# what problems it solves, the purpose for which Tau Chain was invented
* the Halting Problem or more generally Rice’s theorem, which demonstrate that reasoning over computer programs is mathematically impossible in most cases

# What is Tau Chain?
## History
* Ohad Asor
* Zennet
* Old Tau neglected the social side.
## [Features](https://thecreativecrypto.com/the-first-million-person-conversation-interview-ohad-asor-of-tau-chain/)
* Knowledge market
* Computational resources market
* Advanced currency

# Technical functions
## Decentralised computations and data storage
* Decentralize information storage and use while keeping it secure yet widely accessible
* the ability to fairly rent (and rent-out) computational resources, under acceptable risk in the user's terms (as a function of cost)
## decentralised searche engine
* featuring a decentralised search engine that, to some probabilistic extent, ensures that the index contains the correct knowledge (isn't modified, replaced, or omitted).
* using a pricing [formula](http://zennet.sc/zennetpricing.pdf) to eliminates the risk of mispricing, a risk that can be significantly exploited
* probabilistically verify unverifiable computations by calculating the same thing more than once (by randomly choosing more providers), so increasing the cost linearly, decreases the risk exponentially (e.g. x10 more cost yields ^10 less risk)
## TML
* TML is intended to be a compiler-compiler
* there can not be a single universal language as no one language is optimal or adequate for all needs.
* nobody knows how machines can use human languages, therefore tau can't use natural languages but machine comprehensible languages
* machines need to understand the meaning of what we say, but computers expect operational information, while humans use declarative language. In Tau people focus on the "know-what" and machines figure out the "know-how". Tau uses formal logic as it is natural to humans and something machines can work with (cf. "Knowledge Representation and Classical Logic" by Lifschitz et al)
* there are many formalisms of natural language that are close to natural language and comfortable for humans to work with (what we refer to "simple enough English that machines can understand")
* a meta-language that can define new languages and is able to redefine itself and change, a self-amending language
* users define new languages by specifying logical formulas to describe what it means for two documents in different languages to have the same meaning. To define a new language, one needs to define how it translates into an existing language while preserving semantics.
* Tau uses Partial Evaluation to prevent considering the logic of the language(s) again and again with every compilation of documents written in it. This adds desirable features for a compiler-compiler, in the form of Futamura projections.
## the Internet of Languages
* Infrastructure
* users define languages over the internet of languages. Users can express knowledge and opinions in these languages in order to communicate.
* With Tau users express themselves in decidable machine-comprehensible languages. This facilitates Human-Machine-Human communication where Tau organizes what we say and is able to do so since we encode our information in a way accessible to it.
* Semantics in Tau is ontological (objects and relations), not operational as in programming languages, to get an internet of knowledge representation languages. A document in one language can be routed (using TML programs) into other languages
* language translation by synthesizing code from specifications using synthesis capabilities from the MSO+λY world
## Self-defining deterministic logic as a scalable system
* gather knowledge and agree or disagree over it, and perform automated actions arising from the discussion
* Tau doesn't guess the people's opinion. that's the main reason we use logic, not ML for example
* a decentralized program that everyone writes, a program that is waiting for its users to tell it what to do. That program can be the rules of the blockchain itself, effectively [democratizing the rules of governance](https://thecreativecrypto.com/the-first-million-person-conversation-interview-ohad-asor-of-tau-chain/) at the most fundamental level allowing all users equal rights
* Why the logic was chosen with regard to partial fixed point: Tau Chain allows users to change the choice mechanism of itself by having clear rules of changing the rules, to change Tau's code with time recursion in order to deal with rules of changing the rules. This is an important aspect involved in the choice of fixed-point logic for TML, and λY calculus on the Beta (apropos, Bauer showed in "On Self-Interpreters For System-T and Other Typed λ-Calculi" that a language can self-interpret only if it has fixed point, which rules out total programming languages)
* Tau uses PFP logic known from Finite Model Theory with PSPACE-complete expressiveness, decidability and self-defining properties (Imhof, 1999 "Logics that define their own semantics")
## Tau
*social*
* governance model, decided by the users
* choices collaboratively be made over the system, are about the system itself. Tau, is a discussion about Tau.
* users decide who can change the rules (in a decentralized setting)?
*technical*
* a collaboratively self-amending program that can be anything or many programs at once
* Over Tau many drafts that propose Tau's next full code can be submitted by users. Using the logical formalism of these documents Tau can calculate the precise core that everyone agrees on, and list the points to be resolved. Users discuss the future Tau and the opinions map arises from the conversation, determining the next Tau.
## Agoras
* Knowledge economy, [named](https://github.com/naturalog/Bitagoras) after the Ancient Agora of Athens)
1. knowledge market
   *social*
   * consists of users that execute searches and simultaneously maintain the data
   * home and institutional users use and support the infrastructure by running a client. costs usually even-out, though heavy users pay more, heavy maintainers earn more
   *technical*
   * utilising the decentralised search engine and data storage
1. computational resources market
   * maintainers index the knowledge on the web, charge a fee for answers on queries that depends on the amount of usage and the cost of maintenance
1. derivatives market (newly designed economy offering features like risk free interest without printing new money)
   * advanced monetary system
   * the monetary features that Agoras will support
   * ethical value systems in the broad sense, defining good and bad, better and worse as an economy without some subjective valuation or "utility function" can't exist

# Business/use cases
Tau can be anything that its users want it to be, as they ultimately collaboratively determine the very code of the network. Examples:
## automated scheduling
* from app demo on idni.org
## [scaleable decision making](https://thecreativecrypto.com/the-first-million-person-conversation-interview-ohad-asor-of-tau-chain/)
* we cannot ever vote on whether something should be voted on in the first place
* theoretical inability to comprehend the consequences of proposals which could compromise the security of the system
* A [social choice](http://www.idni.org/blog/the-new-tau) mechanism where small or very large group of people repeatedly reach and follow agreements.
A chronological and conceptually bottom-up order about the creation of a knowledge society.
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
   * change (choice about choice)
      * opinions flow through certain pipes and reach the voting stage almost empty from the vast information gathered in the process
      * everyone has an equal right to propose what to vote over
      * If rules can change themselves, they inevitably contradict themselves as they try to say something else. This is formalized in a paradox-free manner using recursion.
   * knowledge market
      * based on agoras'
      * hardware rent market using Agoras' decentralised search engine
      * a knowledge economy, on top of the knowledge society
      * using decentralised search engines, data storage and computation
## Structured knowledge
* Similar to wolfram alpha?
## knowledge economy
   * based on agoras' knowledge market
   * lives on knowledge society-framework Tau
   * an economic system that supports the production, pricing, shipment, and arena (agora), of some knowledge (the knowledge of the text on the web)
   * deeper and more meaningful knowledge than existing static searched based on thesaurus and ML that has no real understanding of the subjects

# Roadmap
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
# Technical details
   * Integrate .pdf's and discussion from IRC + bitcointalk
