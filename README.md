<img width="1536" height="1024" alt="spam-detector-overview" src="https://github.com/user-attachments/assets/6ba92e1e-ddc4-4d4a-95f8-8e0ad88e5ff8" /># Email Spam Detection with Machine Learning


![Overview]()

---

## What’s the Problem?

Spam emails aren’t just annoying — they’re often dangerous. From phishing links to fraud schemes, they clutter inboxes and trick users. This project tackles that problem head-on by building a machine learning model that can spot spam automatically and filter it out before it causes trouble.

---

## What This Project Covers

1. **Cleaning the Data:** We start by scrubbing the dataset — removing noise, handling missing fields, and shaping raw email text into usable inputs.

2. **Feature Engineering:** Instead of using emails as-is, we break them down: sender info, subject keywords, body content — everything that helps spot patterns typical of spam.

3. **Choosing the Right Models:** We experiment with several ML models — from decision trees and support vector machines to Naive Bayes — to see which one performs best.

4. **How We Measure Success:** It’s not just about accuracy. We look at precision, recall, F1 score, and ROC-AUC to understand how well the model distinguishes spam from legit emails.

5. **Tuning the Model:** We fine-tune hyperparameters to reduce false positives and increase reliability.

6. **Making It Reliable:** Cross-validation ensures our model isn’t just memorizing the dataset — it’s actually learning and generalizing to unseen emails.

7. **Real-World Use:** We explore how this model could plug into existing email systems to quietly filter spam in the background.

8. **Privacy First:** We’re mindful of data privacy and only use email content in a secure, anonymized way.

9. **What’s Next:** We acknowledge spam tactics evolve constantly. Future improvements could include real-time learning and hybrid models.

---

## Project in Action

This project builds a spam filter powered by machine learning. It learns from patterns in the data — like common trigger words or suspicious formatting — and flags likely spam. Here’s what we did:

- **Processed the Raw Data**: Converted unstructured emails into machine-readable inputs.
- **Extracted Useful Signals**: Pulled out important cues from headers, subjects, and message bodies.
- **Trained and Evaluated Models**: Tried multiple approaches and validated them using strong metrics.
- **Fine-Tuned Everything**: Adjusted model settings to get the best performance.
- **Tested for Generalization**: Ensured the model performs well even on new, unseen data.
- **Explored Deployment Paths**: Considered real-life applications in email services or browser plugins.

---

## Final Results

- About **13.41%** of messages in our dataset were spam — a meaningful chunk that needs filtering.
- Common spam keywords included **"free"**, **"call"**, **"txt"**, and **"now"** — strong signals during analysis.
- The **Multinomial Naive Bayes** model stood out, achieving a **recall of 98.49%** — making it highly reliable at catching spam without letting much slip through.

This solution proves how well-chosen features, smart model selection, and solid validation techniques can lead to real, usable tools that make digital communication safer.

---

## Author

- **Ojas Kumar Singh**
