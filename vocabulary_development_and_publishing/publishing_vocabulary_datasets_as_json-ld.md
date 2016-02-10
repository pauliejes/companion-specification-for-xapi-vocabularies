## Publishing Vocabulary Datasets as JSON-LD {#publishing-vocabulary-datasets-as-json-ld}

In addition to providing vocabulary datasets as HTML/RDFa, vocabulary authors can also make the dataset available as JSON-LD or “JavaScript Object Notation for Linked Data.” JSON-LD is simply another way of encoding linked data using JSON, and is the preferred alternative representation of the same vocabulary dataset expressed in HTML/RDFa markup. While RDFa requires HTML, JSON-LD could also be embedded in HTML, but that would result in the author having to maintain duplicative information in the same HTML document. Instead, a JSON-LD serialization should be provided as a separate file and accessible through content negotiation. Read the [Resolving IRIs and Content Negotiation](resolving_iris_and_content_negotiation.md) section of this document for more details on content negotiation.

The importance of JSON-LD is that it may be used directly with xAPI web services. JSON-LD is extremely useful for a non-RDF consumer. In other words, JSON-LD is expected to be useful for other types of applications that wouldn’t necessarily directly rely on a SPARQL query interface to obtain vocabulary metadata. Examples of these types of applications might include xAPI authoring tools, Learning Record Store (LRS) applications, and other web applications that would benefit from consuming a JSON representation.

Currently, the vocabulary metadata for each vocabulary term and term list (dataset) should at least be represented as HTML/RDFa. It is expected that the xAPI Vocabulary Server, or other registry interfaces, will make the JSON-LD generation process more automated in the future through web-based forms and publishing tools. For now, examples of a vocabulary provided as JSON-LD is provided in the [xAPI Vocabulary Primer](https://docs.google.com/document/d/1mQDMOussZ7iKkW5jk1sM8KrOOzjsUYVUmSSXyEhk8v8/edit?pref=2&pli=1#heading=h.uo4nz955yyd2).