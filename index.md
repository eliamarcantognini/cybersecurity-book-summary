# Cybersecurity 21-22 summary

- [Cybersecurity 21-22 summary](#cybersecurity-21-22-summary)
  - [Chapter 1](#chapter-1)
    - [1.1 Computer Security Concepts](#11-computer-security-concepts)
      - [Levels of impact](#levels-of-impact)
      - [The challenges of computer security](#the-challenges-of-computer-security)
      - [A model for computer security](#a-model-for-computer-security)
    - [1.2 Threats, Attacks, and Assets](#12-threats-attacks-and-assets)
      - [Threats and Attacks](#threats-and-attacks)
      - [Threats and Assets](#threats-and-assets)
        - [Hardware](#hardware)
        - [Software](#software)
        - [Data](#data)
        - [Communication lines and networks](#communication-lines-and-networks)
    - [1.4 Fundamental Security Design Principles](#14-fundamental-security-design-principles)
    - [1.5 Attack Surfaces and Attack Trees](#15-attack-surfaces-and-attack-trees)
      - [Attack Surfaces](#attack-surfaces)
      - [Attack Trees](#attack-trees)
    - [1.6 Computer Security Strategy](#16-computer-security-strategy)
      - [Security Policy](#security-policy)
      - [Security Implementation](#security-implementation)
      - [Assurance and Evaluation](#assurance-and-evaluation)
  - [Chapter 2](#chapter-2)
    - [2.1 Confidentiality with Symmetric Encryption](#21-confidentiality-with-symmetric-encryption)
      - [Symmetric  Encryption](#symmetric--encryption)
      - [Symmetric Block Encryption Algorithms](#symmetric-block-encryption-algorithms)
        - [Data Encryption Standard](#data-encryption-standard)
        - [Triple DES](#triple-des)
        - [Advanced Encryption Standard](#advanced-encryption-standard)
      - [Stream Ciphers](#stream-ciphers)
    - [2.2 Message Authentication and Hash Functions](#22-message-authentication-and-hash-functions)
      - [Authentication Using Symmetric Encryption](#authentication-using-symmetric-encryption)
      - [Message Authentication without Message Encryption](#message-authentication-without-message-encryption)
        - [Message Authentication Code](#message-authentication-code)
        - [One-Way Hash Function](#one-way-hash-function)
      - [Secure Hash Functions](#secure-hash-functions)
      - [Hash Function Requirements](#hash-function-requirements)
        - [Security of Hash Functions](#security-of-hash-functions)
        - [Secure Hash Function ALgorithms](#secure-hash-function-algorithms)
    - [2.3 Public-Key Encryption](#23-public-key-encryption)
      - [Public-Key Encryption Structure](#public-key-encryption-structure)
      - [Applications for Public-Key Cryptosystems](#applications-for-public-key-cryptosystems)
      - [Requirements for Public-Key Cryptography](#requirements-for-public-key-cryptography)
      - [Asymmetric Encryption ALgorithms](#asymmetric-encryption-algorithms)
        - [RSA](#rsa)
        - [Diffie-Hellman Key Agreement](#diffie-hellman-key-agreement)
        - [Digital Signature Standard](#digital-signature-standard)
        - [Elliptic Curve Cryptography](#elliptic-curve-cryptography)
    - [2.4 Digital Signatures and Key Management](#24-digital-signatures-and-key-management)
      - [Digital Signature](#digital-signature)
      - [Public-Key Certificates](#public-key-certificates)
      - [Symmetric Key Exchange Using Public-Key Encryption](#symmetric-key-exchange-using-public-key-encryption)
      - [Digital Envelopes](#digital-envelopes)
    - [2.5 Random and Pseudorandom Numbers](#25-random-and-pseudorandom-numbers)
      - [The Use of Random Numbers](#the-use-of-random-numbers)
        - [Randomness](#randomness)
        - [Unpredictability](#unpredictability)
      - [Random versus Pseudorandom](#random-versus-pseudorandom)
  - [Chapter 3](#chapter-3)
    - [3.1 Digital User Authentication Principles](#31-digital-user-authentication-principles)
      - [Means of Authentication](#means-of-authentication)
    - [3.2 Password-Based Authentication](#32-password-based-authentication)
      - [The Vulnerability of Passwords](#the-vulnerability-of-passwords)
      - [The use of Hashed Passwords](#the-use-of-hashed-passwords)
        - [UNIX Implementations](#unix-implementations)
      - [Password Cracking of User-Chosen Passwords](#password-cracking-of-user-chosen-passwords)
        - [Traditional Approaches](#traditional-approaches)
        - [Modern Approaches](#modern-approaches)
      - [Password File Access Control](#password-file-access-control)
      - [Password Selection Strategies](#password-selection-strategies)
        - [Rule Enforcement](#rule-enforcement)
        - [Password Checker](#password-checker)
    - [3.3 Token-Based Authentication](#33-token-based-authentication)
      - [Memory Cards](#memory-cards)
      - [Smart Cards](#smart-cards)
    - [3.4 Biometric Authentication](#34-biometric-authentication)
      - [Physical Characteristics Used in Biometric Applications](#physical-characteristics-used-in-biometric-applications)
      - [Operation of a Biometric Authentication System](#operation-of-a-biometric-authentication-system)
    - [3.5 Remote User Authentication](#35-remote-user-authentication)
      - [Password Protocol](#password-protocol)
    - [3.6 Security Issues for User Authentication](#36-security-issues-for-user-authentication)
  - [Chapter 4](#chapter-4)
    - [4.1 Access Control Principles](#41-access-control-principles)
      - [Access Control Context](#access-control-context)
      - [Access Control Policies](#access-control-policies)
    - [4.2 Subject, Objects, and Access Rights](#42-subject-objects-and-access-rights)
    - [4.3 Discretionary Access Control](#43-discretionary-access-control)
    - [4.4 Example: Unix File Access Control](#44-example-unix-file-access-control)
      - [Traditional UNIX File Access Control](#traditional-unix-file-access-control)
      - [Access Control Lists in UNIX](#access-control-lists-in-unix)
    - [4.5 Role-Based Access Control](#45-role-based-access-control)
      - [RBAC Reference Models](#rbac-reference-models)
        - [Base Model - RBAC$_0$](#base-model---rbac_0)
        - [Role Hierarchies - RBAC$_1$](#role-hierarchies---rbac_1)
        - [Constraints - RBAC$_2$](#constraints---rbac_2)
  - [Tutorials](#tutorials)
    - [T1 - Exposed attack surface (nmap)](#t1---exposed-attack-surface-nmap)
    - [T2 - DES and AES encryption using OpenSSL](#t2---des-and-aes-encryption-using-openssl)
    - [T3 - Practical dictionary attack to the symmetric encryption](#t3---practical-dictionary-attack-to-the-symmetric-encryption)
      - [First attempt](#first-attempt)
      - [Second attempt](#second-attempt)
      - [Third attempt](#third-attempt)
      - [Fourth attempt](#fourth-attempt)
    - [T4 - Usage examples of GPG](#t4---usage-examples-of-gpg)
      - [Web-of-Trust](#web-of-trust)
      - [Using GPG for symmetric encryption](#using-gpg-for-symmetric-encryption)
      - [AGE](#age)
    - [T5 - Example of pharming attack to HTTP and HTTPS](#t5---example-of-pharming-attack-to-http-and-https)
      - [Attacking HTTP](#attacking-http)
      - [Attacking HTTPS](#attacking-https)
      - [Revocation of Certificates](#revocation-of-certificates)
    - [T6 - Offline password cracking using John the Ripper (JtR)](#t6---offline-password-cracking-using-john-the-ripper-jtr)

## Chapter 1

The focus of this chapter is on three fundamental questions:

1. What assets do we need to protect?
2. How are those assets threatened?
3. What can we do to counter those threats?

### 1.1 Computer Security Concepts

*Computer Security* definition is: measures and controls that ensure *confidentiality*, *integrity* and *availability* of information system assets including hardware, software, firmware and information being processed, store and communicated.

- *Confidentiality*:
  - _Data confidentiality_: assures that private or confidential information is not made available or disclosed to unauthorized individuals.
  - *Privacy*: assures that individual control or influence what information related to them may be collected and stored and by whom and to whom that information may be disclosed.
- *Integrity*:
  - *Data integrity*: assures that information and programs are changed only in a specified and authorized manner.
  - *System integrity*: assures that a system performs its intended function in a unimpaired manner, free from deliberate or inadvertent unauthorized manipulation of the system.
- *Availability*: assures that systems work promptly and service is not denied to authorized users.

These three concepts form the *CIA triad*. The three concepts embody the fundamental security objectives for both data and for information and computing services.  
FIPS199 provides a useful characterization of these three objectives in terms of requirements and the definition of a loss of security in each category:

- *Confidentiality*: preserving authorized restrictions on information access and disclosure, including means for protecting personal privacy and proprietary information. A loss of confidentiality is the unauthorized disclosure of information.
- *Integrity*: guarding against improper information modification or destruction, including ensuring information nonrepudation and authenticity. A loss of integrity is the unauthorized modification or destruction of information.
- *Availability*: ensuring timely and reliable access to and use of information. A loss of availability is the disruption of access to or use of information or an information system.

Additional concepts are needed to present a complete picture. Two of the most commonly mentioned are:

- *Authenticity*: the property of being genuine and being able to be verified and trusted; confidence in the validity of a transmission, a message, or message originator. This means verifying that users are who they say they are and that each input arriving at the system came from a trusted source.
- *Accountability*: the security goal that generates the requirement for actions of an entity to be traced uniquely to that entity. This supports nonrepudiation, deterrence, fault isolation, intrusion detection and prevention, and after-action recovery and legal action. Because truly secure systems are not yet an achievable goal, we must be able to trace a security breach to a responsible party. Systems must keep records of their activities to permit later forensic analysis to trace security breaches or to aid in transaction disputes.

Note that FIPS 199 includes authenticity under integrity.

#### Levels of impact

We use three levels of impact on organizations or individuals, that are defined in FIPS 199:

- *Low*: the loss could be expected to have a limited adverse effect on organizational operations, organizational assets, or individuals.
- *Moderate*: the loss could be expected to have a serious adverse effect on organization operations, organizational assets, or individuals.
- *High*: the loss could be expected to have a severe or catastrophic adverse effect on organization operations, organizational assets, or individuals.

#### The challenges of computer security

1. Most of the major requirements for security services can be given self-explanatory one-word labels: confidentiality, authentication, nonrepudiation, and integrity.
2. In developing a particular security mechanism or algorithm, one must always consider potential attacks on those security features.
3. The procedures used to provide particular services are often counterintuitive.
4. Having designed various security mechanisms, it is necessary to decide where to use them.
5. Security mechanisms typically involve more than a particular algorithm or protocol. They also require that participants be in possession of some secret information, which raises questions about the creation, distribution and protection of that secret information.
6. Computer security is essentially a battle of wits between a perpetrator who tries to find holes and the designer who tries to close them.
7. There is a natural tendency to perceive little benefit from security investment until a security failure occurs.
8. Security requires regular, even constant monitoring, and this is difficult in today's short-term, overloaded environment.
9. Security is still too often an afterthought to be incorporated into a system after the design is complete, rather than being an integral part of the design process.
10. Users view strong security as an impediment to efficient and user-friendly operation of a system.

#### A model for computer security

The assets of a computer system can be categorized as follows:

- Hardware;
- Software;
- Data;
- Communication facilities and networks: Local and wide area network communication links, bridges, routers, and so on.

In the context of security, out concern is with the vulnerabilities of system resources. They can be listed in general categories as this:

- The system can be corrupted, so it does the wrong thing or gives wrong answers.
- The system can become leaky.
- The system can become unavailable or very slow.

These three general types of vulnerability correspond to the CIA concepts.
Corresponding to the various types of vulnerabilities to a system resource are *threats* that are capable of exploiting those vulnerabilities. A threat represents a potential security harm to an asset. An attack is a threat that is carried out and, if successful, leads to an undesirable violation of security, or threat consequence. The agent carrying out the attack is referred as *threat agent*. We can distinguish two types of attacks:

- Active attack: an attempt to alter system resources or affect their operation.
- Passive attack: an attempt to learn or make use of information from the system that does not affect system resources.

We can also classify attacks based on the origin of the attack:

- Inside attack: initiated by an entity inside the security perimeter.
- Outside attack: initiated from outside the perimeter, by an unauthorized or illegitimate user of the system.

Finally, a *countermeasure* is any means taken to deal with a security attack. Ideally, a countermeasure can be devised to prevent a particular type of attack from succeeding. When prevention is not possible, or fails in some instance, the goal is to detect the attack then recover from the effects of the attack.

### 1.2 Threats, Attacks, and Assets

#### Threats and Attacks

RFC 4949 describes four kinds of threat consequences and lists the kinds of attacks that result in each consequence.

- Unauthorized disclosure is a threat to confidentiality. A circumstance or event whereby an entity gains access to data for which the entity is not authorized. The following types of attacks can result in this threat consequence:
  - Exposure: sensitive data are directly released to an unauthorized entity.
  - Interception: an unauthorized entity directly accesses sensitive data traveling between authorized sources and destinations.
  - Inference: a threat action whereby an unauthorized entity indirectly accesses sensitive data (but not necessarily the data contained in the communication) by reasoning from characteristics or by-products of communications.
  - Intrusion: an unauthorized entity gains access to sensitive data by circumventing a system's security protections.
- Deception is a threat to either system integrity or data integrity. A circumstance or event that may result in an authorized entity receiving false data and believing it to be true. The following types of attacks can result in this threat consequence:
  - Masquerade: an unauthorized entity gains access to a system or performs a malicious act by posing as an authorized entity.
  - Falsification: false data deceive an authorized entity.
  - Repudiation: an entity deceives another by falsely denying responsibility for an act.
- Disruption is a threat to availability or system integrity. A circumstance or event that interrupts or prevents the correct operation of system services and functions. The following types of attacks can result in this threat consequence:
  - Incapacitation: prevents or interrupts system operation by disabling a system component.
  - Corruption: undesirably alters system operation by adversely modifyng system functions or data.
  - Obstruction: a threat action that interrupts delivery of system services by hindering system operation.
- Usurpation is a threat to system integrity. A circumstance or event that results in control of system services or functions by an unauthorized entity. The following types of attacks can result in this threat consequence:
  - Misappropriation: an entity assumes unauthorized logical or pyhysical control of a system resource.
  - Misuse: causes a system component to perform a function or service that is detrimental to system security.

#### Threats and Assets

The assets of a computer system can be categorized as hardware, software, data and communication lines and networks.

##### Hardware

A major threat to computer system hardware is the threat to availability. Hardware is the most vulnerable to attack and the least susceptible to automated controls.

##### Software

Software includes the operating system, utilities and application programs. A key threat to software is an attack on availability.

##### Data

Hardware and software security are typically concerns of computing center professionals or individual concerns of personal computer users. A much more widespread problem is data security, which involves files and other forms of data controlled by individuals, groups and business organizations.
Security concerns with respect to data are broad, encompassing availability, secrecy and integrity. In the case of availability, the concern is with the destruction of data files, which can occur either accidentally or maliciously.
The obvious concern with secrecy is the unauthorized reading of data files or databases. A less obvious threat to secrecy involves the analysis of data and manifests itself in the use of so-called statistical databases, which provide summary or aggregate information.  
Finally, data integrity is a major concern in most installations. Modifications to data files can have consequences ranging from minor to disastrous.

##### Communication lines and networks

Networks security attacks can be classified as:

- Passive attacks: they are in the nature of eavesdropping on, or monitoring of, transmissions. The goal of the attacker is to obtain information that is being transmitted. Passive attacks are very difficult to detect because they do not involve any alteration of the data. Typically, the message traffic is sent and received in an apparently normal fashion and neither the sender nor receiver is aware that a third party has read the messages or observer the traffic pattern. So, two types of passive attacks are:
  - the release of message contents;
  - traffic analysis.
- Active attacks: they involve some modification of the data stream or the creation of a false stream and can be subdivided into four categories:
  - Replay: it involves the passive capture of a data unit and its subsequent retransmission to produce an unauthorized effect.
  - Masquerade: it takes place when one entity pretends to be a different entity. A masquerade attack usually includes one of the other forms of active attack.
  - Modification of messages: it simply means that some portion of a legitimate message is altered, or that messages are delayed or reordered, to produce an unauthorized effect.
  - Denial of service: it prevents or inhibits the normal use or management of communication facilities.

### 1.4 Fundamental Security Design Principles

Fundamental security design principles are:

- Economy of mechanism: it means the design of security measures embodied in both hardware and software should be as simple and small as possible. The motivation for this principle is that relatively simple, small design is easier to test and verify thoroughly. Furthermore, because configuration management issues are simplified, updating or replacing a simple mechanism becomes a less intensive process. In practice, this is perhaps the most difficult principle to honor.
- Fail-safe default: it means access decisions should be based on permission rather than exclusion.
- Complete mediation: it means every access must be checked against the access control mechanism. Systems should not rely on access decisions retrieved from a cache.
- Open design: it means the design of a security mechanism should be open rather than secret. For example, although encryption keys must be secret, encryption algorithms should be open to public scrutiny.
- Least privilege: it means every process and every user of the system should operate using the least set of privileges necessary to perform the task. The system security policy can identify and define the various roles of users or processes. Each role is assigned only those permissions needed to perform its functions.
- Least common mechanism: it means the design should minimize the functions shared by different users, providing mutual security.
- Psychological acceptability: it implies the security mechanisms should not interfere unduly with the work of users, and at the same time meet the needs of those who authorize access. If security mechanisms hinder the usability or accessibility of resources, users may opt to turn off those mechanisms.
- Isolation: it's a principle that applies in three contexts:
  - First, public access systems should be isolated from critical resources (data, processes, etc.) to prevent disclosure or tampering.
  - Second, the processes and files of individual users should be isolated from one another except where it is explicitly desired.
  - Finally, security mechanisms should be isolated in the sense of preventing access to those mechanisms.
- Encapsulation: it can be viewed as a specific form of isolation based on object-oriented functionality. Protection is provided by encapsulating a collection of procedures and data objects in a domain of its own so that the internal structure of a data object is accessible only to the procedures of the protected subsystem and the procedures may be called only at designated domain entry points.
- Modularity: in the context of security it refers both to the development of security functions as separate, protected modules, and to the use of a modular architecture for mechanism design and implementation. With respect to the use of separate security modules, the design goal here is to provide common security functions and services, such as cryptographic functions, as common modules.
- Layering: it refers to the use of multiple, overlapping protection approaches addressing the people, technology, and operational aspects of information systems. By using multiple, overlapping protection approaches, the failure or circumvention of any individual protection approach will no leave the system unprotected.
- Least astonishment: it means a program or user interface should always respond in the way that is least likely to astonish the user.

### 1.5 Attack Surfaces and Attack Trees

#### Attack Surfaces

An attack surface consists of the reachable and exploitable vulnerabilities in a system. Attack surfaces can be categorized in the following way:

- Network attack surface: this category refers to vulnerabilities over an enterprise network, wide-area network, or the Internet. Included in this category are network protocol vulnerabilities, such as those user for DoS attack, disruption of communications links, and various forms of intruder attacks.
- Software attack surface: this refers to vulnerabilities in application, utility, or OS code. A particular focus in this category is Web server software.
- Human attack surface: this category refers to vulnerabilities created by personnel or outsiders, such as social engineering, human error, and trusted insiders.

An attack surface analysis is a useful technique for assessing the scale and severity of threats to a system. A systematic analysis of points of vulnerability makes developers and security analysts aware of where security mechanisms are required. Once an attack surface is defined, designers may be able to find ways to make the surface smaller, thus making the task of the adversary more difficult.
The use of layering, or defense in depth, and attack surface reduction complement each other in mitigating security risk.

#### Attack Trees

An attack tree is a branching, hierarchical data structure that represents a set of potential techniques for exploiting security vulnerabilities. The security incident that is the goal of the attack is represented as the root node of the tree, and the ways by which an attacker could reach that goal are iteratively and incrementally represented as branches and subnodes of the tree. Each subnode defines a subgoal, and each subgoal may have its own set of further subgoals, and so on. The final nodes on the paths outward from the root, that is, the leaf nodes, represent different ways to initiate an attack. Each node other than a leaf is either an AND-node or an OR-node. Branches can be labeled with values representing difficulty, cost, or other attack attributes, so that alternative attacks can be compared.  
The motivation for the use of attack trees is to effectively exploit the information available on attack patterns.

The analysis used to generate this tree considered the three components involved in authentication:

- User terminal and user (UT/U): these attacks target the user equipment, including the tokens that may be involved, such as smartcards or other password generators, as well as the actions of the user.
- Communication channel (CC): this type of attack focuses on communication links.
- Internet banking server (IBS): these types of attacks are offline attack against the servers that host the Internet banking application.

Five overall attack strategies can be identified, each of which exploits one or more of the three components:

- User credential compromise: this strategy can be used against many elements of the attack surface. There are procedural attacks (such as monitoring a user's action to observe credentials), token attack tools (brute force or hacking a smartcard), to embed malicious software, sniffing, and various means to engage in communications with the target user.
- Injection of commands: in this type of attack, the attacker is able to intercept communication between the UT and the IBS.
- User credential guessing: brute force attacks against banking authentication schemes. The attack mechanisms is based on distributed zombie personal computers, hosting automated programs for username (or password) based calculation.
- Security policy violation: for example, violating the bank's security policy in combination with weak access control and logging mechanisms, an employee may cause an internal security incident and expose a customer's account.
- Use of known authenticated session: this type of attack persuades or forces the user to connect to the IBS with a preset session ID. Once the user authenticates to the server, the attacker may utilize the known session ID to send packets to the IBS, spoofing the user's identity.

### 1.6 Computer Security Strategy

A comprehensive security strategy involves three aspects:

- Specification/policy: what is the security scheme supposed to do?
- Implementation/mechanisms: how does it do it?
- Correctness/assurance: does it really work?

#### Security Policy

The first step in devising security services and mechanisms is to develop a security policy. At the least, a security policy is an informal description of desired system behaviour. More usefully, a security policy is a formal statement of rules and practices that specify or regulate how a system or organization provides security services to protect sensitive and critical system resources (RFC 4949). Such a formal security policy lends itself to being enforced by the system's technical controls as well as its management and operational controls.  
In developing a security policy, a security manager needs to consider the following factors:

- The value of the assets being protected.
- The vulnerabilities of the system.
- Potential threats and the likelihood of attacks.

Further, the manager must consider the following trade-offs:

- Ease of use versus security: virtually all security measures involve some penalty in the area of ease of use.
- Cost of security versus cost of failure and recovery: in addition to ease of use and performance costs, there are direct monetary costs in implementing and maintaining security measures. All of these costs must be balanced against the cost of security failure and recovery if certain security measures are lacking.

Security policy is thus a business decision, possibly influenced by legal requirements.

#### Security Implementation

Security implementation involves four complementary courses of action:

- Prevention: an ideal security scheme is one in which no attack is successful. Although this is not practical in all cases, there is a wide range of threats in which prevention is a reasonable goal.
- Detection: in a number of cases, absolute protection is not feasible, but it is practical to detect security attacks.
- Response: if security mechanisms detect an ongoing attack, the system may be able to respond in such a way as to halt the attack and prevent further damage.
- Recovery: an example of recovery is the use of backup systems, so if data integrity is compromised, a prior, correct copy of the data can be reloaded.

#### Assurance and Evaluation

Assurance is an attribute of an information system that provides grounds for having confidence that the system operates such that the system's security policy is enforced. This encompasses both system design and system implementation. Assurance is expressed as a degree of confidence, not in terms of a formal proof that a design or implementation is correct. The state of the art in proving designs and implementations is such that it is not possible to provide absolute proof.  

Evaluation is the process of examining a computer product or system with respect to certain criteria. Evaluation involves testing and may also involve formal analytic or mathematical techniques. The central thrust of work in this area is the development of evaluation criteria that can be applied to any security system and that are broadly supported for making product comparisons.

## Chapter 2

### 2.1 Confidentiality with Symmetric Encryption

The universal technique for providing confidentiality for transmitted or stored data is symmetric encryption.

#### Symmetric  Encryption

Symmetric encryption, also referred to as conventional encryption or single-key encryption, was the only type of encryption in use prior to the introduction of public-key encryption in the late 1970s.

A symmetric encryption scheme has five ingredients:

- Plaintext: this is the original message or data that is fed into the algorithm as input.
- Encryption algorithm: the encryption algorithm performs various substitutions and transformations on the plaintext.
- Secret key: the secret key is also input to the encryption algorithm. The exact substitutions and transformations performed by the algorithm depend on the key.
- Ciphertext: this is the scrambled message produced as output. It depends on the plaintext and the secret key.
- Decryption algorithm: this is essentially the encryption algorithm run in reverse. it takes the ciphertext and the secret key and produces the original plaintext.

There are two requirements for secure use of symmetric encryption:

1. The opponent should be unable to decrypt ciphertext or discover the key even if he or she is in possession of a number of ciphertexts together with the plaintext that produced each ciphertext.
2. The sender and receiver must have obtained copies of the secret key in a secure fashion and must keep the key secure.

There are two general approaches to attacking a symmetric encryption scheme.  
The first attack is known as *cryptanalysis*. Cryptanalytic attacks rely on the nature of the algorithm plus perhaps some knowledge of the general characteristics of the plaintext, or even some sample plaintext-ciphertext pairs. This type of attack exploits the characteristics of the algorithm to attempt to deduce a specific plaintext or to deduce the key being used.  
The second method, known as the *brute-force attack*, it to try every possible key on a piece of ciphertext until an intelligible translation into plaintext is obtained.

#### Symmetric Block Encryption Algorithms

The most commonly used symmetric encryption algorithms are block ciphers. A block cipher processes the plaintext input in fixed-size blocks and produces a block of ciphertext of equal size for each plaintext block. The algorithm processes longer plaintext amounts as a series of fixed-size blocks. The most important symmetric algorithms, all of which are block ciphers, are the *Data Encryption Standard* (DES), triple DES, and the *Advanced Encryption Standard* (AES).

##### Data Encryption Standard

Until recently, the most widely used encryption scheme was based on the DES adopted in 1977 by the National Bureau of Standards (now NIST) as FIPS PUB 46.  
DES takes a plaintext block of 64 bits and a key of 56 bits, to produce a ciphertext block of 64 bits.  
Concerns about the strength of DES fall into two categories: concerns about the algorithm itself, and concerns about the use of a 56-bit key.  
The first concern refers to the possibility that cryptanalysis is possible by exploiting the characteristics of the DES algorithm. Despite numerous approaches, no one has so far reported a fatal weakness in DES.  
A more serious concern is key length. With a key length of 56 bits, there are $2^{56}$ possible keys, which is approximately $7.2 * 10^{16}$ keys. Given the speed of commercial off-the-shelf processors, this key length is woefully inadequate. A paper from Seagate Technology suggests that a rate of one billion ($10^9$) key combinations per second is reasonable for today's multicore computers.  
With this results in mind, a single PC can break DES in about a year; if multiple PCs work in parallel, the time is drastically shortened. And today's supercomputers should be able to find a key in about an hour. Key sizes of 128 bits or greater are effectively unbreakable using simply brute-force approach.

##### Triple DES

The life of DES was extended by the use of triple DES (3DES), which involves repeating the basic DES three times, using either two or three unique keys, for a key size of 112 or 168 bits. 3DES was first standardized for use in financial applications in ANSI standard X9.17 in 1985. 3DES was incorporated as part of the DES in 1999, with the publication of FIPS PUB 46-3.  
3DES has two attractions that assure its widespread use over the next few years. First, with its 168-bit key length, it overcomes the vulnerability to brute-force attack of DES. Second, the underlying encryption algorithm in 3DES is the same as in DES. This algorithm has been subjected to more scrutiny than any other encryption algorithm over a longer period of time, and no effective cryptanalytic attack based on the algorithm rather than brute force has been found. Accordingly, there is a high level of confidence that 3DES is very resistant to cryptanalysis.  
The principal drawback of 3DES is that the algorithm is relatively sluggish in software. A secondary drawback is that both DES and 3DES use a 64-bit block size. For reasons of both efficiency and security, a larger block size is desirable.

##### Advanced Encryption Standard

Typically, symmetric encryption is applied to a unit of data larger than a single 64-bit or 128-bit block. Plaintext sources must be broken up into a series of fixed-length block for encryption by a symmetric block cipher. The simplest approach to multiple-block encryption is knows as electronic codebook (ECB) mode, in which plaintext is handled *b* bit at a time and each block of plaintext is encrypted using the same key. Typically $b = 64$ or $b = 128$. A plain text of length $nb$ is divided into *n b*-bit blocks ($P_1,P_2,...,P_n$). Each block is encrypted using the same algorithm and the same encryption key, to produce a sequence of *n b*-bit blocks of ciphertext($C_1,C_2,...,C_n$).  
For lengthy messages, the ECB mode may not be secure. A cryptanalyst may be able to exploit regularities in the plaintext to ease the task of decryption.  
To increse the security of symmetric block encryption for large sequences of data, a number of alternative techniques have been developed, called *modes of operation*.

#### Stream Ciphers

A block cipher processes the input one block of elements at a time, producing an output block for each input block. A *stream cipher* processes the input elements continuously, producing output one element at a time, as it goeas along. Although block ciphers are far more common, there are certain applications in which a stream cipher is more appropriate.  
A typical stream cipher encrypts plaintext one byte at a time, although a stream cipher may be designed to operate on one bit at a time or on units larger than a byte at a time.In the structure of stream cipher, a key is input to a pseudorandom bit generator that produces a stream of 8-bit numbers that are apparently random (a pseudorandom stream is one that is unpredictable without knowledge of the input key and which has an apparently random character). The output of the generator, called a keystream, is combined one byte at a time with the plaintext stream using the bitwise XOR operation.  
With a properly designed pseudorandom number generator, a stream cipher can be as secure as a block cipher of comparable key length. The primary advantage of a stream cipher is that stream cipher are almost always faster and use far less code than do block ciphers. The advantage of a block cipher is that you can reuse keys.

### 2.2 Message Authentication and Hash Functions

Encryption protects against passive attack (eavesdropping). A different requirement is to protect against active attack (falsification of data and transactions). Protection against such attacks is known as message or data authentication.  
Message or data authentication is a procedure that allows communicating parties to verify that received or stored messages are authentic. The two important aspects are to verify that the contents of the message have not been altered and that the source is authentic.

#### Authentication Using Symmetric Encryption

It would seem possible to perform authentication simply by the use of symmetric encryption. In fact, symmetric encryption alone is not a suitable tool for data authentication.  
To give one simple example, in the ECB mode of encryption, if an attacker reorders the blocks of ciphertext, then each block will still decrypt successfully. However, the reordering may alter the meaning of the overall data sequence. Thus, block reordering is a threat.

#### Message Authentication without Message Encryption

An authentication tag is generated and appended to each message for transmission. The message itself is not encrypted and can be read at the destination independent of the authentication function at the destination. Because this approach do not encrypt the message, message confidentiality is not provided.  
Message encryption by itself does not provide a secure form of authentication. However, it is possible to combine authentication and confidentiality in a single algorithm by encrypting a message plus its authentication tag. Typically, however, message authentication is provided as a separate function from message encryption. A paper suggests three situations in which message authentication without confidentiality is preferable:

1. There are a number of applications in which the same message is broadcast to a number of destinations.
2. Another possible scenario is an exchange in which one side has a heavy load and cannot afford the time to decrypt all incoming messages.
3. Authentication of a computer program in plaintext is an attractive service. The computer program can be executed without having to decrypt it every time, which would be wasteful of processor resources. However, if a message authentication tag were attached to the program, it could be checked whenever assurance is required of the integrity of the program.

Thus, there is a place for both authentication and encryption in meeting security requirements.

##### Message Authentication Code

One authentication technique involves the use of a secret key to generate a small block of data, known as a message authentication code, that is appended to the message. This technique assumes that two communicating parties, say A and B, share a common secret key $K_{AB}$. When A has a message to send to B, it calculates the message authentication code as a complex function of the message and the key: $MAC_M = F(K_{AB}, M)^3$. The message plus code are transmitted to the intended recipient. The recipient performs the same calculation on the received message, using the same secret key, to generate a new message authentication code. The received code is compared to the calculated code. If we assume that only the receiver and the sender know the identity of the secret key, and if the received code matches the calculated code, then:

1. The receiver is assured that the message has not been altered.
2. The receiver is assured that the message is from alleged sender.
3. If the message includes a sequence number then the receiver can be assured of the proper sequence.

A number of algorithms could be used to generate the code. AES would now be the most suitable choice. DES or AES is used to generate an encrypted version of the message, and some of the bits of ciphertext are used as the code. A 16 or 32 bit code used to be typical, but would now be much too small to provide sufficient collision resistance.  
The process just described is similar to encryption. One difference is that the authentication algorithm need not be reversible, as it must for decryption. It turns out that because of the mathematical properties of the authentication function, it is less vulnerable to being broken than encryption.

##### One-Way Hash Function

An alternative to the message authentication code is the one-way hash function. As with the message authentication code, a hash function accepts a variable-size message *M* as input and produces a fixed-size message digest $H(M)$ as output. Typically, the message is padded out to an integer multiple of some fixed length (e.g., 1024 bits) and the padding includes the value of the length of the original message in bits.  
Unlike the MAC, a hash function does not take a secret key as input. The message digest can be encrypted using symmetric encryption; if it is assumed that only the sender and receiver share the encryption key, then authenticity is assured.  

The message digest can also be encrypted using public-key encryption. The public-key approach has two advantages: it provides a digital signature as well as message authentication, and it does not require the distribution of keys to communicating parties.  
These two approaches have an advantage over approaches that encrypt the entire message, in that less computation is required. But an even more common approach is the use of a technique that avoids encryption altogether. Several reasons for this interest are in:

- Encryption software is quite slow.
- Encryption hardware costs are non-negligible.
- Encryption hardware is optimized toward large data sizes.
- An encryption algorithm may be protected by a patent.

The technique that uses a hash function but no encryption for message authentication, known as a keyed hash MAC, assumes that two communicating parties, say A and B, share a common secret key *K*. This secret key is incorporated into the process of generating a hash code. When A has a message to send to B, it calculates the hash function over the concatenation of the secret key and the message: $MD_M = H(K||M||K)$. It then sends $[M||MD_M]$ to B. Because B possesses *K*, it can recompute $H(K||M||K)$ and verify $MD_M$. Because the secret key itself is not sent, it should not be possible for an attacker to modify an intercepted message. As long as the secret key remains secret, it should not be possible for an attacker to generate a false message.  
Note the secret key is used as both a prefix and a suffix to the message. If the secret key is used as either only a prefix or only a suffix, the scheme is less secure.

#### Secure Hash Functions

The one-was hash function, or secure hash function, is important not only in message authentication but also in digital signatures.

#### Hash Function Requirements

The purpose of a hash function is to produce a "fingerprint" of a file, message, or other block of data. To be useful for message authentication, a hash function H must have the following properties:

1. H can be applied to a block of data of any size.
2. H produces a fixed-length output.
3. H(x) is relatively easy to compute for any given *x*, making both hardware and software implementations practical.
4. For any given code *h*, it is computationally infeasible to find x such that $H(x) = h$. A hash function with this property is referred to as one-way or preimage resistant.
5. For any given block *x*, it is computationally infeasible to find $y \neq x$ with $H(y) = H(x)$. A hash function with this property is referred to as second preimage resistant. This is sometimes referred to as weak collision resistant.
6. It is computationally infeasible to find any pair $(x,y)$ such that $H(x) = H(y)$. A hash function with this property is referred to as collision resistant. This is sometimes referred to as strong collision resistant.

The fourth property is the one-way property: it is easy to generate a code given a message, but virtually impossible to generate a message given a code. This property is important if the authentication technique involves the use of a secret value.  
The fifth property guarantees that it is impossible to find an alternative message with the same hash value as a given message. This prevents forgery when an encrypted hash code is used.  
A hash function that satisfies the first five properties is referred to as a weak hash function. If the sixth property is also satisfied, then it is referred to as a strong hash function. A strong hash function protects against an attack in which one party generates a message for another party to sign.  
In addition to providing authentication, a message digest also provides data integrity. It performs the same function as a frame check sequence: if any bits in the message are accidentally altered in transit, the message digest will be in error.

##### Security of Hash Functions

As with symmetric encryption, there are two approaches to attacking a secure hash function: cryptanalysis and brute-force attack.  
As with symmetric encryption algorithms, cryptanalysis of a hash function involves exploiting logical weaknesses in the algorithm.  
The strength of a hash function against brute-force attacks depends solely on the length of the hash code produced by the algorithm. For a hash code of length *n*, the level of effort required is proportional to the following:

|Type|Effort required|
|---|---|
| Preimage resistant | $2^n$ |
| Second preimage resistant | $2^n$ |
| Collision resistant | $2^{n/2}$  |

If collision resistance is required (and this is desirable for a general-purpose secure hash code), then the value $2^{n/2}$ determines the strength of the hash code against brute-force attacks.

##### Secure Hash Function ALgorithms

In recent years, the most widely used hash functions has been the Secure Hash Algorithm (SHA). SHA was developed by the NIST and published (FIPS 180) in 1993. When weakness were discovered in SHA, a revised version was issued as FIPS 180-1 in 1995 and is generally referred to as SHA-1. SHA-1 produces a hash value of 160 bits. In 2002, NIST produced a revised version of the standard, FIPS 180-2, that defined three new versions of SHA, with hash value lengths of 256, 384, and 512 bits, known as SHA-256, SHA-384 and SHA-512. These new versions, collectively know as SHA-2, are teh same as SHA-1.  
SHA-2, particularly the 512-bit version, would appear to provide unassailable security. However, because of the structural similarity of SHA-2 to SHA-1, NIST decided to standardize a new hash function that is very different from SHA-2 and SHA-1. This new hash function, known as SHA-3, was published in 2015 and is now available as an alternative to SHA-2.

### 2.3 Public-Key Encryption

Of equal importance to symmetric encryption is public-key encryption, which finds use in message authentication and key distribution.

#### Public-Key Encryption Structure

Public-key encryption was first publicised by Diffie and Hellman in 1976.  
Public-key algorithms are based on mathematica functions rather than on simple operations on bit patterns. More important, public-key cryptography is *asymmetric*, involving the use of two separate keys. The use of two keys ha profound consequences in the areas of confidentiality, key distribution, and authentication.  
There is nothing in principle about either symmetric or public-key encryption that makes one superior to another from the point of view of resisting cryptanalysis. Because of the computational overhead of current public-key encryption schemes, there seems no foreseeable likelihood that symmetric encryption will be abandoned.  
For public-key key distribution, some form of protocol is needed, often involving a central agent, and the procedures involved are no simpler or any more efficient thant those required for symmetric encryption.

A public-key encryption scheme has six ingredients:

- Plaintext.
- Encryption algorithm.
- Public and private key: this is a pair of keys that have been selected so if one is used for encryption, the other is user for decryption. The exact transformations performed by the encryption algorithm depend on the public or private key that is provided as input.
- Ciphertext.
- Decryption algorithm.

The public key of the pair is made public for others to use, while private key is known only to its owner. A general purpose public-key cryptographic algorithm relies on one key for encryption and a different but related key for decryption.  
The essential steps are the following:

1. Each user generates a pair of keys to be used for the encryption and decryption of messages.
2. Each user places one of the two keys in a public register or other accessible file. This is the public key. The companion key is kept private.
3. If Bob wishes to send a private message to Alice, Bob encrypt the message using Alice's public key.
4. When Alice receives the message, she decrypts it using her private key. No other recipient can decrypt the message because only Alice knows Alice's private key.

With this approach, all participants have access to public keys, and private keys are generated locally by each participant and therefore need never be distributed. As long as a user protects his or her private key, incoming communication is secure. This schema is directed toward providing confidentiality. Only the intended recipient should be able to decrypt the ciphertext because only the intended recipient is in possession of the required private key.

Another mode of operation of public-key cryptography is: a user encrypts data using his or her own private key. Anyone who knows the corresponding public key will then be able to decrypt the message. This scheme is directed toward providing authentication and/or data integrity. If a user is able to successfully recover the plaintext from Bob's ciphertext using Bob's public key, this indicates only Bob could have encrypted the plaintext, thus providing authentication.

#### Applications for Public-Key Cryptosystems

In broad terms, we can classify the use of public-key cryptosystems into three categories: digital signature, symmetric key distribution, and encryption of secret keys. Some algorithms are suitable for all three applications, whereas others can be used only for one or two of these application. Following table indicates the applications supported by the algorithms that will be discussed.

| Algorithm | Digital Signature | Symmetric Key Distribution | Encryption of Secret Keys|
| --- | --- | --- | --- |
| RSA | Yes | Yes | Yes |
| Diffie-Hellman | No | Yes | No |
| DSS | Yes | No | No |
| Elliptic Curve | Yes | Yes | Yes |

#### Requirements for Public-Key Cryptography

The cryptosystem discussed depends on a cryptographic algorithm based on two related keys. Diffie and Hellman lay out the conditions that such algorithms must fulfill:

1. It is computationally easy for a party B to generate a pair public/private key $(PU_b, PR_b)$.
2. It is computationally easy for a sender A, knowing the public key and the message to be encrypted, $M$, to generate the corresponding ciphertext:
$$
C = E(PU_b,M)
$$
3. It is computationally easy for the receiver B to decrypt the resulting ciphertext using the private key to recover the original message:
$$
M = D(PR_b,C) = D[PR_b, E(PU_b,M)]
$$
4. It is computationally infeasible for an opponent, knowing the public key, $PU_b$, to determine the private key, $PR_b$.
5. It is computationally infeasible for an opponent, knowing the public key, $PU_b$, and a ciphertext, $C$, to recover the original message, $M$.
6. Either of the two related keys can be used for encryption, with the other used for decryption:
$$
M = D[PU_b, E(PR_b,M)] = D[PR_b, E(PU_b,M)]
$$

#### Asymmetric Encryption ALgorithms

##### RSA

The RSA scheme has since reigned supreme as the most widely accepted and implemented approach to public-key encryption. RSA is a block cipher in which the plaintext and ciphertext are integers between $0$ and $n-1$ for some $n$. Currently, a 1024-bit key size (about 300 decimal digits) is considered strong enough for virtually all applications.

##### Diffie-Hellman Key Agreement

The purpose of the algorithm is to enable two users to securely reach agreement about a shared secret that can be used as a secret key for subsequent symmetric encryption of messages. The algorithm itself is limited to the exchange of the keys.

##### Digital Signature Standard

The DSS makes use of SHA-1 and presents a new digital signature technique, the Digital Signature ALgorithm (DSA). The Digital Signature Standard (DSS) was originally proposed in 1991 and revised in 1993 in response to public feedback concerning the security of the scheme. There were further revisions in 1998, 2000, 2009, and most recently in 2013. The DSS uses an algorithm that is designed to provide only the digital signature function. Unlike RSA, it cannot be used for encryption or key exchange.

##### Elliptic Curve Cryptography

Recently, a competing system has begun to challenge RSA: elliptic curve cryptography (ECC). The principal attraction of ECC compared to RSA is that it appears to offer equal security for a far smaller bit size, thereby reducing processing overhead. On the other hand, although the theory of ECC has been around for some time, it is only recently that products have begun to appear and that there has been sustained cryptanalytic interest in probing for weaknesses. Thus, the confidence level in ECC is not yet as high as that in RSA.

### 2.4 Digital Signatures and Key Management

With respect to key management and distribution, there are at least three distinct aspects to the use of public-key encryption in this regard:

- The secure distribution of public keys.
- The use of public-key encryption to distribute secret keys.
- The use of public-key encryption to create temporary keys for message encryption.

#### Digital Signature

Public-key encryption can be used for authentication with a technique known as the digital signature. NIST FIPS PUB 186-4 defines a digital signature as follows: the result of a cryptographic transformation of data that, when properly implemented, provides a mechanism for verifying origin authentication, data integrity and signatory non-repudiation.  
Thus, a digital signature is a data-dependent bit pattern, generated by an agent as a function of a file, message, or other form of data block. Another agent can access the data block and its associated signature and verify:

1. the data block has been signed by the alleged signer;
2. the data block has not been altered since the signing.

FIPS 186-4 specifies the use of one of three digital signature algorithms:

- Digital Signature Algorithm (DSA): the original NIST-approved algorithm, which is based on the difficulty of computing discrete logarithms.
- RSA Digital Signature Algorithm: based on the RSA public-key algorithm.
- Elliptic Curve Digital Signature Algorithm (ECDSA): based on elliptic-curve cryptography.

The digital signature does not provide confidentiality. That is, the message being sent is safe from alteration, but not safe from eavesdropping. This is obvious in the case of a signature based on a portion of the message, because the rest of the message is transmitted in the clear. Even in the case of complete encryption, there is no protection of confidentiality because any observer can decrypt the message by using the sender's public key.

#### Public-Key Certificates

On the face of it, the point of public-key encryption is that the public key is public. Thus, if there is some broadly accepted public-key algorithm, such as RSA, any participant can send his or her public key to any other participant or broadcast the key to the community at large. Although this approach is convenient, it has a major weakness. Anyone can forge such a public announcement. That is, some user could pretend to be Bob and send a public key to another participant or broadcast such a public key. Until such time as Bob discovers the forgery and alerts other participants, the forger is able to read all encrypted messages intended for Bob and can use the forged keys for authentication.  
The solution to this problem is the public-key certificate. In essence, a certificate consists of a public key plus a user ID of the key owner, with the whole block signed by a trusted third party. The certificate also includes some information about the third party plus an indication of the period of validity of the certificate. Typically, the third party is a certificate authority (CA) that is trusted by the user community, such as a government agency or a financial institution. A user can present his or her public key to the authority in a secure manner and obtain a signed certificate. The user can then publish the certificate. Anyone needing this user's public key can obtain the certificate and verify that it is valid by means of the attached trusted signature.

One scheme has become universally accepted for formatting public-key certificates: the X.509 standard. It is used in IPsec, TLS, SSH, S/MIME and others.

#### Symmetric Key Exchange Using Public-Key Encryption

With symmetric encryption, a fundamental requirement for two parties to communicate securely is that they share a secret key. Suppose Bob wants to create a messaging application that will enable him to exchange e-mail securely with anyone who has access to the Internet. Suppose Bob wants to do this using symmetric encryption. With symmetric encryption, Bob and his correspondent, say, Alice, must come up with a way to share a unique secret key that no one else knows. How are they going to do that?  
One approach is the use of Diffie-Hellman key exchange. This approach is indeed widely used. However, it suffers the drawback that, in its simplest form, Diffie-Hellman provides no authentication of the two communicating partners. There are variations to Diffie-Hellman that overcome this problem. In addition, there are protocols using other public-key algorithms that achieve the same objective.

#### Digital Envelopes

Another application in which public-key encryption is used to protect a symmetric key is the digital envelope, which can be used to protect a message without needing to first arrange for sender and receiver to have the same secret key. The technique is referred to as a digital envelope, which is the equivalent of a sealed envelope containing an unsigned letter.  
Suppose Bob wishes to send a confidential message to Alice, but they do not share a symmetric secret key. Bob does the following:

1. Prepare a message.
2. Generate a random symmetric key that will be used this one time only.
3. Encrypt that message using symmetric encryption the one-time key.
4. Encrypt the one-time key using public-key encryption with Alice's public key.
5. Attach the encrypted one-time key to the encrypted message and sent it to Alice.

Only Alice is capable of decrypting the one-time key and therefore of recovering the original message. If Bob obtained Alice's public key by means of Alice's public-key certificate, then Bob is assured that it is a valid key.

### 2.5 Random and Pseudorandom Numbers

Random numbers play an important role in the use of encryption for various network security applications.

#### The Use of Random Numbers

A number of network security algorithms based on cryptography make use of random numbers. These applications give rise to two distinct and not necessarily compatible requirements for a sequence of random numbers: randomness and unpredictability.

##### Randomness

Traditionally, the concern in the generation of a sequence of allegedly random numbers has been that the sequence of numbers be random in some well-defined statistical sense. The following two criteria are used to validate that a sequence of numbers is random:

- Uniform distribution: the distribution of numbers in the sequence should be uniform.
- Independence: none one value in the sequence can be inferred from the others.

Although there are well-defined tests for determining that a sequence of numbers matches a particular distribution, there is no such test to "prove" independence. Rather, a number of tests can be applied to demonstrate if a sequence does not exhibit independence. The general strategy is to apply a number of such tests until the confidence that independence exists is sufficiently strong.  
The use of a sequence of numbers that appear statistically random often occurs in the design of algorithms related to cryptography.  
In essence, if a problem is too hard or time-consuming to solve exactly, a simpler, shorter approach based on randomization is used to provide an answer with any desired level of confidence.

##### Unpredictability

In applications such as reciprocal authentication and sessions key generation, the requirement is not so much that the sequence of numbers be statistically random, but that the successive members of the sequence are unpredictable. With "true" random sequences, each number is statistically independent of other numbers in the sequence and therefore unpredictable. However, true random numbers are not always used; rather, sequences of numbers that appear to be random are generated by some algorithm. In this latter case, care must be taken that an opponent is not able to predict future elements of the sequence on the basis of earlier elements.

#### Random versus Pseudorandom

Cryptographic applications typically make use of algorithmic techniques for random number generation. These algorithms are deterministic and therefore produce sequences of numbers that are not statistically random. However, if the algorithm is good, the resulting sequences will pass many reasonable tests of randomness. Such numbers are referred to as pseudorandom numbers.  
Under most circumstances, pseudorandom numbers will perform as well as if they were random for a given use. The phrase "as well as" is unfortunately subjective, but the use of pseudorandom numbers is widely accepted. A true random number generator (TRNG) uses a nondeterministic source to produce randomness.

## Chapter 3

User authentication is the basis for most types of access control and for user accountability. User authentication encompasses two functions. First, the user identifies herself to the system by presenting a credential. Second, the system verifies the user by the exchange of authentication information.

### 3.1 Digital User Authentication Principles

NIST SP 800-63-3 defines digital user authentication as the process of establishing confidence in user identifies that are presented electronically to an information system. Systems can use the authenticated identity to determine if the authenticated individual is authorized to perform particular functions. In many cases, the authentication and transaction, or other authorized function, take place across an open network such as the Internet.

#### Means of Authentication

There are four general means of authenticating a user's identity, which can be used alone or in combination:

- Something the individual knows.
- Something the individual possess: this type of authenticator is referred to as a token.
- Something the individual is (static biometrics).
- Something the individual does (dynamic biometrics): recognition by voice pattern, handwriting, etc.

All of these methods, properly implemented and used, can provide secure user authentication. However, each method has problems.

Multifactor authentication refers to the use of more than one of the authentications means in the preceding list. The strength of authentication systems is largely determined by the number of factors incorporated by the system.

### 3.2 Password-Based Authentication

A widely used line of defense against intruders is the password system.

#### The Vulnerability of Passwords

Typically, a system that uses password-based authentication maintains a password file indexed by user ID. One technique that is typically used is to store not the user's password but a one-was hash function of the password. We can identify the following attack strategies and countermeasures:

- Offline dictionary attack: the attacker obtains the system password file and compares the password hashes against hashes of commonly used password. If a match is found, the attacker can gain access by that ID/password combination. Countermeasures include controls to prevent unauthorized access to the password file, intrusion detection measures to identify a compromise, and rapid reissuance of passwords should the password file be compromised.
- Specific account attack: the attacker targets a specific account and submits password guesses until the correct password is discovered. The standard countermeasure is an account lockout mechanism.
- Popular password attack: a variation of the preceding attack is to use a popular password and try it against a wide range of user IDs. Countermeasures include policies to inhibit the selection by users of common passwords and scanning the IP addresses of authentication requests and client cookies for submission patterns.
- Password guessing against single user: the attacker attempts to gain knowledge about the account holder and system password policies and uses that knowledge to guess the password. Countermeasures include training in and enforcement of password policies that make passwords difficult to guess.
- Workstation hijacking: the attacker waits until a logged-in workstation is unattended. The standard countermeasure is automatically logging the workstation out after a period of inactivity. Intrusion detection schemes can be used to detect changes in user behaviour.
- Exploiting user mistakes: if the system assigns a password, then the user is more likely to write it down because it is difficult to remember. This situation creates the potential for an adversary to read the written password. Unless these preconfigured passwords are changed, they are easily guessed. Countermeasures include user training, intrusion detection, and simpler passwords combined with another authentication mechanism.
- Exploiting multiple password use: attacks can also become much more effective or damaging if different network devices share the same or a similar password for a given user. Countermeasures include a policy that forbids the same or similar password on particular network devices.
- Electronic monitoring: if a password is communicated across a network to log on to a remote system, it is vulnerable to eavesdropping. Simple encryption will not fix this problem, because the encrypted password is, in effect, the password and can be observer and reused by an adversary.

Despite the many security vulnerabilities of passwords, they remain the most commonly used user authentication technique. Among the reasons for the persistent popularity of passwords are the following:

1. Techniques that utilize client-side hardware require the implementation of the appropriate user authentication software to exploit this hardware on both the client and server systems.
2. Physical tokens are expensive and/or inconvenient to carry around.
3. Schemes that rely on a single sign-on to multiple services create a single point of security risk.
4. Automated password managers that relieve users of the burden of knowing and entering passwords have poor support for roaming and synchronization across multiple client platforms, and their usability had not be adequately researched.

#### The use of Hashed Passwords

A widely used password security technique is the use of hashed passwords and a salt value. To load a new password into the system, the user selects or is assigned a password. This password is combined with a fixed-length salt value.  
The password and salt serve as inputs to a hashing algorithm to produce a fixed-length hash code. The hash algorithm is designed to be slow to execute in order to thwart attacks. The hashed password is then stored, together with a plaintext copy of the salt, in the password file for the corresponding user ID.

When a user attempts to log on to a UNIX system, the user provides an ID and a password. The operating system uses the ID to index into the password file and retrieve the plaintext salt and the encrypted password. The salt and user-supplied password are used as input to the encryption routine. If the result matches the stored value, the password is accepted.  
The salt serves three purposes:

- It prevents duplicate passwords from being visible in the password file.
- It greatly increases the difficulty of offline dictionary attacks. For a salt of length $b$ bits, the number of possible passwords is increased by a factor of $2^b$, increasing the difficulty of guessing a password in a dictionary attack.
- It becomes nearly impossible to find out whether a person with passwords on two or more systems has used the same password on all of them.

##### UNIX Implementations

The recommended hash function for many UNIX systems, including Linux, Solaris and FreeBSD, is based on the MD5 secure hash algorithm. The MD5 crypt routine uses a salt of up to 48 bits and effectively has no limitations on password length. It produces a 128-bit hash value. It is also far slower than crypt(3) (the hash routine based on DES). To achieve the slowdown, MD5 crypt uses an inner loop with 1000 iterations.  
Probably the most secure version of the UNIX hash/salt scheme was developed for OpenBSD, another widely used open source UNIX. This scheme uses a hash function based on the Blowfish symmetric block cipher. The hash function, called Bcrypt, is quite slow to execute. Bcrypt allows password of up to 55 characters in length and requires a random salt value of 128 bits, to produce a 192-bit hash value. Bcrypt also includes a cost variable; an increase in the cost variable causes a corresponding increase in the time required to perform a Bcrypt hash. The cost assigned to a new password is configurable, so administrators can assign a higher cost to privileged users.

#### Password Cracking of User-Chosen Passwords

##### Traditional Approaches

The traditional approach to password guessing is to develop a large dictionary of possible passwords and to try each of these against the password file. This means that each password must be hashed using each available salt value then compared with stored hash values. If no match is found, the cracking program tries variations on all the words in its dictionary of likely passwords.

An alternative is to trade off space for time by precomputing potential hash values. For each password, the attacker generates the has values associated with each possible salt value. The result is a mammoth table of hash values known as a rainbow table. This approach can be countered using a sufficiently large salt value and a sufficiently large hash length.

A particular problem is that users, when permitted to choose their own password, tend to choose short ones. The analysis of the 70 million passwords estimates that passwords provide fewer than 10 bits of security against an online, trawling attack, and only about 20 bits of security against an optimal offline dictionary attack. It can be seen then that using offline search enables an adversary to break a large number of accounts, even if a significant amount of iterated hashing is used.

Password length is only part of the problem. Many people, when permitted to choose their own password, pick a password that is guessable. This makes the job of password cracking straightforward. The cracker simply has to test the password file against lists of likely passwords.

Attacks that use a combination of brute-force and dictionary techniques have become common. A notable example of this dual approach is John the Ripper, an open-source password cracker first developed in 1996 and still in use.

##### Modern Approaches

Sadly, this type of vulnerability has not lessened in the past. However, password-cracking techniques have improved to keep pace. The improvements are of two kinds.  
First, the processing capacity available for password cracking as increased dramatically.  
The second area of improvement in password cracking is in the use of sophisticated algorithms to generate potential password.  
But the best results have been achieved by studying examples of actual passwords in use. To develop techniques that are more efficient and effective than simple dictionary and brute-force attacks, researchers and hackers have studied the structure of passwords.  
Using large dataset of leaked passwords as training data, a paper reports on the development of a probabilistic context-free grammar for password cracking. In this approach, guesses are ordered according to their likelihood, based on the frequency of their character-class structures in the training data, as well as the frequency of their digit and symbol substrings. This approach has been shown to be efficient in password cracking.

#### Password File Access Control

One way to thwart a password attack is to deny the opponent access to the password file. If the hashed password portion of the file is accessible only by a privileged user, then the opponent cannot read it without already knowing the password of a privileged user. Often, the hashed passwords are kept in a separate file from the user IDs, referred to as a shadow password file. Special attention is paid to making the shadow password file protected from unauthorized access. Although password file protection is certainly worthwhile, there remain vulnerabilities:

- Many systems are susceptible to unanticipated break-ins. A hacker may be able to exploit a software vulnerability in the operating system to bypass the access control system long enough to extract the password file.
- An accident of protection might render the password file readable.
- Some of the users have accounts on other machines in other protection domains, and they use the same password.
- A weakness in physical security may provide opportunities for a hacker. Sometimes, there is a backup to the password file on an emergency repair disk or archival disk. Access to this backup enables the attacker to read the password file.
- Instead of capturing the system password file, another approach to collecting user IDs and passwords is through sniffing network traffic.

Thus, a password protection policy must complement access control measures with techniques to force users to select passwords that are difficult to guess.

#### Password Selection Strategies

Our goal is to eliminate guessable passwords while allowing the user to select a password that is memorable. Four basic techniques are in use:

- User education: this strategy is unlikely to succeed at most installations, particularly where there is a large user population or a lot of turnover. Perhaps a good technique for choosing a password is to use the first letter of each word of a phrase.
- Computer-generated passwords: it also have problems. In general, computer-generated password schemes have a history of poor acceptance by users.
- Reactive password checking: it is a strategy in which the system periodically runs its own password cracker to find guessable passwords. The system cancels any passwords that are guessed and notifies the user. This tactic has a number of drawbacks. First, it is resource intensive if the job is done right. Furthermore, any existing password remain vulnerable until the checker finds them.
- Complex password policy (or proactive password checker): it is a promising approach for improved password security. In this scheme, a user is allowed to select his or her own password. However, at the time of selection, the system checks to see if the password is allowable and, if not, rejects it. The trick with a proactive password checker is to strike a balance between user acceptability and strength. If the system uses some simple algorithm to define what is acceptable, this provides guidance to password crackers to refine their guessing technique.

##### Rule Enforcement

The first approach is a simple system for rule enforcement. NIST SP 800-63-2 suggests the following alternative rules:

- Password must have at least sixteen characters (basic16).
- Password must have at least eight characters including an uppercase and lowercase letter, a symbol, and a digit. It may not contain a dictionary word (comprehensive8).

Although this approach is superior to simply educating users, it may not be sufficient to thwart password crackers. This scheme alerts cracker as to which password not to try, but may still make it possible to do password cracking.  
The process of rule enforcement can be automated by using a proactive password checker, such as the openware pam_passwdqc, which enforces a variety of rules on passwords and is configurable by the system administrator.

##### Password Checker

Another possible procedure is simply to compile a large dictionary of possible "bad" passwords. When a user selects a password, the system checks to make sure that it is not on the disapproved list. There are two problems with this approach:

- Space: the dictionary must be very large to be effective.
- Time: the time required to search a large dictionary may itself be large.

### 3.3 Token-Based Authentication

Objects that a user possesses for the purpose of user authentication are called tokens.

#### Memory Cards

Memory cards can store but not process data. There are also memory cards that include an internal electronic memory.  
Memory cards can be used alone for physical access, such as a hotel room. For authentication, a user provides both the memory card and some form of password or PIN. A typical application is an ATM. An adversary must gain physical possession of the card (or be able to duplicate it) plus must gain knowledge of the PIN. Among the potential drawbacks NIST SP 800-12 notes the following:

- Requires special reader: this increases the cost of using the token and creates the requirement to maintain the security of the reader's hardware and software.
- Token loss: a lost token temporarily prevents its owner from gaining system access. Thus, there is an administrative cost in replacing the lost token. In addition, if the token is found, stolen, or forged, then an adversary need only determine the PIN to gain unauthorized access.
- User dissatisfaction: although users may have no difficulty in accepting the use of a memory card for ATM access, its use for computer access may be deemed inconvenient.

#### Smart Cards

A wide variety of devices qualify as smart tokens. These can be categorized along four dimensions that are not mutually exclusive:

- Physical characteristics: smart tokens include an embedded microprocessor.
- User interface: manual interfaces include a keypad and display for human/token interaction.
- Electronic interface: a smart card or other token requires an electronic interface to communicate with a compatible reader/writer. A card may have one or both of the following types of interface:
  - Contact: a contact smart card must be inserted into a smart card reader with a direct connection to a conductive contact plate on the surface of the card (typically gold plated).
  - Contactless: a contactless card requires requires only close proximity to a reader. Both the reader and the card have an antenna, and the two communicate using radio frequencies.
- Authentication protocol: the purpose of a smart token is to provide a means for user authentication. We can classify the authentication protocols used with smart tokens into three categories:
  - Static: with a static protocol, the user authenticates himself or herself to the token then the token authenticates the user to the computer.
  - Dynamic password generator: in this case, the token generates a unique password periodically. This password is then entered into the computer system for authentication, either manually by the user or electronically via the token.
  - Challenge-response: in this case, the computer system generates a challenge, such as a random string of numbers. The smart token generate a response based on the challenge.

For user authentication, the most important category of smart token is the smart card, which has the appearance of a credit card, has an electronic interface, and may use any of the type of protocols just described.  
A smart card contains within it an entire microprocessor, including processor, memory, and I/O ports. Some versions incorporate a special co-processing circuit for cryptographic operation to speed the task of encoding and decoding messages or generating digital signatures to validate the information transferred.  
A typical smart card includes three types of memory:

- Read-only memory (ROM), which stores data that does not change during the card's life, such as the card number and the cardholder's name.
- Electrically erasable programmable ROM (EEPROM), which holds application data and programs, such as the protocols that the card can execute. It also holds data that may vary with time.
- Random access memory (RAM), which holds temporary data generated when applications are executed.

Each time the card is inserted into a reader, a reset is initiated by the reader to initialize parameters such as clock value. After the reset function is performed, the card responds with answer to reset (ATR) message. This message defines the parameters and protocols that the card can use and the functions it can perform. The terminal may be able to change the protocol used and other parameters via a protocol type selection (PTS) command. The card's PTS response confirms the protocols and parameters to be used. The terminal and card can now execute the protocol to perform the desired application.

### 3.4 Biometric Authentication

A biometric authentication system attempts to authenticate an individual based on his or her unique physical characteristics. These include static and dynamic characteristics. In essence, biometrics is based on pattern recognition. Compared to password and tokens, biometric authentication is both technically more complex and expensive.

#### Physical Characteristics Used in Biometric Applications

A number of different types of physical characteristics are either in use or under study for user authentication. The most common are the following:

- Facial characteristics: they are the most common. The most common approach is to define characteristics based on relative location and shape of key facial features. An alternative approach is to use an infrared camera to produce a face thermogram that correlates with the underlying vascular system in the human face.
- Fingerprints: they have been used as a mean of identification for centuries, and the process has been systematized and automated particularly for law enforcement purposes. Fingerprints are believed to be unique across the entire human population. In practice, automated fingerprint recognition and matching system extract a number of features from the fingerprint for storage as a numerical surrogate for the full fingerprint pattern.
- Hand geometry: it identify features of the hand, including shape, and length and widths of fingers.
- Retinal pattern: it is the pattern formed by veins beneath the retinal surface. It is unique and therefore suitable for identification.
- Iris: the detailed structure of the iris.
- Signature: each individual has a unique style of handwriting and this is reflected especially in the signature.
- Voice: voice patterns are more closely tied to the physical and anatomical characteristics of the speaker. Nevertheless, there is still a variation from sample to sample over time from the same speaker, complicating the biometric recognition task.

#### Operation of a Biometric Authentication System

Each individual who is to be included in the database of authorized users must first be enrolled in the system. For a biometric system, the user presents a name and, typically, some type of password or PIN to the system. At the same time, the system senses some biometric characteristic of this user. The system digitizes the input then extracts a set of features that can be stored as a number or set of numbers representing this unique biometric characteristic; this set of numbers is referred to as the user's template. The user is now enrolled in the system, which maintains for the user a name (ID), perhaps a PIN or password, and the biometric value.  
Depending on application, user authentication on a biometric system involves either verification or identification. Verification is analogous to a user logging on to a system by using a memory card or smart card coupled with a password or PIN. For biometric verification, the user enters a PIN and also uses a biometric sensor. The system extracts the corresponding feature and compares that to the template stored for this user. If there is a match, then the system authenticates this user.  
For an identification system, the individual uses the biometric sensor but presents no additional information. The system then compares the presented template with the set of stored templates. If there is a match, then this user is identified.

### 3.5 Remote User Authentication

The simplest form of user authentication is local authentication. The more complex case is that of remote user authentication, which takes place over the Internet, a network, or a communications link. Remote user authentication raises additional security threats, such as an eavesdropper being able to capture a password, or an adversary replaying an authentication sequence that has been observed.  
To counter threats to remote user authentication, systems generally rely on some form of challenge-response protocol.

#### Password Protocol

For example, a user first transmits his or her identity to the remote host. The host generates a random number $r$, often called a *nonce*, and returns this nonce to the user. In addition, the host specifies two function, $h()$ and $f()$, to be used in the response. This transmission from host to user is the challenge. The user's response is the quantity $f(r',h(P'))$, where $r' = r$ and $P'$ is the user's password. The function $h$ is a hash function, so the response consists of the hash function of the user's password combined with the random number using the function $f$.  
The host stores the has function of each registered user's password, depicted as $h(P(U))$ for user $U$. When the response arrives, the host compares the incoming $f(r', h(P'))$ to the calculated $f(r, h(P(U)))$. If the quantities match, the user is authenticated.  
This scheme defends against several forms of attack. The host stores not the password but a hash code of the password. This secures the password from intruders into the host system. In addition, not even the hash of the password is transmitted directly, but rather a function in which the password hash is one of the arguments. Thus, for a suitable function $f$, the password hash cannot be captured during transmission. Finally, the use of a random number as one of the arguments of $f$ defends against a replay attack, in which an adversary captures the user's transmission and attempts to log on to a system by retransmitting the user's messages.

### 3.6 Security Issues for User Authentication

As with any security service, user authentication, particularly remote user authentication, is subject to a variety of attacks. The following list summarizes the principal attacks on user authentication:

- Client attack:
  - Description: those in which an adversary attempts to achieve user authentication withouts access to the remote host or to the intervening communications path. The adversary attempts to masquerade as a legitimate user. One way to thwart such an attack is to select a password that is both lengthy and unpredictable (large entropy).
  - Authenticators:
    - Password examples: guessing, exhaustive search
      - Typical defenses: large entropy, limited attempts
    - Token examples: exhaustive search
      - Typical defenses: large entropy, limited attempts, theft of object requires presence
    - Biometric examples: false match
      - Typical defenses: large entropy, limited attempts
- Host attack:
  - Description: host attacks are directed at the user file at the host where passwords, token passcodes, or biometric templates are stored.
  - Authenticators:
    - Password examples: plaintext theft, dictionary/exhaustive search
      - Typical defenses: hashing, large entropy, protection of password database
    - Token examples: passcode theft
      - Typical defenses: large entropy, limited attempts, theft of object requires presence, 1-time passcode
    - Biometric examples: template theft
      - Typical defenses: capture device authentication, challenge response
- Eavesdropping, theft and copying attack:
  - Description: eavesdropping in the context of passwords refers to an adversary's attempt to learn the password by observing the user, finding a written copy of the password, or some similar attack that involves the physical proximity of user and adversary. Another form of eavesdropping is keystroke logging (keylogging). For a token, an analogous threat is theft of the token or physical copying of the token. The analogous threat for a biometric protocol is copying or imitating the biometric parameter so as to generate the desired template.
  - Authenticators:
    - Password examples: "shoulder surfing"
      - Typical defenses: user diligence to keep secret, administrator diligence to quickly revoke compromised passwords, multifactor authentication
    - Token examples: theft, counterfeiting hardware
      - Typical defenses: multifactor authentication, tamper resistant/evident token
    - Biometric examples: copying (spoofing) biometric
      - Typical defenses: copy detection at capture device and capture device authentication
- Replay attack:
  - Description: it involves an adversary repeating a previously captured user response.
  - Authenticators:
    - Password examples: replay stolen password response
      - Typical defenses: challenge-response protocol
    - Token examples: replay stolen password response
      - Typical defenses: challenge-response protocol, 1-time passcode
    - Biometric examples: replay stolen biometric template response
      - Typical defenses: copy detection at capture device and capture device authentication via challenge-response protocol
- Trojan horse attack:
  - Description: an application or physical device masquerades as an authentic application or device for the purpose of capturing a user password, passcode, or biometric. The adversary can then use the captured information to masquerade as a legitimate user.
  - Authenticators:
    - Password, token, biometric examples: installation of rogue client or capture device
      - Typical defenses: authentication of client or capture device within trusted security perimeter
- DoS attack:
  - Description: it attempts to disable a user authentication service by flooding the service with numerous authentication attempts.
  - Authenticators:
    - Password, token, biometric examples: lockout by multiple failed authentication
      - Typical defenses: multifactor with token

## Chapter 4

Two definitions of access control are useful:

- NISTIR 7298 defines access control as the process of granting or denying specific request to:
  1. obtain and use information and related information processing servers
  2. enter specific physical facilities.
- RFC 4949 defines access control as a process by which use of system resources is regulated according to a security policy and is permitted only bu authorized entities according to that policy.

### 4.1 Access Control Principles

In a broad sense, all of computer security is concerned with access control.  
Indeed, RFC 4949 defines computer security as follows: measures that implement and assure security services in a computer system, particularly those that assure access control service.

#### Access Control Context

In addition to access control, this context involves the following entities and functions:

- Authentication: verification that the credentials of a user or other system entity are valid.
- Authorization: the granting of a right or permission to a system entity to access a system resource.
- Audit: an independent review and examination of system records and activities in order to test for adequacy of system controls, to ensure compliance with established policy and operational procedures, to detect breaches in security, and to recommend any indicated changes in control, policy, and procedures.

An access control mechanism mediates between a user and system resources. The system must first authenticate an entity seeking access. Then the access control function determines if the specific requested access by this user is permitted. An auditing function monitors and keeps a record of user accesses to system resources.  
A number of components may cooperatively share the access control function.

#### Access Control Policies

An access control policy dictates what types of access are permitted, under what circumstances, and by whom. Access control policies are generally grouped into the following categories:

- Discretionary access control (DAC): controls access based on the identity of the requestor and on access rules stating what requestors are allowed to do.
- Mandatory access control (MAC): controls access based on comparing security labels with security clearances.
- Role-based access control (RBAC): controls access based on the roles that users have within the system and on rules stating what accesses are allowed to users in given roles.
- Attribute-based access control (ABAC): controls access based on attributes of the user, the resource to be accessed, and current environmental conditions.

DAC is the traditional method of implementing access control. MAC is a concept that evolved out of requirement for military information security and is best covered in the context of trusted system. Both RBAC and ABCAC have become increasingly popular.  
These four policies are not mutually exclusive. An access control mechanism can employ two or even all three of these policies to cover different classes of system resource.

### 4.2 Subject, Objects, and Access Rights

The basic elements of access control are:

- Subject: a subject is an entity capable of accessing objects. Generally, the concept o subject equates with that of process. Basic access control system typically define three classes of subject, with different access rights for each class:
  - Owner: this may be the creator of a resource, such as a file.
  - Group: a named group of users may also be granted access rights. In most schemes, a user may belong to multiple groups.
  - World: users who are not included in the categories owner and group.
- An object is a resource to which access is controlled. In general, an object is an entity used to contain and/or receive information. The number and types of objects to be protect by an access control system depends on the environment in which access control operates and the desired tradeoff between security and complexity, processing burden and ease of use.
- An access right describes the way in which a subject may access an object. Access rights could include the following:
  - Read;
  - Write;
  - Execute;
  - Delete;
  - Create;
  - Search.

### 4.3 Discretionary Access Control

A discretionary access control scheme is one in which an entity may be granted access rights that permit the entity, by its own volition, to enable another entity to access some resource. A general approach to DAC is that of an access matrix. The access matrix concept was formulated by Lampson and refined by Graham and Denning and by Harrison et al..  
One dimension of the matrix consists of identified subject that may attempt data access to the resources. The other dimension lists the objects that may be accessed. Each entry in the matrix indicates the access rights of a particular subject for a particular object.

In practice, an access matrix is usually sparse and is implemented by decomposition in one of two ways.

The matrix may be decomposed by columns, yielding access control lists (ACLs). For each object, an ACL list users and their permitted access rights. The ACL may contain a default, or public, entry. This allows users that are not explicitly listed as having special rights to have a default set of rights. The default set of rights should always follow the rule of least privilege or read-only access, whichever is applicable. ACLs are convenient, because each ACL provides the information for a given resource.

Decomposition by rows yields capability tickets. A capability ticket specifies authorized objects and operations for a particular user. Each user has a number of tickets and may be authorized to loan or give them to others. Because tickets may be dispersed around the system, they present a greater security problem than access control lists. The integrity of the ticket must be protected, and guaranteed. In particular, the ticket must be unforgeable. These tickets would have to be held in a region of memory inaccessible to users. Another alternative is to include an unforgeable token in the capability.  
This form of capability ticket is appropriate for use in a distributed environment, when the security of its contents cannot be guaranteed. The convenient aspects of capability tickets are that it is easy to determine the set of access rights that a given user has.

A paper proposes a data structure that is not sparse, like the access matrix, but is more convenient than either ACLs or capability lists. An authorization table contains one row for one access right of one subject to one resource.

### 4.4 Example: Unix File Access Control

All types of UNIX files are administered by the operating system by means of inodes. An inode (index node) is a control structure that contains the key information needed by the operating system for a particular file. Several file names may be associated with a single inode, but an active inode is associated with exactly one file, and each file is controlled by exactly one inode.  
Directories are structured in a hierarchical tree. A directory is simply a file that contains a list of file name plus pointers to associated inodes. Thus, associated with each directory is its own inode.

#### Traditional UNIX File Access Control

Most UNIX systems depend on the file access control scheme introduced with the early version of UNIX. Each UNIX user is assigned a unique user ID. A user is also a member of a primary group, and possibly a number of other groups, each identified by a group ID. When a file is created, it is designated as owned by a particular user. It also belongs to a specific group, which initially is either its creator's primary group, or the group of its parent directory.  
Associated with each file is a set of 12 protection bits. The owner ID, group ID, and protection bits are part of the file's inode. Nine of the protection bits specify read, write, and execute permission for the owner of the file, other members of the group to which this file belongs, and all other users. These form a hierarchy of owner, group, and all others, with the highest relevant set of permissions being used.  
When applied to a directory, the read and write bits grant the right to list and to create/rename/delete files in the directory. The execute bit grants the right to descend into the directory or search it for a filename.  
The remaining three bits define special additional behaviour for files or directories. Two of these are SetUID and SetGID permissions. If those permission are set, it happens that when a user (with execute privileges for this file) executes the file, the system temporarily allocates the rights of the user's ID of the file creator, or the file's group, respectively, to those of the user executing the file. These are known as the "effective user ID" and "effective group ID" and are used in addition to the "real user ID" and "real group ID" of the executing user when making access control decisions for this program. This change is only effective while the program is being executed. It enables users to access certain files in a controlled fashion.  
The final permission bit is the "sticky" bit. When applied to a directory it specifies that only the owner of any file in the directory can rename, move, or delete that file. This is useful for managing files in shared temporary directories.  
One particular user ID is designated as "superuser". The superuser is exempt from the usual file access control constraints and has system-wide access. Great care is needed when writing such programs.

This access scheme is adequate when file access requirements align with users and a modest number of groups of users. If there are a large number of different grouping of users requiring a range of access rights to different files, then a very large number of groups may be needed to provide this. This rapidly become unwieldy and difficult to manage, if event possible at all. One way to overcome this problem is to use access control lists, which are provided in most modern UNIX systems.

#### Access Control Lists in UNIX

Many modern UNIX and UNIX-based operating systems support access control lists. The feature is referred to as extended access control list, while the traditional UNIX approach is referred to as minimal access control list.  
FreeBSD allows teh administrator to assign a list of UNIX user IDs and groups to a file by using the *setfacl* command. Any number of users and groups can be associated with a file, each with three protection bits (read, write, execute), offering a flexible mechanism for assigning access rights. FreeBSD files include an additional protection bit that indicates whether the file has an extended ACL.  
FreeBSD and most UNIX implementations that support extended ACLs use the following strategy:

1. The owner class and other class entries in the 9-bit permission field have the same meaning as in the minimal ACL case.
2. The group class entry specifies the permissions for the owner group for this file. These permissions represent the maximum permissions that can be assigned to named users or named groups, other than the owning user. In this latter role, the group class entry functions as a mask.
3. Additional named users and named groups may be associated with the file, each with a 3-bit permission field. The permissions listed for a named user or named group are compared to the mask field. Any permission for the named user or name group that is not present in the mask field is disallowed.

When a process requests access to a file system object, two steps are performed:

1. Selects the ACL entry that most closely matches the requesting process. Only a single entry determines access.
2. Checks if the matching entry contains sufficient permissions. A process can be a member in more than one group; so more than one group entry can match. If any of these matching group entries contain the requested permissions, one that contains the requested permissions is picked.

### 4.5 Role-Based Access Control

RBAC is based on the roles that users assume in a system rather than the user's identity. Typically, RBAC models define a role as a job function within an organization. RBAC systems assign access rights to roles instead of individual users. In turn, users are assigned to different roles, either statically or dynamically, according to their responsibilities.  
The relationship of users to roles is many to many.  
The set of roles in the system in most environments is relatively static, with only occasional additions or deletions. Each role will have specific access rights to one or more resources.  
We can use the access matrix representation to depict the key elements of an RBAC system in simple terms. Each matrix entry is either blank or marked, the latter indicating that this user is assigned to this role. Note a single user may be assigned multiple roles and multiple users may be assigned to a single role. Note a role can be treated as an object, allowing the definition of role hierarchies.  
RBAC lends itself to an effective implementation of the principle of least privilege. Each role should contain the minimum set of access rights needed for that role.

#### RBAC Reference Models

A paper defines a family of reference models that has server as the basis for ongoing standardization efforts. This family consists of four models that are related to each other. RBAC$_0$ contains the minimum functionality for an RBAC system. RBAC$_1$ includes the RBAC$_0$ functionality and adds role hierarchies, which enable one role to inherit permissions from another role. RBAC$_2$ includes RBAC$_0$ and adds constraints, which restrict the ways in which the components of an RBAC system may be configured. RBAC$_3$ contains the functionality of RBAC$_0$, RBAC$_1$ and RBAC$_2$.

| Models | Hierarchies | Constraints |
| --- | --- | --- |
| RBAC$_0$ | No | No |
| RBAC$_1$ | Yes | No |
| RBAC$_2$ | No | Yes |
| RBAC$_3$ | Yes | Yes |

##### Base Model - RBAC$_0$

It contains the four types of entities in an RBAC$_0$ system: user, role, permission and session.  
The many to many relationships between users and roles and between roles and permissions provide a flexibility and granularity of assignment not found in conventional DAC schemes. Without this flexibility and granularity, there is a greater risk that a user may be granted more access to resources than is needed because of the limited control over the types of access that can be allowed.

##### Role Hierarchies - RBAC$_1$

Role hierarchies provide a means of reflecting the hierarchical structure of roles in an organization. Role hierarchies make use of the concept of inheritance to enable one role to implicitly include access rights associated with a subordinate role. One role can inherit access rights from multiple subordinate roles. More than one role can inherit from the same subordinate role.

##### Constraints - RBAC$_2$

Constraints provide a means of adapting RBAC to the specifics of administrative and security policies in an organization. A constraint is a defined relationship among roles or a condition related to roles. A paper lists the following types of constraints:

- Mutually exclusive roles: they are roles such that a user can be assigned to only one role in the set. The mutually exclusive constraint supports a separation of duties and capabilities within an organization. This separation can be reinforced or enhanced by use of mutually exclusive permission assignments. With this additional constraint, a mutually exclusive set of roles has the following properties:
  1. A user can only be assigned to one role in the set;
  2. Any permission (access right) can be granted to only one role in the set.

  Thus, the set of mutually exclusive roles have non overlapping permissions.
- Cardinality: it refers to setting a maximum number with respect to roles. One such constraint is to set a maximum number of users that can be assigned to a given role.
- Prerequisite roles: specified by the system, they dictate a user can only be assigned to a particular role if it is already assigned to some other specified role. A prerequisite can be used to structure the implementation of the least privilege concept.

## Tutorials

### T1 - Exposed attack surface (nmap)

Every host that is connected to a network has an exposed attack surface. Even if there are no active services that are accepting requests from the network, there is always a protocol stack that performs many complex operations on the inbound packets that are received from the network. Very often, an online host also provides services that can be accessed from the network. Being able to precisely determine the exposed attack surface of the hosts in our organization is a basic network security procedure.

The network mapper (`nmap`) is an open source tool that has been specifically designed for discovering the host/devices that are connected in a specific network and to probe their exposed attack surface. It is possible to perform the discovering using various protocols, like ICMP or TCP-SYN.  
Example command: `sudo nmap -sn -v 192.168.1.0/24` (use ICMP), `sudo nmap -sS -v 192.168.1.0/24` (use TCP).

Many tools have been implemented for executing a network discovery. `netdiscover` is another relevant one.
Example command: `sudo netdiscover -i <network_device> -p`, in this case the network discovery procedure is passive. This means that we are not probing the target devices sending packets on the network but only listening on the network.

After finding one or more hosts to which we are interested for a deeper analysis, we can revert to nmap for performing a port scanning of such devices. Now, we are interested in finding what services are listening to network sockets and are accessible from outside the specific host.  
We start by using a feature of nmap that is often able to determine what OS (and version) is running on the chosen device: `sudo nmap -O <ip_host_address>`.  We can use `sudo nmap -sT <ip_host_address>` to perform host scanning with the TCP protocol (or `sudo nmap -sU <ip_host_address>` for UDP). We can add `-p0-65535` argument to scan all the existing ports.

Nmap has a modular structure that is used for integrating adjunctive components. For example, it is possible to enable the execution of one or more scripts that are specifically designed for finding vulnerabilities in the software installed on the targe machine. A typical example is the "vuln" script that is part of the standard nmap distribution: `sudo nmap --script vuln -v <ip_host_address>`, it inspect the services running on the machine and likely some known vulnerabilities have been reported.  
Another script, much more aggressive, is: `sudo nmap -Pn --script ssh-brute -v <ip_host_address>` which uses a brute-force attack on a exposed service (i.e. ssh). In other words, it tries often used combinations of username and password.

### T2 - DES and AES encryption using OpenSSL

In GNU/LINUX, encrypting a text using the DES cipher is very easy. In fact, it is sufficient to use the implementation provided by the OpenSSL software tool.  
Example command: `openssl enc -e -des -salt -in plaintext.txt -out ciphertext.bin -pass pass:cybersecurity`, we obtain a new binary file that contains the ciphered text.  
We can decrypt using `openssl enc -d -des -in ciphertext.bin -out plaintext2.txt -pass pass:cybersecurity` and we can verify if the file is byte-to-byte identical with plaintext.txt `diff plaintext2.txt plaintext.txt`.  
It is useful to perform encryption in parallel for reducing the amount of time needed for encrypting a file.

### T3 - Practical dictionary attack to the symmetric encryption

Let's suppose that an attacker has been able to intercept and record a message that has been encrypted using a symmetric block cipher. And assume that the attacker knows the specific cipher used for encrypting the message and the different encryption parameters. In practice, the whole security (i.e. confidentiality) of the transmission is based on a strong cipher and the confidentiality of the symmetric encryption key.  
The command used by the sender to encrypt the message is: `openssl enc -e -aes-256-cbc -iter 1 -md sha512 -in plaintext.txt -out ciphertext.bin -pass pass:<password>`. Note that use a password for getting a key is called *derivation*. In the command, the hash function "hash512" is run a single time.  
The approach followed by the attacker to break the encryption is to try all the possible keys. This operation must be done considering two important aspects:

- avoid false negative: a specific word is tried but not detected as the correct key for decrypting the message;
- minimize or avoid false positives: a word that is unable to decrypt the message in the correct plaintext is reported as correct.

#### First attempt

```sh
# Stage: 1	"Testing all the keys in a given dictionary"
# Italian dictionary (common Italian words)
DICT="/usr/share/dict/italian"

# Checking the number of input parameters
if [ "$#" -ne 1 ]; then
    echo "brute-force-openssl-1.sh: ERROR (Illegal number of parameters)"
    echo "syntax: brute-force-openssl-1.sh ciphertext.bin"
    
    exit 1
fi

# Ciphertext (input parameter)
INPUT_FILE="$1"

echo "brute-force-openssl-1.sh: running..."

# Checking all the words in the dictionary
while read tested_key; do
 # Assuming to know the used encryption algorithm and parameters
 openssl enc -d -aes-256-cbc -iter 1 -md sha512 -in $1 -out plaintext-test.txt -pass pass:$tested_key &> /dev/null

 # If the decryption has not returned errors
 if [ $? -eq 0 ]
 then
  # I found the key!!!
  echo -e -n "Found: >>>$tested_key<<<\tand the recovered messages is: "
  cat plaintext-test.txt
  echo ""
  break
 fi
done <$DICT

rm -f output.txt plaintext-test.txt
```

The first attempt produce a result that is not what we expected. That's because of the semantics of the errors reported by OpenSSL. It returns an error only if there is an alignment problem of the generated output with respect to the expected output (i.e., the different output sizes differ). In practice, brute-forcing a message encrypted by using OpenSSL and following this approach would generate a relevant number of false positives. Verify that using the second approach.

#### Second attempt

```sh
# Stage: 2 "Testing all the keys in a given dictionary"
#   "Not stopping after the first success"

# Italian dictionary (common Italian words)
DICT="/usr/share/dict/italian"

# Checking the number of input parameters
if [ "$#" -ne 1 ]; then
    echo "brute-force-openssl-2.sh: ERROR (Illegal number of parameters)"
    echo "syntax: brute-force-openssl-2.sh ciphertext.bin"
    
    exit 1
fi

# Ciphertext (input parameter)
INPUT_FILE="$1"

echo "brute-force-openssl-2.sh: running..."

# Checking all the words in the dictionary
while read tested_key; do
 # Assuming to know the used encryption algorithm and parameters
 openssl enc -d -aes-256-cbc -iter 1 -md sha512 -in $1 -out plaintext-test.txt -pass pass:$tested_key &> /dev/null

 # If the decryption has not returned errors
 if [ $? -eq 0 ]
 then
  # I found a possible key!!!
  echo -e -n "Found: >>>$tested_key<<<\tand the recovered messages is: "
  cat plaintext-test.txt
  echo ""
 fi
done <$DICT

rm -f output.txt plaintext-test.txt

```

We have solved the problem of false positives but we introduced false negative. We can use a simple heuristic function that is based on another assumption: the message contains at least a given number of consecutive letters. Of course it's not a realistic assumption.

#### Third attempt

```sh
# Stage: 3 "Testing all the keys in a given dictionary"
#   "Not stopping after the first success"
#   "Adding a simple heuristic to reduce false positives"

# Italian dictionary (common Italian words)
DICT="/usr/share/dict/italian"

# Checking the number of input parameters
if [ "$#" -ne 1 ]; then
    echo "brute-force-openssl-3.sh: ERROR (Illegal number of parameters)"
    echo "syntax: brute-force-openssl-3.sh ciphertext.bin"
    
    exit 1
fi

# Ciphertext (input parameter)
INPUT_FILE="$1"

echo "brute-force-openssl-3.sh: running..."

# Checking all the words in the dictionary
while read tested_key; do
 # Assuming to know the used encryption algorithm and parameters
 openssl enc -d -aes-256-cbc -iter 1 -md sha512 -in $1 -out plaintext-test.txt -pass pass:$tested_key &> /dev/null

 # If the decryption has not returned errors
 if [ $? -eq 0 ]
 then
  # I found a possible key!!!
  
  # Simple heuristic - I look for a sequence of at least 5 consecutive characters
  egrep -an --color '.*[[:alpha:]]{5,}' plaintext-test.txt
  
  if [ $? -eq 0 ]
  then
   echo -e -n "Found: >>>$tested_key<<<\tand the recovered messages is: "
   cat plaintext-test.txt
   echo ""
  fi
 fi
done <$DICT

rm -f output.txt plaintext-test.txt

```

We can see that even using the proposed heuristic, we have been unable to avoid all the false positives even if we have been able to reduce them.  

#### Fourth attempt

```sh
# Stage: 4 "Testing all the keys in a given dictionary"
#   "Not stopping after the first success"
#   "Adding a simple heuristic to reduce false positives"
#   "Let's go parallel!" (this stage is composed of 2 files:
#    - main (sequential bootstrap)
#    - satellite (parallel execution)

#############
# main
#############

# Italian dictionary (common Italian words)
DICT="/usr/share/dict/italian"

# Checking the number of input parameters
if [ "$#" -ne 1 ]; then
 echo "brute-force-openssl-4-main.sh: ERROR (Illegal number of parameters)"
 echo "syntax: brute-force-openssl-4-main.sh ciphertext.bin"
    
 exit 1
fi

# Ciphertext (input parameter)
INPUT_FILE="$1"

echo "brute-force-openssl-4-main.sh: running... (parallel execution of many workers)"

# Using GNU parallel to execute in parallel the encryption (and hopefully to speed up operations)
cat $DICT | parallel --pipe -N 10000 --jobs 4 --max-args=1 ./brute-force-openssl-4-satellite.sh $1
#############
# satellite
#############
# echo "...worker $$ is running..."

while LINE='$\n' read -r tested_key; do
    
 openssl enc -d -aes-256-cbc -iter 1 -md sha512 -in $1 -out plaintext-test-$$.txt -pass pass:$tested_key &> /dev/null

 # If the decryption has not returned errors
 if [ $? -eq 0 ]
 then
  # I found a possible key!!!
  
  # Simple heuristic - I look for a sequence of at least 5 consecutive characters
  egrep -an --color '.*[[:alpha:]]{5,}' plaintext-test-$$.txt
  
  if [ $? -eq 0 ]
  then
   echo -e -n "Found: >>>$tested_key<<<\tand the recovered messages is: "
   cat plaintext-test-$$.txt
   echo ""
  fi
 fi

 rm -f plaintext-test-$$.txt
done
```

To speed up the execution of the dictionary attack we can use the GNU parallel tool. To do that we need a main script that controls the execution of many satellite scripts.


### T4 - Usage examples of GPG

GPG (GnuPG) us a complete implementation of the OpenPGP standard for sending and receiving secure emails. GPG implements both symmetric and asymmetric encryption ciphers and it is typically used for encrypting email but it can be also used for encrypting generic input files.  
The first step is about generating a new couple of keys for an identity: `gpg --gen-key`. The default parameters used are fair but they can be tuned. After some time, the keys are generated and then tagged with a specific identifier. It is possible to list all the public (`gpg --list-public-keys`) or private (`gpg --list-private-keys`) keys that are stored in our system.  
Just after creating the new key-pair, it's important to generate and secure the corresponding revocation certificate.

To make available to the public the public-key we can use various systems. For example we can publish a text file in a website (`gpg --export -a <Key-ID> > mykey.asc`) or we can use a key server (`gpg --send-keys --keyserver <KEY_SERVER> <KEY_ID>`). A key server is an infrastructure that is specifically dedicated to the publication of public keys and their management. Obviously it possible to query the key server for finding already existing public keys (`gpg --search-keys <EMAIL_LINKED_TO_KEY>`) and we can import that public key to our keyring.  
Assuming we imported the key linked to the email "foo@bar.xy", we can encrypt a document that needs to be delivered in a confidential way to the owner of the public key: `gpg --encrypt --recipient 'foo@bar.xy' foo.txt`. If it's not important to hide the content of the message but only to authenticate its originator we use `gpg --output foo.txt.sig --sign foo.txt`.  
It is also possible to combine both operations to get CIA: `gpg --encrypt --sign --recipient 'foo@bar.xy' foo.txt`.

#### Web-of-Trust

Consider the problem related to the authenticity of the public-key that we used for encrypting our message to preserve confidentiality. The mechanism that is typically used by gpg is called *web-of-trust*. The basic idea of the web-of-trust is that after carefully checking the identity of the people that we know (in real life) and their matching with their corresponding public-key,, then we can validate this match by signing their public-key (using our private-key). In practice, signing a key of someone has the effect of extending our web-of-trust and moreover, maybe we can accept to trust someone that is unknown to us that has been validated by one or more friends of ours.  
Since it results quite uneasy to bring with us the printed version of our public-key it is preferred to use the fingerprint (`gpg --fingerprint <KEY_ID>`). The procedure is as follows:

1. print out on paper the fingerprint and the identifier of the public-key;
2. provide all that to the person that is willing to sign our public key;
3. get the key to be signed using `gpg --keyserver <keyserver> --recv-keys <Keys_ID>`;
4. after a final check to verify the information, proceed with key signature using `gpg --sign-key <KEY_ID>`;
5. propagate the signing operation to a key server to build a public web-of-trust using `gpg --keyserver <keyserver> --send-key <KEY_ID>`.

It is possible to list all the signature that have been collected by a specific public-key using `gpg --list-sigs <KEY_ID>`.

#### Using GPG for symmetric encryption

GPG also implements some symmetric ciphers, for example use `gpg --output foo.txt.gpg --symmetric foo.txt` to encrypts an input file using the default symmetric cipher provided by GPG. The different ciphers can be listed with `gpg --version`.

#### AGE

Age is a promising tool for encrypting message and files and it is implemented using Go. It is cross-platform and it already part of many Linux distributions.

### T5 - Example of pharming attack to HTTP and HTTPS

#### Attacking HTTP

The general structure of the attack is composed of the following steps:

1. cloning of the pages of the target website + implementing local modifications;
2. setup of a fake HTTP server that is used to service the pages requested by the victim web browser;
3. redirections of the request made by the web browser to the fake HTTP server.

The first two points are simple, the third point is the core of the attack. This redirection can be implemented in many different ways: 

- the typical attack pattern is about modifying the DNS host addresses provided by the router to the hosts in the local network. In fact, the DHCP protocol is not only responsible to provide an IP address to every host that is newly connect to the network but also to provide some basic communication parameters such as the IP addresses of the DNS servers and the IP address of the default gateway;
- by modifying the default gateway;
- installation, by the attacker, of a rogue DHCP server that provides forged parameters to the clients entering the network. This would be typically combined with a DoS attack to the legitimate DHCP server to slow it down (or stop) its execution;
- modifying the content of the "/etc/hosts" file that is used by the local DNS resolver (only for single host attack);
- configuration of (transparent) HTTP proxies;
- modification of some specific information (e.g. the destination IP address) on the packers in the communication flow, using specific tools that operate at the kernel level such as `iptabled` and `nftables`.

#### Attacking HTTPS

The main difference between HTTPS and HTTPS is the usage of an encrypted communication protocol based on TLS. The goal of TLS is to provide confidentiality, integrity and also authenticity to the data stream.  
For a pharming attack over the HTTPS protocols, the three steps above are not sufficient. It is also necessary to assume the compromission of the SSL/TLS certificate.  
Since it is possible, but very unlikely, that an attacker is able to compromise a CA then we will assume that the compromission will be only local. The best possibility for the attacker is to attack the integrity of the web browser used by the victim. Also in this case, there are many possible avenues of attack but the simplest consists of adding a new host certificate to the list of trusted certificates recognized by the browser. Note that operation does not need any special execution privilege.

#### Revocation of Certificates

A final point that must be considered is the violation of the certificate authority (it does not happen very often). When it happens, all the certificates that have been issued by the CA with the compromised private key must be revoked as soon as possible. The mechanism for the certificate revocation must be implemented in all browser and in all the libraries that make use of encrypted communications that are based on TLS.

### T6 - Offline password cracking using John the Ripper (JtR)

a