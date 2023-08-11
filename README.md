# Open-Wordpress-
owner: sammyfilly<openworkspace@gmail.com
Home
Search
Search
Acronym helper

☰ Menu
Home
GNSO Preliminary Issues Report Policy Issues relating to IDN at the top-level
Translate

English French German Italian Portuguese Russian Spanish 


GNSO Preliminary Issues Report Policy Issues relating to IDN at the top-level
Last Updated:31 August 2009
Date
28 May 2006
Table of contents Page

A. Summary

B. Objective

C. Background

D. Issues

E. Recommendations

F. References

A. Summary

As requested by the GNSO Council at its meeting on 2 December 2005 and during subsequent discussions, in particular during the ICANN meeting in Wellington (25 — 31 March, 2006), this document sets out policy issues involved with the potential introduction of IDNs into the root zone of the DNS, provides relevant references, and suggests how to proceed. The issue areas are related to the issues identified in the ongoing policy development process on introduction of new gTLDs.

It is recommended that the GNSO launch a focused policy development process, in close consultation with the ccNSO and the broader ICANN community including the Government Advisory Committee (on the public policy aspects). The recommended first step in this process is that a specifically appointed group from the GNSO and the ccNSO Councils prioritize among the issues, select issues to address, and propose how to address them.

B. Objective

This report is designed to give the GNSO Council the information necessary to make a decision about whether to proceed with a policy development process on policy aspects related to the introduction of IDNs at the root. It should be read in conjunction with the Background Report on Internationalized Domain Names already prepared.

As agreed during discussions in Wellington, the intention is to establish a full picture of issues that need to be dealt with before deployment of IDN TLDs can take place. It follows that the issues listed in this report are of a broad nature, reaching beyond the remit of the GNSO and calling for necessary expert advice from other ICANN entities such as the ccNSO, the GAC, and the President's Advisory Committee for IDNs.

The GNSO Guidelines for Issues Reports have been used to frame this document. In particular, the Issues Report describes the key issues, provides relevant background and links, and recommends how to proceed.

C. Background

Technical tests of two approaches to the insertion of internationalized domain name (IDN) labels into the root zone of the DNS are currently being developed within the ICANN President's Advisory Committee that has been established to discuss key IDN implementation issues. The intention to perform the tests along with a timeline was publicly announced on 14 March 2006, see http://www.icann.org/announc ements/announcement-14mar06.htm

The outcome of the technical tests will provide information to address and inform policy questions that need to be addressed. The tests will include the insertion of IDN labels into the root zone of the DNS by the following two approaches:

DNAME records — this approach provides an alias designation for an entire top-level domain by mapping a new top-level domain onto one that already exists. For an existing TLD, this corresponds to the use of a punycode1 string to provide an internationalized alias designation for that TLD using a DNAME record in the root zone.

NS-records — this approach permits the insertion of an internationalized label (in punycode) in the root zone without the duplication of a pre-existing sub domain structure.

These two approaches are not mutually exclusive. Accordingly, if both are technically feasible, one of these approaches will not preclude the use of the other, pending policy considerations. DNAME records imply a situation where the operator of an existing TLD would map it into some other script equivalent, either synonymous to or a transliteration of the original TLD. NS records allow the creation of a new TLD that can be proposed by any entity regardless of whether it is currently operating a top-level domain or not.

While recognizing that it would be premature to anticipate the outcome of these tests, discussions have emerged in parallel on how to address related policy issues. The GNSO has requested an issues report to this end. This issues report should be read with the understanding that any outcome of ongoing policy issue discussions would be conditional upon the viability of necessary technical solutions. A key background for this issues report is the GNSO Council resolution of 2 December 2005:

"WHEREAS, the GNSO Council recognises that one of the goals of ICANN is to increase the internationalisation of the domain name space.

WHEREAS, the GNSO Council wishes to liaise closely with the ccNSO with respect to the issue of localised IDN equivalents of existing gTLDs and ccTLDs, and for the purpose of jointly requesting an issues report

The GNSO Council requests that the staff produce an issues report on the policy issues associated with creating internationalised equivalents of existing gTLDs, and second level domains within existing gTLDs.

The GNSO also requests that the staff liaise with the ccNSO to ensure that the policy issues associated with internationalised versions of the existing ccTLDs can also be considered."

Since this resolution was adopted, discussions within the GNSO Council and with other ICANN entities, in particular during the ICANN meeting in Wellington (25 — 31 March, 2006), have shown a need to frame the issue areas more broadly than originally specified in the resolution, in order to get a proper overview. During the Wellington meetings, it was also proposed to form a joint working group for IDN matters, consisting of members of the GNSO and ccNSO Councils.

During these discussions, the need to connect to the ongoing policy development process for new gTLDs was also highlighted, with a view to map the IDN-related issues to the issue areas already identified in the ongoing PDP for new gTLDs, notably selection criteria, allocation methods and contractual conditions.

Some guiding principles also emerged during these discussions, in particular the necessity to focus on user experience, user expectations and user needs with respect to timeliness. Also, in view of a timely introduction, the priority for the next steps should be to identify the issues to be worked on first, as well as who should be involved in addressing each issue, to allow the initial introduction of IDNs.

The Issues Report has been drafted based on these discussions and on a precursor to the Issues Report drafted as a discussion paper and introduced at the Wellington meeting.

D. Policy Issues

During the discussions in Wellington, possible scenarios were identified as a starting point for analyzing the issues involved:

a) A gTLD registry operator wishes to introduce an IDN based string that relates to the existing gTLD.

b) A ccTLD registry operator wishes to introduce an IDN based string that relates to the existing ccTLD.

c) A party may wish to introduce an IDN based string that relates to a gTLD, in competition with the gTLD registry operator.

d) A party may wish to introduce an IDN based string that relates to a ccTLD in competition with the ccTLD.

e) A party wishes to introduce a new IDN string with no relationship to an existing TLD.

These scenarios may need individual consideration and may imply different issues and different preferred solutions. With a general presumption that an introduction of IDNs at the root is feasible, potential policy issues are listed in question form below. Some of these issues relate only to certain scenarios above while others relate to all.

As mentioned previously, guiding principles for assessing the issues would include achieving timely benefit for Internet users, ensuring that user expectations are met and providing a good user experience. Issues are listed below related to the identified issue areas of the ongoing policy development process regarding new gTLD, in order to connect to this process. This mapping is not stringent, though, as many issues relate to more than one of these areas.

Issues of relevance for selection criteria

Does the operation of an IDN TLD registry require particular additional competences that should be reflected in selection criteria?

In how far is it essential to safeguard against business failure of new IDN TLDs? Do such risks for a new IDN TLD differ from those involved in a new TLD in general?

How should the choice of the IDN string or strings be governed? How would the approaches for gTLDs and for ccTLDs differ?

Is it from a policy standpoint advisable to create internationalized equivalents of existing TLDs? How could an introduction of internationalized equivalents of existing TLDs best promote competition and choice for end-users?

What selection and approval processes should apply for translation and/or transliteration of an existing <.tld> to its script equivalent(s) <.idn-tld>? Should any transliteration be phonetic (= transcription) or definitional/literal? Should a registry be able to determine its own equivalent(s), subject to an approval process involving input from the community, including governments? How should public policy aspects be reflected in such an approval process?

Should there be a limit on the number of IDN top-level labels per existing TLD? If so, how many IDN strings should be allowed per existing TLD? For ccTLDs, should such a limit be related to the number of official languages or scripts used within the respective country?

Should entities other than the existing TLD registry be entitled to run an IDN equivalent or equivalents of this TLD? If so, under what policies should the 'new' registry manage the <.idn-tld>? Are there special considerations required in this regard concerning TLDs with eligibility requirements?

Should the IDN based string relate to an official language within the country of the ccTLD? In cases when a language can be represented in multiple scripts, should each script be entitled to a separate IDN based string?

What is the accepted representation of a country name in non-Latin scripts? As ISO 3166 provides for translations of its labels into other scripts, what status should be given to these translations regarding IDN based strings? Should there be a requirement that any party aspiring to run an IDN version of a ccTLD must be located within the geographic territory associated with the ccTLD?

What considerations need to be made for languages and scripts used across multiple countries?

What are the advantages and drawbacks of having a TLD (<.tld>) and its internationalized equivalent (<.idn-tld>) in the same TLD or in two different TLDs?

In particular, is there a policy preference to have domain names under <.tld> and <.idn-tld> resolve to the same website or to different sites?

Ancillary aspects are whether <idn-domain>.<idn-tld> should be the same as <idn-domain>.<tld>, whether the registrant of <domain>.<tld> also should have <domain>.<idn-tld> and similar aspects regarding combinations with <idn-domain>.<tld> and <idn-domain>.<idn-tld>?

Would any or both of the two approaches under consideration for technical tests lead to overall satisfactory results from a policy perspective?

How can any risks for end user confusion best be counteracted?

Issues of relevance for allocation methods

If more than one party apply for the same IDN top-level label, on what grounds should a single applicant be selected? Similarly, how to select between more than one party that apply for different IDN top-level labels but with identical purposes?

How should conflicts between a proposed IDN top-level label and a trademark be resolved? Does a specific dispute resolution mechanism need to be put in place to resolve such conflicts?

In what order should applications for IDN top-level labels be handled in case of limited resources?

Issues of relevance for contractual conditions

What particular contractual provisions are required for an <.idn-tld> in addition to those normally required for any <.tld>? How could IETF IDN standards and ICANN's IDN Guidelines best be incorporated in the contractual conditions?

To what extent are current established policies adequate for IDNs? Are modifications of the existing UDRP required to address disputes concerning IDN labels? Are modifications needed to facilitate usability of WHOIS information for end-users with different scripts?

Provided that an internationalized equivalent of a TLD exists as <idn-tld> in some script, should there be a policy for what script(s) may be used at the second level, such as <idn-domain>.<idn-tld>? In other words, should the script used on the second level match the script used in top-level? Given that, with specific exceptions, mixing of scripts is prohibited on the second level, should the same rule apply to the top-level?

Should a registrant in <.tld> have a prior right to register in the IDN version <.idn-tld>? Would current domain name holders feel that they are forced to register in the IDN equivalent for brand protection? Does an intellectual property rights holder in one or more jurisdictions have a prior right to register in an IDN version?

What rules should govern timing and sequencing of the launch of IDN top-level domains? Is there a need for sunrise periods? Is there a need for concurrent launch of multiple IDN top-level domains for fair competition reasons?

Other aspects

The above examples of issue areas and aspects are not exhaustive. There are certainly other IDN aspects to consider that may affect policy preferences, like email interoperability, browser appearance of various identifiers etc. As an example; even though ASCII encodings of IDNs may be introduced into the domain name strings — there are still issues in using such domain names in email and websites.

E. Recommendations

It is recommended that the GNSO launch a policy development process on the issues outlined in the 2 December 2005 resolution, as expanded upon during discussions in Wellington, in cooperation with the ccNSO (on the ccTLD aspects) and the Government Advisory Committee (on the public policy aspects), as well as in close consultation with the broader ICANN community.

Proposed approach and next steps

1. Based on existing work and this report, with a positive presumption that an introduction of IDNs in the root zone of the DNS is feasible, the GNSO and the ccNSO will jointly examine and complete the inventory of policy issues involved, requesting advice from the GAC and the President's Advisory Committee for IDNs as appropriate.

2. In view of a timely launch of IDNs in the root, the GNSO and the ccNSO will jointly prioritize the issues, selecting those essential for a launch, resolve how to address them and by whom.

3. The GNSO and the ccNSO, individually and/or jointly as agreed in 2 above, will examine the issues and propose solutions, in particular relating to the issue areas identified in the PDP for new gTLDs, completing the outcome of the latter with the special considerations called for due to the introduction of IDNs in the root.

4. Regarding consultation of the ccNSO during a GNSO policy development process, there appear to be two options:

Regular, informal consultations between the ccNSO and GNSO during the GNSO PDP, without a formal ccNSO PDP, or

The ccNSO also launches a formal PDP to run concurrently with that of the GNSO, and with both PDPs accommodating mutual consultation by way of mutual liaisons.

ICANN staff recommends that either option should take as its starting point the joint ccNSO/GNSO working group on IDN. It is recommended that this group be tasked with prioritizing the issues, proposing a selection of issues to address and how to address them in view of the options above.

5. ICANN staff also recommends that the GNSO Council take as its starting point the joint ccNSO/GNSO working group when the Council considers whether a PDP be performed through a task force, or some other mechanism. .

F. References

Punycode, an introduction

Punycode is a bootstring encoding that will convert the local characters in a domain name into the limited character set that is supported by the DNS. The encoding is applied to each component of a domain name and a prefix 'xn--' is added to the translated Punycode string. For example, the first component of the domain name rødgrødmedfløde.dk becomes 'xn--rdgrdmedflde-vjbdg' , and the domain will be represented as xn--rdgrdmedflde-vjbdg.dk. This kind of encoding would apply for top-level labels with characters from non-Latin scripts.

ICANN's IDN Implementation Guidelines, available at http://www.icann.org/topic s/idn/implementation-guidelines.htm

Technical test announcement, available at http://www.icann.org/announc ements/announcement-14mar06.htm

IDN Background paper, available at

http://gnso.icann .org/mailing-lists/archives/council/msg01479.html

Selected IETF documents, RFCs 3454, 3490, 3491, and 3492

New gTLD PDP, progress reflected on the GNSO website at http://gnso.icann.org/issues/new-gtlds/

1 A short introduction to Punycode is provided in the References section.







Comments concerning the layout, construction and functionality of this site should be sent to webmaster [at] gnso.icann.org
© 2018 The Internet Corporation for Assigned Names and Numbers. All rights reserved    Privacy Policy  Terms of Service   Cookies Policy
