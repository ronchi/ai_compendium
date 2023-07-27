# A Compendium of Artificial Intelligence (specifically for lawyers)
This compendium was produced for the 2023 Texas Advanced Business Law Conference.  This document is seen as far more useful than a traditional paper.  Moreover, this compendium may be updated in the future, in stark contrast to traditional papers.

## Table of Contents

1.  [What is Artificial Intelligence?](https://github.com/ronchi/ai_compendium/blob/main/README.md#what-is-artificial-intelligence)
2.  [Types of AI](https://github.com/ronchi/ai_compendium/blob/main/README.md#types-of-ai)
    1.  [Natural Language Processing]()
    2.  [Generative AI (like ChatGPT)]()
3.  [AI for the Practice of Law](https://github.com/ronchi/ai_compendium/blob/main/README.md#ai-for-the-practice-of-law)
4.  A Few Things That Litigators Should Know About AI
5.  A Few Things That Transactional Attorneys Should Know About AI

## What is Artificial Intelligence?
There is no one single (adequate) definition of artificial intelligence.  Fortunately, there is a "classic" formulation of AI in the categorizaion of thinking and acting, as illustrated in the following set of quotes, courtesy of AI pioneers Stuart Russell and Peter Norvig in their book "[Artificial Intelligence: A Modern Approach](https://people.eecs.berkeley.edu/~russell/aima/)" (4th ed., 2023):

### Thinking Humanly: The Cognitive Modeling Approach

`"The exciting new effort to make computers think ... machines with minds, in the full and literal sense." (Gaugeland, 1985)`

`"{The automation of} Activities that we associate with human thinking, activities such as decision-making, problem solving, learning..." (Bellman, 1978)`

### Thinking Rationally: The "Laws of Thought" Approach

`"The study of mental faculties through the use of computational models." (Charniak and McDermott, 1985)`

`"The study of the computations that make it possible to perceive, reason, and act." (Winston, 1992)`

### Acting Humanly: The Turing Test Approach

`"The art of creating machines that perform functions that require intelligence when performed by people." (Kurzweil, 1990)`

`"The study of how to make computers do things at which, at the moment, people are better." (Rich and Knight, 1991)`

### Acting Rationally: The Rational Agent Approach

`"Computational Intelligence is the stuy of the design of intelligent agents." (Poole et al., 1998)`

`AI ...is concerned with intelligent behavior in artificats." (Nilsson, 1998)`

You can find other definitions [here](https://www.britannica.com/technology/artificial-intelligence), [here](https://www.hpe.com/us/en/what-is/artificial-intelligence.html), and [here](https://www.ibm.com/topics/artificial-intelligence).

A few things to note.  All of those quotes were from the Twentieth Century.  AI was first conceived by [Aristotle](https://en.wikipedia.org/wiki/Aristotle).  Work on neural networks started in the 1950's.  What you see now is the culmination of decades of work by thousands of people.

## Types of AI

Some types (or combinations of types) of AI are famous.  Many types of AI labor in the background -- unseen and unnoticed -- yet some of which have significant legal implications.

The most important thing to remember is that there are many types of AI.  One set of types has to do with the four categories above (thinking/acting humanly/rationally).  A more practical set of categories can be distilled from the products that we encounter in our daily lives, as outlined in the chart below:

![Types of AI](https://github.com/ronchi/ai_compendium/blob/main/ai_types.png)

We will address each type of AI, as well as link to various other sources, below.

### Natural Language Processing (NLP)

NLP is the aspect of AI that lawyers deal with most often -- both directly and indirectly.

#### Definition of Natural Language Processing

#### Context Extraction

##### Use Cases

##### Examples

##### In General:

##### Legal Aspects:

##### Roll Your Own

#### Classification

##### Use Cases

##### Examples

##### In General:

##### Legal Aspects:

##### Roll Your Own

#### Machine Translation

##### Use Cases

##### Examples

##### In General:

##### Legal Aspects:

##### Roll Your Own

#### Answering Questions

##### Use Cases

##### Examples

##### In General:

##### Legal Aspects:

##### Roll Your Own

#### Text Generation

##### Use Cases

##### Examples

##### In General:

##### Legal Aspects:

##### Roll Your Own

#### Generative AI (ChatGPT-like combination of Answering Questions and Text Generation)

What is Generative AI?

Generative AI is a subset of Natural Language Processing.  Specifically, Generative AI employs the *Answering Questions* and *Text Generation* aspects of NLP.  The *Answering Questions* aspect is the interface that is used to ask the question.  In recent parlance, the *Answering Questions* aspect is called a *Prompt*.  The answer that comes back is from the *Text Generation* machine.  A classic example of the Promt/Generation duo is [ChatGPT](https://openai.com/blog/chatgpt).

Essentially, Generative AI makes use of a model (such as a "Large Language Model" like GPT4) that enables the AI to generate new content with little human interaction.  You should think of it as an automated paraphraser, albeit with some serious caveats.  AI professionals refer to Generative AI as "a stochastic parrot" or "a reality-starved paraphraser".  The AI doesn't know what it is saying (or whether what it says is real or not), but it says it very nicely.  Sometimes, the Generative AI can depart significantly from reality, and this is known as "going [hysterical](https://www.windowscentral.com/software-apps/users-show-microsoft-bings-chatgpt-ai-going-off-the-deep-end)."  However, even with those limitations, Generative AI has met with great commercial success.  Since most Generative AI is not tied to reality, marketing people love it.  

Beware, however, for lawyers have been sanctioned for using Generative AI unwisely.  See, *e.g.*, [Mata v. Avianca, Inc.](https://storage.courtlistener.com/recap/gov.uscourts.nysd.575368/gov.uscourts.nysd.575368.54.0_3.pdf) ("Peter LoDuca, Steven A. Schwartz and the law firm of Levidow, Levidow & Oberman P.C. (the "Levidow Firm") (collectively, "Respondents") abandoned their responsibilities when they submitted non-existent judicial opinions with fake quotes and citations created by the artificial intelligence tool ChatGPT, then continued to stand by the fake opinions after judicial orders called their existence into question.")

Unwise reliance on Generative AI is enough of a problem that some courts now have standing orders related to AI-generated material.  *See, e.g.*, an [order](http://chrome-extension/efaidnbmnnnibpcajpcglclefindmkaj/https:/www.ilnd.uscourts.gov/_assets/_documents/_forms/_judges/Fuentes/Standing%20Order%20For%20Civil%20Cases%20Before%20Judge%20Fuentes%20rev'd%205-31-23.pdf) by Magistrate Judge Gabriel A. Fuentes (N.D. Ill.) that was adopted on May 31, 2023.

Having said all of this, you should know that you can "fine tune" your own AI on something real.  In other words, you can direct the AI to look at a corpus of documents (e.g., opinions from the Texas Supreme Court, or [ESI](https://en.wikipedia.org/wiki/Electronically_stored_information_(Federal_Rules_of_Civil_Procedure)) from a witness) and let it answer questions -- and identify the document(s) from which it drew to answer your question.  Such fine tuning can reduce the amount of hysteria produced by the model and, in some cases, cause the model to tell you from whence it derived the answer -- which makes it easier to verify the results.

Here is a set of articles that discuss Generative AI in depth.

##### In General:

- [Gartner Experts Answer the Top Generative AI Questions for Your Enterprise](https://www.gartner.com/en/topics/generative-ai) (This article discusses what Generative AI is, the history, the hype, the reality, and the use cases.)
- [Generative AI: Perspectives from Stanford HAI](https://hai.stanford.edu/sites/default/files/2023-03/Generative_AI_HAI_Perspectives.pdf) (This March, 2023 paper is from the Stanford University Human-Centered Artificial Intelligence initiative discusses the potential of Generative AI.)

##### Legal Aspects:

- [The Generative AI Revolution: Key Legal Considerations for the Consumer Products Industry](https://www.natlawreview.com/article/generative-ai-revolution-key-legal-considerations-consumer-products-industry) (This article discusses the important legal aspects of generative AI systems such as [OpenAI's ChatGPT](https://openai.com/blog/chatgpt), [Microsoft's Copilot](https://adoption.microsoft.com/en-us/copilot/), and similar commercial offerings.)
- [ChatGPT Goes to Law School](https://ssrn.com/abstract=4335905) (The authors of this paper used ChatGPT to generate answers to four real exams at the University of Minnesota Law School.  The resulting answers were graded (blindly) and ChatGPT received an average grade of C+ -- low, but passing.  Further advise was provided on how to use ChatGPT in legal writing.)
- [Generative AI in the Legal Profession](https://clp.law.harvard.edu/knowledge-hub/magazine/issues/generative-ai-in-the-legal-profession/) ("When Open AI released ChatGPT in late 2022, it galvanized the collective imagination—and collective anxiety. Even lawyers wondered how such new AI technologies would change their profession.")
- [The Implications of ChatGPT for Legal Services and Society](https://clp.law.harvard.edu/article/the-implications-of-chatgpt-for-legal-services-and-society/) ("To demonstrate ChatGPT's remarkable sophistication and potential implications, for both legal services and society more generally, most of this paper was generated in about an hour through prompts within the chatbot. The disruptions from AI’s rapid development are no longer in the distant future. They have arrived, and this essay offers a small taste of what lies ahead.")

##### Rolling Your Own:

- [A Complete Guide to Fine Tuning Large Language Models](https://www.simform.com/blog/completeguide-finetuning-llm/) ("Fine-tuning in large language models (LLMs) involves re-training pre-trained models on specific datasets, allowing the model to adapt to the specific context of your business needs. This process can help you create highly accurate language models, tailored to your specific business use cases.")
- [LLM Finetuning](https://huggingface.co/docs/autotrain/llm_finetuning) (discusses how to fine tune your large language model (LLM) with your own data.)
- [Build LLM-powered chatbot in 5 minutes using HugChat and Streamlit](https://dev.to/codemaker2015/build-llm-powered-chatbot-in-5-minutes-using-hugchat-and-streamlit-2f53) ("We will dive into a step-by-step process of developing an LLM-powered chatbot using HugChat, a powerful Python library that simplifies the integration of LLMs into chatbot applications. Furthermore, we will leverage Streamlit, a user-friendly framework for creating interactive web applications, to provide a seamless user interface and deployment platform for our chatbot.")
- [How to use HuggingChat (free ChatGPT) in Python](https://medium.com/cassandra-cryptoassets/how-to-use-huggingchat-free-chatgpt-in-python-ac51ed9dd1f) (A step by step guide to using the HuggingChat Python API.)

## AI for the Practice of Law

- [Generative AI in the Legal Profession](https://clp.law.harvard.edu/knowledge-hub/magazine/issues/generative-ai-in-the-legal-profession/) ("When Open AI released ChatGPT in late 2022, it galvanized the collective imagination—and collective anxiety. Even lawyers wondered how such new AI technologies would change their profession.")
- [The Implications of ChatGPT for Legal Services and Society](https://clp.law.harvard.edu/article/the-implications-of-chatgpt-for-legal-services-and-society/) ("To demonstrate ChatGPT's remarkable sophistication and potential implications, for both legal services and society more generally, most of this paper was generated in about an hour through prompts within the chatbot. The disruptions from AI’s rapid development are no longer in the distant future. They have arrived, and this essay offers a small taste of what lies ahead.")
- [Generative Legal Minds](https://clp.law.harvard.edu/knowledge-hub/magazine/issues/generative-ai-in-the-legal-profession/generative-legal-minds/) ("How ChatGPT and other technologies might change legal research and writing")

### Machine Learning

#### Deep Learning

#### Supervised Learning

#### Unsupervised Learning

### Vision

#### Image Recognition

#### Machine Vision

### Speech

#### Speech-to-Text

#### Text-to-Speech

### Expert Systems

### Genetic Algorithms

### Robotics

### Planning

## A Few Things That Litigators Should Know About AI
## A Few Things that Transactional Attorneys Should Know About AI
