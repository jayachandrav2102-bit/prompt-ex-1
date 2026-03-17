Aim:
Comprehensive Report on the Fundamentals of Generative AI and Large Language Models (LLMs)

Experiment:
Develop a comprehensive report for the following exercises:
1.	Explain the foundational concepts of Generative AI. 
2.	Focusing on Generative AI architectures. (like transformers).
3.	Generative AI applications.
4.	Generative AI impact of scaling in LLMs.


~~~
DEVELOPED BY : V JAYACHANDRA
REG NO:212225230111

“To evaluate and compare the effective of prompting techniques (Zero-shot,few-shot,chain of thoughts,role-based) across different AI platforms (e.g :  Chatgpt  , Gemini, Claude,Copilot) in a specific task:
TEXT SUMMARIZATION “

 BLOCK OF CHAIN:
           * Blockchain is a revolutionary technology that functions as a shared, immutable digital ledger. The name "blockchain" comes from its structure data is organized in blocks, with each new block linked to the one before it, forming a continuous chain.

            *Each block contains crucial data, such as a list of transactions, a timestamp, and a unique identifier called a cryptographic hash. This hash is generated from the block's contents and the hash of the previous block, ensuring that each block is tightly connected to the one before it.

              * Blockchain's linked structure makes data tampering detectable by altering hashes and breaking the chain.It acts as a distributed database, storing transactions across the network.Each transaction is verified by the majority, ensuring legitimacy.This decentralization prevents any single party from manipulating the data.Blockchain is decentralized and distributed, meaning no single authority controls it. Instead, multiple computers (nodes) on a network each have a copy of the blockchain, keeping the ledger synchronized. This setup ensures that once data, like a transaction, is recorded and confirmed, it becomes immutable almost impossible to alter or delete

1.How does Blockchain Technology Work? 
One of the famous use of Blockchain is Bitcoin. Bitcoin is a cryptocurrency and is used to exchange digital assets online. Bitcoin uses cryptographic proof instead of third-party trust for two parties to execute transactions over the Internet. Each transaction protects through a digital signature. 

2.blockchain network :

Blockchain Decentralization
There is no Central Server or System which keeps the data of the Blockchain. The data is distributed over Millions of Computers around the world which are connected to the Blockchain. This system allows the Notarization of Data as it is present on every Node and is publicly verifiable.

Prompting Techniques Compared

1. Zero-Shot Prompting
Definition:
-->The AI is given only the task, with no examples or guidance.

Example Prompt:
“Summarize the following article in 5 lines.”

Performance Comparison:
Platform--	Effectiveness
ChatGPT --	Clear, readable, well-structured summaries
Gemini --	Accurate but sometimes too brief
Claude --	Very fluent, human-like summaries
Copilot -- Basic summarization, less depth

2. Few-Shot Prompting
Definition:
-->The AI is given examples before the task.

Example Prompt:
Example:
Text: "AI is transforming education..."
Summary: "AI improves learning through automation and personalization."

Now summarize:
"Artificial Intelligence is changing healthcare by..."

Performance Comparison:
Platform--	Effectiveness
ChatGPT--	Highly structured, accurate
Gemini--	Good alignment with examples
Claude--	Best contextual understanding
Copilot--	Moderate improvement


3. Chain-of-Thought Prompting
Definition:
-->AI is guided to think step-by-step before summarizing.

Example Prompt:
“Read the text, identify key ideas, group them, then produce a summary.”


Performance Comparison:
Platform--Effectiveness
ChatGPT--	Excellent logical structuring
Gemini--	Good reasoning flow
Claude--	Deep understanding, high clarity
Copilot--	Limited reasoning depth

4. Role-Based Prompting
Definition:
-->The AI is assigned a professional role.

Example Prompt:
“You are a teacher. Summarize this text for school students.”

Performance Comparison:
Platform--	Effectiveness
ChatGPT--	Style adapts well to role
Gemini--	Good tone control
Claude--	Most natural tone adaptation
Copilot--	Basic role understanding


<img width="836" height="590" alt="image" src="https://github.com/user-attachments/assets/d469f6b7-b104-4f9c-8460-497d189a0920" />
~~~


Conclusion:
Different prompting techniques significantly affect summarization quality:

Zero-shot → Speed-focused, low control

Few-shot → Best balance of quality + consistency

Chain-of-thought → Best for deep understanding and accuracy

Role-based → Best for audience-specific communication

Final Insight:
For text summarization tasks, the most effective techniques are:

        Few-shot prompting + Chain-of-thought prompting,
        
while Role-based prompting is ideal for educational and professional context.
