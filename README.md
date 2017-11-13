# Is a complete sentence

In previous work, we have to keep the sentence quality, including completeness. I have nothing to do about it because the working system is just a batch of scripts full of regex or words.

I'm wondering how to model model a sentence whether is complete.

I think, from statistic attitude, we can statistic a complete sentence's ends N-grams. So according to the probability of the rear part of the sentence, we may can give a conclusion. But only N-gram probability is not enogh, or in other words, it is hard to make a threshold to let us predict.

A simplest thought is use NN to do a binary classification:

A network receive the rear part of sentence, and predict is is a complete sentence's probability.

It may be OK!

# steps

[ ] build dataset
[ ] pre-trained nn
[ ] choice rear part sentence's representation.
[ ] choice loss
[ ] write code and run (trying to use PyTorch)


# details

1. build dataset

`TODO`
