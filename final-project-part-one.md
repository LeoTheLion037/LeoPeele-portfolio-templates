| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |




# Outline
For my final project, I would like to explore phishing scams. My presentation will focus on how phishing messages have changed over time, and which messages have yielded the best or worst results depending on who you ask. My background is primarily in software development, but I think phishing scams are interesting and I have some familiarity from previous projects I have done in this realm (hackathon project & data analysis on malicious URLs). 

We have all received phishing emails, and many of them. We have probably all received voice phishing, text phishing, and even more types of spam. We have a lot of technology that can help filter out spam or nip phishing in the bud, but unfortunately there is still a lot that gets through, and phishing scam tactics have evolved over time. Not too long ago the stereotypical phishing email had to do with a Nigerian Price seeking to distribute wealth rife with spelling errors, but has evolved into sneakier notifications telling you a non existent package has been lost or that you received a non existent ticket. I think a lot of people are overconfident in their ability to spot scam emails, and I want to highlight how a lot of recommendations from years past don't really hold up anymore. I'm interested in showing the evolution of scam messages, how it may mirror current events (pandemic, AI technology, etc.) and how success rates of scamming have changed or stayed the same.

# Project Structure
Phishing emails are everywhere and have been everywhere for a while

How did phishing email scams start, how successful were they?

Which current events or technological changes evolved different types of phishing mediums and messages?

What does phishing look like today?

Has anything significant changed in the last 20 years in regard to phishing?

Call to action, what you can do to protect yourself and protect others


## Initial sketches

[Final Project Early Sketch.pdf](https://github.com/user-attachments/files/32633944/Final.Project.Early.Sketch.pdf)


# The data

For my data sources, I will be pulling from several reports and online datasets containing instances of phishing emails and overall statistics for suspicious email flagging. I will start with this kaggle phishing dataset[1], which includes several compiled phishing email databases. I will filter for instances which include a subject line and message body and timestamp. I will then compare this to the Zenodo phishing email dataset, and filter out duplicate entries (same sender, receiver, and timestamp). These datasets will help give me an idea of the evolution of message types over time.

From these datasets, I will move into my second phase which is success rate of different phishing emails. This step gets tricky because there are some potential privacy concerns with analyzing this data. To circumvent this, I will be looking over several reports, including the knowbe4 annual benchmarking phishing report by industry(3). I will combine this with reports from Pistachio (4) and  proofpoint (5) for different angles and measures. 

# Method and medium
I am planning on using Tableau for my project. I feel like it offers the most potential for visualizations, and I have gotten more and more comfortable with it throughout this course.


## References
[1] Kaggle Phishing Dataset, https://www.kaggle.com/datasets/naserabdullahalam/phishing-email-dataset

[2] Zenodo Phishing Email Curated Datasets, https://zenodo.org/records/8339691
A. I. Champa, M. F. Rabbi, and M. F. Zibran, “Why phishing emails escape detection: A closer look at the failure points,” in 12th Interna- tional Symposium on Digital Forensics and Security (ISDFS), 2024, pp. 1–6.
A. I. Champa, M. F. Rabbi, and M. F. Zibran, “Curated datasets and feature analysis for phishing email detection with machine learning,” in 3rd IEEE International Conference on Computing and Machine Intelligence (ICMI), 2024, pp. 1–7.

[3] Kowbe4 Report, https://www.knowbe4.com/resources/reports/phishing-by-industry-benchmarking-report

[4] Pistachio Report, https://pistachioapp.com/blog/click-rate-isnt-enough-to-measure-phishing-resilience

[5] ProofPoint Report, https://www.proofpoint.com/us/products/security-awareness-training/phishing-simulations

## AI acknowledgements
I did not use AI for this assignment, although I may use it further down to assist with technical challenges of using Tableau. Additionally, I did indirectly use AI when performing google searches as the AI overview is now built into search engines.
