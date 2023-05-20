# nanogpt
Learning and modifying [nanogpt](https://github.com/karpathy/nanoGPT) by Andrej Karpathy.

## Result

Result of few minutes of pretraining on `tiny_shakespeare` dataset with train loss around `1.5` and validation loss `1.7`. Dropout needs to increase to reduce overfitting as after train loss around `1.7` the validation loss starts diverging. 

### Hyperparameters

These hyperparameter used for generation below result.

```
batch_size = 64
context_length = 256
train_iters = 4000
eval_iters = 30
learning_rate = 6e-4
embed_dim=256
num_heads=4
dropout=0.2
```

### sample generation

```
All the have use Of the prare did use:
I three, who I said is teach I do good his the.

DUCHERD:

There's to the love, perdony well well the won:
O, to thy mine my day elatt woound say to't.

HASTINGS:
The she us countols to do't, I chargefull friends and must these,
That fulloward gentle time, aitting being dukes,
With of more too beg a liken betch antirmented.

WARWICK:
Then deliven she tooo? How!
Hold host wisere! custsited Perbray? contry we it Yed.

PAULINA:
My noise saleve: let sould brother. Your Mortain'd lourshut thou holpe?
The trous too firstaful his banishal to bain,
Yet my liege, this a me, in untword, so my socouss,
Offtunly'd end. their by odds: say monst arther.

AUTOLYCUS:
O, like.

DUKE VINCENTIO:
Whose in they loe, the bears was seats's king?

HENRY BOLIMNGO:
There their
```



## References
- https://github.com/karpathy/nanoGPT
- https://github.com/karpathy/char-rnn
- https://www.youtube.com/watch?v=kCc8FmEb1nY
- https://github.com/karpathy/minGPT
