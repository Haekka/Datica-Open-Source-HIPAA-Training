
Title:
Lesson 9 | Administrative Simplification
---

Lesson Notes: What is administrative simplification under HIPAA?
:dart: The intent of administrative simplification is to make data exchange easier.
:dart: The rules define a set of data exchange coding standards.

---

Lesson Content:

This area of HIPAA relates to the accepted coding for data exchanged in healthcare. The transactions this applies to are financial-related (claims, eligibility, enrollment, etc). As the name implies, the intent is to make it administratively easier to exchange data by not having to keep track of an endless number of code sets. The common code sets range from X12 or NCPDP (pharmacy-related) and include DRG, ICD, CPT, NDC, SNOMED-CT, and LOINC amongst others.

---

External resources:

This area of HIPAA relates to the accepted coding for data exchanged in healthcare. The transactions this applies to are financial-related (claims, eligibility, enrollment, etc). As the name implies, the intent is to make it administratively easier to exchange data by not having to keep track of an endless number of code sets. The common code sets range from X12 or NCPDP (pharmacy-related) and include DRG, ICD, CPT, NDC, SNOMED-CT, and LOINC amongst others.

Here's a quick overview of these code sets and their intended function.

They are all linked to the appropriate browsers where possible so that you can get a better idea as to what they look like.

* SNOMED-CT or Systematized Nomenclature of Medicine - Clinical Terms: SNOMED-CT is a comprehensive vocabulary that covers almost every aspect of clinical care - ranging from anatomy to diagnoses to observations and procedures. SNOMED-CT requires a license but since the US is a participating country in [IHTSDO][1], it can be used freely after accepting a simple license agreement. There are no fees to use this in any commercial application. (See the following links for more info.)
[Website][2], [Browser][3], [Download][4].
* LOINC or Logical Observation Identifiers Names and Codes. This is meant primarily for laboratory and clinical observations. It was developed by the [Regenstrief Institute][5]. Note that LOINC doesn't have codes for anatomy for one. But, as you can imagine, there is some overlap with SNOMED-CT. There was a 2013 agreement announced for the two creating bodies to [work together][6] to map and link SNOMED-CT and LOINC. The use of LOINC is also possible with the acceptance of a simple license agreement. There are no fees to use this in any commercial application. [Website][7], [Browser][8],[Download][9]
* ICD 9 and 10 - The International Classification of Diseases. It was developed and is managed by the [World Health Organization][10]. It was initially developed for epidemiology but has since evolved significantly. The US was / is one of the last to switch over to the latest version, ICD-10. ICD-10 was complicated as it introduced a lot more detail (for example, its codes allow one to distinguish between the right and left lobes of a lung and even more granularly,) and an almost 10x increase in codes which is why its rollout in the US was delayed and is still problematic. The use of ICD 9 and 10 is also possible with the acceptance of a simple license agreement (see the download link for more info.) There are no fees to use this in any commercial application. [Website][11], [Browser][12], [Download][13]
* CPT - Common Procedure Terminology. It was developed and is maintained by the American Medical Association [AMA][14]. CPT coding is similar to ICD-9 and ICD-10 coding, except that it identifies the services rendered rather than the diagnosis on the claim. ICD code sets also contain procedure codes but these are only used in the inpatient setting. There is a necessary license agreement for any use and a fee for usage as well (see the download link for more info.) [Website][15], [Download][16]
* RxNORM - RxNorm provides normalized names for clinical drugs and links its names to many of the drug vocabularies commonly used in pharmacy management and drug interaction software, including those of First Databank, Micromedex, MediSpan, Gold Standard, and Multum. By providing links between these vocabularies, RxNorm can mediate messages between systems not using the same software and vocabulary. [Website][17], [Browser][18]
* HL7 - Health Language 7. This is more of a messaging and interoperability oriented standard and organization. It is the most common standard set for exchanging data between clinical systems. There are multiple HL7 message standards. However, HL7 has had to evolve to include codesets to enable this exchange. [Website][19], Browser - none, Download - you must be a paid member to access and use it.
* Other codesets - There are others of course. Often there are specific codesets which are mandated for use in a particular context. For example, for immunizations, interoperability and Meaningful Use require the use of the CVX codeset which is put out by the CDC. These are all accessible at via the following links. [Website][20], [Browser][21]

---

Lesson Scenario:

What defines the format of electronic transfer of information between providers and payers to carry out financial activities?

- <input type="checkbox"> `HIPAA`
- <input type="checkbox"> `Privacy`
- <input type="checkbox"> `EDI`
- <input type="checkbox"> `Security`

<div class="reveal-answer">
	<button class="button">Reveal Answer</button>
	<blockquote><p>EDI standards have been defined for electronic data exchange to exchange data between providers and payers. Specific EDI formats are EDI 835, EDI 837 etc.</p></blockquote>
</div>



[1]:	http://www.ihtsdo.org/
[2]:	http://www.ihtsdo.org/snomed-ct/snomed-ct0/
[3]:	http://bioportal.bioontology.org/ontologies/SNOMEDCT?p=classes
[4]:	http://www.nlm.nih.gov/research/umls/licensedcontent/downloads.html
[5]:	http://www.regenstrief.org/
[6]:	http://www.regenstrief.org/news/new-regenstrief-and-ihtsdo-agreement-make-emrs-more-effective-improving-health-care/
[7]:	http://loinc.org/
[8]:	http://bioportal.bioontology.org/ontologies/LOINC?p=classes
[9]:	http://loinc.org/downloads
[10]:	http://who.int
[11]:	http://www.who.int/classifications/icd/en/
[12]:	http://apps.who.int/classifications/icd10/browse/2010/en
[13]:	http://www.nlm.nih.gov/research/umls/licensedcontent/downloads.html
[14]:	http://www.ama-assn.org/ama
[15]:	http://www.ama-assn.org/ama/pub/physician-resources/solutions-managing-your-practice/coding-billing-insurance/cpt.page
[16]:	https://commerce.ama-assn.org/store/catalog/subCategoryDetail.jsp?category_id=cat1150007&navAction=push
[17]:	http://www.nlm.nih.gov/research/umls/rxnorm/
[18]:	http://mor.nlm.nih.gov/download/rxnav/
[19]:	http://hl7.org
[20]:	https://phinvads.cdc.gov/vads/BrowseValueSets_browse.action
[21]:	https://phinvads.cdc.gov/vads/BrowseValueSets_browse.action