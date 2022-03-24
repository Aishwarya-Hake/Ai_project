# English_german_lang_translation_model

Language Translation (German to English)

The objective of the project is to implement language
translation model aka machine translation for converting
German to English (and vice versa)
For this, the data is a text file (.txt) of English-German sentence
pairs. The actual data contains over 150,000 sentence-pairs.
However, it is suggested to use only the first 50,000 sentence
pairs to reduce the training time of the model.

You can download the Data set from
http://www.manythings.org/anki/

Text Pre-Processing
Quite an important step in any project, especially so in NLP.
The data we work with is more often than not unstructured so
there are certain things we need to take care of before jumping
to the model building part.
(a) Text Cleaning
(b) Text to Sequence Conversion
A Seq2Seq model requires that we convert both the input and
the output sentences into integer sequences of fixed length.
