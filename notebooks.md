# Notebooks

(notebook1)=
## Notebook 1: Basics; and how to fine-tune a text classifier.

[Run this Notebook on Colab](https://colab.research.google.com/drive/1aAvxhsVmM2-OoDn6Fs1gSY3P_xbNmDdT?usp=sharing).

This course introduces you to Transformers, a class of deep learning
neural networks based on the Transformer architecture. Although this
architecture was introduced relatively recently
{cite}`10.5555/3295222.3295349`, history did not start in 2017. Many
of the components in and ideas behind the Transformer have a history
that harks back to the first wave of neural network research
{cite}`mcculloch43a,rosenblatt1958,minsky1969`, as well as the second
wave {cite}`rumelhart86,Elman1990`.

In some of the following notebooks we follow, broadly, the book
[Natural Language Processing with
Transformers](https://www.oreilly.com/library/view/natural-language-processing/9781098136789/),
by 🤗 staff members Lewis Tunstall, Leandro von Werra, and Thomas
Wolf. See the [full notebook
collection](https://github.com/nlp-with-transformers/notebooks) for
this book.

(notebook2)=
## Notebook 2: Text generation with GPT

[Run this Notebook on Colab](https://colab.research.google.com/drive/1MxJucIR3UL9YbGiTmkD6ZMwJeL8dM3Ie?usp=sharing)

In {ref}`lecture1` we talk about different types of transformer-based
models. But before we dive in, we wanted to take some time to look at
one particular type of models in more detail: models trained for text
generation. These are the models that became most prominent recently,
because they lie at the core of all the amazing and popular large
language models that have been taking the world by storm in the last
couple of years (think [ChatGPT](https://chatgpt.com/),
[Claude](https://claude.ai/),
[LLaMa](https://www.llama.com/models/llama-4/),
[DeepSeek](https://www.deepseek.com/en) etc.). Later, we will talk in
some detail about how these modern interactive models relate to the
basic text-generating models like the one we will look at in this
notebook.

We are going to explore text generation with GPT-style
Transformers. This notebook loosely follows Chapter 5 of the Natural
Language Processing With Transformers book, and its associated
notebook. This notebook introduces you to some concepts related to
generating text, and features two exercises:

* The first exercise focuses on hyperparameters for text
generation (in particular, temperature).

* The second exercise is about testing the capacities of GPT-2, the
predecessor of GPT-3 and 4, in your native language.

We are using the [GPT2 model on Hugging
Face](https://huggingface.co/openai-community/gpt2). If your runtime
engine allows it, you may also try the larger models GPT-Medium,
GPT-Large, or GPT-XL. Performance quality tends to go up with larger
models.

(notebook3)=
## Notebook 3: The Transformer Anatomy Lesson

[Run this Notebook on Colab](https://colab.research.google.com/drive/1sb_S_oAQWvU-hlXcTqCtzaSWFsH0q-bw?usp=sharing)

This notebook consists of two parts:

* PART I: Implement a full transformer encoder in PyTorch. Note that
  we will not train it. In this implementation, we pretty closely
  follow Chapter 3 of the [Natural Language Processing with
  Transformers](https://www.oreilly.com/library/view/natural-language-processing/9781098136789/)
  book.

* PART II: Visualizing attention, in which we use the 
  [bertviz](https://github.com/jessevig/bertviz) library to visualize
  internals of
  [bert-base-uncased](https://huggingface.co/google-bert/bert-base-uncased),
  a pretrained BERT model.

(notebook4)=
## Notebook 4: Tokenizers and Tools

[Run this Notebook on Colab](https://colab.research.google.com/drive/1ve_gtqXIyN1W2KOwP5SRb7LhcB-cLEtH?usp=sharing)

This notebook consists of two parts that have to do with the two
different topics covered in {ref}`lecture4` and Lukas Edman's
{ref}`lectureguest` on tokenization:

* PART I: **Tokenization and character-level information**. In
  {ref}`lecture4` we discussed standard practices of text tokenization
  for recent transformer language models. In particular, the most
  common subword tokenization algorithm, BPE, was
  introduced. Additionally, we discussed character-level tokenization
  as an alternative to subword tokenization algorithms.

* PART II: **Tools and agents**. LLM output can be used to trigger
  external instruments, such as web search, calculator etc. The output
  of running these external instruments then can be fed back to the
  LLM and may further condition its text generation. We will play with
  agents and tools with the
  [smolagents](https://huggingface.co/docs/smolagents/en/index)
  library.

(notebook5)=
## Notebook 5: Transformers for NLP

[Run this Notebook on Colab](https://colab.research.google.com/drive/1teoyckS5ZTbGZqHSCxrjyQL9gXgG3KAo?usp=sharing)

In this Notebook we exemplify how to use Transformers for NLP tasks
such as multi-lingual named-entity recognition.

(notebook6)=
## Notebook 6: Efficient LLM Inference

[Run this Notebook on Colab](https://colab.research.google.com/drive/1-te53ydLjnP-YHUuwthO0G8Z44bB1yq6?usp=sharing)

In this notebook we exemplify two efficient inference approaches: int8 quantization and speculative decoding, as discussed in {ref}`lecture6`.

(notebook7)=
## Notebook 7: Reasoning with LLMs

[Run this Notebook on Colab](https://colab.research.google.com/drive/1Mp6Ehq8HxVx_bCRUEMa9c6Fk15oyVUxk?usp=sharing)

Accompanying {ref}`lecture7`, this Notebook walks you through
inference using Qwen-2.5-1.5B and DeepSeek-R1-Distill-Qwen-1.5B. You
are introduced in comparing direct versus chain-of-thought reasoning,
with math problem solving as the test domain.


