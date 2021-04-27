# SPARQL-queries
Selection of SPARQL queries to be used in the LiLa endpoints: [https://lila-erc.eu/sparql/index.html](https://lila-erc.eu/sparql/index.html).

List of available queries (in alphabetical order):
- affixes-nouns.rq: counts the frequency of affixes (both prefixes and suffixes) attached to nouns in the LiLa Knowledge Base and sorts them from the most to the least frequent;
- etymology.rq: retrieves all lemmas with a Proto-Italic reconstructed form;
- form-lemma.rq: retrieves the occurrences of the forms of a specific lemma (e.g., "malus" [<http://lila-erc.eu/data/id/lemma/111418>](<http://lila-erc.eu/data/id/lemma/111418>)) in all the corpora linked to the LiLa Knowledge Base;
- forms-DVE.rq: counts the occurrences of each form of the lemmas 'dico' and 'facio' in the work "De Vulgari Eloquentia" of Dante Alighieri;
- greek-Aulularia.rq: retrieves all lemmas of the "Querolus sive Aulularia" corpus with a Greek etymology (and thus included in the "Index Graecorum Vocabulorum in Linguam Latinam");
- greek-etymology.rq: retrieves all the lemmas with a Greek etymology (and thus included in the "Index Graecorum Vocabulorum in Linguam Latinam");
- latinwordnet_synset.rq: retrieves all the lemmas belonging to a specific synset;
- lemmi-POS-gender.rq: counts the lemmas in the LiLa Knowledge Base having a specific Part-of-Speech (e.g., NOUN) and a specific gender (e.g., neuter);
- lemmi-POS-suffix.rq: retrieves the lemmas in the Lemma Bank with a specific Part-of-Speech (e.g., NOUN) and a suffix;
- lemmi-POS.rq: retrieves the lemmas in the lemmaBank with a specific Part-of-Speech (e.g., NOUN);
- protoItalic-Monarchia.rq: retrieves all the lemmas with a Proto-Italic reconstructed form in the "Monarchia" of Dante Alighieri;
- tokens.rq: given a lemma (e.g., "occido"), it retrieves all the tokens having that lemma in the works linked in the LiLa knowledge base;
- UDante-affix.rq: given an affix (e.g., “in- (negative)”), finds all the lemmas with such affix in UDante and IT-TB;
- UDante-lexicalbase.rq: given a lexical base (e.g., "loquor"), it finds all the lemmas belonging to the same lexical base in Dante and IT-TB;
- UDante-sentiment.rq: retrieves the list of lemmas with a specific polarity in UDante;
- UDante-synset.rq: finds all the lemmas belonging to a specific synset in UDante and IT-TB;
- UDante-syntax.rq: given a specific lemma (e.g., "loquor"), it retrieves all the lemmas that are annotated as nsubj in Dante and subj ITTB.
