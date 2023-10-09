# highlightjs-turtle
Semantic Web languages

[highlight.js](https://github.com/highlightjs/highlight.js) syntax definitions for these semantic web languages:
- SPARQL 1.1: [Query](https://www.w3.org/TR/sparql11-query/) and [Update](https://www.w3.org/TR/sparql11-update/) languages. See [BNF grammar](https://www.w3.org/TR/sparql11-query/#sparqlGrammar) and [syntax diagrams](http://rawgit2.com/VladimirAlexiev/grammar-diagrams/master/sparql11-grammar.xhtml)
- [Turtle 1.1](https://www.w3.org/TR/turtle/)
- [SHACL Compact](https://w3c.github.io/shacl/shacl-compact-syntax/]. See [BNF grammar](https://github.com/VladimirAlexiev/grammar-diagrams/raw/master/shaclc-grammar.ebnf) and [syntax diagrams][http://rawgit2.com/VladimirAlexiev/grammar-diagrams/master/shaclc-grammar.xhtml].
  Still in TODO
- [GraphDB Rules](http://graphdb.ontotext.com/documentation/standard/reasoning.html)

Links:
- http://highlightjs.org for more info on `highlight.js` and a live demo.
- https://github.com/highlightjs/highlightjs-shexc for another semantic language, SHEX (Shape Expressions)
- [highlight-to-reveal](https://github.com/VladimirAlexiev/highlight-to-reveal) for info about using this in [reveal.js](https://github.com/hakimel/reveal.js), a tool for web-based presentations.
  NOTE: this is outdated!

## Contributors
- Mark Ellis, [@ellismarkf](https://github.com/ellismarkf), Stardog Union
- Vladimir Alexiev, [@VladimirAlexiev](https://github.com/VladimirAlexiev), Ontotext Corp

## Build
First checkout the highlight.js code then simplink these files to the `src/languages` directory of that repository and run `node tools/build.js turtle typescript javascript json sparql` (or other languages as you prefer).