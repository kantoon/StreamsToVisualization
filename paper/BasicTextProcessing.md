# Basic Text Processing

To better understand what is necessary for a computer to master processing natural language, it is important to first understand the human language. The greatest challenges occur here since the human language is highly ambiguous. 

There is an endless list of factors that need to be accounted for, only some being mentioned here. A linguist would explain that the English language is structured in a subject-verb-object fashion. Not all languages share this same format and are therefore not all processed using the same techniques.

Before meaning can be extracted from a block of text, it must be broken down into smaller constituents by parsing. Parsing output can sometimes be viewed in a parse tree, a pictorial representation of relationships among constituents. Tokenization separates a stream of text into words, phrases, symbols, or other meaningful elements defined as tokens.

There are many methods and goals of parsing that involve more intricate steps, only a few generalized here. Say the goal token is a word. The definition of a “word” must be determined.  One may suggest a continuous string of characters. Another may suggest a separation by a white space or punctuation mark. What about contractions or words separated with spaces like “New York”? The flaws in these definitions require the application of normalization, standardizing the words in such a way that there is no ambiguity. 

Another angle of tokenization is with lemmas. To construct meaning from some text, we can perhaps take the set of all the forms that have  the same meaning (a lemma) and determine if that set is large enough to conclude that is the main topic of some text.

Some may argue that this “rule-based” natural language processing is not the way to go, and a more statistical approach will provide more sufficient results.
