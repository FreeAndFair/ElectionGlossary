<link rel="stylesheet" href="https://pages.nist.gov/nist-header-footer/css/nist-combined.css">
<script src="https://pages.nist.gov/nist-header-footer/js/jquery-1.9.0.min.js" type="text/javascript" defer="defer"></script>
<script src="https://pages.nist.gov/nist-header-footer/js/nist-header-footer.js" type="text/javascript" defer="defer"></script>

# Election Terminology Glossary
> This glossary contains election terms including those used in the  Voluntary Voting System Guidelines 2.0 (VVSG 2.0) requirements and glossary and in the NIST Common Data Format (CDF) specifications.  The glossary was  built via a joint effort by The Democracy Fund, the VVSG Election Modeling public working group, NIST, and other individuals in the election community.  The Democracy Fund in particular has recognized that a glossary of common election terms would help states and others working in elections to all "speak the same language."  The glossary provides synonyms and as much as is possible, descriptions of how a term's meaning may differ depending on its usage across different states and territories.


## <a name="absentee-ballot"></a>absentee ballot
[Ballot](#ballot) used for [absentee voting](#absentee-voting).


Synonyms: `mail ballot`, `postal ballot`

## <a name="absentee-voting"></a>absentee voting
Voting that is typically unsupervised at a location chosen by the [voter](#voter) either before or on [election day](#election-day).


Synonyms: `all-mail voting`, `mail voting`, `postal voting`, `vote-by-mail`

## <a name="access-control"></a>access control
The process of granting or denying specific requests to:
 - obtain and use information and related information processing services; and
 - enter specific physical facilities.


## <a name="acceptance-testing"></a>acceptance testing
Examination of a [voting system](#voting-system) and by the purchasing [election jurisdiction](#election-jurisdiction) to validate:
 - the performance of delivered [devices](#device) to ensure they meet procurement requirements, and
 - that the delivered system is, in fact, the certified system purchased.
 This usually happens in a simulated-use environment.


## <a name="accessibility"></a>accessibility
Measurable characteristics that indicate the degree to which a system is available to, and usable by, individuals with disabilities. The most common disabilities include those associated with vision, hearing, mobility, and cognition.


## <a name="accreditation"></a>accreditation
Formal recognition that a laboratory is competent to carry out specific [tests](#test) or calibrations.


## <a name="accreditation-body"></a>accreditation body
 1. Authoritative body that provides [accreditation](#accreditation).
 2. Independent organization responsible for assessing the performance of other organizations against a recognized [standard](#standard), and
 3. formally confirming the status of those that meet the standard.


## <a name="activation-device"></a>activation device
[Programmed device](#programmed-device) that creates credentials necessary to begin a [voting session](#voting-session) using a specific [ballot style](#ballot-style). Examples include [electronic poll books](#electronic-poll-book) and card activators that contain credential information necessary to determine the appropriate ballot style for the [voter](#voter).


## <a name="active-period"></a>active period
Span of time during which a [vote-capture device](#vote-capture-device) either is ready to begin a [voting session](#voting-session) or is in use during a voting session.


## <a name="adjudication"></a>adjudication
Process of resolving flagged [cast ballots](#cast-ballot) to reflect [voter intent](#voter-intent). Common reasons for flagging include:
 - write-ins,
 - [overvotes](#overvote),
 - marginal [machine-readable mark](#machine-readable-mark),
 - having no [contest selections](#contest-selection) marked on the entire [ballot](#ballot), or
 - the ballot being unreadable by a scanner.


## <a name="adjudication-required-ballot"></a>adjudication-required ballot
A [ballot](#ballot) that contains [contest selections](#contest-selection) that require [adjudication](#adjudication).


## <a name="administrato"></a>adminstrator
A [voting system](#voting-system) user with the highest level of access.

Synonyms: `admin`, `highest level of authorized user`


## <a name="air-gap"></a>air gap
A physical separation between systems that requires data to be moved by some external, manual procedure.


## <a name="alert-time"></a>alert time
During a voting session, the amount of time that a [voting device](#voting-device) will wait for detectible [voter](#voter) activity after issuing an alert before going into an inactive state requiring [election worker](#election-worker) intervention.


## <a name="alternative-format"></a>alternative format
The [ballot](#ballot) or accompanying information is said to be in an alternative format if it is presented in non-standard ballot language and format. Examples include, but are not limited to, languages other than English, Braille, ASCII text, large print, recorded audio.


## <a name="appropriate-mark"></a>appropriate mark
An [expected mark](#expected-mark) made according to the [ballot instructions](#ballot-instructions).


## <a name="approval-voting"></a>approval voting
A [vote variation](#vote-variation) used for [elections](#election) in which each [voter](#voter) may "approve" of (that is, select) any number of [candidates](#candidate). Typically, the winner(s) is the most-approved candidate(s).


Synonyms: `equal-and-even cumulative voting`, `proportional voting`

## <a name="archival-media"></a>archival media
Storage media that is designed to preserve content for an extended period of time with minimal data corruption or loss.


## <a name="assistive-technology"></a>assistive technology
A [device](#device) that improves or maintains the capabilities of people with disabilities (such as no vision, low vision, mobility, or cognitive). These devices include headsets, keypads, software, sip-and-puff, and voice synthesizers.


## <a name="asymmetric-cryptography"></a>asymmetric cryptography
[Encryption](#encryption) system that uses a public and [private key](#private-key) pair for cryptographic operation. The private key is generally stored in a user's [digital certificate](#digital-certificate) and used typically to decrypt or digitally sign data. The [public key](#public-key) is used typically to encrypt the data or verify its [digital signatures](#digital-signature). The keys could be used interchangeably as needed, that is, a public key can be used to decrypt data and the private key can be used to encrypt the data.


## <a name="audio-format"></a>audio format
A [display format](#ballot-display-format) in which [contest options](#contest-option) and other information are communicated through sound and speech.


Synonyms: `audio ballot`

## <a name="audit"></a>audit
1. Systematic, independent, documented process for obtaining [records](#record), statements of fact, or other relevant information and assessing them objectively to determine the extent to which specified requirements are fulfilled.
2. Verification of statistical or exact agreement of records from different processes or subsystems of a [voting system](#voting-system).
3. A review of a system and its controls to determine its operational status and the accuracy of its outputs.


## <a name="audit-device"></a>audit device
[Voting device](#voting-device) dedicated exclusively to independently verifying or assessing the [voting system](#voting-system)'s performance.


## <a name="audit-trail"></a>audit trail
Information [recorded](#record) during [election](#election) activities to reconstruct steps followed or to later verify actions taken with respect to the [voting system](#voting-system).  Audit trails may include event logs, paper records, error messages, and reports.


## <a name="authentication"></a>authentication
Verifying the identity of a user, process, or [device](#device), often as a prerequisite to allowing access to resources in an information system.


## <a name="ballot"></a>ballot
Presentation of the [contest options](#contest-option) for a particular [voter](#voter).


## <a name="ballot-counting-logic"></a>ballot counting logic
The software logic that
 - defines the combinations of [contest selections](#contest-selection) that are valid and invalid on a given [ballot](#ballot) and,
 - determines how the contest selections are totaled in a given [election](#election).


## <a name="ballot-data"></a>ballot data
A list of [contests](#contest) and associated options that may appear on a [ballot](#ballot) for a particular [election](#election).


## <a name="ballot-display-format"></a>ballot display format
The concrete presentation of the contents of a [ballot](#ballot) or other information for the voter or election pfficial appropriate to the particular voting technology being used. The contents may be rendered using various methods of presentation (visual or audio), language, or graphics.


## <a name="ballot-image"></a>ballot image
Archival  digital image (e.g. JPEG, PDF, etc. ) captured from one or more sides of a [paper ballot](#paper-ballot) [cast](#cast) by an individual [voter](#voter).


## <a name="ballot-instructions"></a>ballot instructions
Information provided to the [voter](#voter) that describes the procedure for marking the [ballot](#ballot). This information may appear directly on the paper or electronic ballot or may be provided separately.


## <a name="ballot-manifest"></a>ballot manifest
A catalog prepared by [election officials](#election-official) listing all the physical [paper ballots](#paper-ballot) and their locations in sequence.


## <a name="ballot-marking-device"></a>ballot marking device
A [device](#device) that:
 - permits [contest options](#contest-option) to be reviewed on an electronic interface,
 - produces a human-readable [paper ballot](#paper-ballot), and
 - does not make any other lasting [record](#record) of the [voter](#voter)'s selections.


Synonyms: `BMD`, `EBM`, `electronic ballot marker`

## <a name="ballot-measure"></a>ballot measure
A question that appears on a [ballot](#ballot) with options, usually in the form of an approval or rejection.


Synonyms: `ballot issue`, `ballot proposition`, `ballot question`, `referendum`

## <a name="ballot-measure-option"></a>ballot measure option
A [contest option](#contest-option) that specifies a response to a [ballot measure](#ballot-measure).


## <a name="ballot-on-demand®"></a>ballot on demand®
A process that produces a [paper ballot](#paper-ballot) of the required [ballot style](#ballot-style) that meets a specific [voter](#voter)'s needs. The use of this process requires:
 - a system with a printer that can create a tabulatable paper ballot; and
 - a [device](#device) driving the printer that has all the data needed to print each ballot style and allows selection of the needed style.

Note: "ballot on demand" is a registered trademark of ES&S.


Synonyms: `BOD`

## <a name="ballot-production"></a>ballot production
Process of generating [ballots](#ballot) for presentation to [voters](#voter), for example, printing [paper ballots](#paper-ballot) or configuring the ballot presentation for an electronic display.


## <a name="ballot-rotation"></a>ballot rotation
The process of varying the order of listed [candidates](#candidate) within a [contest](#contest). This allows each candidate to appear first on the list of candidates an approximately equal number of times across different [ballot styles](#ballot-style) or [election districts](#election-district).


## <a name="ballot-secrecy"></a>ballot secrecy
A goal of [voting systems](#voting-system) to ensure that no [contest selections](#contest-selection) can be associated with a [voter](#voter).


## <a name="ballot-style"></a>ballot style
[Ballot data](#ballot-data) that has been put into [contest](#contest) order for a particular [precinct](#precinct) or precinct split and considers a particular set of [voter](#voter) situations. Voter situations include party affiliation (for [closed primaries](#closed-primary)), and age of the voter (in states that permit 17-year-olds to [vote](#vote) in [primary elections](#primary-election)), among others.


## <a name="barcode"></a>barcode
An optical, machine-readable representation of data as a sequence of bars and spaces that conform to accepted [standards](#standard). Linear (1d) barcode standards include UPC, EAN and 128. QR is an example of a 2d barcode standard.


## <a name="barcode-reader"></a>barcode reader
[Device](#device) used to scan [barcodes](#barcode) and convert the encoded information into a usable format.
 Barcode readers are used to scan codes on a variety of [election](#election) materials including [ballots](#ballot), driver's licenses, voter ID cards, voter information packets, envelopes, and other election documents.


## <a name="baseline-voting"></a>baseline voting
A [vote variation](#vote-variation) in which the [candidate](#candidate) with the most [votes](#vote) wins. In single-seat [contests](#contest), the [voter](#voter) may only select one [contest option](#contest-option).  In [multi-seat contests](#multi-seat-contest) for n [seats](#seat), the voter may select up to n contest options.


Synonyms: `Plurality voting`

## <a name="batch"></a>batch
A collection of [paper ballots](#paper-ballot) gathered as a group for tabulation or for auditing.


## <a name="batch-fed-scanner"></a>batch-fed scanner
An electronic [voting device](#voting-device) that:
 - accepts stacks of hand-marked or BMD-produced [paper ballots](#paper-ballot) and automatically processes them until the stack is empty;
 - is usually used at an [election jurisdiction](#election-jurisdiction)'s central location;
 - is most commonly used to process [absentee ballots](#absentee-ballot);
 - usually has input and output hoppers for [ballots](#ballot);
 - scans a ballot and rejects it if either unreadable or un-processable;
 - detects, interprets, and validates [contest selections](#contest-selection);
 - detects and sorts (either digitally or physically) ballots that are unreadable or un-processable, or that contain undeterminable selections, marking exceptions, or write-ins; and
 - [tabulates](#tabulate) and [reports](#report) [contest](#contest) results as required.
 This unit was previously referred to as central count optical scanner or CCOS.


Synonyms: `CCOS`, `central tabulator`, `central-count optical scanner`, `high-speed optical scanner`

## <a name="benchmark"></a>benchmark
Quantitative point of reference to which the measured performance of a system or [device](#device) may be compared.


## <a name="blank-ballot"></a>blank ballot
An issued [ballot](#ballot) without any selections made.


Synonyms: `unmarked ballot`

## <a name="Bluetooth"></a>Bluetooth
A wireless  protocol that  allows  two  similarly  equipped  devices  to  communicate  with  each  other within  a short  distance,  e.g.,  30  ft.


## <a name="callable-unit"></a>callable unit
(Of a software program or logical design) Function, method, operation, subroutine, procedure, or analogous structural unit that appears within a [module](#module).


## <a name="candidate"></a>candidate
Person contending in a [contest](#contest) for [office](#office). A candidate may be explicitly presented as one of the [contest options](#contest-option) or may be a write-in candidate.


## <a name="candidate-option"></a>candidate option
A [contest option](#contest-option) that is associated with a [candidate](#candidate).


## <a name="canvass"></a>canvass
The process of compiling, reviewing, and validating [election](#election) returns that forms the basis of the official results by a [political subdivision](#political-subdivision).


## <a name="cast"></a>cast
(v) The final action a [voter](#voter) takes in selecting [contest options](#contest-option) and irrevocably confirming their intent to [vote](#vote) as selected.


## <a name="cast-ballot"></a>cast ballot
[Ballot](#ballot) in which the [voter](#voter) has taken final action in selecting [contest options](#contest-option) and irrevocably confirmed their intent to [vote](#vote) as selected.


Synonyms: `voted ballot`

## <a name="cast-vote-record"></a>cast vote record
Archival tabulatable [record](#record) of a set of [contest selections](#contest-selection) produced by a single [voter](#voter) as interpreted by the [voting system](#voting-system).


Synonyms: `CVR`

## <a name="central-reporting-device"></a>central reporting device
Electronic [voting device](#voting-device) that consolidates and [reports](#report) [vote](#vote) totals from multiple [precincts](#precinct) at a central location.


## <a name="certification-testing"></a>certification testing
[Testing](#test) of a [voting system](#voting-system) performed by a testing authority (such as the EAC or a state) to ensure that the system meets the requirements defined in the [standards](#standard) being tested against in the manner specified in its product documentation.


## <a name="ciphertext"></a>ciphertext
Data or information in its encrypted form.


## <a name="closed-primary"></a>closed primary
[Partisan primary](#partisan-primary) [election](#election) in which the [voter](#voter) receives a [ballot](#ballot) containing only those [party-specific contests](#party-specific-contest) pertaining to the [political party](#political-party) with which the voter is affiliated, along with [non-party-specific contests](#non-party-specific-contest) presented at the same election. Unaffiliated voters may be permitted to [vote](#vote) only on non-party-specific contests.


## <a name="combined-precinct"></a>combined precinct
Two or more [precincts](#precinct) treated as a single precinct for a specific [election](#election).


Synonyms: `consolidated precinct`, `super precinct`

## <a name="commercial-off-the-shelf"></a>commercial-off-the-shelf
[Hardware](#hardware) or software [components](#component) that are widely available for purchase and can be integrated into special-purpose systems.


Synonyms: `COTS`

## <a name="common-data-format"></a>common data format
[Standard](#standard) and practice of creating and storing data in a common, described format that can be read by other systems.


Synonyms: `CDF`

## <a name="Common-Industry-Format"></a>Common Industry Format
Format used for [usability](#usability) [test](#test) reporting.
The format is described in ISO/IEC 25062:2006 "Common Industry Format (CIF) for Usability Test Reports," one of a group of usability [standards](#standard). CIF is the format required for usability test reporting.


Synonyms: `CIF`

## <a name="component"></a>component
Element within a larger [voting system](#voting-system).


## <a name="confidentiality"></a>confidentiality
Prevention of unauthorized disclosure of information.


## <a name="configuration-management"></a>configuration management
A continuous process of recording and maintaining consistent and reliable [records](#record) pertaining to an organization's [hardware](#hardware) and software composition, including software version control and hardware updates.


## <a name="conformance"></a>conformance
Fulfilling specified requirements by a product, process, or service.


## <a name="conformance-testing"></a>conformance testing
Process of testing a [device](#device) or system of devices against the requirements specified in one or more [standards](#standard). The outcomes of a [conformance](#conformance) [test](#test) are generally a pass or fail result, possibly including [reports](#report) of problems encountered during the execution.


Synonyms: `conformity assessment`

## <a name="contest"></a>contest
A single decision or set of associated decisions being put before the [voters](#voter) (for example, the option of [candidates](#candidate) to fill a particular public [office](#office) or the approval or disapproval of a constitutional amendment). This term encompasses other terms such as "race," "question," and "issue" that are sometimes used to refer to specific kinds of contests. It does not refer to the legal challenge of an [election](#election) outcome.


## <a name="contest-option"></a>contest option
A votable choice that appears under a [contest](#contest).


## <a name="contest-option-position"></a>contest option position
A specified area on a [ballot](#ballot) where a [voter](#voter)'s selection in a particular [contest](#contest) can be indicated.


Synonyms: `ballot marking target area`, `ballot selection position`, `target`, `target area`

## <a name="contest-option-vote"></a>contest option vote
[Vote](#vote) that will be [tabulated](#tabulate) for a particular [contest option](#contest-option).


Synonyms: `valid vote`

## <a name="contest-selection"></a>contest selection
A selection made on the [ballot](#ballot) by a [voter](#voter) with respect to a specific single [contest](#contest) (for example, a [candidate](#candidate), the value "Yes" or "Approve").


## <a name="core-logic"></a>core logic
Subset of application logic that is responsible for [vote](#vote) recording and tabulation.


## <a name="corrective-action"></a>corrective action
Action taken to eliminate the causes of an existing deficiency or other undesirable situation in order to prevent it from recurring.


## <a name="counted-ballot"></a>counted ballot
A [read ballot](#read-ballot) that has been processed and whose [votes](#vote) are included in the vote totals.


Synonyms: `tabulated ballot`, `tallied ballot`

## <a name="cross-party-endorsement"></a>cross-party endorsement
[Endorsement](#endorsement) of a single [candidate](#candidate) or slate of candidates by more than one [political party](#political-party). The candidate or slate appears on the [ballot](#ballot) representing each endorsing political party.


Synonyms: `cross filing`

## <a name="cryptographic-end-to-end-voting-system"></a>cryptographic end-to-end (E2E) verifiable voting systems
A [voting system](#voting-system) that uses cryptographic techniques to store an encrypted copyvof the voter's ballot selections while maintaining ballot secrecy and allows elections outcomes to be independently and universally verified by members of the public. These voting systems provide voters with a special receipt of their cast ballot - one that allows them to verify their vote was included in the outcome but does not reveal to anyone how they voted.


Synonyms: `receipt-based systems`

## <a name="cryptographic-hash"></a>cryptographic hash
A cryptographic algorithm that computes a numerical hash value based on a data file or electronic message. It should be infeasible in practice to find two distinct data files or messages that will result in the same numerical hash value. The numerical value can be considered to be a fingerprint of the file or message. Colloquially known as a hash, hash function, or digital fingerprint. Hashes provide integrity protection.


## <a name="cryptographic-key"></a>cryptographic key
A numeric value used as input to cryptographic operations, such as [decryption](#decryption), [encryption](#encryption), signature generation, or verification of a [digital signature](#digital-signature).


## <a name="cryptography"></a>cryptography
Discipline that embodies the principles, means, and methods for transforming data to hide their semantic content, prevent their unauthorized use, prevent their undetected modification, or establish their authenticity.


## <a name="cumulative-voting"></a>cumulative voting
A [vote variation](#vote-variation) used in multi-seat [contests](#contest) where a [voter](#voter) is permitted to distribute allowed selections to 1 or more candidates in whole vote increments.


## <a name="cybersecurity"></a>cybersecurity
Measures taken to protect computer systems and data from attack and unauthorized access or use.


## <a name="decertification"></a>decertification
Revocation of national or state certification of a [voting system](#voting-system) or any of its [components](#component).


## <a name="decryption"></a>decryption
Cryptographic process of transforming encrypted data back into its pre-encryption form.


## <a name="defense-in-depth"></a>defense-in-depth
Also called the "Castle" approach. Multiple levels of logical and physical security measures that deny a single point of security [failure](#failure) in a system. Examples include the combined use of passwords, [encryption](#encryption), lock-and-key access, security seals, and logs.


## <a name="device"></a>device
Physical apparatus and any supporting supplies, materials, and logic that together form a functional unit that performs assigned tasks as an integrated whole.


## <a name="digital-certificate"></a>digital certificate
A data set used to identify the holder of the certification and to verify, using a PKI, the authenticity of the certificate. It typically includes the holder's [private key](#private-key) and is used for cryptographic operations such as digitally signing or encrypting data.


## <a name="digital-signature"></a>digital signature
A cryptographic operation where a [private key](#private-key) is used to digitally sign an electronic document and the associated [public key](#public-key) is used to verify the signature. Digital signatures provide data [authentication](#authentication) and integrity protection.


## <a name="direct-recording-electronic-voting-machine"></a>direct recording electronic voting machine
A [vote-capture device](#vote-capture-device) that allows:
 - electronic presentation of a [ballot](#ballot),
 - electronic selection of valid [contest options](#contest-option), and
 - electronic storage of [contest selections](#contest-selection) as individual [records](#record).
 It also provides a summary of these contest selections.


Synonyms: `DRE`

## <a name="direct-voter-associations"></a>direct voter associations
A voter's personally identifiable information (PII) created or stored by the voting system that can be used to associate a voter with their ballot selections.  Examples include first name, last name, address, driver's license, voter registration number, and other PII


Synonyms: `PII`

## <a name="early-voting"></a>early voting
Voting that occurs prior to [election day](#election-day) under the supervision of [election workers](#election-worker).


Synonyms: `in-person absentee voting`

## <a name="early-voting-center"></a>early voting center
Physical location where individuals may [cast](#cast) a [ballot](#ballot) before [election day](#election-day) under the supervision of [election workers](#election-worker).


Synonyms: `early vote center`

## <a name="elected-office"></a>elected office
An [office](#office) that is filled primarily or exclusively via [election](#election).


## <a name="election"></a>election
A formal process in which qualified [voters](#voter) select [candidates](#candidate) to fill [seats](#seat) in one or more [offices](#office) and/or [vote](#vote) on one or more proposed [ballot measures](#ballot-measure).


## <a name="Election-Assistance-Commission"></a>Election Assistance Commission
Election Assistance Commission, created by the [Help America Vote Act](#Help-America-Vote-Act) (HAVA) to assist the states regarding HAVA compliance and to distribute HAVA funds to the states. The EAC is also charged with creating [voting system](#voting-system) guidelines and operating the Federal Government's first voting system certification program. The EAC is also responsible for maintaining the National Voter Registration form, conducting research, and administering a national clearinghouse on [elections](#election) that includes shared practices, information for [voters](#voter), and other resources to improve elections.


Synonyms: `EAC`

## <a name="election-certification"></a>election certification
The act of confirming the final official results of a jurisdiction's [election](#election). This event occurs after results from valid [ballots](#ballot) are tallied from all sources ([election day](#election-day), [absentee voting](#absentee-voting), [early voting](#early-voting), [provisional ballots](#provisional-ballot), etc.) and results are validated and approved by those legally responsible.


## <a name="election-day"></a>election day
The last day on which [voters](#voter) may [cast](#cast) a [ballot](#ballot). [Absentee ballots](#absentee-ballot) and [early voting](#early-voting) ballots may be cast in advance of election day.


## <a name="election-definition"></a>election definition
Data used in defining an [election](#election), including [election districts](#election-district), [contests](#contest), [candidates](#candidate), and [ballot style](#ballot-style) information.


## <a name="election-definition-medium"></a>election definition medium
Programmed memory component containing all applicable [election definition](#election-definition) data required by an [election system](#election-system) device.


## <a name="election-district"></a>election district
Administrative area in which [voters](#voter) are entitled to [vote](#vote) in [contests](#contest) that are specific to that area.


## <a name="election-jurisdiction"></a>election jurisdiction
A geographical area to which an authorized authority has been granted to administer [elections](#election) for political or administrative [offices](#office). Areas of jurisdiction apply to local, state, and federal levels. States, counties, cities, [towns](#town), and [townships](#township) are all examples of jurisdictions.


## <a name="election-management-system"></a>election management system
Set of processing functions and databases within a [voting system](#voting-system) typically used to:
 - develop and maintain [election definition](#election-definition) data,
 - perform [ballot](#ballot) layout functions,
 - create ballot presentation templates for ballot printers or [devices](#device) used by [voters](#voter) for ballot markup,
 - [tabulate](#tabulate) [votes](#vote),
 - consolidate and [report](#report) results, and
 - maintain [audit trails](#audit-trail).


Synonyms: `EMS`

## <a name="election-official"></a>election official
Any person who is involved with administering or conducting an [election](#election), including government personnel and temporary [election workers](#election-worker). This may include any county clerk and recorder, election judge, member of a [canvassing](#canvass) board, central election official, [election day](#election-day) worker, member of a board of county commissioners, member or secretary of a board of directors authorized to conduct public elections, representative of a governing body, or other person engaged in the performance of election duties as required by the election code.


## <a name="election-programming"></a>election programming
Process by which [election officials](#election-official) or their designees use [voting system software](#voting-system-software) to create the [election definition](#election-definition) and configure all [election definition medium](#election-definition-medium) for use in a specific [election](#election).


## <a name="election-results-report"></a>election results report
A [tabulation report](#tabulation-report) produced after the closing of [polls](#polling-place) for the purpose of publicizing the vote counts.


## <a name="Election-Results-Reporting-System"></a>Election Results Reporting System
A system that:
 - aggregates and displays [election](#election) results across the [election jurisdiction](#election-jurisdiction),
 - can be real-time or near real-time,
 - can provide a variety of formats for displaying election results, and
 - may provide direct feeds for the media.


Synonyms: `ENR`, `ERR`, `election night reporting`

## <a name="election-system"></a>election system
1. A technology-based system that is used to collect, process, and store data related to [elections](#election) and election administration. In addition to [voter](#voter) registration systems and public election websites, election systems include [voting systems](#voting-system), [vote](#vote) tabulation systems, [electronic poll books](#electronic-poll-book), [election results reporting systems](#Election-Results-Reporting-System), and auditing [devices](#device).
2. Entire array of procedures, people, resources, equipment, and locations associated with conducting elections.


## <a name="election-worker"></a>election worker
Any person who interacts with those coming to [vote](#vote). This includes any [poll](#polling-place) worker, [election day](#election-day) worker, [early voting](#early-voting) worker, or other temporary staff engaged in supporting the voting or vote counting process.


Synonyms: `poll worker`

## <a name="electronic-ballot-delivery"></a>electronic ballot delivery
The delivery of [ballot](#ballot) and [voter](#voter) information packets electronically. The MOVE Act requires each state to provide for the electronic delivery (via fax, email, or an Internet-supported application) of ballots and related information from the local election office to the registered [UOCAVA voter](#UOCAVA-voter).


## <a name="electronic-ballot-interface"></a>electronic ballot interface
Subsystem within a [voting system](#voting-system) which communicates [ballot](#ballot) information to a [voter](#voter) in video, audio, or other [alternative format](#alternative-format) which allows the voter to select [contest options](#contest-option) using vocalization or physical actions.


## <a name="electronic-ballot-return"></a>electronic ballot return
The return of a [voted ballot](#cast-ballot) or [voter](#voter) information packet using electronic means. This can be by fax, email, or through the use of an Internet supported application. Sometimes referred to as "Internet Voting."


## <a name="electronic-device"></a>electronic device
[Device](#device) that uses electronic or electromechanical [components](#component).


## <a name="electronic-poll-book"></a>electronic poll book
[Device](#device) that partially automates the process of checking in [voters](#voter), assigning them the correct [ballot style](#ballot-style), and marking voters who have been issued a [ballot](#ballot). May be used in place of a traditional paper [poll](#polling-place) book. E-poll books can be stand alone at the [precinct](#precinct) with a separate copy of the registration list or can be networked into a central voter registration system. They can check and update voter [records](#record) in real time.


Synonyms: `EPB`, `e-poll book`

## <a name="electronic-voter-interface"></a>electronic voter interface
[Component](#component) of an electronic [vote-capture device](#vote-capture-device) that communicates [ballot](#ballot) information to the [voter](#voter) and accepts [contest selection](#contest-selection) input from the voter.


## <a name="eligible-voters"></a>eligible voters
The universe of all [voters](#voter) who, if they [cast](#cast) a [ballot](#ballot), would have the legal right to have eligible [contests](#contest) on that ballot [tabulated](#tabulate). This would include those who do not appear in the list of eligible voters because they live in a same-day registration or no registration state and did not or could not register ahead of time.


## <a name="encryption"></a>encryption
Cryptographic process of transforming data (called "plaintext") into a form (called "[ciphertext](#ciphertext)") that conceals the data's original meaning to prevent it from being known or used. Encryption provides [confidentiality](#confidentiality) protection.


## <a name="endorsement"></a>endorsement
Approval by a [political party](#political-party), for example, as the [candidate](#candidate) that the party fields in a particular [contest](#contest) or as the candidate that should receive straight party [votes](#vote). In some states, more than one party may endorse a candidate or [contest option](#contest-option).


## <a name="enhanced-visual-format"></a>enhanced visual format
A display format that is an alternative visual format supporting personal screen display choices such as text size, color contrast, and preferred language.


## <a name="error-correction-code"></a>error correction code
Coding system that allows data being read or transmitted to be checked for errors and, when detected, corrects those errors.


## <a name="error-rate"></a>error rate
Ratio of the number of errors that occur to the volume of data processed.


## <a name="escalation-of-privilege"></a>escalation of privilege
An attack on a system where the attacker is using some means to bypass [security controls](#security-controls) in order to attain a higher privilege level on the target system.


## <a name="exhausted-ballot"></a>exhausted ballot
Refers to processing a [ranked choice voting](#ranked-choice-voting) [contest](#contest) on a [cast ballot](#cast-ballot), when that [ballot](#ballot) becomes inactive and cannot be advanced in the tabulation for a contest because there are no further valid rankings on the ballot for continuing [contest options](#contest-option).


## <a name="expected-mark"></a>expected mark
Mark that falls wholly or partially inside a [contest option position](#contest-option-position).


## <a name="eXtensible-markup-language"></a>eXtensible markup language
A text-based language used to organize and present information on the World Wide Web.


Synonyms: `XML`

## <a name="extraneous-mark"></a>extraneous mark
A mark on a [paper ballot](#paper-ballot) that appears to be unrelated to the act of indicating a [voter](#voter)'s selection. Examples include:
a mark made unintentionally by a voter that is obviously not related to making a selection; a hesitation mark, a dot within or outside of the [contest option position](#contest-option-position) made by resting a pen or pencil on the [ballot](#ballot); written notes or identifying information not related to indication of the voter's selection; or printing defects.


Synonyms: `inadvertent mark`, `random mark`, `stray mark`

## <a name="failure"></a>failure
Looking at [voting system](#voting-system) reliability, a failure is an event that results in:
 - loss of one or more functions,
 - degradation of performance resulting in a [device](#device) that is unable to perform its intended function,
 - automatic reset, restart, or reboot of the [voting device](#voting-device), operating system or application software, requiring an unanticipated intervention by a person in the role of [election worker](#election-worker) or technician before normal operation can continue, or
 - error messages or audit log entries indicating that a failure has occurred.


## <a name="failure-rate"></a>failure rate
Ratio of the number of [failures](#failure) that occur to the volume of data processed.


## <a name="fault"></a>fault
Flaw in design or implementation that may result in the qualities or behavior of the [voting system](#voting-system) deviating from the qualities or behavior that are anticipated, including those specified in the VVSG or in manufacturer-provided documentation.


## <a name="fault-tolerant"></a>fault-tolerant
A system that continues to operate after the [failure](#failure) of a computer or network [component](#component).


## <a name="Federal-Information-Processing-Standards"></a>Federal Information Processing Standards
Standards for federal computer systems developed by NIST. These [standards](#standard) are developed when there are no existing industry standards to address federal requirements for system [interoperability](#interoperability), portability of data and software, and computer security.


Synonyms: `FIPS`

## <a name="finding"></a>finding
(n) Result of a formal evaluation by a [test](#test) lab or accredited expert.


Synonyms: `verdict`

## <a name="firewall"></a>firewall
A gateway system designed to prevent unauthorized access to a private network or intranet that is connected to the internet. A firewall can be implemented in either [hardware](#hardware) or software, or a combination of both.


## <a name="firmware"></a>firmware
A specific class of software encoded directly into a [hardware](#hardware) [device](#device) that controls its defined functions and provides the low-level control for the computer's specific hardware (such as the firmware that initially boots an operating system).


## <a name="functional-configuration-audit"></a>functional configuration audit
Exhaustive verification of every system function and combination of functions cited in the [manufacturer](#manufacturer)'s documentation. The FCA verifies the accuracy and completeness of the system's Voter Manual, Operations Procedures, Maintenance Procedures, and Diagnostic Testing Procedures.


Synonyms: `FCA`

## <a name="functional-test"></a>functional test
[Test](#test) performed to verify or validate the accomplishment of one or more functions.


## <a name="general-election"></a>general election
[Election](#election) in which all [eligible voters](#eligible-voters), regardless of party affiliation, are permitted to select [candidates](#candidate) to fill public [office](#office) and/or [vote](#vote) on [ballot measures](#ballot-measure).


## <a name="geographical-information-system"></a>geographical information system
A system designed to capture, store, manipulate, analyze, manage, and present all types of spatial or geographical data. GIS systems are used to validate voting district boundaries and may be integrated with the voter registration system.


Synonyms: `GIS`

## <a name="geopolitical-unit"></a>geopolitical unit
Describes units of geopolitical geography so that they can be associated with [contests](#contest), [offices](#office), [ballot styles](#ballot-style), and [election](#election) results.


Synonyms: `GpUnit`

## <a name="graceful-recovery"></a>graceful recovery
Termination of a process that allows the operating system or parent process to regain normal control.  Does no crash the machine or result in a general protection fault (GPF) or blue screen.  The user is not required to close the application and can continue to use the other functionality.


## <a name="hand-count"></a>hand-count
Counting ballot sheets and/or selections on [ballot](#ballot) sheets by human examination.


## <a name="hardware"></a>hardware
The physical, tangible, mechanical, or electromechanical [components](#component) of a system.


## <a name="Help-America-Vote-Act"></a>Help America Vote Act
Act passed by the U.S. Congress in 2002 to make sweeping reforms to the nation's [voting process](#voting-process). HAVA addresses improvements to [voting systems](#voting-system) and [voter](#voter) access that were identified following the 2000 [election](#election).


Synonyms: `HAVA`

## <a name="implementation-statement"></a>implementation statement
Statement by a [manufacturer](#manufacturer) indicating the capabilities, features, and optional functions as well as extensions that have been implemented.


Synonyms: `implementation conformance statement`

## <a name="in-person-voting"></a>in-person voting
Voting that occurs in an official location under the supervision of [election workers](#election-worker).


## <a name="independently"></a>independently
Without assistance from an [election worker](#election-worker) or other person.


## <a name="indirect-selection"></a>indirect selection
The mechanism by which a selection for a specific [contest option](#contest-option) automatically selects other linked contest options. An example is a straight party selection that causes indirect selections for all contest options of the identified party.


## <a name="military-voter"></a>military voter
A unique identifier used to associate a voter with their ballot selections.  Indirect associations do not include PII.


## <a name="information-security"></a>information security
Protecting information and information systems from unauthorized access, use, disclosure, disruption, modification, or destruction in order to provide integrity, [confidentiality](#confidentiality), and availability.


Synonyms: `IS`

## <a name="inspection"></a>inspection
Examination of a product design, product, process, or installation and determination of its conformity with specific requirements.


## <a name="interaction-mode"></a>interaction mode
Control or navigation option that enables [voters](#voter) to operate and interact with the [voting system](#voting-system), used in conjunction with a display format.


## <a name="interoperability"></a>interoperability
The extent to which systems from different [manufacturers](#manufacturer) and [devices](#device) with different system configurations can communicate with each other.


## <a name="intrusion-detection-system"></a>intrusion detection system
A [hardware](#hardware) or software application that detects and [reports](#report) a suspected security breach, policy violation, or other compromise that may adversely affect the network.


Synonyms: `IDS`

## <a name="key-management"></a>key management
Activities involving handling of [cryptographic keys](#cryptographic-key) and other related security parameters (such as passwords) during the entire [life cycle](#life-cycle) of the keys, including their generation, storage, establishment, entry and output, zeroization, and revocation.


## <a name="life-cycle"></a>life cycle
Systems engineering concept that identifies the phases that a system passes through, from concept to retirement. There are different concerns and activities associated with each phase of the life cycle.


## <a name="limited-dexterity-mode"></a>limited dexterity mode
An interaction mode with accessibility features for voters with no use of one or both hands or low dexterity.  This mode includes the tactile mode and the non-manual mode.


## <a name="locality"></a>locality
Generic term used in [election](#election) contexts to signify a [town](#town), village or city contained within an [election jurisdiction](#election-jurisdiction), such as a county.


## <a name="logic-and-accuracy-testing"></a>logic and accuracy testing
Equipment and system readiness [tests](#test) whose purpose is to detect malfunctioning [devices](#device) and improper election-specific setup before the equipment or systems are used in an [election](#election). [Election officials](#election-official) conduct L&A tests prior to the start of an election as part of the process of setting up the system and the devices for an election according to jurisdiction practices and conforming to any state laws.


Synonyms: `L&A`, `LAT`

## <a name="logic-defect"></a>logic defect
[Fault](#fault) in software, [firmware](#firmware), or hardwired logic.


## <a name="logical-correctness"></a>logical correctness
Condition signifying that, for a given input, a computer program will satisfy the program specification and produce the required output.


## <a name="low/no-dexterity-mode"></a>low/no dexterity mode
An [interaction mode](#interaction-mode) with [accessibility](#accessibility) features for [voters](#voter) with no use of one or both hands or low dexterity.


## <a name="machine-readable-mark"></a>machine-readable mark
Mark in a [contest selection](#contest-selection) position of a [paper ballot](#paper-ballot) that meets requirements for detection by a scanner.


## <a name="machine-unreadable-mark"></a>machine-unreadable mark
Mark in a [contest selection](#contest-selection) position of a [paper ballot](#paper-ballot) that cannot be detected as readable or marginal by a scanner, and may require human [adjudication](#adjudication).


## <a name="majority-voting"></a>majority voting
A [vote variation](#vote-variation) which requires the winning [candidate](#candidate) to receive more than half of the [votes](#vote) [cast](#cast). If no candidate wins an outright majority, a [runoff election](#runoff-election) may be held between the top two vote-getters.


## <a name="malware"></a>malware
Software or [firmware](#firmware) intended to perform an unauthorized process that will have adverse impact on the [confidentiality](#confidentiality), integrity, or availability of a system. For example, a virus, worm, Trojan horse, or other code-based entity that infects a host. Spyware and some forms of adware are also examples of malware.


Synonyms: `malicious code`

## <a name="manually-marked-paper-ballot"></a>manually-marked paper ballot
[Paper ballot](#paper-ballot) marked by a [voter](#voter) using a writing utensil.


Synonyms: `MMPB`

## <a name="manufacturer"></a>manufacturer
Entity with ownership and control over a [voting system](#voting-system) submitted for testing.


## <a name="marginally-machine-readable-mark"></a>marginally machine-readable mark
An intentional mark in a [contest selection](#contest-selection) position of a [paper ballot](#paper-ballot) that does not meet the requirements for a reliably detectable selection, and therefore requires human [adjudication](#adjudication). A marginal mark may be determined to indicate a selection, depending on state law.


Synonyms: `marginal mark`

## <a name="marked-ballot"></a>marked ballot
[Ballot](#ballot) that contains all of a [voter](#voter)'s selections.


## <a name="message-authentication-code"></a>message authentication
A data authenticator generated from the message, usually though cryptographic techniques, that is designed to reveal both accidental errors and intentional modifications of the data.  In general, a cryptographic key is also required as an input.


## <a name="military-voter"></a>military voter
A member of a uniformed service in active service, including army, navy, air force, marine corps, coast guard and merchant marine, and their spouses and dependents.


## <a name="misfeed-rate"></a>misfeed rate
Ratio of the misfeed total to the total [ballot](#ballot) volume.


## <a name="module"></a>module
A structural unit of a software program that serves a specific function for the program or that serves to make the program modular in structure for the purposes of easier understanding and maintenance.


## <a name="multi-factor-authentication"></a>multi-factor authentication
[Authentication](#authentication) mechanism requiring two or more of the following:
 - something you know (such as a password),
 - something you have (such as a [token](#token)),
 - something you are (for example, biometric authentication).


## <a name="multi-seat-contest"></a>multi-seat contest
[Contest](#contest) in which multiple [candidates](#candidate) are elected to fill a specified number of [seats](#seat).


## <a name="municipality"></a>municipality
Term as used in [election](#election) contexts to signify a jurisdiction such as city, [town](#town), or village that has some form of local government for which elections are generally conducted.


## <a name="N-of-M-voting"></a>N-of-M voting
[Vote variation](#vote-variation) in which the [voter](#voter) is entitled to allocate a fixed number of [votes](#vote) (N) over a list of M [contest options](#contest-option) or [write-in options](#write-in-option), with the constraint that at most 1 vote may be allocated to a given contest option. This usually occurs when multiple [seats](#seat) are concurrently being filled in a governing body such as a city council or school board where [candidates](#candidate) contend for at-large seats. The voter is not obliged to allocate all N votes. 1-of-M is N-of-M voting where N = 1.


## <a name="national-certification-test-report"></a>national certification test report
[Report](#report) of the results of independent testing of a [voting system](#voting-system) by a [Voting System Test Lab](#voting-system-test-lab) (VSTL) delivered to the EAC with a recommendation about granting a certification number.


## <a name="National-Institute-of-Standards-and-Technology"></a>National Institute of Standards and Technology
Federal organization tasked with assisting in the development of [voting system](#voting-system) [standards](#standard). NIST develops and maintains standards for a wide array of technologies. NIST scientists assist the EAC in developing testable standards for voting systems.


Synonyms: `NIST`

## <a name="non-manual-mode"></a>non-manual-mode
An interaction mode that uses assistive technology, for example, a sip-and-puff switch, to allow voters with no use of their hands to operate the voting system.


## <a name="non-party-specific-contest"></a>non-party-specific contest
[Contest](#contest) where eligibility to [vote](#vote) in that contest is independent of [political party](#political-party) affiliation.


## <a name="non-user-serviceable-failure"></a>non-user-serviceable failure
Functional [failure](#failure) that requires the [manufacturer](#manufacturer) or highly trained personnel to repair.


## <a name="nonpartisan-office"></a>nonpartisan office
[Elected office](#elected-office) for which [candidates](#candidate) appear on the [ballot](#ballot) without [political party](#political-party) designation.


## <a name="nonpartisan-primary"></a>nonpartisan primary
[Primary election](#primary-election) held to narrow the field of [candidates](#candidate) in [non-party-specific contests](#non-party-specific-contest).


## <a name="nonvolatile-memory"></a>nonvolatile memory
Memory in which information can be stored indefinitely with no external power applied.


## <a name="notice-of-clarification"></a>notice of clarification
Document providing further guidance and explanation on the requirements and procedures of the EAC's [Voting System](#voting-system) Certification or Voting System Testing Lab ([VSTL](#voting-system-test-lab)) programs. NOCs may be issued in response to a clarification request from a Voting System Test Lab or an EAC registered [manufacturer](#manufacturer). EAC may also issue NOCs when it determines general clarifications are necessary.


## <a name="observational-test"></a>observational test
Operational [test](#test) conducted on [voting devices](#voting-device) during an [election](#election) by real [voters](#voter) to establish confidence that the [voter verifiable](#voter-verifiable) paper [record](#record) is produced correctly when [assistive technology](#assistive-technology) is used. Devices subjected to observational testing are used for normal collection of [votes](#vote); the votes collected are included in the election tally.


## <a name="office"></a>office
A position established by law with certain associated rights and duties.


## <a name="open-primary"></a>open primary
[Partisan primary](#partisan-primary) [election](#election) in which the [voter](#voter) may choose a [political party](#political-party) at the time of voting and [vote](#vote) in [party-specific contests](#party-specific-contest) associated with that party, along with [non-party-specific contests](#non-party-specific-contest) presented at the same election. Some states require voters to publicly declare their choice of party at the [polling place](#polling-place), after which the [election worker](#election-worker) provides or activates the appropriate [ballot](#ballot). Other states allow the voters to make their choice of party within the privacy of the voting booth.


Synonyms: `pick-your-party primary`

## <a name="open-source"></a>open source
Computer software with its [source code](#source-code) (human readable code) made available with a license in which the copyright holder provides the rights to study, change, and distribute the software to anyone and for any purpose. Open source software may:
 - be developed in a collaborative public manner;
 - be reviewed by multiple professional and amateur programmers;
 - require a fee and be licensed like other software; or
 - be fully open source or may have only a portion of the software open source.


## <a name="optical-scan"></a>optical scan
[Voting system](#voting-system) that [tabulates](#tabulate) [votes](#vote) marked in [contest option positions](#contest-option-position) or contained with a barcode on the surface of a [paper ballot](#paper-ballot).


## <a name="overseas-voter"></a>overseas voter
A U.S. citizen who is living outside of the United States and is eligible to [vote](#vote) in their last place of residence in the United States.


## <a name="overvote"></a>overvote
Occurs when the number of selections made by a [voter](#voter) in a [contest](#contest) is more than the maximum number allowed.


Synonyms: `over-vote`

## <a name="paper-ballot"></a>paper ballot
A piece of paper, or multiple sheets of paper, on which all [contest options](#contest-option) of a given [ballot style](#ballot-style) are printed.


## <a name="paper-ballot-sheet"></a>paper ballot sheet
A single piece of paper that forms part of a [paper ballot](#paper-ballot). Paper ballots may contain multiple sheets.


## <a name="paper-ballot-side"></a>paper ballot side
The face of a [paper ballot sheet](#paper-ballot-sheet). A [paper ballot](#paper-ballot) may have two sides.


## <a name="paper-based-voting-system"></a>paper-based voting system
A voting system that records votes, counts votes, and/or produces a report of the vote count from votes cast on paper cards or sheets.


## <a name="partisan-office"></a>partisan office
[Elected office](#elected-office) for which [candidates](#candidate) may appear on the [ballot](#ballot) with a [political party](#political-party) designation.


## <a name="partisan-primary"></a>partisan primary
[Primary election](#primary-election) held to narrow the field of [candidates](#candidate) in [party-specific contests](#party-specific-contest).


## <a name="party-specific-contest"></a>party-specific contest
[Contest](#contest) where eligibility to [vote](#vote) in that contest is restricted based on [political party](#political-party) affiliation or lack of any affiliation. The affiliation might be the registered affiliation of the [voter](#voter) or it might be an affiliation declared at the time of voting.


## <a name="pattern-voting"></a>pattern voting
Selecting [contest options](#contest-option) across multiple [contests](#contest) in a predetermined pattern intending to signal one's identity to someone else. The possibility of pattern voting can be an issue for publishing [Cast](#cast) [Vote](#vote) Records (CVR) because it may compromise [voter](#voter) privacy if there are enough selections in each published CVR to make it likely a selection pattern might be unique.


## <a name="penetration-testing"></a>penetration testing
An evaluation method that enables researchers to search for vulnerabilities in a system.


Synonyms: `Pen Testing`

## <a name="personal-assistive-device"></a>personal assistive device
[Assistive technology](#assistive-technology) belonging to [voters](#voter) rather than any supplied with the [voting system](#voting-system).


## <a name="personal-identifiable-information"></a>personal identifiable information
Any information about an individual including:
 - information that can be used to distinguish or trace an individual's identity, such as name, social security number, date and place of birth, mother's maiden name, or biometric [records](#record); and
 - any other information that can be linked to an individual, such as medical, educational, financial, and employment information.


Synonyms: `PII`, `voter identifying information`, `VII`

## <a name="physical-configuration-audit"></a>physical configuration audit
[Inspection](#inspection) by a [voting system test lab](#voting-system-test-lab) (VSTL) that compares the [voting system](#voting-system) [components](#component) submitted for [certification testing](#certification-testing) to the [manufacturer](#manufacturer)'s technical documentation and confirms that the documentation submitted meets the national certification requirements. Includes witnessing the executable system being built to ensure that the certified release is built from the [tested](#test) components.


Synonyms: `PCA`

## <a name="plurality-voting"></a>plurality voting
A [vote variation](#vote-variation) in which the candidate with the most votes wins, without necessarily receiving a majority of votes.


## <a name="political-party"></a>political party
An association of individuals under whose name a [candidate](#candidate) may appear on a [ballot](#ballot).


## <a name="political-subdivision"></a>political subdivision
Any unit of government, such as counties, cities, school districts, and water and conservation districts having authority to hold [elections](#election) for public [offices](#office) or on [ballot measures](#ballot-measure).


## <a name="polling-location"></a>polling location
Physical address of a [polling place](#polling-place).


## <a name="polling-place"></a>polling place
Location at which [voters](#voter) may [cast](#cast) in-person [ballots](#ballot) under the supervision of [election workers](#election-worker) during one or more specific time periods.


Synonyms: `poll`, `polling station`

## <a name="post-election-tabulation-audit"></a>post-election tabulation audit
A post-election [audit](#audit) that involves hand-counting a sample of [votes](#vote) on paper [records](#record), then comparing those [counts](#tabulate) to the corresponding vote totals originally [reported](#report):
 - as a check on the accuracy of [election](#election) results, and
 - to detect discrepancies using accurate [hand-counts](#hand-count) of the paper records as the [benchmark](#benchmark).



## <a name="precinct"></a>precinct
[Election](#election) administration division corresponding to a geographic area that is the basis for determining which [contests](#contest) the [voters](#voter) legally residing in that area are eligible to [vote](#vote) on.


Synonyms: `tabulation district`, `ward`

## <a name="precinct-count"></a>precinct count
Counting ballots in the same [precinct](#precinct) in which those [ballots](#ballot) have been [cast](#cast).


## <a name="precinct-split"></a>precinct split
A subdivision of a [precinct](#precinct) which arises when a precinct is split by two or more [election districts](#election-district) that may require different [ballot styles](#ballot-style).


Synonyms: `split`, `split precinct`, `sub-precinct`

## <a name="presentable-ballot-style"></a>presentable ballot style
[Ballot style](#ballot-style) that includes all presentational details required to generate a [ballot](#ballot). This may include language, ordering of [contests](#contest) and [candidates](#candidate), and structural content such as headers.


## <a name="presidential-primary-election"></a>presidential primary election
[Primary election](#primary-election) in which [voters](#voter) choose the delegates to the presidential nominating conventions allotted to their states by the national party committees.


## <a name="primary-election"></a>primary election
[Election](#election) held to determine which [candidates](#candidate) qualify to appear as [contest options](#contest-option) in subsequent elections.


## <a name="privacy-(for-voters)"></a>privacy (for voters)
A property of a [voting system](#voting-system) that is designed and deployed to enable [voters](#voter) to obtain a [ballot](#ballot), and mark, verify, and [cast](#cast) it without revealing their ballot selections or selections of language, display and [interaction modes](#interaction-mode) to anyone else.
This does not preclude the ability of a voter to request assistance under state law.


## <a name="private-key"></a>private key
The secret part of an asymmetric key pair that is typically used to digitally sign or decrypt data.


## <a name="product-standard"></a>product standard
[Standard](#standard) that specifies requirements to be fulfilled by a product or a group of products, to confirm it can perform its intended task.


## <a name="programmed-device"></a>programmed device
[Electronic device](#electronic-device) that includes software. Most electronic [voting devices](#voting-device) include application logic (software) and are, therefore, programmed devices.


## <a name="proportional-voting"></a>proportional voting
A [vote variation](#vote-variation) used in [multi-seat contests](#multi-seat-contest) where the [votes](#vote) allowed in the [contest](#contest) are distributed to the selected [candidates](#candidate) proportionally depending on the number of selections. This may result in candidates receiving fractional votes.


## <a name="provisional-ballot"></a>provisional ballot
A failsafe [ballot](#ballot) provided to a [voter](#voter) whose eligibility for a regular ballot cannot be immediately determined. The ballot may be [counted](#tabulate) or further processed depending on state law.


Synonyms: `affidavit ballot`

## <a name="public-key"></a>public key
Public part of an asymmetric key pair that is typically used to verify [digital signatures](#digital-signature) or encrypt data.


## <a name="public-key-infrastructure"></a>public key infrastructure
A set of roles, policies, and procedures used to establish greater trust in the authenticity of a [digital certificate](#digital-certificate) and for use in creating, managing, distributing, using, storing, and revoking digital certificates.


Synonyms: `PKI`

## <a name="public-test"></a>public test
An abbreviated logic and accuracy [test](#test) of voting equipment, pre-announced in public media and open to public attendance, usually in [conformance](#conformance) with specific [election](#election) calendar timing.


## <a name="QR-Code®"></a>QR Code®
A 2-D, trademarked barcode.  An optical, 2-D machine-readable representation of data that conforms to accepted [standards](#standard).


Synonyms: `Quick Response code`

## <a name="range voting"></a>range voting
A [vote variation](#vote-variation) for single-seat contests, in which voters give each candidate a score, the scores are added (or averaged), and the candidate with the highest total is elected.


## <a name="ranked-choice-voting"></a>ranked choice voting
A [vote variation](#vote-variation):
 - which allows each [voter](#voter) to rank [contest options](#contest-option) in order of the voter's preference,
 - in which [votes](#vote) are [counted](#tabulate) in rounds using a series of runoff tabulations to defeat contest options with the fewest votes, and,
 - which elects a winner with a majority of final round votes in a single-winner [contest](#contest) and provides proportional representation in multi-winner contests.


Synonyms: `IRV`, `RCV`, `instant run-off voting`, `ranked order`

## <a name="read-ballot"></a>read ballot
[Cast ballot](#cast-ballot) that has been successfully accepted and initially processed.


Synonyms: `scanned ballot`

## <a name="recall-issue-with-options"></a>recall issue with options
[Vote variation](#vote-variation) that allows [voters](#voter) to remove elected representatives from [office](#office) before their terms of office expire. The recall may involve not only the question of whether a particular officer should be removed, but also the question of naming a successor in the event that there is an affirmative [vote](#vote) for the recall.


## <a name="recallable-ballot"></a>recallable ballot
[Recorded ballot](#recorded-ballot) that can be individually retrieved and included or excluded from further processing.


## <a name="recertification"></a>recertification
Re-examination, and possibly retesting, of a [voting system](#voting-system) that was modified after being previously certified. The object of recertification is to determine if the system as modified still conforms to the requirements.


## <a name="record"></a>record
(n) Preserved evidence of activities performed or results achieved (for example, forms, [reports](#report), [test](#test) results).
 (v) To create a record.


## <a name="recorded-ballot"></a>recorded ballot
A [ballot](#ballot) for which there is an associated [cast vote record](#cast-vote-record).


## <a name="recount"></a>recount
Repeat tabulation of [votes](#vote) [cast](#cast) in an [election](#election), whether manually or electronically, that is used to determine the accuracy of an initial count.


## <a name="report"></a>report
Self-contained, time-stamped, archival [record](#record), such as a printout or analogous electronic file that is produced at a specific time and subsequently protected from modification.


## <a name="report-total-error-rate"></a>report total error rate
Ratio of the [report](#report) total error to the report total volume.


## <a name="reporting-unit"></a>reporting unit
Geographical area in which [reported](#report) totals or counts are reported (for example, an [election jurisdiction](#election-jurisdiction), [precinct](#precinct), or [election district](#election-district)).


## <a name="reproducibility"></a>reproducibility
Ability to obtain the same [test](#test) results by using the same [test method](#test-method) on identical test items in different testing laboratories with different operators using different equipment.


## <a name="residual-vote"></a>residual vote
[Vote](#vote) that could not be allocated to a specific [contest option](#contest-option) due to an [undervote](#undervote) or [overvote](#overvote).


## <a name="resiliance"></a>resiliance
The ability to recover gracefully from error conditions and unexpected circumstances. For example, manually marked paper preserves evidence of exceptions that can advise both [adjudication](#adjudication) and [audit](#audit) to achieve better interpretation of original [voter intent](#voter-intent).


## <a name="reviewed-ballot"></a>reviewed ballot
Ballot that has been reviewed (either electronically or by the voter) before it is cast, to determine what [contest selections](#contest-selection) and if applicable unselected [contest options](#contest-option) it contains.


## <a name="risk-assessment"></a>risk assessment
The process of identifying the risks to system security and determining the probability of occurrence, the resulting impact, and safeguards that would mitigate this impact.


## <a name="risk-limiting-tabulation-audit"></a>risk-limiting tabulation audit
[Post-election tabulation audit](#post-election-tabulation-audit) procedure for checking a sample of [ballots](#ballot) (or [voter verifiable](#voter-verifiable) [records](#record)) that is guaranteed to have a large, pre-specified chance of correcting the [reported](#report) outcome if the reported outcome is wrong (that is, if a full [hand-count](#hand-count) would reveal an outcome different from the reported outcome).


Synonyms: `RLA`

## <a name="runoff-election"></a>runoff election
[Election](#election) to select a winner following a [primary election](#primary-election) or a [general election](#general-election), in which no [candidate](#candidate) in the [contest](#contest) received the required minimum percentage of the [votes](#vote) [cast](#cast). The two candidates receiving the most votes for the contest in question proceed to a runoff election.


## <a name="score-voting"></a>score voting
A [vote variation](#vote-variation) for single-seat [contests](#contest), in which [voters](#voter) give each [candidate](#candidate) a score, the scores are added (or averaged), and the candidate with the highest total is elected.


Synonyms: `range voting`

## <a name="seat"></a>seat
An [elected office](#elected-office) position that a single officeholder may occupy for a term of [office](#office).


## <a name="second-chance-voting"></a>second chance voting
Feature of a [voter-facing scanner](#voter-facing-scanner) that reviews the [ballot](#ballot) for possible marking mistakes, informs the [voter](#voter), and presents an opportunity to [cast](#cast) as-is or return the ballot.


## <a name="security-analysis"></a>security analysis
An inquiry into the potential existence of security flaws in a [voting system](#voting-system). Includes an analysis of the system's software, [firmware](#firmware), and [hardware](#hardware), as well as the procedures associated with system development, deployment, operation, and management.


## <a name="security-controls"></a>security controls
Management, operational, and technical controls (that is, safeguards or countermeasures) prescribed for an information system to protect the [confidentiality](#confidentiality), integrity, and availability of the system and its information.


## <a name="security-strength"></a>security strength
A metric associated with the amount of work (that is, the number of operations) that is required to break a cryptographic algorithm or system.


## <a name="software-independence"></a>software independence
Quality of a [voting system](#voting-system) or [voting device](#voting-device) where a previously undetected change or [fault](#fault) in software cannot cause an undetectable change or error in [election](#election) outcome. In practice, voting systems are generally viewed as possessing the quality of software independence when they allow for a voter-verifiable paper record of voters' contest selections to be created and compared against vote totals or against an electronic cast vote record used in determining vote totals.


Synonyms: `SI`

## <a name="source-code"></a>source code
Human readable computer instructions that, when compiled or interpreted, define the functionality of a [programmed device](#programmed-device). Source code can be written by humans or by computers.


## <a name="spear-phishing"></a>spear phishing
A targeted attack by hackers, using bogus emails, that attempts to get the victim to provide login information or personal information to the hackers. Spear Phishing attempts may appear to originate from legitimate, known sources, such as organizational IT or known vendors.


## <a name="special-election"></a>special election
[Primary election](#primary-election) or [general election](#general-election) that is not regularly scheduled. A special election may be combined with a scheduled [election](#election).


## <a name="spoil"></a>spoil
(A [ballot](#ballot)) To mark or otherwise alter a ballot so it indicates in a human-readable manner that the ballot is not to be [cast](#cast).


## <a name="spoiled-ballot"></a>spoiled ballot
A [ballot](#ballot) that has been issued to a [voter](#voter) but will not be [cast](#cast), usually because it has been incorrectly marked or impaired in some way.


## <a name="standard"></a>standard
A document that provides requirements, specifications, guidelines, or characteristics that can be used consistently to ensure that materials, products, processes, and services are fit for their purpose.


## <a name="straight-party-override"></a>straight party override
Explicit [voter](#voter) selection that overrides or supplements the [vote](#vote) selections made by a [straight party voting](#straight-party-voting) option.  Straight party overrides may be subject to state [election](#election) rules for how they work or whether they are allowed.


## <a name="straight-party-voting"></a>straight party voting
Mechanism that allows [voters](#voter) to [cast](#cast) a single [vote](#vote) to select all [candidates](#candidate) on the [ballot](#ballot) from a single [political party](#political-party).


## <a name="street-segment-data"></a>street segment data
The portion of a street between two consecutive cross streets that can be assigned to a [precinct](#precinct).


## <a name="support-software"></a>support software
Software that aids in developing, maintaining, or using other software, for example, compilers, loaders and other utilities.


## <a name="symmetric-cryptography"></a>symmetric cryptography
[Encryption](#encryption) system that uses the same key for encryption and [decryption](#decryption). This key must be kept secret.


Synonyms: `secret key cryptography`

## <a name="system-extent"></a>system extent
Administrative unit that is the entire scope within which the [voting system](#voting-system) is used (for example, a county). The system extent corresponds to the top-level reporting context for which the system generates [reports](#report).


## <a name="t-coil"></a>t-coil
Inductive coil used in some hearing aids to allow reception of an audio band magnetic field signal instead of an acoustic signal. The magnetic or inductive mode of reception is commonly used in conjunction with telephones, auditorium loop systems, and other systems that provide the required magnetic field output.


## <a name="tabulate"></a>tabulate
Process of totaling [votes](#vote).


Synonyms: `count`

## <a name="tabulation-report"></a>tabulation report
A [report](#report) containing the counts associated with [ballots](#ballot) that have been tabulated.


## <a name="tactile-controls"></a>tactile controls
A tactile control is a physically control discernable or perceptible by touch using hands, feet, or other parts of the body. (Does not include touch screens.)  Dual switches are a form of tactile controls that can be used by [voters](#voter) with minimal use of their hands.


## <a name="technical-data-package"></a>technical data package
[Manufacturer](#manufacturer) documentation relating to the [voting system](#voting-system), which can include manuals, description of [components](#component), and details of architectural and engineering design.


Synonyms: `TDP`

## <a name="test"></a>test
Procedure used to determine one or more characteristics of a given product, process, or service according to a specified procedure for [conformity assessment](#conformance-testing). A test may be an operational test or a non-operating test (for example, an [inspection](#inspection)).


## <a name="test-deck"></a>test deck
A set of marked ballots with a predetermined outcome. Used for [logic and accuracy testing](#logic-and-accuracy-testing) of a [voting system](#voting-system).


## <a name="test-method"></a>test method
Specified technical procedure for performing a [test](#test), procedures by which tests are derived, or a combination of these.


## <a name="test-plan"></a>test plan
Document created prior to testing that outlines the scope and nature of testing, items to be [tested](#test), test approach, resources needed to perform testing, test tasks, risks, and schedule.


## <a name="test-suite"></a>test suite
Implementation of a set of operational [tests](#test) for a particular object (such as a specific [voting system](#voting-system)) or class of objects (such as all voting systems that can interpret the language in which the test data are expressed).


## <a name="third-party-logic"></a>third-party logic
Software, [firmware](#firmware), or hardwired logic that is neither application logic nor [COTS](#commercial-off-the-shelf). This includes, for example, general-purpose software developed by a third party that is either customized (for example, ported to a new platform, as is Windows Embedded Compact), not widely used, or source-code generated by a COTS package.


## <a name="token"></a>token
Something a user possesses and controls, typically a key or password, that is used to authenticate an identity.


Synonyms: `authentication token`, `cryptographic token`

## <a name="touch-screen-voting-machine"></a>touch screen voting machine
A [vote-capture device](#vote-capture-device) that utilizes a computer screen to display the [ballot](#ballot) and allows the [voter](#voter) to indicate their selections by touching designated locations on the screen.


## <a name="town"></a>town
An urban area that has a name, defined boundaries, and local government, and that is generally larger than a village and smaller than a city. Term used in New England, New York, and Wisconsin to refer to the equivalent of the [civil township](#township) in these states.


## <a name="township"></a>township
A widely used unit of local government in the United States, subordinate to a county, with some form of local government for which it generally conducts [elections](#election).


Synonyms: `civil township`

## <a name="undervote"></a>undervote
Occurs when the number of [voter](#voter) selections in a [contest](#contest) is less than the maximum number allowed for that contest or when no selection is made. The number of undervotes is equal to the number of [votes](#vote) lost, for example, if no selection is made in a vote for two contest, the number of votes lost is two.


Synonyms: `under-vote`

## <a name="Uniformed-and-Overseas-Citizens-Absentee-Voting-Act"></a>Uniformed and Overseas Citizens Absentee Voting Act
Act of Congress in 1986 requiring that the states and territories allow certain groups of citizens to register and [vote](#vote) absentee in [elections](#election) for Federal [offices](#office).


Synonyms: `UOCAVA`

## <a name="UOCAVA-voter"></a>UOCAVA voter
An [overseas voter](#overseas-voter) or an active duty member of the U.S. military, either within or outside the United States, including any accompanying spouse and family members who are eligible to [vote](#vote) in their last place of residence in the United States. The [Uniformed and Overseas Citizens Absentee Voting Act](#Uniformed-and-Overseas-Citizens-Absentee-Voting-Act) is commonly referred to as UOCAVA.


## <a name="usability"></a>usability
Effectiveness, efficiency, and satisfaction with which a specified set of users can achieve a specified set of tasks in a particular environment. Usability in the context of [voting](#vote) refers to [voters](#voter) being able to [cast](#cast) [valid votes](#valid-vote) as they intended quickly, without errors, and with confidence that their [contest selections](#contest-selection) were [recorded](#record) correctly. It also refers to the usability of the setup and operation of voting equipment in the [polling place](#polling-place).


## <a name="usability-testing"></a>usability testing
[Testing](#test) that encompasses a range of methods that examine how users in the target audience actually interact with a system, in contrast to analytic techniques such as [usability](#usability) [inspection](#inspection).


## <a name="user-serviceable-failure"></a>user-serviceable failure
Functional [failure](#failure) that can be remedied by a troubleshooter or [election official](#election-official) using only knowledge found in voting equipment user documentation.


## <a name="valid-vote"></a>valid vote
See [contest option vote](#contest-option-vote).


## <a name="validation"></a>validation
Process of evaluating a system or [component](#component) during or at the end of the development process to determine whether it satisfies specified requirements.


## <a name="visual-format"></a>visual format
A display format in which information is displayed on screen or paper for perception using sight.


## <a name="vote"></a>vote
Indication of support for a particular [contest option](#contest-option).


## <a name="vote-center"></a>vote center
A physical location where [voters](#voter) from multiple [precincts](#precinct) may [cast](#cast) their [ballots](#ballot).


## <a name="vote-variation"></a>vote variation
Voting style or feature, including but not limited to the following: [approval voting](#approval-voting), Borda count, [cumulative voting](#cumulative-voting), [N-of-M voting](#N-of-M-voting), plurality voting, proportional voting, range voting, and [ranked choice voting](#ranked-choice-voting), [score voting](#score-voting).


## <a name="vote-by-mail"></a>vote-by-mail
Method of voting by which [eligible voters](#eligible-voters) are [mailed ballots](#absentee-ballot) and information packets by the local [election jurisdiction](#election-jurisdiction). [Voters](#voter) may be able to return their [marked ballots](#marked-ballot) by mail, bring them to an election office, or drop them off in secure drop boxes.


Synonyms: `VBM`, `all-mail voting`, `mail voting`, `postal voting`

## <a name="vote-capture-device"></a>vote-capture device
Component of a voting system that captures and/or counts voter selections from paper or electronic ballots.  Vote-capture devices may or may not be directly voter-facing; voter-facing vote-capture devices include ballot marking devices and voter-facing scanners, while non-voter-facing vote-capture devices include batch-fed scanners.


## <a name="voter"></a>voter
Person permitted to [cast](#cast) a [ballot](#ballot).


## <a name="voter-intent"></a>voter intent
A cognitive construct, formed by the [voter](#voter), that they attempt to express through actions taken to mark, verify, and [cast](#cast) the issued [ballot](#ballot).


## <a name="voter-intent-standard"></a>voter intent standard
A [standard](#standard) for counting ballots that aims to ensure that [ballots](#ballot) are counted in accordance with the goals of the [voter](#voter), using written rules for both human processes and machine algorithms to ensure that all ballots marked in a similar way are counted in the same way.


## <a name="voter-verifiable"></a>voter verifiable
A [voting system](#voting-system) feature that provides the [voter](#voter) an opportunity to verify that their [contest selections](#contest-selection) are being [recorded](#record) correctly before the [ballot](#ballot) is [cast](#cast).


## <a name="voter-verifiable-paper-audit-trail"></a>voter verifiable paper audit trail
A paper document that the voter can review before officially [casting](#cast) their [ballot](#ballot).


Synonyms: `VVPAT`

## <a name="voter-facing-scanner"></a>voter-facing scanner
An electronic [voting device](#voting-device) that:
 - accepts hand-marked or BMD-produced [paper ballots](#paper-ballot) one sheet at a time;
 - is usually used for [in-person voting](#in-person-voting);
 - permits [election workers](#election-worker) to open and close the [polls](#polling-place);
 - scans a [ballot](#ballot) and rejects it if either unreadable or un-processable;
 - detects, interprets and validates [contest selections](#contest-selection);
 - notifies the [voter](#voter) of voting exceptions (such as [undervotes](#undervote) or [overvotes](#overvote)) or unreadable marks;
 - stores accepted ballots in a secure container; sorts or otherwise marks ballots or [ballot images](#ballot-image) that need subsequent human review; and
 - [tabulates](#tabulate) and [reports](#report) [contest](#contest) results after polls are closed.  

 This unit was previously referred to as [precinct count](#precinct-count) optical scanner or PCOS.


Synonyms: `PCOS`, `precinct-count optical scanner`

## <a name="voting-device"></a>voting device
[Device](#device) that is part of the [voting system](#voting-system).


## <a name="voting-process"></a>voting process
Entire array of procedures, people, resources, equipment, and locations associated with conducting [elections](#election).


## <a name="voting-session"></a>voting session
A collection of activities including [ballot](#ballot) issuance, [voter](#voter) interaction with the [vote-capture device](#vote-capture-device), voting, verification, and casting.


## <a name="voting-station"></a>voting station
The location within a [polling place](#polling-place) where [voters](#voter) may [record](#record) their [votes](#vote). A voting station includes the area, location, booth, or enclosure where voting takes place.


## <a name="voting-system"></a>voting system
Equipment (including [hardware](#hardware), [firmware](#firmware), and software), materials, and documentation used to:
 1. define elections and [ballot styles](#ballot-style),
 2. configure voting equipment,
 3. identify and validate voting equipment configurations,
 4. perform logic and accuracy [tests](#test),
 5. activate [ballots](#ballot)for voters,
 6. record [votes](#vote) cast by voters,
 7. [count](#tabulate) votes,
 8. label ballots needing special treatment,
 9. generate [reports](#report),
 10. export election data includng election results,
 11. archive election data, and
 12. and produce [records](#record) in support of audits.


## <a name="voting-system-software"></a>voting system software
The executable code and associated configuration files needed for the proper operation of the [voting system](#voting-system).


## <a name="voting-system-test-lab"></a>voting system test lab
Privately owned testing laboratories that [test](#test) [voting systems](#voting-system) (and other [election systems](#election-system)) for [conformance](#conformance) to the Voluntary Voting System Guidelines (VVSG) or to other requirements, including individual state requirements. VSTLs are periodically reviewed for conformance to National Voluntary Laboratory Accreditation Program (NVLAP) administered by the National Institute for Standards and Technology (NIST).


Synonyms: `VSTL`

## <a name="white-box-testing"></a>white box testing
[Testing](#test) based on an analysis of the internal structure of the [component](#component) or system.


## <a name="Wi-Fi"></a>Wi-Fi
A [wireless](#wireless) networking technology that uses radio waves to provide high-speed Internet network connections.


## <a name="Wide-area-network"></a>Wide area network
A network that connects computers across metropolitan, regional, and national boundaries. The internet is an example of a WAN.


Synonyms: `WAN`

## <a name="wireless"></a>wireless
Connectivity using electro-magnetic waves instead of wire connections.


## <a name="write-in-option"></a>write-in option
A type of [contest option](#contest-option) that allows a [voter](#voter) to specify a [candidate](#candidate), usually not already listed as a contest option. Depending on [election jurisdiction](#election-jurisdiction) rules, in some cases only previously approved names will be considered as valid write-in [contest selections](#contest-selection).


## <a name="zero-report"></a>zero report
A [tabulation report](#tabulation-report) produced at the opening of [polls](#polling-place) to check that there are no stored [votes](#vote).
