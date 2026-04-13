# 📊 Index of Results

This directory contains the multi-level analysis of AI Mental Health Chatbot reviews, moving from broad quantitative distributions to granular qualitative insights.

---

### 📂 1. Data Pipeline
* [**1. Data Pipeline**](/1_Data_Funnel/1_Data_Pipeline.md)  
  *Visualising the filtering process from the original Kaggle dataset (N=31,739) to the high-insight categorised sample (N=119).*

### 📂 2. Quantitative Analysis
* [**2.1 Original Dataset**](/2_Quantitative_Analysis/2.1_Original_Dataset.md)  
  *Baseline distribution of all reviews across Replika, Wysa, Woebot, and Youper.*
* [**2.2 Filtered Subset: Anxiety Mentions**](/2_Quantitative_Analysis/2.2_Filtered_dataset.md)  
  *Breakdown of the 680 reviews specifically mentioning "anxiety" or "anxious."*
* [**2.3 Categorised Final Dataset**](/2_Quantitative_Analysis/2.3_Categorised_final_dataset.md)  
  *Distribution of the final dataset which has been categorised."*

### 📂 3. Qualitative Deep-Dive
* [**3.1.1 Thematic Prevalence**](/3_Qualitative_Deep_Dive/3.1.1_Thematic_prevalence.md)  
  *The total volume of conversation across all identified theme mentions (N=144).*
* [**3.1.2 Categorical Distribution**](/3_Qualitative_Deep_Dive/3.1.2_Categorical_distribution.md)  
  *A granular codebook mapping specific user feedback categories to overarching themes (N=180).*
* [**3.2 Dominant Theme by Rating**](/3_Qualitative_Deep_Dive/3.2_Dominant_Theme_by_Rating.md)  
  *Correlation between user sentiment and the primary psychological driver of the review (N=119).*
* [**3.3 Thematic Distribution by App**](/3_Qualitative_Deep_Dive/3.3_Thematic_Distribution_by_App.md)  
  *Comparison of user experiences and complaints across different platforms (N=144).*

---

### 💡 Methodology Note: Understanding Sample Sizes (N)

You may notice that the total counts vary between tables. This is a deliberate reflection of the multi-layered nature of qualitative coding:

1. **The Unique User Count (N=119):** This represents the number of individual high-insight reviews analyzed. This count is used when determining the **Dominant Theme** (Table 3.2).
2. **The Thematic Mentions (N=144):** Many users touched upon multiple distinct themes (e.g., praising **Companionship** while reporting **Technical Issues**). We tracked every mention to capture the full breadth of the user experience.
3. **The Categorical Granularity (N=180):** At the most granular level, a single theme (like **Functional Support**) may be comprised of multiple sub-categories (like **Breathing Exercises** and **Meditation**). 

This approach ensures that while we respect the individual user's primary sentiment, we do not erase the complexity of their feedback.
