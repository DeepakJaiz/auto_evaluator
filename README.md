# auto_evaluator

### Aim
In this lesson we want to create a app which thake some data and from that data we provide some questions and answer. Then we test that answer through LLM and grade them.

Context

Document Question-Answering is a popular LLM use-case. LangChain makes it easy to assemble LLM components (e.g., models and retrievers) into chains that support question-answering: input documents are split into chunks and stored in a retriever, relevant chunks are retrieved given a user question and passed to an LLM for synthesis into an answer.

Challenge

The quality of QA systems can vary considerably; for example, we have seen cases of hallucination and poor answer quality due specific parameter settings. But, it is not always obvious to (1) evaluate the answer quality in a systematic way and (2) use this evaluation to guide improved QA chain settings (e.g., chunk size) or components (e.g., model or retriever choice).

App overview

This app aims to address the above limitations. Recent work from Anthropic has used model-written evaluation sets. OpenAI and others have shown that model-graded evaluation is an effective way to evaluate models. This app combines both of these ideas into a single workspace, auto-generating a QA test set and auto-grading the result of the specified QA chain.

![image](https://github.com/DeepakJaiz/auto_evaluator/assets/120568685/d9a2aaac-e8c1-4836-b6d8-7121ad797ccf)

### Reference
https://github.com/langchain-ai/auto-evaluator/blob/main/README.md

### Prerequist
`You required Phython in your system fyou can follow this (https://www.python.org)`<br/>
`OpenAi API key required to get you can follow this link (https://platform.openai.com/account/api-keys)`<br/>
`Create a account on huggingface https://huggingface.co/login`<br/>

### Modules required
All the requirment are define in requirment.text file.
### How to run
1. Open the huggingface after login.
2. Go to the space button and then create new space.
3. For creating new space enter the name of space as you want, then select "streamlit" from select the space sdk. Then make your space public or private as you want.
4. After that click the create space.
5. Then upload all the above file in your space.
6. Then you can see your application by clicking the app button.

### How to use app
1. In left side enter your open API Key.
2. Upload you source data in pdf and text format.
3. Upload your test question answer in JSON format just below it.
