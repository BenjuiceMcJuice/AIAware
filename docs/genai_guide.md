# GenAI — A Practical Guide for Everyone

> *Internal source document. This is the original content that AI Sense is based on.*

---

## Who is this for?

This guide is for anyone curious about or already using Generative AI tools — whether you are 12 or 62, using it at home, at school, or at work. No technical background is needed.

---

## 1. What is Generative AI and How Does it Work?

Generative AI (GenAI) is a type of artificial intelligence that **generates** content — such as text, images, code, or documents — in response to something you give it. That "something" is called a **prompt**, and it can be words, questions, files, images, or a combination.

Well-known examples include ChatGPT, Claude, Gemini, and Copilot, among many others.

It is worth thinking of GenAI as a tool — much like a calculator. A calculator does not do your maths homework for you in any dishonest sense; it helps you work faster and more accurately. GenAI is the same principle, just applied to a much wider range of tasks.

---

## 2. Where Does it Get its Information?

GenAI tools are trained on vast amounts of text data — essentially a huge portion of the written internet. This includes academic research papers, books, forums, news articles, code repositories, and yes, the occasional angry rant someone posted online at 2am.

This means GenAI can be excellent on well-documented topics — coding languages, widely covered subjects, established processes — but may be less reliable on niche, recent, or contested topics.

**Importantly, GenAI does not work like a search engine.** It does not "look things up" when you ask a question. Instead, during training it learned statistical patterns — which words, ideas, and structures tend to follow others. When you send a message, it predicts the most coherent and relevant response based on those patterns.

Think of it less like a library and more like a very well-read colleague who has absorbed an enormous amount of information and can synthesise it on demand — but who can also occasionally misremember things, fill in gaps with plausible-sounding but incorrect information, or state something confidently that is simply wrong.

This last point is important enough to have its own section later.

---

## 3. How to Interact With it

GenAI tools typically work through a simple text-based conversation interface. You send a message, it responds. Many tools also allow you to attach files, images, or documents which the AI can read and analyse.

Responses can come back as plain text, formatted documents, code, or in some tools, generated images.

Most GenAI tools maintain memory **within** a conversation — meaning it remembers what you said earlier in the same chat. Some tools also carry memory **across** conversations, though this varies.

A few things worth knowing from the start:

- The quality of what you get back is directly related to the quality of what you put in. Vague questions tend to get vague answers.
- You can give GenAI a role or frame to work within. For example, starting with "Act as an experienced project manager..." can meaningfully shape the tone and focus of its responses.
- You can always ask it to explain, simplify, or redo something if the first response is not what you needed.

---

## 4. Ask vs. Do — Being Clear About What You Want

One of the most common sources of frustration with GenAI is not being explicit about the **type** of response you want. There is a significant difference between asking for an opinion and asking for an action.

Consider the difference between:

- "What do you think of this document?" — you want feedback, critique, suggestions
- "Rewrite this document" — you want it to produce something

If you are not clear, GenAI will make an assumption — and it may well guess wrong. It might start editing when you only wanted a review, or it might only comment when you wanted it to roll its sleeves up and produce something.

Get into the habit of being explicit:

- "Review this and tell me what you think, do not change anything yet"
- "Now go ahead and rewrite section 2 based on your feedback"
- "Give me your opinion first, then ask me if I want you to action it"

This applies to format. If you want bullet points, say so. If you want a formal tone, say so. If you want it short, say so. GenAI responds well to clear direction.

---

## 5. Understanding Tokens — Why There Are Limits

GenAI tools run on a system of **tokens**. Every piece of text you send, every file you attach, and every word of the response generated uses tokens. The more complex or lengthy the task, the more tokens are consumed.

Most GenAI tools offer a free tier which comes with token limits — for example, a cap on how many images you can analyse per day, or how many long documents you can process in an hour.

Paid versions typically increase these limits significantly.

This is also why keeping conversations focused and starting new conversations for new topics is good practice — every message you send in a conversation often causes the tool to re-process the entire conversation history, which uses more tokens than you might expect.

---

## 6. Limitations and Hallucinations — The Most Important Section

This is arguably the most critical thing to understand about GenAI.

GenAI **can and does make things up**. This is known as "hallucination." It will sometimes state incorrect facts, fabricate references, invent statistics, or produce plausible-sounding but entirely wrong information — and it will do so with complete confidence and no indication that anything is amiss.

This is not a bug that will simply be fixed one day. It is a characteristic of how these models work.

What this means practically:

- Never use GenAI output for anything important without checking it
- Be especially cautious with specific facts, figures, dates, names, and citations
- If something sounds surprising or too convenient, verify it independently
- The more niche or specific the topic, the higher the risk of inaccuracy

GenAI is a powerful tool for drafting, structuring, summarising, and generating ideas. It is not a reliable source of ground truth on its own.

---

## 7. Privacy and Data — What You Should and Should Not Share

For personal use, the main consideration is being aware that anything you type into a GenAI tool may be stored, reviewed, or used by the provider depending on their terms of service. Read the small print.

For professional or corporate use, this becomes more important. Many organisations have specific policies on what can and cannot be shared with external AI tools. As a general rule:

- Do not paste in confidential client data, personal data, or sensitive commercial information unless you are using a tool that your organisation has specifically approved and secured for that purpose
- Be aware that some corporate GenAI deployments (like this one) are specifically designed to keep data within a secure environment — know which you are using
- When in doubt, anonymise or generalise the information before sharing it

---

## 8. Is it Cheating?

This is a question worth addressing directly because many people feel uncertain about it.

**Using GenAI is not cheating by default.** It is a tool. Using a calculator is not cheating. Using a spell-checker is not cheating. Using GenAI to help you work faster, clearer, or better is not cheating — in most contexts.

### It is cheating when:

- You are being assessed on your own knowledge and are expected to demonstrate it personally — in an exam, a test, or a job interview
- You submit AI-generated work as your own in an academic setting where original thinking is being evaluated
- You enter AI-generated content into a competition that explicitly prohibits it
- You use it to deceive someone about your own capabilities or knowledge

### It is not cheating when:

- You have the idea in your head but struggle to express it clearly, and use GenAI to help you find the right words
- You could do the task yourself but it would take significantly longer and the output is yours to own and stand behind
- You use it to research options, draft a starting point, or structure your thinking
- You use it like a very capable assistant — one whose work you review, edit, and take responsibility for

The key principle is this: **you own and are responsible for anything you send out, regardless of whether GenAI produced it.** If you would not be comfortable defending it or explaining it if questioned, do not send it.

---

## 9. Getting the Most Out of GenAI

**Start with clarity.** Before you open a conversation, spend a moment thinking about what you actually want out of it. A clear goal produces a better result.

**Chunk your work.** Do not ask GenAI to take two complex documents, compare them, and produce a new one all in one go. The output will almost certainly be poor. Break the task into steps and work through them one at a time.

**Use new conversations for new topics.** Mixing topics in a single conversation can produce unexpected results as the AI tries to link things that are not related. A fresh conversation gives a clean context.

**Treat it like a capable but occasionally unreliable colleague.** It will sometimes misinterpret your instructions, make assumptions, or go off track. That is normal. Correct it, redirect it, and carry on.

**Know that some GenAI tools are better at certain tasks than others.** It is worth experimenting to find what works best for your specific needs.

**You can ask GenAI how to use GenAI.** If you are not sure how to approach a task, ask it to suggest an approach. You can then work through that approach step by step.

---

## 10. Example Use Cases — From Simple to Complex

To give a sense of the range of what is possible:

- Answering a factual question or explaining a concept in plain language
- Rewriting a piece of text in a different tone or format
- Drafting an email or document from rough notes
- Structuring a project plan or approach
- Comparing two documents and summarising the differences
- Analysing a data table and explaining what it might mean
- Writing or debugging code for Excel, applications, or other tools
- Combining several of the above as part of a larger project

---

## 11. Working Through a Bigger Project — A Practical Example

For more complex tasks, a step-by-step approach works best. Here is an example of how that might look in practice:

1. Describe the overall goal to GenAI and ask it to suggest a structured approach. Save that as your working plan.
2. Feed the plan back in and say "Let's start with step 1."
3. Work through step 1, review the output, make any edits, and save the result.
4. In the next message, include the updated plan and the output from step 1, then say "Let's move to step 2."
5. Continue this way, keeping the AI informed of where you are and what has already been done.
6. Keep going until you are satisfied with the outcome.

This approach keeps the work manageable, the context clear, and the quality of output significantly higher than trying to do everything at once.

---

*This document is intended as a living guide. As GenAI tools evolve, some specifics will change — but the core principles of clarity, scepticism, ownership, and common sense will remain relevant.*
