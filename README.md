# Named-Entity-Recognizer

In Natural Language Processing (NLP) an Entity Recognition is one of the common problem. The entity is referred to as the part of the text that is interested in. In NLP, NER is a method of extracting the relevant information from a large corpus and classifying those entities into predefined categories such as location, organization, name and so on. Information about lables:

geo = Geographical Entity

org = Organization

per = Person

gpe = Geopolitical Entity

tim = Time indicator

art = Artifact

eve = Event

nat = Natural Phenomenon

In this project, I have built the named entity recognizer uing spacy to extract the transaction amount and vendor details from the transaction sms. Spacy is an open-source NLP library for advanced Natural Language Processing in Python and Cython. It's well maintained and has over 20K stars on Github. There are several pre-trained models in Spacy that you can use directly on your data for tasks like NER, Information Extraction etc. But I have trained a custom spacy model to incorporate my own custom entities.
