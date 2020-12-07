# MAML Handwriting Test

Experiments on few shot MAML classification with a bunch of handwritten digits. Using the [Learn2Learn](https://github.com/learnables/learn2learn) Package for Meta-Learning.

```Meta Omniglot with MAML.ipynb``` - contains code to train a MAML model on the Omniglot Dataset and save the model onto a file.

```[Testing] Meta Omniglot with MAML.ipynb``` - Tests the meta-trained model on 15 handwritten digits (1 to 5).


## Digits

![alt text](https://github.com/joeljosephjin/maml-handwriting-test/blob/main/hand5.png "Handwritten Digits")


## Results

### Meta-Testing Training Loss (MAML) for five steps

```
0 11.376582145690918
1 6.310839653015137
2 3.8237736225128174
3 1.8176089525222778
4 0.8511329889297485
```

### Meta-Testing Testing Loss (Random Initialization) for five steps

```
0 9.94571590423584
1 7.830267906188965
2 6.406075477600098
3 3.634197235107422
4 1.3334368467330933
```

### Meta-Testing Testing Loss (MAML)
```
21.9514
```

### Meta-Testing Testing Loss (Random Initialization)
```
21.7752
```
