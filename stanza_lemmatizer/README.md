## Stanza lemmatizer with MedLexSp forms and lemmas of medical terms

The lemmatizer model (``ancora-medlexsp.pt``) is an updated version of the Ancora default model for Spanish with medical lemmas and forms from the MedLexSp lexicon (new 104 551 forms).

Note that the model ``ancora-medlexsp.pt`` is only used for lemmatization.

For part-of-speech tagging (in addition to lemmatization), use the file ``MedLexSpPOS.pickle``, as explained in the companion jupyter notebook (``stanza_medlexsp.ipynb``).

Tested in Stanza vs. 1.4.0 and python 3.7.

### Where do you have to place the ``ancora-medlexsp.pt`` file?

Place the model file ``ancora-medlexsp.pt`` in the folder with the Spanish Stanza models. 

Generally, it is found in: ``/home/stanza_resources/es/lemma/ancora.pt``

Rename the new model file, or update the path with the new file name (``ancora.pt`` &rarr; ``ancora-medlexsp.pt``)


