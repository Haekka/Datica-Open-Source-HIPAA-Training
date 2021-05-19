
Title:
Lesson 7 | All about PHI
---

Lesson Notes: The what and how of PHI?
:dart: PHI is Protected Health Information. ePHI is just electronic PHI.
:dart: Protected health information (PHI) is any information about health status, provision of health care, or payment for health care that can be linked to a specific individual.

---

Lesson Content:

**The acronym**: **PHI** stands for **P**rotected **H**ealth **I**nformation.

**The definition**: Here’s the Wikipedia definition. Protected health information (PHI) is any information about health status, provision of health care, or payment for health care that can be linked to a specific individual. PHI can be in oral, written or electronic form.

**Elements of PHI**

The generally accepted set of individually unique data elements include the [following][1]:

1. Name.
2. Geographic Locators.
3. Dates.
4. Phone numbers.
5. Fax numbers. 
6. Social security numbers. 
7. Medical record number. 
8. Health plan beneficiary numbers. 
9. Account numbers.
10. Certificate/license numbers.
11. Vehicle identifiers and serial numbers, including license plate numbers.
12. Device identifiers and serial numbers. 
13. Web Universal Resource Locators (URLs).
14. Internet Protocol (IP) address numbers.
15. Biometric identifiers, including finger and voice prints.
16. Full face photographic images and any comparable images. 
17. Any other unique identifying number, characteristic, or code.

These 17 elements are the core set of data elements that individually or in combination can be used to uniquely identify an individual. And, considering the fact that the above list of identifiers has **fax numbers** and not Twitter @usernames, Facebook IDs, or a host of other modern, more common identifiers, it's clear that the PII list is not the most up to date and some more thought should go into recognizing and protecting identifiable information. However, since patient data is valuable in clinical trials, medical case studies etc., the above list is used as a guideline to ensure privacy.

---

External resources:


**The acronym**: **PHI** stands for **P**rotected **H**ealth **I**nformation - not personal health information (although that’s in essence what it implies), not personally identifiable health information (I’ve seen it used although that would technically be PIHI) and I’m sure there are variants of this that you’ve heard as well.

**The definition**: Here’s the Wikipedia definition. Protected health information (PHI) is any information about health status, provision of health care, or payment for health care that can be linked to a specific individual. HHS provides an even simpler definition of PHI - individually identifiable health information transmitted or maintained in any form or medium by a Covered Entity or its Business Associate; the definition of a “business associate” has been extended with the HIPAA Omnibus rule that went into effect in 2013. This term “information” is interpreted rather broadly and includes any part of a patient’s medical record or payment history. The key here is this phrase “that can be linked to a specific individual”. Which is where the other acronym, PII (Personally Identifiable Information) - [here’s the link to the Wikipedia article on that][2] - becomes relevant. The major difference between PHI and PII is that PII is a legal definition - i.e. PII is anything that could be used to uniquely identify an individual. PHI is a subset of PII in that a medical record could be used to identify a person - especially if the disease or condition is rare enough.

For information to be considered PHI, it must meet all of the following three conditions:

1. The information is created, received, or maintained by a health provider or health plan.
2. The information is related to past, present or future health care or payment for that health care.
3. The information identifies a member or patient, or there is enough information to be able to identify the individual.

Health information that is not linked to an individual by one or more of the 18 HIPAA identifiers (see the next section) and for which there is no reasonable basis to believe that the information can be used to identify the individual is not protected health information.Individually identifiable health information ceases to be PHI 50 years after death.

PHI can be in oral, written or electronic form.

**Protection of PHI**

The core of the HIPAA regulations is to ensure that ownership of any and all medical data is retained solely by the individual. The individual can then decide to parcel out access to others - providers, family members, employers if needed or necessary or simply by preference of the record owner. Only an individual has the right to grant access to their medical data. This was mainly done for the following reasons:

1. Privacy: Obviously we would prefer that our neighbor (or in some cases, family members) not know about whatever condition we might be suffering from or medication we are taking.
2. Bias and discrimination: AIDS, mental health and other conditions have some (albeit declining) social stigma associated with them. The HIPAA PHI provisions ensure that employers and others do not have access to one’s medical record and use the information contained within to discriminate against the individual based on their health information.

**Elements of PHI**

Protection and privacy come into play once the individual has been uniquely identified. [There are after all 25.8 million Americans who have diabetes][3]. Which leads to the question of what data can be used to uniquely identify an individual. The generally accepted set of individually unique data elements include the [following][4]:

1. Name - Well, of course i.e. first name, last name, maiden name combinations. One could argue that just any \<strong\>one\</strong\> of the above doesn&#39;t uniquely identify an individual after all &quot;James&quot; is a pretty common name. But it could be possible to identify an individual using a combination of data i.e. first name, zipcode, street address etc.
2. Geographic Locators. Everything (street address, city, precinct, zipcode, lat long coordinates etc.) are considered PII. The first three digits of the zipcode are usually considered ok for use except in the case of certain zipcodes which cover a small population (less than 20,000). There are currently 17 zipcodes that fit that profile - 036, 692, 878, 059, 790, 879, 063, 821, 884, 102, 823, 890, 203, 830, 893, 556, 831. So three digit zipcodes are ok to be used except for the above listed ones.
3. Dates. Pertaining to significant events in an individual’s life - birth, death, marriage, admission, discharge etc. Just the year is generally considered fine for use except in the case of the very elderly (\>89 years of age; in which case they would be represented by an aggregate category e.g. =\>90 ).
4. Phone numbers. Well, of course.
5. Fax numbers. This is, IMHO, a carryover from the old days. Do you know a lot of people with a personal fax number? But, it does make sense.
6. Social security numbers. Check. 
7. Medical record number. This is usually a random number and could be used if one also knew the institution that assigned it.
8. Health plan beneficiary numbers. This is your insurance card / member ID.
9. Account numbers. Bank numbers etc.
10. Certificate/license numbers. Drivers license, birth certificate number etc.
11. Vehicle identifiers and serial numbers, including license plate numbers. If it’s good enough for the police to track someone down...
12. Device identifiers and serial numbers. Medical devices have unique serial numbers. So does your phone and your computer. Your computer’s MAC id is unique as well.
13. Web Universal Resource Locators (URLs). This is a bit murky but is in here to cover all possibilities. \<a href="http://www.facebook.com" rel="nofollow"\>http://www.facebook.com\</a\> isn’t very unique. But if logged within a specific application, could indeed be very unique to an individual.
14. Internet Protocol (IP) address numbers. Your IP address can be used to easily identify your address. There are several free services that offer this (do a quick google search for \<a href="https://www.google.com/search?q=address+from+ip&amp;oq=address" rel="nofollow"\>address from ip\</a\> and try this as an \<a href="http://geobytes.com/get-city-details-api/" rel="nofollow"\>example\</a\>.
15. Biometric identifiers, including finger and voice prints. Don’t forget retinal images.
16. Full face photographic images and any comparable images. Check and becoming a lot more prevalent.
17. Any other unique identifying number, characteristic, or code. Re code - note this does not mean the unique code assigned by the system to code the data.

These 17 elements are the core set of data elements that individually or in combination can be used to uniquely identify an individual. And, considering the fact that the above list of identifiers has **fax numbers** and not Twitter @usernames, Facebook IDs, or a host of other modern, more common identifiers, it's clear that the PII list is not the most up to date and some more thought should go into recognizing and protecting identifiable information. However, since patient data is valuable in clinical trials, medical case studies etc., the above list is used as a guideline to ensure privacy.

**Anonymization & De-identification of PHI**

* *Anonymization* is a process by which PHI elements are removed or changed with the purpose of minimizing / removing the possibility of going back to the original data set. This involves removing all identifying data to create unlinkable data.
* *De-identification* under HIPAA occurs when data has been stripped of common identifiers by two methods:
Remove the 18 elements listed above;

If another approach is used, ensure a statistically small / negligible risk of re-identification which is validated by a statistics expert (you have to love the interpretability of that rule).

---

Lesson Scenario:

What are examples of protected health information that might be connected to an individual?

- <input type="checkbox"> `Telephone number`
- <input type="checkbox"> `Address`
- <input type="checkbox"> `Zipcode`
- <input type="checkbox"> `Date of Birth`
- <input type="checkbox"> `Gender`

<div class="reveal-answer">
	<button class="button">Reveal Answer</button>
	<blockquote><p>Zipcodes (except for a small set) cannot be used to uniquely identify an individual. Neither can gender.</p></blockquote>
</div>







[1]:	http://www.oshpd.ca.gov/Boards/CPHS/HIPAAIdentifiers.pdf
[2]:	http://en.wikipedia.org/wiki/Personally_identifiable_information
[3]:	http://ndep.nih.gov/diabetes-facts/
[4]:	http://www.oshpd.ca.gov/Boards/CPHS/HIPAAIdentifiers.pdf