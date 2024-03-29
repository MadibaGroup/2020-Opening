# Appendix: Description of Each Category 
## Facts: Definition or Description

Many papers start with a straightforward definition of the subject of the paper. These tend to be neutral and like something you’d read in a glossary.

>Malware sandboxes are automated dynamic analysis tools that execute samples in an isolated and instrumented environment.

>Secure two-party computation allows two parties to process their sensitive data in such a way that its privacy is protected.

>HMAC is a cryptographic authentication algorithm, the ‘Keyed-Hash Message Authentication Code,’ widely used in conjunction with the SHA-256 cryptographic hashing primitive.

Similarly, papers might provide a description of what the subject of a sentence does or how it works. These are also neutral statements and like something you’d read in a textbook. 

>Traditionally, digital investigations have aimed to recover evidence of a cyber-crime or perform incident response via analysis of non-volatile storage.

>Mobile social applications discover nearby users and provide services based on user activity (what the user is doing) and context (who and what is nearby).

>To reduce the memory footprint of a system, the system software shares identical memory pages between processes running on the system.

## Facts: Claimed Fact

Another neutral approach to an opening sentence is to provide a fact that is relevant to the subject of the paper. Later we will discuss arguments which are often expressed as if they are facts but are only debatably true. A claimed fact’s correctness should either be apparent or at least provable (i.e., falsifiable). 

>Users are often advised or required to choose passwords that comply with certain policies.

>Mobile apps frequently demand access to private information.

>For several decades, car keys have been used to physically secure vehicles.

Some sentences use stronger and more vivid language but are still factually based. 

>In spite of extensive industrial and academic efforts (e.g., [3, 41, 42]), distributed denial-of-service (DDoS) attacks continue to plague the Internet.

## Facts: Technical Advances

Many opening sentences lay out a technical advance in the subject of the sentence. This creates a window of opportunity for the researcher to later identify a novel research problem caused by the changing technology.  It is common to see words like: evolve, become, transition, and improve.

>Recent advances in cloud computing enable customers to outsource their computing tasks to the cloud service providers (CSPs).

>Browsers have evolved over recent years to mediate a wealth of user interactions with sensitive data.

>Since its beginning in the early nineties, the Web evolved from a mechanism to publish and link static documents into a sophisticated platform for distributed Web applications

## Facts: Historic Events

A final neutral opening sentence will refer to some historic event. 

>In 1996, Wagner and Schneier performed an analysis of the SSL 3.0 protocol [67].

>In February 2011, a new Tor hidden service [16], called “Silk Road,” opened its 
doors.

>The Network Time Protocol (NTP) is one of the Internet’s oldest protocols, dating back to RFC 958 [15] published in 1985.

In some cases, a paper opens with a “compound” sentence that makes reference to a historic event in one clause of the sentence, while having additional clauses of a different category. For example, the following sentence refers to a historic event as well as a technical advance.

>Starting from Denning’s seminal work in 1986 [9], intrusion detection has evolved into a number of different approaches.

## Arguments: General Argument

Many opening sentences issue a subjective argument that represents the authors’ opinion. Unlike a fact, it isn’t straightforward that the reader will accept it as true. While arguments are less neutral than facts, they can be more interesting and provocative, which can help draw the reader into the paper.

The arguments we categorize under “general arguments” do not fit elsewhere in our categorization system. As we go through more categories, we will see other more specific kinds of arguments. 

>It is a truth universally acknowledged, that password-based authentication on the web is insecure.

>The dismissal of human memory by the security community reached the point of parody long ago.

>In recent years, unwanted software has risen to the forefront of threats facing users.

>The phenomenal growth of Android devices brings in a vibrant application ecosystem.

## Arguments: Problem Statement 

A special type of argument is a “problem statement” which uses the opening sentence to establish a problem or challenge to be solved. 

>A key challenge when running untrusted virtual machines is providing them with efficient and secure I/O.

>Determining the semantic similarity between two pieces of binary code is a central problem in a number of security settings.

>It is difficult to keep secrets during program execution.

For some sentences, the problem is not stated explicitly but can be inferred from what is said. For example, the “pressure to respond” in the following sentence implies a problem.

>As popular applications rely on personal, privacy-sensitive information about users, factors such as legal regulations, industry self-regulation, and a growing body of privacy-conscious users all pressure developers to respond to demands for privacy.

## Suitability: Importance of subject

A large set of sentences make a special kind of argument: that the subject of the opening sentence is suitable or worthy of research. The exact reasons they are suitable fall into a few sub-categories: the subject is important, ubiquitous, complex, novel, popular with other researchers, or has been around a long time. 

Many opening sentences state that their subject is important, with the implication that it is thus suitable for research.

>Security has now become an important and real concern to connected and/or automated vehicles.

>Error handling is an important aspect of software development.

>SSL/TLS is, due to its enormous importance, a major target for attacks.

Some sentences do not explicitly use the word “important” but find other ways to convey the same notion. For example, a concern or component might be described as essential or crucial or serious.

>The threat of data theft in public and private clouds from insiders (e.g. curious administrators) is a serious concern.

>The same-origin policy (SOP) is a cornerstone of web security, guarding the web content of one domain from the access from another domain.

## Suitability: Ubiquity of subject

The most popular kind of opening sentence argues that a subject is suitable for research because it is ubiquitous and widely used.

>Billions of users now depend on online services for sensitive communication.

>Embedded systems are omnipresent in our everyday life.

>Android is the major platform for mobile users and mobile app developers.

## Suitability: Popularity of subject

While the ubiquity of a subject corresponds to how widely it is used, a closely related variant points out that the subject has received a lot of attention. Often, this means attention from other researchers which lends credibility to the subject for further research.

>Protecting the privacy of user data within mobile applications (apps for short) has always been at the spotlight of mobile security research.

>The black-market economy for purchasing Facebook likes, Twitter followers, and Yelp and Amazon reviews has been widely acknowledged in both industry and academia [6, 27, 37, 58, 59].

>Since the first widely-exploited buffer overflow used by the 1998 Morris worm [27], the prevention, exploitation, and mitigation of memory corruption vulnerabilities have occupied the time of security researchers and cybercriminals alike.

## Suitability: Longevity of subject 

In this category, how long a subject has been around is the key component to why it is a suitable subject for study. In some cases, a specific duration is provided and in others, it is implied that the amount of time is significant.

>Redaction of sensitive information from documents has been used since ancient times as a means of concealing and removing secrets from texts intended for public release.

>Since its beginning in the early nineties, the Web evolved from a mechanism to publish and link static documents into a sophisticated platform for distributed Web applications.

## Suitability: Complexity of subject

In this category, the complexity of the subject is highlighted, implying that the complexity creates new issues or requires further research. The complexity might be inherent to the subject itself. Or there might be a complex set of external factors to consider.

>Today, large and complex software is built with many components integrated using APIs.

>The capabilities and limitations of disassembly are not always clearly defined or understood, making it difficult for researchers and reviewers to judge the practical feasibility of techniques based on it.

>As popular applications rely on personal, privacy-sensitive information about users, factors such as legal regulations, industry self-regulation, and a growing body of privacy-conscious users all pressure developers to respond to demands for privacy.

## Suitability: Novelty of subject

Finally, a degree of novelty is an important component in any research question so it is unsurprising that papers begin arguing novelty from their opening sentence. In this category, sentences focus on something that is new or emerging. 

>In the last few years, a new class of cyber attacks has emerged that is more targeted at individuals and organizations.

>Although the operating system (OS) kernel has always been an appealing target, until recently attackers focused mostly on the exploitation of vulnerabilities in server and client applications— which often run with administrative privileges—as they are (for the most part) less complex to analyze and easier to compromise.

This sentence manages to appeal to both longevity and novelty by relating two subjects.

>While cryptocurrency has been studied since the 1980s [22, 25, 28], bitcoin is the first to see widespread adoption.

## Narrative

A potentially interesting way to draw a reader into a paper is by establishing a narrative: a scenario that gets the reader thinking about themselves or other people and what they might do.  

>Consider that you are a domain owner, holding a few domain names that you do not have a better use of.

>Consider the setting where a client owns a public input x, a server owns a private input w, and the client wishes to learn z := F(x,w) for a program F known to both parties.

Narratives might also set a scene, like the academic version of an “establishing shot” from films and TV. 

>Our phones are always within reach and their location is mostly the same as our location.

>We live in a “big data” world.

>The battle for the living room is in full swing.

## Question  

Making the reader curious is another good way to begin a paper, and this can be accomplished using a question. In our sample, this was underused with only one example.

>Do programmers leave fingerprints in their source code?
