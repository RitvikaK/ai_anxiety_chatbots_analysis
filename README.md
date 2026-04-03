# 🧠 AI Chatbot Analysis: Navigating Anxiety Support

An investigation into how conversational AI tools support or hinder users experiencing anxiety. This project analyzes **31,739 reviews** to isolate the functional mechanics of digital mental health support.

## ❓ Research Question
> **How do AI conversational tools support or hinder users experiencing anxiety?**

---

## 📊 Dataset & Scope
* **Source:** Kaggle Chatbot Reviews Dataset
* **Population ($N=31,739$):** Total raw reviews.
* **Filtered Subset ($n=680$):** Anxiety-specific interactions.
* **Qualitative Sample ($n=119$):** High-insight reviews selected via stratified random sampling.

**Primary Apps Analyzed:** * 🦉 **Wysa** (Purpose-built mental health)
* 🤖 **Replika** (General companionship)
* 🩺 **Woebot / Youper** (Clinical-lite)

---

## 🛠️ Deep Dives
* [**Full Methodology**](methodology) – *Data cleaning, sampling logic, and RAND() implementation.*
* [**Thematic Codebook**](methodology/thematic_coding_framework.md) – *The 10-point framework used to categorize user friction and value.*

---

## ⚡ Key Insights

### 💥 1. Empathy Over Algorithm
Users prioritize **Companionship (Theme 8)** and "feeling heard" over technical accuracy. High ratings (4–5★) are driven by the *emotional experience* rather than the AI's advanced capabilities.

### 💥 2. Niche Design Drives Satisfaction
Wysa leads with predominantly 5-star ratings because its design is closely aligned with anxiety use-cases. In contrast, **Replika** shows a dramatic rating drop when filtered for anxiety, indicating that general-purpose AI often fails to meet the specific needs of vulnerable users.

### 💥 3. Value Outweighs Friction
Users frequently award Wysa 5 stars even when noting **Repetition (Theme 3)** or **Misunderstanding (Theme 2)**. This suggests that the immediate relief provided by the tool outweighs minor technical frustrations.

### 💥 4. Failure Modes are App-Specific
Negative experiences are not uniform. While **Youper** struggles with **Paywall Friction (Theme 1)**, **Replika** is more frequently flagged for **Intrusive Behavior (Theme 4)** and **Trust/Safety Concerns (Theme 5)**.

---

## ⚠️ Limitations
* **Dataset Skew:** Heavily weighted toward Wysa and Replika.
* **Subjectivity:** Manual thematic coding involves researcher interpretation.
* **Sample Size:** Qualitative analysis is limited to $n=119$ high-insight reviews.

---

## 🚀 Future Work
* Implement **NLP/LLM-based classification** to scale the analysis.
* Include social media discourse (Reddit/Twitter) for broader context.
* Expand keyword filtering beyond "anxiety" to include "panic," "dread," and "overwhelmed."
