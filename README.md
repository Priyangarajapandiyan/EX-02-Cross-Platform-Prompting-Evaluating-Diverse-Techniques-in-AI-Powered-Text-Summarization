# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization
Four prompting strategies were used:

### A. Zero-Shot Prompting
The AI is directly asked to summarize the article without examples.

**Example:**  
“Summarize the following blockchain article in simple language for undergraduate students.”

---

### B. Few-Shot Prompting
The AI is provided with sample summaries before the actual task.

**Example:**  
Providing 1–2 example technical summaries before asking for the blockchain summary.

---

### C. Chain-of-Thought Prompting
The AI is instructed to analyze the article step-by-step before generating the summary.

**Example:**  
“Identify the important concepts first and then generate a concise summary.”

---

### D. Role-Based Prompting
A role or persona is assigned to the AI.

**Example:**  
“Act as a university professor and summarize blockchain technology for students.”

---

## Step 4: Generate Responses
The same blockchain article was given to every AI platform.

Each prompting strategy was tested individually:
- Zero-Shot
- Few-Shot
- Chain-of-Thought
- Role-Based

The generated summaries were collected and analyzed.

---

## Step 5: Organize Results
The responses were compared based on:
- Accuracy
- Coherence
- Simplicity
- Speed
- User Experience

---

# Result

## ChatGPT + Zero-Shot Prompting

### Prompt Used
> “Summarize the following article on Blockchain Technology in simple language for undergraduate students.”

### Summary Generated
Blockchain is a decentralized digital system used to securely store information across multiple computers. Data is stored in blocks linked together using cryptographic techniques. Blockchain removes the need for a central authority and improves transparency and security. It is commonly used in cryptocurrencies like Bitcoin and also in banking, healthcare, and supply chains. Major challenges include energy consumption and scalability.

### Evaluation
- Accuracy: High
- Coherence: Good
- Simplicity: Excellent
- Speed: Very Fast
- User Experience: Excellent

---

## Gemini + Few-Shot Prompting

### Prompt Used
> “Here are two sample technical summaries. Now summarize the blockchain article similarly.”

### Summary Generated
Blockchain is a secure distributed database where records are stored in connected blocks. Every participant has access to the same data, making the system transparent and difficult to alter. Blockchain supports cryptocurrency systems and improves applications in finance, healthcare, and logistics. However, challenges such as high power usage and slower transaction speed still exist.
