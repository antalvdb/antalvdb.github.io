# Lectures

(lecture1)=
## Lecture 1: Introduction and a brief history of neural networks

This lecture maps a travel route past the three waves of neural
network hype: the Perceptron era, the Back-propagation era, and the
Deep learning era. It sketches the evolution from Jeff Elman's
recurrent neural nets {cite}`Elman1990` to GRUs {cite}`Cho2014a`,
LSTMs {cite}`10.1162/neco.1997.9.8.1735` and the Transformer
{cite}`10.5555/3295222.3295349`.

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQxT-bCUZgsRhxZnUugaesEahWdAMPLuMiCQ-brO-WZJo4CGEW0urzRs3Sv_PQOADDN0-u6Y2YfzW7-/pubembed?start=false&loop=false&delayms=60000" frameborder="0" width="780" height="484" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

(lecture2)=
## Lecture 2: Transformers: Key concepts and building blocks

This lecture is accompanied by {ref}`notebook2`.

The Transformer {cite}`10.5555/3295222.3295349` is the current best
solution to predicting the next word, with autoregression and an
impressive method to keep track of all things that matter in the input
seen so far, *attention*. This lecture introduces the key concepts and
building blocks of the Transformer architecture.

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRCTGAFcNirv9hwFCb5C6FEYiyswahd_v1tuLhbdghE9tiWZB3S-HfYFhAWKektJvJYKlMnjGD028Ag/pubembed?start=false&loop=false&delayms=60000" frameborder="0" width="780" height="484" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

(lecture3)=
## Lecture 3: Transformers recap, In-context learning, Post-training, Agents

This lecture is accompanied by {ref}`notebook3` and {ref}`notebook4`.

After a short recap of the Transformer architecture, we dive into
aspects of training Transformers beyond pre-training: in-context
learning and post-training. We also talk about putting LLMs to work as
agents. We conclude with two frequently-used Transformer features: the
mixture-of-experts architecture and LoRA.

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQfTajMvhhw38ocjv3JpneVrzvmLnl0_1eyAIKShwiuiGJPxiYotCbSBfQ7JVAkly2IK712hXyTsEU4/pubembed?start=false&loop=false&delayms=30000" frameborder="0" width="780" height="484" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

(lecture4)=
## Lecture 4: Efficient LLMs

This lecture is accompanied by {ref}`notebook5` and {ref}`notebook6`.

LLM efficiency is a big issue; the size wars of the commercial LLM
providers, predictable from the scaling laws of Transformers, are
softened by smart countermeasures that optimize aspects of the LLM
architecture and processes. Not being able to ever be complete, this
lecture covers a mixture of methods such as flash attention, PEFT, KV
caching, distillation, and speculative decoding.

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vT19vXigOGa_7uajcubu3qBgWuj1Trr4YJ8m09Vssrs6-Q0F5hrAKReqWv6kc7Z5QZFKCPUGlPW164O/pubembed?start=false&loop=false&delayms=60000" frameborder="0" width="780" height="484" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

(lecture5)=
## Lecture 5: Benchmarking LLMs

This lecture is accompanied by {ref}`notebook8`.

Evaluating LLMs is not a simple matter. Many evaluation metrics and
benchmarks that emerged from the field of natural language processing
are still usable, but the capabilities of chatbots based on
autoregressive encoder Transformers have
spawned an entirely new type of benchmark task that increasingly looks
like the tests we took at school or in college.

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vTx50M8aMrWu8z1hSqoJZLgkwAG1R7wBEllRo8KhXIlEJ3EpxrpwuP7gwfngkPFUJ_E9CDfX7FVF59Y/pubembed?start=false&loop=false&delayms=60000" frameborder="0" width="780" height="484" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

(lecture6)=
## Lecture 6: Data, bias, alignment

Data is a key ingredient to training and fine-tuning
Transformers. What do we know from language data, and what does Zipf's
law predict? If commercial LLMs are trained on trillions of tokens,
where does all that data come from? What type of biases occur in them,
can we detect and mitigate them? Chatbot developers typically *want*
to mitigate bias because they want there models to be aligned with the
values and expectations of users. How to align a chatbot - or, how to
turn a next-token predictor into a helpful dialogue partner?

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQ32RvAo6yKyRuiE97qADMOB918EOd0ykkJ0yg---ZvlnDRQT4c8k2ssU355yEz9FjnP1ZID8SM4yAk/pubembed?start=false&loop=false&delayms=60000" frameborder="0" width="780" height="484" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

(lecture7)=
## Lecture 7: Reasoning in LLMs

This lecture is accompanied by {ref}`notebook7`.

LLMs are to some extent capable of reasoning. One way is by running an
internal dialogue, a 'chain of thought', thereby allowing building a
reasoning chain in multiple hops. Within bounds they can even reason
by propagation of information in the internal graph of the Transformer
architecture. In this lecture we talk about both these types of
implicit and explicit reasoning.

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vTMKm8w_4mPGGRfG3SC8EaDRj0HZQjzCIFLX5Ahl5ymgV8lvpwe3RqkMQ2RpmGsGDpXQvsZE3ZxBBLJ/pubembed?start=false&loop=false&delayms=60000" frameborder="0" width="780" height="484" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

(lectureguest)=
## Guest Lectures

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
(Utrecht University) talks about the *governance of
Transformers*, introducing a thought-provoking contrast between the
*relentless computing* of commercial AI, versus a *conditional
computing* practice that would allow governments to stimulate the
development of AI conditioned on the return of public value.

<iframe src="docs/Ferrari-2026.pdf"
   width="780" height="484">

(lecturediff)= [Ruurd
Kuiper](https://research.umcutrecht.nl/researchers/ruurd-kuiper/)
introduces the topic of diffusion-based LLMs, an idea that deviates
from the standard left-to-right autoregressive text generation
framework of decoder Transformers. Instead, diffusion-based LLMs
generate a full text, by starting with a block of fully masked text,
and iteratively unmasking and generating sub-parts of the full text.

This lecture is accompanied by {ref}`notebook10`.

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vT03k6-uZZxphOG0iX38bHM3fW7dSX6x_0-07yIKr2CmGbTK-5VFsDQPuUg36_UHOuNRYQ_ZDRqzDSQ/pubembed?start=false&loop=false&delayms=60000" frameborder="0" width="780" height="484" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>


(lecturemisc)=
## The Mixed Bag Lecture

There are so many more interesting topics to cover that are impossible
to fit in a single teaching block. In this lecture we scoop up some
miscellaneous and related topics such as Mixtures of Experts,
watermarking and fingerprinting, the predictive brain in cognitive
neuroscience, and [TESCREAL](https://en.wikipedia.org/wiki/TESCREAL).

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQ3KbJAKnz06R1xIy-j6WZpjq0DyeFfUfVbuPoohfNlqcm2ZlF7y9ojJLd3D75wduc3qmjU0hyCc9u6/pubembed?start=false&loop=false&delayms=60000" frameborder="0" width="780" height="484" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

