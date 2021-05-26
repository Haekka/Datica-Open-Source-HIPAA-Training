Title:
Lesson 4 | HIPAA Entities
---

Lesson Notes: What are the different types of entities under HIPAA?
:dart: HIPAA defines two types of entities - covered entities and business associates.
:dart: Subcontractors are business associates of business associates

---

Lesson Content:

HIPAA defines entities in two broad buckets:

1. **Covered Entities**. Health systems, payers, and clearinghouses (process claims) fall into this category. If you’re curious, here’s an official [site][1] that helps you determine if you’re a covered entity.

2. **Business Associates**. These, most likely you if you’re reading this, are entities that provide services to covered entities and through those services access, transmit, process, or store PHI. Changes to HIPAA that went into effect in the fall of 2013 expanded the definition of business associate to include *“subcontractors,”* or entities that provide services to business associates. A simple use case - a developer that builds a PHR for a hospital is a business associate, and the hosting provider that the developer uses (ideally Datica) is a subcontractor. The developer signs a BAA with the hospital and with the hosting provider, again ideally Datica.

---

External resources:
HIPAA defines entities in two broad buckets:

1. **Covered Entities**. Health systems, payers, and clearinghouses (process claims) fall into this category. If you’re curious, here’s an official [site][2] that helps you determine if you’re a covered entity.

2. **Business Associates**. These, most likely you if you’re reading this, are entities that provide services to covered entities and through those services access, transmit, process, or store PHI. Changes to HIPAA that went into effect in the fall of 2013 expanded the definition of business associate to include *“subcontractors,”* or entities that provide services to business associates. A simple use case - a developer that builds a PHR for a hospital is a business associate, and the hosting provider that the developer uses (ideally Datica) is a subcontractor. The developer signs a BAA with the hospital and with the hosting provider, again ideally Datica.

**What is a "covered entity" under HIPAA?**

The term "covered entity" under the HIPAA Privacy Rule refers to three specific groups, including health plans, health care clearinghouses, and health care providers that transmit health information electronically.  Covered entities under the HIPAA Privacy Rule must comply with the Rule's requirements for safeguarding the privacy of protected health information.  Below is a more detailed list of those who fall under the covered entity category under HIPAA.

- Health Plans (licensed insurers, ERISA plans, HMOs, Medicare, etc.)
- Providers (physicians, hospitals, home health, DME, pharmacy, chiropractic, dental, etc.) that conduct one or more of the HIPAA-defined transactions electronically
- Clearinghouses (billing services, value-added networks and switches if these entities perform clearinghouse functions such as claims routing, and cleansing entities)

**What is a “business associate” under HIPAA?**

The HIPAA Privacy Rule outlines the types of entities that are covered by HIPAA and entities that have to follow the HIPAA security and privacy rules. The main categories are clearinghouses, covered entities (CEs) - typically hospitals, payers, providers, and business associates. Business associates are by far the biggest cohort of cloud computing companies.

Business associates are people or organizations who contract and provide services and/or technology for covered entities. In the process of providing those services or those technologies, business associates handle, process, transmit, or in some way interact with electronic protected health information (ePHI) from those covered entities. With this ePHI access, business associates are required to sign what’s called a business associate agreement (BAA).

Datica is a subcontractor for some of our customers and, as such, we do sign BAAs. We also act as a business associate directly for covered entities like enterprises, and sign BAAs in this capacity. We offer the same compliant software in both circumstances, but the relationship is slightly different in the eyes of HIPAA.

**What about Subcontractors?**

Subcontractors are entities that business associates use to process, create, or store PHI. Subcontractors don’t have business associate agreements, or really any direct relationships, with covered entities; but, starting 9/23/2013, these subcontractors need to have business associate agreements (BAAs) with business associates. It’s all very obvious and confusing at the same time. Essentially you can think of subcontractors as a business associate of a business associate.

The best examples of subcontractors we can think of are hosted services providers like Amazon Web Services, Datica, and Rackspace. Datica is a subcontractor for some of our customers and, as such, we do sign BAAs. We also act as a business associate directly for covered entities like enterprises, and sign BAAs in this capacity. We offer the same API-based services for developers in both circumstances, but the relationship is slightly different in the eyes of HIPAA.

At Datica we know that subcontractors, as defined by HIPAA, have existed for a long time. As more health apps and services have shifted to hosted, or cloud based, and more infrastructure tools (app dev, logging, analytics, data collections, etc) have become mainstream, covered entities and business associates have begun to rely on “subcontractors”. The new HIPAA rules now mean those subcontractors need to work with business associates to assure all parties are covered in terms of liability.

This is a very exciting and major shift for health tech. HIPAA has finally acknowledged subcontractors and the role they play in creating, processing, and transmitting PHI. That’s important for health tech to build smart, scalable, and interoperable tools. As a developer in healthcare, if you’re considering acting as a business associate, or selling services to a covered entity, you need to understand if you fit into a certain entity category as defined by HIPAA.

The Omnibus Rule also defined a PHR (Personal Health Record) vendor, offering a PHR through a covered entity, as a business associate.

---

Lesson Scenario:
If you work for a technology company that sells cloud software to health systems, what type of entity are you?

- `Covered entity`
- `Subcontractor`
- `Business Associate`
- `None of the above`

Answer: You work for a business associate. Business associates provide technology or services to covered entities (health systems).

[1]:	http://www.hhs.gov/ocr/privacy/hipaa/understanding/coveredentities/index.html
[2]:	http://www.hhs.gov/ocr/privacy/hipaa/understanding/coveredentities/index.html