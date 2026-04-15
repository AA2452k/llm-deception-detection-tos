# Investigating how LLMs are trained and its impact on cybersecurity
python tool assessing the Ability of Open-Source LLMs to Identify Deceptive  Clauses in Terms of Service Using Chain-of-Thought Prompting:  A Comprehensive Study


    ## Abstract
 Terms of Service (TOS) agreements shape our interactions with digital services, defining
 how our data is collected, shared, and retained. They specify our rights and responsibil
ities, often concealing clauses that could undermine user privacy or impose burdensome
 conditions. Many users rarely read these agreements in full, and the rise of “dark pat
terns” means that troubling clauses are frequently obscured by complicated language. On
 the other hand, large language models (LLMs) have emerged as powerful tools for analyz
ing text. This dissertation explores whether open-source LLMs,specifically Mistral-7B
Instruct, Meta-Llama-3-8B-Instruct, and Microsoft Phi-2, can effectively identify decep
tive or privacy-violating clauses within TOS documents. Through a binary classification
 framework (deceptive versus legitimate), I evaluate whether Chain-of-Thought (CoT)
 prompting enhances performance compared to straightforward classification prompts.
 The study begins with a review of relevant literature on TOS deception, dark patterns, le
gal technology, and prompting strategies for LLMs. A reproducible experimental method
ology is detailed, featuring a balanced dataset of ten legitimate and ten deceptive clauses.
 The implementation is described through a comprehensive analysis of the accompany
ing notebook code, covering dataset construction, prompt generation, response parsing,
 evaluation metrics, visualization, and qualitative error analysis.The study’s results show
 varied performance across the models, with Chain-of-Thought (CoT) prompting signifi
cantly improving the performance of Mistral-7B-Instruct. Eventually, this study argues
 that CoT prompting has the potential to enhance the transparency and performance of
 deception detection, though its effectiveness varies by model
