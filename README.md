# LLMs-with-Google-Cloud-and-Python

In this section we will be using the PaLM2 model from Google. It is well known for its ability to
1. Write code and solve mathematical problems.
2. Classify inofrmations.
3. Question and aswering system.
4. Translate and understand different languages.
5. Generate texts.

PaLM do great job in identifying and mitigating the potential biases and harmful outcomes. 

Full transfomer consist of 
1. Encoder - which convert the input text to the intermediate representation, often known as embedding.
2. Decoder -  which convert the intermediate represenation back to the input text.

One of the key concept that we need to be aware about when learning about the Transfomer model is "self-attention" mechanism. Imagine each word in a sentence thinking about its relation to every other words. In simple way we can say self attention means each word asking "How much should I care about the every other word in this text?". for example, let's consider this example "The animal didn't cross the street beacuse it was too tired. In this sentence there are 11 words, each 10 words will be thinking and trying to figure out its relationship with them. A clear instance is that of word "it" in the above sentence. sometime it is not not clear what "it"is pointing to. Is "it" talking about the animal or street.

This is where the self attention mechanism comes in handy. It helps the models to decide which word or token are most relevant or connected to the word "it".





