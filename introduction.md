# Introduction {#introduction}

Designing for, developing, and generating analytics with the Experience API (xAPI) all demand consistent practices for semantically describing the concepts associated with the data. The requirement for a common vocabulary of Verbs and Activity Types was removed from the core xAPI specification as of the 0.95 version. Since then, the specification recommended that implementers either reuse existing vocabulary terms and identifiers or create new ones on their own. However, until now the xAPI community has lacked definitive guidelines for applying semantic practices when creating and publishing new identifiers and vocabularies.

In terms of interoperability, the core xAPI specification simply requires the data to be represented as JavaScript Object Notation (JSON) syntax, which adequately addresses structural interoperability (the ability of two or more applications or agents to exchange data). JSON is easy for humans to read and write, and easy for applications to parse and generate. This focus on structural interoperability was initially identified as the top priority of the Advanced Distributed Learning (ADL) community in order to enable the integration of learning experience data from diverse sources to any application or platform. In addition to structural interoperability, semantic data interoperability is also needed for both humans and applications to meaningfully interpret the information being exchanged. Semantic interoperability is also needed to improve vocabulary term reuse among communities of practice and to prevent duplication of terms with the same or similar meaning. In other words, without a semantic data model implementing the core xAPI specification requires more manual work to interpret, organize, aggregate, reuse, maintain, and generally do consistently useful things with the data.

In 2015, the xAPI community formed a small working group to investigate existing semantic web technologies and practices that could be leveraged for creating, publishing, and maintaining xAPI vocabularies as reusable and dereferenceable resources on the web.

This document is ancillary and intended to serve as a companion ([as described here](https://github.com/adlnet/xAPI-Spec/blob/master/xAPI.md#verb)) to the core xAPI specification. This companion specification will provide the basic building blocks for describing xAPI vocabularies as linked datasets on the web. This draft will initially address the xAPI vocabulary requirements for Verbs and Activity Types with the expectation that semantic practices will be identified and added (as needed) for future xAPI vocabulary elements.