# Vocabulary Dataset Schema {#vocabulary-dataset-schema}

The previous sections described the characteristics of vocabularies and the notion of expressing vocabulary data as an organized dataset. This section formally describes the data schema for xAPI vocabularies expressed as RDF. A schema is a common approach for how to define classes and attributes that should used to describe things. The term "RDF vocabulary" is sometimes used as an umbrella term in the LD community instead of schema. However, to avoid ambiguity with the general (and often overlapping) use of the word “vocabulary” in the LD community, the term “schema” will be used in this specification to best convey how Verb and Activity Type datasets are modeled and described.

It is common practice for schemas to incorporate and reuse classes and properties from pre-existing ontologies and schemas, where stable and appropriate ones could be leveraged. RDFS, OWL, and SKOS were primarily used to model the xAPI Vocabulary Dataset Schema. The recommended and optional schema elements are detailed in the tables below following Figure 4\.

A list of the pre-existing ontologies and schemas used are also provided for convenience, while complete class and property descriptions are accessible from the namespace IRI column in the table. An IRI is commonly used for each of the classes and properties so that they may be applied and validated by developers and consumers of RDF data. The classes and properties of the vocabulary dataset schema containing an “**xapi:**” prefix exclusively belong to the xAPI namespace.