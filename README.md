# 7-Day AI Agents Crash-Course
In this crash course we will learn how to build intelligent systems that can understand and interact with your data.


## Day 1: Ingest and Index Your Data
On the first day, we will learn how to download and process data from any GitHub repository.

We will download the data as a zip archive, process all the text data from there, and make it available for ingestion into a search engine later.

Today, we will address simple cases where documents are not large.

Lesson: [1-ingest-index-data.md](https://github.com/scalamiguel/ai-agents-crash-course/blob/main/1-ingest-index-data.md)


## Day 2: Chunking and Intelligent Processing for Data
Previously, we prepared data from a GitHub repo. For small sources, like FAQs, that is sufficient.

But large documents, like Evidently’s docs, can cause problems when passed directly to an LLM:

* Models hit token limits
* Prompts get expensive
* Accuracy drops with long contexts
* Much of the text is irrelevant

The solution is chunking: breaking long documents into smaller, focused pieces that are easier (and cheaper) for AI to process.
Your Today’s Tasks

Today, you’ll explore 3 different chunking methods:

1. Simple sliding window: cut into overlapping chunks
2. Paragraph and section splits: use natural document structure
3. LLM-powered chunking: intelligent, semantic splits (requires OpenAI or Groq account)

Remember to start simple. Use advanced methods only if your documents are complex or the results are poor.

Lesson: 
