# Ibaloi NLP Lexicon System: Preserving Ibaloi through Neural Processing

**A digital platform designed to support the preservation, study, and modernization of the Ibaloi language through Natural Language Processing (NLP).**

## 🔗 Quick Links
* **Live Website:** [https://ibaloinlp.vercel.app/](https://ibaloinlp.vercel.app/)
* **Repository:** [https://github.com/nlp-mors3/Morse_RASA](https://github.com/nlp-mors3/Morse_RASA)

---

## 📖 About the Project

[cite_start]The Cordillera Administrative Region (CAR) is home to rich ethnolinguistic groups, yet languages like **Ibaloi** remain underrepresented in modern technological applications[cite: 179, 182]. [cite_start]While traditional dictionaries exist, they often lack the structure required for computational processing[cite: 192].

**The Ibaloi NLP Lexicon System** bridges this gap. [cite_start]It is an academic initiative designed to create a structured, machine-readable lexicon dataset compatible with NLP processes[cite: 27, 184]. [cite_start]The system aims to support future applications such as machine translation, chatbots, and digital cultural preservation[cite: 185].

### Key Objectives
* [cite_start]**Construct a Digital Lexicon:** A structured database of Ibaloi vocabulary with English translations, POS tagging, and phonetic respelling[cite: 196, 197].
* [cite_start]**Crowdsource Language Data:** Utilize a "Sentence Builder" to gather authentic sentence examples from the community[cite: 34].
* [cite_start]**Demonstrate NLP Capabilities:** Implement a **RASA-based** translation tool that combines lexicon matching with generative AI context injection[cite: 35, 143].

---

## 🚀 Key Features

### 1. Digital Lexicon
A searchable database containing over **1,500+ entries**. It serves as the core linguistic resource for the project.
* [cite_start]**Structured Data:** Includes variants, simplified pronunciation (adapted from Google/Oxford conventions), part of speech (POS), and synonyms [cite: 91-98, 224].
* [cite_start]**Search Interface:** Allows users to filter by Ibaloi word, English translation, or spelling variants[cite: 89].

### 2. Sentence Builder (Crowdsourcing Tool)
[cite_start]To address the scarcity of digital Ibaloi resources, we developed a custom data collection module[cite: 227].
* [cite_start]**Workflow:** Users select a "Main Word" provided by our API and construct an Ibaloi sentence around it, providing an English translation [cite: 122-125, 232-234].
* [cite_start]**Backend:** Data is processed via a Node.js API and stored in a structured sheet for validation[cite: 228, 236].

### 3. RASA Translator (Hybrid Neural Translation)
A demonstration of low-resource language modeling using a hybrid approach.
* [cite_start]**Lexicon Matching:** Identifies and highlights known terms from the database[cite: 135].
* [cite_start]**Context Injection:** Uses a Generative AI / RASA pipeline to infer context and generate sentence predictions even when exact matches are missing[cite: 143].
* [cite_start]**Bidirectional:** Supports both English-to-Ibaloi and Ibaloi-to-English translation[cite: 131].

### 4. Research Paper Viewer
[cite_start]An integrated document viewer that presents our full study, *"Constructing a Structured Ibaloi Lexicon through Digital Resource Collection,"* making the methodology accessible to all users[cite: 115].

---

## 🛠️ Technology Stack

* [cite_start]**Frontend:** HTML, CSS, JavaScript [cite: 228]
* [cite_start]**Backend/API:** Node.js, JSON handling [cite: 228, 233]
* [cite_start]**NLP Framework:** RASA, Gemini 2.5 Open Source Framework (referenced in UI) [cite: 63, 67]
* [cite_start]**Deployment:** Vercel [cite: 230]

---

## 🔮 Message to Future Researchers & Contributors

To the students, developers, and linguists who may inherit or fork this repository:

**This project is a starting point, not a finish line.**
We created this system because we recognized that Ibaloi was falling behind in the digital age due to a lack of machine-readable datasets. We have laid the groundwork by scraping dictionaries, standardizing orthography, and building the initial collection infrastructure.

**Where you can take this next:**
1.  **Expand the Dataset:** The *Sentence Builder* is fully functional. Use it to launch wider community campaigns to gather more complex sentence structures. The more data you collect, the better the model becomes.
2.  **Refine the Model:** Our RASA implementation uses a hybrid approach. Future work could focus on fine-tuning specific Large Language Models (LLMs) specifically on the Ibaloi dataset we've started.
3.  **Audio Integration:** We structured the lexicon with pronunciation guides. [cite_start]A logical next step is integrating Text-to-Speech (TTS) or Speech-to-Text (STT) to support oral preservation[cite: 185].

Please treat the data with respect to the culture it represents. [cite_start]Ensure that any major changes to orthography align with the *DepEd Ibaloi Orthography* standards we followed[cite: 203].

*Agmapteng! (Padayon!)*

---

## 👥 The Team (NLP Team Mors3)

[cite_start]**Saint Louis University** - School of Computing and Information Sciences [cite: 152]

* **Alcazar, Xymond Louisse**
* **Lucban, Prince John Louie**
* **Collo, John Henrich**
* **Navarro, Josiah Ezra**
* **Yuen, Ka Hang Christian**
* **Lachica, Rafael**
* **Olanos, Cheni Lei**

---

*© 2025 NLP Team Mors3. [cite_start]All rights reserved.* [cite: 85]
