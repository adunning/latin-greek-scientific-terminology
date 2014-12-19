---
layout: page
title: Latin and Greek in Computer Science Terminology
author: Yuliya Cherenkova
date: 26 November 2014
permalink: '/assignments/cherenkova/'
abstract: |
    Strict, formal terminology in the world of computer science is becoming a necessity as the industry grows. As we develop new design patterns, frameworks, and hardware technologies, we invent, borrow, and reuse terms for them. Due to the lack of globally accepted and enforced standards for terminology in computer science, such rapid terminology growth often leads to confusion and misunderstandings. This issue may be combated by enforcing general conventions and language patterns used by leading computer scientists; yet no convention is mandatory, and the problem is far from resolution.
references:
- event: IEEE 30th International Conference on Data Engineering (ICDE)
  DOI: 10.1109/ICDE.2014.6816748
  URL: http://ieeexplore.ieee.org/lpdocs/epic03/wrapper.htm?arnumber=6816748
  page: '1230-1233'
  ISBN: '978-1-4799-2555-1'
  title-short: VoidWiz
  first-reference-note-number: 1
  container-title: IEEE 30th International Conference on Data Engineering (ICDE)
  author:
  - family: Christodoulakis
    given: Christina
  - family: Faloutsos
    given: Christos
  - family: Miller
    given: Renée J.
  source: CrossRef
  id: christodoulakis:2014voidwiz
  accessed:
    date-parts:
    - - 2014
      - 12
      - 3
  issued:
    date-parts:
    - - 2014
      - 3
  title: 'VoidWiz: Resolving incompleteness using network effects'
  type: paper-conference
  publisher: IEEE
- event: IEEE 30th International Conference on Data Engineering (ICDE)
  DOI: 10.1109/ICDE.2014.6816655
  URL: http://ieeexplore.ieee.org/lpdocs/epic03/wrapper.htm?arnumber=6816655
  page: '244-255'
  ISBN: '978-1-4799-2555-1'
  first-reference-note-number: 1
  container-title: IEEE 30th International Conference on Data Engineering (ICDE)
  author:
  - family: Volkovs
    given: Maksims
  - family: Chiang
    given: Fei
  - family: Szlichta
    given: Jaroslaw
  - family: Miller
    given: Renée J.
  source: CrossRef
  id: volkovs:2014continuous
  accessed:
    date-parts:
    - - 2014
      - 12
      - 3
  issued:
    date-parts:
    - - 2014
      - 3
  title: Continuous data cleaning
  type: paper-conference
  publisher: IEEE
- edition: '2'
  event-place: Oxford
  publisher-place: Oxford
  URL: http://www.oed.com/
  ISBN: '9780198611868'
  number-of-volumes: '20'
  call-number: PE1625 .O87 1991
  first-reference-note-number: 1
  source: Library of Congress ISBN
  id: simpson:1989oxford
  issued:
    date-parts:
    - - 1989
  title: The Oxford English dictionary
  type: book
  publisher: Clarendon Press
  editor:
  - family: Simpson
    given: J.A.
  - family: Weiner
    given: E.S.C.
- edition: '9'
  event-place: Oxford
  publisher-place: Oxford
  URL: http://logeion.uchicago.edu/
  ISBN: '0198642261'
  call-number: PA445.E5 L6 1996
  first-reference-note-number: 1
  number-of-pages: '2042'
  source: Library of Congress ISBN
  id: liddell:1940greek
  issued:
    date-parts:
    - - 1940
  title: A Greek-English lexicon
  type: book
  publisher: Clarendon Press
  editor:
  - family: Liddell
    given: Henry George
  - family: Scott
    given: Robert
  - family: Stuart Jones
    given: Henry
- edition: '3'
  event-place: Oxford
  publisher-place: Oxford
  URL: http://www.oxforddictionaries.com/
  ISBN: '9780199571123'
  call-number: PE1628 .O8675 2010
  first-reference-note-number: 1
  number-of-pages: '2069'
  source: Library of Congress ISBN
  id: stevenson:2010oxford
  issued:
    date-parts:
    - - 2010
  title: Oxford dictionary of English
  type: book
  publisher: Oxford University Press
  editor:
  - family: Stevenson
    given: Angus
- event-place: Oxford
  publisher-place: Oxford
  URL: http://logeion.uchicago.edu/
  call-number: PA2365 .E5 1975
  first-reference-note-number: 1
  number-of-pages: '2019'
  source: toroprod.library.utoronto.ca Library Catalogue
  id: lewis:1879latin
  issued:
    date-parts:
    - - 1879
  title: 'A Latin dictionary'
  type: book
  publisher: Clarendon Press
  editor:
  - family: Lewis
    given: Charlton T.
  - family: Short
    given: Charles
...

# Introduction

The rapid growth of terminology in computer science results in quick creation of synonyms and homographs, and also leads to extensive polysemy. As there exist no general rules pertaining to the terminology in the field other than common sense, misunderstandings are common. This is illustrated by the use of the word *node*. It comes from classical Latin *nōdus*, which means 'knot' [@lewis:1879latin, s.v. 'nodus'], and it keeps its basic meaning in the field of computer science. The *Oxford English Dictionary* (*OED*) suggests that *nōdus* could come from the same Indo-European base as *net*, where a base would mean 'to bind, twist together' [@simpson:1989oxford, s.v. 'net', n.^1^], and this possible connection becomes prominent in computer science, as the term *node* generally refers to a unit in a network of similar units. For a person that tends to focus on algorithms, a node is a point in a graph; for those from the world of networking, a node is any machine: often a client machine, though the definition could also include routers and switches, or refer to a laptop, desktop, or even a Raspberry Pi. Given such imprecise terminology, comprehension between two speakers depends on their familiarity with the context, mutual agreement on terms used, and a desire to understand each other. Words that one computer scientist treats as synonyms the other could easily treat as homonyms.

The focus of this paper is to examine and analyse etymology of terminology used in the world of computer science. The words are selected from two recent papers published in the proceedings of the IEEE 30th International Conference on Data Engineering [@christodoulakis:2014voidwiz; @volkovs:2014continuous], based on two criteria: either they could have a different meaning in various areas of computer science, or they are used frequently in this field.

# Discussion

*Algorithm* is used by computer scientists so frequently that one probably cannot imagine terminology without it. Indeed, algorithms are found everywhere, from frameworks for web development to complex routing protocols in networking. *Algorithm* comes from post-classical Latin *algorithmus* (15th cent.), an alteration of *algorismus*, formed in turn from ancient Greek ἀριθμός, 'number' [@simpson:1989oxford, s.v. 'algorithm', n.]. Tracing it further using the *OED*, we can see that *algorithmus* was used in reference to the 'Arabic system of numbering', or to the 'arithmetic in which Arabic numerals are used' [@simpson:1989oxford, s.v. 'algorism', n.]. Since an algorithm in computer science can be thought of as a sequence of ordered steps, which, in turn, can be numbered, this meaning change could be thought of as a metonymic shift. Related to this, any kind of code editor would provide line numbering, so each line of code, being a line in an editor, could also be thought of as a step having a specific number. Front-end web programming strays from this somewhat due to the nature of asynchronous calls: one cannot be sure at which point in time will the execution of a specific function happen, yet we write code that depends on successful execution of the code, as well as we provide safeguards for the case of failure. Thus, front-end web programming retains the sense of instructions, yet loses the concept of timed execution. Also, it generally cannot guarantee that the code will execute in order it is written. One might speculate that this accounts for the infrequent use of the term *algorithm* in web development terminology with respect to the front end as opposed to the back end.

Another common term in the world of computer science is *implementation*, where 'to implement' typically implies the meaning 'to create'. This term is used frequently with respect to adding new features to the product. *Implementation* ('the action of implementing; fulfillment') can be decomposed to the verb *implement* and suffix *-ation* [@simpson:1989oxford, s.v. 'implementation', n.]. While the suffix is a particular form which forms nouns of action [@simpson:1989oxford, s.v. '-ation', suffix], the verb *implement* can be traced further to the noun of the same form, which implies that the verb was formed via zero derivation [@simpson:1989oxford, s.v. 'implement', v.]. The *OED* describes *implement* as coming from Latin *implēmentum* ('a filling up taken in the sense of "that which serves to fill up or stock (a house, etc.)"'), which, in turn, originates from *implēre* ('to fill') [@simpson:1989oxford, s.v. 'implement', n.]. By contrast, Lewis and Short's *Latin Dictionary* defines *implementum* as 'a filling up, as a diseased condition' [@lewis:1879latin, s.v. 'implementum']. The meaning suggested by the *OED* seems closer to the modern meaning of the word, as by implementing new features we add more functionality to the program.

*Inconsistent* is perhaps the word that computer science engineers hate the most. To be consistent means to follow conventions, which makes code more readable and much easier to fix in case there are bugs in it; yet writing code that is consistent with ancient legacy code can become an exercise in frustration. *Inconsistent* is composed of prefix *in-* and adjective *consistent* [@simpson:1989oxford, s.v. 'inconsistent', adj. and n.]. The *OED* defines *'in-'* as the Latin *in-*, cognate with Greek α-, αν- and Common Germanic *un-*, prefixed to adjectives and their derivatives, rarely to other words, to express negation or privation [@simpson:1989oxford, s.v. 'in-', prefix^3^]. In our case, it is negation. *Consistent* is etymologically from Latin *consistentem*, present participle of consistĕre [@simpson:1989oxford, s.v. 'consistent', adj. and n.], which can be further decomposed to *con-* ('altogether') and *sistĕre* ('to cause to stand, place, stand, stand firm, stand still, stop, etc.') [@simpson:1989oxford, s.v. 'consist', v.]. We could easily extend this definition to the one used in computer science; one must either stay with the original conventions or, in case a change in style or design is required, such a change should be implemented throughout the codebase.

*Hypothesize* is composed of the noun *hypothesis* and the verb-forming suffix *-ize* [@simpson:1989oxford, s.v. 'hypothesize', v.]. This suffix could be traced from late Latin *-izāre, -īzāre*, to Greek -ίζειν (formative of verbs) [@simpson:1989oxford, s.v. '-ize', suffix]. The idea of an hypothesis is as important in computer science as any other field of research. The term originates from Greek ὑπόθεσις ('foundation, base; hence, basis of an argument, supposition, also, subject matter, etc.'), and can be decomposed further into ὑπό ('under') and θέσις ('placing') [@simpson:1989oxford, s.v. 'hypothesis', n.]. Liddell and Scott's *Greek Lexicon* suggests multiple definitions for θέσις, among which 'setting, placing, setting of words in verse' seems relevant to the present meaning, as well as the philosophical 'position, assumed and requiring proof' [@liddell:1940greek, s.v. 'θέσις'].

The term *empirically* can be found in many research papers. One can empirically determine whether a program runs well or crashes by executing it, making this term a source of inside jokes. *Empirically* ('by means of experience, observation, or experiment; [also] demonstrably, verifiably') is composed of adjective *empirical* and suffix *-ly* [@simpson:1989oxford, s.v. 'empirically', adv.]. *Empirical* is constructed from post-classical Latin *empiricus* and suffix *-al* [@simpson:1989oxford, s.v. 'empirical', adj. and n.]. The suffix *-al* comes from French *-al* and its Latin etymon *-ālis*, an adjectival suffix ('of the kind of, relating to') [@simpson:1989oxford, s.v. '-al', suffix^1^]. *Empiric* has a more complicated history: if we treat it as a noun, the *OED* claims it is partly from post-classical Latin *empirica* ('remedy' or 'medicine') and partly from classical Latin *empīricus* ('physician who relies on observation and practice rather than on philosophical theory'), which originated from Hellenistic Greek ἐμπειρικός ('experienced'). An adjective could be traced to the same ἐμπειρικός, which etymologically comes from ἐμπειρία ('experience') and -ικός ('pertaining to') [@simpson:1989oxford, s.v. 'empiric', n. and adj.].

*Infrequent* comes etymologically from Latin *infrequentem*, which is composed of *in-* and *frequentem* ('frequent') [@simpson:1989oxford, s.v. 'infrequent', adj.]. As we have already seen, the prefix simply marks negation. The rest of the word is of a much higher interest. Most computer scientists use it implying the number of occurrences of a specific event repeated per a given unit of time. Those interacting with hardware, such as those programming operating systems at a low level, narrow it down more specifically, using *frequency* to indicate the clock rate of the processor. The noun *frequent* is formed from the same verb (perhaps, via zero-derivation) [@simpson:1989oxford, s.v. 'frequent', n.], which comes from Latin *frequentāre*, which is, in turn, from *frequentem* [@simpson:1989oxford, s.v. 'frequent', v.].

*Conditional* has two meanings in computer science, demonstrating a good use of polysemy. One meaning is 'subject to, depending on, or limited by, one or more conditions; not absolute; made or granted on certain terms or stipulations', which is the general meaning of the word. The second meaning is, however, rather specific, as it is a shorthand for 'conditional operator'. The history of the word can be traced from Middle English *condicionel* through Old French *condicionel* to Latin *condiciōnālem*, which is constructed from *condiciōn-* and the already discussed suffix *-al* [@simpson:1989oxford, s.v. 'conditional', adj. and n.]. *Condiciōnem* ('a compact, stipulation, agreement upon terms') is to be immediately related to *condīcĕre* ('to talk a thing over together, agree upon'), which consists of *con-* ('together') and *dīcĕre* ('to declare, tell, say, etc.') [@simpson:1989oxford, s.v. 'condition', n.].

*Incompleteness* is composed of the noun *incomplete* and the suffix *-ness* [@simpson:1989oxford, s.v. 'incompleteness', n.]. The noun comes from Latin *incomplētus*, being composed of prefix *in-* and adjective *complētus* ('complete') [@simpson:1989oxford, s.v. 'incomplete', adj.]. The prefix *in-*, as earlier cases, is simply a negation. *Complete*, on the other hand, is a much more interesting term to investigate, as it has a specific meaning in computational complexity theory. A problem is being called NP-complete if it is, formally, NP and NP-hard. In a more humanly spoken language this means that the computer science community does not know whether there exists a polynomial time solution for this problem. *Complētus* is past participle of *complēre* ('to fill up, finish, fulfil'), and is composed of the intensive prefix *com-* and *plēre* ('to fill') [@simpson:1989oxford, s.v. 'complete', adj.].

The use of *prediction* in computer science is consistent with its typical meaning in English. It originates from classical Latin *praedictiōn-, praedictiō* ('act of mentioning in advance, prediction, prophecy'), and is constructed from *praedict-*, past participial stem of *praedīcere* ('predict') and suffix *-iō* [@simpson:1989oxford, s.v. 'prediction', n.]. The role of the suffix is to form nouns [@simpson:1989oxford, s.v. '-ion', suffix^1^]. *Praedīcere* is composed of *prae-* and *dīcere* ('to say, tell') [@simpson:1989oxford, s.v. 'predict', v.]. *Prae-* ('before, use as') is supposedly from the same Indo-European base as *fore* [@simpson:1989oxford, s.v. 'pre-', prefix].

*Mathematical* either originates from post-classical Latin *mathematicalis* ('mathematical'), or is composed of classical Latin *mathēmaticus* and suffix *-al*, which as we have already discussed means 'pertaining to' [@simpson:1989oxford, s.v. 'mathematical', adj. and n.]. Latin *mathēmaticus* (one of the meanings of which, is, surprisingly, 'astrologer') comes from ancient Greek μαθηματικός ('mathematical, mathematician'), originating from μαθηματ-, μάθημα ('something learned, knowledge, the mathematical sciences') and the already discussed suffix -ικός [@simpson:1989oxford, s.v. 'mathematic', n. and adj.]. Liddell and Scott's *Greek Lexicon* describes μαθητικός, among other meanings, as 'fond of learning' [@liddell:1940greek, s.v. 'μαθηματικός'].

*Incremental* is composed of the noun *increment* and the already discussed suffix *-al* [@simpson:1989oxford, s.v. 'incremental', adj.]. *Increment* comes from Latin *incrēmentum* ('increase, means of growth'), which, in turn, comes from the stem of *incrēscĕre* ('to increase') and suffix *-ment* [@simpson:1989oxford, s.v. 'increment', n.]. The suffix seems to originate from a Indo-European base that forms nouns from verbs [@simpson:1989oxford, s.v. '-ment', suffix]. *Incrēscĕre* can be further decomposed to prefix *in-* and *crēscĕre* ('to grow') [@simpson:1989oxford, s.v. 'increase', v.]. The meaning of the prefix in this case is 'into, in, within; on, upon; towards, against' [@simpson:1989oxford, s.v. 'in-', prefix]. *Increment* or more specifically *to increment* occurs frequently in computer science terminology mostly due to the concept of incrementing (or, more rarely, decrementing) a counter in a loop.

Computer science cannot exist without the concept of a *database*. Information has to be stored and retrieved from a specific location, and there must be a way to organize and analyse it as fast as possible. By convention, when referring to databases and drawing their representation on whiteboards people draw a cylinder, due to the shape of a platter in a hard-disk drive. This term comes from French *disque* and its etymon is a classical Latin *discus* ('round flat object, also kind of dish', in post-classical Latin also 'surface' or 'face of the sun'), which originates from ancient Greek δίσκος, which is composed of δικεῖν ('to throw, cast') and a noun-forming suffix -σκος [@simpson:1989oxford, s.v. 'disc', n.]. The term *database* is a compound of *data* and *base* [@simpson:1989oxford, s.v. 'database', n.]. *Data* comes from classical Latin *data*, plural of *datum*, in common usage usually treated a mass noun [@simpson:1989oxford, s.v. 'data', n.]. The word is often found in the context of the phrase *big data*, referring to enormously large data sets that are difficult to process and, in order to do so, specific technologies and patterns are required. *Base* originates from Anglo-Norman *basse*, Anglo-Norman and Old/Middle French *base* ('foundation, pedestal, base of a column, bottom, ground, base of a geometrical figure'), which comes from classical Latin *basis* (retaining the meanings mentioned above). This, in turn, comes from ancient Greek βάσις, which adds meanings 'step, stepping, foot' to the already mentioned ones and is composed of the stem of βαίνειν, 'to go' (which comes from the same Indo-European base as *come*) and suffix -σις [@simpson:1989oxford, s.v. 'base', n.^1^].

*Collection* is most frequently used in computer science as in modern English, but one can observe some deviations within the field. For example, Java has an incredibly useful interface named *collection* which represents a group of objects. In Backbone.js, on the other hand, *collections* are ordered sets of models, which contain both data and logic surrounding it with respect to the database. There is potential here for the term to be misunderstood, and its meaning should be clarified whenever it is used. *Collection* comes from Old French *collection*, which could be traced to Latin *collectiōnem* ('gathering together or up', noun of action), originating from *colligĕre* ('to collect') [@simpson:1989oxford, s.v. 'collection', n.]. This can be decomposed into *col-* and *legĕre* ('to gather') [@simpson:1989oxford, s.v. 'collect', v.].

*Stochastic* serves as a good reminder that statistics gets closer to computer science. It comes from Greek στοχαστικός, which originates from στοχάζεσθαι ('to aim at a mark, guess'), and this could be further traced to στόχος ('aim, guess') [@simpson:1989oxford, s.v. 'stochastic', adj.].

Yet another word that seems to be obtaining a new meaning is *propagation*. In networking, the term *propagation delay* is used to refer to amount of time it takes for the head of the signal to travel from the sender to the receiver. The term has similar meaning in operating systems as well. In web programming, conversely, *event propagation* refers to event bubbling and event capturing on the web page. In this case, *propagation* retains the same idea of moving forward, but loses the flavour of being first. Due to the fact both terms are compounds, they could be distinguished easily. A person might, however, develop an inexact notion of the term due to prior familiarity with it in another field, which may become a source for further misconceptions. *Propagation* comes from Middle French *propagacion, propagation* ('descendant, production of offspring, procreation, race, generation') and its etymon classical Latin *propāgātiōn-, propāgātiō* ('reproduction [of plants] by layers of slips, continuation of a family by procreation, transmission to posterity, action of extending in space or time, prolongation', in post-classical Latin also 'offspring, progeny'). It could be decomposed into *propāgāt-*, past participial stem of *propāgāre* ('propagate') and suffix *-iō* [@simpson:1989oxford, s.v. 'propagation', n.]. The suffix *-iō* is from classical Latin and its role is forming nouns of condition or action [@simpson:1989oxford, s.v. '-ion', suffix^1^]. *Propāgāre* is composed of prefix *pro-* and *pag-*, stem of *pangere* ('to fix, fasten, set, plant') [@simpson:1989oxford, s.v. 'propagate', v.]. *Pro-* ('out, with outward extension') comes from classical Latin *prō-* [@simpson:1989oxford, s.v. 'pro-', prefix^1^].

*Value* is another word that cannot be forgotten while talking about computer science. Variables are everywhere; variables have values. Variables, their values, and the manipulation of those composes the essence of coding. This term also refers to contents of a hash table bucket corresponding to a certain key. *Value* comes from Anglo-Norman *valu, valeu, valew, valwe, walue*, Anglo-Norman and Old French *valuwe*, Anglo-Norman and Old French, Middle French *value* ('material worth, price, fair equivalent, reputation, (personal) merit', in Anglo-Norman also 'importance (of a person), social standing') [@simpson:1989oxford, s.v. 'value', n.]. In computer science, a *value* is an expression which cannot be evaluated any further. A value can be a complex object or some kind of primitive that cannot be evaluated further; we can relate the meanings provided by the *OED* to this case. We can also trace the origins of the word further, discovering that it comes from classical Latin *valēre* [@simpson:1989oxford, s.v. 'value', n.].

*Organization* conveys the general meaning of 'order', or of something being put together. *Computer organization* describes the way the elements in computer are put together, starting from basic logic gates and finally coming to microprocessors. *Code organization* is a less frequent term which implies that the code is structured with respect to some design principles. *Organization* comes from Middle French *organisation* and its etymon post-classical Latin *organizatio* ('organization'). This could be further decomposed into *organizat-*, past participial stem of *organizare* ('organize') and classical Latin *-iō* (which we already have discussed above) [@simpson:1989oxford, s.v. 'organization', n.]. *Organizare* ('to accompany on the organ, to arrange, to provide with bodily organs or physical structure') originates from classical Latin *organum* ('organ') and suffix *-izāre* [@simpson:1989oxford, s.v. 'organize', v.]. The suffix can be traced to Greek -ίζειν, formative of verbs.

*Application* has multiple meanings. One is rather familiar: 'the action or fact of putting something to a use or purpose; employment, specific use'. The other is specific to the field: 'a function performed by a computer to meet a specific user requirement; (now usually) a program or piece of software designed to perform such a function' [@simpson:1989oxford, s.v. 'application', n.]. We now have a concept of a *web application* (or a *web app*), which is any software that runs in a web browser. (Plug-ins also run in the browser, but are not web applications.) An *app* is typically used to refer to an application written for a mobile device. *Application* comes from Middle French *application, applicacion, appliquation* ('action of administering a medicine or treatment, action of adapting a principle, a maxim, a comparison, etc., action of placing one thing on another or of adding one thing to another, action of using something for a particular purpose, action of touching, sustained attention, (apparent) approach of two celestial objects to one another, thing which is applied (e.g. a medical dressing), action of putting into practice or into effect, attachment or devotion') and its etymon classical Latin *applicātiōn-, applicātiō* ('action of attaching or joining', in post-classical Latin also 'action of a celestial object in approaching another, action of putting into practice, administration of a medical treatment') [@simpson:1989oxford, s.v. 'application', n.]. The closest meaning to the use of the term in the field of computer science seems to be the 'action of attaching or joining'. We can decompose the word further into *applicāt-*, past participial stem of *applicāre* ('apply') and the already discussed suffix *-iō*. It can be dissected even further into *ap-* and *plicāre* ('to fold') [@simpson:1989oxford, s.v. 'apply', v.]. Prefix *ap-* is an assimilated form of Latin ad- ('to') [@simpson:1989oxford, s.v. 'ap-', prefix^1^].

*Scalability* is a major contemporary concern. If a program works well on one machine, we want it to use multiple machines, utilizing combined computational power, increasing throughput, and performing as fast as on a single machine (or faster, if possible). The *OED* lacks a specific entry for this term, which is formed from the adjective *scalable* by adding a noun-forming suffix *-ity*. The suffix originates from French *-ité*, classical Latin -itāt-, -itās [@simpson:1989oxford, s.v. '-ity', suffix]. *Scalable* is composed from *scale* and the suffix *-able* [@simpson:1989oxford, s.v. 'scalable', adj.]. The suffix comes from Anglo-Norman and French *-able* and its etymon classical Latin *-ābilis*, a suffix forming adjectives, the special form taken by the suffix *-bilis* when added to verbs in *-āre* [@simpson:1989oxford, s.v. '-able', suffix]. The verb *scale* can be traced to a noun *scale* [@simpson:1989oxford, s.v. 'scale', v.^3^], possibly indicating zero derivation. *Scale* comes from Italian *scala* or its source Latin *scāla* (a ladder), from *scandĕre* ('to climb') [@simpson:1989oxford, s.v. 'scale', n.^3^].

Another word that is directly from statistics, showing how closely these fields are connected, is *distribution*. It comes from French *distribution*, earlier *-cion*, which can be traced to Latin *distribūtiōnem* (noun of action), that comes from *distribuĕre*, 'to distribute' [@simpson:1989oxford, s.v. 'distribution', n.]. *Distribuĕre* can be further decomposed into prefix *dis-* ('in various directions') and *tribuĕre* ('to assign, grant, deliver').

*Tuple* has different meanings in some areas of computer science. For those coding in Python, a *tuple* is an immutable structure containing at least one value. For someone working with databases, a *tuple* is a record in a database. There is no agreement on the pronunciation of the term, which adds to the confusion. *Tuple* as a standalone term is not yet included in the *OED*; it comes from *-tuple* [@stevenson:2010oxford, s.v. 'tuple'], while *-tuple* ('with preceding algebraic symbol: [an entity or set] consisting of as many parts or elements as indicated by the symbol') acts as a suffix formed from *quintuple*, from post-classical Latin *quintuplus* [@simpson:1989oxford, s.v. '-tuple', adj. and n.].

*Relation* is used in many phrases, as in *recurrence relation*. *Recurrence relations* are used to describe the running time of divide and conquer algorithms. However, in the world of databases, a *relation* is a table in a database. *Relation* comes from Anglo-Norman *relacioun*, Anglo-Norman and Middle French *relation, relacion* ('report, account, connection, bond, report [in court], testimony, travel narrative, connection between people', [in geometry] 'relationship of two quantities with reference to their size, sexual relations') and its Latin etymon *relātiōn-, relātiō* ('action of laying a matter before the Senate, motion so introduced, action of referring a case back to the original magistrate', in rhetoric 'balancing of opposites, reference [of a thing] to some standard or measure of comparison, action of giving or sending in return, repayment, action of narrating, narration, recital, action of carrying back', in post-classical Latin also, in philosophy, 'connection, association, kinship'), which could be further decomposed into *relāt-* (a past participial stem of *referre*) and the already discussed suffix *-iō*. [@simpson:1989oxford, s.v. 'relation', n.]. Latin *referre* ('to bring back or again, to move back, withdraw, to report, record, to have recourse, to raise [a matter] in debate, to write down, to enter in one's accounts, to assign, to ascribe, to trace back, to give in return, to restore, to repay, to reply, to pay as a due, render, to redirect, to bring back into use, revive, to recall, to mention, relate, to go back, return, to revert') can be further decomposed to *re-* and *ferre* ('to bear, carry') [@simpson:1989oxford, s.v. 'refer', v.]. The Latin prefix *re-* is cognate with Umbrian *re-*; its further etymology is unknown. With respect to our word, it means 'back from a point reached, back to or towards the starting point' [@simpson:1989oxford, s.v. 're-', prefix].

# Conclusion

The terminology of computer science consists of numerous terms, some of which retain the meaning provided in standard dictionaries, yet for many of them, new meanings still have to be added to trusted sources. This paper has investigated the etymology of a handful of specific terms, but there are many more examples of words derived from Latin and Greek (such as *abstraction*, *protocol*, *request*, *script*, and *segmentation*). Because the nomenclature of computer science is often derived from standard English words, one finds terms with a variety of etymological backgrounds (compare *acknowledgement*, *phishing*, *cluster*, and *cloud*). The computer science community is also famous for creating acronyms such as *RSA*, *HTTP*, *SSD*, and even verbs derived from these (*to scp*, *to chmod*, etc.). Computer science grows rapidly, and so does its terminology, generating new, sometimes conflicting definitions that may have multiple meanings within specific fields.

# References
