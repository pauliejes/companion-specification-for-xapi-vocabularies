## Provenance Metadata {#provenance-metadata}

“Provenance” is any information about entities, activities, and people involved in producing a piece of data or thing in the world. Dublin Core is a very common source for providing provenance metadata about how things are described and organized. While iterating on examples, the xAPI Vocabulary working group determined that many of the properties from Dublin Core had overlapping similarity in SKOS and also the Provenance (PROV) Ontology. However, most of the analogous SKOS and PROV terms were deemed more appropriate. For example, **skos:prefLabel** can only be used once for each language tag with a concept, and represents the single most preferred way of labeling that concept in that language. In the interests of minimal complexity and reducing the number of external dependencies, the overlapping Dublin Core terms were excluded from the xAPI Vocabulary Dataset Schema, which helped to also eliminate the need to define additional rules outside of Dublin Core for their use in xAPI vocabularies. Dublin Core is currently used in the xAPI Vocabulary Dataset Schema only for providing specific creation and modification dates for vocabularies. Vocabulary authors are encouraged to look into the expressive constructs in PROV for all other provenance metadata. Refer to the [xAPI Vocabulary Primer](http://#) for examples and ideas on how to apply PROV to xAPI vocabulary datasets.