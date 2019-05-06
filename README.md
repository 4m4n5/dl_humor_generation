# dl_humor_generation
pytorch implementation of encoder decoder with attention for humorous captioning.

Natural language is used in day to day life to evoke and convey thoughts, feelings, and emotions. One of the emotions commonly expressed through language is humor. It is a universal phenomenon that occurs in all languages and has a wide appeal. With the advent of social media platforms, new forms of creative expression such as memes[1] and gifs have become really popular. 

Generating humor is challenging because it is not always direct. It can have different styles such as sarcasm, satire, irony etc. In the context of memes, the joke has to be expressed in a few words, usually 20 or less and support the background image. Hence, the syntax of the language used in memes is different and does not follow the conventional language structure.

In this project, we introduce a model using encoder-decoder framework with attention mechanism to generate memes where the attention mechanism is applied on a abstract vector space representing the image and thematic linguistic representation of the meme. 
