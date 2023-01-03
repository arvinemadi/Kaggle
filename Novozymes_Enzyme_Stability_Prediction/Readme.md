The notebook shows the process. It has been cleaned up a little. But we still could not get good score on the leader board. It is either that the distribution of the competition test data is very different or that we are missing something about loading and uploading the test data. On our test_data split the score is very good.

Tried many things on the process and the notebook has been cleaned up. Things tried in this note book:

- ESM embedding for Protein sequences from [Facebook](https://github.com/facebookresearch/esm) and use it as base of transfer learning 
- Regression techniques
- kNN regression
- Regression based on siamese networks and similar to TNN (Twin Neural Network) [Reference](https://arxiv.org/pdf/2012.14873.pdf)

Although it may not work and we cannot get good score from leaderboad, it was a good excersice to try different things. In the process learnt a lot about memory management and clean-up for cuda and become much faster in setting up dataloaders and training with pytorch. Also it seems to do well in such projects we need more memory and faster GPU ;)

OK. I tried several other things but the highest score that I got was 0.17/1.00. I think I give up at this point. People pn the discussion board have reported that nobody got a score better than 0.2 by only using the provided train dataset on Kaggle. Instead they loaded and added train data from other spurces, things like list of mutations etc. Well, that is the problem of this type of competitions when other datasets are OK to use, it would need a high domain knowledge of the field, in this case protein engineerg. I did not want to add other data and I thought that the competition is fair that you can at least get a decent score by using the provided training dataset. If it was not possible why was it even provided, they could just say find training dataset yourself!

Anyway, It was an OK exercise, but next time I see that external data can be used I would be a bit more careful how much time and effort I would put into that.




