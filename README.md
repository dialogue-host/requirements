# 🌸 Dialogue - Social Media

**Tools for all humans to collectively think, decide and act under any form of repression.**

---

## Core Principles

*Core principles* clarify Dialogue's *aim* described above. They are fairly general but each highlights different aspects of the platform. See the [rationale section](#core-principles-rationale) for a detailed description of each principle.

### Tools

- **Transparent**: Actively expose and explain all platform mechanisms, algorithmic systems, and community processes to enable informed user participation and control.
- **Modular**: Support community-driven development by building every interface and algorithm as swappable components that can be addapted by users to their specific needs.
- **Empirical**: Rigorously justify, study and stress test every feature to ensure its functioning truly align with the platform's *aim*.

### For All Humans

- **Empathic**: Support peoples physical and mental well being, foster honesty, mutual respect and understanding, inclusiveness and constructive communication.
- **Assertive**: Encourages people to stand up for their own needs and values, to confront differing opinions and ideas and promote moderation in the face of domination, harassment and instrumentalization.
- **Accessible**: Ensure accessibility and ease of use to the largest amount of people possible by considering technical knowledge, economical status, cultural background, physical and mental disabilities, spoken languages, literacy and every other possibly hindering factor.
- **Attractive**: Bring local and online communities onboard by implementing win win mechanisms and focusing on their concrete needs.
- **Durable**: Ensure the platform's social and technical foundations remain viable and relevant for generations.

### To Collectively Think

- **Empowering**: Entrust people with control over their digital environment and enable them to decide on contents they want to be exposed to or to moderate.
- **Collaborative**: Foster collaboration, cooperation and collective creative work among people, groups and communities.
- **Expressive**: Provide spaces for creative expression, public discourse and knowledge sharing.
- **Informative**: Create community-driven systems for news gathering, investigation and reporting able to highlight biases and diverging opinions.

### To Collectively Decide

- **Deliberate**: Provide methods and tools for collaborative deliberation, discussion and thoughtful consideration of differing opinions.
- **Democratic**: Make bottom up, collective human decision-making more efficient, reliable and accessible than centralized systems both at local and global scales.

### To Collectively Act

- **Optimistic**: Builds confidence in our collective ability to overcome current challenges and shape better futures through human ingenuity and collective action.
- **Sustainable**: Implement various means for platform developers, content creators and other contributors to get revenue and sustain their work on the long term.

### Under Any Form of Repression

- **Private**: Guarantee personal data sovereignty and communication confidentiality.
- **Resilient**: Maintain platform availability and usability even in places where it has been outlawed.
- **Safe**: Ensure users can communicate without fear of identification or retribution even in repressive environments.
- **Independent**: Organize platform architecture and governance in a way that can resist and survive possible coercion from states or multinational corporations.

## Contribute

Our current priority is to complete this document, to clarify its concepts and to start designing the platform's architecture. The best way for you to contribute is to send your remarks and suggestions as a *GitHub* issue or sending them directly to me.

Spotting ideas that lack clarity or words that need explanation - especially for people with no technical background - is of interest. Many technical aspects are lacking as this document is work in progress but please inform us about any consideration that we might be missing. There is no dumb remarks as long as they are stated in a respectful manner.

## Requirements

Here we build up a set of requirements. They are classified either as *crucial*, *important*, *desirable* or *two sided*. We also state which *core principle* each aims to fulfill. The reasoning justifying their prioritization and expected impacts has to be described if not self evident. The quality of a requirement comes from its clarity, concision, completeness, consistency, correctness, concreteness, specificity, measurability and actionability. We write the requirements using assertive wordings. The requirements are numbered only for referencing sake and not as a hierarchization.

We group requirements into different *systems*. We aim to minimize their size and interdependency. For each, we describe the *plan* we expect to follow to get the *system* to a complete state. The quality of a *plan* is evaluated based on how well it fulfills the requirements, which uncertainties it presents, how well the costs are balanced with sources of funding, which peoples and communities could be interested in contributing, how much work and time is required to attain completion.

### Name

| ref | requirement | fulfills | priority |
| --: | ----------- | -------- | -------- |
| 1. | Have a meaning that mirrors the platform's intent and purposes. | *transparent* and *attractive* | *crucial* |
| 2. | Be readable and pronounceable in a large amount of languages. | *accessible* | *important* |
| 3. | Be memorable and findable. | *attractive* | *important* |

*Dialogue* is a great name that is short, that is pronounceable in many languages and that really highlights much of the philosophy behind the project.

> A dialogue consists of a cross-examination of different speeches, all of which commit their author. It is not about imposing a cognitive point of view, a perspective or reference. Each word transmitted in communication seeks to be decoded and received by the recipient, then to signify something that has meaning in their own existence. Dialogue calls for the actors of communication to be transformed in their being, in complete freedom. Active listening, sincere humility and mutual respect are therefore necessary. A successful dialogue produces a diagnosis integrating all the arguments of the participants and a conclusion in which they all agree. - *paraphrasing french wikipedia*

We will be using the `dialogue.host` domain at first and buy ones such as `dialogue.net` and `dialogue.media` as the project gains traction and funding.

| ref | impact | problem/solution |
| --: | ------ | ---------------- |
| req1 | +++ | The notion of dialogue has a clear social aspect, it reflects really well the idea that people are here to listen to one an other (*empathic*), exchange thoughts and ideas (*expressive*), find contradictions in their differing view points (*informative* and *empirical*) and collaborate toward possible solutions (*optimistic* and *democratic*). |
| req2 | ++ | This name also is easy to pronounce and has the same meaning in many languages. |
| req3 | + | It isn't widely used online and a quick search mostly lists dictionaries so it might also be a good name for SEO. Also the ideal domains are unused as of now. |
| cost | - | The `dialogue.net`(registered but unused) and `dialogue.media` (6600$ on [porkbun](porkbun.com)) domains are quite expensive although `dialogue.host` is already a fairly good domain. |

### Visual Identity

The visual identity has essentially the exact same requirements than the platform's name.

The cherry flower 🌸 symbolizes hope, renewal and peace and its soft pink color brings care, kindness, playfulness and joy. The cherry blossom is a very poetic symbol as it embraces the perpetual transformation of the world and announces "le temps des cerises". Although pink can be stereotyped as feminine and romantic, these stereotypes have been challenged by various gender equality movements. Nevertheless to soften these prejudices we can use lighter pastel tones that are less connoted than brighter ones.

But it is not a spotless symbol as it has been used to motivate japanese militarism, nationalism and kamikaze action. But this association doesn't seem to be too deeply ingrained in the japanese imaginary and doesn't seem to come up anywhere else (as of our current understanding).

| ref | impact | problem/solution |
| --: | ------ | ---------------- |
| req1 | +++ | It is a beautiful symbol that matches the **optimistic**, **empathic**, **assertive** and **resilient** principles. |
| req2 | ++- | It has an important cultural baggage in many cultures and is widely understood as a symbol of care, hope and renewal. |
| req3 | +++ | The cherry flower is a very poetic symbol that is quite memorable. |

### Governance

The form that an organization takes shapes what it produces. As we do not want Dialogue to steer off course, we have to be very thoughtful of the way we structure ourselves, take decisions and operate.

| ref | requirement | fulfills | priority |
| --: | ----------- | -------- | -------- |
| 1. | Always justify descisions relative to the platform's *aim* and *core principles*. | *empirical* and *durable* | *crucial* |
| 2. | Be in a process of constant adaptation to our changing world while maintaining Dialogue's original *aim*. | *durable* | *crucial* |
| 3. | Communicate publicly about funding, inner processes and decisions while hiding aspects that could endenger the platform's infrastructure and the people involved. | *transparent* and *resilient* | *crucial* |
| 4. | Prevent state or corporate interests from infiltrating and/or taking over deciding bodies. | *independent* | *crucial* |
| 5. | Keep the organization, its development processes and infrastructure working even under state level interdiction and repression. | *resilient* | *important* |
| 6. | Evaluate, compare to intent and correct in case of misalignment every decision's concrete effects. | *empirical* | *crucial* |
| 7. | Support and credit contributors to ensure their longevity and recognition. | *sustainable* | *desirable* |
| 8. | Represent human diversity amoungst members of the descision bodies. | *empathic* | *important* |
| 9. | Communicate enthusiastically over the work being done, the problems being solved and the systems being built toward. | *optimistic* and *attractive* | *desirable* |
| 10. | Gather, consider, answer and tackle user questions and remarks. | *empirical*, *accessible* and *durable* | *important* |
| 11. | Defend the interests of peoples with various impairments that are unable to involve themselves in the desciding bodies. | *empathic* | *important* |

The project will happen in three phases : An initial phase where only the project's *initiators* are involved. A second phase where the project starts getting traction, more people get involved and the platform is built. And a third where the platform has to be maintained and improved. We consider different roles and responsibilities for each phase.

During the first phase, the *initiators* will be responsible for defining the initial project's aims, epistemology and methodology through the first few versions of its requirements. They will also initiate the platform's dynamic culture and serve as the first members of the *governing organ*.

For the next two phases the *governing organ* will be the deciding body responsible of the project's development and evolution. ...

All other contributors will be part of the *contributor agora*. They can provide feedback, report bugs, and suggest improvements. ...

- roles
  - initiators
    - define the initial project's aims, epistemology and methodology through its requirements
    - initiate the platform's dynamic culture
  - governing organ
    - admission process based on implication level, understanding and accordance with project aims, epistemology and methodology
    - measures
      - empathy -> active listening
      - impication -> reading a corpus of content
    - exclusion process
    - rehabilitation process and transformative and restorative justice
    - continuous internal transformation process
    - decision process through contextualization report and synthesis committees
    - elected and revocable coordination roles
  - contributor agora
    - input gathering process to push topics on the governing organ's agenda
  - operational roles
- communication tools
  - dialogue on the long term for its own maintenance and evolution
  - other forum software in the meantime
  - in person before those are set up

We start as a temporary benevolent dictatorship. Even though it is a very fragile and centralized mode of organization, it ensures alignment with the project's initial intent. Our perspective is to use the organizational tools of *dialogue* to progressively build up processes and transfer governance to its most dedicated contributors.

| ref | impact | problem/solution |
| --: | ------ | ---------------- |
| unknown | -- | Which and how many people will get involved? What are their reasons? |

-- wip

The governing board are the initiators of the platform's culture and its members have to be the prime examples of its *core principles*. Their behavior towards the rest of the community sets the tone and the spirit of the platform. This is a crucial responsibility.

Opportunism has to be strongly rejected to avoid the corporatisation happening in many non profits such a Wikipedia or Mozilla where board members progressively increase their salaries and hoarding their organization's resources.

For now though, we are too early in the platform's development to clearly sketch out any clear *plan*. We can learn form [Open Collective](https://opencollective.com/) in terms of managing funds. Many political and journalistic organizations such as [Wikileaks](https://wikileaks.org/) also have a lot to teach us in terms of functioning in illegality.

### User Interface Design

| ref | requirement | fulfills | priority |
| --: | ----------- | -------- | -------- |
| 1. | Minimize the amount of primitives, concepts and techniques needed to master the interface. | *accessible* | *crucial* |
| 2. | Minimize the potential for errors, bugs and unexpected behavior by designing helpful constraints that avoid error prone conditions. | *durable* and *accessible* | *crucial* |
| 3. | Make the system status explicit and shorten the feedback loop to make it more predictable. | *attractive* | *crucial* |
| 4. | Speak the user's language by following existing conventions and avoiding jargon. | *accessible* | *important* |
| 5. | Organize and hierarchies information from the most urgent and important to the least while avoiding duplicated and irrelevant information. | *attractive* and *accessible* | *important* |
| 6. | Focus on the learning process and dynamically adapt the difficulty curve to the user. | *attractive* and *accessible* | *crucial* |
| 7. | Be efficient for experts to use by providing tailored shortcuts. | *attractive* and *durable* | *important* |
| 8. | Have a clear way to undo actions for users to be able to easily correct their mistakes and feel confident that they won't get stuck and frustrated. | *accessible* | *important* |
| 9. | Maintain a shared lexicon of words, symbols and interactions for every interface to be consistent and predictable throughout the platform. | *accessible* and *durable* | *important* |
| 10. | Minimize user's memory load by making the information required to use the interface immediately visible or easily retrievable through information bubbles. | *accessible* | *desirable* |
| 11. | Express error messages in plain language (no error codes), precisely indicate the problem, and constructively suggest solution(s) that can be applied by a single click if possible. | *accessible* and *durable* | *crucial* |
| 12. | Make the mental model structuring the system explicit and intuitive. | *attractive* and *accessible* | *crucial* |
| 13. | Handle phone, computer and tablet's screen formats as well as their corresponding touch screen, touchpad, mouse and keyboard inputs. | *accessible* | *important* |
| 14. | Follow [web content accessibility guidelines](https://www.w3.org/WAI/standards-guidelines/wcag/). | *accessible* | *important* |
| 15. | Make extensive user research to better understand their needs, concerns and blocking points. | *accessible*, *empathic* and *empirical* | *crucial* |
| 16. | Let users seek information instead of imposing information to them or needlessly attracting their attention. | *empathic* and *empowering* | *desirable* |

### Coding Conventions

| ref | requirement | fulfills | priority |
| --: | ----------- | -------- | -------- |
| 1. | Organize data around a single source of truth. | *accessible* and *durable* | *crucial* |
| 2. | Push for locality of behavior while avoiding code duplication. | *accessible* and *durable* | *important* |
| 3. | Make code self explanatory through its structure and naming convention. Each symbol's name has to convey why it exists, what it does and how it is used. | *accessible* and *durable* | *crucial* |
| 4. | Document everything that cannot be made immediately obvious. | *accessible* and *durable* | *important* |
| 5. | Follow the relevant [*user interface design* requirements](#user-interface-design-heuristics) whenever designing a package or extension. | *accessible*, *attractive* and *durable* | *important* |
| 6. | Follow a standard code formatting. | *durable* | *desirable* |
| 7. | Statically check everything that can be. | *durable* and *secure* | *desirable* |

### Programming Language (Dialang)

The programming language is the lowest level user interface of Dialogue and one of its most basic building blocks. Sadly no existing programming language is close enough to the following requirements so we have to create our own. Also we want to avoid cumulating multiple programming languages and complexifying our stack because of the first requirement.

| ref | requirement | fulfills | priority |
| --: | ----------- | -------- | -------- |
| 1. | The compiler has to be thought out as an user interface and follow the relevant [*user interface design* requirements](#user-interface-design-heuristics). | *accessible* | *crucial* |
| 2. | Enforce [*coding conventions*](#coding-conventions) where possible, facilitate and encourage their use otherwise. | *accessible* and *durable* | *important* |
| 3. | Make side effects very explicit and controllable to minimize the potential for hiding malicious code in packages and extensions. | *transparent*, *secure* and *resilient* | *crucial* |
| 4. | Have first class meta-programming to support tooling development, static analysis and code generation. | *attractive* and *accessible* | *crucial* |
| 5. | Look familiar to seasoned developers. | *attractive* | *desirable* |
| 8. | Make white-spaces syntactically insignificant to make the language more resilient to copy-paste and LLM usage. | *accessible* | *desirable* |
| 9. | Handle an extendable list of compilation targets to make the code portable to many present and future supports. | *accessible* and *durable* | *important* |
| 10. | Handle translation tables, modular lexers, parsers and code generators to translate code back and forth from one spoken language to an other. | *accessible* | *important* |
| 11. | Enable partial and complete code hot swapping even in production. | *modularity* | *crucial* |
| 12. | Minimize bundle size, runtime speed and memory usage. | *durable*, *accessible* and *attractive* | *desirable* |

### Peer to Peer Library

| ref | requirement | fulfills | priority |
| --: | ----------- | -------- | -------- |
| 1. | Enable seem less peer to peer communication and data synchronization. | *resilient*, *independent* and *accessible* | *crucial* |

### Package, Versioning and Distribution Manager

| ref | requirement | fulfills | priority |
| --: | ----------- | -------- | -------- |
| 1. | Incorporate systems for version control, p2p package distribution and deployment to ensure maintainability. | *sustainable* and *resilient* | *crucial* |
| 2. | Integrate [evergreen migrations](https://www.youtube.com/watch?v=4T6nZffnfzg) as the essential method for transitioning versions. | *sustainable* | *desirable* |

### Graphics Library

### IDE

### GUI

Code is a great interface for describing an application's logic but graphical tools are much more adapted when in comes to interfaces and graphic design.

### Teaching Material

### Font

| ref | requirement | fulfills | priority |
| --: | ----------- | -------- | -------- |
| 1. | Covers every character/symbol/glyph from every language and their writing directions (RTL, LTR, TTB). | *accessible* | *important* |
| 2. | Focus on readability at every size. | *accessible* and *sustainable* | *crucial* |
| 3. | Be monospace for use in programming. | required for [Dialang](#programming-language-dialang) | *crucial* |
| 4. | Has a consistent style that matches [dialogue's visual identity](#visual-identity). | *attractive* | *desirable* |

### Programming Toolset (legacy)

A programming language in and of itself is a user interface that serves as a model for thinking and describing processes. We often think of programming languages as things in and of themselves but their compilers, frameworks, IDEs, and tools in general each take a huge role in their ergonomics. As software development is a social process, this thinking can be extended to the blogs, forums and articles that are also part of the programming toolset.

| ref | requirement | fulfills | priority |
| --: | ----------- | -------- | -------- |

- Easy to learn and master (*accessible*)
  - Great beginner resources aimed at non technical peoples
  - Minimize the amount of core concepts
  - Easy to read and to express (avoids [syntactic sugar](https://en.wikipedia.org/wiki/Syntactic_sugar))
  - Single threaded code
  - Consistent interfaces across devices
  - Great programming ergonomics
- Easy to review and maintain (*sustainable*)
  - Enforces good practice through language design and compiler errors
  - Human readable and helpful compilation error messages
  - Compiler enforce good documentation practices
  - When it compiles it works except for mathematically untraceable issues
  - No implicit behavior
  - Strongly typed
  - Enables metaprograming for analysis and automated review
  - Compiler and tooling written in its own language
  - Has clear and uniform naming conventions
  - Standard formatting enforced by the compiler
  - Standard formatting avoids indentation pyramids
- Joins developer and designer's work
  - The code is the single source of truth
  - GUI enables designers to edit view code
    - Single source of truth for the design system, layout and animations
    - Intuitive for designers
    - The design should automatically generate code and have a simple interface for developers to integrate with
    - All of the design has to be under designer control with the least amount of coding knowledge needed
    - Ensure each interface works on any screen format
    - Enforce good accessibility practices
- Built for distributed architecture (*distributed*)
  - [ORDT](http://archagon.net/blog/2018/03/24/data-laced-with-history/) as first class citizen
  - Enable distributed computations for heavy algorithms
  - Integrates peer to peer protocols
- Run and compile on most devices with low network availability (*accessible*)
  - Parallelize program at compile time
  - Tiny bundle size
  - Be [local first](https://www.inkandswitch.com/local-first/)
  - Fast compilation
- Sandboxed (*modular*)
  - Functions have no side effects
  - A single datatype represents all possible side effects
    - It can be extended or shrunk based on the access we want to give to the sub program
- Can be translated in various languages (*accessible*)
- Always a single source of truth (*sustainable*)
  - The code and its documentation is the reference for the communication protocols

#### Programming Language

##### Elm

[Elm](https://elm-lang.org/) has the best compiler messages and maintainability around. It has a very young ecosystem which comes with drawbacks as it lacks many libraries and tools that can be found in main stream languages but the language is stable and complete for its intended use case (web app frontend).

##### Gren

[Gren](https://gren-lang.org/) started as a fork of Elm. It adds quite a few quality of life improvements and is made for full stack apps building on a Node backend. Contrary to Elm and Roc they are building their primary compiler in Gren itself which unifies the tooling in a single language.

##### Roc

[Roc](https://www.roc-lang.org/) is a language inspired by Elm that adds a very useful abstraction of platforms and wants packages to have IDE integration. Its syntax tends to be more familiar to people coming from mainstream programming languages. It still is in full development and will take some time before being stable enough for use in production.

##### Bend

[Bend](https://higherorderco.com/) is great at compile time parallelization. There is discussion for [HVM](https://github.com/HigherOrderCO/HVM) (which Bend is built onto) to become a compilation target for Elm.

#### P2P Networking

Servers are a single point of failure that can easily be shut down by the cloud companies or the states. Organic peer to peer communication on the other hand is much harder to affect as every device of the network must get disconnected from the rest in order to shot down the service.

-- wip : requirements are needed

##### LibP2P

[LibP2P](https://libp2p.io/) is an open source networking library that has a very flexible transport layer with protocol multiplexing. According to their website it is the simplest solution for global scale peer-to-peer networking and includes support for pub-sub message passing, distributed hash tables, NAT hole punching and browser-to-browser direct communication. It is still under active development but is used in production in multiple large scale contexts.

##### Pear

[Pear](https://docs.pears.com/guides/getting-started) is a framework built on Electron made for building and distributing p2p apps.

##### Socket

[Socket](https://socketsupply.co/guides/) is a light framework for building native apps on any platform that integrates a [delay-tolerant networking](https://en.wikipedia.org/wiki/Delay-tolerant_networking#Security_issues) library for p2p pub-sub communication.

### Architecture

In order to articulate all perviously cited systems we need a clear architecture.

- Must enable interface and algorithmic modularity by providing specific api for the different variations of these systems to be integrated through

#### Key Concepts / Ontology

The following concepts are the building blocks that articulate the various facets of the platform.

Users :

- **Entity** : Anything that interacts with the app. This covers *bots*, *people* and *orgs*.
- **Person** : Specifically describes a human user. We chose this word as we want to highlight the fact that we are designing and coding for real peoples.
- **Bot** : Computer program interacting with the platform.
- **Sybil** : Computer program pretending to be a *person*.
- **Org** : Group of *entities* organizing together. They have an *aim*, *processes* and a *record*. It might be publicly visible or private in which case only its *members* and some other authorized *entities* know it exists. *Members* may share *content* internally.
- **Device** : Hardware *device* interacting with various parts of the platform.
- **Legal Entity** : *Entity* having a legal existence outside of the platform. It might be a company, an ONG, an individual, a state, an institution, etc.
- **Server** : *Device* providing storage and replication of *entities* encrypted data. A *person* might setup its own *server* or use one provided by a *legal entity*. *People* must be able to easily switch or leave *servers* at any time.
- **Fiscal Host** : *Legal entity* which holds different *entities*’s funds in their bank account and enable them to receive and spend money. This concept corresponds to [Open Collective's fiscal hosts](https://docs.opencollective.com/help/fiscal-hosts/fiscal-hosts).
- **Authn** : Every *device* has one or more authenticated *peoples*.

Relationships :

- **Acknowledgement** : An *entity* may *acknowledge* an other and recognize some aspect of that *entity*. That might be its existence or its legitimacy. It may correspond to a state recognizing the legitimacy of an other or the existence of a human being through an id card. It may also correspond to a *person* recognizing the legitimacy of an institution. -- wip : quite unsure about this one
- **Contact** : Two *peoples* can connect to one an other as *contacts*. This contact has to be done in person by scanning a qr code from one device to the other. This might also be considered as an *acknowledgement* between humans of their mutual physical existence. This is a key notion for avoiding *sybils*.
- **Friendship** : *Contacts* that trust one an other may link as *friends*. Their devices will sore one an other's encrypted data. They will also permit account retrieval in case all of one *person*'s devices have been lost or stolen.
- **Circle** : A *entity* may group its *acknowledged entities* into *circles* it wants to share *content* with. A *circle* may correspond to a group of friends or family. Those groupings are only known by the *entity* sharing the *content*.
- **Block** : A *person* may hide all *content owned* by an other *entity* by *blocking* it.

Organizing :

- **Member** : *Entity* that is part of an *org*.
- **Aim** : Piece of text describing the goals, intended purposes and general orientation of an *org*. The introduction and the *core principles* together form *Dialogue OC*'s *aim*.
- **Action** : Different actions can be taken by an *org*. This mey be internal *content* moderation, *content* publication and management, modifications of the *aim*, *member* acceptance and exclusion, *role* edition, granting and removal, modifications of *processes*, etc.
- **Process** : Methods and criterions by which *action* can be taken within an *org*. The mechanisms mey include direct voting, temporary *role* granting through [sortition](https://en.wikipedia.org/wiki/Sortition), committee deliberation, etc. Its functioning has to be transparent to every *member*.
- **Record** : List of every *action* taken and the *entities* responsible.
- **Role** : *Members* hold different *roles* within an *org* that charge them with some responsibilities and may grants them the right to take a specific *actions*. A piece of text describes the expected behavior of the holder.

Publishing :

- **Content** : Piece of content matching a specific *format*. Each has an [IPLD](https://ipld.io/) reference.
- **Interaction** : Way a *person* can interact with a piece of *content*. Might be likes, views, reactions, votes, modifications, pinning, claps, agreement slider, shares, comments, etc.
- **Format** : Standard structure of *content* data, metadata, presentation material (miniature, description, etc.) and available *interactions*. This might cover things like articles, posts, long form videos, short vertical videos, live streaming, songs, podcasts, books, comments, playlists, chats, etc.
- **Authz** : Piece of data describing which *entities* get to access and/or *interact* in specific ways with a given piece of *content*. All *content* that is not public is encrypted. *Entities* that have reading rights on the content are the only ones to receive the decryption key and all editions made by non authorized *entities* are simply ignored. *Authz* stands for authorization and must not be mixed with *authn* that stands for authentication instead.
- **Ownership** : Every piece of *content* is owned by an *entity* which is the only one able to modify its *authz*. *Content* is *owned* by its initial emitter but can be transferred to a different *entity*. The *content* will be stored and kept online by the *owner*'s own *devices* and the *owner*'s *friends devices*. In the context of an *org*, its *owned content* gets stored on its own *servers* and/or on its *members devices*.
- **Signature** : Cryptographic signature ensuring the authenticity of the piece of data. Every *content* and *interaction* have to be signed. Different kinds of [group signatures](https://en.wikipedia.org/wiki/Group_signature) mey be used in the case of *org* signatures.
- **Pinning** : A *person* might decide to *pin content* they do not *own* on one or more of its *devices*. Those *devices* will then store the *content* and keep it available online. *Pinned* data isn't stored on *friends devices*.

Interfaces :

- **Component** : Piece of interface serving a specific purpose.
- **Layout** : Piece of interface organizing various *components* on the screen. It may then itself be used as a *component*.
- **Page** : *Layout* covering the whole screen that has a specific url/address.
- **Design** : Set of parameters that can be edited by the *person* which decides on the aesthetic and usability of *components* and *layouts*. It describes dark and light mode colors, font sizes, weather assisting tools are needed, etc.

Presenting :

- **Metric** : Some meaningful information extracted from the pile of raw data by a deterministic algorithm. It may measure the amount of views a piece of *content* got while avoiding to count *sybils*, it might measure how much a specific *person* enjoyed a piece of *content*, extract keywords representing the topic it covered, track an *entity* journalistic accuracy or scientific rigor, etc. It is designed and *owned* by an *entity*.
- **Recommendation** : List of *content* organized by an algorithm through various criterions to a specific *person*. It tries to predict which *content* the given *person* would want to access next based on various *metrics* and based on the *content* that the *person* may be currently reading/watching.
- **Presentation** : *Page* enabling a *person* to read/watch and *interact* with a piece of *content*.
- **Miniature** : *Component* presenting a piece of *content* that enable the *person* to access its *page* or add it to various content *groupings*.
- **Discovery** : *Layout* presenting the *miniatures* of *contents* selected by different *recommendation* systems for the *person* to search through.

#### Identity verification

Online group decision-making often requires some level of identity verification to avoid [Sybil attacks](https://en.wikipedia.org/wiki/Sybil_attack).

##### The social graph of trust

One solution is to build a physical proof of personhood network where users meet in person and establish verified connections by scanning QR codes on each other's devices. This creates a social graph of trust that maintains privacy while making bot accounts detectable through network analysis.

Real human social networks tend to be densely interconnected, whereas bot accounts typically show suspicious patterns: few connections to verified humans, clustering through single gateway users, and unnatural network growth. While bad actors could attempt to verify bot accounts, their suspicious connection patterns would make them identifiable. The system becomes more robust as legitimate human connections accumulate, making it increasingly difficult to fake human-like network patterns at scale.

An organization can then use this network to validate identity. It could only consider votes entered by accounts with multiple trust connections to other members for instance.

-- Look at [web of trust](https://en.wikipedia.org/wiki/Web_of_trust).

#### Default Recommendation System

-- wip

everyone doesn't need to give the same credence to everyone else. Give more credence to people close to you and to people you support the work. Explicitly recommend content to people around you.

#### Collaborative Storage Cloud

[Collaborative storage cloud](https://en.wikipedia.org/wiki/Cooperative_storage_cloud)

#### Resource Management and Payment Methods

-- wip : needs to start with the requirements instead of the solutions.

Payment methods have to be available in order to finance the work of content creators, pay compensations on the collaborative storage cloud.

- the *Dialogue OC* will provide content crowd funding (*accessible* and *sustainable*)
- *orgs* will have tooling to track money and equipments that is held by different *members* on their behalf (*resilient*)
- payments in cryptocurrency will be possible independently of that service (*resilient*)
- the *Dialogue OC* might provide cryptocurrency exchange (*accessible* and *sustainable*)

## Core Principles' Rationale

In this section we detail every principle, we express its underlying rationale, what it is, what it isn't and some practical implications. The important part here is to convey Dialogue's general intent.

### Empathic

When we interact online, we tend to forget that there are human beings on the other side of the screen. This distance makes it easier to ignore others' humanity, leading to behaviors we would rarely engage in face-to-face: going from simple carelessness to harassment and public shaming. These toxic behaviors isolates peoples, encourages stale interactions and deepens social divisions. We want to build bridges and have spaces for people to dialogue with one another.

Being empathic means fostering an environment where people feel safe to express themselves and engage with others constructively. This goes beyond basic politeness - it requires actively designing systems that encourage empathy, honesty, mutual understanding, good faith communication and that supports users mental and physical wellbeing.

This doesn't mean avoiding hard or violent topics, nor does it mean abolishing debate or disagreement. It simply means to make ones best effort to reach the other, try to understand their point of view and progress from there.

Community guidelines and content creation tutorials can encourage empathetic communication, default platform metrics can track and highlight constructive interactions rather than inflammatory ones, default recommender systems can show diverse perspectives to break information bubbles and default interfaces can prompt users to reconsider harmful messages before publishing. These mechanisms help shape a culture where seeking to understand others becomes as natural as expressing oneself.

### Assertive

### Optimistic

In times of global challenges and systemic crises, it's easy to fall into doom scrolling and cynicism. This constant exposure to problems without solutions creates a paralyzing feedback loop: seeing no examples of positive change makes it harder to believe in or work toward solutions, which in turn means fewer positive examples for others.

Building confidence in our collective ability to overcome current challenges means breaking this cycle. It comes by being enthusiastic about the future, sharing practical experiences and organizing to create the changes we want. When others see that change is possible, taking that first step toward engagement becomes possible.

This doesn't mean ignoring problems, promoting blind optimism or deluding oneself on what is possible. It simply means maintaining faith in human ingenuity and working towards concrete solutions. The platform should encourage content creators users stay informed about challenges while emphasizing where action can be taken and positive change happens or is being fought for.

Community guidelines and content creation tutorials can encourage solution-focused storytelling, default platform metrics can track and highlight constructive engagement rather than just reach, and default recommendation systems can be designed to balance problem awareness with solution-finding initiatives. These mechanisms help shape a culture where sharing progress and celebrating small wins becomes as natural as identifying challenges.

### Empowering

Traditional platforms treat users as passive consumers of content and features, offering little control over their digital environment beyond superficial customization options. This creates learned helplessness where users accept whatever changes platforms impose, even when these changes work against their interests or needs. This problem is particularly visible in the [attention economy](https://en.wikipedia.org/wiki/Attention_economy) where corporations compete to grab users' attention at all costs, using invasive and addictive design practices with profound disregard for users' wants and needs.

Empowering means trusting users' capacity to make informed choices about their digital lives. This is about interface customization, recommendation algorithms, content filtering, interaction metrics, and information presentation. Users should understand how these systems affect their behavior and have meaningful ways to adjust or replace them to align with their own purposes and values.

This principle is about respecting users' autonomy and supporting their growth from passive consumers to active participants who understand and control their digital environment. The platform should make visible the mechanisms that guide behavior and provide tools to modify them according to personal values and goals.

Transparent algorithms that users can understand and modify, usage dashboards that help users self-reflect, customizable metrics that align with personal values rather than engagement maximization, and settings to modify or disable potentially addictive features. These mechanisms help users reclaim agency over their online experience and maintain a healthy relationship with technology.

### Expressive

The world wide web brought an unprecedented ability for people to share ideas and knowledge across the world but - as the [platform economy](https://en.wikipedia.org/wiki/Platform_economy) grew - private corporations took control over our means of communication and entertainment. These platforms not only amplify already-popular voices while making it increasingly difficult for new or niche creators to reach and grow their audience, creating a self-reinforcing cycle of visibility inequality, but they also readily comply with state censorship demands, further limiting the diversity of voices and ideas that can be expressed online.

To follow the expressive principle means to provide diverse peoples ways to express, publish, share and sustain creative work. It includes hosting dissident voices. This involves supporting creators, making tools and resources that help them initiate their creative work, find their core audience and open multiple paths to sustainable content creation.

This isn't about limiting successful creators or forcing equality of outcomes. Rather, it means ensuring that success comes from genuine audience connection and content quality rather than algorithmic bias. The goal is to create multiple viable paths to sustainable content creation, where both niche creators serving specific communities and broadly popular voices can thrive.

In practice this comes down to handling various content formats (from text articles to long-form video passing by digital comics), having discovery pages for each of them recommending content based on a variety of metrics and algorithms. To make content production sustainable the platform may integrate crowd funding systems and a page to connect creators and advertisers.

### Informative

Traditional media outlets have consolidated into massive conglomerates whose coverage inevitably aligns with their owners' interests. Meanwhile, social platforms shape public perception through algorithmic amplification that prioritizes engagement over truthfulness. This creates distorted views of reality - sensationalizing certain events while overlooking others, amplifying extreme voices while marginalizing nuanced perspectives. The result is a media landscape where even basic facts become contested territory and where the real significance of events gets lost in a flood of decontextualized content.

Being informative means providing [community-driven systems](https://en.wikipedia.org/wiki/Citizen_journalism) for gathering, verifying, sharing and contextualizing news. This first requires tools for information gathering, sourcing, cross-referencing, investigation and communication. No news covering is truly neutral and being informative also is about making the ideology underlying the presented facts explicit and to contrast it with the way it is presented through different ideological lenses.

This isn't about creating a centralized truth authority or enforcing a single perspective. Rather, it's about providing tools and processes that help communities collectively investigate and document events and encourage them to look across the isle and have a fair view of the opposing perspectives. The goal is to enable rigorous collaborative journalism without creating new gatekeepers or compromising the diversity of viewpoints.

The platform realizes this principle through several complementary mechanisms. For gathering and verifying information, it provides geotagged and timestamped content that can be cross-referenced between witnesses, along with collaborative investigation tools to connect related pieces of evidence. For ensuring coverage quality, reputation systems track journalistic integrity while a suite of tools helps balance coverage priorities: statistical comparisons show how coverage frequency matches real-world occurrence, impact assessment tools measure the scope and duration of effects, communities can define and weight different impact factors, and contextual presentation highlights trends rather than isolated incidents. Default user's interface contrasts their news viewed through different ideological lenses. Together, these mechanisms support rigorous collective journalism that reflects real-world significance and diversity of opinions rather than entertainment value.

-- wip : add peer review before publishing content

### Democratic

Traditional social platforms tend to concentrate power in the hands of platform owners and their algorithms, leaving users and communities with little say in how their spaces are governed. Even when platforms offer community moderation tools, these are often limited and can be overridden by corporate decisions driven by profit motives rather than community needs.

This is also true at a wider scale in corporate and political environment where power is centralized in the hands of the wealthy. Dialogue wants to be a space for the masses to organize, struggle against oppression and decide collectively what future they want to craft for humanity.

Democratic organization means creating spaces where communities can effectively self-govern and make collective decisions. This requires not just voting mechanisms, but comprehensive tools for discussion, investigation, deliberation, consensus-building, and transparent decision-making. The platform must support various forms of democratic governance - from direct democracy to representative systems - while keeping processes clear and accessible to all participants. The different communities and organizations have to be able to take joint decisions, make joint statements and coordinate through the platform.

The democratic principle isn't about forcing every group to use the same democratic model. Rather, it's about making democratic organization more efficient and accessible than centralized control. Communities should be able to choose and evolve their governance structures while maintaining transparency and accountability to their members.

Built-in tools for proposals and voting, structured discussion spaces for investigation and deliberation, tools for collaborative work, transparent record-keeping of decisions and their rationales, and flexible permission systems that communities can adapt to their needs. These mechanisms help make collective decision-making and organizing as fast and more efficient as centralized systems.

### Accessible

Large segments of the population are excluded of the online discourse through various barriers: expensive devices or data plans, complex interfaces that assume technical literacy, designs that don't work with assistive technologies, content available only in majority languages, poor internet access or non [net neutral](https://en.wikipedia.org/wiki/Net_neutrality) internet providers. This creates digital divides that reinforce existing social inequalities and limit the internet's potential for inclusive dialogue and collective action.

Making a social platform truly accessible means considering every feature through multiple lenses:

- Technical: Nice to use for every level of technical literacy, providing shortcuts for experts and helpers for beginners.
- Economical: Works on low-end devices with slow/intermittent connections.
- Cultural: Adapt interfaces and symbols for them to be understood in different cultural contexts.
- Disabilities: Follows the best web accessibility standards and have tools for community and automated, audio and video content transcription.
- Lingual: Available in most languages with tools for community and automated content translation.
- Literacy: Illustrate every button and menu for them to be usable by analphabet and illiterate peoples.
- Other: This list is non exhaustive and other factors that might hinder the platform's accessibility should be considered.

Being accessible is about thoughtful development. We have to think every functionality from the start to be nice and easy to use for everyone.

Responsive interfaces that work across device types, offline-first architecture that handles poor connectivity, built-in translation tools, context-sensitive help systems, and careful attention to accessibility standards. These mechanisms ensure that no one is excluded from participating in the platform's community.

### Attractive

One of the internet's greatest achievements has been helping people maintain meaningful connections across time and distance - old friends finding each other again and families staying close despite living continents apart. But this only works when people can actually find each other on a platform. A social network needs to attract and retain enough users to make these connections possible, otherwise even the best features become meaningless in an empty space.

Being attractive means designing features and mechanisms that give people genuine reasons to join and stay on the platform. This requires both understanding what brings real value to users' lives - whether that's reconnecting with old friends, finding communities that share their interests, or discovering new perspectives - and creating sustainable growth mechanisms that benefit both users and creators. The platform should grow through authentic utility, meaningful interactions, and positive feedback loops that align everyone's interests.

We want to avoid using dark patterns, artificial virality, or manipulative engagement tactics to drive growth. Rather, being attractive is about creating genuine value that makes people want to join and stay. The platform should grow through word-of-mouth and demonstrated utility, not through exploiting psychological vulnerabilities or creating artificial urgency.

Building trust through genuine collaboration with creators and users is key to enable the best advertisement there is: word of mouth. In order to get there we need to support creators and users success through community building tools and sustainable revenue models, and to foster a co-building relationship where their feedback shapes the platform's evolution. To reach new user bases platform-funded and crowdfunded exclusive content can attract new audiences and creators can introduce their communities to the platform through cross-platform content strategies.

### Private

Traditional social platforms treat user data as a commodity to be exploited - selling it to advertisers, training AI models without consent, sharing it with third parties, and readily handing it over to state surveillance. This creates a situation where every interaction, every connection, and every piece of content becomes potential leverage against users, whether for commercial manipulation or state control. Even "private" messages and closed groups are ultimately accessible to platform owners and their partners.

Privacy means giving users genuine control over their data and communications. This extends beyond basic settings to fundamental control over where data is stored, who can access it, and how it's used. Users should understand what data they're generating, have meaningful choices about its storage and sharing, and trust that their private communications remain truly private through strong encryption and transparent security measures.

The aim isn't for all content to be completely private. Rather, it's about ensuring users have real control and understanding of who gets access to which piece of data. The platform should make it easy to share safely when desired while maintaining strong privacy by default and protecting users from accidental exposure.

Strong encryption protects all communications by default, clear interfaces help users understand and control their privacy settings, they get to decide where to store their data, transparent documentation explains how data is stored and processed and granular sharing controls let users decide exactly what to share with whom. These mechanisms ensure users maintain genuine sovereignty over their data while making safe sharing straightforward when desired.

### Resilient

Traditional social platforms are vulnerable to disruption - whether from technical failures, corporate decisions, or state intervention. A single point of failure in their centralized infrastructure can cut off millions of users from their communities. More concerning still, governments can easily pressure these platforms to censor content, block access, or hand over user data, effectively silencing entire populations with a single decision.

Being resilient means ensuring the platform keeps working even under adverse conditions. This requires both technical and social resilience - from maintaining basic functionality during network outages to preserving the platform's governance during targeted disruption attempts. The platform should be able to adapt and recover from failures, help users route around censorship, and maintain essential services even when parts of the network are compromised or blocked.

Build the app's communications as a trustless peer to peer distributed system with no cental node. Follow the best practices in [disruption-tolerant networking](https://en.wikipedia.org/wiki/Delay-tolerant_networking). Structure data as [conflict-free replicated data type](https://en.wikipedia.org/wiki/Conflict-free_replicated_data_type) and propose [cooperative storage](https://en.wikipedia.org/wiki/Cooperative_storage_cloud) to duplicate data across users' devices. Keep the interfaces as functional as possible even without network access. This principle also has implications for the platform's governance. The core developers' team should be organized with resilience in mind as its members might be pressured or even be missing.

### Safe

In many parts of the world, expressing certain views or identities online can lead to real-world persecution. Journalists, whistle-blowers, activists, minorities, and ordinary peoples face harassment, job loss, imprisonment, or worse when their online activities are traced back to them. Traditional platforms not only fail to protect vulnerable users, but often actively cooperate with oppressive entities by providing user data or implementing automated surveillance systems that can be weaponized against their users.

Being safe means ensuring users can communicate without fear of identification or retribution, particularly in repressive environments. This requires strong online anonymity and untraceability, protections against online harassment and exposure as well as undetectability by [network sniffing](https://en.wikipedia.org/wiki/Sniffing_attack) and [spyware](https://en.wikipedia.org/wiki/Spyware). The platform should provide tools and practices that help users maintain their safety while still enabling meaningful participation in their communities.

Strong anonymity by default protect user identities, content warnings and filtering tools help users avoid unwanted exposure, reporting mechanisms enable communities to protect themselves against harassment and safety documentation helps users understand risks and best practices. The platform's security has to be heavily tested and be impervious against spoofing attacks. Ideally the app should also be [polymorphic](https://en.wikipedia.org/wiki/Polymorphic_code) to avoid detection by spyware and it should be able to disguise its communications in order to be unrecognizable by anyone tapping the network.

### Modular

No platform is neutral - its design inherently shapes what gets expressed and how people interact. From recommendation algorithms that determine what content gets seen, to interface choices that guide behavior, to moderation systems that define acceptable speech - every technical choice embodies specific values and priorities. While we strive to align these choices with our *core principles*, we recognize that no single implementation can serve all communities' needs or adapt to every contexts.

Modularity enables communities to adapt how they interact with the platform while maintaining its fundamental integrity. Through carefully designed APIs and secure sandboxing, communities can customize their experience - from recommendation algorithms to interface layouts, from moderation tools to interaction metrics - all while the platform's core architecture and protocols remain unified and secure. This allows each community to shape their environment according to their specific needs and values without compromising the platform's other *core principles* (with the exception of the three philosophical principles which only relate to default options).

The platform realizes this principle through secure APIs for safe extension development, sandboxed environments that protect core functionality and a dedicated space where communities share and discuss their custom packages. As extensions prove their value through widespread adoption and community vetting, they can be considered for integration into the platform's default offering, creating a pathway for community-driven evolution of the core platform itself.

### Independent

Most social platforms are beholden to corporate interests and vulnerable to state control. Whether through profit motives driving harmful engagement tactics, advertisers influencing content policies, or governments demanding user data and censorship compliance, these dependencies fundamentally compromise platforms' ability to serve their users' interests. The result is a social media landscape where neither users nor platform operators can maintain genuine autonomy in pursuing their stated values and goals.

Being independent implies the strong rejection of the profit motive in general and opportunism amongst the people involved. Money has to be used only as a tool needed to build the platform but it must never be confused with the final goal. It is needed to ensure the platform stays true to its *core principles* and to resist both corporate capture and state control.

Systems have to [distribute](](https://hypha.coop/dripline/debate-over-dweb-vs-web3/)) [computing](https://en.wikipedia.org/wiki/Distributed_artificial_intelligence) and [storage](https://en.wikipedia.org/wiki/Cooperative_storage_cloud) loads across all users devices to avoid dependency to any cloud provider. This also lower the maintenance costs and limits the dependency on revenue sources. The source of revenue have to be varied and preferably come from the users who have the most interest in upholding the *core principles*. The org must not grow dependent on any other source of revenue - like advertisement or subsidies - as they may be used to pressure the org if it grows too dependent on them.

To prevent opportunism amongst the peoples involved in the org, salaries have to be limited even for key people and those with conflict of interests have to be severely rejected. Peoples have to show significant investment into the project before they can take part in the decision process. A fund have to be prepared in case members of the organization get intimidated or pressured.

### Sustainable

In the rapidly evolving landscape of technology and social platforms, many projects face challenges in maintaining their relevance and functionality over time. Often, platforms are built with short-term growth goals in mind, leading to technical debt and a lack of consideration for the social and ecological impacts. To ensure long-term viability and continued alignment with user needs, sustainability must be a core consideration from the outset.

Sustainability involves creating a platform that remains viable and relevant across durable timescales. This means choosing stable technologies, building maintainable systems, and establishing governance structures that can evolve with the community's needs. It means that every technical and architectural decision have to be taken with a long term perspective.

It is not about making rigid choices or avoiding new technologies and ideas. It is about the flexibility and adaptability to changing circumstances. Bold technical choices can be made if they are shown to closely match the *core principles*.

Systems should be designed for easy maintenance and scalability, with clear documentation and modular architecture to facilitate updates and improvements. Governance structures should be flexible, allowing for community input and adaptation to new circumstances. Feedback loops that identify areas for improvement have to be thought out to ensure the platform continues to meet user needs and remains aligned with its core principles over time.

### Empirical

In the development of social platforms, assumptions about user behavior and feature effectiveness can lead to misguided decisions and unintended consequences. Without a rigorous approach to testing and validation, platforms risk implementing features that do not serve their intended purposes or align with their initial aim. An empirical approach is essential to ensure that platform development is grounded in reality and evidence.

The empirical principle emphasizes the importance of data-driven decision-making and rigorous testing. It involves gathering quantitative data (while respecting user privacy) but also qualitative feedbacks to study the concrete outcomes and to make adjustments based on evidence. This approach ensures that features and changes are evaluated for their actual impact, allowing the platform to evolve in a way that truly benefits its users.

Empirical does not mean relying solely on quantitative data or ignoring qualitative insights. It is not about reducing user experiences to mere numbers or metrics. Instead, it involves a balanced approach that considers both quantitative and qualitative data, ensuring a comprehensive understanding of user interactions and platform dynamics.

To implement the empirical principle, the platform should establish robust mechanisms for data collection and analysis that is based on user agreement. A/B testing, user feedback loops, and pilot programs can be used to evaluate new features and changes. Regular reviews of platform performance and user satisfaction should inform ongoing development. By fostering a culture of continuous learning and adaptation, the platform can ensure that its evolution is guided by real-world evidence and user needs.

### Transparent

Transparency means users can understand how the platform works, from algorithms to governance. This requires clear documentation, open source code, and explicit explanation of automated systems.

This understanding enables meaningful user participation and control.

## Balancing Core Principles

Each principle corresponds to a specific idea and are thought not to overlap with others but they might compete with one an other when it comes to practical implementation. The aim really is to find the best of both worlds whenever possible and to get to a good equilibrium between the two when they fundamentally contradict one an other. In this section we discuss some of those tensions.

### Complexity vs Accessibility

Complexity grows quickly when designing systems. Giving complete control over the interface to the user (*empowering* and *modular*) might make those really complex to use and understand. The processes able to parse and structure information (*informative*) might also become quite complex.

-- wip

### Privacy vs Openness

A lot of usage data has to be available in order to build good recommender systems (*expressive*). Privacy entails anonymity which makes it hard to discriminate bots and causes a lack of individual accountability (*empathic*, *democratic* and *informative*). It also hinders the ability to gather usage data that can inform the platform's development (*empirical*).

-- wip

### Modularity vs Safety, Resiliency and Accessibility

-- wip

The programming language, its framework and tools have to enforce the best practices in terms of documentation, code clarity, interface accessibility, testability and security.

## Miscellaneous Notes

Various notes and precisions about this document.

### Is the systemic change described in the introduction even possible?

The current socio-economic system - capitalism - is only 300 years old which is ridiculous when compared to the 300,000 years modern humans have been around. Like organisms, societies evolve, they adapt to external threats and iteratively transform to solve their internal contradictions.

Moreover, the seeds are planted: On one hand, we inherited productive capabilities able to provide for everyone's needs enabling their participation to the political process. On the other, our transport and communication capabilities literally shrunk the scale of our planet and give us the opportunity to meet and discuss across continents.

We use this perspective as a north star guiding the project but even if you believe such a deep political transformation of society to be impossible, a tool like *Dialogue* has many immediate positive impacts and is worth pursuing for its own sake. Every *core principle* might individually be a good reason for someone to want to build and support it.

### Will fascist, terrorist and criminal organizations be using Dialogue to their advantage?

The core values of the far right are fundamentally centered around creating hierarchies between people and to violently oppress those who they deem as lesser humans. Religious fundamentalists of all obedience do the same based on religious beliefs. Organized crime is different as it does not have any moral apart form its crushing thirst for money. Those are fundamentally opposed to *Dialogue*'s goal and *core principles* and - as such - we strongly reject their ideas and methods. We know the far right short and aggressive messaging to be very viral on online platforms and they will surely attempt to invade every space possible and prevent constructive discussion to happen.

-- wip : the second paragraph feels insufficient and maybe even unrealistic but I've got to complete more of the requirements to have clearer ideas on this

Online public spaces are hard to defend but good moderation does prevent harmful messaging to be spread. We aim at structuring and confining information based on ideology which will confine their messaging within a given ideological space that can be visited and interacted with but would be compartmented from the others where those ideologies are inappropriate it easy for people to explore other perspectives without being invaded by disruptive uninformed interventions.

Far right groups will probably enjoy the privacy of the platform and its tools to organize but they are already welcomed and supported by mainstream media and private social platforms. They do not need the tools we are building. That is not the case for human rights activists, investigative journalists, feminist groups, whistle blowers and other radical left movements which get increasingly rejected from public discourse. Those groups will find specific tools adapted to their needs on *Dialogue*. They will be able to keep communicating and organizing even under heavy state and corporate repression. Such online spaces barely exist as of now.

### On our use of LLMs and technology in general

Parts of this document have been written in collaboration with a LLM and similar tools will likely be used to implement the platform.

We recognize that these algorithms have been trained in problematic ways using data without author's acknowledgement and poorly paid labor for data labeling. This kind of recognition can equally be given to the manner the computers and servers internet is built on have been assembled and their materials mined.

We believe LLMs as much as any other tool can be used for human emancipation. A hammer can break a skull but it may also serve to build bridges, houses and hospitals. In other words, the deleterious conditions that produced that hammer may be changed with the help of that very hammer. This reasoning works as much for LLMs than for any other industry.

In terms of content originality, we do not attempt to be especially original or novel. Our main aim is to express ideas and develop techniques to bring them to life. No matter who or what expresses those ideas as long as they correspond to our thoughts and needs.

We have made the writing process transparent by sharing the chat history. It can be found in the `.aider.chat.history.md` file.

### Our take on cryptocurrencies

Since the appearance of Bitcoin in 2008, cryptocurrencies and other NFTs have become a heaven for both scammers and speculators.

-- wip : fuck cryptobros, huge variations of value but might still be useful for online transaction when legal means of online payment are failing.

### Our view on intellectual property

-- wip

Intellectual property is an important concept that makes it possible for people to be paid and receive social recognition for their creative and intellectual work. Though we strongly defend this version of intellectual property, we also reject absolutely the way this notion is used to privatize knowledge and turn it into merchandise to be sold and gatekeeped by large multinational corporations.

We provide software to be used by people to share content

- like people who code the torrent client and protocol we are not responsible for the files shared and hosted by the users
- though we will do what we can for content creators to get due recognition and pay for their work
- and we will champion small creators enabling them to live from their work instead of concentrating it in the hands of a few larger ones that either turn into corporations or are already produced by one

### Our specific notion of interoperability

interoperable but in very specific ways /
transparent also means interoperable /
evergreen design architecture /
possible breaking changes /
useful for attractive /
but might break secure, safe and/or private /
keep control within Dialogue /
might be needed for governance

## Legacy text

### Pro-Social Behavior

- Users can make one to one or group chats.
- Users can post content and decide who gets access to it.

### Organization Tools

- Users form organizations and set rules for their functioning.
- Debate and messaging systems encourage constructive dialogue.
- Voting systems are modular and transparent to every member.
- Texts and rules can be collaboratively edited, reviewed and voted.
- Inclusion and expulsion mechanisms are set up as rules.
- Roles can be attributed and revoked via votes.
- Debate surrounding every rule and text is made available and structured in an accessible fashion.

### Content Moderation

- Content moderation is managed by the users.
- Individuals and organizations can provide custom algorithms and metrics as extensions.

### Local First and Fully Distributed

The app has to function as [local first software](https://www.inkandswitch.com/local-first/) so that it stays up even under heavy network partitioning.

**Useful Inspirations**:

- [any-sync](https://github.com/anyproto/any-sync) for automatic conflict resolution.
- [automerge](https://automerge.org/) for automatic conflict resolution.
- [ipns](https://docs.ipfs.tech/concepts/ipns/) for content addressing.
- [socket-runtime](https://github.com/socketsupply/socket) for network buffering.

### Payment System

A payment solution has to be provided as many services required for the platform to function need money to be exchanged.

> Some of the principles below are mathematically impossible. They are quite naive and need more precision.

**Principles**:

- Secure and reliable.
- Anonymous and untraceable.
- Keeps working under heavy network partitioning.
- Byzantine resistant.

**Useful Inspirations**:

- [filecoin](https://filecoin.io/) as a cooperative storage cloud with a reward model, it also doubles as a crypto currency.

### Hard to Track

The software should withstand state level interdiction and make its users as innocuous as possible.

> This would be ideal but I'm out of my technical depth here.

**Principles**:

- The network communications made between clients have to be innocuous and untraceable.
- It should be possible to make the app hardly recognizable by any other software on the device.

**Useful Inspirations**:

- [Metamorphic code](https://en.wikipedia.org/wiki/Metamorphic_code) can be used to make the app unrecognizable.

### Development Financing

The shopping list is long and we will need a lot of resources to get there.

> This is the main pain point. How can we make people accountable?
> This section is very insufficient and idealistic in my opinion.

**Principles**:

- Money only is a mean to an end.
- Development must be done without any profit motive.
- Money is only used to free the most involved volunteers time.
- The hourly pay is fixed and equal for everyone.
- The way the development team is financed must be - if not aligned - at least compatible with the goals of the project otherwise it is better to only involve volunteers.

**Possible Revenue Sources**:

- Providing a market for easily exchanging the platform's currency with circulating ones.
- Consulting for companies and non profits that would like to function in a democratic fashion and would benefit by integrating Dialogue into their organization.
- User's donations under a set threshold to avoid large donators getting leverage.

## Design Ideas

- Detect aggressive or hurtful writing in a post or comment and prompt the user to think about the people that message might hurt before posting it online.
- Users can setup custom content flagging systems and share their flags with one an other.
- Users can code their own recommender systems.

- Different versions of the interface can be provided as extensions.
- Translation algorithms can be provided as extensions and hosted on the user's devices.

## Existing Propositions

> I want to review a lot more existing social media in order to pull inspiration. Here is a set that will be interesting to review:
> Mastodon, Matrix, Secure Scuttlebutt (SSB), Aether, Lemmy, Discord, Signal, Telegram, Slack, WhatsApp, Reddit, YouTube, Instagram, Facebook, Snapchat, TikTok, LinkedIn, Twitter/X, WeChat, Twitch, Medium, BeReal, Clubhouse, Revolt, BlueSky, Keet, campfirechat, zulip, stack overflow, rad.live

### Nebula

Nebula is a video-on-demand streaming service provider. Launched by the Standard Broadcast content management agency in 2019 to complement its creators' other distribution channels (primarily YouTube), the platform has since accumulated over 650,000 subscribers, making it the largest creator-owned internet streaming platform.<sup>[wikipedia](https://en.wikipedia.org/wiki/Nebula_(streaming_service))</sup>

#### Strong Points

- As it is creator-owned, they get to collectively decide on the functioning of the platform and ensures it follows the best interest of the members.
- The creators drive the development by having Nebula sponsoring their Youtube content. In turn the platform pays the creators for the watchtime they get on Nebula. This forms a positive feedback loop.
- They get huge benefits by negotiating group deals with sponsors, microphone brands, stock footage providers, sound editing software, branding designers, etc.
- Content moderation is ensured by selecting the creators that are part of the project which might be decided collectively.

#### Weaknesses

- The creators only own half of the platform and get a 50-50 deal and probably half of the decision making power.
- The creators generally come from a specific socioeconomic background and mostly from the US or the UK as it only is english speaking.
- Creators can hardly have dissenting stances to the collective. Second thought leaving the platform might be an example of this.
- The profitability of the company also is a constraint on creators political stances as the sponsors and partners could pressure Nebula.

#### Architecture

##### Metrics

Lets describe more in detail what a *metric* might be. Most *metrics* come down to tracking a user's various forms of reputation.

Reputation is relative. It varies from one domain to an other (a reputable mathematician might be really dumb when speaking about sociology) and from one ideology to the next (politicians often caricature opposing perspectives). In the same way they are many ways to to measure it : from youtube views to facebook likes passing by citation counts on scientific papers. Each will emphasize different values and aims.

##### Belief System

-- wip : just an idea right now

A *person* can describe its beliefs which can serve to find *content* that questions those beliefs. This mechanism might push users to deepen their understanding of the world. *Content* would describe which belief it tries to change and be evaluated on its ability to change *peoples* beliefs.

##### Interactions

Claps (similar to medium's applause), Favorite (select the 6 best contents of the year), Pin (pin content on your devices to duplicate it and keep it online), Opinion (agree-disagree slider), Flag (flag different characteristics of the content like violent, hateful, poorly researched, etc.), Share (share the link).
