## seq2seq chatbot links

> *Note: the repository is not maintained. Feel free to PM me if you'd like to take up the maintainance.*

Links to the implementations of neural conversational models for different frameworks.
Contributions are welcomed.

___
**Tensorflow**

##### [Conchylicultor/DeepQA](https://github.com/Conchylicultor/DeepQA)
Awesomely nice results:

    Hi			            	→ Hi.
    What is your name ?			→ Laura.
    What does that mean ?		→ I dunno.
    How old are you ?			→ thirty-five.

Along with the decent ones:

    Who is Laura ?				→ My brother.
    Say 'goodbye'				→ Alright.
    Two plus two				→ manny...

##### [nicolas-ivanov/tf_seq2seq_chatbot](https://github.com/nicolas-ivanov/tf_seq2seq_chatbot)
Modified code of [machine translation model](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/models/rnn/translate).
No answering randomisation is implemented in this code, so the models answers with the same phrase way each time:

    hello baby					→ hello
    how old are you ?			→ twenty .
    i am lonely					→ i am not
    nice						→ you ' re not going to be okay .
    so rude						→ i ' m sorry .
    are you a robot or human?	→ no .
    are you better than siri?	→ yes .

##### [inikdom/neural-chatbot](https://github.com/inikdom/neural-chatbot)
No good results so far.

___
**Torch**
##### [macournoyer/neuralconvo](https://github.com/macournoyer/neuralconvo)
One of the best results currently achieved with an open-sourced Seq2seq implementation:

    Hello?					→ Hi.
    How are you?			→ I'm fine.
    What's your name?		→ It's hard to describe.
    How so?					→ I'm not sure.
    What color is the sky?	→ It's blue.
    What is your job?		→ It's not that i'm a fucking werewolf!

___
**Keras**

##### [farizrahman4u/seq2seq](https://github.com/farizrahman4u/seq2seq)
The most popular implementation of Seq2seq architecture on GitHub. 
However, there is still no evidence of getting good results with this repo.

##### [nicolas-ivanov/debug_seq2seq](https://github.com/nicolas-ivanov/debug_seq2seq)
A wrapper for [farizrahman4u/seq2seq](https://github.com/farizrahman4u/seq2seq) used for running experiments. No good results were achieved so far.

##### [codekansas/keras-language-modeling](https://github.com/codekansas/keras-language-modeling)
Need to check this up.

##### [oswaldoludwig/Seq2seq-Chatbot-for-Keras](https://github.com/oswaldoludwig/Seq2seq-Chatbot-for-Keras)
A new model of generative chatbot whose training converges in few epochs, including a model pre-trained on a small but consistent dataset collected from dialogues of English courses online.

    user: Hello! How are you?
    computer:  i am fine , ok , well , thank you  .    (with probability of 0.540239)
    user: What's your name?
    computer:  janet .     (with probability of 0.319482)
    user:  What do you like to do now?
    computer:  let me think a minute .     (with probability of 0.286760)
    user: I want to chat about computer science.
    computer:  i am glad to hear there .     (with probability of 0.293063)
    user: Are you a real girl or a computer program?
    computer:  i am self employed . i would love to be well .     (with probability of 0.026870)
    user: Why don't you look for a job?
    computer:  i do not know . i am the bank .     (with probability of 0.053494)
    user: So, you don't need a job!
    computer:  no . i have to make a lot of money .     (with probability of 0.001279)


## Corpora
##### [AlJohri/OpenSubtitles](https://github.com/AlJohri/OpenSubtitles)
Get a lot of raw movie subtitles (~1.2Gb)

##### [Cornell Movie-Dialogs Corpus](http://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html)
~ 40Mb after clearing out the technical data.


## Papers

* [\[1\] Sequence to Sequence Learning with Neural Networks][1]
* [\[2\] A Neural Conversational Model][2]

[1]: http://papers.nips.cc/paper/5346-sequence-to-sequence-learning-with-neural-networks.pdf
[2]: http://arxiv.org/pdf/1506.05869v1.pdf
