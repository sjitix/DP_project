
In this project I want to analyse whether LLMs charge some languages more than others, due to using more tokens. 
Since they are mostly built on English text, the same sentence can need many more tokens in another language, which makes it more expensive. 
The research question is: does the same text cost more tokens in some languages, and is this linked to  the web presence of that language? 
I will take one text that exists in a few hundred languages and count how many tokens each language needs compared to English, using a tokenizer.
Secondly, I will check if languages with a smaller Wikipedia ( less web presence) need more tokens.
I also have the goal of building my own simple tokenizer to show that a language gets cheaper when the tokenizer learns from more text in that language.
