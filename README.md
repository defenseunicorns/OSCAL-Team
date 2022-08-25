# Background
Software accreditation and security remains a key obstacle in deploying and achieving continuous software delivery in regulated environments. NIST’s OSCAL project presents an opportunity to help streamline the software accreditation process by providing an avenue to express government-required security controls information as machine-readable formats (XML, JSON, YAML). These machine-readable formats can be ingested into Governance, Risk, and Compliance (GRC) tooling and presented as dashboards, visualizations, etc. 

## Defense Unicorns OSCAL-Team
Defense Unicorns holds internal research & development (IRAD) days 1x per month for two days at a time. These days are referred to as “Dash Days.” Defense Unicorns is currently holding “Dash Days of Summer - 2022.” “Dash Days of Summer” is a series of three Dash Days, equating to 6-7 days over a three month period in which a consistent group of Defense Unicorns engineers will decompose and tackle a complex software delivery problem. 
Defense Unicorns' OSCAL-Team is dedicating Dash Days between July and September 2022 to creation of an OSCAL proof of concept aligned with the project objective above. 
We welcome open contributions to this effort. Contributing guidelines shall be published shortly. 

## Purpose
This project aims to leverage and extend NIST’s OSCAL work to improve security and risk assessments, increase optionality in tooling and drive greater commercial software adoption. This repo will aggregate documentation first for the Dash Days OSCAL team as we iterate toward an initial Proof-of-Concept.

## Decision Records
[ADR 7-15-22](./ADR/ADR-7-15.md)

## Relevant Material

### Industry Wide
- [usnistgov/oscal-content GitHub](https://github.com/usnistgov/oscal-content/tree/main/nist.gov/SP800-53/rev5/yaml)
    - This contains the yaml OSCAL catalog and baseline profiles for NIST_SP-800-53_rev5
- [kubernetes/sig-security GitHub](https://github.com/kubernetes/sig-security/blob/main/sig-security-docs/papers/policy/kubernetes-policy-management.md)
    - This contains the whitepaper for kubernetes policy management - with mention of automating compliance controls (mentioning OSCAL)
- [kubernetes Policy Working Group Presentation](https://csrc.nist.gov/csrc/media/Events/2022/3rd-oscal-workshop/documents/2.5%20-%20Main%20-%20IBM_Oscal%20Workshop%20Kubernetes%20Policy%20Working%20Group.pdf)
    - Similar to the above whitepaper

### Big Bang
- [Big Bang OSCAL Document](https://repo1.dso.mil/platform-one/big-bang/bigbang/-/blob/master/oscal-component.yaml)
    - Aggregation of OSCAL documents from many packages into a single document
- [defenseunicorns/bigbang-oscal-component-generator GitHub](https://github.com/defenseunicorns/bigbang-oscal-component-generator)
    - CLI for aggregating OSCAL documents from many packages

