# Lectures

(lecture1)=
## Lecture 1: Introduction and a brief history of neural networks

This lecture maps a travel route past the three waves of neural
network hype: the Perceptron era, the Back-propagation era, and the
Deep learning era. It sketches the evolution from Jeff Elman's
recurrent neural nets {cite}`Elman1990` to GRUs {cite}`Cho2014a`,
LSTMs {cite}`10.1162/neco.1997.9.8.1735` and the Transformer
{cite}`10.5555/3295222.3295349`.

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQsDs8NCjltv9oMxhV61KXKRFUyJ6hvq9gJ6gwcEwoIWX1QHM6l5HUvO636qyG3XHh9L2wBixcMqNP6/pubembed?start=false&loop=false&delayms=60000" frameborder="0" width="780" height="484" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

(lecture2)=
## Lecture 2: Transformers: Key concepts and building blocks

The Transformer {cite}`10.5555/3295222.3295349` is the current best
solution to predicting the next word, with autoregression and an
impressive method to keep track of all things that matter in the input
seen so far, *attention*. This lecture introduces the key concepts and
building blocks of the Transformer architecture.

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQHY0smV_pf2zUBAn-cSDNTiY_CxzdNqQz1svPLcUbA3Muh-GFATFy280LrgCu5lu6dAKRCMjmMUJbA/pubembed?start=false&loop=false&delayms=60000" frameborder="0" width="780" height="484" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

(lecture3)=
## Lecture 3: Transformers recap, In-context learning, Post-training, Tools and agents

After a short recap of the Transformer architecture, we dive into a
select number of unique aspects of training Transformers: in-context
learning and post-training.

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQrHB_THbDDvlR7smOM6TzrblZZ4BvEnS4TUv-0GRiMUoEDG4HmhbSTBz1DQwWeXIsc_28wmxMvm-JB/pubembed?start=false&loop=false&delayms=60000" frameborder="0" width="780" height="484" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

(lecture4)=
## Lecture 4: Benchmarking LLMs

Evaluating LLMs is not a simple matter. Many evaluation metrics and
benchmarks that emerged from the field of natural language processing
are still usable, but the capabilities of chatbots based on
autoregressive encoder Transformers (so-called Generative AI) have
spawned an entirely new type of benchmark task that increasingly looks
like the tests we took at school or in college.

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vSVB7NL9254N3hemwZy3o6pHjatOKY_i1fjPl1_e4WTndE2mPbz-5gpJkc8g5F1LXLs3YeEN56Vdpyk/pubembed?start=false&loop=false&delayms=60000" frameborder="0" width="780" height="484" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

(lecture5)=
## Lecture 5: Data, bias, alignment

Data is a key ingredient to training and fine-tuning
Transformers. What do we know from language data, and what does Zipf's
law predict? If commercial LLMs are trained on trillions of tokens,
where does all that data come from? What type of biases occur in them,
can we detect and mitigate them?

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vSnhPPkLkRBv4eG5etjYcJwOyfftEN1nkO5T-wr_c5Kpc17bTx_FGQMSskPgxIib1b2qsT3T9MrhGR9/pubembed?start=false&loop=false&delayms=60000" frameborder="0" width="780" height="484" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

(lecture6)=
## Lecture 6: Efficient LLMs

This lecture is accompanied by {ref}`notebook6`.

LLM efficiency is a big issue; the size wars of the commercial LLM
providers are fortunately complemented with smart countermeasures that
optimize aspects of the LLM architecture and processes. Not being able
to ever be complete, this lecture covers quantization, speculative
decoding, the Chinchilla scaling law, and parameter-efficient
finetuning (PEFT).

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vSgWdDJiLWw7UCszgLmf0Gyewj7JSDYwPH-IQM5OiwZvkVF_aIHfHRJ4vVJVE2Gam_6_UGIxYA0-g02/pubembed?start=false&loop=false&delayms=60000" frameborder="0" width="780" height="484" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

(lecture7)=
## Lecture 7: Reasoning in LLMs

This lecture is accompanied by {ref}`notebook7`.

LLMs are to some extent capable of reasoning. One way is by running an
internal dialogue, a 'chain of thought', thereby allowing building a
reasoning chain in multiple hops. Within bounds they can even reason
by propagation of information in the internal graph of the Transformer
architecture. In this lecture we talk about both these types of
implicit and explicit reasoning.

<iframe
src="https://docs.google.com/presentation/d/e/2PACX-1vS34Qm_ZF0nNnB7FvT5ki2PRImW6i1vuHqN-q6X8DILVZMgSVoeCWYgqpCGAO2TZXd3fsfWtmdiSjdV/pubembed?start=false&loop=false&delayms=60000"
frameborder="0" width="780" height="484" allowfullscreen="true"
mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

(lectureguest)=
## Guest Lectures (2025)

[Lukas Edman](https://leukas.github.io/cv/) (TU Munich) talked about
tokenization, the essential first step in the training process:
inducing, from training text, a limited token vocabulary consisting of
words, subwords and/or characters, and then tokenizing the raw textual
training material according to this vocabulary, of which the
dimensions are a major factor in neural LLMs. Lukas covers BPE for
token vocabulary induction and spends time asking the question what
could be the benefits of the most extreme tokenizer of all: the
character or byte-level tokenizer.

<iframe
src="https://docs.google.com/presentation/d/e/2PACX-1vQ1BMBiQQIGjgr4s1Qsxj7PbITO2WxMcaNNLrb8zx8Tvt6H1rFr3QB-x_bjc7P7NxvmUbRdU-YvZ_kN/pubembed?start=false&loop=false&delayms=60000"
frameborder="0" width="780" height="484" allowfullscreen="true"
mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

[Fabian Ferrari](https://www.fabianlferrari.com/)
(Utrecht University) gave a lecture on the *governance of
Transformers*, introducing a thought-provoking contrast between the
*relentless computing* of commercial AI, versus a *conditional
computing* practice that would allow governments to stimulate the
development of AI conditioned on the return of public value.

<iframe
src="https://docs.google.com/presentation/d/e/2PACX-1vS743TK5C54h9Ho0r0BtzocTl1B1emaYzIZMm75iOEA7puA3_UXbE8WljTskByLPZ61XIPrV3BhEXb3/pubembed?start=false&loop=false&delayms=30000"
frameborder="0" width="780" height="484" allowfullscreen="true"
mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

(lecturemisc)=
## The Mixed Bag Lecture

There are so many more interesting topics to cover that are impossible
to fit in a single teaching block. In this lecture we scoop up some
miscellaneous and related topics such as Mixtures of Experts,
watermarking and fingerprinting, the predictive brain in cognitive
neuroscience, [TESCREAL](https://en.wikipedia.org/wiki/TESCREAL).
Which topics will we cover in next year's mixed bag lecture?

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vSeSn4TJXrX2lW9RUV87LwywfkczSmwKOsS6minER7YNS7XylMZCCOF1fFUzh97P37un4x1ggCEzxjj/pubembed?start=false&loop=false&delayms=60000" frameborder="0" width="780" height="484" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

