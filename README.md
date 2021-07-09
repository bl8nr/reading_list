# Cyber Reading List
A very useful reading list of technical documents related to internetworking and cybersecurity.

## History of the Internet

---

* ### [On Distributed Communications](https://www.rand.org/content/dam/rand/pubs/research_memoranda/2006/RM3420.pdf)

    #### **Baran, | The Rand Corporation**
   *First introduction to packet switched style distributed networks which were originally designed to create resilient military communications systems that could sustain pretty significant attacks.*

* ### [Brief History of the Internet](https://www.internetsociety.org/wp-content/uploads/2017/09/ISOC-History-of-the-Internet_1997.pdf)

    #### **Internet Society**
    *Literally just a brief history of the internet.*

* ### [Netheads vs Bellheads](https://www.wired.com/1996/10/atm-3/)

    #### Steingberg | WIRED Magazine
    *"The most vicious battle on the Net today is a secret war between techies. At stake is nothing less than the organization of cyberspace."*

## Networking & Internetworking

---

* ### [The Design Philosophy of the DARPA Internet Protocols](http://ccr.sigcomm.org/archive/1995/jan95/ccr-9501-clark.pdf)

    #### **Clark | M.I.T. Laboratory for Computer Science**
    *General overview of the principals/requirements that inspired the design of TCP/IP. A good explination of why TCP/IP looks and works the way it does.*

* ### [End-to-end Arguments in System Design](http://web.mit.edu/Saltzer/www/publications/endtoend/endtoend.pdf)

    #### **Saltzer, Reed & Clark | M.I.T. Laboratory for Computer Science**

* ### [Internet Protocol](https://tools.ietf.org/html/rfc791)

    #### **USC Information Sciences Institute | IETF RFC 791**

* ### [Transmission Control Protocol](https://tools.ietf.org/html/rfc793)

    #### **USC Information Sciences Institute | IETF RFC 793**

* ### [Domain Names - Concepts and Facilities](https://tools.ietf.org/html/rfc882)

  #### **Mockapetris | IETF RFC 882**
  
  *Original RFC arguing for domain names on the internet, their need and ideas for a domain name system*

* ### [Dynamic Host Configuration Protocol](https://tools.ietf.org/html/rfc1531)

  #### **Bucknell University | IETF RFC 1531**

  *RFC that outlines the system that enables computers to automatically configure themselves for network access once they're wired into a network. (i.e. why you don't need to configure anything when you connect to ethernet/WiFi)*

* ### [Congestion Control Principals](https://tools.ietf.org/html/rfc2914)

    #### **Floyd | IETF RFC 2914**
  
    *RFC describing the correct implementation of congestion control in TCP. Consider this when comparing ethernet v. WiFi for optimal performance.*


* ### [Congestion Avoidance and Control](https://ee.lbl.gov/papers/congavoid.pdf)

    #### **Jacobson, Karels**
    
    *Original research paper outlining Van Jacobson's congestion avoidance and control ideas that are widely used in today's TCP implementations.*


* ### [The IP Network Address Translator (NAT)](https://tools.ietf.org/html/rfc1631)

    #### **Egevang, Francis | IETF RFC 1631**
    *Explains how NATs work and why the world can have more internet connected devices than the internet has IP addresses (at least in IPv4).*


* ### [Address Allocation for Private Internets](https://tools.ietf.org/html/rfc1918)

    #### **Rekhter, Moskowitz, Karrenberg, de Groot, Lear | IETF RFC 1918**
    *This may help you make sense of device addressing inside your NAT, like what is 192.168.0.0?*

* ### [Software-Defined Networking (SDN)](https://web.archive.org/web/20170830023729/http://inst.eecs.berkeley.edu/~ee122/fa11/notes/18-SDN122-lecture.pdf)

  #### **Shenker | EE122 Fall 2011**
  *A short slide deck on software-defined networks and why programmable data-planes and centralized control-planes are probably the future of networking*

## The Cloud

---

* ### [TIA-942 Data Center Standards Overview](https://www.accu-tech.com/hs-fs/hub/54495/file-15894024-pdf/docs/102264ae.pdf)

  #### **ADC Telecommunications | TIA-942**
  *A very high level overview of datacenter standards/construction*

## General Cybersecurity

---
* ### [Computer Security Incident Handling Guide](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-61r2.pdf)

    #### **NIST Publiction 800-61**

* ### [Exploring Web Authentication Schemes](https://www.cl.cam.ac.uk/~fms27/papers/2012-BonneauHerOorSta-password--oakland.pdf)

    #### **Bonneau, Herley, van Oorschot, Stajano**

* ### [Reflections on Trusting Trust](https://www.cs.cmu.edu/~rdriley/487/papers/Thompson_1984_ReflectionsonTrustingTrust.pdf)

    #### **Ken Thompson | Turing Award Lecture**

* ### [Trusting Trust](http://web.mit.edu/6.033/2014/wwwdocs/assignments/quizzes/trust_stack_slides.pdf)

    #### **MIT Slide Deck**

* ### [Countering Trusting Trust](https://www.schneier.com/blog/archives/2006/01/countering_trus.html)

    #### **Bruce Schneier | Schneier on Security**

* ### [Designing an Authentication System: a Dialogue in Four Scenes](http://web.mit.edu/kerberos/dialogue.html)

    #### **Bryant | M.I.T.**
    *In the form of a dialogue, describes how M.I.T.'s Kerberos authentication system works.*

* ### [Randomness Requirements for Security](https://tools.ietf.org/html/rfc4086)

  #### **Eastlake, Schiller, Crocker| IETF RFC 4086**
  *Interesting RFC about the importance of entropy in cybersecure systems and different methods that can be used to achieve randomness (or pseudorandomness)*

## Cyber Warfare & Espionage

---
* ### [Intelligence-Driven Computer Network Defense](https://www.lockheedmartin.com/content/dam/lockheed-martin/rms/documents/cyber/LM-White-Paper-Intel-Driven-Defense.pdf)

    #### **Hutchins, Cloppert, Amin | Lockheed Martin Corporation**

* ### [APT 1 Exposing One of China’s Cyber Espionage Units ](https://wmx-api-production.s3.amazonaws.com/courses/3455/supplementary/mandiant-apt1-report.pdf)

    #### **Mandiant Solutions | FireEye**

## Encryption

---
* ### ["Schneier's Law"](https://www.schneier.com/blog/archives/2011/04/schneiers_law.html)

    #### **Bruce Schneier | Schneier on Security**

## Blockchain

---
* ### [Hashcash: A Denial of Service Counter-Measure](http://www.hashcash.org/hashcash.pdf)

    #### **Back | hashcash.org**


## TOR, Anonymity and Privacy

---
https://www.cs.cornell.edu/people/egs/papers/egs-herbivore.pdf
https://users.ece.cmu.edu/~adrian/731-sp04/readings/dcnets.html Chaumian DC-Nets
https://www.freehaven.net/anonbib/cache/chaum-mix.pdf
http://www.cs.jhu.edu/~fabian/courses/CS600.424/course_papers/goldschlag96hiding.pdf
https://www.usenix.org/legacy/publications/library/proceedings/sec04/tech/full_papers/dingledine/dingledine.pdf

## Exploit Specific Readings

---

* ### [The Rise and Decline ofNTP DDoS Attacks](https://conferences.sigcomm.org/imc/2014/papers/p435.pdf)

    #### **Czyz, Kallitsis, Gharaibeh, Papadopoulos, Bailey, Karir**

* ### [How security flaws work: The buffer overflow](https://arstechnica.com/information-technology/2015/08/how-security-flaws-work-the-buffer-overflow/)

    #### **Ars Staff | Ars Technica**
    *Just an article about how buffer overflows work*


## Other Stuff

---
* ### [Guidelines for Evidence Collection and Archiving](https://tools.ietf.org/html/rfc3227)

    #### **Brezinski, Killalea | IETF RFC 3227**


https://www.schneier.com/wp-content/uploads/2016/02/paper-self-study.pdf
https://www.sans.org/reading-room/whitepapers/vpns/prime-numbers-public-key-cryptography-969
https://wmx-api-production.s3.amazonaws.com/courses/3455/supplementary/STIX_Whitepaper_v1.1.pdf
