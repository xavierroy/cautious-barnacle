---
title: "about chatbots"
date: 2020-06-22T11:02:51+05:30
type: post
audiences: ["writers"]
categories: ["TechComm"]
tags : ["chatbots", "ai"]
twitlink: https://twitter.com/PaperArrow/status/1274943212881244162
---


> I wrote this post after a discussion on chatbots in one of the technical writing groups.  There was a poll asking people what they preferred: talking to a chatbot or a human. About 70 % stated that they preferred talking to an agent instead of a chatbot. I realised this was mostly due to a misconception on what chatbots can do. I thought it would make sense to consolidate my notes on what chatbots are and post them.

A **chatbot** is a software that simulates a conversation with a user. This conversation can happen  _textually_ via messaging applications or websites or _orally_ via voicebots (chatbots that supports voice) or smart assistants.

Currently, there are two approaches to chatbots. One is the rules-based approach or the AI-based approach.

In a _rules-based bot_, the conversation follows a predetermined path (known as a _decision tree_). The decision tree can be thought of akin to a flowchart, and they can be simple or complex decision trees. These bots work best when confined to a specific domain and are easy to build as the rules of interaction are well-defined. The rule-based bots are analogous to an IVR in a customer care center. One drawback is these bots cannot switch contexts within a conversation as they have very structured dialogs and answer specific questions by matching the user input to pre-programmed answers.

An _AI-based bot_ depends on various artificial intelligence techniques like Natural Language Processing (NLP) and Machine Learning (ML) to understand the user input and communicate accordingly. The bots can also learn over time and improve their responses. These bots can follow two different models: _retrieval-based_ model or _generative_ model.

* A **retrieval-based** bot model uses a repository of predefined responses and a heuristic to pick an appropriate response based on the input and context. The heuristic could be as simple as a rule-based expression match, or as complex as an ensemble of Machine Learning classifiers. These systems don’t generate any new text, they just pick a response from a fixed set. For example, a bot for a store that can respond to questions about opening hours or returns policy.
* A **generative** bot model does not rely on pre-defined responses. They generate new responses from scratch. Generative models are typically based on Machine Translation techniques, but instead of translating from one language to another, we “translate” from an input to an output (response). Smart assistants like Google Assistant, Alexa and Siri fall under this category.



Let's consider a use-case for a bank for these different chatbot types. The bank wants to offer its customers the ability to view their bank balance, trigger a payment, or look up transaction fees.

A first-gen bot would show you options to look up your balance or pay your credit card bills. It may even display a list of say transaction fees. Most of the time, these bots require you to use a pre-configured word/phrase like “View Account Balance” or a number to perform the action.

An AI-based bot would accept either text or voice to perform the same operation as above but with an expected keyword in your conversation. It looks for some keywords to trigger an action. A well-trained bot could understand the difference when you say _I want to view my account balance_ and _I want to view my loan balance_. It could either trigger a follow-up query if you state, _I want to view my balance_. And a third-gen bot could also support other banking tasks like applying for loans or transfer money.

Chatbots, for technical writers provides an interesting challenge. Because firstly, there is no UI that requires extensive documentation. Secondly, the lack of a UI requires a different type of documentation, one where words take precedence and where the language of the bot takes precedence. Its tone and voice may determine its success. 


