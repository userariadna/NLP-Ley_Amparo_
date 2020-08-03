# NLP-Ley_Amparo_
The following pdf is the next content for all the files.
http://www.diputados.gob.mx/LeyesBiblio/pdf/LAmp_150618.pdf

The base of this article is the natural language preprocessing for legal texts.

What is Text processing?
A keypart of NLP is transforming text into mathematical objects.NLTK provides various functions that help us 
transform the text into vectors. The most basic NLTK function  for this purpose is tokenization , which splits 
a domument into a list of units. These units could be words, alphabets, or sentences.



What is for lemmatization and stemming?

We can further modify our vector by using lemmatization and stteming, which are techniques that are used 
to reduce words in their root form.The rationale behind this step is that the imginary n-dimensional space
that  we are navigating does not need to have sparate axes for a word and that word's inflected form 
(for example, eat and eating, don't need to be two separate axis).Therefore, we should reduce each word's 
inflected form to its root form. However, thsis approach has its critics because in manycases, inflected word 
froms give a different meaning than the root word. Therefore,you must perform stemming and lemmatization after c
considering its pros and cosnt.

Fore more information read Hands on Python Natural Language Preprocessing 
