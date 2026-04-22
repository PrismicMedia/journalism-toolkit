# Legal Disclaimer, Terms of Use, and Limitation of Liability

**Document version:** 2.0
**Effective date:** 23 April 2026
**Governing law:** Republic of India
**Applies to:** the software, plugin, agents, commands, skills, prompts, scripts, configuration files, documentation, and any derivative thereof contained in, or distributed from, the repository located at `https://github.com/swarochish/journalism-toolkit` (the **"Software"**), its forks, mirrors, archives, and any copy in any medium.

**Author / Licensor:** Swarochish Chekuri (the **"Author"**).
**You / the User:** any natural or juristic person who downloads, clones, forks, installs, loads, executes, integrates, invokes, calls, studies, modifies, or otherwise deals with the Software (the **"User"**).

This document forms part of the licence terms of the Software. It operates **in addition to, and not in substitution of**, the MIT License distributed with the Software. Where any provision of this document conflicts with the MIT License on a point the MIT License does not address, this document prevails. Where the MIT License is silent, this document fills the gap. Nothing here purports to reduce any right the User has under the MIT License.

**By downloading, cloning, forking, installing, loading, executing, integrating, or otherwise using the Software — in whole or in part, directly or indirectly, via any interface — the User irrevocably accepts every clause of this document. If the User does not accept any clause, the User must not use the Software and must destroy all copies in the User's possession or control.**

---

## Table of Contents

1. [Nature of the Software](#1-nature-of-the-software)
2. [No Professional Advice](#2-no-professional-advice)
3. [AI / LLM Output — Hallucination & Fabrication Warning](#3-ai--llm-output--hallucination--fabrication-warning)
4. [User Responsibility and Mandatory Verification Duty](#4-user-responsibility-and-mandatory-verification-duty)
5. [Prohibited Uses](#5-prohibited-uses)
   - [5A. Enumerated Prohibitions](#5a-enumerated-prohibitions)
   - [5B. Residual Catch-all Compliance Obligation](#5b-residual-catch-all-compliance-obligation)
6. [Digital Personal Data Protection Act 2023 — Posture](#6-digital-personal-data-protection-act-2023--posture)
7. [Intermediary Posture and IT Act 2000 Section 79](#7-intermediary-posture-and-it-act-2000-section-79)
8. [Copyright, Trademarks, and Third-Party Tools](#8-copyright-trademarks-and-third-party-tools)
9. [Contempt, Sub-Judice Matters, and Sealed Proceedings](#9-contempt-sub-judice-matters-and-sealed-proceedings)
10. [National Security, Defence, Intelligence, and Official Secrets Carve-out](#10-national-security-defence-intelligence-and-official-secrets-carve-out)
11. [Indemnification by the User](#11-indemnification-by-the-user)
12. [Limitation of Liability](#12-limitation-of-liability)
13. [Governing Law, Jurisdiction, and Forum](#13-governing-law-jurisdiction-and-forum)
14. [Severability, No Waiver, Entire Agreement, Amendment](#14-severability-no-waiver-entire-agreement-amendment)

---

## 1. Nature of the Software

**1.1** The Software is an **educational and analytical framework** consisting of prompt templates, agent definitions, slash commands, skills, orchestration logic, and documentation intended for use within the Claude Code environment (or any compatible agentic AI host). It is offered **as a framework for research, pedagogy, and private experimentation**. It is not a news publication, a journalism product, a media service, a press undertaking, a fact-checking service, a forensic laboratory, a credit-reference service, a background-verification service, a litigation-support service, or any form of regulated media or investigative offering.

**1.2** The Software, by itself, **does not collect, generate, transmit, publish, broadcast, or host any content about any identifiable person**. All content referencing identifiable persons, entities, or events is generated at runtime by a large language model ("**LLM**") under the sole control, direction, and instruction of the User. The User is the sole originator, commissioner, publisher, and disseminator of any such content.

**1.3** The Author is **not a "journalist," "news publisher," "news aggregator," "intermediary," "social media intermediary," or "significant social media intermediary"** within the meaning of the Information Technology Act 2000, the Information Technology (Intermediary Guidelines and Digital Media Ethics Code) Rules 2021, the Press and Registration of Periodicals Act 2023, the Press Council Act 1978, or any cognate statute, merely by reason of distributing the Software under an open-source licence. No editorial, curatorial, or publisher relationship exists between the Author and the User.

> **Statutory references:** Information Technology Act 2000, §§ 2(w), 79; Information Technology (Intermediary Guidelines and Digital Media Ethics Code) Rules 2021; Press and Registration of Periodicals Act 2023; Press Council Act 1978; Digital Personal Data Protection Act 2023, § 2(i).

---

## 2. No Professional Advice

**2.1** The Software and any output produced through it **do not constitute legal advice, journalistic advice, editorial judgement, forensic-expert opinion, financial advice, medical advice, psychological advice, investment advice, tax advice, or any other professional counsel**. The Author is not engaged in the practice of law, journalism, forensic science, or any other regulated profession through the distribution of the Software.

**2.2** No attorney–client, journalist–source, confessor–penitent, or fiduciary relationship is created by the User's use of the Software. Any output of the Software that resembles legal analysis, forensic conclusion, or expert opinion is **the product of a stochastic language model** and carries no evidentiary weight.

**2.3** For any matter with legal, safety, reputational, financial, or health consequences, the User must consult a qualified human professional duly licensed in the relevant jurisdiction before acting.

> **Statutory references:** Advocates Act 1961, §§ 29, 33 (practice of law reserved to enrolled advocates); Bharatiya Sakshya Adhiniyam 2023, § 39 (expert opinion, previously Indian Evidence Act 1872 § 45); Consumer Protection Act 2019 (professional-service standards).

---

## 3. AI / LLM Output — Hallucination & Fabrication Warning

**3.1 Critical warning.** The Software operates by issuing instructions to a large language model. Large language models are known to produce output that is **false, fabricated, invented, hallucinated, materially misleading, defamatory per se, or internally inconsistent**, even when prompted with accurate inputs and even when operating within the Software's agent structure. This limitation is intrinsic to the present state of the technology and is not a defect of the Software.

**3.2 Non-exhaustive examples of LLM failure modes** the User must anticipate:

- **Fabricated factual allegations** against named persons or entities (e.g., a purported bribe, affair, criminal conviction, disease, affiliation, or financial transaction that never occurred).
- **Fabricated attribution** — quotations, statements, tweets, emails, or documents falsely attributed to a named person.
- **Fabricated financial links** — a false assertion that Person A funded Person B, or that Company X holds a stake in Company Y, where no such relationship exists.
- **Fabricated network maps** — coordinated-inauthentic-behaviour clusters, bot networks, or troll armies that are statistical artefacts rather than real coordination.
- **Fabricated deepfake verdicts** — the tool may wrongly classify authentic media as manipulated, or vice versa.
- **Fabricated sources** — citations to non-existent reports, non-existent case law, non-existent URLs, or non-existent authors.
- **Fabricated sincerity scores** — numerical scores (e.g., "grassroots sincerity: 12/100") produced by a stochastic process with no scientific validity and no peer-reviewed basis.
- **Fabricated translations** — purported translations of foreign-language content that misstate the original meaning.
- **Fabricated timelines** — events placed at dates that differ from the historical record.

**3.3** Any such output is **not a factual claim by the Author, the Software, or any agent, command, skill, or orchestrator** contained in the repository. It is a conditional-probability string produced by a third-party language model in response to the User's prompt. The User **must** treat every identifying factual claim as unverified and as probably false until independently corroborated by at least two contemporaneous, independent, human-sourced, non-LLM-generated references.

**3.4** The Software **does not** endorse, ratify, adopt, validate, or vouch for any output it produces or assists in producing. The presence of confident language, numerical precision, source-grade labels (e.g., "Tier 1 verified"), or structured report formatting in any output is purely stylistic and carries no probative value whatsoever.

> **Statutory references:** Bharatiya Nyaya Sanhita 2023, §§ 356 (defamation), 353 (statements conducing to public mischief); Information Technology Act 2000, §§ 66C (identity theft), 66D (cheating by personation using computer resource), 66E (violation of privacy); common-law publisher liability as explicated in *Subramanian Swamy v Union of India* (2016) 7 SCC 221.

---

## 4. User Responsibility and Mandatory Verification Duty

**4.1** The User is the **sole publisher, commissioner, and originator** of any output generated with the assistance of the Software that is stored, forwarded, posted, broadcast, printed, shared, hosted, transmitted, or otherwise communicated to any third party or to the public. The User bears full legal, ethical, reputational, professional, and financial responsibility for every such output without exception.

**4.2** Before any such publication, forwarding, or use for a decision affecting a third party, the User **shall**:

(a) independently verify every identifying factual claim through **at least two contemporaneous, independent, human-sourced, non-LLM-generated references**;
(b) obtain, where the matter concerns an identifiable living person, a meaningful right of reply from that person and record the response fairly;
(c) obtain qualified legal review from an advocate duly enrolled under the Advocates Act 1961 (or equivalent jurisdiction) on defamation, privacy, contempt, copyright, and election-law exposure;
(d) comply with the editorial, ethical, and fact-checking standards of the User's employing or commissioning organisation, or, in the absence of such, the *Norms of Journalistic Conduct* issued by the Press Council of India;
(e) preserve, in an unalterable form, the full prompt history, model responses, and verification trail for a period of not less than seven years; and
(f) make and retain a contemporaneous, signed written record of the User's own conclusion that each such output is, to the User's personal knowledge after independent verification, true, fair, and in the public interest.

**4.3** The User acknowledges that failure to undertake the verification duty in clause 4.2 is **grossly negligent** and shall operate as a complete bar to any claim, contribution, indemnity, or relief sought from the Author in respect of any harm arising from the User's publication.

**4.4** Clauses 4.1–4.3 are cumulative with, and do not limit, any other statutory or common-law duty the User owes to any third party.

> **Statutory references:** *Shreya Singhal v Union of India* (2015) 5 SCC 1 (speaker/publisher liability); *Subramanian Swamy v Union of India* (2016) 7 SCC 221 (criminal defamation); *Justice K.S. Puttaswamy (Retd.) v Union of India* (2017) 10 SCC 1 (right to privacy); Press Council of India, Norms of Journalistic Conduct (updated edition).

---

## 5. Prohibited Uses

### 5A. Enumerated Prohibitions

The User shall **not** use the Software, any agent, command, skill, prompt, or output thereof, directly or indirectly, alone or in combination with any other instrument, for any of the following purposes:

**(a) Stalking, harassment, doxxing, and intimate-partner surveillance.** Compiling, publishing, or transmitting any dossier, profile, location record, contact graph, photograph, or behavioural analysis of any identifiable natural person without that person's free, specific, informed, unambiguous, and revocable consent, save where a recognised journalistic public-interest defence is available under Indian law and has been legally vetted in advance.

**(b) Targeting minors.** Any analysis, profiling, sincerity-scoring, bot-classification, or media-forensic operation directed at a natural person below the age of eighteen (18) years, save where the operation is strictly necessary for the safety or protection of that minor and is conducted under the supervision of a statutory child-protection authority.

**(c) Election interference.** Production or distribution of any material intended to influence, disrupt, or manipulate any election, referendum, by-election, or poll conducted under the Representation of the People Act 1951 or any cognate statute, including the publication of fabricated statements, deepfake audiovisual content, or coordinated-inauthentic-behaviour payloads referring to any candidate or party.

**(d) Private-person surveillance.** Use of bot-detection, grassroots-sincerity, author-history, technical-infrastructure, or financial-trail agents against any person who is not a voluntary, current, public-facing figure in relation to the matter under examination.

**(e) National-security-adjacent targets.** Any investigation, profiling, or analysis concerning (i) personnel, installations, operations, communications, or procurement of the Indian Armed Forces, Central Armed Police Forces, intelligence agencies, or atomic-energy installations; (ii) any matter covered by a classification under the Official Secrets Act 1923; (iii) any person or entity notified under the Unlawful Activities (Prevention) Act 1967; (iv) any matter subject to a national-security-related sealed-cover proceeding. See further clause 10.

**(f) Sub-judice reporting in breach of contempt law.** Publication of any material that prejudges, prejudices, or interferes with the fair trial of any civil or criminal proceeding pending before any court or tribunal in India. See further clause 9.

**(g) Credit, employment, housing, insurance, or analogous automated decision-making.** Any use of Software output as a factor in deciding, or as an input to any system that decides, the creditworthiness, employment suitability, tenancy, insurance eligibility, or admission of any identifiable person. The Software's output is not admissible in any such decision.

**(h) Securities-law-regulated decisions.** Use of any output — including financial-trail, ownership-mapping, or narrative-analysis output — as the basis for, or as a contributor to, any trading decision in any security listed on any recognised stock exchange, or as the basis for any public recommendation concerning any such security. Such use may attract liability under the SEBI (Prohibition of Insider Trading) Regulations 2015, the SEBI (Prohibition of Fraudulent and Unfair Trade Practices) Regulations 2003, and the SEBI (Research Analysts) Regulations 2014.

**(i) Attacks on the financial integrity of listed companies or public institutions.** Coordinated publication of unverified allegations calculated to move the price of a listed security, or to destabilise a scheduled commercial bank, public-sector undertaking, statutory body, or regulated entity.

**(j) Discrimination prohibited by the Constitution of India.** Any use that targets persons on the basis of religion, race, caste, sex, place of birth, language, or descent in a manner inconsistent with Articles 14, 15, 19, and 21 of the Constitution of India.

**(k) Creation of non-consensual intimate imagery or deepfake sexual content.** Absolutely prohibited. Generation, retention, study, or distribution for any purpose, including "detection research," is forbidden under this document and is an offence under the Information Technology Act 2000 and the Protection of Children from Sexual Offences Act 2012.

**(l) Impersonation.** Use of the Software to impersonate any journalist, publication, law-enforcement agency, regulator, court, or officer of the state.

**(m) Conspiracy or abetment.** Use of the Software in concert with any other person to commit any of the acts prohibited above, or to commit any offence under the Bharatiya Nyaya Sanhita 2023.

> **Statutory references:** Bharatiya Nyaya Sanhita 2023, §§ 61 (criminal conspiracy), 78 (stalking), 79 (insult to modesty), 152 (endangering sovereignty, unity and integrity of India), 197 (imputations, assertions prejudicial to national integration), 351–354 (criminal intimidation), 356 (defamation); Information Technology Act 2000, §§ 66C, 66D, 66E, 67, 67A, 67B (§ 66A having been struck down in *Shreya Singhal v Union of India* (2015) 5 SCC 1 and **not** relied upon); Protection of Children from Sexual Offences Act 2012; Unlawful Activities (Prevention) Act 1967; Official Secrets Act 1923; Representation of the People Act 1951, §§ 123, 125, 125A, 126; SEBI (Prohibition of Insider Trading) Regulations 2015; SEBI (Prohibition of Fraudulent and Unfair Trade Practices) Regulations 2003; Constitution of India, Articles 14, 15, 19, 21; Contempt of Courts Act 1971.

### 5B. Residual Catch-all Compliance Obligation

The enumeration in clause 5A is **illustrative, not exhaustive**. The User shall, at all times and at the User's own cost, comply with **every applicable law, rule, regulation, notification, guideline, licence condition, contractual obligation, code of conduct, and court order** (i) of the Republic of India, (ii) of any jurisdiction from which the User operates the Software, (iii) of any jurisdiction in which any output is received, published, forwarded, stored, or consumed, and (iv) of any platform on which any output is posted. The omission of any specific prohibition from clause 5A shall not be construed as consent, licence, permission, or safe-harbour for that conduct. Any conduct not expressly permitted by applicable law is, for the purposes of this document, prohibited.

---

## 6. Digital Personal Data Protection Act 2023 — Posture

**6.1** The Author **is not a Data Fiduciary, Data Processor, Significant Data Fiduciary, or Consent Manager** within the meaning of the Digital Personal Data Protection Act 2023 in respect of any personal data processed through the Software. The Author does not determine the purpose or means of any processing; the User alone does so by framing prompts and directing agents.

**6.2** Upon the User's first act of processing any personal data through or with the assistance of the Software, the User becomes, at law, the **Data Fiduciary** in respect of that processing. The User thereupon assumes every obligation of a Data Fiduciary under the Act, including but not limited to: lawful-basis establishment (§ 4); notice to the Data Principal (§ 5); consent management (§ 6); processing for legitimate uses (§ 7); general obligations (§ 8); children's data (§ 9); obligations in case of a personal-data breach (§ 8(6)); retention and erasure (§ 8(7)–(8)); rights of Data Principals (§§ 11–14); and compliance with any direction of the Data Protection Board (§§ 27–28).

**6.3** The User warrants that the User has a valid, lawful, and documentable basis under § 4 of the Act for every processing activity. The User shall not rely on the Software's framework, the Author, or any description in the repository as constituting or evidencing any such basis.

**6.4** The User shall not submit to the Software any personal data received through a pre-existing fiduciary, professional, medical, counselling, or legally privileged relationship except in strict accordance with the duty of confidentiality governing that relationship.

**6.5** The User shall bear, at the User's sole cost, any enquiry, notice, proceeding, penalty, or direction of the Data Protection Board of India arising from the User's processing. The User shall not implicate, name, or seek to implead the Author as a noticee, respondent, or co-party in any such proceeding.

> **Statutory references:** Digital Personal Data Protection Act 2023, §§ 2(i) (Data Fiduciary), 2(k) (Data Processor), 4 (grounds for processing), 5 (notice), 6 (consent), 7 (legitimate uses), 8 (general obligations), 9 (children), 11–14 (rights of Data Principals), 27–28 (Data Protection Board), 33 (penalties). Read with the Digital Personal Data Protection Rules 2025 (as notified).

---

## 7. Intermediary Posture and IT Act 2000 Section 79

**7.1** The repository is **source code distributed through a software-development platform**. It is not an "intermediary" for the purposes of the Information Technology Act 2000, and the Author is not an intermediary. No third-party content is received, hosted, transmitted, or published by the Software in the course of its ordinary operation; all such acts are performed, if at all, by the User directly through the User's own chosen LLM provider, hosting provider, publishing platform, or distribution channel.

**7.2** To the extent, if at all, that the Author is treated as an intermediary in relation to the repository itself (for example, the GitHub repository's README and documentation), the Author claims the benefit of the safe-harbour principles reflected in § 79 of the Information Technology Act 2000 and the Intermediary Guidelines Rules 2021, namely: (i) the Author does not initiate the transmission of any third-party content to which the Software is applied; (ii) the Author does not select the receiver of such content; (iii) the Author does not select or modify such content; and (iv) the Author observes the due-diligence obligations applicable to a non-significant intermediary.

**7.3** On receipt of a valid order from a court of competent jurisdiction or a notification under § 79(3)(b) of the Information Technology Act 2000 from the appropriate Government, the Author will act with expedition to comply, consistent with the principles laid down in *Shreya Singhal v Union of India* (2015) 5 SCC 1.

> **Statutory references:** Information Technology Act 2000, §§ 2(w), 79, 79(3)(b); Information Technology (Intermediary Guidelines and Digital Media Ethics Code) Rules 2021, Part II; *Shreya Singhal v Union of India* (2015) 5 SCC 1.

---

## 8. Copyright, Trademarks, and Third-Party Tools

**8.1** The Software's documentation names a number of third-party products, services, and APIs (by way of illustration only: GPTZero, DeepL, Sensity AI, MoviePy, Whisper, Plotly, Folium, and others). Such naming is **descriptive and illustrative only**. It does not constitute endorsement, partnership, certification, recommendation, or affiliation. All trademarks, service marks, and trade names are the property of their respective owners. The User shall independently procure, licence, and comply with the terms of service of every such third-party product before use.

**8.2** The Software does not itself copy, reproduce, or distribute any third-party copyrighted work. The User shall comply with the Copyright Act 1957 (and analogous foreign copyright law) in respect of every work the User processes through the Software, including by ensuring that any use qualifies under § 52 of the Copyright Act 1957 (fair dealing) or under a valid licence.

**8.3** Where any agent prompt refers to the use of a third-party API (for example, translation, deepfake-detection, or archival APIs), the User alone is responsible for key provisioning, quota, billing, rate-limit compliance, and the terms of service of the relevant provider.

> **Statutory references:** Copyright Act 1957, §§ 14, 51, 52, 63; Trade Marks Act 1999, §§ 29, 30.

---

## 9. Contempt, Sub-Judice Matters, and Sealed Proceedings

**9.1** The User shall not, using any output of the Software, publish or cause to be published any material that:

(a) prejudices, prejudges, or interferes with the fair trial of any civil or criminal proceeding pending before any court or tribunal in India;
(b) scandalises or tends to scandalise the authority of any court;
(c) breaches any order for in-camera proceedings, sealed-cover submissions, witness-protection directions, victim-anonymity directions, or gag orders;
(d) breaches any statutory protection of identity under the Protection of Children from Sexual Offences Act 2012 § 23, the Bharatiya Nyaya Sanhita 2023, or any analogous enactment protecting the identity of victims, witnesses, or informants;
(e) breaches the in-chambers confidentiality of arbitration proceedings under § 42A of the Arbitration and Conciliation Act 1996.

**9.2** The User shall obtain contemporaneous legal review in every case where the User publishes material referring to a pending proceeding.

> **Statutory references:** Contempt of Courts Act 1971, §§ 2(c), 3, 10; Arbitration and Conciliation Act 1996, § 42A; Protection of Children from Sexual Offences Act 2012, § 23; Bharatiya Nagarik Suraksha Sanhita 2023 (reporting restrictions, previously CrPC 1973 § 327).

---

## 10. National Security, Defence, Intelligence, and Official Secrets Carve-out

**10.1** The Software is **not licensed** for use against (i) personnel, installations, operations, communications, procurement, or vendors of the Indian Armed Forces, Central Armed Police Forces, or intelligence agencies; (ii) matters classified under the Official Secrets Act 1923; (iii) persons, groups, or organisations notified under the Unlawful Activities (Prevention) Act 1967; (iv) matters the subject of a national-security sealed-cover proceeding; or (v) atomic-energy installations.

**10.2** Where, notwithstanding clause 10.1, the User engages in any such use, the User does so entirely on the User's own account, at the User's own risk, and without any licence from the Author. Any resulting liability — including under the Official Secrets Act 1923, the Unlawful Activities (Prevention) Act 1967, the Atomic Energy Act 1962, the National Security Act 1980, or any analogous statute — rests exclusively with the User.

**10.3** Nothing in this document authorises any conduct that would amount to an offence under the Official Secrets Act 1923 or the Unlawful Activities (Prevention) Act 1967.

> **Statutory references:** Official Secrets Act 1923, §§ 3, 5; Unlawful Activities (Prevention) Act 1967; Atomic Energy Act 1962, §§ 18, 24; National Security Act 1980.

---

## 11. Indemnification by the User

**11.1** The User shall, at the User's own cost, **defend, indemnify, and hold harmless** the Author, the Author's family, heirs, legal representatives, co-authors, contributors, maintainers, reviewers, and agents (collectively, the **"Indemnitees"**), from and against any and all:

(a) claims, suits, complaints, First Information Reports, private complaints, legal notices, cease-and-desist letters, take-down notices, regulatory proceedings, administrative enquiries, DPDP Board proceedings, criminal investigations, civil actions, arbitration claims, income-tax or GST enquiries, and foreign-jurisdiction proceedings;
(b) damages, compensation, fines, penalties, confiscations, interest, and costs awarded or imposed;
(c) reasonable legal fees, advocate's fees, counsel's fees, senior counsel's fees, arbitrator's fees, travel, accommodation, document-production, and expert-witness costs actually incurred;
(d) reputational-repair, public-relations, and press-advisory costs reasonably incurred;
(e) settlement payments reasonably made with the Author's prior written consent (such consent not to be unreasonably withheld);

in each case **arising out of or in connection with**: (i) the User's use of the Software; (ii) any output generated with the assistance of the Software by, for, or on behalf of the User; (iii) any breach by the User of this document; (iv) any act or omission of the User constituting an offence or tort; or (v) any third-party claim premised on conduct attributable to the User.

**11.2** The User shall not settle any such claim, proceeding, or investigation in a manner that admits any liability, fault, or wrongdoing on the part of any Indemnitee, or that imposes any continuing obligation on any Indemnitee, without the Author's prior written consent.

**11.3** The Author reserves the right, at the Author's option and at the User's cost, to assume the exclusive defence and control of any matter otherwise subject to indemnification by the User. The User shall cooperate fully with any such defence.

**11.4** The indemnity in this clause 11 is in addition to, and not in substitution of, the "AS IS / NO WARRANTY / NO LIABILITY" provisions of the MIT License. It survives termination, revocation, or expiry of any licence to use the Software.

> **Statutory references:** Indian Contract Act 1872, §§ 124 (indemnity), 125 (rights of indemnity-holder); Code of Civil Procedure 1908, Order VIII-A.

---

## 12. Limitation of Liability

**12.1** To the maximum extent permitted by law, **no Indemnitee shall be liable** to the User or to any third party for any loss, damage, cost, expense, penalty, claim, or injury of any nature — direct, indirect, incidental, consequential, special, exemplary, punitive, reputational, financial, criminal, regulatory, or otherwise — arising out of or in connection with the Software, its use, its availability, its output, its unavailability, any reliance placed on any output, or any breach or alleged breach of this document, whether framed in contract, tort (including negligence), statute, equity, restitution, or otherwise, and whether or not the possibility of such loss was foreseeable or was notified to the Indemnitee.

**12.2** Without prejudice to the generality of clause 12.1, no Indemnitee shall be liable for:

(a) **any loss of reputation, standing, professional licence, employment, business opportunity, contract, or revenue** suffered by the User or any third party;
(b) **any criminal prosecution, conviction, sentence, detention, or penalty** imposed on the User or any third party;
(c) **any civil liability for defamation, breach of privacy, intentional infliction of emotional distress, or breach of confidence** attaching to the User or any third party;
(d) **any regulatory penalty** imposed by the Data Protection Board of India, the Securities and Exchange Board of India, the Competition Commission of India, the Telecom Regulatory Authority of India, the Press Council of India, the Election Commission of India, the Reserve Bank of India, or any foreign regulator;
(e) **any tax, duty, cess, or equalisation levy** assessed on the User or any third party;
(f) **any loss of data, loss of goodwill, or interruption of business** suffered by the User.

**12.3** Where the law of any jurisdiction does not permit the exclusion or limitation of certain liabilities, the aggregate liability of all Indemnitees, cumulatively, in respect of all claims by the User under or in connection with this document and the Software, whether in one claim or in a series of related claims, shall not exceed **Indian Rupees One Hundred (INR 100.00)**, being the nominal consideration acknowledged to have been received in respect of the Software.

**12.4** This clause 12 operates cumulatively with, and does not in any way reduce, the "AS IS / NO WARRANTY / NO LIABILITY" provisions of the MIT License and with every other limitation and exclusion in this document.

> **Statutory references:** Indian Contract Act 1872, §§ 73, 74 (damages); MIT License, paragraphs 2 (no warranty) and 3 (no liability).

---

## 13. Governing Law, Jurisdiction, and Forum

**13.1 Governing law.** This document, the Software, the User's use of the Software, the licence granted to the User, and any non-contractual obligation arising out of or in connection with them, shall be governed by, and construed in accordance with, the **laws of the Republic of India**, without regard to conflict-of-laws principles.

**13.2 Exclusive forum — civil, contractual, tortious, and regulatory proceedings.** Subject to clause 13.3 below, the User and the Author irrevocably agree that the **competent courts at Hyderabad, Telangana, India** shall have **exclusive jurisdiction** to hear and determine any dispute, controversy, claim, suit, action, enquiry, complaint, or proceeding arising out of or in connection with this document, the Software, or the User's use of the Software, including without limitation: (i) any civil suit for damages, injunction, specific performance, declaration, or account; (ii) any proceeding for breach of contract; (iii) any tortious claim (including defamation, breach of privacy, or intentional infliction of harm) arising as between the User and the Author; (iv) any proceeding under the Digital Personal Data Protection Act 2023 to the extent forum is electable by the parties; (v) any proceeding under the Consumer Protection Act 2019 to the extent forum is electable by the consumer; and (vi) any proceeding in aid of, or for enforcement of, an arbitral award rendered in accordance with this document.

**13.3 Criminal-matter carve-out.** The User and the Author acknowledge that the jurisdiction of criminal courts in India is fixed by statute (the Bharatiya Nagarik Suraksha Sanhita 2023 and cognate enactments) and cannot be waived or conferred by agreement. Clause 13.2 shall therefore not apply to the jurisdiction of any criminal court. The User nonetheless acknowledges, for the avoidance of doubt, that any offence alleged to have been committed through or with the assistance of the Software is committed by the User and not by the Author, and the User undertakes not to name, implicate, or seek to implead the Author as an accused, co-accused, abetter, or conspirator in any such proceeding.

**13.4 Service of process.** The User consents to service of process at the User's GitHub-registered email address, the email address used to clone, pull, or push to the repository, or any email address the User has supplied to the Author. Service so effected shall be deemed good service notwithstanding the absence of physical delivery.

**13.5 No forum-shopping.** The User undertakes not to initiate, support, or finance any proceeding against any Indemnitee in any forum other than the exclusive forum identified in clause 13.2 (subject to clause 13.3). Any such proceeding shall, in addition to any other remedy, sound in damages against the User for breach of this clause.

> **Statutory references:** Code of Civil Procedure 1908, §§ 9, 20; Bharatiya Nagarik Suraksha Sanhita 2023 (criminal jurisdiction, previously CrPC 1973 §§ 177–189); Digital Personal Data Protection Act 2023, § 28; Consumer Protection Act 2019, § 34; Arbitration and Conciliation Act 1996, § 20 (place of arbitration).

---

## 14. Severability, No Waiver, Entire Agreement, Amendment

**14.1 Severability.** If any clause, sub-clause, sentence, phrase, or word of this document is held by any court, tribunal, arbitrator, or regulator of competent jurisdiction to be invalid, illegal, void, unenforceable, or contrary to public policy, that holding shall not affect the validity, legality, or enforceability of the remainder of this document, which shall continue in full force and effect. The invalid portion shall be deemed replaced by a valid provision that most closely reflects the original intent of the parties.

**14.2 No waiver.** No failure or delay by the Author in exercising any right, power, or remedy under this document shall operate as a waiver of that right, power, or remedy. No single or partial exercise of any right, power, or remedy shall preclude any further or other exercise of it.

**14.3 Entire agreement.** This document, together with the MIT License distributed with the Software, constitutes the entire agreement between the User and the Author in respect of the Software and supersedes all prior and contemporaneous oral or written understandings, proposals, or representations. The User acknowledges that the User has not relied on any statement, representation, warranty, or assurance not expressly set out in this document or in the MIT License.

**14.4 Amendment.** The Author may update this document from time to time by publishing a revised version to the repository. Each such revision bears an effective date. The User's continued use of the Software after the effective date of a revised version constitutes acceptance of the revised version. A User who does not accept a revised version must cease all use of the Software and destroy all copies in the User's possession or control.

**14.5 Language.** This document is executed in the English language. Any translation is for convenience only; in case of conflict, the English version prevails.

**14.6 No partnership or agency.** Nothing in this document shall be construed as creating any partnership, joint venture, agency, employment, fiduciary, or franchise relationship between the User and any Indemnitee.

**14.7 Third-party beneficiaries.** The Indemnitees other than the Author (namely, the Author's family, heirs, legal representatives, co-authors, contributors, maintainers, reviewers, and agents) are intended third-party beneficiaries of clauses 11 and 12 and may enforce those clauses in their own name.

**14.8 Assignment.** The Author may assign the benefit of this document. The User may not assign the burden of this document without the Author's prior written consent.

---

## Contact

Good-faith legal notices may be addressed to the Author via the GitHub repository's issue tracker or through the contact channel listed in the repository's `README.md`. Service of legal process is governed by clause 13.4.

---

*End of document. Total 14 clauses. Effective from 23 April 2026 until superseded by a later-dated version of this document published in the repository.*
