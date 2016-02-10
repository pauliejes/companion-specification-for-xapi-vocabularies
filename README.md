# Companion Specification for xAPI Vocabularies {#companion-specification-for-xapi-vocabularies}

Companion Specification for Experience API (xAPI) Vocabularies

![logo](assets/logo.png)

December 2015

DRAFT v.1.0 PROPOSAL

(send questions or feedback to: xapi-vocabulary@adlnet.gov)

Table of Contents

1.  [Status of this Document](status_of_this_document.md)
2.  [License](license.md)
3.  [Introduction](introduction.md)
4.  [Background and Motivation](background_and_motivation.md)
5.  [How to Read this Document](how_to_read_this_document/README.md)
    1.  [Scope & Audience](how_to_read_this_document/scope_&_audience.md)
    2.  [Conformance](how_to_read_this_document/conformance.md)
6.  [Semantic Web Technology, Linked Data, and RDF](semantic_web_technology,_linked_data,_and_rdf/README.md)
    1.  [RDF Data Structure](semantic_web_technology,_linked_data,_and_rdf/rdf_data_structure.md)
7.  [xAPI Vocabularies as Linked Datasets](xapi_vocabularies_as_linked_datasets.md)
8.  [Relationship Between Vocabularies, Profiles, and Recipes](relationship_between_vocabularies,_profiles,_and_r.md)
9.  [Vocabulary Dataset Schema](vocabulary_dataset_schema/README.md)
    1.  [Namespace](vocabulary_dataset_schema/namespace.md)
    2.  [Classes and Properties](vocabulary_dataset_schema/classes_and_properties.md)
    3.  [Recommended Classes](vocabulary_dataset_schema/recommended_classes.md)
    4.  [Optional Classes](vocabulary_dataset_schema/optional_classes.md)
    5.  [Recommended Properties](vocabulary_dataset_schema/recommended_properties.md)
    6.  [Optional Properties](vocabulary_dataset_schema/optional_properties.md)
10.  [Dataset Schema Design](dataset_schema_design/README.md)
    1.  [Alignment with SKOS](dataset_schema_design/alignment_with_skos.md)
    2.  [xAPI Verbs and Activity Types as Concepts](dataset_schema_design/alignment_with_skos.md#xapi-verbs-and-activity-types-as-concepts)
    3.  [xAPI Vocabularies as Concept Schemes](dataset_schema_design/alignment_with_skos.md#xapi-vocabularies-as-concept-schemes)
    4.  [Provenance Metadata](dataset_schema_design/provenance_metadata.md)
11.  [Vocabulary Development and Publishing](vocabulary_development_and_publishing/README.md)
    1.  [IRI Design and Persistence](vocabulary_development_and_publishing/iri_design_and_persistence.md)
    2.  [IRI Principles](vocabulary_development_and_publishing/iri_design_and_persistence.md#iri-principles)
    3.  [Recommended IRI Design Practices](vocabulary_development_and_publishing/iri_design_and_persistence.md#recommended-iri-design-practices)
    4.  [Generating and Maintaining Vocabulary IRIs](vocabulary_development_and_publishing/generating_and_maintaining_vocabulary_iris.md)
    5.  [Resolving IRIs and Content Negotiation](vocabulary_development_and_publishing/resolving_iris_and_content_negotiation.md)
    6.  [Publishing Vocabulary Datasets as HTML/RDFa](vocabulary_development_and_publishing/publishing_vocabulary_datasets_as_htmlrdfa.md)
    7.  [Publishing Vocabulary Datasets as JSON-LD](vocabulary_development_and_publishing/publishing_vocabulary_datasets_as_json-ld.md)
12.  [Vocabulary Search and Reuse](vocabulary_search_and_reuse.md)
    1.  [SPARQL](vocabulary_search_and_reuse.md#sparql)
    2.  Federated Search

13.  [Vocabulary Implementation Requirements](vocabulary_implementation_requirements.md)
14.  [References](references.md)
15.  [Additional Resources](additional_resources.md)
16.  [Acknowledgements](acknowledgements.md)
17.  [Appendices](appendices/README.md)
    1.  [Appendix A: HTML/RDFa Vocabulary Dataset Example](appendices/appendix_a_htmlrdfa_vocabulary_dataset_example.md)
    2.  [Appendix B: Content Negotiation .HTACCESS (Apache) Example](appendices/appendix_b_content_negotiation_htaccess_apache_exa.md)