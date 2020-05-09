

Persian NLP Framework
=========================

## For educational purposes
In this project, high simplicity and readability have been very important And suitable for better understanding Persian doc processing algorithms.
In this project, all the modules are written in the simplest possible way. This project is completely modular, which gives it a high modify capability. 

#### The capabilities of this framework are:
1. Reading Xml Dataset
2. Tokenize Sentences
3. Removing Stopwords
4. Replacement method 
    >-Ali : $Ali - li$A - i$Al
5. Posting compression
6. Dictionary compression
7. save dict and posting in BTree for fastest and better performance
8. Query Search Engine Optimize

After all this project is fully Compatible with Google colaboratory.

let see some example :
<i>
>model = Sequential() <br />
>model.add(ReaderXML(["Source/NewXML1.xml"],[ "TEXT" ]))<br />
>model.add(Tokenizer())<br />
>model.add(StopWord(stop_words))<br />
>model.add(Dictionary())<br />
>model.add(Replacement())<br />
>model.add(Posting())<br />
>model.add(PostingCompress("Gama"))<br />
>model.add(Compress("Full"))<br />
>model.add(BTree("Full"))<br />
    </i>

every single module has documentation and examples.
