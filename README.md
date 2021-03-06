# Simple-JATS

**JATS** is the XML rich format for Science contents, stands *"[Journal Article Tag Suite](https://en.wikipedia.org/wiki/Journal_Article_Tag_Suite)"*.  **Simple JATS**  intend to be simultaneally a less richer JATS subset and an [HTML5](https://en.wikipedia.org/wiki/HTML5) [polyglot](https://www.w3.org/TR/html-polyglot/) subset. 

## Motivations 

JATS was inspired by and used some XHTML 1.1 (HTML4 structures), as the *paragraph*, *table* and *MathML* modules. In nowadays, with the HTML5 use consolidation, with its fine-grained structure, the HTML content expression is approximating to JATS. But [syntax](https://en.wikipedia.org/wiki/XML_schema) and semantic interpretations of HTML5 are so flexible, making the JATS-back process impraticable... There are some ways to constraint HTML5:

* Add semantic constraints by [RDFa](https://en.wikipedia.org/wiki/RDFa), eg. by [schema.org/ScholarlyArticle](http://schema.org/ScholarlyArticle)

* Add structure constraints by simple convention (eg. restrictive structure).

Even with constraints, it is not a complete map to JATS, we can express only the first levels (and/or the most frequent tags) of the “JATS tree”...  By other hand, in many applications this “first levels of the JATS tree” is enough, and their user-communities  can agree about basic conventions:

1. To express online “first-access content” of scholar articles, by HTML. <br/>Example: all OpenAccess repositories (PubMed Central, SciELO, etc.) and all "big" OpenAccess journals (eg. PLOS), offer its articles in an (structured) HTML navigation context. 

2. To the production of (poor JATS) scholar journal articles at journals with a lower degree of maturity . <br/>Example:  many Latim America’s English journals at Redalyc and SciELO  (and perhaps half of all only-non-english journals) are "poor JATS".

3. To store [HTML corpora](https://en.wikipedia.org/wiki/Text_corpus) of encyclopedical, technical  or scientific contents. <br/>Example: ... 

4. To JATS supply-chain and internal workflow, as intermediary format, before to obtain complete JATS. <br/>Example: ...

And there are some trends to beobserved: in item-1, some JATS journals, as PeerJ, are developing XSLT to the obtain a kind of "JATS-preserving semantics" in the HTML convertion; in item-2, the [Marcalyc](https://xmljatsredalyc.org/2016/07/28/marcalyc/) process is producing and accepting  JATS with less richness tham SciELO or PMC; in item-3 the Mediawiki and DBpedia  community was developed some XML standars that can be mapped to a simplified form of JATS; in item-4, the Caboverde editorial framework and others are using a kind of Simple JATS in its internal workflow. 



