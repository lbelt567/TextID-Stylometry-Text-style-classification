# TextID-Stylometry-Text-style-classification
This project uses Python and machine learning to develop a statistical model of text that will allow you to "ID" an author or style—with varying degrees of success!—from samples of text...
This is sometimes known as Stylometry.
Either way, it's fun to compare your prose to see which of two "corpora" it more closely matches!
Statistical models are one way to quantify how similar one piece of text is to another. Such models were used as evidence that the book The Cuckoo's Calling was written by J. K. Rowling (using the name Robert Galbraith) in the summer of 2013. Details on that story and the analysis done appear at this link.

The comparative analysis of those works used simple models—perhaps surprisingly simple—of an "author's style," for example, the distribution of word lengths in a document. The five "text features" that we ask you to implement for this project are:

The distribution of words used by an author.
The distribution of word lengths (noted above).
The distribution of word stems used (e.g., "spam" and "spamming" would have the same stem).
The distribution of sentence lengths used.
Plus, the project asks you to include one more "text feature" of your own design:
For example, you could use punctuation in some way.
Or you could compute something else about the text—it could be the number of words ending in "ness," something about capitalization, or anything else you can compute or count using Python...
Here is an article on the punctuation analysis of several works...
...and an analysis of punctuation across computer programming languages.

Perhaps the most common and most successful application of this kind of textual analysis is Spam detection and filtering.
