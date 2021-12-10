# SPARQL-queries
Selection of SPARQL queries to be used in the LiLa endpoints: [https://lila-erc.eu/sparql/index.html](https://lila-erc.eu/sparql/index.html).

**10/12/2021 - We migrated our endpoint to Virtuoso: the queries have been updated accordingly**

List of available queries (in alphabetical order):
- affixes-nouns.rq: counts the frequency of affixes (both prefixes and suffixes) attached to nouns in the LiLa Knowledge Base and sorts them from the most to the least frequent;
- corpora.rq: lists all the corpora currently available in the LiLa Knowledge Base;
- distinctivelemmas-Fibonacci.rq: finds all the lemmas that are used only by Fibonacci, thus are not present in the other corpora currently linked in the LiLa KB;
- distinctivelemmas-DVE.rq: find all the lemmas that are used by Dante only in the "De Vulgari Eloquentia" and not in his other works;
- etymology.rq: retrieves all lemmas with a Proto-Italic reconstructed form;
- form-lemma.rq: retrieves the occurrences of the forms of a specific lemma (e.g., "malus" [<http://lila-erc.eu/data/id/lemma/111418>](<http://lila-erc.eu/data/id/lemma/111418>)) in all the corpora linked to the LiLa Knowledge Base;
- forms-DVE.rq: counts the occurrences of each form of the lemmas 'dico' and 'facio' in the work "De Vulgari Eloquentia" of Dante Alighieri;
- greek-Aulularia.rq: retrieves all lemmas of the "Querolus sive Aulularia" corpus with a Greek etymology (and thus included in the "Index Graecorum Vocabulorum in Linguam Latinam") and having the suffixes "-or" and "-ic";
- greek-etymology.rq: retrieves all the lemmas with a Greek etymology (and thus included in the "Index Graecorum Vocabulorum in Linguam Latinam");
- latinwordnet_synset.rq: retrieves all the lemmas belonging to a specific synset;
- lemmi-POS-gender.rq: counts the lemmas in the LiLa Knowledge Base having a specific Part-of-Speech (e.g., NOUN) and a specific gender (e.g., neuter);
- lemmi-POS-suffix.rq: retrieves the lemmas in the Lemma Bank with a specific Part-of-Speech (e.g., NOUN) and a suffix;
- lemmi-POS.rq: retrieves the lemmas in the lemmaBank with a specific Part-of-Speech (e.g., NOUN);
- lexicons.rq: lists all the lexicons currently available in the LiLa Knowledge Base;
- protoItalic-Monarchia.rq: retrieves all the lemmas with a Proto-Italic reconstructed form in the "Monarchia" of Dante Alighieri;
- sentiment-text.rq: performs lexicon-based sentiment analysis on each text of the Epistole by Dante Alighieri using LatinAffectus v2;
- sentiment-paragraph.rq: performs lexicon-based sentiment analysis on each paragraph of the letters written by Dante Alighieri using LatinAffectus v2;
- synset-frame.rq: finds the forms that have a specific synset in the currently revised portion of Latin WordNet (e.g. 00179311-v: "take out, take away") and a valency frame with specific functor (e.g., ADDR "addressee") in Latin Vallex;
- tokens.rq: given a lemma (e.g., "occido"), it retrieves all the tokens having that lemma in the works linked in the LiLa knowledge base;
- UDante-affix.rq: given an affix (e.g., “in- (negative)”), it finds all the lemmas with such affix in UDante and IT-TB;
- UDante-lexicalbase.rq: given a lexical base (e.g., "loquor"), it finds all the lemmas belonging to the same lexical base in Dante and IT-TB;
- UDante-sentiment.rq: retrieves the list of lemmas with a specific polarity in UDante;
- UDante-synset.rq: finds all the lemmas belonging to a specific synset in UDante and IT-TB;
- UDante-syntax.rq: given a specific lemma (e.g., "loquor"), it retrieves all the lemmas that are annotated as nsubj in Dante and subj IT-TB.
