\# Korashi Books Helper 📚



A simple AI-powered FAQ chatbot for a fictional independent bookshop in Cairo, built with Dify Cloud.



\## Live Chatbot



\*\*Public Dify Web App:\*\*


https://udify.app/chat/1OMg7ny5fItNAOLr






\## Project Overview



Korashi Books Helper is a no-code AI chatbot designed to answer common customer questions about a fictional Cairo bookshop.



The chatbot uses a Dify Knowledge Base containing a custom FAQ document. This helps keep answers grounded in the shop's information and prevents the assistant from inventing policies or details.



\## LLM Provider



\* \*\*Platform:\*\* Dify Cloud Sandbox

\* \*\*LLM Provider:\*\* Google AI Studio / Gemini

\* \*\*Model:\*\* Gemini model configured in Dify

\* \*\*Cost:\*\* $0



\## Knowledge Base



The chatbot uses `faq.md` as its Knowledge Base.



The FAQ covers:



\* Opening hours

\* Location

\* Shipping policy

\* Return policy

\* Payment methods

\* Book languages

\* Special orders

\* Contact channels



\## System Prompt



The full system prompt used for the chatbot is available in:



`system\_prompt.md`



The assistant is instructed to:



\* Answer using the FAQ Knowledge Base.

\* Stay within the bookshop-related scope.

\* Avoid making up information.

\* Politely say when information is not available.



\## Project Structure



```text

dify-bookshop-chatbot/

├── README.md

├── faq.md

├── system\_prompt.md
└── screenshots/
    ├── 01_app_setup.png
    ├── 02_knowledge_attached.png
    ├── 03_conversation_1.png
    ├── 04_conversation_2.png
    └── 05_conversation_3.png

```



\## Screenshots


The `screenshots/` folder contains evidence of:

1. Dify chatbot setup.
2. Knowledge Base integration.
3. Three FAQ conversations using the public chatbot.
\## How to Recreate



1\. Create a free account on Dify Cloud.

2\. Create a new \*\*Chatbot\*\* app.

3\. Configure a free-tier LLM provider.

4\. Upload `faq.md` as a Knowledge Base.

5\. Attach the Knowledge Base to the chatbot Context.

6\. Add the system prompt from `system\_prompt.md`.

7\. Test the FAQ questions in the Dify preview.

8\. Publish the chatbot.

9\. Open the public URL in another browser or Incognito mode.

10\. Test the chatbot using the FAQ questions.



\## Grounding and Fallback



The chatbot is designed to answer questions only when the required information is available in the FAQ Knowledge Base.



If information is not available, the assistant should politely explain that it does not have that information instead of guessing.



\## Privacy



This project uses fictional shop information only. No real customer data or private personal information is included.



\## Project Goal



The goal is to demonstrate how a simple, useful FAQ chatbot can be built with Dify using RAG/Knowledge Base functionality without writing code.



