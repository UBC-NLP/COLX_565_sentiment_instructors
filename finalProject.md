# Final Project: Sentiment Analysis in the Real World  

## Overview  
This **group project** (4 students per team) will challenge you to develop a sentiment analysis system that addresses a **real-world problem** using the methods covered in this course. You will not only build a sentiment classifier but also engage in **data collection, labeling, analysis, model explanation, and ethical evaluation**.  

### **Key Goals of This Project:**  
✔ Apply **sentiment analysis techniques** to real-world text data.  
✔ Design **custom datasets**, requiring hands-on **data labeling**.  
✔ Develop **explainable models**—not just high accuracy but **interpretable** results.  
✔ Address **societal and ethical issues** such as **bias, multilingual challenges, and domain adaptation**.  
✔ Avoid **over-reliance on AI automation** by incorporating human-driven insights.  

---

## **Project Phases & Milestones (66% of Course Grade)**  

| Milestone       | Weight  | Due Date         | Submission Format |
|----------------|---------|------------------|-------------------|
| **Milestone 1: Dataset, Task Definition, and Baseline Models**  | 30% | TBA (Mid-March) | GitHub + Report |
| **Milestone 2: Final System, Evaluation, and Explainability**   | 36% | TBA (End of Term) | GitHub + Report + Presentation |

---

## **Project Structure & Requirements**  

### **📌 Milestone 1: Dataset, Task Definition, and Baseline Models (30%)**  
In this phase, your team will:  

1. **Define a Sentiment Analysis Task (5%)**  
   - Choose a real-world problem that involves sentiment analysis. Some possible options include:  
     - **Consumer Feedback:** Analyze sentiment in product reviews from a specific domain (e.g., healthcare, tech, books, fashion).  
     - **Financial Sentiment:** Examine sentiment in stock market discussions.  
     - **Political/Public Sentiment:** Study sentiment shifts in tweets or news articles around political events.  
     - **Social Justice Issues:** Investigate sentiment surrounding topics like climate change, gender equality, or online hate speech.  
     - **Multilingual Sentiment:** Analyze sentiment in a non-English dataset (e.g., Arabic, Spanish, Chinese).  

2. **Collect & Curate a Dataset (10%)**  
   - Each team **must build its own dataset**. This means **no direct use of pre-labeled datasets** (e.g., IMDb, SST).  
   - Data must be sourced from APIs, web scraping (if ethical/legal), or provided corpora.  
   - **Minimum dataset size:** 2,000-5,000 text samples.  
   - At least **20% of the dataset must be manually labeled** by the team.  
   - Describe the **dataset characteristics** (e.g., domain, language, challenges in labeling).  

3. **Implement Baseline Models (10%)**  
   - Train a **basic sentiment classifier** using classical machine learning (e.g., Logistic Regression, Naïve Bayes, SVM).  
   - Train an **off-the-shelf transformer-based model** (e.g., BERT).  
   - Compare **performance, interpretability, and limitations** of both approaches.  

4. **Submit a Report (5%)**  
   - Provide a **structured report (3-4 pages)** detailing:  
     - **Task Definition** (problem statement, relevance).  
     - **Dataset Description** (size, sources, labeling process).  
     - **Initial Model Experiments** (performance comparison).  
     - **Challenges Faced** (data collection, annotation).  

✅ **Submission:** Upload dataset, models, and report to GitHub.  

---

### **📌 Milestone 2: Final System, Evaluation, and Explainability (36%)**  
In this phase, your team will:  

1. **Develop an Improved Sentiment Model (10%)**  
   - Apply **advanced techniques** such as:  
     - **Fine-tuning a transformer-based model** (e.g., BERT, RoBERTa, GPT-based classifiers).  
     - **Instruction fine-tuning** for better generalization.  
     - **Prompt engineering & Chain-of-Thought (CoT) reasoning** (if using LLMs).  
     - **Multilingual adaptation** (if applicable).  
   - Compare the new model’s **performance vs. baseline models**.  

2. **Explainability & Interpretability (8%)**  
   - Apply explainability tools (e.g., SHAP, LIME, attention visualization).  
   - Provide **case studies** showing **why** the model makes certain predictions.  
   - Discuss **common failure cases** and their implications.  

3. **Bias, Ethics, and Societal Impact Analysis (8%)**  
   - Conduct an **ethics analysis** covering:  
     - **Bias in dataset or models** (e.g., does the model amplify certain perspectives?).  
     - **Fairness across demographics** (e.g., differences in sentiment classification for different groups).  
     - **Potential misuse scenarios** (e.g., sentiment-based filtering of speech).  

4. **Final Report (5%)**  
   - Structured report (5-6 pages) covering:  
     - **Refined Model Performance** (quantitative & qualitative evaluation).  
     - **Explainability & Interpretability Analysis**.  
     - **Bias & Societal Impact Discussion**.  
     - **Final Reflections** on learnings and project evolution.  

5. **Final Presentation (5%)**  
   - **15-minute in-class presentation**  
   - Present key findings, model comparison, and ethical considerations.  
   - **Live demo of sentiment classifier** (if applicable).  

✅ **Submission:** Upload model, code, report, and presentation slides to GitHub.  

---

## **Evaluation Rubric**  

| Criteria | Excellent (100%) | Satisfactory (80%) | Needs Improvement (60%) | Poor (40% or below) |
|----------|------------------|--------------------|-------------------------|----------------------|
| **Dataset Quality (10%)** | Large, well-annotated dataset with strong rationale. | Adequate dataset but lacks depth in annotation. | Limited dataset with minimal effort in labeling. | Poor dataset, mostly pre-labeled. |
| **Baseline Models (10%)** | Strong implementation with clear comparisons. | Models implemented but comparison lacks depth. | Weak implementation, missing comparisons. | Poor or missing baseline models. |
| **Advanced Model (10%)** | Well-trained and fine-tuned, strong evaluation. | Model trained, but minimal optimization. | Basic implementation, lacks experimentation. | Model missing or poorly implemented. |
| **Explainability (8%)** | High-quality interpretability analysis. | Some interpretability analysis but lacks depth. | Minimal discussion of model explanation. | No model explainability provided. |
| **Bias & Ethics (8%)** | Thoughtful, deep analysis of societal impact. | Discusses bias but lacks detailed insights. | Minimal ethical discussion. | No ethics or bias analysis. |
| **Final Report (5%)** | Clear, structured, high-quality report. | Report complete but lacks strong analysis. | Basic report, missing key insights. | Report missing or poorly written. |
| **Presentation (5%)** | Engaging, well-structured, strong demo. | Clear but missing depth in some areas. | Basic slides, unclear discussion. | Poor presentation or missing demo. |

---

## **Final Notes**
- 📌 **AI Automation Policy:** Using AI for **automation of analysis without critical engagement** (e.g., blindly applying ChatGPT for model training, auto-labeling datasets) **will be penalized**.  
- 📌 **Collaboration Policy:** All contributions must be **documented in GitHub** with commit history.  

---
