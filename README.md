# **Long-term Agentic Memory with LangGraph**

**[Deeplearning.ai | LangChain](https://www.deeplearning.ai/short-courses/long-term-agentic-memory-with-langgraph/)**

**Andrew Ng - CEO, Deeplearning.ai**

**Harrison Chase - Co-Founder & CEO, LangChain**

***Notes by Vishnu Subramanian - AI/ML Computational Science Associate Manager, Accenture | AI Researcher & Instructor, BloomTech***

***Wednesday, 03/26/2025 - Wednesday, 03/26/2025***

## ***1 - Introduction***

- We’ve recently seen many agentic applications being built.
- This has helped us build a mental framework that’s useful to think about when you’re building agents.
- More and more AI applications are being built to persist over time, and this really drives the need for Agentic Memory.
- An example would be an AI Personal Assistant. The more it learns, the better it’s likely to be at a future task.
- To add memory to an agent, we must first figure out what information to store inside the long-term memory, and when it’s time to use the information, what to retrieve.
- First, on what to store, chatbots initially just stored conversational history at each turn of the conversation as their memory.
- But agents that act for you over time, need a long-term memory. For example, a calendar agent might need to persist information about meetings over long periods and across multiple invocations of the agent. 
- Then comes retrieval. Retrieval will take information from the memory and insert it into the context. We will learn to look into when and what to retrieve.
- Additionally, you also need to decide when to update the stored information. Should it be updated through each iteration of an agent loop, or in the background over time?
- To address these questions, it’s useful to think about three types of memories.
- Semantic Memories: These are facts, like important birthdays for a calendar agent.
- Episodic Memories: These are experiences that can help an agent remember how to do tasks.
- Procedural Memories: These involve rules for an agent to follow.
- To help manage memory, a new spin-off library of LangChain called LangMem has been created.
- LangMem supports a Vector Database that provides searchable, shareable and persistent storage that can be updated immediately by the agent, or in the background by a helper agent.
- In this course, we’ll build a useful email assistant that utilizes all these concepts using LangMem.

***WIP - More Notes Incoming!***
