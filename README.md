# Phenotyping-with-GPT

Feature extraction is perhaps the most essential tool available to assist and improve the current methods of notetaking and information sharing in the clinical field. Large Language Models (LLM) and Natural Language Processing (NLP) provide increasingly useful to perform feature extraction on clinical data. However, the use of these models often requires pre-training on a similar dataset to avail the most optimistic results. We use a few-shot learning technique with the most widely available LLM tool, GPT, evaluating its ability to perform on an unstructured clinical dataset of NICU patients when it is mostly untrained. This process is aided by a self-critiquing function, which optimizes and reduces the randomness of its output. Experimental results both confirm the impact of self-verification on the accuracy of LLM results and show GPT-4's promising potential to assist in future feature extraction tasks from clinical data with widespread applications. We release our code and clinical annotated dataset in order to encourage further research.  

Attached is a 45-note dataset annotated according to the categorization below, along with a program that prompts GPT-4 to extract keywords in each note from the diagnosis category and self-verifies the output in an iterative function.

![image](https://github.com/kcorra26/Phenotyping-with-GPT/assets/114637035/75e40e4f-b937-4d52-9279-43a57ed8cdc9)

