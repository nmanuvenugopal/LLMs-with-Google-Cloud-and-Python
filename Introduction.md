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

Once all the text is converted to the tokens, the encoder component of the transformer model is convert or encode the token to a internal representation and the internal representation is going to be n-diamensionsal vector. So, each token will have corresponding n-diamentional vetor and it is quite large.
![image](https://github.com/nmanuvenugopal/LLMs-with-Google-Cloud-and-Python/assets/99719105/e29475ca-d8c9-4c32-bbf4-29b8a3205fc9)

Then we can use these embedded data with LLM for variety of tasks such as classification, generation etc. In our case, what LLM do is that, it will show the probabilities for the vectors that going to show up after this text (from the below figure, the first vector has the 45% probability of showing next and the second has 32% showing up next.).
![image](https://github.com/nmanuvenugopal/LLMs-with-Google-Cloud-and-Python/assets/99719105/6428f0c6-9ea8-40ce-87bf-d2ebcd4986b4)

It is quite hard to understand the vector represntation of each token or word, then we will do the reverse of above startegy. This can be attained by using the decoder component of the transformer model, whattransfomer model does is that it will convert the embedded text back to the original text format.
![image](https://github.com/nmanuvenugopal/LLMs-with-Google-Cloud-and-Python/assets/99719105/b693f581-2538-447c-b945-809d80d7eb80)

ref: LLMs with Google Cloud and Python, Jose Portilla, Udemy






