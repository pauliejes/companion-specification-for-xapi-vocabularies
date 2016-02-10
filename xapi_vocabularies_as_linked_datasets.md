# xAPI Vocabularies as Linked Datasets {#xapi-vocabularies-as-linked-datasets}

In this companion document, a "dataset" is structured data describing vocabulary terms, such as xAPI Verbs. Synonymous concepts to a dataset include such things as collections, lists, or metadata record sets. A dataset may also be self-describing in that it contains information about the entire dataset itself.

Linked Datasets provide an opportunity to share common meaning and common identifiers across the xAPI community and provide consistent and reliable identifiers for a list of vocabulary terms organized as Verbs and Activity Types. A Linked Dataset is in RDF and consists of:

1.  An IRI or blank node to identify each resource in the dataset.
2.  An IRI for the whole dataset.
3.  RDF metadata to describe the dataset and the resources in the dataset.
4.  References to ontology/schema IRIs which define the concepts and relationships used within the dataset.

A basic example of the cmi5 verbs represented as an RDF dataset is available as a HTML code example in [Appendix A](appendices/README.md). This example provides a representation of the dataset as RDF data embedded in HTML attributes, also known as RDFa. This is a simple approach and meets multiple requirements for xAPI vocabulary datasets to be published as both human readable (HTML) and machine readable (RDF) representations. However, simply adding the proper attributes to a single source HTML document does not completely eliminate the need to provide additional representations of the dataset in other RDF formats. Publishing vocabularies as RDFa is the easiest way to make vocabulary data easily discoverable by search engines and able to be queried using SPARQL and the IRI location as an endpoint. Once a dataset has been made available as RDFa, registries can also query and capture the data, improving opportunities for wider vocabulary search, discovery, and reuse.

Inserting RDF attributes to HTML elements makes the data in that page able to be easily serialized in other RDF formats; however, providing JSON-LD to non RDF-aware clients requires some additional constraints to be placed on the JSON-LD document. If a dataset is also made available in other serializations such as JSON-LD then other applications (e.g., LRS, LMS, Authoring Tools) can also dynamically retrieve the complete vocabulary dataset and meaning of each of the terms. This is made possible through client-server content negotiation. More information on using content negotiation to provide both HTML and JSON-LD is provided in

Section X

. A more advanced example of a vocabulary provided as a JSON-LD dataset is available in the [xAPI Vocabulary Primer](https://docs.google.com/document/d/1mQDMOussZ7iKkW5jk1sM8KrOOzjsUYVUmSSXyEhk8v8/edit?pref=2&pli=1#heading=h.uo4nz955yyd2).