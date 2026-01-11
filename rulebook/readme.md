Semantic integrity refers to the ability of a healthcare information system to preserve the clinical meaning of data consistently across different systems, applications, and contexts. It ensures that a medical concept recorded in one system is interpreted in exactly the same way when shared, analyzed, or reused by another system.

In healthcare IT, semantic integrity is achieved by avoiding the use of magic strings (free-text or hard-coded values) and instead using standardized coded values. Local or proprietary codes are mapped to standard terminologies through FHIR ConceptMap, which serves as a controlled mapping layer. The FHIR $translate operation is then used to dynamically convert local codes into their standardized equivalents.

By using this approach, systems maintain interoperability, reduce ambiguity, support accurate clinical decision-making, and enable reliable analytics and reporting—without embedding clinical meaning directly into application logic.
