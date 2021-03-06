---
inFeed: true
description: >-
  Redreamer is an experiment in artificial intelligence and dreams. Using a
  recurrent neural network trained on a decade’s worth of dream journals this
  machine is recurrently dreaming, redreaming, dreaming new, fresh entries.
dateModified: '2018-03-19T17:31:35.234Z'
datePublished: '2018-03-19T17:31:35.852Z'
title: ''
author: []
publisher: {}
via: {}
sourcePath: >-
  _posts/2018-03-18-redreamer-is-an-experiment-in-artificial-intelligence-and-dr.md
hasPage: true
starred: false
datePublishedOriginal: '2018-03-18T20:00:54.568Z'
url: redreamer-is-an-experiment-in-artificial-intelligence-and-dr/index.html
_type: Article

---
Redreamer is an experiment in artificial intelligence and dreams. Using a recurrent neural network trained on a decade's worth of dream journals this machine is recurrently dreaming, redreaming, dreaming new, fresh entries.

While many deep learning projects focused on natural language processing use large datasets in order to better imitate a broader range of conversational dialogue, this project is focused on a very specific corpus: my dream journals from roughly 2010-2018\. This is a relatively small set of data at only a few hundred pages of typed text. It's also a peculiar dataset because it is in the language of dreams, which doesn't strictly make sense, and which includes dialogue, description, and uncertainty.

The project is also meant to raise questions of authorship, experience, and the self. Am I the author of the work if the machine is trained on my work? There are other projects using similar technology that ask the same question: [DeepBach][0] generates music in the style of Bach, while [TensorFlow RNN Shakespeare][1] creates novel Shakespearean text in the same way the REDREAMER Project works. Is a DeepBach chorale a Bach chorale? Is a TensorFlow Shakespeare script written by Shakespeare? Are these dreams my own?

Maybe even more pressing than the question of authorship is the question: "Can an algorithm dream?" The question is whether or not there is anything truly different between the black box of a deep learning algorithm and the black box of the brain. Like the brain, this machine is given a set amount of input --- or experience --- and tries to process and make sense of that experience. The making sense for humans happens during sleep, and the making sense for a recurrent neural network happens during training.

As the neural network approaches an error rate of 0 it more accurately makes sense of the dataset it's been given. It notices patterns and is able to make better predictions about what one word comes after another, how sentences should fit together, how phrases make sense in context. Using this ability to predict it is able to produce novel text.

The texts of the REDREAMER Project are generated by this neural network. While the network can produce as much or as little text as requested, these small pieces illustrate the strange logic and poetic language of dreams, and the subtle off-ness of the AI generated text, which seems to be able to make sense, until it breaks the rules of grammar and convention.

This project uses a recurrent neural network built written in Python using Tensorflow. It's based on [this model][2] which was originally used to create novel scripts as part of a Udacity Deep Learning course. [The GitHub for the project can be found here.][3]

[0]: http://www.flow-machines.com/deepbach-polyphonic-music-generation-bach-chorales/
[1]: https://github.com/martin-gorner/tensorflow-rnn-shakespeare/blob/master/rnn_train.py
[2]: https://github.com/udacity/deep-learning/tree/master/tv-script-generation "TV Script Generation Github"
[3]: https://github.com/lfhvn/REDREAMER