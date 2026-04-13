## 🛠️ Data Processing & Methodology

To ensure the research was both statistically representative and qualitatively rich, a multi-stage pipeline was developed to move from raw data to actionable insights.

### 1. Data Cleaning & Pre-processing
The initial Kaggle dataset contained **31,739 reviews**. The following cleaning steps were applied to isolate relevant discourse:

* **Missing Value Handling:** Executed a listwise deletion of all rows containing **null** review content to maintain dataset integrity.
* **Feature Selection:** Dropped non-essential metadata columns (`type`, `post_id`, `title`, `url`, `body`, `comment_text`) to focus exclusively on user-generated text and star ratings.
* **Keyword Filtering:** Isolated anxiety-specific interactions by filtering for the tokens **"anxious"** and **"anxiety"**. This reduced noise from general chatbot use-cases (e.g., productivity or entertainment).
* **Deduplication:** Identified and removed duplicate entries to prevent the over-representation of cross-posted reviews or bot-generated noise.

> [!NOTE]
> Following pre-processing, the "Anxiety-Specific" sub-population totaled **$N=680$** reviews.

---

### 2. Sampling Strategy
To make manual qualitative coding feasible while maintaining the "voice" of the larger dataset, a **Stratified Random Sample** ($n=200$) was extracted:

* **Proportional Allocation:** To avoid bias, the sample was stratified by star rating (1–5). The number of reviews drawn from each stratum was proportional to its size in the $N=680$ pool.
    * *Logic:* $n_{h} = (N_{h} / N) \times n$
* **Randomization:** Each review was assigned a random decimal using a `=RAND()` generator in Excel, ensuring every eligible review had an equal probability of selection.

---

### 3. Qualitative Coding Framework
The sample underwent a rigorous two-stage manual analysis to move beyond surface-level sentiment.

#### **Stage 1: Insight Stratification**
Reviews were screened for "Insight Depth" to ensure the analysis focused on functional feedback rather than vague praise or complaints.
* **High Insight ($n=119$):** Reviews detailing *specific* interactions, app features, or emotional outcomes.
* **Low Insight:** Non-descriptive sentiment (e.g., "Good app," "I hate this").

#### **Stage 2: Thematic Coding**
The **10-Point Functional/Friction Framework** was applied to the high-insight subset. This involved mapping user text to specific Theme IDs (e.g., *Paywall Friction* vs. *Companionship*) to identify the mechanical drivers of user satisfaction.

---

### 4. Synthesis & Visualization
* **Quantitative Analysis:** Pivot tables were used to cross-reference Theme IDs against Star Ratings, revealing which app behaviors triggered specific rating outcomes.
* **Data Visualization:** Frequency distributions and app-level comparisons (Wysa vs. Replika) were generated to highlight the "Hero" vs. "Villain" features of the user experience.
