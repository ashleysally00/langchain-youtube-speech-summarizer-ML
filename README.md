# LangChain YouTube Speech Summarizer (ML) 
This project uses **LangChain**, **Python**, and **YouTube transcripts** to summarize inspirational commencement speeches using machine learning.

# What is LangChain?

[LangChain](https://www.langchain.com/) is an open-source framework for developing applications powered by large language models (LLMs). It provides tools to help manage prompts, chains of logic, external tools like vector databases, and memory. It’s especially useful for building language-aware applications such as chatbots, summarizers, and retrieval-based Q&A systems.

---

## Why use LangChain?

### It Connects LLMs to Tools

LangChain lets you go beyond just sending a prompt to an LLM. You can:

- Connect to **APIs**
- Use **databases and vector stores** (like FAISS, Pinecone, or Milvus)
- Read files (**PDFs, CSVs, websites**)
- Trigger **code execution**, **search engines**, and more

---

## Do you need LangChain for this project?

No, you don’t strictly need LangChain — you could build this project using just Python and the OpenAI API. But LangChain makes the process **easier**, **faster**, and **more scalable**.

### Without LangChain

You would have to manually:
- Split the transcript into chunks
- Write custom logic for summarization or Q&A
- Handle embeddings and vector search from scratch
- Connect everything together with boilerplate code

### With LangChain

You get:
- Built-in **text splitters** (like `RecursiveCharacterTextSplitter`)
- Easy **chain management** (e.g., summarize → combine)
- Pre-built interfaces for **LLMs**, **retrievers**, and **prompt templates**
- Optional **memory** and **agent support** for more advanced apps
- Seamless integration with **vector stores** (FAISS, Chroma, Milvus, etc.)

### Why it matters

LangChain helps turn a simple script into a **reusable, modular, and production-ready LLM application**.

If you want to:
- Add Q&A  
- Let users upload their own speech  
- Swap models  
- Or expand your app later...

LangChain makes all of that much easier.

---

## Project Goal

This project will demonstrate how LangChain can process transcripts—like YouTube speeches—and turn them into clear, concise summaries that highlight their original message and emotional tone.

---

## Speech 1: Sundar Pichai – "Dear Class of 2020"

**Summary:**

Sundar Pichai encourages the graduating class to remain optimistic despite uncertainty. Drawing from his own humble beginnings, he highlights the power of technology as a lifeline and a tool for connection, education, and opportunity. He urges graduates to stay open, impatient, and hopeful as they shape the future, emphasizing their ability to create positive change.

---

**Transcript:**

> Congratulations to the Class of 2020. As you begin this new chapter in your life, you might be feeling uncertain or anxious about what’s ahead. But it’s important to remember that this is not the first time the world has faced great challenges. And it won’t be the last.  
>   
> The world will overcome this pandemic and we’ll rebuild — and we’ll do it together.  
>   
> I grew up without much access to technology. We didn’t get our first telephone until I was ten. I didn’t have regular access to a computer until I came to America for graduate school. And our television, when we finally got one, only had one channel. So my experience was very different from what many of you have grown up with.  
>   
> But I’ve always been fascinated by technology and the opportunities it creates. The past few months have made it clear that technology can be a lifeline — whether it’s helping us stay in touch with loved ones, continue our education, or run a business.  
>   
> And that’s why I believe it’s more important than ever to ensure that technology serves everyone — that it is helpful and improves people’s lives. That’s what Google tries to do. And that’s what drew me to technology in the first place.  
>   
> To the graduates: Be open, be impatient, be hopeful. You have the chance to change everything. I am optimistic that you will.

---

More speeches and features coming soon!
