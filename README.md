# NLP-Ley_Amparo_
The following pdf is the next content for all the files.
http://www.diputados.gob.mx/LeyesBiblio/pdf/LAmp_150618.pdf
#Code #1




The base of this article is the natural language processing 

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
considering its pros and cons.

In the first code example,stemming was able to transform more words than lemmatizing, but even this is far from perfect.

from sklearn.feature_extraction.text import CountVectorizer 
CountVectorizer is a tool provided by the sklearn sciket-learn librarary in Python that saves all the the effort perfomedin the previos section and provides application prograamming interfeces (APIs) 
that would convently help in buildingA BoW model.


It converts a list of text documents into a matrix such that entry in the matrix would correspond to the count of a particular token in the respective sentenes. Let's look at how to isn

from sklearn.feature_extraction.text import CountVectorizer
It converts a list of text documents into a matrix such that each entry in the matrix would correspond to the count of a particular token in the respective sentences. Let's look at how instantiate CountVectorizer and fit data to it in the code. 


from nltk.tokenize import word_tokenize 
from nltk.stem import WordNetLemmatizer 

from nltk.stem import PorterStemmer
from nltk.tokenize import word_tokenize 

Fore more information read Hands on Python Natural Language Preprocessing that would help in building BoW model.






