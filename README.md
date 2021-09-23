# ConversationalAI
This file contains info I have found on the internet regarding conversational artificial intelligence and basics about AI. The objective of this file is to give a brief understanding of conversational AI and try to demystify the confusing tech keywords used in the field of AI.

## Table of Contents
1. [What is conversational AI]()
2. [Dialogue Systems]()
3. [How does it work]()

## What is conversational AI

According to [IBM](https://www.ibm.com/cloud/learn/conversational-ai#toc-what-iscon-7iQb1_He), conversational AI is a **chatbot** geared with *machine learning* and *natural language processing*(nlp) to talk like one of us.

In the old days, chatbots were merely an interactive FAQ that were prone to errors when encountering a user input that was not expected by the developers.

Today, chatbots use *natural language understanding*(nlu) to aid itself in determining the user's intentions. This allows the chatbot to not only catch a variety of user inputs and respond successfully, but also have the ability to predict what the user might query next and actually suggest helpful actions. An example from IBM:

> For example, if a user asks about tomorrow's weather, a traditional chatbot can respond plainly whether it will rain. An AI chatbot, however, might also inquire if the user wants to set an earlier alarm to adjust for the longer morning commute (due to rain).

In summary, conversational AI is a subset of chatbots that are smarter than the previous ones.

## Dialogue systems

Now, as I dive deeper into this aspiring technical field, I am overwhelmed by the terminologies that are sometimes mixed with other words or misused (but I have failed to recognize it). However, one keyword that I was able to consistently find in the sources was dialogue system (a.k.a conversational agent).

A dialogue system is a computer system intended to converse with human. According to the source from [Stanford](https://web.stanford.edu/~jurafsky/slp3/24.pdf), dialogue systems have two sub classes: *task-oriented dialogue agents* and *chatbots*.

The task-oriented dialogue agents are used to help users complete tasks. A lot of the digital assistants like Siri, Alexa, Google, Cortana, etc fall under this category. Compared to chatbots, task-oriented dialogue agents are not designed for extended conversations.

The chatbots on the other hand, are designed for extended conversations to mimic the human-to-human interaction. However, this does not mean that task-oriented dialogue agents and chatbots are opposite. Some chatbots can also serve as a task-oriented dialogue agent but with a much natural (human-like) flow to it.

## How does it work

Let's start with some of the major chatbot architectures. As of now, it appears the names for these architectures are not 100% fixed and the sources seem to describe something similar but with different names to it.
I have narrowed down to the following architectures:
1. Rule-based
2. Corpus-based

///////////////////////////////////////
2. Statistical data-driven systems based on machine learning //
3. Neural dialogue systems based on end-to-end learning //

// information retrieval systems, encoder-decoder generators
///////////////////////////////////////

Rule-based systems analyze input using patterns(rules). These patterns are prepared before the chatbot is used and a very good example is the ELIZA chatbot developed by Weizenbaum in 1966. ELIZA was used to simulate a psychologist and make the users reflect on themselves by reflecting the statements back to them.

For example, consider a chatbot that has the following rule: `0 YOU 0 ME` (where 0 is a wildcard | Kleene*), and will respond with `WHAT MAKES YOU THINK I 3 YOU` (where 3 is the index of the wildcard, so the second wildcard). When the user inputs `I KNOW YOU HATE ME`, the response will be `WHAT MAKES YOU THINK I HATE YOU`.

Just from the example, the power of rule-based systems heavily depend on the developer.


response generators (output generator)


chatbot - https://www.ibm.com/cloud/learn/chatbots-explained
machine learning - https://www.ibm.com/cloud/learn/machine-learning
nlp - https://www.ibm.com/cloud/learn/natural-language-processing
nlu - https://en.wikipedia.org/wiki/Natural-language_understanding 
ai vs machine learning vs deep learning - https://www.ibm.com/cloud/blog/ai-vs-machine-learning-vs-deep-learning-vs-neural-networks
chatbots & dialogue systems (stanford) - https://web.stanford.edu/~jurafsky/slp3/24.pdf
chatbots & dialogue systems (princeton) - https://www.cs.princeton.edu/courses/archive/fall19/cos484/lectures/lec18.pdf
Grammatical Framework - https://en.wikipedia.org/wiki/Grammatical_Framework
Comparison of different machine translation approaches - https://en.wikipedia.org/wiki/Comparison_of_different_machine_translation_approaches
chirpy-cardinal (stanford chatbot) - http://ai.stanford.edu/blog/chirpy-cardinal/



## Papers
- [Conversational AI: Dialogue Systems, Conversational Agents, and Chatbots](https://www.morganclaypool.com/doi/abs/10.2200/S01060ED1V01Y202010HLT048)
