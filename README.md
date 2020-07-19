# TV Script Generation

This project was developed under the Deep Learning degree program of Udacity. We make use of Recurrent Neural Networks to create an automatic script generator for a TV series. 

![Imgur](https://i.imgur.com/oFn36NB.png)

       
## Recurrent Neural Network 
We implement the RNN using PyTorch's Module class. Additionally, use LSTM cells. 
\
\
\
\
![Imgur](https://i.imgur.com/fzasvdH.png)
\
\
\
**Training parameters**

```
num_epochs = 10 
learning_rate = 0.001
vocab_size = len(vocab_to_int) 
output_size = vocab_size
embedding_dim = 250
hidden_dim = 250
n_layers = 2
show_every_n_batches = 1000
```


# Dataset

Can be found on [Kaggle](https://en.wikipedia.org/wiki/Seinfeld).

*A dataset for people who love data science and Seinfeld.*\
There are complete scripts of 9 seasons of the series.

# Result - A Script Generated for Seinfiled
\
\
\
![Imgur](https://i.imgur.com/YwM33ee.png)


\
\
**The Script:** Its not perfect but quite impressive!
---
\
*jerry:...(she makes a clicking sound with her mouth)*

*jerry:(to george) oh my god, what are you doing?*

*jerry: i don't know. you know what i mean?*

*george: no.*

*george: you know, i don't know what you do.*

*george: well, you know, i think it's not a mistake.*

*elaine: well, i guess i'll tell you.*

*jerry:(to kramer) hey.*

*jerry: hi. how 'bout a date?*

*elaine:(to kramer) hey, hey!(jerry looks at her watch.)*

*kramer:(looking at the bathroom) oh, i can't believe this.*

*kramer: well, i'm sorry, you know what?*

*helen: what?! i don't know what i said.*

*elaine: what? i mean, i know what the hell do you mean?*

*jerry: yeah, yeah.*

*george:(to kramer) hey...*

*kramer: hey, jerry!*

*jerry: hey. hey, i don't know.*

*kramer: well, it's just that i can't take a bite.*

*jerry: what is that smell?*