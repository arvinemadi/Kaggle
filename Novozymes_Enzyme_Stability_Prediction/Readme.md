The notebook shows the process. It has been cleaned up a little. But we still could not get good score on the leader board. It is either that the distribution of the competition test data is very different or that we are missing something about loading and uploading the test data. On our test_data split the score is very good.

Tried many things on the process and the notebook has been cleaned up. Things tried in this note book:

- ESM embedding for Protein sequences from [Facebook](https://github.com/facebookresearch/esm) and use it as base of transfer learning 
- Regression techniques
- kNN regression
- Regression in based on siamese networks and similar to TNN (Twin Neural Network) [Reference](https://arxiv.org/pdf/2012.14873.pdf)

Although it may not work and we cannot get good score from leaderboad, it was a good excersice to try different things. In the process learnt a lot about memory management and clean-up for cuda and become much faster in setting up dataloaders and training with pytorch.



