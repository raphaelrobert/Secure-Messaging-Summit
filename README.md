# Welcome to the Secure Messaging Summit!


Find me in [github](https://github.com/claucece/Secure-Messaging-Summit/tree/master)!

This is a summit inspired by the [OTRv4 summit](https://petsymposium.org/2019/program.php)
held last year. It is a summit where people from different places
(academia, industry, open source implementations, and legal perspectives) talk
about the latest problems and advancements on the secure messaging sphere.

This form takes inspiration from the [pl-hci-school-2020](https://shriram.github.io/pl-hci-school-2020/)
organized by Sarah Chasins, Elena Glassman, Shriram Krishnamurthi and Hila Peleg,
and by the [Fourteenth Algorithmic Number Theory Symposium, ANTS-XIV](https://www.math.auckland.ac.nz/~sgal018/ANTS/index.html)
organized by Steven Galbraith.

# Information

The event will be entirely virtual.

The summit will run over two days, on the first week of September: **the 3rd and 4th of September**.
It’ll end up being centered around times convenient to the morning in the Americas,
the afternoon in Europe and Africa, and the evening in Western Asia. We are very
sorry with the people from Central, East, South, Southeast, North Asia and the
Australian continent. The next edition will prioritize the times for those
places.

The times, therefore, are:

* 3rd of September: from 8:45 NY time to ~14:15 NY time (from 14:45 CEST to ~20:15 CEST)
* 4th of September: from 11:00 NY time to ~13:30 NY time (from 17:00 CEST to ~19:30 CEST)

After each session, there will be a time for socializing, if wanted.

The schedule will be:

| 3rd                             | 4th                                        |
|---------------------------------|--------------------------------------------|
| Talks from different speakers   | Panel around the legal/political aspects   |
| Socializing time                | Socializing time                          |

## Speakers

**The list of confirmed speakers for the 3rd are:**

* [Rosario Gennaro](https://www-cs.ccny.cuny.edu/~rosario/), from the City College of New York, with the talk:

  **The Simulation Paradigm and Deniable Communications**

  *In this talk, Gennaro will survey the area of Deniable Communication and the
  use of the Simulation Paradigm to define and prove what deniability is. He will
  discuss the fundamental differences between zero-knowledge and deniability
  simulations, and then focus on the specific application of deniable
  authentication and key-exchange. He will conclude by presenting recent work
  that analyzes the deniability of widely used messaging protocols, such as
  Signal.*

* Nikolas Unger, from the University of Waterloo, with the talk:

  **What user studies tell us about secure messaging?**

  *Are people concerned about mass surveillance? How do users perceive end-to-end
  encryption and people who use it? Did the Snowden revelations alter user
  perceptions of encryption? What security properties are important to users?
  What security properties do they erroneously expect? How do these concerns
  vary among sub-populations? Should we show ciphertext to users? What threat
  actors are users concerned about? How do we visually communicate security?
  What metaphors should we use for security and privacy? Does secure messaging
  make messaging secure? Why is everyone using Zoom and Telegram? How do people
  perceive SMS and landline calls? What happened to PGP? Is adoption of secure
  messaging limited by poor usability? How should we design trust establishment
  ceremonies? Are trust establishment ceremonies even important? Are the
  values of users and developers aligned?*

  *In the past 25 years, user studies have investigated the answers to these
  questions and more. This talk surveys the most notable results from user
  studies in the academic literature with respect to questions about the
  usability and deployability of secure messaging technology. These results do
  not tell the whole story, but they do provide useful insights for protocol
  designers and software developers.*

* [Paul Rösler](http://roeslpa.de/), from the Ruhr University Bochum, with
  the talk:

  **Resolving Concurrency in Group Ratcheting Protocols**

  *Post-Compromise Security, or PCS, refers to the ability of a given protocol
  to recover—by means of normal protocol operations—from the exposure of local
  states of its (otherwise honest) participants. Reaching PCS in group messaging
  protocols so far either bases on `n` parallel two-party messaging protocol
  executions between all pairs of group members in a group of `n` users (like in
  the Signal client), or on tree based group ratcheting protocols (e.g.,
  developed in the context of the IETF Message Layer Security initiative). Both
  approaches have great restrictions: parallel pairwise executions induce for
  each state update a communication overhead of `O(n)`. While tree based
  protocols reduce this overhead to `O(log n)`, they cannot handle concurrent
  state updates. For resolving such inevitably occurring concurrent updates,
  these protocols delay reaching PCS up to `n` communication time slots
  (potentially more in asynchronous settings such as messaging). Furthermore,
  a consensus mechanism (such as a central server) is needed in practice.*

  *In this talk, based on a joint work with Alexander Bienstock and Yevgeniy
  Dodis, the speaker will discuss the trade-off between PCS, concurrency, and
  communication overhead in the context of group ratcheting. In particular, he
  will explain why state updates, concurrently initiated by `t` group members
  for reaching PCS immediately induce a communication overhead of `Ω(t)` per
  message. He will show a new group ratcheting construction that resolves the
  aforementioned restriction of concurrency but reaches a communication overhead
  of only `O(t * log(n/t))`, which smoothly increases from `O(log n)` with no
  concurrency to `O(n)` with unbounded concurrency. Thus, we present a protocol
  in which each group member can (nearly) immediately recover from exposures
  independent of concurrency in the group with almost minimal communication
  overhead. We believe that this result is of interest for the IETF Message
  Layer Security (MLS) standardization effort; but more general and more
  importantly for distributed messaging environments where concurrency is
  unavoidable.*

* [Daniel Kales](https://www.iaik.tugraz.at/person/daniel-kales/), from the
  Technical University of Graz, with the talk:

  **Mobile Private Contact Discovery**

  *Mobile Contact Discovery is a process executed by messaging applications to
  find contacts from a user's local address book that are also using the
  messaging service. Naive solutions can pose problems for the privacy of the
  user's contacts, especially, those not actually using the messaging service
  themselves. This talk will cover the basics of Mobile Contact Discovery and
  explore different variants of a cryptographic solution (Private Set
  Intersection) to this problem.  We discuss some of the problems (performance-related
  and others) of using such protocols as a solution for Mobile Contact Discovery,
  in large-scale messaging services with potentially hundreds of millions of users.*

* [Thomas Ristenpart](https://rist.tech.cornell.edu/) from Cornell Tech

  Abstract to be published soon.

* Raphael Robert from Wire

  Abstract to be published soon.

The topics that they will present vary from deniability, message franking,
group messaging, mobile private contact discovery, and concurrent ratcheting.
Expect the missing abstracts for those talks to be published soon.

**The list of confirmed participants on the panel for the 4th are:**

* Moderator: Iraklis Symeonidis from the University of Luxembourg
* [Danny O'Brien](https://www.eff.org/about/staff/danny-obrien-0) from EFF
* [Erica Portnoy](https://www.eff.org/about/staff/erica-portnoy) from EFF
* [Glacier Kwong](https://en.wikipedia.org/wiki/Glacier_Kwong) from Keyboard Freedom
* [Lobsang Gyatso](https://tibetaction.net/profile/lobsang/) from the Tibetan Action Institute
* [Carolina Botero](https://twitter.com/carobotero?lang=en) from Fundacion Karisma
* [Paulina Gutiérrez](https://indela.fund/en/paulina-gutierrez-2/) from ARTICLE19

Expect the topics to be talked on the panel to be published soon. But, they will
manly explore the challenges, threats and advantages that secure messaging
faces on different regions of the world from a legal, political and even
sociological perspective.


There are many great people in this area, and we're sorry we can't invite all of
them. If this goes well, hopefully we'll have more of them in the future!

The talks and panel might be recorded prior consent from the speakers.

# Registration

## How to Register

We have no idea how much demand there will be. We will provide a registration
form starting from August.

Registration will open on the 10th of August and end on the 30 of August. Times
for opening and closing registration will be on UTC-5.

Registration is free; but you must read and accept our [Code of Conduct](https://github.com/claucece/Secure-Messaging-Summit/blob/master/code-of-conduct.md), and be aware of the [SNAPL Friendly Environment Policy](https://snapl.org/2015/policy.html).

We require that every participant represent themselves by the name that they
use for their professional work (this can be a pseudonym that they generally
use for their professional work). No participant can impersonate another person.

### Before you register

On the Internet, signing up is cheap. Showing up is hard. Check your calendar
to make sure you're free, and block off the dates: commit to participating
before you sign up. Do not sign up until you've blocked out the dates in your
calendar.

Nevertheless, we understand that things can change. If you have signed up but
won't be participating, let us know.

### Registration form

To be provided on the 10th of August at 7:00 UTC-5. It will close on the 30 of
August at 23:00 UTC-5.

Note that you have to provide a valid email address at registration, as subsequent
communications regarding the event will be sent to that address.

There are two ways of registering:

1. By using the [google form](https://docs.google.com/forms/d/e/1FAIpQLSf1Knazuv88jaoZW1HAvK9XpHHMHh4YS2UlYsWSZoqAjKdHQw/viewform?usp=sf_link)
2. By sending an email to `securemessaging2020@riseup.net`, with the
   following information (`*` means mandatory):
   * Last Name\*,
   * First Name\*,
   * email address \*,
   * affiliation/institution\*,
   * In which time zone will you be during the summit (UTC),
   * The typed statement: 'I confirm that I have read and agree to abide by the
     code of conduct of the event' \*.
   * The typed statement: 'I confirm that I understand the SNAPL Friendly
     Environment Policy to be used at the event' \*.

You can send encrypted emails for registration and subsequent communications by
using PGP. The public key of `securemessaging2020@riseup.net` can be found
[here](https://github.com/claucece/Secure-Messaging-Summit/blob/master/SecureMessaging2020%20(BDDA279F)%20%E2%80%93%20Public.asc).
The fingerprint is: `8D6F D710 7F9A 2EC7 9634  4A8D C83B FA0F BDDA 279F`.
If you send encrypted emails, first please either send your public key or
upload it in a server where it can be publicly found.

# Format

## What we will use

* Zoom.
* Zulip: for chatting with other participants or with the speaker.
* Yotribe: for socializing after the sessions.
* YouTube: for posting the recorded talks, if consent was given.

## Who This Event is Not For

This isn't a place for people to be exclusionary or for harassment. This event
has a code of conduct and we’ll use the [SNAPL Friendly Environment Policy](https://snapl.org/2015/policy.html).

## Sponsors

This is nicely sponsored by [NLnet](https://nlnet.nl/).

You can be another sponsor if you like! ;)
