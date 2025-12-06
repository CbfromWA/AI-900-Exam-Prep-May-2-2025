Here is a structured **10-Day / 40-Hour Study Plan** tailored for the May 2025 version of the AI-900 exam.

This schedule prioritizes the high-weight **Generative AI** section and ensures you get hands-on familiarity with the new **Azure AI Foundry** terminology.

### **Schedule Overview**

* **Daily Commitment:** 4 Hours  
* **Total Duration:** 10 Days  
* **Strategy:** Theory (Morning) $\\to$ Hands-on/Video (Mid) $\\to$ Practice Quiz (End)

### ---

**Phase 1: Foundations & Machine Learning (Days 1-3)**

#### **Day 1: AI Concepts & Responsible AI (15-20%)**

* **Hour 1 (Read):** Introduction to AI Workloads (ML, Vision, NLP, GenAI, Document Intelligence).  
* **Hour 2 (Deep Dive):** **Responsible AI.** Memorize the 6 principles (Fairness, Reliability, Privacy, Inclusiveness, Transparency, Accountability). Create a flashcard for each.  
* **Hour 3 (Video/Lab):** Watch "Microsoft AI Fundamentals" intro videos on YouTube or Microsoft Learn. Explore the Azure Portal interface (create a free account if you haven't).  
* **Hour 4 (Quiz):** Take a 20-question practice set specifically on Responsible AI scenarios (e.g., "A model denies a loan to a specific demographic—which principle is violated?").  
* **Link:** [Introduction to AI concepts](https://learn.microsoft.com/en-us/training/modules/get-started-ai-fundamentals/)

#### **Day 2: Machine Learning Principles (15-20%)**

* **Hour 1 (Read):** Differentiate the 3 core types: **Regression** (Numbers), **Classification** (Labels/Categories), and **Clustering** (Grouping).  
* **Hour 2 (Deep Dive):** Understand the "black box" of training. Inputs \= Features, Output \= Labels. Understand Train vs. Validation datasets.  
* **Hour 3 (Lab):** Go to Azure Machine Learning Studio. Click through the "Automated ML" wizard just to see the interface. You don't need to run a paid job, just see the options.  
* **Hour 4 (Quiz):** Practice identifying the problem type. (e.g., "Predicting stock prices" $\\to$ Regression).  
* **Link:** [Introduction to machine learning concepts](https://learn.microsoft.com/en-us/training/modules/fundamentals-machine-learning/)

#### **Day 3: Azure ML Tools (AutoML & Designer)**

* **Hour 1 (Read):** Study **Automated ML (AutoML)**. Key concept: It automates algorithm selection and hyperparameter tuning. Best for "No Code" users.  
* **Hour 2 (Read):** Study **Azure Machine Learning Designer**. Key concept: "Drag-and-drop" visual interface for building pipelines.  
* **Hour 3 (Lab):** Use the "Designer" in Azure to drag a "Linear Regression" module onto the canvas. Visualizing this helps memory.  
* **Hour 4 (Review):** Review the difference between "Compute Targets" (where the training happens) and "Endpoints" (where the model lives for consumption).

### ---

**Phase 2: Vision & Language (Days 4-6)**

#### **Day 4: Computer Vision (15-20%)**

* **Hour 1 (Read):** **Azure AI Vision** capabilities: Image Classification vs. Object Detection.  
* **Hour 2 (Deep Dive):** **OCR (Optical Character Recognition)**. Understand the "Read API" for documents. Differentiate between "Vision" (general objects) and "Face" (emotion/identity).  
* **Hour 3 (Lab):** Visit the [Azure AI Vision Studio](https://portal.vision.cognitive.azure.com/). Use the demo to upload a photo of your desk and see what it detects.  
* **Hour 4 (Quiz):** Practice questions focusing on which service to pick (e.g., "Scan a receipt" $\\to$ Document Intelligence/OCR).  
* **Link:** [Get started with computer vision](https://learn.microsoft.com/en-us/training/modules/get-started-computer-vision-azure/)

#### **Day 5: NLP \- Text Analysis (15-20%)**

* **Hour 1 (Read):** **Azure AI Language** service. Concepts: Sentiment Analysis, Key Phrase Extraction, Entity Recognition (NER).  
* **Hour 2 (Deep Dive):** **Question Answering (QA)** and Conversational Language Understanding (CLU). Understand how bots interpret "intent" (what the user wants).  
* **Hour 3 (Lab):** Visit [Language Studio](https://language.cognitive.azure.com/). Try the "Analyze Sentiment" demo with different sentences.  
* **Hour 4 (Quiz):** Focus on scenarios: "A hotel wants to analyze reviews" $\\to$ Sentiment Analysis.  
* **Link:** [Get started with NLP](https://learn.microsoft.com/en-us/training/modules/get-started-language-azure/)

#### **Day 6: NLP \- Speech & Translation**

* **Hour 1 (Read):** **Azure AI Speech**. Speech-to-Text (STT) and Text-to-Speech (TTS). Real-time vs. Batch transcription.  
* **Hour 2 (Read):** **Azure AI Translator**. Text translation and Document translation (keeping formatting).  
* **Hour 3 (Video):** Watch a demo of "Azure AI Speech Studio" creating a custom voice or transcribing audio.  
* **Hour 4 (Review):** Consolidate all NLP services. Make a cheat sheet mapping "Service Name" to "Capability".

### ---

**Phase 3: Generative AI & Exam Polish (Days 7-10)**

#### **Day 7: Generative AI Concepts (20-25%) \- *Crucial Day***

* **Hour 1 (Read):** What are LLMs (Large Language Models)? How do they predict the next token?  
* **Hour 2 (Deep Dive):** **Prompt Engineering**. Techniques: Zero-shot, Few-shot, Chain-of-thought. Understand "Grounding" (using your own data to stop hallucinations).  
* **Hour 3 (Read):** **Copilots**. Understand the ecosystem: GitHub Copilot (Code), M365 Copilot (Docs/Email), Security Copilot.  
* **Hour 4 (Quiz):** Focus on GenAI vocabulary: Token, Temperature, Prompt, Completion.  
* **Link:** [Introduction to generative AI](https://learn.microsoft.com/en-us/training/modules/fundamentals-generative-ai/)

#### **Day 8: Azure AI Foundry & Responsible GenAI**

* **Hour 1 (Read):** **Azure AI Foundry**. This is the *new* big topic. Understand it is the "Unified Platform" for building AI apps.  
* **Hour 2 (Deep Dive):** **Model Catalog**. Know that this is where you find GPT-4, Llama, Mistral, etc.  
* **Hour 3 (Read):** **Azure AI Content Safety**. How to filter harmful inputs (jailbreaks) and outputs (hate speech).  
* **Hour 4 (Quiz):** Scenarios involving safety: "How do we prevent the bot from swearing?" $\\to$ Content Safety filters.

#### **Day 9: Full Practice Mode**

* **Hour 1:** Take the [Official Microsoft Practice Assessment](https://www.google.com/search?q=https://learn.microsoft.com/en-us/credentials/certifications/azure-ai-fundamentals/practice/assessment?assessment-type%3Dpractice%26assessmentId%3D26). Do it in "Exam Mode" (timed).  
* **Hour 2:** Review every wrong answer. Don't just read the right answer; find out *why* the other 3 were wrong.  
* **Hour 3:** Target your weakest area. (Usually GenAI or specific Vision services). Re-read that module.  
* **Hour 4:** Take the practice assessment again. Aim for 80%+.

#### **Day 10: Final Polish**

* **Hour 1:** Review your "Cheat Sheet" of service names. (Vision vs Face, Language vs Speech).  
* **Hour 2:** Review the 6 Responsible AI principles again (they are easy points if you know them).  
* **Hour 3:** "Azure AI Foundry" vocabulary check. Ensure you aren't using old terms like "Bot Framework Composer" (mostly deprecated/legacy).  
* **Hour 4:** Relax, hydrate, and prepare your testing environment (if taking online) or bag (if going to a center).